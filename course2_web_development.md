# Course 2: Web Development (HTML, CSS, JS)

## Course Description

Embark on a journey to become a web developer with this comprehensive course covering the foundational pillars of the web: HTML, CSS, and JavaScript. You will learn to structure web pages with HTML, style them beautifully with CSS, and add interactivity and dynamic behavior with JavaScript. This course is designed for beginners and progressively builds up your skills to tackle modern web development challenges. Through hands-on projects and detailed explanations, you'll gain the confidence to build your own websites and web applications.

## Prerequisites

*   Basic computer literacy and familiarity with using a web browser.
*   No prior coding experience is required.
*   A text editor (e.g., VS Code, Sublime Text, Atom) and a modern web browser (e.g., Chrome, Firefox).

## Course Outline

### Module 1: Introduction to Web Development & HTML Fundamentals (Expanded)

This module introduces the world of web development and dives deep into HTML, the backbone of all web pages, now expanded for more comprehensive coverage.

*   **Lesson 1.1: The World Wide Web and How Websites Work**
    *   Understanding the Internet vs. The World Wide Web.
    *   Clients and Servers: The request-response cycle.
    *   IP Addresses, Domain Names, and DNS (Domain Name System).
    *   HTTP/HTTPS protocols: The language of the web.
    *   Anatomy of a URL (Scheme, Domain, Path, Query String, Fragment).
    *   How a browser renders a webpage (parsing HTML, CSS, executing JS).
    *   <YouTube videoId="JjH5IEaXCqA" title="How the Internet Works in 5 Minutes by Vint Cerf" />
    *   <YouTube videoId="7_LPdttKXPc" title="How Websites Work: The Request/Response Cycle by Treehouse" />
    *   <YouTube videoId="x3c1ih2NJE" title="What is DNS? | How DNS Works by Cloudflare" />

*   **Lesson 1.2: Frontend vs. Backend vs. Full-Stack Development**
    *   **Frontend Development (Client-Side):**
        *   Focus: What the user sees and interacts with in the browser.
        *   Core Technologies: HTML, CSS, JavaScript.
        *   Responsibilities: UI/UX design implementation, responsiveness, interactivity.
        *   Common Frameworks/Libraries: React, Angular, Vue.js.
    *   **Backend Development (Server-Side):**
        *   Focus: Server logic, databases, APIs, application performance, security.
        *   Core Technologies: Python (Django, Flask), Node.js (Express), Java (Spring), Ruby (Rails), PHP (Laravel), Databases (SQL, NoSQL).
        *   Responsibilities: Building APIs, managing data, server-side rendering.
    *   **Full-Stack Development:**
        *   Proficiency in both frontend and backend technologies.
        *   Understanding the entire web development process.
    *   The role of databases in web applications.
    *   <YouTube videoId="ROUTEJG3Qvs" title="Web Development In 2024 - A Practical Guide by Traversy Media" /> (Recap for roles)
    *   <YouTube videoId="pkdgVYehiTE" title="Frontend vs Backend Development - What's the Difference? by freeCodeCamp.org" />

*   **Lesson 1.3: Essential Tools for Web Developers**
    *   **Text Editors:**
        *   Purpose: Writing and editing code.
        *   Popular Choices: VS Code (Visual Studio Code), Sublime Text, Atom, Brackets, Notepad++.
        *   Key Features: Syntax highlighting, code completion, extensions, integrated terminal.
    *   **Web Browsers:**
        *   Purpose: Rendering web pages, testing code.
        *   Popular Choices: Google Chrome, Mozilla Firefox, Safari, Edge.
    *   **Browser Developer Tools:**
        *   Accessing DevTools (F12 or right-click > Inspect).
        *   Elements Panel: Inspecting and modifying HTML/CSS.
        *   Console Panel: Viewing JavaScript errors, logs, running JS commands.
        *   Network Panel: Analyzing resource loading and API calls.
        *   Sources Panel: Debugging JavaScript.
        *   Application Panel: Inspecting local storage, cookies, etc.
    *   **Version Control Systems (Git/GitHub - Introduction):**
        *   Purpose: Tracking changes to code, collaboration. (Deeper dive later).
    *   <YouTube videoId="B-s71nLt2pQ" title="How To Set Up Your Front-End Web Development Environment by freeCodeCamp.org" /> (Recap for setup)
    *   <YouTube videoId="H0XScE_x4qE" title="VS Code Tutorial for Beginners - Getting Started with VS Code by Traversy Media" />
    *   <YouTube videoId="x4q86IjJFag" title="Google Chrome Developer Tools Crash Course by Traversy Media" />

*   **Lesson 1.4: Introduction to HTML - The Structure of the Web**
    *   What is HTML? HyperText Markup Language.
    *   Not a programming language, but a markup language.
    *   Purpose: To define the structure and content of a web page.
    *   Analogy: The skeleton of a webpage.
    *   Evolution of HTML (HTML4, XHTML, HTML5). Key features of HTML5.
    *   The W3C (World Wide Web Consortium) and web standards.
    *   <YouTube videoId="UB1O30fR-EE" title="HTML Crash Course For Absolute Beginners by Traversy Media" /> (Recap)
    *   <YouTube videoId="kUMe1FH4CHE" title="What is HTML? by Mosh Hamedani" />

*   **Lesson 1.5: Basic HTML Document Structure - `<!DOCTYPE>`, `<html>`, `<head>`, `<body>`**
    *   The `<!DOCTYPE html>` declaration: Informs the browser about the HTML version (HTML5).
    *   The `<html>` element: The root element of an HTML page.
        *   `lang` attribute (e.g., `<html lang="en">`) for language specification.
    *   The `<head>` section: Contains meta-information about the HTML document (not displayed directly on the page).
        *   `<meta charset="UTF-8">`: Specifies character encoding (UTF-8 is standard).
        *   `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Configures the viewport for responsive design.
        *   `<title>Page Title</title>`: Defines the title that appears in the browser tab or window title bar.
        *   Links to CSS files (`<link>`) and JavaScript files (`<script>`) (covered later).
    *   The `<body>` section: Contains the visible content of the HTML document.
    *   Writing your first "Hello, World!" HTML page.
        ```html
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>My First Page</title>
        </head>
        <body>
            <h1>Hello, World!</h1>
            <p>This is my first webpage.</p>
        </body>
        </html>
        ```
    *   <YouTube videoId="gogft330fYA" title="HTML Tutorial for Beginners - 01 - Introduction to HTML by Programming with Mosh" /> (Focus on basic structure)

*   **Lesson 1.6: HTML Elements, Tags, and Attributes**
    *   **HTML Elements:** The building blocks of HTML pages, representing different types of content.
        *   Defined by a start tag, some content, and an end tag (e.g., `<p>This is a paragraph.</p>`).
        *   Some elements are "empty" or "void" (e.g., `<br>`, `<img>`, `<hr>`) and don't have end tags.
    *   **HTML Tags:** Keywords surrounded by angle brackets (`<tagname>`).
        *   Opening tags (e.g., `<h1>`) and closing tags (e.g., `</h1>`).
    *   **HTML Attributes:** Provide additional information about HTML elements.
        *   Always specified in the start tag.
        *   Come in name/value pairs like `name="value"`.
        *   **Example:** `<a href="https://example.com">Visit Example</a>` (`href` is an attribute of the `<a>` tag).
        *   Global attributes (can be used on any HTML element, e.g., `id`, `class`, `style`, `title`).
    *   Nesting HTML elements correctly.
    *   <YouTube videoId="Y1BlT4_c_SU" title="HTML Elements, Tags, and Attributes Explained by Kevin Powell" />

*   **Lesson 1.7: HTML Headings and Paragraphs**
    *   Headings (`<h1>` to `<h6>`): Define hierarchical headings.
        *   `<h1>` is the most important heading, `<h6>` is the least.
        *   Browsers display headings with default styling (font size, boldness).
        *   Importance for SEO and accessibility (screen readers use headings to navigate).
        *   Use headings in logical order.
    *   Paragraphs (`<p>`): Define blocks of text.
        *   Browsers automatically add some space (margin) before and after paragraphs.
    *   **Example:**
        ```html
        <h1>Main Title of the Page</h1>
        <p>This is an introductory paragraph.</p>
        <h2>Section 1 Title</h2>
        <p>Content for section 1...</p>
        <h3>Subsection 1.1 Title</h3>
        <p>Details for subsection 1.1...</p>
        ```
    *   <YouTube videoId="xsPXYjINFY" title="HTML Headings & Paragraphs by The Net Ninja" />

*   **Lesson 1.8: Text Formatting in HTML - Bold, Italic, Emphasis, Strong, etc.**
    *   **Physical Style Tags (older, less semantic):**
        *   `<b>`: Bold text.
        *   `<i>`: Italic text.
        *   `<u>`: Underlined text (use with caution, can be confused with links).
        *   `<s>` or `<strike>`: Strikethrough text.
    *   **Semantic Style Tags (preferred, convey meaning):**
        *   `<strong>`: Defines important text (browsers typically render as bold).
        *   `<em>`: Defines emphasized text (browsers typically render as italic).
        *   `<mark>`: Defines marked or highlighted text.
        *   `<small>`: Defines smaller text.
        *   `<sub>`: Subscript text.
        *   `<sup>`: Superscript text.
    *   The difference between `<b>` and `<strong>`, `<i>` and `<em>`.
    *   **Example:** `<p>This is <strong>very important</strong> and should be <em>emphasized</em>.</p>`
    *   <YouTube videoId="s156ljqIqg" title="HTML Text Formatting - Bold, Italic, Strong, Em, etc. by Dev Ed" />

*   **Lesson 1.9: Line Breaks and Horizontal Rules**
    *   Line Breaks (`<br>`): Inserts a single line break.
        *   An empty/void element.
        *   Use sparingly; CSS is generally preferred for controlling spacing and layout.
        *   Useful for addresses or poetry where line division is significant.
    *   Horizontal Rules (`<hr>`): Defines a thematic break in an HTML page, often displayed as a horizontal line.
        *   An empty/void element.
        *   Used to separate content sections.
    *   **Example:**
        ```html
        <p>First line of address.<br>Second line of address.</p>
        <hr>
        <p>New section starts here.</p>
        ```
    *   <YouTube videoId="thYtW5hN0o" title="HTML br and hr tags by Tutorialspoint" />

*   **Lesson 1.10: Comments in HTML**
    *   Purpose of comments: Add notes for developers, explain code, or temporarily remove code without deleting it.
    *   Comments are ignored by the browser and not displayed on the webpage.
    *   Syntax: `<!-- This is an HTML comment -->`
    *   Multi-line comments are possible using the same syntax.
    *   **Example:**
        ```html
        <!-- This section is for the main navigation -->
        <nav>...</nav>
        <!-- <p>This paragraph is temporarily hidden.</p> -->
        ```
    *   Best practices for writing useful comments.
    *   <YouTube videoId="A9cGXOTO2QE" title="HTML Comments - How to Write Comments in HTML by HTML Tutorial - Telusko" />

*   **Lesson 1.11: HTML Lists - Unordered, Ordered, and Description Lists**
    *   **Unordered Lists (`<ul>`):** Creates a bulleted list.
        *   List items are defined with `<li>` (list item) tags.
        *   **Example:**
            ```html
            <ul>
                <li>Apples</li>
                <li>Bananas</li>
                <li>Oranges</li>
            </ul>
            ```
    *   **Ordered Lists (`<ol>`):** Creates a numbered list.
        *   List items also use `<li>` tags.
        *   `type` attribute for different numbering styles (`1`, `A`, `a`, `I`, `i`).
        *   `start` attribute to begin numbering from a specific value.
        *   `reversed` attribute to reverse the numbering.
        *   **Example:** `<ol type="A" start="3"><li>Step C</li><li>Step D</li></ol>`
    *   **Description Lists (`<dl>`):** Creates a list of terms and their descriptions.
        *   `<dt>` (description term).
        *   `<dd>` (description details).
        *   **Example:** `<dl><dt>HTML</dt><dd>HyperText Markup Language</dd></dl>`
    *   Nesting lists within other lists (e.g., a `ul` inside an `li` of another `ul`).
    *   <YouTube videoId="09oErColl_c" title="HTML Lists - UL, OL, and DL by Dev Ed" /> (Recap)
    *   <YouTube videoId="WD3002Gq2A" title="HTML Lists Tutorial - Unordered, Ordered, and Definition Lists by ProgrammingKnowledge" />

*   **Lesson 1.12: HTML Links (Anchor Tags) - Absolute and Relative URLs**
    *   The `<a>` (anchor) tag: Defines hyperlinks.
    *   The `href` attribute: Specifies the URL of the page the link goes to.
    *   **Absolute URLs:** Full web address (e.g., `https://www.example.com/page.html`). Used for linking to external websites.
    *   **Relative URLs:** Path relative to the current page or site root. Used for linking to pages within the same website.
        *   Same directory: `contact.html`
        *   Subdirectory: `products/product1.html`
        *   Parent directory: `../about.html`
        *   Root relative: `/css/style.css` (starts from the site root).
    *   The `target` attribute:
        *   `_self`: Opens the link in the same window/tab (default).
        *   `_blank`: Opens the link in a new window/tab.
        *   `_parent`, `_top` (for frames, less common now).
    *   Link text (the visible part of the link). Best practices for accessible link text.
    *   <YouTube videoId="4d3s_N7uLtw" title="HTML Links & Images Tutorial by The Net Ninja" /> (Focus on links part)
    *   <YouTube videoId="QMiVn8G0oXA" title="HTML Links - Absolute vs Relative URLs by Kevin Powell" />

*   **Lesson 1.13: HTML Links - Linking to Page Sections (Anchors) and Email/Telephone Links**
    *   **Linking to Sections within the Same Page (Fragment Identifiers):**
        *   Create an `id` attribute on the target element: `<h2 id="section2">Section 2</h2>`
        *   Link to it using `#id_name`: `<a href="#section2">Jump to Section 2</a>`
    *   **Email Links (`mailto:`):**
        *   `href="mailto:email@example.com"`
        *   Can include subject and body: `href="mailto:info@example.com?subject=Inquiry&body=Hello there,"` (URL encoding for spaces and special characters might be needed).
    *   **Telephone Links (`tel:`):**
        *   `href="tel:+1234567890"` (Opens the dialer on mobile devices).
    *   The `title` attribute for links (provides advisory information, often appears as a tooltip).
    *   The `download` attribute (suggests the browser download the linked resource).
    *   <YouTube videoId="k0HL0q4gwjw" title="HTML Links - mailto, tel, and more! by Envato Tuts+" />
    *   <YouTube videoId_ HTML_DOWNLOAD_ATTRIBUTE_by_W3Schools title="HTML Download Attribute by W3Schools" /> (Placeholder: W3Schools usually has good short explanations)

*   **Lesson 1.14: HTML Images - `<img>` Tag, `src`, `alt`, `width`, `height` Attributes**
    *   The `<img>` tag: Embeds an image in an HTML page (empty/void element).
    *   The `src` attribute: Specifies the path (URL) to the image file.
        *   Can be relative or absolute.
    *   The `alt` attribute: Provides alternative text for an image.
        *   **Crucial for accessibility** (screen readers read it).
        *   Displayed if the image cannot be loaded.
        *   Good for SEO.
        *   **Always include meaningful alt text.** If an image is purely decorative, use `alt=""`.
    *   The `width` and `height` attributes: Specify the image dimensions in pixels.
        *   Can be used to reserve space for the image, preventing layout shifts.
        *   However, CSS is generally preferred for responsive image sizing.
    *   Common image formats for the web: JPEG (photos), PNG (transparency, graphics), GIF (animations), SVG (scalable vector graphics), WebP (modern, efficient).
    *   **Example:** `<img src="images/logo.png" alt="Company Logo" width="150" height="75">`
    *   <YouTube videoId="4d3s_N7uLtw" title="HTML Links & Images Tutorial by The Net Ninja" /> (Focus on images part)
    *   <YouTube videoId="SRY1c0k8XgE" title="HTML Images - Everything You Need to Know by Kevin Powell" />

*   **Lesson 1.15: Introduction to Semantic HTML - Writing Meaningful Markup**
    *   What is Semantic HTML? Using HTML tags that accurately describe the meaning and structure of the content, rather than just its presentation.
    *   Benefits:
        *   **Accessibility:** Helps screen readers and assistive technologies understand the page structure.
        *   **SEO (Search Engine Optimization):** Helps search engines better index content.
        *   **Maintainability:** Makes code easier to read and understand for developers.
        *   **Clarity:** Provides a clear outline of the page content.
    *   Examples of Semantic Elements (introduced in HTML5):
        *   `<header>`: Introductory content for a page or section.
        *   `<nav>`: Navigation links.
        *   `<main>`: The main content of the document (should be unique per page).
        *   `<article>`: Self-contained content that could be distributed independently (e.g., blog post, news article, forum post).
        *   `<section>`: A thematic grouping of content, typically with a heading.
        *   `<aside>`: Content tangentially related to the main content (e.g., sidebar, pull quotes, author bio).
        *   `<footer>`: Footer content for a page or section (copyright, contact info, related links).
        *   `<figure>` and `<figcaption>`: For images, diagrams, code snippets, etc., with an associated caption.
        *   `<time>`: For representing dates and times in a machine-readable format.
        *   `<address>`: For contact information.
    *   Using `<div>` and `<span>` for non-semantic grouping (when no specific semantic element applies, often for styling purposes).
    *   <YouTube videoId="k_AlE6E160c" title="Semantic HTML5 Elements Explained by freeCodeCamp.org" />
    *   <YouTube videoId="T7gKZA22jHY" title="Why Semantic HTML is Important by Kevin Powell" />

---
### Module 2: Advanced HTML & Introduction to CSS (Expanded)

This module covers more advanced HTML concepts like tables and forms, and then introduces CSS for styling web pages, with expanded detail.

*   **Lesson 2.1: HTML Tables - Structure (`<table>`, `<tr>`, `<th>`, `<td>`)**
    *   Purpose of HTML tables: To present tabular data in rows and columns.
    *   Basic Table Structure:
        *   `<table>`: Defines the table.
        *   `<tr>`: Defines a table row.
        *   `<th>`: Defines a table header cell (typically bold and centered by default). Used for column or row titles.
        *   `<td>`: Defines a table data cell (standard content cell).
    *   **Example:**
        ```html
        <table>
            <tr>
                <th>First Name</th>
                <th>Last Name</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>John</td>
                <td>Doe</td>
                <td>john.doe@example.com</td>
            </tr>
            <tr>
                <td>Jane</td>
                <td>Smith</td>
                <td>jane.smith@example.com</td>
            </tr>
        </table>
        ```
    *   Importance of using tables for data, not for page layout (use CSS for layout).
    *   <YouTube videoId="htC0Mrn_h7M" title="HTML Tables Crash Course by Traversy Media" /> (Recap)

*   **Lesson 2.2: HTML Tables - Captions, Headers, Footers, and Grouping (`<caption>`, `<thead>`, `<tbody>`, `<tfoot>`)**
    *   `<caption>`: Provides a title or caption for the table. Should be the first child of `<table>`.
    *   `<thead>`: Groups header content in an HTML table. Contains `<tr>` elements with `<th>` cells.
    *   `<tbody>`: Groups the main body content in an HTML table. Contains `<tr>` elements with `<td>` (and sometimes `<th>` for row headers).
    *   `<tfoot>`: Groups footer content in an HTML table. Useful for sums or summary information.
    *   These elements help structure the table semantically and can assist browsers in scrolling or printing large tables.
    *   **Example:**
        ```html
        <table>
            <caption>Monthly Sales Figures</caption>
            <thead>
                <tr>
                    <th>Month</th>
                    <th>Revenue</th>
                    <th>Expenses</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>January</td>
                    <td>$10,000</td>
                    <td>$6,000</td>
                </tr>
                <!-- more rows -->
            </tbody>
            <tfoot>
                <tr>
                    <td>Total</td>
                    <td>$X,XXX</td> <!-- Calculated value -->
                    <td>$Y,YYY</td> <!-- Calculated value -->
                </tr>
            </tfoot>
        </table>
        ```
    *   <YouTube videoId="I1vIhGSCYw" title="HTML Tables - thead, tbody, tfoot, and caption by Kevin Powell" />

*   **Lesson 2.3: HTML Tables - Spanning Rows and Columns (`rowspan`, `colspan`)**
    *   `colspan` attribute (on `<th>` or `<td>`): Specifies how many columns a cell should span (merge horizontally).
        *   **Example:** `<th colspan="2">Contact Details</th>`
    *   `rowspan` attribute (on `<th>` or `<td>`): Specifies how many rows a cell should span (merge vertically).
        *   **Example:** `<td rowspan="2">Shared Task</td>`
    *   Careful planning is needed when using `rowspan` and `colspan` to maintain table structure.
    *   Complex table layouts using these attributes.
    *   <YouTube videoId="ORr4pLeQ0A" title="HTML Table Colspan & Rowspan Explained by Dev Ed" />

*   **Lesson 2.4: HTML Forms - Introduction and the `<form>` Element**
    *   Purpose of HTML forms: To collect user input.
    *   The `<form>` element: Container for different types of input elements.
    *   Key `<form>` attributes:
        *   `action`: Specifies the URL where the form data should be submitted (e.g., a server-side script or API endpoint).
        *   `method`: Specifies the HTTP method to use when submitting the form:
            *   `GET`: Appends form data to the URL (visible, limited size, good for search forms).
            *   `POST`: Sends form data in the HTTP request body (more secure for sensitive data, no size limit).
        *   `name`: Names the form (useful for JavaScript access).
        *   `target`: Specifies where to display the response after submitting (e.g., `_blank`).
        *   `enctype`: Specifies how form data should be encoded when `method="POST"` (e.g., `application/x-www-form-urlencoded` (default), `multipart/form-data` for file uploads, `text/plain`).
        *   `novalidate`: Disables default browser validation.
    *   <YouTube videoId="fNcJuPIZ2WE" title="HTML Forms - Input Types & Attributes by Dev Ed" /> (Focus on `<form>` element)
    *   <YouTube videoId_ HTML_FORM_ATTRIBUTES_ACTION_METHOD_ENCTYPE_by_W3Schools title="HTML Form Attributes (action, method, enctype) by W3Schools" /> (Placeholder: W3Schools often has concise explanations)

*   **Lesson 2.5: Basic Input Elements - Text, Password, Submit, Reset**
    *   The `<input>` tag: The most versatile form element, type is defined by the `type` attribute.
    *   `<input type="text">`: For single-line text input.
        *   Common attributes: `name` (essential for submission), `id` (for labels), `value` (initial/default value), `placeholder` (hint text), `size` (visible width in characters), `maxlength` (max characters allowed), `required` (must be filled), `readonly` (cannot be changed), `disabled` (cannot be interacted with).
    *   `<input type="password">`: Similar to text, but characters are masked.
    *   `<input type="submit">`: A button that submits the form data to the server (specified in `action`).
        *   `value` attribute defines the button text (e.g., "Login", "Send").
    *   `<input type="reset">`: A button that resets all form fields within the same `<form>` to their initial values.
    *   The `<label>` element: Associates text with a form control for better usability and accessibility.
        *   Using the `for` attribute on `<label>` to link to the `id` of an input element. Clicking the label focuses the input.
        *   Implicitly associating by wrapping the input: `<label>Username: <input type="text" name="username"></label>`
        *   **Example:** `<label for="username">Username:</label> <input type="text" id="username" name="username">`
    *   <YouTube videoId="YwbIeMlxZAU" title="HTML Forms In Depth - More Input Types & Attributes by Traversy Media" /> (Focus on these basic types)
    *   <YouTube videoId_ HTML_LABEL_ELEMENT_FOR_ACCESSIBILITY_by_Kevin_Powell title="HTML Label Element for Accessibility by Kevin Powell" /> (Placeholder: Kevin Powell is great for accessibility)

*   **Lesson 2.6: Radio Buttons and Checkboxes**
    *   `<input type="radio">`: Allows the user to select only one option from a group.
        *   All radio buttons in a group must have the same `name` attribute. This links them.
        *   Each radio button has a unique `value` attribute, which is sent if that option is selected.
        *   `checked` attribute to pre-select an option.
        *   **Example:**
            ```html
            <p>Preferred Contact Method:</p>
            <input type="radio" id="contact_email" name="contact_method" value="email" checked>
            <label for="contact_email">Email</label><br>
            <input type="radio" id="contact_phone" name="contact_method" value="phone">
            <label for="contact_phone">Phone</label>
            ```
    *   `<input type="checkbox">`: Allows the user to select zero, one, or multiple options.
        *   Each checkbox typically has its own `name` attribute if they represent different boolean flags. If they are part of a group of choices for the same category, they might share a `name` (backend processing would handle this as an array).
        *   `value` attribute (sent if checked).
        *   `checked` attribute to pre-select.
        *   **Example:**
            ```html
            <p>Interests:</p>
            <input type="checkbox" id="interest_coding" name="interests_coding" value="coding">
            <label for="interest_coding">Coding</label><br>
            <input type="checkbox" id="interest_design" name="interests_design" value="design" checked>
            <label for="interest_design">Design</label>
            ```
    *   <YouTube videoId="QRrT7h9-KI" title="HTML Radio Buttons & Checkboxes by The Net Ninja" />
    *   <YouTube videoId_ ACCESSIBLE_RADIO_BUTTONS_AND_CHECKBOXES_by_Web_Dev_Simplified title="Accessible Radio Buttons and Checkboxes by Web Dev Simplified" /> (Placeholder: WDS is good for practical examples)

*   **Lesson 2.7: The `<button>` Element and File Uploads**
    *   The `<button>` element: A more flexible button than `<input type="button">` or `<input type="submit">`.
        *   Can contain HTML content (e.g., text, images, icons). This is its main advantage.
        *   `type` attribute:
            *   `submit`: Submits the form data (default if inside a form).
            *   `reset`: Resets form fields.
            *   `button`: A clickable button with no default behavior (typically used with JavaScript).
        *   **Example:** `<button type="submit"><img src="icon.png" alt=""> <strong>Send</strong> Application</button>`
    *   `<input type="file">`: Allows users to select one or more files from their device to be uploaded.
        *   `accept` attribute to suggest acceptable file types to the browser (e.g., `image/*`, `.pdf`, `audio/mp3`). This is a hint, not a security measure.
        *   `multiple` attribute to allow multiple file selection.
        *   Requires `method="POST"` and `enctype="multipart/form-data"` on the `<form>` element for actual file upload to a server.
        *   Styling file inputs can be tricky and often requires CSS workarounds.
    *   <YouTube videoId="0M9u0qSqFg" title="The HTML Button Element by Kevin Powell" />
    *   <YouTube videoId="Wg97n6c5V0" title="HTML File Upload Tutorial by codeanform" />
    *   <YouTube videoId_ STYLING_HTML_FILE_INPUTS_by_CSS_Tricks title="Styling HTML File Inputs by CSS-Tricks" /> (Placeholder: CSS-Tricks is a go-to resource)

*   **Lesson 2.8: Dropdown Lists (`<select>`, `<option>`, `<optgroup>`)**
    *   `<select>`: Creates a dropdown list (also known as a combo box).
        *   `name` attribute for form submission.
        *   `id` attribute for label association.
        *   `multiple` attribute to allow multiple selections (usually changes rendering to a list box).
        *   `size` attribute to specify the number of visible options (if > 1, often renders as a list box).
        *   `required`, `disabled` attributes.
    *   `<option>`: Defines an option within the select list.
        *   `value` attribute: The value sent to the server when this option is selected. If omitted, the text content of the option is used.
        *   Content between `<option>` tags is the displayed text for the user.
        *   `selected` attribute to pre-select an option.
        *   `disabled` attribute to make an option unselectable.
    *   `<optgroup>`: Groups related options within a select list.
        *   `label` attribute for the group title (displayed but not selectable).
        *   `disabled` attribute to disable all options within the group.
    *   **Example:**
        ```html
        <label for="department">Department:</label>
        <select id="department" name="department">
            <option value="">--Please choose an option--</option> <!-- Placeholder option -->
            <optgroup label="Sales & Marketing">
                <option value="sales_na">Sales (North America)</option>
                <option value="marketing_eu">Marketing (Europe)</option>
            </optgroup>
            <optgroup label="Engineering">
                <option value="dev_frontend">Frontend Development</option>
                <option value="dev_backend">Backend Development</option>
            </optgroup>
            <option value="hr" disabled>Human Resources (Coming Soon)</option>
        </select>
        ```
    *   <YouTube videoId="kL0o3P-0gY" title="HTML Select Dropdown List - <select>, <option>, <optgroup> by The Net Ninja" />
    *   <YouTube videoId_ ACCESSIBLE_DROPDOWN_LISTS_HTML_SELECT_by_A11ycasts title="Accessible Dropdown Lists (HTML Select) by A11ycasts (Google Chrome Developers)" /> (Placeholder: A11ycasts for accessibility)

*   **Lesson 2.9: Text Areas (`<textarea>`) and Grouping Form Elements (`<fieldset>`, `<legend>`)**
    *   `<textarea>`: Defines a multi-line text input control (for longer text like comments or messages).
        *   `name`, `id` attributes.
        *   `rows` attribute: Specifies the visible number of text lines.
        *   `cols` attribute: Specifies the visible width in average character widths.
        *   Content between `<textarea>` and `</textarea>` tags is the default text.
        *   `placeholder`, `maxlength`, `required`, `readonly`, `disabled`, `wrap` (`soft`, `hard`, `off`) attributes.
    *   `<fieldset>`: Groups related elements in a form, visually and semantically. Often rendered with a border.
    *   `<legend>`: Defines a caption or title for the `<fieldset>` element. It should be the first child of the `<fieldset>`.
    *   **Example:**
        ```html
        <fieldset>
            <legend>Contact Information</legend>
            <label for="email">Email:</label> <input type="email" id="email" name="email"><br>
            <label for="phone">Phone:</label> <input type="tel" id="phone" name="phone">
        </fieldset>
        <fieldset>
            <legend>Your Message</legend>
            <textarea id="message" name="message" rows="5" cols="30"></textarea>
        </fieldset>
        ```
    *   <YouTube videoId="N0weVpQ-a0" title="HTML Textarea, Fieldset & Legend by The Net Ninja" />
    *   <YouTube videoId_ HTML_FIELDSET_AND_LEGEND_FOR_FORM_ACCESSIBILITY_by_Deque_Systems title="HTML Fieldset and Legend for Form Accessibility by Deque Systems" /> (Placeholder: Deque for accessibility)

*   **Lesson 2.10: HTML5 Data-Related Elements (`<datalist>`, `<output>`, `<progress>`, `<meter>`)**
    *   `<datalist>`: Specifies a list of pre-defined options for an `<input>` element. Provides autocomplete/suggestion functionality.
        *   The `<input>` element's `list` attribute must refer to the `id` of the `<datalist>`.
        *   Each option within `<datalist>` is defined by an `<option>` tag with a `value`.
        *   **Example:** `<input list="browsers" name="browser"><datalist id="browsers"><option value="Chrome"><option value="Firefox"></datalist>`
    *   `<output>`: Represents the result of a calculation or user action.
        *   `for` attribute can link it to the IDs of elements involved in the calculation.
        *   `name` attribute.
        *   Often updated using JavaScript.
    *   `<progress>`: Represents the completion progress of a task.
        *   `value` attribute (current progress).
        *   `max` attribute (total work required).
        *   Indeterminate state if `value` is omitted.
    *   `<meter>`: Represents a scalar measurement within a known range (a gauge).
        *   `value`, `min`, `max`, `low`, `high`, `optimum` attributes.
        *   Visually distinct from `<progress>`.
    *   <YouTube videoId="8ImzL2tvNqA" title="HTML5 Datalist Element by Academind" />
    *   <YouTube videoId="CPhXk1qC8M" title="HTML5 Progress & Meter Elements by DesignCourse" />

*   **Lesson 2.11: HTML5 Input Attributes for Enhanced Forms**
    *   `autocomplete`: Controls whether browsers can automatically complete input fields (on/off, or specific tokens like "name", "email", "tel").
    *   `autofocus`: Automatically focuses an input field when the page loads. Use sparingly.
    *   `form`: Associates an input field with a form, even if the input is outside the `<form>` tags (value is the `id` of the form).
    *   `formaction`, `formmethod`, `formenctype`, `formnovalidate`, `formtarget`: Override the corresponding attributes of the parent `<form>` element, specifically for a submit button.
    *   `list`: (Covered with `<datalist>`).
    *   `multiple`: (Covered with `email`, `file`, `select`).
    *   `pattern`: (Covered with validation).
    *   `placeholder`: (Covered).
    *   `readonly`: (Covered).
    *   `required`: (Covered).
    *   `step`: (Covered with `type="number"` and `type="range"`).
    *   <YouTube videoId="LHFhwjId8I" title="HTML5 Form Input Attributes by ProgrammingKnowledge" />
    *   <YouTube videoId_ HTML5_NEW_FORM_ATTRIBUTES_OVERVIEW_by_MDN_Web_Docs title="HTML5 New Form Attributes Overview by MDN Web Docs" /> (Placeholder: MDN is authoritative)

*   **Lesson 2.12: Introduction to CSS - Selectors, Properties, Values**
    *   Recap CSS Syntax: `selector { property: value; }`
    *   Understanding Selectors more deeply:
        *   What they target (HTML elements).
        *   Their role in connecting HTML structure to CSS rules.
    *   Understanding Properties:
        *   The aspect of the element you want to change (e.g., `color`, `font-size`, `background-color`, `width`, `margin`).
        *   CSS has hundreds of properties.
    *   Understanding Values:
        *   The specific setting for a property (e.g., `red`, `16px`, `#FFFFFF`, `100px`, `10px auto`).
        *   Different properties accept different types of values (keywords, lengths, colors, percentages, URLs, etc.).
    *   The "Cascade" in CSS: How conflicting style rules are resolved. Order of precedence:
        1.  Inline styles.
        2.  ID selectors.
        3.  Class selectors, attribute selectors, pseudo-classes.
        4.  Type selectors, pseudo-elements.
        5.  Universal selector (`*`), inherited values.
        *   `!important` rule (use with extreme caution, generally avoid).
        *   Specificity calculations (a more formal way to determine precedence).
    *   Inheritance: Some CSS properties are inherited by child elements from their parents (e.g., `color`, `font-family`), while others are not (e.g., `border`, `padding`).
    *   <YouTube videoId="yfoY53QXEnI" title="CSS Crash Course For Absolute Beginners by Traversy Media" /> (Recap with more context)
    *   <YouTube videoId="6Q7gK3ikf0" title="CSS Specificity Explained by Kevin Powell" />
    *   <YouTube videoId="P0a9h2uA0" title="CSS Inheritance Explained by Kevin Powell" />

*   **Lesson 2.13: CSS Units - Absolute and Relative Lengths**
    *   **Absolute Units:** Fixed and will not change based on other elements.
        *   `px` (pixels): Most common absolute unit. 1px = 1/96th of an inch.
        *   `pt` (points): 1pt = 1/72nd of an inch (common in print).
        *   `cm`, `mm`, `in` (centimeters, millimeters, inches): For print or physical measurements.
        *   `pc` (picas): 1pc = 12pt.
    *   **Relative Units:** Value is relative to another length property. More flexible for responsive design.
        *   `%` (percentage): Relative to the same property of the parent element (e.g., `width: 50%` is half the parent's width).
        *   `em`: Relative to the `font-size` of the current element. If used for `font-size` itself, it's relative to the parent's `font-size`. Can compound.
        *   `rem` (root em): Relative to the `font-size` of the root (`<html>`) element. Preferred for font sizes for easier global scaling and avoiding compounding issues.
        *   `vw` (viewport width): 1vw = 1% of the viewport width.
        *   `vh` (viewport height): 1vh = 1% of the viewport height.
        *   `vmin`, `vmax`: Relative to the smaller or larger of viewport width/height.
        *   `ch` (character width): Relative to the width of the "0" (zero) character in the current font.
        *   `ex` (x-height): Relative to the x-height of the current font.
    *   Choosing appropriate units for different properties (e.g., `rem` for fonts, `%` or `vw` for layouts, `px` for borders).
    *   <YouTube videoId="1xoKqcnY7oY" title="CSS Colors, Backgrounds, and Units by Kevin Powell" /> (Focus on Units part)
    *   <YouTube videoId="N5EaKFKqMXA" title="CSS Units - px, em, rem, vw, vh and more explained by Web Dev Simplified" />

*   **Lesson 2.14: CSS Selectors - Combinators (Descendant, Child, Sibling)**
    *   **Descendant Combinator (space):** Selects elements that are descendants of a specified element (any level down).
        *   **Example:** `div p { color: blue; }` (selects all `<p>` elements inside any `<div>`).
    *   **Child Combinator (`>`):** Selects elements that are direct children of a specified element (only one level down).
        *   **Example:** `ul > li { list-style-type: square; }` (selects `<li>` elements that are direct children of a `<ul>`).
    *   **Adjacent Sibling Combinator (`+`):** Selects an element that is immediately preceded by a specified element (must be siblings and adjacent).
        *   **Example:** `h1 + p { margin-top: 0; }` (selects the first `<p>` that immediately follows an `<h1>`).
    *   **General Sibling Combinator (`~`):** Selects elements that are siblings of a specified element and come after it (don't have to be immediately adjacent).
        *   **Example:** `h2 ~ p { text-decoration: underline; }` (selects all `<p>` elements that are siblings of and follow an `<h2>`).
    *   Combining these with type, class, and ID selectors.
    *   <YouTube videoId="0zSj0m1r0E" title="CSS Combinators (Descendant, Child, Adjacent Sibling, General Sibling) by Kevin Powell" />

*   **Lesson 2.15: CSS Selectors - Attribute Selectors and Pseudo-Classes (Basic)**
    *   **Attribute Selectors:** Select elements based on the presence or value of their attributes.
        *   `[attribute]`: Selects elements with a specific attribute, regardless of its value.
            *   **Example:** `a[target] { background-color: yellow; }` (selects `<a>` tags with a `target` attribute).
        *   `[attribute=value]`: Selects elements with a specific attribute and value.
            *   **Example:** `input[type="text"] { border: 1px solid gray; }`
        *   `[attribute~=value]`: Selects elements where the attribute value is a space-separated list containing a specific value.
        *   `[attribute|=value]`: Selects elements where the attribute value starts with a specific value followed by a hyphen (e.g., `lang="en-us"`).
        *   `[attribute^=value]`: Selects elements where the attribute value starts with a specific value.
        *   `[attribute$=value]`: Selects elements where the attribute value ends with a specific value.
        *   `[attribute*=value]`: Selects elements where the attribute value contains a specific value.
    *   **Basic Pseudo-Classes:** Select elements based on their state or position (more in a later module).
        *   Link states: `:link` (unvisited link), `:visited` (visited link).
        *   User action states: `:hover` (mouse over), `:active` (being clicked), `:focus` (has keyboard focus).
        *   **Example:** `a:hover { color: red; text-decoration: none; }`
        *   Input states: `:checked` (for checkboxes/radio), `:disabled`, `:enabled`, `:required`, `:optional`.
    *   <YouTube videoId="FQdaUv95mR8" title="CSS Selectors - Every CSS Selector Explained by Web Dev Simplified" /> (Revisit for Attribute and basic Pseudo-classes)
    *   <YouTube videoId_ CSS_ATTRIBUTE_SELECTORS_by_The_Net_Ninja title="CSS Attribute Selectors by The Net Ninja" /> (Placeholder: The Net Ninja has good selector videos)
    *   <YouTube videoId_ CSS_PSEUDO_CLASSES_HOVER_FOCUS_ACTIVE_by_Kevin_Powell title="CSS Pseudo-Classes (hover, focus, active) by Kevin Powell" /> (Placeholder: Kevin Powell for pseudo-classes)

---
### Module 3: CSS Box Model, Typography, and Layout Basics (Expanded)

This module delves into the CSS Box Model, text styling, and fundamental CSS layout techniques, with more comprehensive coverage.

*   **Lesson 3.1: The CSS Box Model - Content, Padding, Border, Margin**
    *   Every HTML element is a rectangular box.
    *   Understanding the four components of the box model:
        *   **Content:** The actual content of the box (text, images, etc.). Its dimensions are defined by `width` and `height` properties.
        *   **Padding:** Transparent area around the content, inside the border. Clears an area around the content.
            *   `padding-top`, `padding-right`, `padding-bottom`, `padding-left`.
            *   Shorthand: `padding: top right bottom left;` (e.g., `padding: 10px 20px 10px 20px;`).
            *   Two-value shorthand: `padding: top/bottom right/left;` (e.g., `padding: 10px 20px;`).
            *   One-value shorthand: `padding: all_four_sides;` (e.g., `padding: 10px;`).
        *   **Border:** A line that goes around the padding and content.
            *   `border-width`, `border-style` (solid, dashed, dotted, double, groove, ridge, inset, outset, none, hidden), `border-color`.
            *   Shorthand: `border: width style color;` (e.g., `border: 1px solid black;`).
            *   Individual side borders: `border-top-style`, `border-left-width`, `border-bottom-color`, etc.
            *   `border-radius` for rounded corners.
        *   **Margin:** Transparent area outside the border. Clears an area around the element, separating it from other elements.
            *   `margin-top`, `margin-right`, `margin-bottom`, `margin-left`.
            *   Shorthand properties similar to padding.
            *   `margin: auto;` for horizontal centering of block elements with a defined width.
    *   Visualizing the box model using browser developer tools (Elements panel > Computed tab).
    *   <YouTube videoId="rIO532_iZc0" title="The CSS Box Model Explained by Traversy Media" /> (Recap)
    *   <YouTube videoId="s_n0kOy1nUw" title="CSS Box Model - A Deep Dive by Kevin Powell" />

*   **Lesson 3.2: `width`, `height`, `min-width`, `max-width`, `min-height`, `max-height`**
    *   `width` and `height` properties: Define the width and height of the content area of an element (by default, see `box-sizing`).
        *   Values: `px`, `%` (of containing block's width/height), `em`, `rem`, `vw`, `vh`, `auto` (default, browser calculates).
    *   `min-width` and `max-width`: Constrain the width of an element.
        *   `min-width`: Element can be wider but not narrower. Useful for preventing content from becoming too squished.
        *   `max-width`: Element can be narrower but not wider (very useful for responsive images and fluid layouts, e.g., `img { max-width: 100%; height: auto; }`).
    *   `min-height` and `max-height`: Constrain the height of an element.
    *   How these interact with padding, border, and content, especially with different `box-sizing` values.
    *   **Example:** Creating a responsive container: `div { width: 90%; max-width: 960px; margin: 0 auto; }`
    *   <YouTube videoId="zNPNgRF940A" title="CSS min-width, max-width, min-height, max-height by Web Dev Simplified" />
    *   <YouTube videoId_ CSS_DIMENSION_PROPERTIES_by_DesignCourse title="CSS Dimension Properties (width, height, min/max) by DesignCourse" /> (Placeholder: DesignCourse often has good visual explanations)

*   **Lesson 3.3: The `box-sizing` Property (`content-box` vs. `border-box`)**
    *   `content-box` (default): The `width` and `height` properties apply only to the content area. Padding and border are added *outside* this width/height, making the element visually larger.
        *   Total width = `width` + `padding-left` + `padding-right` + `border-left-width` + `border-right-width`.
    *   `border-box`: The `width` and `height` properties include the content, padding, and border. Padding and border are drawn *inside* the specified width/height.
        *   This model is often more intuitive for layout, as setting `width: 200px;` means the element will be exactly 200px wide on screen, regardless of padding/border.
    *   **Common best practice (Paul Irish reset):** Apply `border-box` globally:
        ```css
        html {
          box-sizing: border-box;
        }
        *, *::before, *::after { /* Selects all elements, including pseudo-elements */
          box-sizing: inherit; /* Makes all elements inherit box-sizing from their parent, ultimately from html */
        }
        ```
    *   Understanding how `box-sizing` affects layout calculations and simplifies responsive design.
    *   <YouTube videoId="0q4E1n0xYgE" title="CSS Box Sizing (content-box vs border-box) Explained by Kevin Powell" />
    *   <YouTube videoId_ WHY_BORDER_BOX_IS_AWESOME_by_CSS_Tricks_Chris_Coyier title="Why Border-Box is Awesome by CSS-Tricks (Chris Coyier)" /> (Placeholder: Chris Coyier's articles are seminal)

*   **Lesson 3.4: Margin Collapsing - Understanding Vertical Margins**
    *   What is Margin Collapsing? When the top and/or bottom margins of adjacent block-level elements combine (collapse) into a single margin whose size is the largest of the individual margins (or largest of positive and smallest of negative if negative margins are involved).
    *   Rules for margin collapsing:
        *   **Adjacent siblings:** Bottom margin of the first collapses with the top margin of the second.
        *   **Parent and first/last child:** If there is no border, padding, inline content, height, min-height, max-height, or clearance separating the parent's margin from its first/last child's margin, then their margins collapse.
        *   **Empty blocks:** Top and bottom margins of an empty block (with no border, padding, height, or content) may collapse with each other.
    *   Horizontal margins do not collapse.
    *   How padding or borders on the parent can prevent parent-child margin collapsing.
    *   This can be confusing but is important for predicting vertical spacing. Using DevTools to inspect computed margins can help.
    *   <YouTube videoId="H54MJ3gU0A" title="Understanding Margin Collapse in CSS by Kevin Powell" />
    *   <YouTube videoId_ MARGIN_COLLAPSING_IN_CSS_EXPLAINED_by_Web_Dev_Simplified title="Margin Collapsing in CSS Explained by Web Dev Simplified" /> (Placeholder: WDS for clear explanations)

*   **Lesson 3.5: CSS Typography - `font-family` and Web Safe Fonts**
    *   `font-family`: Specifies a prioritized list of font family names and/or generic family names for an element.
    *   **Font Stacks:** Listing multiple fonts, separated by commas. The browser will use the first font in the list that it has installed or can access.
        *   Always end with a generic font family as a fallback.
    *   **Generic Font Families:**
        *   `serif`: Fonts with serifs (small strokes at the ends of characters, e.g., Times New Roman, Georgia).
        *   `sans-serif`: Fonts without serifs (e.g., Arial, Helvetica, Verdana).
        *   `monospace`: Fonts where all characters have the same fixed width (e.g., Courier New, Consolas). Used for code.
        *   `cursive`: Fonts that emulate handwriting (e.g., Comic Sans MS - use with caution, Brush Script MT).
        *   `fantasy`: Decorative/playful fonts (e.g., Impact).
        *   `system-ui`: Uses the default UI font of the operating system.
    *   **Web Safe Fonts:** Fonts commonly installed on most operating systems, ensuring consistent display.
        *   Examples: Arial, Verdana, Helvetica, Tahoma, Trebuchet MS, Times New Roman, Georgia, Garamond, Courier New, Brush Script MT.
    *   Quoting font names with spaces: `font-family: "Times New Roman", Times, serif;`
    *   <YouTube videoId="xR564C2hX0Y" title="CSS Typography - Crash Course by DesignCourse" /> (Focus on font-family)
    *   <YouTube videoId="XyE1f9lV8A" title="CSS Font Family and Web Safe Fonts by Kevin Powell" />

*   **Lesson 3.6: CSS Typography - `font-size`, `font-weight`, `font-style`, `font-variant`**
    *   `font-size`: Sets the size of the font.
        *   Units: `px`, `em`, `rem` (recommended for scalability), `%`, keywords (`xx-small`, `x-small`, `small`, `medium`, `large`, `x-large`, `xx-large`, `smaller`, `larger`).
    *   `font-weight`: Sets the boldness of the font.
        *   Values: `normal` (default, usually 400), `bold` (usually 700), `bolder`, `lighter`.
        *   Numeric values: `100` to `900` (multiples of 100). `400` is `normal`, `700` is `bold`. Availability of weights depends on the font family.
    *   `font-style`: Sets the style of the font.
        *   Values: `normal` (default), `italic`, `oblique` (a slanted version of the normal font, often browser-generated if true italic isn't available).
    *   `font-variant`: Controls variations like `small-caps`.
        *   `font-variant: small-caps;` (displays lowercase letters as smaller uppercase letters).
    *   The `font` shorthand property: `font: [font-style] [font-variant] [font-weight] [font-stretch] font-size[/line-height] font-family;` (Order matters, `font-size` and `font-family` are required).
    *   <YouTube videoId="sLGMn_isyk" title="CSS Font Size, Weight, and Style by Envato Tuts+" />
    *   <YouTube videoId_ CSS_FONT_SHORTHAND_PROPERTY_by_The_Net_Ninja title="CSS Font Shorthand Property by The Net Ninja" /> (Placeholder: The Net Ninja is good for shorthands)

*   **Lesson 3.7: CSS Typography - `text-align`, `text-decoration`, `text-transform`, `text-indent`**
    *   `text-align`: Specifies the horizontal alignment of text within an element.
        *   Values: `left` (default for LTR languages), `right` (default for RTL languages), `center`, `justify` (stretches lines so each line has equal width, use with care for readability, can create awkward spacing).
        *   Applies to block-level containers.
    *   `text-decoration`: Specifies decorations added to text.
        *   Shorthand for `text-decoration-line`, `text-decoration-color`, `text-decoration-style`, `text-decoration-thickness`.
        *   `text-decoration-line`: `none` (default), `underline`, `overline`, `line-through`.
        *   Often used to remove underlines from links: `a { text-decoration: none; }`
    *   `text-transform`: Controls the capitalization of text.
        *   Values: `none` (default), `capitalize` (first letter of each word), `uppercase` (all letters), `lowercase` (all letters).
    *   `text-indent`: Specifies the indentation of the first line of text in a block.
        *   Values: length (`px`, `em`, `%`). Can be negative for a hanging indent.
    *   <YouTube videoId_ CSS_TEXT_PROPERTIES_OVERVIEW_by_Programming_with_Mosh title="CSS Text Properties Overview by Programming with Mosh" /> (Placeholder: Mosh for concise overviews)
    *   <YouTube videoId_ TEXT_DECORATION_ADVANCED_CSS_by_Kevin_Powell title="Text Decoration Advanced CSS by Kevin Powell" /> (Placeholder: Kevin Powell for deep dives)

*   **Lesson 3.8: CSS Typography - `line-height`, `letter-spacing`, `word-spacing`, `white-space`**
    *   `line-height`: Specifies the height of a line box. Used to control the space between lines of text (leading).
        *   Values: `normal` (default, browser-dependent, usually around 1.2 to 1.5), unitless number (multiplies the element's font-size, e.g., `1.6`), length (`px`, `em`, `rem`), percentage (`%` of current font-size).
        *   Unitless numbers are generally recommended for scalability and predictability.
    *   `letter-spacing`: Increases or decreases the space between characters in text.
        *   Values: `normal` (default), length (`px`, `em`). Can be negative.
    *   `word-spacing`: Increases or decreases the space between words.
        *   Values: `normal` (default), length (`px`, `em`). Can be negative.
    *   `white-space`: Controls how whitespace inside an element is handled.
        *   Values: `normal` (collapses whitespace, wraps text), `nowrap` (prevents wrapping), `pre` (preserves whitespace like HTML `<pre>`), `pre-wrap` (preserves whitespace, but wraps), `pre-line` (collapses whitespace sequences, but preserves newlines).
    *   Using these properties to improve readability and aesthetics.
    *   <YouTube videoId="0YMrZiiHakA" title="CSS Line Height, Letter Spacing, Word Spacing by DesignCourse" /> (Check if this covers white-space too)
    *   <YouTube videoId_ CSS_WHITE_SPACE_PROPERTY_by_The_Net_Ninja title="CSS White Space Property by The Net Ninja" /> (Placeholder)

*   **Lesson 3.9: Using Web Fonts (`@font-face` and Google Fonts)**
    *   **Web Safe Fonts Recap:** Limited choices.
    *   **Web Fonts:** Allow you to use fonts that are not installed on the user's computer. The browser downloads the font file.
    *   **`@font-face` rule:** CSS rule to define your own custom fonts.
        *   Specify `font-family` name (you choose this for use in your CSS).
        *   `src`: URL to the font file(s) (`.woff2` (best compression), `.woff`, `.ttf`, `.otf`). Provide multiple formats for browser compatibility, `woff2` and `woff` are generally sufficient for modern browsers.
        *   `format()` hint for browsers.
        *   `font-weight`, `font-style`, `font-stretch`, `font-display` descriptors within `@font-face`.
        *   **Example:**
            ```css
            @font-face {
              font-family: 'MyCustomFont';
              src: url('mycustomfont.woff2') format('woff2'),
                   url('mycustomfont.woff') format('woff');
              font-weight: normal;
              font-style: normal;
            }
            ```
    *   **Google Fonts:** A popular free service for web fonts.
        *   Browse and select fonts on the Google Fonts website.
        *   Link to the font in your HTML `<head>`: `<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">`
        *   Or use `@import` in CSS: `@import url('https://fonts.googleapis.com/css2?family=Open+Sans&display=swap');` (generally, `<link>` is preferred for performance).
        *   Use the font name in your CSS `font-family` property: `font-family: 'Roboto', sans-serif;`
    *   `font-display` property (e.g., `swap`, `block`, `fallback`, `optional`): Controls how fonts are rendered while loading, impacting perceived performance and FOUT/FOIT.
    *   <YouTube videoId="sH35_f_h00" title="How to use Google Fonts & Custom Fonts with @font-face by Kevin Powell" />
    *   <YouTube videoId="wS-A2U73L8" title="Google Fonts Tutorial for Beginners by Traversy Media" />

*   **Lesson 3.10: The `display` Property - `block`, `inline`, `inline-block`, `none`**
    *   The `display` property controls how an element is rendered in the document flow and how it interacts with other elements.
    *   **`block`:**
        *   Starts on a new line and takes up the full width available by default.
        *   `width`, `height`, `margin` (top/bottom/left/right), `padding` properties apply.
        *   Examples: `<div>`, `<p>`, `<h1>`-`<h6>`, `<ul>`, `<li>`, `<form>`, `<header>`, `<footer>`, `<section>`.
    *   **`inline`:**
        *   Flows along with surrounding text/content, does not start on a new line.
        *   Takes up only as much width as necessary for its content.
        *   `width` and `height` properties do NOT apply.
        *   Vertical `margin` and `padding` (top/bottom) are respected but do not affect the layout of surrounding block elements (they might overlap). Horizontal `margin` and `padding` work as expected.
        *   Examples: `<span>`, `<a>`, `<img>` (behaves like inline but respects width/height by default - technically an "inline replaced element"), `<strong>`, `<em>`, `<b>`, `<i>`.
    *   **`inline-block`:**
        *   Flows along with surrounding text/content (like `inline`).
        *   BUT, `width`, `height`, `margin` (all sides), `padding` properties apply (like `block`).
        *   A hybrid, often useful for creating grid-like items that sit next to each other without forcing line breaks.
    *   `display: none;`: Hides the element completely (removed from document flow, takes up no space, not accessible to screen readers). Contrast with `visibility: hidden;`.
    *   <YouTube videoId="Qf-wdyxX7rA" title="CSS Display Property (inline, block, inline-block, none) by Kevin Powell" /> (Recap)
    *   <YouTube videoId="GFm_k5y0tQ" title="CSS Display Block vs Inline vs Inline-Block by Web Dev Simplified" />

*   **Lesson 3.11: The `visibility` and `opacity` Properties**
    *   `visibility` property:
        *   `visible` (default): The element is visible.
        *   `hidden`: The element is invisible, but it still takes up space in the layout (unlike `display: none;`). Its content is not accessible to screen readers typically.
        *   `collapse`: For table rows, columns, row groups, and column groups. If used on other elements, it often behaves like `hidden`.
    *   `opacity` property:
        *   Sets the opacity level for an element (how transparent it is).
        *   Value from `0.0` (fully transparent) to `1.0` (fully opaque).
        *   Affects the element and all its children.
        *   An element with `opacity: 0;` is invisible but still interactive (e.g., clickable) and takes up space.
    *   Differences and use cases for `display: none;`, `visibility: hidden;`, and `opacity: 0;`.
    *   <YouTube videoId="9L6M0N0V8I" title="display: none; VS visibility: hidden; VS opacity: 0; by The Net Ninja" />
    *   <YouTube videoId_ CSS_OPACITY_VS_RGBA_FOR_TRANSPARENCY_by_Traversy_Media title="CSS Opacity vs RGBA for Transparency by Traversy Media" /> (Placeholder: Traversy often covers practical differences)

*   **Lesson 3.12: CSS Positioning - `static`, `relative`**
    *   The `position` property sets how an element is positioned in a document.
    *   Offset properties (`top`, `right`, `bottom`, `left`) are used to specify the final location of positioned elements (for `relative`, `absolute`, `fixed`, `sticky`).
    *   **`static` (default):**
        *   The element is positioned according to the normal flow of the document.
        *   Offset properties (`top`, `right`, `bottom`, `left`) and `z-index` have no effect.
    *   **`relative`:**
        *   The element is positioned relative to its normal position in the document flow.
        *   Offset properties (`top`, `right`, `bottom`, `left`) will cause it to be adjusted away from its normal position, without affecting the layout of surrounding elements (space for it is still reserved in normal flow).
        *   Establishes a new positioning context for absolutely positioned child elements.
    *   **Example:** `<div style="position: relative; top: 10px; left: 20px; background: lightcoral;">This is shifted.</div><div style="background: lightblue;">Next element.</div>` (The lightblue div will not move up to fill the space left by the red div's shift).
    *   <YouTube videoId="jx5jmI0UlXU" title="CSS Position Property (Static, Relative, Absolute, Fixed, Sticky) by Traversy Media" /> (Focus on static, relative)

*   **Lesson 3.13: CSS Positioning - `absolute`, `fixed`**
    *   **`absolute`:**
        *   The element is removed from the normal document flow. No space is created for it in the page layout.
        *   It is positioned relative to its nearest *positioned* ancestor (an ancestor with `position` value other than `static` - i.e., `relative`, `absolute`, `fixed`, or `sticky`).
        *   If no positioned ancestor exists, it is positioned relative to the initial containing block (usually the `<html>` element/viewport).
        *   Offset properties (`top`, `right`, `bottom`, `left`) are used to place it.
        *   **Example:** A modal dialog overlaying the page content, or an icon placed at a specific corner of a card component.
    *   **`fixed`:**
        *   The element is removed from the normal document flow.
        *   It is positioned relative to the browser viewport (the visible window area).
        *   It stays in the same place even when the page is scrolled.
        *   Often used for fixed headers, footers, navigation bars, or "Back to Top" buttons.
    *   Understanding positioning contexts is key for `absolute` positioning. A common pattern is to make a parent `position: relative;` and a child `position: absolute;` to position the child within the parent.
    *   <YouTube videoId="jx5jmI0UlXU" title="CSS Position Property (Static, Relative, Absolute, Fixed, Sticky) by Traversy Media" /> (Focus on absolute, fixed)
    *   <YouTube videoId_ CSS_POSITION_ABSOLUTE_VS_FIXED_by_Kevin_Powell title="CSS Position Absolute vs Fixed by Kevin Powell" /> (Placeholder: Kevin Powell is excellent for these concepts)

*   **Lesson 3.14: CSS Positioning - `sticky` and `z-index`**
    *   **`sticky`:**
        *   A hybrid of `relative` and `fixed` positioning.
        *   The element is treated as `position: relative` within its normal flow until it scrolls to a specified offset (defined by `top`, `right`, `bottom`, or `left`), at which point it becomes "stuck" (behaves like `position: fixed`) relative to its containing block or the viewport (depending on ancestors).
        *   Must specify at least one offset property (e.g., `top: 0;`) for sticky positioning to work effectively.
        *   Useful for sticky headers or sidebars that scroll with the content until they reach the top of the viewport.
    *   **`z-index`:**
        *   Specifies the stack order of *positioned* elements (elements with `position` other than `static`).
        *   An element with a greater `z-index` value will be displayed in front of an element with a lower `z-index` value.
        *   Can be positive, negative, or zero. Default is `auto` (effectively 0).
        *   `z-index` only works on positioned elements.
        *   **Stacking Contexts:** New stacking contexts can be formed by elements with `position: absolute/relative` and `z-index` other than `auto`, or elements with `position: fixed/sticky`, `opacity < 1`, `transform`, `filter`, etc. `z-index` values are only compared within the same stacking context. This is a common source of confusion.
    *   <YouTube videoId="jx5jmI0UlXU" title="CSS Position Property (Static, Relative, Absolute, Fixed, Sticky) by Traversy Media" /> (Focus on sticky)
    *   <YouTube videoId="sQUq35SM79U" title="CSS Z-Index and Stacking Contexts by Kevin Powell" />

*   **Lesson 3.15: CSS Floats and Clearfix (Legacy Layout Technique)**
    *   `float` property:
        *   Values: `left`, `right`, `none` (default), `inline-start`, `inline-end`.
        *   Allows an element to be taken out of the normal flow and placed along the left or right side of its container. Text and inline elements will wrap around it.
        *   Historically used for creating multi-column layouts (e.g., sidebars) and wrapping text around images.
        *   **Issues with floats:**
            *   Parent container collapse: If a parent element only contains floated elements, its height might become zero because floated elements are out of the normal flow.
            *   Complex to manage for full-page layouts compared to Flexbox/Grid.
            *   Order dependence.
    *   `clear` property:
        *   Values: `left`, `right`, `both`, `none` (default), `inline-start`, `inline-end`.
        *   Specifies on which sides of an element floating elements are not allowed to float. If an element has `clear: both;`, its top edge will be below the bottom edge of any preceding floated elements.
        *   Used to stop elements from wrapping around a floated element or to ensure an element appears below floated content.
    *   **The Clearfix Hack:** Techniques to make a container expand to contain its floated children, solving the collapsing parent issue.
        *   Common method (Micro Clearfix): Using a pseudo-element (`::after` or `::before`) on the container with `content: ""; display: table; clear: both;`.
        *   Another method: `overflow: auto;` or `overflow: hidden;` on the parent (can have side effects like clipping content or creating scrollbars).
    *   While Flexbox and Grid are preferred for modern layouts, understanding floats is useful for older codebases or specific use cases like simple image-text wrapping.
    *   <YouTube videoId="4p64hQG_PLE" title="CSS Floats Explained (and why you shouldn't use them for layout) by Kevin Powell" />
    *   <YouTube videoId_ CSS_CLEARFIX_HACK_EXPLAINED_by_Traversy_Media title="CSS Clearfix Hack Explained by Traversy Media" /> (Placeholder: Traversy often covers these practical solutions)

---
### Module 4: Modern CSS Layouts - Flexbox and Grid (Expanded)

This module focuses on powerful modern CSS layout systems: Flexbox and Grid, providing in-depth coverage.

*   **Lesson 4.1: Introduction to CSS Flexbox - Terminology and Core Concepts**
    *   What is Flexbox? A one-dimensional layout system for arranging items in rows OR columns.
    *   Designed for laying out components and distributing space among items in a container.
    *   Key Terminology:
        *   **Flex Container:** The parent element on which `display: flex` or `display: inline-flex` is applied.
        *   **Flex Items:** The direct children of the flex container.
        *   **Main Axis:** The primary axis along which flex items are laid out (defined by `flex-direction`). Can be horizontal (row) or vertical (column).
        *   **Cross Axis:** The axis perpendicular to the main axis.
        *   Main Start/End, Cross Start/End.
        *   Main Size, Cross Size.
    *   Enabling Flexbox: `display: flex;` (creates a block-level flex container) or `display: inline-flex;` (creates an inline-level flex container).
    *   <YouTube videoId="K74l26pE4YA" title="Flexbox CSS In 20 Minutes by Traversy Media" /> (Recap)
    *   <YouTube videoId_ FLEXBOX_FUNDAMENTALS_ILLUSTRATED_by_CSS_Tricks title="Flexbox Fundamentals Illustrated by CSS-Tricks (Visual Guide)" /> (Placeholder: CSS-Tricks has great visual guides)
    *   <YouTube videoId="u044iM9xsWU" title="CSS Flexbox Explained in 10 minutes by freeCodeCamp.org" />

*   **Lesson 4.2: Flex Container Properties - `flex-direction` and `flex-wrap`**
    *   **`flex-direction`:** Defines the main axis and the direction items are placed in the flex container.
        *   `row` (default): Main axis is horizontal, left-to-right (in LTR languages).
        *   `row-reverse`: Main axis is horizontal, right-to-left.
        *   `column`: Main axis is vertical, top-to-bottom.
        *   `column-reverse`: Main axis is vertical, bottom-to-top.
    *   **`flex-wrap`:** Controls whether flex items are forced onto one line or can wrap onto multiple lines if they exceed the container's width/height.
        *   `nowrap` (default): Items are forced into a single line (may overflow).
        *   `wrap`: Items wrap onto multiple lines if needed.
        *   `wrap-reverse`: Items wrap onto multiple lines in reverse order.
    *   **`flex-flow` (Shorthand):** Combines `flex-direction` and `flex-wrap`.
        *   **Example:** `flex-flow: row wrap;`
    *   Practical examples of changing direction and wrapping for navigation menus or galleries.
    *   <YouTube videoId="Y8zMYaD16w8" title="CSS Flexbox - Full Tutorial by SuperSimpleDev" /> (Focus on these properties)
    *   <YouTube videoId_ CSS_FLEX_DIRECTION_AND_FLEX_WRAP_by_Kevin_Powell title="CSS flex-direction and flex-wrap by Kevin Powell" /> (Placeholder: Kevin Powell is excellent for Flexbox)

*   **Lesson 4.3: Flex Container Properties - Aligning Items on the Main Axis (`justify-content`)**
    *   **`justify-content`:** Defines how flex items are aligned along the main axis of the flex container (distributes extra space when items don't fill the container, or manages overflow if they do).
    *   Values:
        *   `flex-start` (default): Items are packed toward the start of the main axis.
        *   `flex-end`: Items are packed toward the end of the main axis.
        *   `center`: Items are centered along the main axis.
        *   `space-between`: Items are evenly distributed; first item at the start, last item at the end, space is only between items.
        *   `space-around`: Items are evenly distributed with equal space around them (half-space at ends).
        *   `space-evenly`: Items are evenly distributed with equal space between them and at the ends (all spaces are equal).
    *   Visual examples for each value in both `row` and `column` directions.
    *   **Example:** Creating a navigation bar with evenly spaced links: `.nav { display: flex; justify-content: space-around; }`
    *   <YouTube videoId="FVgLybwIJw" title="Flexbox justify-content Property by Academind" />
    *   <YouTube videoId_ CSS_FLEXBOX_JUSTIFY_CONTENT_VISUAL_GUIDE_by_CSS_Tricks title="CSS Flexbox justify-content Visual Guide by CSS-Tricks" /> (Placeholder)

*   **Lesson 4.4: Flex Container Properties - Aligning Items on the Cross Axis (`align-items`)**
    *   **`align-items`:** Defines how flex items are aligned along the cross axis of the flex container (within a single line).
    *   Values:
        *   `stretch` (default): Items stretch to fill the container's cross size (if their cross-axis dimension is `auto`).
        *   `flex-start`: Items are packed toward the start of the cross axis.
        *   `flex-end`: Items are packed toward the end of the cross axis.
        *   `center`: Items are centered along the cross axis.
        *   `baseline`: Items are aligned based on their text baselines (useful for aligning text content across items of different sizes).
    *   Visual examples demonstrating alignment for items of different heights/widths.
    *   How this interacts with `flex-direction` (cross axis changes based on main axis direction).
    *   <YouTube videoId="Y8zMYaD16w8" title="CSS Flexbox - Full Tutorial by SuperSimpleDev" /> (Look for align-items section)
    *   <YouTube videoId_ CSS_FLEXBOX_ALIGN_ITEMS_DEEP_DIVE_by_Kevin_Powell title="CSS Flexbox align-items Deep Dive by Kevin Powell" /> (Placeholder)

*   **Lesson 4.5: Flex Container Properties - Aligning Multiple Lines (`align-content`)**
    *   **`align-content`:** Defines how multiple lines of flex items are aligned along the cross axis when there is extra space in the flex container (i.e., when `flex-wrap: wrap` or `wrap-reverse` is used and items wrap to multiple lines).
    *   This property has no effect when there is only one line of flex items.
    *   Values (similar to `justify-content` but for the cross axis distribution of lines):
        *   `stretch` (default): Lines stretch to take up remaining space.
        *   `flex-start`: Lines packed to the start of the cross axis.
        *   `flex-end`: Lines packed to the end of the cross axis.
        *   `center`: Lines centered in the cross axis.
        *   `space-between`: Lines evenly distributed; first line at start, last at end.
        *   `space-around`: Lines evenly distributed with equal space around each line.
        *   `space-evenly`: Lines evenly distributed with equal space between them and at the ends.
    *   Visual examples showing how lines of wrapped items are distributed.
    *   <YouTube videoId_ CSS_FLEXBOX_ALIGN_CONTENT_EXPLAINED_by_Traversy_Media title="CSS Flexbox align-content Explained by Traversy Media" /> (Placeholder)
    *   <YouTube videoId_ FLEXBOX_ALIGN_CONTENT_VS_ALIGN_ITEMS_by_Web_Dev_Simplified title="Flexbox align-content vs align-items by Web Dev Simplified" /> (Placeholder)

*   **Lesson 4.6: Flex Item Properties - `order`**
    *   **`order`:** Controls the visual order in which flex items appear in the flex container, independent of their source order in the HTML.
    *   Default value is `0`.
    *   Items are laid out in ascending order of their `order` value (e.g., `-1` comes before `0`, which comes before `1`).
    *   Items with the same `order` value are laid out in source order.
    *   Can take positive or negative integer values.
    *   **Example:** `<div class="item" style="order: -1;">First Visually</div> <div class="item" style="order: 1;">Last Visually</div> <div class="item">Middle (default order 0)</div>`
    *   Useful for reordering items visually without changing HTML structure (e.g., for responsive design where a sidebar might move).
    *   Accessibility consideration: `order` changes visual order but not tab order or screen reader order.
    *   <YouTube videoId_ CSS_FLEXBOX_ORDER_PROPERTY_by_The_Net_Ninja title="CSS Flexbox Order Property by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId_ ACCESSIBILITY_AND_CSS_ORDER_PROPERTY_by_A11ycasts title="Accessibility and CSS Order Property by A11ycasts" /> (Placeholder)

*   **Lesson 4.7: Flex Item Properties - `flex-grow`, `flex-shrink`, `flex-basis`**
    *   These properties control how flex items size themselves within the flex container, particularly when there's extra space or not enough space.
    *   **`flex-basis`:** Defines the default/ideal size of an item along the main axis before remaining space is distributed.
        *   Can be a length (`px`, `em`, `%`), `auto` (item's content size or explicit width/height), or `content` (intrinsic size based on content).
        *   If set to `0` (or `0%`), the extra space is distributed based purely on `flex-grow` proportions.
    *   **`flex-grow`:** Defines the ability of a flex item to grow if necessary (a unitless proportion that dictates how much of the available free space it should take).
        *   Default is `0` (item does not grow).
        *   If all items have `flex-grow: 1`, they share extra space equally. If one has `flex-grow: 2` and others `1`, it takes twice as much of the available space as the others.
    *   **`flex-shrink`:** Defines the ability of a flex item to shrink if necessary (when items overflow the container).
        *   Default is `1` (item can shrink).
        *   If `0`, item will not shrink below its `flex-basis`.
        *   The amount an item shrinks is proportional to its `flex-shrink` value multiplied by its `flex-basis`.
    *   Understanding how these three properties work together is key to mastering flex item sizing.
    *   <YouTube videoId_ CSS_FLEX_GROW_SHRINK_BASIS_EXPLAINED_by_Kevin_Powell title="CSS flex-grow, flex-shrink, flex-basis Explained by Kevin Powell" /> (Placeholder: Kevin Powell is excellent for this)
    *   <YouTube videoId="Y8zMYaD16w8" title="CSS Flexbox - Full Tutorial by SuperSimpleDev" /> (Look for grow, shrink, basis sections)

*   **Lesson 4.8: Flex Item Properties - The `flex` Shorthand and `align-self`**
    *   **`flex` (Shorthand):** Combines `flex-grow`, `flex-shrink`, and `flex-basis`.
        *   One value syntax:
            *   `flex: <number>;` (e.g., `flex: 1;`) - equivalent to `flex-grow: <number>; flex-shrink: 1; flex-basis: 0%;` (This is a common way to make items share space proportionally).
            *   `flex: auto;` - equivalent to `1 1 auto`.
            *   `flex: none;` - equivalent to `0 0 auto`.
            *   `flex: initial;` - equivalent to `0 1 auto` (default flex value).
        *   Two-value syntax: `flex: <flex-grow> <flex-basis>;` (shrink defaults to 1). `flex: <flex-grow> <flex-shrink>;` (basis defaults to 0%).
        *   Three-value syntax: `flex: <flex-grow> <flex-shrink> <flex-basis>;`
        *   It's often recommended to use the longhand properties if you find the shorthand confusing initially.
    *   **`align-self`:** Allows the default alignment (or the one specified by `align-items` on the container) to be overridden for individual flex items.
        *   Values are the same as `align-items`: `auto` (default, inherits from container), `stretch`, `flex-start`, `flex-end`, `center`, `baseline`.
    *   **Example:** Making one specific item in a row align to the bottom while others are at the top using `align-self: flex-end;`.
    *   <YouTube videoId_ CSS_FLEX_SHORTHAND_PROPERTY_by_The_Net_Ninja title="CSS Flex Shorthand Property by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId_ CSS_FLEXBOX_ALIGN_SELF_by_Kevin_Powell title="CSS Flexbox align-self by Kevin Powell" /> (Placeholder)

*   **Lesson 4.9: Practical Flexbox Examples - Navigation Bars and Card Layouts**
    *   Building a responsive navigation bar using Flexbox.
        *   Aligning logo to the left, links to the right or centered.
        *   Using `margin: auto` on a flex item for separation.
        *   Handling wrapping on smaller screens with media queries and changing `flex-direction`.
    *   Creating a layout of equally spaced cards.
        *   Using `flex-wrap: wrap` and `justify-content` for distribution.
        *   Controlling card sizing with `flex-basis` (e.g., `flex-basis: 300px;`) and `flex-grow: 1;` to allow them to grow and fill space.
        *   Ensuring consistent spacing with gaps or margins.
    *   Step-by-step coding examples with HTML and CSS.
    *   <YouTube videoId_ BUILD_A_RESPONSIVE_NAVBAR_WITH_FLEXBOX_by_Traversy_Media title="Build a Responsive Navbar with Flexbox by Traversy Media" /> (Placeholder)
    *   <YouTube videoId_ FLEXBOX_CARD_LAYOUT_TUTORIAL_by_DesignCourse title="Flexbox Card Layout Tutorial by DesignCourse" /> (Placeholder)

*   **Lesson 4.10: Introduction to CSS Grid Layout - Terminology and Core Concepts**
    *   What is CSS Grid? A two-dimensional layout system for arranging items in rows AND columns.
    *   Designed for overall page layouts as well as component layouts. It offers more control over both dimensions simultaneously than Flexbox.
    *   Key Terminology:
        *   **Grid Container:** The parent element on which `display: grid` or `display: inline-grid` is applied.
        *   **Grid Items:** The direct children of the grid container.
        *   **Grid Lines:** The dividing lines that make up the structure of the grid (horizontal and vertical). They can be numbered or named.
        *   **Grid Tracks:** The space between two adjacent grid lines (these are the columns or rows themselves).
        *   **Grid Cell:** The space between two adjacent row and two adjacent column grid lines (the smallest unit of the grid).
        *   **Grid Area:** A rectangular space made up of one or more grid cells, defined by four grid lines.
        *   **Gutters (Gaps):** Space between grid tracks, defined by `gap`, `row-gap`, `column-gap`.
    *   Enabling Grid: `display: grid;` (creates a block-level grid container) or `display: inline-grid;` (creates an inline-level grid container).
    *   Using Browser DevTools to visualize and inspect grids.
    *   <YouTube videoId="jV8B24rSN5o" title="CSS Grid Layout Crash Course by Traversy Media" /> (Recap)
    *   <YouTube videoId_ CSS_GRID_TERMINOLOGY_ILLUSTRATED_by_CSS_Tricks title="CSS Grid Terminology Illustrated by CSS-Tricks (Visual Guide)" /> (Placeholder: CSS-Tricks has great visual guides)
    *   <YouTube videoId="0xMQfnTU6oo" title="CSS Grid Tutorial - A Complete Guide by Web Dev Simplified" /> (Introduction part)

*   **Lesson 4.11: Defining Grid Structure - `grid-template-columns` and `grid-template-rows`**
    *   **`grid-template-columns`:** Defines the number and size of columns in the grid.
        *   Values:
            *   Lengths (`px`, `em`, `%` - percentage of container width).
            *   `auto` (size based on content of items in that track, or remaining space).
            *   `fr` unit (fractional unit, distributes available space proportionally after fixed/content-sized tracks are accounted for).
        *   `repeat()` function: `repeat(count, track_size_list)` e.g., `repeat(3, 1fr)` for three equal columns, or `repeat(auto-fit, minmax(200px, 1fr))` for responsive columns.
        *   `minmax()` function: `minmax(min_size, max_size)` for defining a size range for a track.
    *   **`grid-template-rows`:** Defines the number and size of rows in the grid.
        *   Similar values and functions as `grid-template-columns`.
    *   Implicit vs. Explicit Grid: If items are placed outside the explicitly defined grid (e.g., more items than cells defined), implicit tracks are created. Their size is controlled by `grid-auto-columns` and `grid-auto-rows` (default is `auto`).
    *   **Example:** `grid-template-columns: 1fr 2fr 100px; grid-template-rows: auto 150px min-content;`
    *   <YouTube videoId_ CSS_GRID_TEMPLATE_COLUMNS_ROWS_FR_UNIT_by_Kevin_Powell title="CSS Grid grid-template-columns, grid-template-rows & fr unit by Kevin Powell" /> (Placeholder)
    *   <YouTube videoId="0xMQfnTU6oo" title="CSS Grid Tutorial - A Complete Guide by Web Dev Simplified" /> (Focus on template columns/rows)
    *   <YouTube videoId_ CSS_GRID_REPEAT_MINMAX_AUTOFIT_AUTOFILL_by_LayoutLand_Jen_Simmons title="CSS Grid repeat(), minmax(), auto-fit, auto-fill by Layout Land (Jen Simmons)" /> (Placeholder)

*   **Lesson 4.12: Placing Items in the Grid - Line-Based Placement and `grid-area` Shorthand**
    *   Grid lines are numbered (starting from 1 for the first line). Negative numbers count from the end (e.g., -1 is the last line).
    *   **`grid-column-start` / `grid-column-end`:** Define which column line an item starts and ends on.
    *   **`grid-row-start` / `grid-row-end`:** Define which row line an item starts and ends on.
    *   Shorthands:
        *   `grid-column: start-line / end-line;`
        *   `grid-row: start-line / end-line;`
    *   Using `span` keyword: `grid-column: span 2;` (item spans 2 columns from its start line). Or `grid-column: 1 / span 2;`.
    *   **`grid-area` (Shorthand for all four line properties):** `grid-area: row-start / column-start / row-end / column-end;`
    *   **Example:**
        ```css
        .item1 {
            grid-column-start: 1;
            grid-column-end: 3; /* Spans column 1 and 2 */
            grid-row-start: 1;
            grid-row-end: 2;
        }
        /* Equivalent using shorthand: */
        .item1-shorthand { grid-column: 1 / 3; grid-row: 1 / 2; }
        .item1-area { grid-area: 1 / 1 / 2 / 3; }
        ```
    *   Overlapping items (controlled by source order or `z-index` if positioned).
    *   <YouTube videoId_ CSS_GRID_LINE_BASED_PLACEMENT_by_The_Net_Ninja title="CSS Grid Line-Based Placement by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId_ CSS_GRID_AREA_PROPERTY_by_Kevin_Powell title="CSS Grid grid-area property by Kevin Powell" /> (Placeholder)

*   **Lesson 4.13: Placing Items in the Grid - Using Named Grid Lines and `grid-template-areas`**
    *   **Naming Grid Lines:** You can name grid lines in `grid-template-columns` and `grid-template-rows`.
        *   **Example:** `grid-template-columns: [sidebar-start] 1fr [sidebar-end main-start] 3fr [main-end];`
        *   Then place items using these names: `grid-column: sidebar-start / main-end;`
    *   **`grid-template-areas`:** Defines named areas within the grid container, making item placement more visual and semantic.
        *   Syntax: Define a string for each row, with names for cells. Use `.` for an empty cell. Names must span rectangular areas.
        *   **Example:**
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
            ```
    *   **`grid-area` (on grid item):** Assigns a grid item to a named area defined by `grid-template-areas`.
        *   **Example:** `.header-item { grid-area: header; }`
    *   This method is excellent for overall page layouts and makes responsive changes easier by redefining `grid-template-areas` in media queries.
    *   <YouTube videoId_ CSS_GRID_TEMPLATE_AREAS_EXPLAINED_by_Traversy_Media title="CSS Grid grid-template-areas Explained by Traversy Media" /> (Placeholder)
    *   <YouTube videoId_ NAMED_GRID_LINES_AND_AREAS_IN_CSS_GRID_by_Kevin_Powell title="Named Grid Lines and Areas in CSS Grid by Kevin Powell" /> (Placeholder)

*   **Lesson 4.14: Grid Gaps (`gap`, `row-gap`, `column-gap`) and Alignment (`justify-items`, `align-items`, `justify-content`, `align-content`)**
    *   **`gap` (shorthand for `row-gap` and `column-gap`):** Defines the size of the gutters between grid tracks.
        *   `row-gap`: Space between rows.
        *   `column-gap`: Space between columns.
        *   **Example:** `gap: 20px;` or `gap: 10px 20px;` (row-gap column-gap).
    *   **Aligning Items within their Grid Cell (on the Grid Container):**
        *   **`justify-items`:** Aligns items along the inline (row) axis within their cell. Values: `start`, `end`, `center`, `stretch` (default).
        *   **`align-items`:** Aligns items along the block (column) axis within their cell. Values: `start`, `end`, `center`, `stretch` (default), `baseline`.
    *   **Aligning the Grid itself within the Container (on the Grid Container, if grid is smaller than container):**
        *   **`justify-content`:** Aligns the entire grid along the inline (row) axis. Values: `start`, `end`, `center`, `space-between`, `space-around`, `space-evenly`, `stretch`.
        *   **`align-content`:** Aligns the entire grid along the block (column) axis. Values: `start`, `end`, `center`, `space-between`, `space-around`, `space-evenly`, `stretch`.
    *   **Overriding Alignment for Individual Items (on Grid Items):**
        *   `justify-self`: Overrides `justify-items` for a specific item.
        *   `align-self`: Overrides `align-items` for a specific item.
    *   <YouTube videoId_ CSS_GRID_GAPS_AND_ALIGNMENT_by_The_Net_Ninja title="CSS Grid Gaps and Alignment by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId_ CSS_GRID_ALIGNMENT_ALL_PROPERTIES_by_Web_Dev_Simplified title="CSS Grid Alignment (All Properties) by Web Dev Simplified" /> (Placeholder)

*   **Lesson 4.15: Responsive Web Design Principles with Flexbox and Grid**
    *   Recap: Fluid grids, flexible images, media queries.
    *   Using Flexbox for component-level responsiveness (e.g., navigation items stacking, card elements adjusting order or wrapping).
    *   Using Grid for page-level responsiveness (e.g., changing number of columns with `repeat(auto-fit, minmax(X, 1fr))`, re-arranging `grid-template-areas` in media queries, changing `grid-auto-flow`).
    *   Combining Flexbox and Grid: Grid for overall page layout, Flexbox for aligning items or components *within* those grid areas. This is a very common and powerful pattern.
    *   Techniques for responsive layouts:
        *   Changing `flex-direction` or `grid-template-columns`/`rows` inside media queries.
        *   Using `fr` units and `minmax()` in Grid for intrinsic responsiveness (adapts without media queries).
        *   Using `flex-wrap: wrap;` in Flexbox.
        *   The `clamp()` CSS function for fluid typography and spacing.
    *   Mobile-first vs. Desktop-first approach in the context of Flexbox/Grid.
    *   **Example:** A 3-column grid layout on desktop that becomes a single column on mobile by changing `grid-template-columns` or `grid-template-areas`.
    *   <YouTube videoId="srvUrASNj0s" title="Responsive Web Design - HTML & CSS Tutorial by freeCodeCamp.org" /> (Revisit with Flexbox/Grid context)
    *   <YouTube videoId_ RESPONSIVE_LAYOUTS_WITH_FLEXBOX_AND_GRID_by_Kevin_Powell title="Responsive Layouts with Flexbox and Grid by Kevin Powell" /> (Placeholder)
    *   <YouTube videoId_ CSS_GRID_AND_FLEXBOX_TOGETHER_FOR_POWERFUL_LAYOUTS_by_Traversy_Media title="CSS Grid and Flexbox Together for Powerful Layouts by Traversy Media" /> (Placeholder)

---
### Module 5: JavaScript Fundamentals (Expanded)

This module introduces JavaScript, the programming language of the web, for adding interactivity and dynamic behavior, with expanded lesson details.

*   **Lesson 5.1: Introduction to JavaScript - What, Why, and How**
    *   What is JavaScript? A high-level, interpreted (or JIT-compiled), multi-paradigm programming language.
    *   Primary role: Making web pages interactive and dynamic (Client-Side JavaScript).
    *   Other uses: Server-side (Node.js), mobile apps (React Native, Ionic), desktop apps (Electron), game development.
    *   Key characteristics: Dynamically typed, single-threaded (with event loop for concurrency).
    *   A brief history of JavaScript (Brendan Eich, Netscape, ECMAScript).
    *   Why learn JavaScript? Essential for modern web development, vast ecosystem, large community.
    *   <YouTube videoId="W6NZfCO5SIk" title="JavaScript Crash Course For Beginners by Traversy Media" /> (Recap)
    *   <YouTube videoId="hdI2bqOjy3c" title="What is JavaScript? by Programming with Mosh" />

*   **Lesson 5.2: Setting Up Your JavaScript Environment**
    *   **Browser Console:**
        *   Accessing the console in Chrome, Firefox, Edge.
        *   Running simple JavaScript commands directly.
        *   Using `console.log()` for output and basic debugging. Other console methods (`console.error()`, `console.warn()`, `console.table()`).
    *   **HTML `<script>` Tag:**
        *   Internal JavaScript: Placing JS code directly within `<script> ... </script>` tags.
            *   Placement: Usually just before the closing `</body>` tag (to ensure HTML is loaded before script tries to manipulate it). Can also be in `<head>` with `defer` or `async` attributes.
            ```html
            <script>
                console.log("Hello from internal JavaScript!");
                // alert("This is an alert!"); // Example of an alert (use sparingly)
            </script>
            ```
        *   External JavaScript: Linking to an external `.js` file. (Recommended for organization).
            *   HTML: `<script src="app.js"></script>`
            *   `app.js` file: `console.log("Hello from external JavaScript file!");`
    *   `async` vs `defer` attributes for `<script>` tags in `<head>`:
        *   `async`: Downloads script asynchronously, executes as soon as downloaded (can interrupt HTML parsing if it happens before DOMContentLoaded). Order not guaranteed for multiple async scripts.
        *   `defer`: Downloads script asynchronously, executes after HTML parsing is complete but before DOMContentLoaded event, in the order they appear in the HTML.
    *   Using a text editor (like VS Code) with Node.js for local JS development (optional for frontend basics, but good to know for later).
    *   <YouTube videoId="qgHwsgYgP4" title="Running JavaScript - The Console, Script Tags, And More by Web Dev Simplified" />
    *   <YouTube videoId_ SCRIPT_ASYNC_DEFER_ATTRIBUTES_EXPLAINED_by_Fireship title="Script async & defer attributes explained by Fireship" /> (Placeholder: Fireship for concise explanations)

*   **Lesson 5.3: Variables - `var`, `let`, and `const`**
    *   What are Variables? Named containers for storing data values.
    *   Declaring Variables:
        *   `var` (older keyword): Function-scoped or globally-scoped. Can be re-declared and updated. Prone to hoisting issues (variable declaration is "lifted" to the top of its scope, but initialization is not). (Generally avoid in modern JS).
        *   `let` (ES6+): Block-scoped (`{}`). Can be updated but not re-declared within the same scope. Subject to Temporal Dead Zone (TDZ) - cannot be accessed before declaration.
        *   `const` (ES6+): Block-scoped. Cannot be updated (reassigned) or re-declared. Must be initialized at declaration. (Use for values that shouldn't change). For objects and arrays declared with `const`, their properties/elements can be changed, but the variable itself cannot be reassigned to a new object/array.
    *   Variable Naming Conventions (camelCase is common: `myVariableName`). Rules for identifiers.
    *   Assignment Operator (`=`).
    *   **Examples:**
        ```javascript
        let age = 30;
        const name = "Alice";
        var city = "New York"; // Avoid var

        age = 31; // OK
        // name = "Bob"; // Error: Assignment to constant variable.
        // let age = 35; // Error: 'age' has already been declared in this scope

        const person = { city: "London" };
        person.city = "Paris"; // OK, modifying property of const object
        // person = { city: "Rome" }; // Error, cannot reassign const variable
        ```
    *   Understanding Scope (Global, Function, Block) and Hoisting in detail.
    *   <YouTube videoId="9qnN_dGNnQ" title="JavaScript var, let, and const - ES6 by Traversy Media" />
    *   <YouTube videoId_ JAVASCRIPT_SCOPE_AND_HOISTING_EXPLAINED_by_Web_Dev_Simplified title="JavaScript Scope and Hoisting Explained by Web Dev Simplified" /> (Placeholder)

*   **Lesson 5.4: JavaScript Data Types - Primitives**
    *   JavaScript is dynamically typed (variable types are determined at runtime).
    *   **Primitive Data Types:** Immutable (their value cannot be changed directly once created; operations on primitives return new primitive values).
        *   **String:** Sequence of characters (text). Enclosed in single quotes (`'...'`), double quotes (`"..."`), or backticks (`` `...` `` - template literals).
            *   **Example:** `let greeting = "Hello, world!"; let message = `User: ${name}`;`
        *   **Number:** Numeric values (64-bit floating-point format). Includes integers and floating-point numbers. Special values: `Infinity`, `-Infinity`, `NaN` (Not a Number - result of invalid math operations).
            *   **Example:** `let count = 100; let price = 19.99; let notANum = 0/0; // NaN`
        *   **Boolean:** Logical type, can only be `true` or `false`.
            *   **Example:** `let isActive = true; let isLoggedIn = false;`
        *   **Undefined:** A variable that has been declared but not yet assigned a value. Also the default return value of functions that don't explicitly return anything.
            *   **Example:** `let user; console.log(user); // undefined`
        *   **Null:** Represents the intentional absence of any object value. It's an assignment value, meaning a variable can be explicitly set to `null`.
            *   **Example:** `let selectedProduct = null;`
        *   **Symbol (ES6+):** Unique and immutable primitive value, often used as unique property keys for objects to avoid naming collisions.
        *   **BigInt (ES2020+):** For representing and manipulating integers larger than the maximum safe integer for Numbers (`Number.MAX_SAFE_INTEGER`). Created by appending `n` to an integer literal (e.g., `123n`).
    *   The `typeof` operator to check the type of a variable (note: `typeof null` is "object" - a long-standing quirk).
    *   <YouTube videoId="jS4aFq5-91M" title="JavaScript Variables, Data Types, and Operators by Programming with Mosh" /> (Focus on Data Types, Primitives)
    *   <YouTube videoId_ JAVASCRIPT_PRIMITIVE_DATA_TYPES_IN_DEPTH_by_Academind title="JavaScript Primitive Data Types In-Depth by Academind" /> (Placeholder)

*   **Lesson 5.5: JavaScript Data Types - Objects (and Arrays as a type of Object)**
    *   **Object Type:** Represents a collection of key-value pairs (properties). Mutable (their content can be changed after creation).
        *   Object Literals: `let person = { firstName: "John", lastName: "Doe", age: 30, address: { street: "123 Main St", city: "Anytown" } };`
        *   Keys are usually strings (can be Symbols). Values can be any data type, including other objects or functions (methods).
        *   Accessing properties: Dot notation (`person.firstName`) or Bracket notation (`person["age"]`, `person.address.city`). Bracket notation is useful for dynamic property names or names with special characters.
        *   Adding/Modifying properties: `person.email = "john@example.com"; person.age = 31;`
        *   Deleting properties: `delete person.age;`
    *   **Arrays:** Special type of object used for ordered lists of items. Indexed by numbers (starting from 0).
        *   Array Literals: `let colors = ["red", "green", "blue", 10, { id: 1 }];` (can hold mixed data types).
        *   Zero-based indexing: `colors[0]` is "red".
        *   `length` property: `colors.length` gives the number of elements.
        *   Modifying elements: `colors[1] = "yellow";`
        *   Adding elements: `push()` (end), `unshift()` (beginning). (More on array methods later).
    *   (Functions are also a type of object - covered in detail later).
    *   Understanding that primitives are passed by value, objects (including arrays and functions) are passed by reference (the variable holds a reference/pointer to the object in memory).
    *   <YouTube videoId="X0løXN02JU0" title="JavaScript Objects - In-Depth Tutorial by Programming with Mosh" />
    *   <YouTube videoId="oigfaZ5ApsM" title="JavaScript Arrays & Array Methods by Traversy Media" /> (Focus on array creation and basic properties)

*   **Lesson 5.6: JavaScript Operators - Arithmetic, Assignment, Comparison**
    *   **Arithmetic Operators:**
        *   `+` (Addition, also String Concatenation if one operand is a string).
        *   `-` (Subtraction).
        *   `*` (Multiplication).
        *   `/` (Division).
        *   `%` (Modulus/Remainder): `10 % 3` results in `1`.
        *   `**` (Exponentiation - ES7+): `2 ** 3` results in `8`.
        *   `++` (Increment): Increases a numeric variable by 1. `x++` (postfix: uses value then increments) or `++x` (prefix: increments then uses value).
        *   `--` (Decrement): Decreases by 1. Similar prefix/postfix behavior.
    *   **Assignment Operators:**
        *   `=` (Simple Assignment).
        *   Compound assignment: `+=`, `-=`, `*=`, `/=`, `%=`, `**=`.
            *   **Example:** `let x = 10; x += 5; // x is now 15 (equivalent to x = x + 5)`
    *   **Comparison Operators:** Return a boolean (`true` or `false`).
        *   `==` (Loose Equality): Compares values after attempting type coercion. (Often discouraged due to unpredictable behavior).
            *   **Example:** `5 == "5"` is `true`.
        *   `===` (Strict Equality): Compares values AND types without coercion. (Generally preferred).
            *   **Example:** `5 === "5"` is `false`.
        *   `!=` (Loose Inequality).
        *   `!==` (Strict Inequality). (Generally preferred).
        *   `>` (Greater than), `<` (Less than), `>=` (Greater than or equal to), `<=` (Less than or equal to).
    *   Operator Precedence (e.g., `*` and `/` before `+` and `-`). Use parentheses `()` to control order. (Refer to MDN for full table).
    *   <YouTube videoId="jS4aFq5-91M" title="JavaScript Variables, Data Types, and Operators by Programming with Mosh" /> (Focus on Operators section)
    *   <YouTube videoId_ JAVASCRIPT_COMPARISON_OPERATORS_STRICT_VS_LOOSE_EQUALITY_by_Web_Dev_Simplified title="JavaScript Comparison Operators: Strict vs Loose Equality by Web Dev Simplified" /> (Placeholder)

*   **Lesson 5.7: JavaScript Operators - Logical, String, Ternary, and More**
    *   **Logical Operators:**
        *   `&&` (Logical AND): Returns the first falsy operand, or the last operand if all are truthy. Short-circuits (if first operand is falsy, second is not evaluated).
            *   **Example:** `true && "hello"` is `"hello"`; `false && "hello"` is `false`.
        *   `||` (Logical OR): Returns the first truthy operand, or the last operand if all are falsy. Short-circuits.
            *   **Example:** `null || "default"` is `"default"`; `"hi" || "bye"` is `"hi"`.
        *   `!` (Logical NOT): Converts operand to boolean and then negates it. `!true` is `false`; `!"hello"` is `false`.
        *   Truthy and Falsy values in JavaScript (`false`, `0`, `-0`, `0n` (BigInt zero), `""` (empty string), `null`, `undefined`, `NaN` are falsy. All other values are truthy, including objects and arrays (even empty ones)).
    *   **String Operator:**
        *   `+` (Concatenation): Joins strings. `let fullName = "John" + " " + "Doe";`
    *   **Ternary Operator (Conditional Operator):**
        *   `condition ? expressionIfTrue : expressionIfFalse;`
        *   A shorthand for simple `if...else` statements.
        *   **Example:** `let access = (userAge >= 18) ? "granted" : "denied";`
    *   **Comma Operator:** Evaluates multiple expressions and returns the value of the last expression. (Rarely used).
    *   **Bitwise Operators:** (`&`, `|`, `^`, `~`, `<<`, `>>`, `>>>`) - for low-level operations on binary representations (advanced, mention briefly).
    *   <YouTube videoId_ JAVASCRIPT_LOGICAL_OPERATORS_AND_TRUTHY_FALSY_VALUES_by_The_Net_Ninja title="JavaScript Logical Operators and Truthy/Falsy Values by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId_ JAVASCRIPT_TERNARY_OPERATOR_IN_DEPTH_by_Academind title="JavaScript Ternary Operator In-Depth by Academind" /> (Placeholder)

*   **Lesson 5.8: Type Conversion and Coercion**
    *   **Explicit Type Conversion (Casting):** Manually converting a value from one type to another.
        *   `String(value)` or `value.toString()`: Converts `value` to a string.
            *   **Example:** `String(123)` is `"123"`.
        *   `Number(value)`: Converts `value` to a number. Can result in `NaN` if conversion is not possible.
            *   **Example:** `Number("42")` is `42`; `Number("hello")` is `NaN`.
        *   `parseInt(string, [radix])`: Parses a string and returns an integer. `radix` specifies the base (e.g., 10 for decimal, 2 for binary). Stops at first non-numeric character.
        *   `parseFloat(string)`: Parses a string and returns a floating-point number.
        *   `Boolean(value)`: Converts `value` to a boolean. All falsy values convert to `false`, all truthy values to `true`.
    *   **Implicit Type Coercion:** JavaScript automatically converts types in certain operations, which can sometimes lead to unexpected results.
        *   Using the `+` operator with a string and a number: `5 + "5"` results in string concatenation `"55"`.
        *   Using other arithmetic operators (`-`, `*`, `/`) with a string that looks like a number: `"5" * 2` results in numeric multiplication `10`.
        *   In comparisons with `==` (loose equality): `"10" == 10` is `true`.
        *   In logical contexts (like `if` statements): `if ("text") { ... }` ("text" is coerced to `true`).
    *   Understanding coercion rules (especially with `==`) is important for debugging. Using strict equality (`===` and `!==`) helps avoid many coercion pitfalls.
    *   <YouTube videoId="PgrjC2H9AcI" title="JavaScript Type Coercion Explained by Fun Fun Function" />
    *   <YouTube videoId_ JAVASCRIPT_EXPLICIT_VS_IMPLICIT_COERCION_by_Kyle_Simpson_Frontend_Masters title="JavaScript Explicit vs Implicit Coercion by Kyle Simpson (Frontend Masters)" /> (Placeholder)

*   **Lesson 5.9: Working with Strings - Properties and Methods**
    *   Strings are immutable primitives but have object-like methods (JavaScript wraps the primitive string with a String object when a method is called).
    *   `length` property: `let str = "hello"; console.log(str.length); // 5`
    *   Common String Methods:
        *   `toUpperCase()`, `toLowerCase()`
        *   `indexOf(searchValue, [fromIndex])`, `lastIndexOf(searchValue, [fromIndex])`: Find substring position, return -1 if not found.
        *   `includes(searchValue, [fromIndex])`: Check if string contains a substring (ES6+), returns boolean.
        *   `startsWith(searchValue, [fromIndex])`, `endsWith(searchValue, [endPosition])` (ES6+), returns boolean.
        *   `slice(startIndex, [endIndex])`: Extracts a part of a string. `endIndex` is exclusive. Negative indices count from end.
        *   `substring(startIndex, [endIndex])`: Similar to slice, but handles arguments differently if `startIndex > endIndex`.
        *   `substr(startIndex, length)`: (Deprecated, use slice or substring).
        *   `replace(searchValue, newValue)`: Replaces first occurrence of `searchValue` (string or regex) with `newValue`. For global replace with string, use regex with `g` flag.
        *   `replaceAll(searchValue, newValue)` (ES2021+): Replaces all occurrences.
        *   `split(separator, [limit])`: Splits string into an array of substrings based on `separator`.
        *   `trim()`: Removes whitespace from both ends. `trimStart()`, `trimEnd()`.
        *   `charAt(index)`, `charCodeAt(index)` (returns UTF-16 code unit).
        *   Accessing characters using bracket notation: `str[0]` (returns character, or `undefined` if out of bounds).
    *   **Template Literals (ES6+):** Backticks `` `...` ``.
        *   Allow embedded expressions using `${expression}`: `` `My name is ${name} and I am ${age}.` ``
        *   Allow multi-line strings easily without `\n`.
    *   <YouTube videoId="mbZASK_60I" title="JavaScript String Methods by Programming with Mosh" />
    *   <YouTube videoId_ JAVASCRIPT_TEMPLATE_LITERALS_ES6_by_The_Net_Ninja title="JavaScript Template Literals (ES6) by The Net Ninja" /> (Placeholder)

*   **Lesson 5.10: Working with Numbers - Methods and Math Object**
    *   Number type covers integers and floats. Special values: `Infinity`, `-Infinity`, `NaN`.
    *   Number Methods (called on Number objects, or use `Number.` static methods):
        *   `num.toFixed(digits)`: Formats a number using fixed-point notation, returns a string. Rounds if necessary.
        *   `num.toPrecision(precision)`: Formats a number to a specified length (total significant digits), returns a string.
        *   `num.toString([radix])`: Converts number to string. `radix` (2-36) specifies the base (e.g., base 2 for binary, 16 for hexadecimal).
        *   `Number.isInteger(value)`: Checks if `value` is an integer.
        *   `Number.isNaN(value)`: Checks if `value` is `NaN`. (More reliable than global `isNaN()`).
        *   `Number.isFinite(value)`: Checks if `value` is a finite number (not `Infinity`, `-Infinity`, or `NaN`).
        *   `Number.parseInt(string, [radix])`, `Number.parseFloat(string)` (static versions of global functions).
    *   The `Math` Object (built-in global object with properties and methods for mathematical constants and functions):
        *   Constants: `Math.PI`, `Math.E`.
        *   Rounding: `Math.round(x)` (to nearest integer), `Math.ceil(x)` (up to next integer), `Math.floor(x)` (down to previous integer), `Math.trunc(x)` (removes decimal part).
        *   `Math.abs(x)` (absolute value).
        *   `Math.pow(base, exponent)`.
        *   `Math.sqrt(x)` (square root).
        *   `Math.random()`: Returns a pseudo-random floating-point number between 0 (inclusive) and 1 (exclusive).
            *   Generating random integers in a range: `Math.floor(Math.random() * (max - min + 1)) + min`.
        *   `Math.min(val1, val2, ...)`, `Math.max(val1, val2, ...)`.
        *   Trigonometric functions (`Math.sin()`, `Math.cos()`, `Math.tan()`, etc.).
    *   <YouTube videoId_ JAVASCRIPT_NUMBER_METHODS_AND_MATH_OBJECT_by_Traversy_Media title="JavaScript Number Methods and Math Object by Traversy Media" /> (Placeholder)
    *   <YouTube videoId_ JAVASCRIPT_MATH_OBJECT_TUTORIAL_by_freeCodeCamp title="JavaScript Math Object Tutorial by freeCodeCamp.org" /> (Placeholder)

*   **Lesson 5.11: Control Flow - `if`, `else if`, `else` Statements**
    *   Conditional execution of code based on boolean expressions.
    *   `if (condition) { // code to run if condition is true }`
    *   `if (condition) { ... } else { // code to run if condition is false }`
    *   `if (condition1) { ... } else if (condition2) { ... } else { ... }` (multiple conditions checked sequentially).
    *   Nesting conditional statements (can become complex, consider alternatives like `switch` or functions for deep nesting).
    *   Using comparison (`>`, `<`, `===`, `!==`) and logical (`&&`, `||`, `!`) operators in conditions.
    *   Truthy/Falsy values in conditions (any non-falsy value is treated as `true`).
    *   **Example:**
        ```javascript
        let score = 75;
        let grade;
        if (score >= 90) {
            grade = 'A';
        } else if (score >= 80) {
            grade = 'B';
        } else if (score >= 70) {
            grade = 'C';
        } else {
            grade = 'D';
        }
        console.log(`Your grade is: ${grade}`); // Your grade is: C
        ```
    *   <YouTube videoId="s9wW2PpjmkE" title="JavaScript Control Flow - If/Else, Switch, Loops by Academind" /> (Focus on if/else)

*   **Lesson 5.12: Control Flow - `switch` Statement**
    *   An alternative to long `if...else if...else` chains for checking a variable against multiple discrete values (cases).
    *   Syntax:
        ```javascript
        switch (expression) { // expression is evaluated once
            case value1:
                // code block to execute if expression === value1
                break; // Important: exits the switch block
            case value2:
                // code block to execute if expression === value2
                break;
            // ... more cases
            default: // Optional
                // code block to execute if no case matches
        }
        ```
    *   The `break` statement is crucial to prevent "fall-through" (where execution continues into the next case block regardless of match).
    *   The `default` case is optional and executes if no other `case` matches the expression.
    *   Strict comparison (`===`) is used for matching `expression` with `case` values.
    *   Grouping cases: Multiple `case` statements can share the same code block if `break` is omitted strategically.
    *   **Example:** Handling different user roles or commands.
        ```javascript
        let day = new Date().getDay(); // 0 for Sunday, 1 for Monday, etc.
        let dayName;
        switch (day) {
            case 0: dayName = "Sunday"; break;
            case 1: dayName = "Monday"; break;
            // ... other days
            case 6: dayName = "Saturday"; break;
            default: dayName = "Unknown Day";
        }
        console.log(`Today is ${dayName}.`);
        ```
    *   <YouTube videoId_ JAVASCRIPT_SWITCH_STATEMENT_TUTORIAL_by_The_Net_Ninja title="JavaScript Switch Statement Tutorial by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId="s9wW2PpjmkE" title="JavaScript Control Flow - If/Else, Switch, Loops by Academind" /> (Focus on switch)

*   **Lesson 5.13: Loops - `for` Loop**
    *   Repeating a block of code a specific number of times.
    *   Syntax: `for (initialization; condition; finalExpression/increment) { // code block to repeat }`
        1.  `initialization`: Executed once before the loop starts (e.g., `let i = 0;`). Often declares a loop counter.
        2.  `condition`: Evaluated before each iteration. If `true`, the loop's code block executes. If `false`, the loop terminates.
        3.  `code block`: The statements to be executed in each iteration.
        4.  `finalExpression/increment`: Executed after each iteration (e.g., `i++`, `i += 2`). Typically updates the loop counter.
    *   **Example:** Printing numbers 0 to 4:
        ```javascript
        for (let i = 0; i < 5; i++) {
            console.log(i); // Outputs 0, 1, 2, 3, 4
        }
        ```
    *   Looping through arrays: `for (let i = 0; i < myArray.length; i++) { console.log(myArray[i]); }`
    *   `break` statement to exit a loop prematurely.
    *   `continue` statement to skip the current iteration and proceed to the next `finalExpression`.
    *   Nested `for` loops (loops inside other loops).
    *   <YouTube videoId_ JAVASCRIPT_FOR_LOOP_TUTORIAL_by_Programming_with_Mosh title="JavaScript For Loop Tutorial by Programming with Mosh" /> (Placeholder)
    *   <YouTube videoId="s9wW2PpjmkE" title="JavaScript Control Flow - If/Else, Switch, Loops by Academind" /> (Focus on for loop)

*   **Lesson 5.14: Loops - `while` and `do...while` Loops**
    *   **`while` loop:** Repeats a block of code as long as a specified condition remains true.
        *   Syntax: `while (condition) { // code block; // IMPORTANT: ensure condition eventually becomes false to avoid an infinite loop }`
        *   The `condition` is checked *before* each iteration. If initially false, the loop body never executes.
        *   **Example:**
            ```javascript
            let count = 0;
            while (count < 3) {
                console.log("Count is: " + count);
                count++; // Increment to eventually make condition false
            }
            ```
    *   **`do...while` loop:** Similar to `while`, but the code block is executed at least once, *before* the condition is checked at the end of the iteration.
        *   Syntax: `do { // code block } while (condition);`
        *   **Example:** Useful for scenarios where you need to perform an action at least once, like prompting for input.
            ```javascript
            let input;
            do {
                input = prompt("Enter 'exit' to quit:"); // Prompt is a browser function
            } while (input !== "exit" && input !== null); // Condition checked after the block
            console.log("Exited loop.");
            ```
    *   Choosing between `for`, `while`, and `do...while`: `for` is common for known iteration counts; `while` for unknown counts based on a condition; `do...while` when at least one execution is guaranteed.
    *   <YouTube videoId_ JAVASCRIPT_WHILE_AND_DO_WHILE_LOOPS_by_The_Net_Ninja title="JavaScript While and Do While Loops by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId="s9wW2PpjmkE" title="JavaScript Control Flow - If/Else, Switch, Loops by Academind" /> (Focus on while/do-while)

*   **Lesson 5.15: Introduction to Functions - Defining, Calling, Parameters, and Return Values**
    *   What are Functions? Reusable blocks of code designed to perform a particular task or calculate a value.
    *   Benefits: Code reusability (DRY - Don't Repeat Yourself), organization, modularity, abstraction (hiding complexity).
    *   **Function Declaration (Function Statement):**
        ```javascript
        // Defining the function
        function greet(name) { // 'name' is a parameter (a placeholder for an input)
            let message = "Hello, " + name + "!";
            return message; // Returns the calculated message
        }

        // Calling/invoking the function
        let myGreeting = greet("Alice"); // "Alice" is an argument (the actual value passed)
        console.log(myGreeting); // Output: Hello, Alice!
        ```
    *   **Function Expression:** Assigning an anonymous (or named) function to a variable.
        ```javascript
        const add = function(num1, num2) { // Anonymous function
            return num1 + num2;
        };
        let sum = add(5, 3); // sum is 8
        ```
    *   Function Hoisting: Function declarations are fully hoisted (can be called before defined). Function expressions are not hoisted in the same way (the variable declaration is hoisted, but the function assignment is not).
    *   **Parameters:** Variables listed in the function definition.
    *   **Arguments:** Actual values passed to the function when it is called.
    *   **Default Parameters (ES6+):** `function multiply(a, b = 1) { return a * b; }`
    *   **The `return` statement:** Specifies the value the function should output. If a function doesn't have a `return` statement, or has `return;` with no value, it implicitly returns `undefined`. A function execution stops once a `return` statement is encountered.
    *   <YouTube videoId="N8ap4k_1QEQ" title="JavaScript Functions - Tutorial for Beginners by Programming with Mosh" /> (Introduction and basics)
    *   <YouTube videoId_ JAVASCRIPT_FUNCTIONS_PARAMETERS_ARGUMENTS_RETURN_VALUES_by_Traversy_Media title="JavaScript Functions: Parameters, Arguments, Return Values by Traversy Media" /> (Placeholder)

---
### Module 6: DOM Manipulation, Events, and Basic Web Applications (Expanded)

This module focuses on how JavaScript interacts with HTML (the DOM) and handles user events to build dynamic web pages, with expanded lessons and a more structured project.

*   **Lesson 6.1: What is the DOM? Understanding the Document Object Model**
    *   The DOM is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content.
    *   The browser parses HTML into a tree-like structure of objects (nodes).
    *   Each HTML element becomes a node in the DOM tree.
    *   Types of Nodes: Element nodes, Text nodes, Attribute nodes, Comment nodes.
    *   The `document` object: The entry point to the DOM, representing the entire HTML document.
    *   Why manipulate the DOM? To create dynamic content, update styles, respond to user interactions without reloading the page.
    *   <YouTube videoId="WnILZLS5s4k" title="What is the DOM? Document Object Model Explained by Traversy Media" /> (Recap)
    *   <YouTube videoId_ DOM_TREE_EXPLAINED_VISUALLY_by_Fireship title="DOM Tree Explained Visually by Fireship" /> (Placeholder)

*   **Lesson 6.2: Selecting DOM Elements - Part 1 (Older Methods)**
    *   Accessing elements to manipulate them.
    *   `document.getElementById('idName')`: Selects a single element by its unique `id` attribute. Returns the element object or `null`.
        *   **Example:** `const mainTitle = document.getElementById('main-heading');`
    *   `document.getElementsByTagName('tagName')`: Selects all elements with the given tag name. Returns an `HTMLCollection` (live, array-like object).
        *   **Example:** `const allParagraphs = document.getElementsByTagName('p');`
    *   `document.getElementsByClassName('className')`: Selects all elements with the given class name. Returns an `HTMLCollection`.
        *   **Example:** `const highlightedItems = document.getElementsByClassName('highlight');`
    *   Understanding HTMLCollections: Live collections (update automatically if DOM changes), array-like (can access by index, has `length`), but not full arrays (lack array methods like `forEach` directly - need conversion or `for` loop).
    *   <YouTube videoId_ JAVASCRIPT_DOM_SELECTORS_GETELEMENTBYID_TAGNAME_CLASSNAME_by_The_Net_Ninja title="JavaScript DOM Selectors (getElementById, TagName, ClassName) by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId="0ik6X4DJKCc" title="JavaScript DOM Manipulation - Full Course for Beginners by freeCodeCamp.org" /> (Focus on older selectors)

*   **Lesson 6.3: Selecting DOM Elements - Part 2 (Modern Methods - Query Selectors)**
    *   `document.querySelector('cssSelector')`: Selects the *first* element that matches the specified CSS selector(s). Returns the element object or `null`.
        *   Can use any valid CSS selector (type, class, ID, attribute, combinators).
        *   **Example:** `const firstButton = document.querySelector('button.primary');`
        *   **Example:** `const mainContentDiv = document.querySelector('#main-content');`
    *   `document.querySelectorAll('cssSelector')`: Selects *all* elements that match the specified CSS selector(s). Returns a `NodeList` (static, array-like object).
        *   **Example:** `const allListItems = document.querySelectorAll('ul > li');`
    *   Understanding NodeLists: Static collections (don't update automatically if DOM changes after selection, unless it's a "live" NodeList from certain properties like `childNodes`). Array-like, and often have `forEach` method directly.
    *   `querySelector` and `querySelectorAll` are generally preferred for their flexibility.
    *   <YouTube videoId_ JAVASCRIPT_QUERYSELECTOR_AND_QUERYSELECTORALL_by_Web_Dev_Simplified title="JavaScript querySelector and querySelectorAll by Web Dev Simplified" /> (Placeholder)
    *   <YouTube videoId="0ik6X4DJKCc" title="JavaScript DOM Manipulation - Full Course for Beginners by freeCodeCamp.org" /> (Focus on query selectors)

*   **Lesson 6.4: Traversing the DOM - Navigating Parent, Child, and Sibling Nodes**
    *   Once an element is selected, you can navigate from it.
    *   **Parent Node:**
        *   `element.parentNode`: Returns the parent node (can be any node type).
        *   `element.parentElement`: Returns the parent element node (or `null` if parent is not an element).
    *   **Child Nodes:**
        *   `element.childNodes`: Returns a live `NodeList` of all child nodes (including text nodes - whitespace - and comment nodes).
        *   `element.children`: Returns a live `HTMLCollection` of only child *element* nodes. (Often more useful).
        *   `element.firstChild`: First child node (can be text).
        *   `element.lastChild`: Last child node (can be text).
        *   `element.firstElementChild`: First child *element* node.
        *   `element.lastElementChild`: Last child *element* node.
    *   **Sibling Nodes:**
        *   `element.previousSibling`, `element.nextSibling` (can be text nodes).
        *   `element.previousElementSibling`, `element.nextElementSibling` (element nodes only).
    *   <YouTube videoId_ JAVASCRIPT_DOM_TRAVERSAL_PARENT_CHILD_SIBLING_by_Traversy_Media title="JavaScript DOM Traversal (Parent, Child, Sibling) by Traversy Media" /> (Placeholder)
    *   <YouTube videoId_ NAVIGATING_THE_DOM_TREE_IN_JAVASCRIPT_by_Academind title="Navigating the DOM Tree in JavaScript by Academind" /> (Placeholder)

*   **Lesson 6.5: Modifying DOM Element Content - `innerHTML`, `textContent`, `innerText`**
    *   `element.innerHTML`: Gets or sets the HTML content (markup) within an element.
        *   Can be used to completely replace content, including HTML tags.
        *   **Security Risk:** If setting `innerHTML` with user-provided content, it can lead to Cross-Site Scripting (XSS) vulnerabilities if not sanitized.
        *   **Example (Setting):** `myDiv.innerHTML = '<h2>New Title</h2><p>New paragraph.</p>';`
    *   `element.textContent`: Gets or sets the text content of an element and all its descendants, ignoring HTML tags (tags are stripped).
        *   Safer for setting text content, as it doesn't parse HTML.
        *   **Example (Setting):** `myParagraph.textContent = "This is plain text, <strong>tags</strong> are ignored.";`
    *   `element.innerText`: Similar to `textContent`, but is "layout-aware." It considers CSS styling (e.g., hidden elements are not included) and approximates rendered text.
        *   Can be slower than `textContent`.
        *   Generally, `textContent` is preferred for performance and predictability when dealing with raw text.
    *   <YouTube videoId_ JAVASCRIPT_INNERHTML_VS_TEXTCONTENT_VS_INNERTEXT_by_Web_Dev_Simplified title="JavaScript innerHTML vs textContent vs innerText by Web Dev Simplified" /> (Placeholder)
    *   <YouTube videoId="0ik6X4DJKCc" title="JavaScript DOM Manipulation - Full Course for Beginners by freeCodeCamp.org" /> (Focus on content modification)

*   **Lesson 6.6: Modifying DOM Element Attributes - `getAttribute`, `setAttribute`, `removeAttribute`**
    *   Getting attribute values: `element.getAttribute('attributeName')`.
        *   **Example:** `let linkURL = myLink.getAttribute('href');`
    *   Setting attribute values: `element.setAttribute('attributeName', 'newValue')`.
        *   Creates the attribute if it doesn't exist.
        *   **Example:** `myImage.setAttribute('src', 'new_image.jpg');`
        *   **Example:** `myInput.setAttribute('disabled', ''); // or true`
    *   Removing attributes: `element.removeAttribute('attributeName')`.
        *   **Example:** `myInput.removeAttribute('disabled');`
    *   Direct property access for common attributes (e.g., `element.id`, `element.className`, `element.src`, `element.href`).
        *   These often reflect the attribute value but can sometimes differ (e.g., `href` property returns the full URL).
    *   <YouTube videoId_ JAVASCRIPT_DOM_ATTRIBUTES_GETATTRIBUTE_SETATTRIBUTE_by_The_Net_Ninja title="JavaScript DOM Attributes (getAttribute, setAttribute) by The Net Ninja" /> (Placeholder)

*   **Lesson 6.7: Modifying CSS Styles with JavaScript - `element.style` and `element.classList`**
    *   **Using `element.style` property:**
        *   Accesses inline styles of an element.
        *   CSS properties are written in camelCase (e.g., `backgroundColor` for `background-color`).
        *   Sets styles directly on the element (inline style).
        *   **Example:** `myDiv.style.color = 'blue'; myDiv.style.fontSize = '20px';`
        *   Less ideal for significant styling changes (better to use CSS classes).
    *   **Using `element.classList` property (DOMTokenList):** Preferred method for dynamic styling.
        *   `element.classList.add('className')`: Adds a CSS class.
        *   `element.classList.remove('className')`: Removes a CSS class.
        *   `element.classList.toggle('className')`: Adds class if not present, removes if present. Returns `true` if class was added, `false` if removed.
        *   `element.classList.contains('className')`: Checks if class is present, returns boolean.
        *   `element.classList.replace('oldClass', 'newClass')`.
        *   **Example:**
            ```css
            /* style.css */
            .active { background-color: yellow; font-weight: bold; }
            ```
            ```javascript
            // script.js
            const myElement = document.getElementById('item');
            myElement.classList.add('active'); // Applies styles from .active class
            // myElement.classList.toggle('active');
            ```
    *   <YouTube videoId_ JAVASCRIPT_CHANGING_CSS_STYLES_ELEMENT_STYLE_CLASSLIST_by_Traversy_Media title="JavaScript Changing CSS Styles (element.style, classList) by Traversy Media" /> (Placeholder)
    *   <YouTube videoId="0ik6X4DJKCc" title="JavaScript DOM Manipulation - Full Course for Beginners by freeCodeCamp.org" /> (Focus on style/class modification)

*   **Lesson 6.8: Creating and Adding DOM Elements - `createElement`, `appendChild`, `insertBefore`**
    *   `document.createElement('tagName')`: Creates a new HTML element.
        *   **Example:** `const newDiv = document.createElement('div');`
    *   Creating Text Nodes: `document.createTextNode('Some text')`.
    *   Adding elements to the DOM:
        *   `parentNode.appendChild(childNode)`: Adds `childNode` as the last child of `parentNode`.
            *   **Example:** `parentDiv.appendChild(newParagraph);`
        *   `parentNode.insertBefore(newNode, referenceNode)`: Inserts `newNode` before `referenceNode` (which must be a child of `parentNode`).
            *   **Example:** `list.insertBefore(newItem, list.firstElementChild);` (inserts at the beginning)
    *   Setting attributes and content for newly created elements before appending.
    *   **Example: Creating and adding a new list item:**
        ```javascript
        const ul = document.querySelector('ul.my-list');
        const newLi = document.createElement('li');
        newLi.textContent = "New Item 4";
        newLi.classList.add('list-item');
        ul.appendChild(newLi);
        ```
    *   <YouTube videoId_ JAVASCRIPT_CREATE_AND_APPEND_DOM_ELEMENTS_by_The_Net_Ninja title="JavaScript Create and Append DOM Elements by The Net Ninja" /> (Placeholder)

*   **Lesson 6.9: Removing and Replacing DOM Elements - `removeChild`, `replaceChild`, `element.remove()`**
    *   `parentNode.removeChild(childNode)`: Removes `childNode` from `parentNode`. The removed node still exists in memory and can be re-added.
        *   **Example:** `list.removeChild(list.children[1]);` // Removes the second list item
    *   `element.remove()` (Modern method): Removes the element itself from the DOM. Simpler.
        *   **Example:** `const itemToRemove = document.getElementById('old-item'); itemToRemove.remove();`
    *   `parentNode.replaceChild(newChild, oldChild)`: Replaces `oldChild` with `newChild`.
        *   **Example:** `parent.replaceChild(newItem, existingItem);`
    *   <YouTube videoId_ JAVASCRIPT_REMOVE_AND_REPLACE_DOM_ELEMENTS_by_Academind title="JavaScript Remove and Replace DOM Elements by Academind" /> (Placeholder)

*   **Lesson 6.10: Introduction to Events and Event Handling**
    *   What are Events? Actions or occurrences that happen in the browser, such as a user clicking a button, moving the mouse, pressing a key, a page finishing loading, a form being submitted, etc.
    *   Event-Driven Programming: JavaScript's model for interactivity. Code runs in response to events.
    *   **Event Handlers/Listeners:** Functions that are executed when a specific event occurs on a specific element.
    *   Three ways to handle events (with `addEventListener` being the preferred modern way):
        1.  Inline HTML event attributes (e.g., `<button onclick="myFunction()">Click</button>`) - Generally discouraged for separation of concerns.
        2.  DOM element properties (e.g., `myButton.onclick = function() { ... };`) - Better, but only one handler per event type per element.
        3.  `element.addEventListener('eventType', callbackFunction, [options/useCapture])` - Most flexible and recommended. Allows multiple listeners.
    *   <YouTube videoId="XEMhrfCMQ-Y" title="JavaScript Event Listeners - Crash Course by Traversy Media" /> (Recap)
    *   <YouTube videoId_ JAVASCRIPT_EVENTS_INTRODUCTION_by_Programming_with_Mosh title="JavaScript Events Introduction by Programming with Mosh" /> (Placeholder)

*   **Lesson 6.11: Common Event Types - Click, Mouse, Keyboard, Form, Load**
    *   **Mouse Events:**
        *   `click`, `dblclick`
        *   `mousedown`, `mouseup`
        *   `mouseover`, `mouseout` (fires when mouse leaves element or its children)
        *   `mouseenter`, `mouseleave` (fires only when mouse leaves the element itself, doesn't bubble from children)
        *   `mousemove`
    *   **Keyboard Events:**
        *   `keydown` (key is pressed down)
        *   `keyup` (key is released)
        *   `keypress` (character key is pressed - somewhat deprecated, `keydown` is often preferred)
    *   **Form Events:**
        *   `submit` (on the `<form>` element when submitted)
        *   `focus` (element gains focus)
        *   `blur` (element loses focus)
        *   `change` (value of an input, select, textarea changes and loses focus)
        *   `input` (value of an input or textarea changes - fires immediately)
    *   **Document/Window Events:**
        *   `load` (on `window` when page and all resources fully loaded)
        *   `DOMContentLoaded` (on `document` when HTML is fully parsed, scripts can run, but images/stylesheets may not be loaded yet - often preferred for starting JS logic).
    *   <YouTube videoId_ JAVASCRIPT_COMMON_EVENT_TYPES_by_The_Net_Ninja title="JavaScript Common Event Types by The Net Ninja" /> (Placeholder)

*   **Lesson 6.12: The `event` Object and `event.preventDefault()` / `event.stopPropagation()`**
    *   When an event occurs, an `event` object is automatically passed to the event handler function.
    *   The `event` object contains information about the event:
        *   `event.target`: The element that triggered the event.
        *   `event.currentTarget`: The element to which the event listener is attached (useful with event delegation).
        *   `event.type`: The type of event (e.g., "click").
        *   Keyboard event properties: `event.key`, `event.code`, `event.keyCode` (older), `event.altKey`, `event.ctrlKey`, `event.shiftKey`.
        *   Mouse event properties: `event.clientX`, `event.clientY`, `event.pageX`, `event.pageY`, `event.button`.
    *   `event.preventDefault()`: Prevents the browser's default action for that event.
        *   **Example:** Preventing a form from submitting traditionally to handle it with JavaScript (AJAX). Preventing a link from navigating.
    *   `event.stopPropagation()`: Stops the event from "bubbling" up the DOM tree to parent elements.
    *   Event Bubbling vs. Event Capturing (briefly explain, bubbling is default).
    *   <YouTube videoId_ JAVASCRIPT_EVENT_OBJECT_PREVENTDEFAULT_STOPPROPAGATION_by_Traversy_Media title="JavaScript Event Object, preventDefault, stopPropagation by Traversy Media" /> (Placeholder)
    *   <YouTube videoId_ EVENT_BUBBLING_AND_CAPTURING_IN_JAVASCRIPT_by_Web_Dev_Simplified title="Event Bubbling and Capturing in JavaScript by Web Dev Simplified" /> (Placeholder)

*   **Lesson 6.13: Event Delegation**
    *   What is Event Delegation? A pattern where you attach a single event listener to a parent element instead of attaching listeners to many individual child elements.
    *   How it works: Leverages event bubbling. The listener on the parent checks `event.target` to see if the event originated from a child element of interest.
    *   Benefits:
        *   Performance: Fewer event listeners to manage.
        *   Dynamic Content: Automatically works for child elements added to the parent *after* the listener was attached.
    *   **Example:** Handling clicks on list items by attaching one listener to the `<ul>` element.
        ```javascript
        const myList = document.getElementById('myList');
        myList.addEventListener('click', function(event) {
            if (event.target.tagName === 'LI') { // Or event.target.matches('li.item-class')
                console.log('Clicked on list item:', event.target.textContent);
            }
        });
        ```
    *   <YouTube videoId_ JAVASCRIPT_EVENT_DELEGATION_EXPLAINED_by_Kevin_Powell title="JavaScript Event Delegation Explained by Kevin Powell" /> (Placeholder)

*   **Lesson 6.14: Project - To-Do List Application - Part 1: HTML Structure and Basic Styling**
    *   Goal: Build a functional To-Do List application.
    *   **HTML Structure (`index.html`):**
        *   Input field for adding new tasks.
        *   "Add Task" button.
        *   An unordered list (`<ul>`) to display tasks.
        *   Basic page title and heading.
    *   **CSS Styling (`style.css`):**
        *   Basic styling for the input field, button, and list.
        *   Styling for completed tasks (e.g., line-through).
        *   (Keep styling simple to focus on JS functionality for now).
    *   Link CSS file to HTML. Create an empty `script.js` file and link it (deferred).
    *   <YouTube videoId_ BUILD_A_TODO_APP_HTML_CSS_JAVASCRIPT_by_Traversy_Media title="Build A Todo App With HTML, CSS & JavaScript by Traversy Media" /> (Watch for initial HTML/CSS setup phase)

*   **Lesson 6.15: Project - To-Do List Application - Part 2: Adding Tasks with JavaScript**
    *   **JavaScript Logic (`script.js`):**
        *   Select DOM elements: input field, add button, task list (`<ul>`).
        *   Event listener for the "Add Task" button (or form submission).
        *   Inside the event handler:
            *   Get the text value from the input field.
            *   Validate if the input is not empty.
            *   Create a new list item (`<li>`) element.
            *   Set its `textContent` to the task text.
            *   Create "Complete" and "Delete" buttons (or icons) and append them to the `<li>`.
            *   Append the new `<li>` to the `<ul>`.
            *   Clear the input field.
    *   Testing adding multiple tasks.
    *   <YouTube videoId_ JAVASCRIPT_TODO_LIST_TUTORIAL_ADDING_TASKS_by_Dev_Ed title="JavaScript ToDo List Tutorial - Adding Tasks by Dev Ed" /> (Placeholder)

*   **Lesson 6.16: Project - To-Do List Application - Part 3: Completing and Deleting Tasks**
    *   **JavaScript Logic (continued):**
        *   Use event delegation on the `<ul>` to handle clicks on "Complete" and "Delete" buttons.
        *   **Completing Tasks:**
            *   If "Complete" button is clicked, toggle a CSS class (e.g., `.completed`) on the parent `<li>` element to style it (e.g., line-through text, different color).
        *   **Deleting Tasks:**
            *   If "Delete" button is clicked, remove the parent `<li>` element from the DOM.
    *   Ensuring the correct task is targeted using `event.target` and DOM traversal (`.parentElement` or `.closest('li')`).
    *   Testing completion and deletion functionality.
    *   <YouTube videoId_ JAVASCRIPT_TODO_LIST_TUTORIAL_COMPLETE_DELETE_TASKS_by_Web_Dev_Simplified title="JavaScript ToDo List Tutorial - Complete & Delete Tasks by Web Dev Simplified" /> (Placeholder)

This completes the expansion of Module 6 for Course 2, and thus Course 2 as a whole.
