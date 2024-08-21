# Lesson 13: CSS Grid

## Introduction to CSS Grid

CSS Grid is a powerful layout system that allows you to create complex, responsive web layouts with ease. Unlike Flexbox, which is primarily one-dimensional (either row or column), CSS Grid is two-dimensional, allowing you to work with both rows and columns simultaneously.

### Key Concepts of CSS Grid

- **Grid Container**: The parent element that holds grid items. It is defined by setting the `display` property to `grid` or `inline-grid`.

- **Grid Items**: The child elements within a grid container. These items are placed into the defined grid structure.

- **Grid Lines**: The dividing lines that separate the grid into cells.

- **Grid Tracks**: The rows and columns of the grid.

- **Grid Cells**: The individual spaces between grid lines.

### Basic Grid Properties

- **`display: grid;`**: Defines a grid container and enables grid layout for its children.

- **`grid-template-columns`**: Defines the columns of the grid.
  - Example: `grid-template-columns: 1fr 2fr;` creates two columns, with the second column being twice as wide as the first.

- **`grid-template-rows`**: Defines the rows of the grid.
  - Example: `grid-template-rows: 100px auto;` creates a fixed-height row and a row that takes up the remaining space.

- **`grid-gap`**: Sets the gap between grid items.
  - Example: `grid-gap: 10px;`

## Building Complex Layouts with Grid

CSS Grid allows you to create complex layouts by defining grid areas and placing items within those areas.

### Example CSS for a Grid Layout

```css
.container {
    display: grid;
    grid-template-columns: 1fr 2fr 1fr;
    grid-template-rows: auto 200px auto;
    grid-gap: 10px;
}

.header {
    grid-column: 1 / 4; /* Span all three columns */
    background-color: lightblue;
}

.sidebar {
    grid-column: 1 / 2;
    background-color: lightcoral;
}

.main {
    grid-column: 2 / 3;
    background-color: lightgreen;
}

.footer {
    grid-column: 1 / 4; /* Span all three columns */
    background-color: lightgoldenrodyellow;
}
```

### Explanation of the Example

- **`.container`**: The grid container defines a layout with three columns and three rows, with gaps between the grid items.

- **`.header`**: Spans all three columns, creating a full-width header.

- **`.sidebar`**: Occupies the first column, creating a sidebar.

- **`.main`**: Occupies the second column, creating the main content area.

- **`.footer`**: Spans all three columns, creating a full-width footer.

### Example HTML with Grid Layout

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .container {
            display: grid;
            grid-template-columns: 1fr 2fr 1fr;
            grid-template-rows: auto 200px auto;
            grid-gap: 10px;
        }

        .header {
            grid-column: 1 / 4; /* Span all three columns */
            background-color: lightblue;
            padding: 20px;
            text-align: center;
        }

        .sidebar {
            grid-column: 1 / 2;
            background-color: lightcoral;
            padding: 20px;
        }

        .main {
            grid-column: 2 / 3;
            background-color: lightgreen;
            padding: 20px;
        }

        .footer {
            grid-column: 1 / 4; /* Span all three columns */
            background-color: lightgoldenrodyellow;
            padding: 20px;
            text-align: center;
        }
    </style>
    <title>CSS Grid Layout</title>
</head>
<body>
    <div class="container">
        <div class="header">Header</div>
        <div class="sidebar">Sidebar</div>
        <div class="main">Main Content</div>
        <div class="footer">Footer</div>
    </div>
</body>
</html>
```

By understanding CSS Grid and its properties, you can create complex, responsive layouts that adapt seamlessly to different devices and screen sizes, providing a flexible and powerful tool for modern web design.

---

This lesson provides a foundational understanding of CSS Grid, preparing you to design intricate web layouts with precision and control.