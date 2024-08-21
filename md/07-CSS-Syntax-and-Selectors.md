# Lesson 7: CSS Syntax and Selectors

## Understanding CSS Syntax

CSS (Cascading Style Sheets) is used to style HTML elements on a web page. The basic syntax of CSS consists of selectors, properties, and values. A CSS rule set is made up of a selector and a declaration block.

### Basic CSS Syntax

```css
selector {
    property: value;
    property: value;
}
```

### Explanation of the Syntax:

- **Selector**: The selector targets the HTML elements you want to style.
- **Property**: The property is the aspect of the element you want to change, such as color, font-size, or margin.
- **Value**: The value specifies the setting for the property.

### Example

```css
p {
    color: blue;
    font-size: 16px;
}
```

- This rule set targets all `<p>` elements, setting their text color to blue and font size to 16 pixels.

## Types of Selectors

CSS selectors are used to "select" the HTML elements you want to style. There are several types of selectors, each serving a different purpose.

### Element Selector

The element selector targets all instances of a specified HTML element.

- **Example**:
  ```css
  h1 {
      color: red;
  }
  ```
  - This targets all `<h1>` elements, setting their text color to red.

### Class Selector

The class selector targets elements with a specific class attribute. Classes are reusable and can be applied to multiple elements.

- **Syntax**: `.classname`
- **Example**:
  ```css
  .highlight {
      background-color: yellow;
  }
  ```
  - This targets all elements with the class `highlight`, setting their background color to yellow.

- **HTML Example**:
  ```html
  <p class="highlight">This text is highlighted.</p>
  ```

### ID Selector

The ID selector targets a single element with a specific id attribute. IDs should be unique within a page.

- **Syntax**: `#idname`
- **Example**:
  ```css
  #header {
      background-color: lightgray;
  }
  ```
  - This targets the element with the id `header`, setting its background color to light gray.

- **HTML Example**:
  ```html
  <div id="header">This is the header section.</div>
  ```

### Attribute Selector

The attribute selector targets elements with a specific attribute or attribute value.

- **Syntax**: `[attribute]` or `[attribute="value"]`
- **Example**:
  ```css
  input[type="text"] {
      border: 1px solid black;
  }
  ```
  - This targets all `<input>` elements with the attribute `type="text"`, setting their border to a solid black line.

### Example CSS with Various Selectors

```css
/* Element selector */
h2 {
    color: green;
}

/* Class selector */
.button {
    padding: 10px 20px;
    background-color: blue;
    color: white;
}

/* ID selector */
#main-content {
    margin: 20px;
    padding: 10px;
    background-color: #f9f9f9;
}

/* Attribute selector */
a[target="_blank"] {
    color: orange;
}
```

By understanding CSS syntax and the different types of selectors, you can effectively target and style HTML elements, creating visually appealing and well-structured web pages.

---

This lesson provides a foundational understanding of CSS syntax and selectors, preparing you for more advanced styling techniques and responsive design.