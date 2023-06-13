# Learning to code your first website

## Objectives

The goal of this lesson is to learn how to create websites using html, css and javascript. These technologies are the
basics of coding websites and will be useful to understand how a website works.

## The lessons you will have

- Learn HTML
- Learn CSS
- build your own website
- Learn JavaScript

## Activity

### Learn HTML

HTML, which stands for Hypertext Markup Language, is the standard markup language used for creating and structuring web
pages. It provides a set of predefined tags or elements that define the structure and content of a webpage.

HTML documents are composed of a series of elements, each enclosed within opening <tag> and closing </tag> tags. These
elements can represent various types of content, such as headings, paragraphs, images, links, tables, forms, and more.

The structure of an HTML document typically includes:

```<!DOCTYPE html>``` declaration: This specifies the version of HTML being used, which is HTML5 in modern web development.

```<html>``` element: This serves as the root element and encapsulates the entire HTML document.

```<head>``` element: This contains metadata about the webpage, such as the title displayed in the browser's title bar, links to external stylesheets, and other information that is not displayed directly on the page.

```<body>``` element: This represents the main content area of the webpage and contains all the visible content that users see when they visit the page.

Within the <body> element, you can use a variety of tags to structure and format the content, create headings and
paragraphs, insert images, create lists, define tables, and more. HTML also allows you to add hyperlinks to other pages
or resources and embed multimedia elements such as videos or audio.
Instructions:

1. Create a new HTML file:
    - Open a text editor such as Notepad++ or Visual Studio Code.
    - Create a new blank file.
    - Save the file with the ".html" extension, for example, "my_website.html".
2. Basic structure:
    - Inside the HTML file, add the following basic tags:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Website</title>
</head>
<body>
<!-- Your HTML content will be added here -->
</body>
</html>
```

3. Add content to your page:

Inside the <body> tag, add the following elements:

- A level 1 heading:

```html
<h1>Welcome to my website!</h1>
```

- A paragraph of text:

```html
<p>This is my first website.</p>
```

- A bulleted list:

```html

<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

- An image:

```html
<img src="path/to/image.jpg" alt="My first image">
```

- A link to another page:

```html
<a href="path/to/another_page.html">Link to another page</a>
```

4. Save the file and open it in your browser:

- Save your modifications to the HTML file.
- Open your web browser (e.g., Google Chrome, Firefox, etc.).
- Drag the HTML file into the browser window or use the "Open File" option in the browser menu.
- Verify that your page is displayed correctly with the content you added.

5. Further exploration (optional):

- Try adding more HTML elements to your page, such as lower-level headings (``<h2>``, ``<h3>``, etc...),
  tables (``<table>``), forms (``<form>``), etc.
- Experiment with text formatting using tags like ``<strong>``, ``<em>``, ``<u>``, ``<s>``, etc.

#### To understand :

``<html>``: Defines the root of an HTML document.

``<head>``: Contains metadata and other header elements for an HTML document.

``<title>``: Defines the title of the document, displayed in the browser's title bar or tab.

``<body>``: Represents the content of an HTML document.

``<h1>`` to ``<h6>``: Defines six levels of headings, with ``<h1>`` being the highest and ``<h6>`` the lowest.

``<p>``: Represents a paragraph of text.

``<a>``: Creates a hyperlink to another webpage or a specific location within the same document.

``<img>``: Inserts an image into the document.

``<ul>``: Represents an unordered (bulleted) list.

````html

<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
````

``<ol>``: Represents an ordered (numbered) list.

``<li>``: Represents a list item within ``<ul>`` or ``<ol>``.

``<table>``: Represents tabular data.

``<tr>``: Defines a row within a table.

````html

<table>
    <tr>
        <td>Cell 1</td>
        <td>Cell 2</td>
        <td>Cell 3</td>
    </tr>
</table>
````

``<th>``: Defines a header cell within a table row.

````html

<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
        <td>Data 3</td>
    </tr>
</table>
````

``<td>``: Defines a standard cell within a table row.

````html

<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
        <td>Data 3</td>
    </tr>
</table>
````

``<form>``: Represents an HTML form for user input.

``<input>``: Creates an input field within a form.

``<button>``: Creates a clickable button.

``<textarea>``: Defines a multi-line text input control.

``<select>``: Creates a dropdown list.

``<option>``: Defines an option within a ``<select>`` element.

``<div>``: Represents a division or section in an HTML document.

````html

<div>
    <h2>Welcome to my website!</h2>
    <p>This is a sample paragraph.</p>
</div>
````

``<span>``: Defines a section of text within another element.

This concludes the TP on Introduction to HTML. I hope this was helpful for you to get started on creating your own
website! Feel free to explore further and learn more advanced HTML concepts.

