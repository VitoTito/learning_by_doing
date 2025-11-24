# HTML/CSS

## Introduction

**HTML = Hyper-Text Markup Language** : how some content should be displayed (with tags) => *structure, fundation of a website*

**CSS = Cascading Style Sheets** : decorations, design and colors

`index.html` : generally the main page

## Main tags of HTML

- `<html> </html>` : root element of an HTML page. All is inside !
- `<head> </head>` : information about the web page
- `<title> </title>` : title of the web page
- `<link rel="icon" type="image/jpg" href="favicon.jpg">` : icon of the website
- `<body> </body>` : visible content of the web page
- `<h1> </h1>` : title of level 1 (h2 = title of level 2, h3 = title of level 3...)
- `<p> </p>` : paragraph
- `<pre> </pre>` : paragraph but retain any line breaks/spaces
- `<br>` : line break
- `<hr>` : horizontal line
- `<!-- this is a comment -->` : comment
- `<a href="link.com">  </a>` : hyperlink (digital reference to data, clicking on it)
    **Attributes**
    - `href=` : link / file to follow
    - `target="_blank"` : opening in a new tab / window
    - `title="Goes to Google"` : text displayed when mouse on the link
-  `<img src="assets/costume.png">` : displaying an image
    **Attributes**
    - `height=200px` : height
    - `width="200px"` : width
    - `alt="Text If Needed"` : alternative text if the image cannot be displayed
- `<audio controls> <source src="file.mp3"> <audio>` : audio
- `<video controls> <source src="video.mp4"> </video>` : video
- `<b> </b>` : makes text bold
- `<i> </i>` : makes text italic
- `<u> </u>` : makes text underlined
- `<del> </del>` : shows text as deleted
- `<big> </big>` : displays text in a bigger size
- `<small> </small>` : displays text in a smaller size
- `<sub> </sub>` : displays text as subscript
- `<sup> </sup>` : displays text as superscript
- `<tt> </tt>` : displays text in a monospaced typeface
- `<mark> </mark>` : highlights text
- `<span>` : inline container grouping elements (styling purposes), targeting a piece of text / fragment
- `<div>` : block container grouping elements (styling purposes), grouping blocs, taking all the width
- **3 types of list :** 
    1. **Ordered list** : `<ol> <li> item </li> </ol>`
    2. **Unordered list** : `<ul> <li> item </li> </ul>`
    3. **Description list** : `<dl> <dt> term </dt> <dd> description </dd> </dl>`
- `<table> <tr> <th> header </th> </tr> <tr> <td> data </td> </tr> </table>` : creating a table with rows (tr = table rows), headers (th = table headers) and cells (td = table data)
- `<button> </button>` : creates a clickable button element
- `<script> </script>` : defines a block of JavaScript code to add interactivity or manipulate the page
- `<form> </form>` :: creating a form