---
tags:
- HTML
---

HTML (HyperText Markup Language) is the stand ard markup language used to create web pages. It defines the structure of web content.

HTML documents are made up of a series of tags, which are words or abbreviations enclosed in angle brackets (`< >`). Tags typically come in pairs with an opening tag and a closing tag, and they wrap the content they affect. For example, `<p>This is a paragraph.</p>`, where `<p>` is the opening tag and `</p>` is the closing tag.

Examples of HTML tags include `<html>`, `<head>`, `<body>`, `<div>`, `<span>`, `<h1>`, `<a>`, `<img>`, and indeed, `<table>`.

An attribute, on the other hand, is additional information about a tag that you include inside the opening tag. Attributes come in name-value pairs, for example `src="image.jpg"`. Some attributes are universal and can be used with any tag, like `class` and `id`, but others are specific to certain tags. 

For instance, in the `<img src="image.jpg" alt="An image">` tag, `src` and `alt` are attributes. They provide more information about the image: `src` specifies the source of the image, and `alt` provides alternative text in case the image cannot be displayed.

In a table tag `<table border="1">`, `border` is an attribute that specifies the border thickness of the table.

So, to determine whether something in HTML is a tag or an attribute, look at where it's located. If it's in angle brackets and wraps content, it's a tag. If it's inside a tag and provides additional information about that tag, it's an attribute.

The very basic HTML document structure:

```HTML
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
  </body>
</html>
```
Here's what each TAGS does :
- `<!DOCTYPE html>`: This is the document type declaration and it tells the browser that this is an HTML5 document.
- `<html>`: This is the root element of an HTML page.
- `<head>`: This element contains meta-information about the HTML document, such as its title.
- `<title>`: This element specifies a title for the HTML document (which is shown in the browser's title bar or tab).
- `<body>`: This contains the content of the HTML document, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- `<h1>`: This is a heading element. The number indicates the level of the heading (1-6, with 1 being the highest and most important level).
- `<p>`: This is a paragraph element.

**LINKS**
[[2-HTML - Linking JS file to HTML]]
[[4-HTML attributes - basics]]
[[5-HTML tags - basic]]


how to use coloring style into div and spans tags inside html file in css
css body tags

css background image