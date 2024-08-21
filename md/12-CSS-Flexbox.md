# Lesson 12: CSS Flexbox

## Understanding the Flexbox Layout Model

Flexbox, or the Flexible Box Layout, is a CSS layout model designed to provide a more efficient way to arrange items within a container. It is particularly useful for creating responsive layouts that adapt to different screen sizes and orientations.

### Key Concepts of Flexbox

- **Flex Container**: The parent element that holds flex items. It is defined by setting the `display` property to `flex` or `inline-flex`.

- **Flex Items**: The child elements within a flex container. These items are automatically arranged based on the container's properties.

- **Main Axis and Cross Axis**: Flexbox operates on two axes:
  - **Main Axis**: The primary axis along which flex items are laid out. It can be horizontal or vertical, depending on the `flex-direction`.
  - **Cross Axis**: The axis perpendicular to the main axis.

### Basic Flexbox Properties

- **`display: flex;`**: Defines a flex container and enables flexbox layout for its children.

- **`flex-direction`**: Specifies the direction of the flex items.
  - Values: `row`, `row-reverse`, `column`, `column-reverse`.

- **`justify-content`**: Aligns flex items along the main axis.
  - Values: `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `space-evenly`.

- **`align-items`**: Aligns flex items along the cross axis.
  - Values: `flex-start`, `flex-end`, `center`, `baseline`, `stretch`.

- **`flex-wrap`**: Controls whether flex items should wrap onto multiple lines.
  - Values: `nowrap`, `wrap`, `wrap-reverse`.

## Creating Responsive Layouts with Flexbox

Flexbox makes it easy to create responsive layouts that adjust to different screen sizes. Here's an example of a responsive layout using Flexbox:

### Example CSS for a Flexbox Layout

```css
.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
}

.item {
    flex: 1 1 200px; /* Grow, shrink, and set base width */
    margin: 10px;
    padding: 20px;
    background-color: lightblue;
    text-align: center;
}
```

### Explanation of the Example

- **`.container`**: The flex container that holds the flex items. It uses `flex-wrap: wrap;` to allow items to wrap onto new lines as needed.

- **`.item`**: Each flex item has a flexible width (`flex: 1 1 200px;`), allowing it to grow and shrink based on the container's width, with a base width of 200px.

### Example HTML with Flexbox Layout

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: center;
        }

        .item {
            flex: 1 1 200px; /* Grow, shrink, and set base width */
            margin: 10px;
            padding: 20px;
            background-color: lightblue;
            text-align: center;
        }
    </style>
    <title>Responsive Flexbox Layout</title>
</head>
<body>
    <div class="container">
        <div class="item">Item 1</div>
        <div class="item">Item 2</div>
        <div class="item">Item 3</div>
        <div class="item">Item 4</div>
    </div>
</body>
</html>
```

By understanding the Flexbox layout model and using its properties, you can create flexible and responsive layouts that adapt seamlessly to different devices and screen sizes.

---

This lesson provides a foundational understanding of CSS Flexbox, preparing you to design modern, responsive web layouts with ease.