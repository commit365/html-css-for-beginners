# Lesson 14: Responsive Design

## Media Queries and Breakpoints

Responsive design ensures that a website looks and functions well on a variety of devices and screen sizes. Media queries are a key tool in achieving responsive design, allowing you to apply different styles based on the characteristics of the user's device, such as screen width.

### Media Queries

Media queries are CSS rules that apply styles only when certain conditions are met. They are used to create breakpoints, which are specific screen widths where the design changes to accommodate different devices.

- **Basic Syntax**:
  ```css
  @media (condition) {
      /* CSS rules */
  }
  ```

- **Example**:
  ```css
  /* Styles for screens larger than 768px */
  @media (min-width: 768px) {
      .container {
          display: flex;
          flex-direction: row;
      }
  }

  /* Styles for screens smaller than 768px */
  @media (max-width: 767px) {
      .container {
          display: block;
      }
  }
  ```

### Breakpoints

Breakpoints are the specific screen widths at which your design changes. Common breakpoints target devices like smartphones, tablets, and desktops.

- **Common Breakpoints**:
  - 320px: Small mobile devices
  - 480px: Mobile devices
  - 768px: Tablets
  - 1024px: Small desktops
  - 1200px: Large desktops

## Mobile-First Design Principles

Mobile-first design is an approach where you start designing for the smallest screens first and then add styles for larger screens. This approach ensures that your website is optimized for mobile devices, which are increasingly the primary way users access the web.

### Mobile-First Approach

1. **Start with a Base Style**: Write your default styles for the smallest screen size (mobile devices).

2. **Add Media Queries for Larger Screens**: Use media queries to add styles for larger screens, progressively enhancing the design.

- **Example**:
  ```css
  /* Base styles for mobile devices */
  .container {
      display: block;
      padding: 10px;
  }

  /* Styles for tablets and larger devices */
  @media (min-width: 768px) {
      .container {
          display: flex;
          padding: 20px;
      }
  }

  /* Styles for desktops and larger devices */
  @media (min-width: 1024px) {
      .container {
          padding: 30px;
      }
  }
  ```

### Example HTML with Responsive Design

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* Base styles for mobile devices */
        .container {
            display: block;
            padding: 10px;
            background-color: lightgray;
        }

        .item {
            background-color: lightblue;
            margin: 10px 0;
            padding: 20px;
            text-align: center;
        }

        /* Styles for tablets and larger devices */
        @media (min-width: 768px) {
            .container {
                display: flex;
                flex-direction: row;
                justify-content: space-between;
            }

            .item {
                flex: 1;
                margin: 10px;
            }
        }

        /* Styles for desktops and larger devices */
        @media (min-width: 1024px) {
            .container {
                padding: 30px;
            }
        }
    </style>
    <title>Responsive Design Example</title>
</head>
<body>
    <div class="container">
        <div class="item">Item 1</div>
        <div class="item">Item 2</div>
        <div class="item">Item 3</div>
    </div>
</body>
</html>
```

By understanding media queries, breakpoints, and mobile-first design principles, you can create responsive websites that provide an optimal viewing experience across a wide range of devices, from mobile phones to large desktop monitors.

---

This lesson provides a foundational understanding of responsive design, preparing you to build flexible and adaptable web layouts that meet the needs of modern users.

[Next: 15-Building-a-Simple-Web-Page](./15-Building-a-Simple-Web-Page.md)