# Lesson 15: Building a Simple Web Page

## Creating a Personal Portfolio or Blog Page

A personal portfolio or blog page is a great way to showcase your skills, projects, and thoughts. It serves as an online resume and a platform to express your creativity. In this lesson, we'll create a basic structure for a portfolio or blog page using HTML and CSS.

### Planning Your Page

Before you start coding, it's helpful to plan the structure and content of your page. Consider the following sections:

1. **Header**: Includes your name or the name of your blog and a navigation menu.
2. **About Section**: A brief introduction about yourself or your blog.
3. **Portfolio/Blog Section**: Displays your projects or blog posts.
4. **Contact Section**: Provides a way for visitors to contact you.
5. **Footer**: Contains copyright information or additional links.

### Setting Up Your HTML Structure

Create a new HTML file named `index.html` and set up the basic structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Welcome to my portfolio! I am a web developer with a passion for creating beautiful and functional websites.</p>
    </section>

    <section id="portfolio">
        <h2>My Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>Description of project 1.</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>Description of project 2.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: example@example.com</p>
    </section>

    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>
</body>
</html>
```

## Applying HTML and CSS Learned So Far

Now, let's style the page using CSS. Create a new CSS file named `styles.css` and add the following styles:

```css
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px;
}

.project {
    background-color: #f4f4f4;
    margin: 10px 0;
    padding: 10px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
```

### Explanation of the CSS

- **`body`**: Sets the font and line height for the entire page and removes default margins and padding.
- **`header`**: Styles the header with a dark background and white text.
- **`nav ul`**: Removes list styling and displays navigation links inline.
- **`section`**: Adds padding and margin to each section for spacing.
- **`.project`**: Styles individual project entries with a light background and padding.
- **`footer`**: Styles the footer with a dark background and white text, and fixes it to the bottom of the page.

By following this lesson, you can create a simple yet effective personal portfolio or blog page using the HTML and CSS skills you've learned. This project serves as a foundation that you can expand upon as you continue to develop your web design skills.

---

This lesson provides a practical application of HTML and CSS, allowing you to build a personal web page that showcases your abilities and creativity.
