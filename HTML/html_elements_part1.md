
# Comprehensive Guide to HTML Elements

This document provides an overview of HTML elements, their purposes, and examples of how to use them. HTML elements are the building blocks of HTML documents, defining the structure and content of web pages.

## 1. Document Structure Elements

### `<!DOCTYPE html>`
Defines the document type and HTML version.

```html
<!DOCTYPE html>
```

### `<html>`
The root element of an HTML document.

```html
<!DOCTYPE html>
<html>
  <!-- Content goes here -->
</html>
```

### `<head>`
Contains metadata, scripts, and links to stylesheets.

```html
<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
</head>
<body>
  <!-- Body content goes here -->
</body>
</html>
```

### `<body>`
Contains the content of the document, such as text, images, links, etc.

```html
<body>
  <h1>Welcome to My Webpage!</h1>
  <p>This is a paragraph of text.</p>
</body>
```
### Output:
<div style="border: 1px solid #ddd; padding: 10px; margin-top: 10px;">

<body>
  <h1>Welcome to My Webpage!</h1>
  <p>This is a paragraph of text.</p>
</body>

</div>

### `<title>`
Sets the title of the document, shown in the browser tab.

```html
<head>
  <title>My Webpage Title</title>
</head>
```

### `<meta>`
Defines metadata such as character set, author, description, etc.

```html
<head>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML, CSS, JavaScript">
  <meta name="author" content="John Doe">
</head>
```

## 2. Text Content Elements

### `<h1>` to `<h6>`
Define headings, with `<h1>` being the highest (most important) level and `<h6>` the lowest.

```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
<h3>Sub-subheading</h3>
```

### `<p>`
Defines a paragraph of text.

```html
<p>This is a paragraph.</p>
```

### `<blockquote>`
Defines a block of text that is a quotation from another source.

```html
<blockquote cite="https://www.example.com">
  This is a blockquote example.
</blockquote>
```

### `<ol>`
Defines an ordered (numbered) list.

```html
<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ol>
```

### `<ul>`
Defines an unordered (bulleted) list.

```html
<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ul>
```

### `<li>`
Defines a list item within `<ol>`, `<ul>`, or `<menu>`.

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

### `<a>`
Defines a hyperlink.

```html
<a href="https://www.example.com">Visit Example.com</a>
```

### `<em>`
Emphasizes text (italic by default).

```html
<p>This is an <em>emphasized</em> word.</p>
```

### `<strong>`
Defines important text (bold by default).

```html
<p>This is a <strong>strong</strong> word.</p>
```

### `<br>`
Inserts a line break.

```html
<p>First line.<br>Second line.</p>
```

### `<hr>`
Inserts a thematic break (horizontal line).

```html
<hr>
```

### `<code>`
Defines a piece of computer code.

```html
<p>Here is some code: <code>console.log('Hello, world!');</code></p>
```

### `<pre>`
Defines preformatted text.

```html
<pre>
  Text inside a pre element
  is displayed in a fixed-width
  font, and preserves both spaces
  and line breaks.
</pre>
```
