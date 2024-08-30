# Lesson 4: HTML Structure

## Understanding the Basic Structure of an HTML Document

An HTML document is the foundation of a web page, providing the structure and content that browsers render. Understanding the basic structure of an HTML document is essential for creating well-organized and functional web pages.

### Basic Structure of an HTML Document

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>Welcome to My Web Page</h1>
    <p>This is a paragraph of text on my web page.</p>
</body>
</html>
```

### Explanation of the Structure:

- `<!DOCTYPE html>`: This declaration defines the document type and version of HTML. It ensures that the browser interprets the document as HTML5.

- `<html>`: The root element that encloses the entire HTML document.

- `<head>`: Contains metadata about the document, such as the title, character set, and links to stylesheets or scripts. This section is not visible on the web page.

- `<title>`: Sets the title of the web page, which appears in the browser tab.

- `<body>`: Contains the visible content of the web page, such as text, images, and links.

## Elements, Tags, and Attributes

### HTML Elements

An HTML element consists of a start tag, content, and an end tag. Elements define the structure and content of a web page.

- **Example**: `<h1>Welcome to My Web Page</h1>`
  - `<h1>` is the start tag.
  - `Welcome to My Web Page` is the content.
  - `</h1>` is the end tag.

### HTML Tags

Tags are the building blocks of HTML. They are enclosed in angle brackets and come in pairs: a start tag and an end tag.

- **Start Tag**: Marks the beginning of an element (e.g., `<p>`).
- **End Tag**: Marks the end of an element (e.g., `</p>`).

### HTML Attributes

Attributes provide additional information about an element. They are included within the start tag and consist of a name and a value.

- **Example**: `<img src="image.jpg" alt="Description">`
  - `src` is an attribute that specifies the image source.
  - `alt` is an attribute that provides alternative text for the image.

### Common HTML Elements

- **Headings**: `<h1>`, `<h2>`, `<h3>`, etc., used to define headings.
- **Paragraphs**: `<p>`, used to define paragraphs of text.
- **Links**: `<a href="url">`, used to create hyperlinks.
- **Images**: `<img src="image.jpg" alt="Description">`, used to embed images.

By understanding the basic structure of an HTML document and the concepts of elements, tags, and attributes, you can create well-structured and meaningful web pages that form the foundation for further styling and interactivity.

---

This lesson provides a foundational understanding of HTML structure, preparing you for more advanced topics in web development.

[Next: 05-Common-HTML-Elements](./05-Common-HTML-Elements.md)