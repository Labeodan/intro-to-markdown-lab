# How to Write an HTML Boilerplate

An HTML Boilerplate is the starting template for any HTML document. It provides a standard structure to build your webpage.

## Basic HTML Boilerplate

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>HTML Boilerplate</title>
    <script defer src="app.js"></script>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>This is where your header contents. like your Nav </h1>
    </header>
    
    <main>
        <section>
            <p>This is a section of content on your webpage.</p>
        </section>
    </main>
    
    <footer></footer>

</body>
</html>
```
## Key Elements:
1. **`<!DOCTYPE html>`**: Defines the document type (HTML5).
2. **`<html lang="en">`**: Sets the language for the document.
3. **`<meta charset="UTF-8">`**: Specifies the character encoding.
4. **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Ensures responsive design.
5. **`<title>`**: Defines the title of the page shown in the browser tab.
6. **`<link rel="stylesheet" href="styles.css">`**: Links an external CSS file.
7. **`<script defer src="app.js"></script>`**: Links an external JavaScript file.
8. **`<header>`, `<main>`, `<footer>`**: Semantically organizes the content of your webpage.

## Customization:
- Change the page title inside the `<title>` tag.
- Modify the CSS and JavaScript file paths in the `<link>` and `<script>` tags.
- Add more sections or content within the `<main>` tag to expand your page.
