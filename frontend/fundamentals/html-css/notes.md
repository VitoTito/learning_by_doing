# HTML/CSS

## Introduction

**HTML = Hyper-Text Markup Language** : how some content should be displayed (with tags) => *structure, fundation of a website*

**CSS = Cascading Style Sheets** : decorations, design and colors

`index.html` : generally the main page

## Main elements of HTML

- `<html> </html>` : root element of an HTML page. All is inside !
- `<head> </head>` : information about the web page
- `<title> </title>` : title of the web page
- `<link rel="icon" type="image/jpg" href="favicon.jpg">` : icon of the website
- `<body> </body>` : visible content of the web page
- `<header> </header>` : top section of the page or a section, usually logo, navigation menu, and introductory content
- `<main> </main>` : primary content of the page : unique and directly related to the main purpose of the webpage
- `<footer> </footer>` : bottom section of the page, usually  copyright info, contact links, social media, or secondary navigation
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
- `<form> </form>` : creating a form
- `<label> </label>` : for form : label associated to a text field
- `<input> </input>` : for form : interactive field in a form


## Main elements of CSS

3 differents way to apply it :
1. **Inline** : directly on an HTML element using the `style` attribute
2. **Internal** : inside the `style` tag in the `<head>` of the document
3. **External** : written in a separate .css file and linked via `<link>` in the `<head>`

**Selectors**:
1. *Element selector* : `p{}` target all `<p>` tags for instance
2. *Class selector* : `.className{}` target elements with `class="className"` and **can be used on several elements**
3. *ID selector* : `#idName{}` target element with `id="idName"` and must be **unique in the page**
4. *Group selector* :  `h1, h2, h3{}` apply same style to multiple elements
5. *Descendant / child / pseudo-class selectors :* : `div p{}` apply to p in div elements

**Properties**

- **Text / font**:
  - `color` : text color
  - `font-family` : font type (often 3-4 defined, fallbacks in case if)
  - `font-size` : size of the text
  - `font-weight` : bold, normal, etc.
  - `text-decoration` : underline, line-through, none
  - `line-height` : space between lines

- **Box model**:
  - `margin` : space outside the element
  - `padding` : space inside the element
  - `border` : border around the element
  - `width` / `height` : dimensions of the element
  - `box-sizing` : content-box / border-box

- **Backgrounds**:
  - `background-color`
  - `background-image`
  - `background-size`
  - `background-position`
  - `background-repeat`

- **Display & layout**:
  - `display` : block, inline, inline-block, flex, grid, none

1. **block**  
    - The element takes the **full width** available.  
    - Always starts on a **new line**.  
    - You can set `width`, `height`, `margin`, `padding`, etc.  
    - Example elements: `<div>`, `<p>`, `<h1>`, `<section>`  

2. **inline**  
    - The element **does not start on a new line**.  
    - Takes **only the width of its content**.  
    - Cannot set `width` or `height`.  
    - Example elements: `<span>`, `<a>`, `<strong>`  

3. **inline-block**  
    - Behaves like **inline** (stays in line)  
    - But allows setting `width`, `height`, `margin`, `padding`  
    - Great for creating small blocks in a line  

4. **none**  
    - The element is **completely hidden**  
    - It **occupies no space** in the layout  
    - Different from `visibility: hidden`, which keeps the space  

5. **flex**  
    - Activates **Flexbox layout** for the element  
    - Allows easy alignment, spacing, and responsive layouts  
    - Child elements become flex items  

6. **grid**  
    - Activates **CSS Grid layout** for the element  
    - Allows complex grids with rows and columns  
    - Very powerful for full-page or component layouts  


  - `position` : static, relative, absolute, fixed, sticky
  - `top`, `right`, `bottom`, `left` : coordinates for positioned elements
  - `z-index` : layer order
  - `float` : allows elements to float left or right (old layout method)
  - `overflow` : controls what happens when content exceeds its box (visible, hidden, clip, scroll, auto)

- **Flexbox / Grid**:
  - `display: flex` / `display: grid` : 
  - `justify-content`, `align-items`
  - `flex-direction`, `flex-wrap`
  - `grid-template-columns`, `grid-template-rows`

- **Other effects / visual**:
  - `opacity` : transparency
  - `text-shadow` : shadow around text
  - `box-shadow` : shadow around elements
  - `border-radius` : rounded corners
  - `transform` : rotate, scale, translate
  - `transition` : smooth changes
  - `animation` : keyframe animations