# Course 2: Web Development (HTML, CSS, JS)

## Course Description

Embark on a journey to become a web developer with this comprehensive course covering the foundational pillars of the web: HTML, CSS, and JavaScript. You will learn to structure web pages with HTML, style them beautifully with CSS, and add interactivity and dynamic behavior with JavaScript. This course is designed for beginners and progressively builds up your skills to tackle modern web development challenges. Through hands-on projects and detailed explanations, you'll gain the confidence to build your own websites and web applications.

## Prerequisites

*   Basic computer literacy and familiarity with using a web browser.
*   No prior coding experience is required.
*   A text editor (e.g., VS Code, Sublime Text, Atom) and a modern web browser (e.g., Chrome, Firefox).

## Course Outline

### Module 1: Introduction to Web Development & HTML Fundamentals

This module introduces the world of web development and dives deep into HTML, the backbone of all web pages.

*   **Lesson 1.1: What is Web Development?**
    *   Understanding the Internet and the World Wide Web.
    *   Client-Side vs. Server-Side Development.
    *   Frontend vs. Backend Development (and Full-Stack).
    *   The roles of HTML, CSS, and JavaScript.
    *   Tools of the Trade: Browsers, Text Editors, Developer Consoles.
    *   <YouTube videoId="ROUTEJG3Qvs" title="Web Development In 2024 - A Practical Guide by Traversy Media" />
    *   **Example:** When you visit a website like Google, your browser (client) requests the page from Google's servers. The servers send back HTML, CSS, and JavaScript files, which your browser then renders to display the webpage.

*   **Lesson 1.2: Setting Up Your Development Environment**
    *   Choosing and Installing a Text Editor (VS Code recommended).
        *   Basic VS Code setup: extensions (Live Server, Prettier).
    *   Understanding Web Browsers and their Developer Tools (Inspecting elements, Console, Network).
    *   Creating your first project folder and HTML file.
    *   <YouTube videoId="B-s71nLt2pQ" title="How To Set Up Your Front-End Web Development Environment by freeCodeCamp.org" />

*   **Lesson 1.3: Your First HTML Page - Structure and Syntax**
    *   What is HTML? (HyperText Markup Language)
    *   Basic HTML Document Structure:
        ```html
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>My First Web Page</title>
        </head>
        <body>
            <!-- Content goes here -->
        </body>
        </html>
        ```
    *   Understanding Tags, Elements, and Attributes.
        *   **Tag:** `<h1>`, `<p>`, `<a>`
        *   **Element:** `<h1>Hello World</h1>`
        *   **Attribute:** `<a href="https://example.com">Click me</a>` (`href` is an attribute)
    *   The `<!DOCTYPE html>` declaration.
    *   The `<html>` element and `lang` attribute.
    *   The `<head>` section: `<meta>`, `<title>`, linking CSS and JS (later).
    *   The `<body>` section: Visible content of the page.
    *   Comments in HTML: `<!-- This is a comment -->`
    *   <YouTube videoId="UB1O30fR-EE" title="HTML Crash Course For Absolute Beginners by Traversy Media" />

*   **Lesson 1.4: HTML Text Formatting and Semantics**
    *   Headings: `<h1>` to `<h6>`.
    *   Paragraphs: `<p>`.
    *   Emphasis and Importance: `<em>` (italic), `<strong>` (bold).
    *   Other text formatting: `<i>`, `<b>`, `<u>`, `<s>`, `<small>`, `<mark>`.
    *   Line breaks: `<br>`.
    *   Horizontal rules: `<hr>`.
    *   Quotations: `<blockquote>`, `<q>`, `<cite>`.
    *   Preformatted text: `<pre>`.
    *   Code: `<code>`.
    *   Semantic HTML: Using tags that describe the meaning of the content (e.g., `<article>`, `<section>`, `<nav>`, `<aside>`, `<footer>`, `<header>`).
    *   **Example:**
        ```html
        <article>
            <header>
                <h1>Understanding Semantic HTML</h1>
            </header>
            <p>Semantic HTML tags provide meaning to your web page's structure.</p>
            <footer>
                <p>Author: Web Dev Professor</p>
            </footer>
        </article>
        ```
    *   <YouTube videoId="k_AlE6E160c" title="Semantic HTML5 Elements Explained by freeCodeCamp.org" />

*   **Lesson 1.5: Lists in HTML**
    *   Unordered Lists: `<ul>` and `<li>`.
        ```html
        <ul>
            <li>Coffee</li>
            <li>Tea</li>
            <li>Milk</li>
        </ul>
        ```
    *   Ordered Lists: `<ol>` and `<li>`.
        ```html
        <ol>
            <li>Gather ingredients</li>
            <li>Mix them</li>
            <li>Bake for 30 minutes</li>
        </ol>
        ```
    *   Description Lists: `<dl>`, `<dt>`, `<dd>`.
        ```html
        <dl>
            <dt>HTML</dt>
            <dd>HyperText Markup Language</dd>
            <dt>CSS</dt>
            <dd>Cascading Style Sheets</dd>
        </dl>
        ```
    *   Nesting Lists.
    *   <YouTube videoId="09oErColl_c" title="HTML Lists - UL, OL, and DL by Dev Ed" />

*   **Lesson 1.6: Links and Images in HTML**
    *   Creating Hyperlinks (Anchor tags): `<a>`.
        *   `href` attribute: URL or path to another file.
        *   `target` attribute: `_blank` (opens in new tab), `_self` (default).
        *   Linking to sections within the same page (using `id` attributes).
        *   Email and telephone links (`mailto:`, `tel:`).
    *   **Example:** `<a href="about.html" target="_blank">About Us</a>`
    *   Embedding Images: `<img>`.
        *   `src` attribute: Path to the image file.
        *   `alt` attribute: Alternative text for accessibility and if the image fails to load (very important!).
        *   `width` and `height` attributes (use with caution, CSS is preferred for sizing).
    *   **Example:** `<img src="images/logo.png" alt="Company Logo" width="100">`
    *   Image formats (JPEG, PNG, GIF, SVG).
    *   <YouTube videoId="4d3s_N7uLtw" title="HTML Links & Images Tutorial by The Net Ninja" />

### Module 2: Advanced HTML & Introduction to CSS

This module covers more advanced HTML concepts like tables and forms, and then introduces CSS for styling web pages.

*   **Lesson 2.1: HTML Tables**
    *   Creating Tables: `<table>`, `<tr>` (table row), `<th>` (table header), `<td>` (table data).
    *   Table Captions: `<caption>`.
    *   Spanning Rows and Columns: `rowspan` and `colspan` attributes.
    *   Grouping Table Content: `<thead>`, `<tbody>`, `<tfoot>`.
    *   Styling Tables (briefly, more in CSS module).
    *   **Example:**
        ```html
        <table>
            <caption>Monthly Sales</caption>
            <thead>
                <tr>
                    <th>Month</th>
                    <th>Sales</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>January</td>
                    <td>$10,000</td>
                </tr>
                <tr>
                    <td>February</td>
                    <td>$12,000</td>
                </tr>
            </tbody>
        </table>
        ```
    *   <YouTube videoId="htC0Mrn_h7M" title="HTML Tables Crash Course by Traversy Media" />

*   **Lesson 2.2: HTML Forms - Input Elements**
    *   The `<form>` element: `action` and `method` (GET, POST) attributes.
    *   Basic Input Types:
        *   `text`: `<input type="text" name="username" id="username">`
        *   `password`: `<input type="password" name="password">`
        *   `submit`: `<input type="submit" value="Login">`
        *   `reset`: `<input type="reset">`
        *   `radio`: `<input type="radio" name="gender" value="male"> Male` (same `name` for a group)
        *   `checkbox`: `<input type="checkbox" name="subscribe" value="yes"> Subscribe`
        *   `button`: `<input type="button" value="Click Me">` or `<button>Click Me</button>`
    *   The `<label>` element: Associating text with form controls (using `for` attribute with input `id`).
    *   `name` attribute: Essential for form submission.
    *   `value` attribute: Default value or value sent on submission.
    *   `placeholder` attribute: Hint text in input fields.
    *   `required` attribute: Making fields mandatory.
    *   <YouTube videoId="fNcJuPIZ2WE" title="HTML Forms - Input Types & Attributes by Dev Ed" />

*   **Lesson 2.3: HTML Forms - Advanced Elements & Attributes**
    *   Text Areas: `<textarea name="message" rows="5" cols="30"></textarea>`.
    *   Dropdown Lists (Select Boxes): `<select>` and `<option>`.
        ```html
        <select name="country">
            <option value="us">United States</option>
            <option value="ca">Canada</option>
        </select>
        ```
    *   File Uploads: `<input type="file">`.
    *   HTML5 Input Types: `email`, `url`, `number`, `date`, `color`, `range`, `search`.
    *   Form Validation (Client-side basics using HTML5 attributes).
    *   Grouping Form Elements: `<fieldset>` and `<legend>`.
    *   <YouTube videoId="YwbIeMlxZAU" title="HTML Forms In Depth - More Input Types & Attributes by Traversy Media" />

*   **Lesson 2.4: Introduction to CSS (Cascading Style Sheets)**
    *   What is CSS? Its role in presentation and styling.
    *   Benefits of separating structure (HTML) from presentation (CSS).
    *   Three ways to include CSS:
        *   Inline Styles: `style` attribute on HTML elements (avoid for large scale).
            *   **Example:** `<p style="color: blue; font-size: 16px;">This is blue text.</p>`
        *   Internal (Embedded) Styles: `<style>` tag in the `<head>` section.
            ```html
            <head>
                <style>
                    p {
                        color: red;
                    }
                </style>
            </head>
            ```
        *   External Style Sheets: Linking a `.css` file (most common and recommended).
            *   **HTML:** `<link rel="stylesheet" href="styles.css">`
            *   **styles.css:** `p { color: green; }`
    *   Basic CSS Syntax: `selector { property: value; }`.
    *   Comments in CSS: `/* This is a CSS comment */`.
    *   <YouTube videoId="yfoY53QXEnI" title="CSS Crash Course For Absolute Beginners by Traversy Media" />

*   **Lesson 2.5: CSS Selectors - Targeting HTML Elements**
    *   Universal Selector: `*` (selects everything - use with caution).
    *   Type/Element Selectors: `p`, `h1`, `div`.
    *   Class Selectors: `.classname` (reusable styles).
        *   **HTML:** `<p class="highlight">Important text.</p>`
        *   **CSS:** `.highlight { background-color: yellow; }`
    *   ID Selectors: `#idname` (unique identifier for an element).
        *   **HTML:** `<div id="main-content">...</div>`
        *   **CSS:** `#main-content { border: 1px solid black; }`
    *   Attribute Selectors: `[attribute]`, `[attribute=value]`, `[attribute~=value]`, etc.
        *   **Example:** `input[type="text"] { border: 1px solid gray; }`
    *   Grouping Selectors: `h1, h2, h3 { color: navy; }`
    *   Descendant Combinator (space): `div p` (selects all `p` elements inside a `div`).
    *   Child Combinator (`>`): `ul > li` (selects `li` elements that are direct children of `ul`).
    *   Adjacent Sibling Combinator (`+`): `h1 + p` (selects the first `p` immediately following an `h1`).
    *   General Sibling Combinator (`~`): `h1 ~ p` (selects all `p` elements that are siblings after an `h1`).
    *   <YouTube videoId="FQdaUv95mR8" title="CSS Selectors - Every CSS Selector Explained by Web Dev Simplified" />

*   **Lesson 2.6: CSS Colors, Backgrounds, and Units**
    *   Color Values:
        *   Named Colors: `red`, `blue`, `green`.
        *   Hexadecimal: `#FF0000`, `#00FF00`.
        *   RGB: `rgb(255, 0, 0)`.
        *   RGBA: `rgba(255, 0, 0, 0.5)` (includes alpha for transparency).
        *   HSL/HSLA: `hsl(0, 100%, 50%)`.
    *   Applying Colors: `color` (for text), `background-color`.
    *   Background Images: `background-image`, `background-repeat`, `background-position`, `background-size`, `background-attachment`.
    *   CSS Units:
        *   Absolute Units: `px` (pixels), `pt` (points), `cm`, `mm`, `in`.
        *   Relative Units:
            *   `%` (percentage of parent element).
            *   `em` (relative to the font-size of the element).
            *   `rem` (relative to the font-size of the root `<html>` element - highly recommended for font sizes).
            *   `vw` (viewport width), `vh` (viewport height).
    *   <YouTube videoId="1xoKqcnY7oY" title="CSS Colors, Backgrounds, and Units by Kevin Powell" />

### Module 3: CSS Box Model, Typography, and Layout Basics

This module delves into the CSS Box Model, text styling, and fundamental CSS layout techniques.

*   **Lesson 3.1: The CSS Box Model**
    *   Understanding the components: Content, Padding, Border, Margin.
    *   `width` and `height` properties (content box by default).
    *   `padding`: Space between content and border. ( `padding-top`, `padding-right`, etc. and shorthand `padding: 10px;`)
    *   `border`: The line around the padding. (`border-width`, `border-style`, `border-color`, and shorthand `border: 1px solid black;`)
    *   `margin`: Space outside the border, between elements. (`margin-top`, `margin-right`, etc. and shorthand `margin: 10px;`)
    *   `box-sizing` property: `content-box` (default) vs. `border-box` (highly recommended - width/height include padding and border).
        *   **Global reset:** `*, *::before, *::after { box-sizing: border-box; }`
    *   Collapsing Margins.
    *   <YouTube videoId="rIO532_iZc0" title="The CSS Box Model Explained by Traversy Media" />

*   **Lesson 3.2: CSS Typography**
    *   `font-family`: Specifying typefaces (serif, sans-serif, monospace, cursive, fantasy) and fallback fonts.
        *   **Example:** `font-family: Arial, Helvetica, sans-serif;`
    *   `font-size`: Setting text size (using `px`, `em`, `rem`).
    *   `font-weight`: `normal`, `bold`, numeric values (100-900).
    *   `font-style`: `normal`, `italic`, `oblique`.
    *   `text-align`: `left`, `right`, `center`, `justify`.
    *   `text-decoration`: `none`, `underline`, `overline`, `line-through`.
    *   `text-transform`: `none`, `capitalize`, `uppercase`, `lowercase`.
    *   `line-height`: Spacing between lines of text.
    *   `letter-spacing` and `word-spacing`.
    *   Using Web Fonts (e.g., Google Fonts via `@import` or `<link>`).
    *   <YouTube videoId="xR564C2hX0Y" title="CSS Typography - Crash Course by DesignCourse" />

*   **Lesson 3.3: CSS Display Property and Basic Layout**
    *   `display` property: `block`, `inline`, `inline-block`, `none`.
        *   `block`: Takes full width, starts on a new line (e.g., `<div>`, `<p>`, `<h1>`).
        *   `inline`: Takes only necessary width, does not start on a new line (e.g., `<span>`, `<a>`, `<img>`). Width/height and top/bottom margins don't apply directly.
        *   `inline-block`: Like `inline`, but respects width/height and top/bottom margins/padding.
        *   `none`: Hides the element.
    *   Centering block-level elements: `margin: 0 auto;` (when width is set).
    *   The `visibility` property (`visible`, `hidden`). Difference between `display: none` and `visibility: hidden`.
    *   <YouTube videoId="Qf-wdyxX7rA" title="CSS Display Property (inline, block, inline-block, none) by Kevin Powell" />

*   **Lesson 3.4: CSS Positioning**
    *   `position` property: `static` (default), `relative`, `absolute`, `fixed`, `sticky`.
    *   `static`: Normal flow of the document. `top`, `right`, `bottom`, `left`, `z-index` have no effect.
    *   `relative`: Positioned relative to its normal position. Can use `top`, `right`, `bottom`, `left`. Other elements are not affected.
    *   `absolute`: Positioned relative to its nearest *positioned* ancestor (or the initial containing block). Taken out of normal flow.
    *   `fixed`: Positioned relative to the viewport. Stays in the same place even when scrolling. Taken out of normal flow.
    *   `sticky`: A hybrid of `relative` and `fixed`. Behaves like `relative` until it hits a specified offset, then becomes `fixed`.
    *   `top`, `right`, `bottom`, `left` properties for offset.
    *   `z-index`: Controlling stacking order of positioned elements.
    *   <YouTube videoId="jx5jmI0UlXU" title="CSS Position Property (Static, Relative, Absolute, Fixed, Sticky) by Traversy Media" />

*   **Lesson 3.5: CSS Floats and Clearfix (Legacy Layout Technique)**
    *   `float` property: `left`, `right`, `none`. Used for wrapping text around images or creating multi-column layouts (less common now due to Flexbox/Grid).
    *   The `clear` property: `left`, `right`, `both`, `none`. Used to stop elements from wrapping around floated elements.
    *   The "clearfix hack": Techniques to contain floated children within a parent element.
        *   **Example (modern clearfix):**
            ```css
            .clearfix::after {
                content: "";
                clear: both;
                display: table;
            }
            ```
    *   Understanding float issues (collapsing parent, etc.).
    *   While Flexbox and Grid are preferred, understanding floats is useful for older codebases.
    *   <YouTube videoId="4p64hQG PLE" title="CSS Floats Explained by Kevin Powell" /> (He also explains why not to use them for layout anymore)

*   **Lesson 3.6: Pseudo-classes and Pseudo-elements**
    *   Pseudo-classes: Select elements based on their state or position.
        *   Link states: `:link`, `:visited`, `:hover`, `:active`.
        *   Form states: `:focus`, `:checked`, `:disabled`, `:required`, `:optional`.
        *   Positional: `:first-child`, `:last-child`, `:nth-child(n)`, `:nth-of-type(n)`.
        *   `:not(selector)`.
    *   **Example:** `a:hover { color: red; }`
    *   Pseudo-elements: Style specific parts of an element.
        *   `::before`: Inserts content before the element's content.
        *   `::after`: Inserts content after the element's content.
        *   `::first-line`: Styles the first line of a block-level element.
        *   `::first-letter`: Styles the first letter of a block-level element.
        *   `::selection`: Styles the portion of a document that has been highlighted by the user.
    *   **Example:** `p::first-letter { font-size: 2em; font-weight: bold; }`
    *   Using `content` property with `::before` and `::after`.
    *   <YouTube videoId_G01p6hbusA title="CSS Pseudo Classes and Pseudo Elements by Traversy Media" />

### Module 4: Modern CSS Layouts - Flexbox and Grid

This module focuses on powerful modern CSS layout systems: Flexbox and Grid.

*   **Lesson 4.1: Introduction to CSS Flexbox**
    *   What is Flexbox? A one-dimensional layout system for arranging items in rows or columns.
    *   Flex Container and Flex Items.
    *   Main Axis and Cross Axis.
    *   Enabling Flexbox: `display: flex;` or `display: inline-flex;` on the parent container.
    *   <YouTube videoId="K74l26pE4YA" title="Flexbox CSS In 20 Minutes by Traversy Media" />

*   **Lesson 4.2: Flex Container Properties**
    *   `flex-direction`: `row` (default), `row-reverse`, `column`, `column-reverse`. (Defines the main axis)
    *   `flex-wrap`: `nowrap` (default), `wrap`, `wrap-reverse`. (Controls if items wrap to new lines)
    *   `flex-flow`: Shorthand for `flex-direction` and `flex-wrap`.
    *   `justify-content`: Alignment along the main axis (`flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `space-evenly`).
    *   `align-items`: Alignment along the cross axis (`stretch`, `flex-start`, `flex-end`, `center`, `baseline`).
    *   `align-content`: Alignment of multiple lines (when `flex-wrap: wrap` is used) (`flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `stretch`).
    *   **Example:** Creating a navigation bar where items are evenly spaced.
        ```css
        .nav-container {
            display: flex;
            justify-content: space-around;
            background-color: lightgray;
        }
        .nav-item { padding: 10px; }
        ```
    *   <YouTube videoId="Y8zMYaD16w8" title="CSS Flexbox - Full Tutorial by SuperSimpleDev" />

*   **Lesson 4.3: Flex Item Properties**
    *   `order`: Controls the order of flex items.
    *   `flex-grow`: Ability for a flex item to grow if necessary (distributes extra space).
    *   `flex-shrink`: Ability for a flex item to shrink if necessary.
    *   `flex-basis`: Default size of an item before remaining space is distributed.
    *   `flex`: Shorthand for `flex-grow`, `flex-shrink`, and `flex-basis`.
    *   `align-self`: Overrides `align-items` for individual flex items.
    *   **Example:** Making one item in a flex container take up more space.
        ```css
        .item-main { flex-grow: 2; } /* Will be twice as large as items with flex-grow: 1 */
        ```
    *   <YouTube videoId="Y8zMYaD16w8" title="CSS Flexbox - Full Tutorial by SuperSimpleDev" /> (Continued)

*   **Lesson 4.4: Introduction to CSS Grid Layout**
    *   What is CSS Grid? A two-dimensional layout system for rows AND columns.
    *   Grid Container and Grid Items.
    *   Enabling Grid: `display: grid;` or `display: inline-grid;` on the parent container.
    *   Defining Grid Structure: `grid-template-columns` and `grid-template-rows`.
        *   Units: `px`, `%`, `auto`, `fr` (fractional unit), `minmax()`, `repeat()`.
    *   **Example:**
        ```css
        .grid-container {
            display: grid;
            grid-template-columns: 1fr 2fr 1fr; /* Three columns, middle one is twice as wide */
            grid-template-rows: auto 100px;   /* Two rows, first auto height, second 100px */
            gap: 10px; /* Gap between grid cells */
        }
        ```
    *   <YouTube videoId="jV8B24rSN5o" title="CSS Grid Layout Crash Course by Traversy Media" />

*   **Lesson 4.5: Grid Container Properties & Item Placement**
    *   `grid-template-areas`: Defining named grid areas for easier item placement.
    *   `grid-gap` (or `gap`, `row-gap`, `column-gap`): Spacing between grid cells.
    *   `justify-items` and `align-items`: Aligning items within their grid cell (for the container).
    *   `justify-content` and `align-content`: Aligning the grid itself within the container (if the grid is smaller than its container).
    *   Placing Items:
        *   Line-based placement: `grid-column-start`, `grid-column-end`, `grid-row-start`, `grid-row-end`.
        *   Shorthands: `grid-column`, `grid-row`.
        *   Using `span` keyword.
        *   Placing items into named areas: `grid-area`.
    *   **Example using `grid-template-areas`:**
        ```css
        .container {
            display: grid;
            grid-template-columns: 1fr 3fr;
            grid-template-rows: auto 1fr auto;
            grid-template-areas:
                "header header"
                "sidebar main"
                "footer footer";
            gap: 10px;
        }
        .header { grid-area: header; }
        .sidebar { grid-area: sidebar; }
        .main { grid-area: main; }
        .footer { grid-area: footer; }
        ```
    *   <YouTube videoId="0xMQfnTU6oo" title="CSS Grid Tutorial - A Complete Guide by Web Dev Simplified" />

*   **Lesson 4.6: Responsive Web Design Principles**
    *   What is Responsive Web Design (RWD)? Creating web pages that look good on all devices (desktops, tablets, phones).
    *   Key Concepts:
        *   Fluid Grids (using percentages or `fr` units).
        *   Flexible Images (using `max-width: 100%; height: auto;`).
        *   Media Queries: Applying different CSS rules based on device characteristics (e.g., viewport width, orientation).
    *   Viewport Meta Tag: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`.
    *   Writing Media Queries:
        ```css
        /* Default styles (mobile-first) */
        .container { width: 100%; }

        /* Tablet styles */
        @media (min-width: 768px) {
            .container { width: 750px; }
        }

        /* Desktop styles */
        @media (min-width: 992px) {
            .container { width: 970px; }
        }
        ```
    *   Mobile-First vs. Desktop-First approaches.
    *   Testing responsiveness using browser developer tools.
    *   <YouTube videoId="srvUrASNj0s" title="Responsive Web Design - HTML & CSS Tutorial by freeCodeCamp.org" />

### Module 5: JavaScript Fundamentals

This module introduces JavaScript, the programming language of the web, for adding interactivity and dynamic behavior.

*   **Lesson 5.1: Introduction to JavaScript**
    *   What is JavaScript? Its role in making web pages interactive.
    *   Client-Side JavaScript.
    *   Where JavaScript fits (HTML for structure, CSS for style, JS for behavior).
    *   Adding JavaScript to an HTML page:
        *   Internal JS: `<script>` tag in `<head>` or `<body>` (usually before `</body>`).
            ```html
            <script>
                console.log("Hello from internal JavaScript!");
            </script>
            ```
        *   External JS: Linking a `.js` file (recommended).
            *   **HTML:** `<script src="app.js"></script>`
            *   **app.js:** `console.log("Hello from external JavaScript!");`
    *   The Browser Console for output and debugging.
    *   Comments in JS: `// Single-line comment` and `/* Multi-line comment */`.
    *   <YouTube videoId="W6NZfCO5SIk" title="JavaScript Crash Course For Beginners by Traversy Media" />

*   **Lesson 5.2: Variables, Data Types, and Operators**
    *   Variables: `let`, `const`, and `var` (understanding scope and hoisting differences, prefer `let` and `const`).
        *   **Example:** `let age = 30; const name = "Alice";`
    *   Data Types:
        *   Primitive Types: `String`, `Number` (integers and floats), `Boolean`, `Null`, `Undefined`, `Symbol` (ES6), `BigInt` (ES2020).
        *   Object Type: `Object` (including arrays, functions, dates).
    *   Type Coercion and `typeof` operator.
    *   Operators:
        *   Arithmetic: `+`, `-`, `*`, `/`, `%` (modulus), `**` (exponentiation).
        *   Assignment: `=`, `+=`, `-=`, `*=`, `/=`.
        *   Comparison: `==` (loose equality), `===` (strict equality - preferred), `!=`, `!==`, `>`, `<`, `>=`, `<=`.
        *   Logical: `&&` (AND), `||` (OR), `!` (NOT).
        *   String Concatenation with `+`.
    *   Template Literals (Backticks): ``` `Hello, ${name}!` ```.
    *   <YouTube videoId="jS4aFq5-91M" title="JavaScript Variables, Data Types, and Operators by Programming with Mosh" />

*   **Lesson 5.3: Control Flow - Conditional Statements and Loops**
    *   Conditional Statements:
        *   `if`, `else if`, `else`.
            ```javascript
            let score = 85;
            if (score >= 90) {
                console.log("Grade: A");
            } else if (score >= 80) {
                console.log("Grade: B");
            } else {
                console.log("Grade: C or below");
            }
            ```
        *   Ternary Operator: `condition ? exprIfTrue : exprIfFalse;`
        *   `switch` statement.
    *   Loops:
        *   `for` loop:
            ```javascript
            for (let i = 0; i < 5; i++) {
                console.log("Iteration " + i);
            }
            ```
        *   `while` loop.
        *   `do...while` loop.
        *   `break` and `continue` statements.
    *   <YouTube videoId="s9wW2PpjmkE" title="JavaScript Control Flow - If/Else, Switch, Loops by Academind" />

*   **Lesson 5.4: Functions in JavaScript**
    *   What are Functions? Reusable blocks of code.
    *   Defining Functions:
        *   Function Declaration: `function greet(name) { return "Hello, " + name; }`
        *   Function Expression: `const greet = function(name) { return "Hello, " + name; };`
        *   Arrow Functions (ES6): `const greet = (name) => "Hello, " + name;` or `const add = (a, b) => { return a + b; };`
    *   Calling Functions.
    *   Parameters and Arguments.
    *   Return Values.
    *   Scope: Global vs. Local (Function Scope, Block Scope with `let`/`const`).
    *   Default Parameters (ES6).
    *   Rest Parameters (ES6).
    *   <YouTube videoId="N8ap4k_1QEQ" title="JavaScript Functions - Tutorial for Beginners by Programming with Mosh" />

*   **Lesson 5.5: Arrays and Array Methods**
    *   What are Arrays? Ordered collections of items.
    *   Creating Arrays: `let fruits = ["Apple", "Banana", "Cherry"];` or `let numbers = new Array(1, 2, 3);`
    *   Accessing Elements (zero-based indexing).
    *   Modifying Elements.
    *   Array Properties: `length`.
    *   Common Array Methods:
        *   `push()`, `pop()` (add/remove from end).
        *   `shift()`, `unshift()` (add/remove from beginning).
        *   `indexOf()`, `includes()`.
        *   `slice()`, `splice()`.
        *   `concat()`, `join()`.
        *   Iteration methods: `forEach()`, `map()`, `filter()`, `reduce()`, `find()`, `some()`, `every()`.
    *   **Example (map):** `let numbers = [1, 2, 3]; let doubled = numbers.map(num => num * 2); // [2, 4, 6]`
    *   <YouTube videoId="oigfaZ5ApsM" title="JavaScript Arrays & Array Methods by Traversy Media" />

*   **Lesson 5.6: Objects and Object Basics**
    *   What are Objects? Collections of key-value pairs (properties).
    *   Creating Objects:
        *   Object Literal:
            ```javascript
            let person = {
                firstName: "John",
                lastName: "Doe",
                age: 30,
                greet: function() {
                    console.log("Hello, my name is " + this.firstName);
                }
            };
            ```
        *   Constructor Functions (less common now, classes preferred).
    *   Accessing Properties: Dot notation (`person.firstName`) and Bracket notation (`person["lastName"]`).
    *   Modifying Properties.
    *   Adding and Deleting Properties.
    *   Methods in Objects (functions as properties).
    *   The `this` keyword (context in methods).
    *   Iterating over object properties (`for...in` loop, `Object.keys()`, `Object.values()`, `Object.entries()`).
    *   <YouTube videoId="X0løXN02JU0" title="JavaScript Objects - In-Depth Tutorial by Programming with Mosh" />

### Module 6: DOM Manipulation, Events, and Basic Web Applications

This module focuses on how JavaScript interacts with HTML (the DOM) and handles user events to build dynamic web pages.

*   **Lesson 6.1: Introduction to the DOM (Document Object Model)**
    *   What is the DOM? A programming interface for HTML documents. Represents the page structure as a tree of objects.
    *   How JavaScript interacts with the DOM.
    *   The `document` object.
    *   Selecting Elements:
        *   `document.getElementById('id')`
        *   `document.getElementsByClassName('classname')` (returns HTMLCollection)
        *   `document.getElementsByTagName('tagname')` (returns HTMLCollection)
        *   `document.querySelector('cssSelector')` (returns the first match)
        *   `document.querySelectorAll('cssSelector')` (returns a NodeList)
    *   **Example:** `const heading = document.getElementById('main-title');`
    *   <YouTube videoId="WnILZLS5s4k" title="What is the DOM? Document Object Model Explained by Traversy Media" />

*   **Lesson 6.2: Traversing and Manipulating the DOM**
    *   Navigating the DOM Tree:
        *   `parentNode`, `childNodes`, `firstChild`, `lastChild`, `nextSibling`, `previousSibling`.
        *   `parentElement`, `children`, `firstElementChild`, `lastElementChild`, `nextElementSibling`, `previousElementSibling` (preferred over node versions).
    *   Modifying Element Content:
        *   `innerHTML` (can include HTML tags, security risk if using user input).
        *   `textContent` (plain text only, safer).
        *   `innerText` (similar to `textContent` but considers styling).
    *   Modifying Element Attributes: `getAttribute()`, `setAttribute()`, `removeAttribute()`.
        *   Direct property access for some attributes (e.g., `element.id`, `element.src`).
    *   Modifying Element Styles: `element.style.property = 'value'` (e.g., `heading.style.color = 'blue';`).
    *   Working with CSS Classes: `element.classList.add()`, `remove()`, `toggle()`, `contains()`.
    *   **Example:**
        ```javascript
        const para = document.querySelector('.my-paragraph');
        para.textContent = "New content for the paragraph!";
        para.classList.add('highlight');
        ```
    *   <YouTube videoId="0ik6X4DJKCc" title="JavaScript DOM Manipulation - Full Course for Beginners by freeCodeCamp.org" /> (Select relevant sections)

*   **Lesson 6.3: Creating and Removing DOM Elements**
    *   Creating New Elements: `document.createElement('tagName')`.
    *   Adding Elements to the DOM:
        *   `parentNode.appendChild(childNode)`
        *   `parentNode.insertBefore(newNode, referenceNode)`
    *   Removing Elements: `parentNode.removeChild(childNode)` or `childNode.remove()` (newer).
    *   Replacing Elements: `parentNode.replaceChild(newChild, oldChild)`.
    *   **Example: Creating a list item and adding it to a list.**
        ```javascript
        const ul = document.querySelector('ul');
        const newLi = document.createElement('li');
        newLi.textContent = "New Item";
        ul.appendChild(newLi);
        ```
    *   <YouTube videoId="0ik6X4DJKCc" title="JavaScript DOM Manipulation - Full Course for Beginners by freeCodeCamp.org" /> (Continued)

*   **Lesson 6.4: Handling Events in JavaScript**
    *   What are Events? Actions that occur on a web page (clicks, mouse movements, key presses, form submissions, page loads).
    *   Event Listeners: Attaching functions to run when an event occurs.
    *   Methods for Attaching Event Listeners:
        *   Inline HTML event attributes (e.g., `onclick="..."` - generally discouraged).
        *   DOM element properties (e.g., `button.onclick = function() { ... };` - only one per event).
        *   `addEventListener('eventtype', callbackFunction)` (recommended, multiple listeners possible).
        *   `removeEventListener('eventtype', callbackFunction)`.
    *   The `event` object: Contains information about the event (e.g., `event.target`, `event.preventDefault()`, `event.stopPropagation()`).
    *   Common Event Types: `click`, `mouseover`, `mouseout`, `mousedown`, `mouseup`, `mousemove`, `keydown`, `keyup`, `keypress`, `focus`, `blur`, `submit`, `load`, `DOMContentLoaded`.
    *   **Example:**
        ```javascript
        const myButton = document.getElementById('myBtn');
        myButton.addEventListener('click', function(event) {
            console.log('Button clicked!');
            console.log(event.target); // Logs the button element
        });
        ```
    *   <YouTube videoId="XEMhrfCMQ-Y" title="JavaScript Event Listeners - Crash Course by Traversy Media" />

*   **Lesson 6.5: Building a Simple To-Do List Application (Project)**
    *   Project Goal: Create a web page where users can add tasks, mark tasks as complete, and remove tasks.
    *   HTML Structure: Input field, add button, unordered list for tasks.
    *   CSS Styling: Basic styling for the application.
    *   JavaScript Logic:
        *   Function to add a new task:
            *   Get value from input field.
            *   Create new `<li>` element with task text.
            *   Add buttons/checkboxes for complete/delete.
            *   Append to the `<ul>`.
        *   Event listener for "add task" button.
        *   Event delegation for "complete" and "delete" actions on tasks (attach listener to parent `<ul>`).
        *   Functionality to toggle task completion (e.g., line-through style).
        *   Functionality to remove a task from the list.
    *   This project integrates HTML, CSS, DOM manipulation, and event handling.

*   **Lesson 6.6: Introduction to Asynchronous JavaScript (Callbacks, Promises, Async/Await - Overview)**
    *   Synchronous vs. Asynchronous code execution.
    *   Why Asynchronous JS? (Handling time-consuming operations like fetching data without blocking the main thread).
    *   Callbacks: Functions passed as arguments to other functions, executed later.
        *   Callback Hell / Pyramid of Doom.
    *   Promises: Objects representing the eventual completion (or failure) of an asynchronous operation.
        *   States: `pending`, `fulfilled`, `rejected`.
        *   `.then()` for success, `.catch()` for errors, `.finally()`.
    *   `async/await` (ES2017): Syntactic sugar over Promises, making async code look more synchronous.
        *   `async` functions always return a Promise.
        *   `await` pauses execution until a Promise settles.
    *   Brief overview of `fetch()` API for making network requests (uses Promises).
    *   **Example (Promise):**
        ```javascript
        fetch('https://api.example.com/data')
            .then(response => response.json())
            .then(data => console.log(data))
            .catch(error => console.error('Error fetching data:', error));
        ```
    *   **Example (async/await):**
        ```javascript
        async function fetchData() {
            try {
                const response = await fetch('https://api.example.com/data');
                const data = await response.json();
                console.log(data);
            } catch (error) {
                console.error('Error fetching data:', error);
            }
        }
        fetchData();
        ```
    *   <YouTube videoId="V_Kr9OSfDeU" title="Async JS Crash Course - Callbacks, Promises, Async Await by Traversy Media" />
    *   This is an introduction; deeper dives into async operations are typically covered in more advanced courses.

---

This course provides a solid foundation in frontend web development. Each lesson should be expanded with more examples, coding exercises, and mini-projects to reinforce learning. Good luck on your web development journey!
