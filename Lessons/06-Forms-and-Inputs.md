# Lesson 6: Forms and Inputs

## Creating Forms

Forms are essential components of web pages, allowing users to input and submit data. HTML forms are created using the `<form>` element, which can contain various input elements like text fields, checkboxes, radio buttons, and submit buttons.

### Basic Structure of a Form

```html
<form action="/submit-form" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>
    
    <input type="submit" value="Submit">
</form>
```

### Explanation of the Structure:

- `<form>`: The container for the form elements. The `action` attribute specifies the URL where the form data should be submitted, and the `method` attribute specifies the HTTP method to use (e.g., `post` or `get`).

- `<label>`: Associates a text label with a form element, improving accessibility. The `for` attribute should match the `id` of the corresponding input element.

- `<input>`: Represents an input field. The `type` attribute defines the type of input (e.g., text, email), and the `name` attribute specifies the name of the form data when submitted.

- `<input type="submit">`: A button that submits the form data to the server.

## Input Types and Attributes

HTML provides a variety of input types and attributes to capture different kinds of user input. Here are some common input types and their attributes:

### Text Input

- **Type**: `text`
- **Attributes**: `placeholder`, `maxlength`, `required`

```html
<input type="text" name="username" placeholder="Enter your username" maxlength="20" required>
```

### Email Input

- **Type**: `email`
- **Attributes**: `placeholder`, `required`

```html
<input type="email" name="email" placeholder="Enter your email" required>
```

### Password Input

- **Type**: `password`
- **Attributes**: `placeholder`, `required`

```html
<input type="password" name="password" placeholder="Enter your password" required>
```

### Radio Buttons

- **Type**: `radio`
- **Attributes**: `name`, `value`, `checked`

```html
<label>
    <input type="radio" name="gender" value="male" checked> Male
</label>
<label>
    <input type="radio" name="gender" value="female"> Female
</label>
```

### Checkboxes

- **Type**: `checkbox`
- **Attributes**: `name`, `value`, `checked`

```html
<label>
    <input type="checkbox" name="subscribe" value="newsletter" checked> Subscribe to newsletter
</label>
```

### Submit Button

- **Type**: `submit`
- **Attributes**: `value`

```html
<input type="submit" value="Submit">
```

### Example Form with Various Inputs

```html
<form action="/submit-form" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <label for="password">Password:</label>
    <input type="password" id="password" name="password" required>

    <label>
        <input type="radio" name="gender" value="male" checked> Male
    </label>
    <label>
        <input type="radio" name="gender" value="female"> Female
    </label>

    <label>
        <input type="checkbox" name="subscribe" value="newsletter" checked> Subscribe to newsletter
    </label>

    <input type="submit" value="Submit">
</form>
```

By understanding how to create forms and use different input types and attributes, you can design interactive and user-friendly web pages that effectively capture user input.

---

This lesson provides a foundational understanding of HTML forms and inputs, preparing you for more advanced form handling and validation techniques.

[Next: 07-CSS-Syntax-and-Selectors](./07-CSS-Syntax-and-Selectors.md)