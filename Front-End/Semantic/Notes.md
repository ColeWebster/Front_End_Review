# Notes for Semantic HTML

**Accessibility**:</strong> Semantic HTML makes webpages accessible for mobile devices and for people with disabilities as well. This is because screen readers and browsers are able to interpret the code better.

**SEO:** It improves the website SEO, or Search Engine Optimization, which is the process of increasing the number of people that visit your webpage. With better SEO, search engines are better able to identify the content of your website and weight the most important content appropriately.

**Easy to understand**: Semantic HTML also makes the website’s source code easier to read for other web developers.

## Structural Elements

- **main**: Is used to encapsulate the dominant content within a webpage.

- **foot**: Contained to the bottom of the page. Usually contains information such as Contact, Copyright, Terms of use, Site map and References to top of page links.

- **articles**: Defines elements in a document, such as chapters, headings or any other area of the document.

- **section**:Handles content that can stand on its own such as articles, blogs, comments, magazines etc.

- **aside**: element is used to mark additional information that can enhance another element but isn’t required in order to understand the main content. This element can be used alongside other elements such as <em>article</em> or <em>section</em>. 

## Review
**Q: What's the difference between embed and video?**
<br>
A: video can only be used for video, while embed can be used for any type of media.
<br>
<br>
**Q: What is wrong with this code?**
```
<figcaption>
  <img src="sunset.jpg">
  <figure>Beautiful sunset</figure>
</figcaption>
```

A: The use of `<figure>` and `<figcaption>` needs to be reversed. `<figcaption>`  is used to insert text related to the content in the `<figure>` such as description.

**Q: Why is the `<div>` tag not semantic?**
<br>
A: It provides no context as to what the content is inside of the tag. 

**Q: Why is the code below incorrect?**
```
<audio src ="AudioFile.mp3" />
```

A: It is not a self closing tag and requires an opening and closing tag. 

**Q: Which code snippet is the correct way to rewrite this in Semantic HTML?**
```
<div id="header">
    <h1>Code</h1>
</div>
```
A: See Below:

```
<header>
    <h1>Code</h1>
</header>
```
<br>
