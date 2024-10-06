# How to Write an HTML Boilerplate
![HTML Boilerplate](https://media.istockphoto.com/id/183381310/photo/html-code.jpg?s=2048x2048&w=is&k=20&c=jFq0b0FXjnUVTlHwpHRVf5K-2JY1eph1aNfXWsA3URE=)

An HTML boilerplate is a basic starting template for any web development project. Here's a basic HTML boilerplate structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    <!-- Your content goes here -->
</body>
</html>
```

### Explanation of the Boilerplate:

1. **DOCTYPE Declaration**: `<!DOCTYPE html>` tells the browser that the document is in HTML5.
2. **HTML Tag**: `<html>` is the root element of an HTML document. `lang="en"` specifies the language as English.
3. **Head Section**: The `<head>` tag contains meta-information about the document, such as the character set and viewport settings.
    - **Meta Charset**: `<meta charset="UTF-8">` defines the character encoding.
    - **Meta Viewport**: `<meta name="viewport" content="width=device-width, initial-scale=1.0">` ensures the page is responsive on different devices.
    - **Title**: The `<title>` tag sets the title of the web page that appears in the browser tab.
4. **Body Section**: The `<body>` tag contains the visible content of the web page. You will place your content here.

## 2. Why Use an HTML Boilerplate?

Using a boilerplate helps you get started quickly without missing essential elements in your HTML structure. It provides:
- A standardized format for web documents.
- Compatibility across various devices and browsers.
- Ease of managing meta tags and scripts.

## 3. Customizing Your Boilerplate

After creating the basic structure, you can modify the HTML boilerplate to include your styles, scripts, and additional content. Simply insert your code in the `<body>` section and link CSS or JavaScript files as needed.

For example:
```html
<link rel="stylesheet" href="styles.css">
<script src="script.js"></script>
```
For more information please visit [MDN docs.]https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started

