No problem, Pawan! Here's the complete guide formatted in Markdown:

```markdown
# 1. Basics of HTML

## **Introduction to HTML**
HTML (HyperText Markup Language) is the standard language used to create web pages. It defines the structure of a webpage using a system of tags that wrap content. HTML is essential for building the foundation of any website.

---

## **HTML Structure**

Every HTML document starts with a basic structure. Here’s an example of the fundamental layout of an HTML page:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First HTML Page</title>
</head>
<body>
    <h1>Welcome to My Web Page</h1>
    <p>This is my first webpage using HTML!</p>
</body>
</html>
```

- `<!DOCTYPE html>`: Declares the document type and version of HTML.
- `<html>`: The root element that contains all other elements.
- `<head>`: Contains meta-information about the document (e.g., charset, title).
- `<meta charset="UTF-8">`: Specifies the character encoding.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Ensures responsiveness on mobile devices.
- `<title>`: The title of the webpage, which appears on the browser tab.
- `<body>`: The content that users will see on the webpage.

---

## **Basic Tags**

### **1. Headings (`<h1>` to `<h6>`)**

HTML provides six levels of headings, from `<h1>` (the highest) to `<h6>` (the lowest). These tags structure content hierarchically.

```html
<h1>Main Heading (h1)</h1>
<h2>Subheading (h2)</h2>
<h3>Sub-subheading (h3)</h3>
<h4>Sub-sub-subheading (h4)</h4>
<h5>Small heading (h5)</h5>
<h6>Tiniest heading (h6)</h6>
```

Headings are important for SEO and accessibility. Use them to structure your content logically.

---

### **2. Paragraphs (`<p>`)**

The `<p>` tag defines a paragraph of text. It automatically adds some margin (space) around the text.

```html
<p>This is a paragraph of text. HTML paragraphs are great for writing descriptive content.</p>
```

---

### **3. Links (`<a>`)**

The `<a>` tag (anchor) is used to create hyperlinks, allowing users to navigate to different web pages or resources.

```html
<a href="https://www.example.com" target="_blank">Visit Example Website</a>
```

- `href`: Specifies the URL of the link.
- `target="_blank"`: Opens the link in a new tab.

---

### **4. Images (`<img>`)**

The `<img>` tag is used to display images on a webpage. It is a self-closing tag, meaning it doesn’t have a closing counterpart like `</img>`.

```html
<img src="https://www.example.com/image.jpg" alt="Description of the image" width="500">
```

- `src`: The URL or path of the image.
- `alt`: Alternative text for accessibility, shown if the image fails to load.
- `width`: Controls the width of the image.

---

### **5. Lists**

#### **Unordered List (`<ul>`)**: Displays a list of items with bullet points.

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

#### **Ordered List (`<ol>`)**: Displays a list of items in numerical order.

```html
<ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
</ol>
```

#### **List Item (`<li>`)**: Represents each item in the list, whether it's in an unordered or ordered list.

---

## **Full Example**

Here’s how these tags might come together in a simple webpage:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic HTML Example</title>
</head>
<body>
    <h1>Welcome to My Web Page</h1>
    
    <p>This is a basic HTML webpage showcasing different HTML elements.</p>

    <h2>Headings</h2>
    <h3>This is a level 3 heading</h3>

    <h2>Images</h2>
    <img src="https://www.example.com/cat.jpg" alt="A cute cat" width="300">

    <h2>Links</h2>
    <p>Click here to visit <a href="https://www.example.com" target="_blank">Example.com</a>.</p>

    <h2>Lists</h2>
    <p>Here is an unordered list:</p>
    <ul>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ul>

    <p>Here is an ordered list:</p>
    <ol>
        <li>Step one</li>
        <li>Step two</li>
        <li>Step three</li>
    </ol>
</body>
</html>
```

This simple example introduces some basic tags and how they work together.
```

This Markdown version will help you easily follow the learning guide with formatted code snippets and explanations!