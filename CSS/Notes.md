# Notes for CSS

The anatomy of both methods does share common features. Notice how both syntaxes contain a declaration. Declarations are the core of CSS. They apply a style to the selected element. Here, the `<p>` element has been selected in both syntaxes and will be styled to display the text in blue.

Understanding that a declaration is used to style a selected element is key to learning how to style HTML documents with CSS! The terms below explain each of the labels in the diagram on the right.

## Ruleset Terms:

**Selector**—The beginning of the ruleset used to target the element that will be styled.

**Declaration Block**—The code in-between (and including) the curly braces ({ }) that contains the CSS declaration(s).

**Declaration**—The group name for a property and value pair that applies a style to the selected element.

**Property**—The first part of the declaration that signifies what visual characteristic of the element is to be modified.

**Value**—The second part of the declaration that signifies the value of the property.

## Inline Style Terms:

**Opening Tag**—The start of an HTML element. This is the element that will be styled.

**Attribute**—The style attribute is used to add CSS inline styles to an HTML element.

**Declaration**—The group name for a property and value pair that applies a style to the selected element.

**Property**—The first part of the declaration that signifies what visual characteristic of the element is to be modified.

**Value**—The second part of the declaration that signifies the value of the property.

## Classes and ID's

CSS can select HTML elements by their type, class, and ID. CSS classes and IDs have different purposes, which can affect which one you use to style HTML elements.

CSS classes are meant to be reused over many elements. By writing CSS classes, you can style elements in a variety of ways by mixing classes. For instance, imagine a page with two headlines. One headline needs to be bold and blue, and the other needs to be bold and green. Instead of writing separate CSS rules for each headline that repeat each other’s code, it’s better to write a .bold CSS rule, a .green CSS rule, and a .blue CSS rule. Then you can give one headline the bold green classes, and the other the bold blue classes.

While classes are meant to be used many times, an ID is meant to style only one element. As you’ll learn in the next exercise, IDs override the styles of types and classes. Since IDs override these styles, they should be used sparingly and only on elements that need to always appear the same.

## Specificity
Specificity is the order by which the browser decides which CSS styles will be displayed. A best practice in CSS is to style elements while using the lowest degree of specificity so that if an element needs a new style, it is easy to override.

IDs are the most specific selector in CSS, followed by classes, and finally, type. 

## Review
**Q: Which of the following best descibes the concept of CSS selector specificity?**

**A:** Refers to how a browser decides which stles to display when there are multiple styles defined that could apply to the same element.


**Q: What does the `<style>` HTML tag allow?**

**A:** Writing one of more CSS rules in CSS syntax inside an HTML file. 

**Q: The following HTML code attempts to change the color of the paragraph text, but fails to do so. Why?**
```
<p color="red">I am learning to code!</p>
```

**A:** The color attribute is invalid. It should be changed to style then set equal to color: red;
```
<p style="color: red;">I am learning to code!</p>
```

**Q: What is the correct syntaxto select an element inside another element?**

**A:** 
```
.main-list li {}
```

**Q: What is the correct syntax to style multiple, unrelated selectors?**

**A:**
```
.nav-menu,
p {

}
```