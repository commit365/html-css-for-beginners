# Lesson 5: Common HTML Elements

## Headings, Paragraphs, Links, Images, and Lists

HTML provides various elements to structure content on a web page. Here are some of the most common elements you'll use:

### Headings

Headings are used to define the structure and hierarchy of content. HTML provides six levels of headings, from `<h1>` (most important) to `<h6>` (least important).

- **Example**:
  ```html
  <h1>Main Heading</h1>
  <h2>Subheading</h2>
  <h3>Sub-subheading</h3>
  ```

### Paragraphs

Paragraphs are used to define blocks of text. The `<p>` element is used to create a paragraph.

- **Example**:
  ```html
  <p>This is a paragraph of text on my web page.</p>
  ```

### Links

Links, or hyperlinks, are used to navigate between web pages. The `<a>` element is used to create a link, with the `href` attribute specifying the destination URL.

- **Example**:
  ```html
  <a href="https://www.example.com">Visit Example</a>
  ```

### Images

Images are embedded using the `<img>` element. The `src` attribute specifies the image source, and the `alt` attribute provides alternative text for accessibility.

- **Example**:
  ```html
  <img src="image.jpg" alt="Description of the image">
  ```

### Lists

Lists are used to group related items. HTML provides two types of lists: ordered lists (`<ol>`) and unordered lists (`<ul>`), with list items defined using the `<li>` element.

- **Ordered List Example**:
  ```html
  <ol>
      <li>First item</li>
      <li>Second item</li>
      <li>Third item</li>
  </ol>
  ```

- **Unordered List Example**:
  ```html
  <ul>
      <li>First item</li>
      <li>Second item</li>
      <li>Third item</li>
  </ul>
  ```

## Semantic HTML

Semantic HTML elements provide meaning to the content, improving accessibility and SEO by clearly defining the structure of a web page. Here are some common semantic elements:

### Header

The `<header>` element represents the introductory content or a set of navigational links.

- **Example**:
  ```html
  <header>
      <h1>Website Title</h1>
      <nav>
          <a href="#home">Home</a>
          <a href="#about">About</a>
          <a href="#contact">Contact</a>
      </nav>
  </header>
  ```

### Footer

The `<footer>` element represents the footer of a document or section, typically containing information about the author, copyright, or links to related documents.

- **Example**:
  ```html
  <footer>
      <p>&copy; 2024 My Website</p>
  </footer>
  ```

### Article

The `<article>` element represents a self-contained piece of content, such as a blog post, news article, or forum post.

- **Example**:
  ```html
  <article>
      <h2>Article Title</h2>
      <p>This is the content of the article.</p>
  </article>
  ```

### Section

The `<section>` element represents a thematic grouping of content, typically with a heading.

- **Example**:
  ```html
  <section>
      <h2>Section Title</h2>
      <p>This is the content of the section.</p>
  </section>
  ```

By understanding and using these common HTML elements, you can create well-structured, accessible, and meaningful web pages that enhance the user experience and improve search engine optimization.

---

This lesson provides an overview of essential HTML elements, preparing you for more advanced web development concepts.