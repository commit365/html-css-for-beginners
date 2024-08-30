# Lesson 2: What is CSS?

## Overview of CSS

CSS, or Cascading Style Sheets, is the language used to describe the presentation and layout of a web page. While HTML provides the structure and content, CSS is responsible for the visual styling, including colors, fonts, spacing, and layout. By separating the content from its presentation, CSS allows for more flexibility and control over the appearance of web pages.

### Key Features of CSS:
- **Selectors**: CSS uses selectors to target HTML elements. Selectors can be based on element type, class, ID, or other attributes.
- **Properties and Values**: CSS defines styles using properties and values. For example, `color: blue;` sets the text color to blue.
- **Cascading and Inheritance**: CSS rules can cascade, meaning that more specific rules can override general ones. Styles can also be inherited from parent elements.

## Understanding the Role of CSS in Styling Web Pages

CSS plays a crucial role in web development by enhancing the visual appeal and user experience of a website. It allows developers to create responsive, visually engaging, and consistent designs across different devices and screen sizes.

### Role of CSS:
- **Styling and Layout**: CSS controls the look and feel of a web page, including colors, fonts, margins, padding, and positioning.
- **Responsive Design**: CSS enables responsive design through media queries, allowing web pages to adapt to different screen sizes and devices.
- **Consistency and Reusability**: By using external stylesheets, CSS promotes consistency and reusability across multiple web pages.

### Example of a Simple CSS Stylesheet:

```css
/* Style for the body element */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 0;
}

/* Style for headings */
h1 {
    color: #333;
    text-align: center;
}

/* Style for paragraphs */
p {
    color: #666;
    line-height: 1.5;
    margin: 20px;
}
```

### Explanation of the Example:
- The `body` selector applies styles to the entire page, setting the font, background color, and removing default margins and padding.
- The `h1` selector targets all `<h1>` elements, setting the text color and alignment.
- The `p` selector targets all `<p>` elements, setting the text color, line height, and margin.

By using CSS, you can create visually appealing web pages that enhance the user experience and maintain a consistent look and feel across your site.

---

This lesson provides a foundational understanding of CSS, preparing you for more advanced styling techniques and responsive design concepts.

[Next: 03-Setting-Up-Your-Environment](./03-Setting-Up-Your-Environment.md)