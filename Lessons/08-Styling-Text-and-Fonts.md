# Lesson 8: Styling Text and Fonts

## Changing Font Styles, Sizes, and Colors

CSS allows you to style text in various ways, making your web pages visually appealing and easy to read. Here are some common CSS properties used to style text:

### Font Style

The `font-style` property is used to make text italic or oblique.

- **Example**:
  ```css
  p {
      font-style: italic;
  }
  ```

### Font Size

The `font-size` property sets the size of the text. You can use units like pixels (`px`), ems (`em`), or percentages (`%`).

- **Example**:
  ```css
  h1 {
      font-size: 24px;
  }
  ```

### Font Color

The `color` property sets the color of the text. You can use color names, hexadecimal values, or RGB values.

- **Example**:
  ```css
  a {
      color: #ff6347; /* Tomato color */
  }
  ```

### Font Weight

The `font-weight` property sets the thickness of the text. Common values are `normal`, `bold`, or numerical values like `400`, `700`.

- **Example**:
  ```css
  strong {
      font-weight: bold;
  }
  ```

### Example CSS for Text Styling

```css
body {
    font-family: Arial, sans-serif;
    font-size: 16px;
    color: #333;
}

h1 {
    font-size: 32px;
    font-weight: bold;
    color: #0056b3;
}

p {
    font-size: 14px;
    line-height: 1.6;
    color: #666;
}
```

## Using Google Fonts

Google Fonts is a library of free, open-source fonts that you can use on your web pages. Here's how to incorporate Google Fonts into your project:

### Selecting a Font

1. **Visit Google Fonts**: Go to [Google Fonts](https://fonts.google.com) and browse the available fonts.
2. **Choose a Font**: Click on a font to view its details and click the "Select this style" button to choose the styles you want.

### Adding Google Fonts to Your Project

1. **Copy the Link**: After selecting a font, Google Fonts provides a `<link>` tag to include in your HTML document. For example:
   ```html
   <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">
   ```

2. **Include in HTML**: Add the `<link>` tag inside the `<head>` section of your HTML file.

   ```html
   <head>
       <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">
   </head>
   ```

3. **Apply the Font in CSS**: Use the `font-family` property to apply the Google Font to your elements.

   ```css
   body {
       font-family: 'Open Sans', sans-serif;
   }
   ```

### Example of Using Google Fonts

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            font-size: 16px;
            color: #333;
        }
        h1 {
            font-size: 28px;
            font-weight: 700;
            color: #0056b3;
        }
    </style>
    <title>Styling Text with Google Fonts</title>
</head>
<body>
    <h1>Welcome to My Web Page</h1>
    <p>This is a sample paragraph styled with Google Fonts.</p>
</body>
</html>
```

By understanding how to style text and use Google Fonts, you can enhance the typography of your web pages, making them more attractive and readable.

---

This lesson provides a foundational understanding of styling text and fonts in CSS, preparing you for more advanced design techniques.

[Next: 09-Box-Model-and-Layout](./09-Box-Model-and-Layout.md)