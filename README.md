# Tech-Notes

# WEB TECHNOLOGIES

## INTRODUCTION TO WEB TECHNOLOGIES

Web Technology refers to the set of tools, languages, and techniques used to design, develop, and maintain websites and web applications that run on the internet or intranet.

A complete web application is built using three core client-side technologies:

* **HTML (HyperText Markup Language)** – Used to create the structure and content of web pages.
* **CSS (Cascading Style Sheets)** – Used to style and design the appearance of web pages.
* **JavaScript** – Used to add logic, interaction, and dynamic behavior to web pages.

Together, HTML, CSS, and JavaScript form the **front-end (client side)** of web development.

Browsers like Chrome, Firefox, Edge, etc., interpret these technologies and display the final output to users.

## INTRODUCTION TO HTML

### What is HTML?

HTML is a markup language used to create the structure and content of a web page.

It defines elements such as:

* Headings
* Paragraphs
* Images
* Links
* Tables
* Forms
* Multimedia

HTML tells the browser **what content exists** on the page, not how it should look.

### 🔹 Full Form of HTML

**HTML** stands for 👉 **HyperText Markup Language**

* **HyperText** → Text that contains links to other text or pages
* **Markup** → Uses tags to mark elements
* **Language** → Follows predefined rules and syntax

### 🔹 History of HTML

* 1989 – Invented by Tim Berners-Lee
* 1991 – First version of HTML released
* HTML 2.0 – Standardized version
* HTML 4.01 – Widely used for many years
* **HTML5 (2014)** – Major advancement including:

  * Audio and video support
  * Semantic elements (`<header>`, `<footer>`, `<section>`)
  * Improved forms and APIs

* HTML5 is the current and most widely used standard.

### 🔹 Characteristics of HTML

* Easy to learn and use
* Platform independent
* Case-insensitive
* Uses predefined tags
* Supports multimedia
* Works with CSS and JavaScript
* Interpreted by browsers (not compiled)

### 🔹 Output in HTML

HTML does not have output methods like programming languages.

* The output of HTML is the **rendered webpage displayed by the browser** after interpreting HTML tags.

## 🔹 HTML ELEMENTS (Expanded Explanation)

An HTML element is the fundamental building block of a webpage.
It tells the browser what type of content it is and how it should behave.

### Structure of an HTML element:

html
<tagname> Content </tagname>

* Opening tag – tells the browser the element starts here
* Content – text, image, or nested elements
* Closing tag – tells the browser the element ends here

 Some elements are **container elements**, while some are **void elements** (no closing tag, e.g., `<img>`, `<br>`, `<input>`).

## 🔹 TYPES OF ELEMENTS

### 1. Block-Level Elements

**Characteristics:**

* Always start on a new line
* Take 100% width of parent container
* Height & width can be controlled
* Used for sections, layout, grouping content

**Examples:**

* `<div>`, `<p>`, `<h1>`–`<h6>`, `<section>`, `<article>`

* Browsers stack block elements vertically.

### 2️⃣ Inline-Level Elements

**Characteristics:**

* Do not start on a new line
* Take only required space
* Width & height cannot be set
* Used for styling parts of text

**Examples:**

* `<span>`, `<a>`, `<b>`, `<i>`, `<strong>`

* Inline elements flow horizontally inside text.

## 🔹 ATTRIBUTES (Expanded)

Attributes provide extra information about an element.

html
<tag attribute="value">

**Why attributes matter:**

* Control behavior (`href`, `src`)
* Improve accessibility (`alt`, `title`)
* Enable styling & scripting (`id`, `class`)

## 🔹 ANCHOR TAG (`<a>`)

Used for navigation.

**Attributes:**

* `href` → destination
* `target` → where to open link

Values of `target`:

* `_self`
* `_blank`
* `_parent`
* `_top`

NOTE: Anchor tags are inline elements by default.

## 🔹 MEDIA TAGS

### 🖼 Image (`<img>`)

* Self-closing tag
* Uses `src` and `alt`
* Important for SEO & accessibility

### 🔊 Audio (`<audio>`)

* Plays sound files
* `controls` is important

### 🎥 Video (`<video>`)

* Plays video directly
* `poster`, `muted`, `autoplay` supported

### 🖥 Iframe (`<iframe>`)

* Embeds external content
* Used for YouTube, Maps

## TABLE TAGS

```html
<table>
  <tr>
    <th>Header</th>
    <td>Data</td>
  </tr>
</table>

* `<th>` – semantic meaning
* `<thead>`, `<tbody>`, `<tfoot>` – structure

Use tables only for tabular data.

## 🔹 FORMS

Used to collect user input.

**Attributes:**

* `action` – URL
* `method` – GET / POST


CSS (Cascading Style Sheets)

### 🔹 What is CSS?

CSS controls:

* Colors
* Fonts
* Layout
* Spacing
* Positioning
* Animations

### 🔹 History of CSS

* 1996 – Introduced by Håkon Wium Lie
* CSS1 – Basic styling
* CSS2 – Positioning
* CSS3 – Flexbox, Grid, Animations

### 🔹 Characteristics of CSS

* Separates content from design
* Improves reusability
* Reduces repetition
* Makes websites responsive

### 🔹 Ways to Add CSS

* Inline
* Internal
* External (Best practice)


## JavaScript

### Definition

JavaScript is a scripting or programming language used to add functionality to web pages.

### History

* Invented by Brenden Eich (1995)
* First name: **MOCHA → LiveScript → JavaScript**
* Standardized as **ECMAScript**
* ES6 (2015), Current: **ES14 (2023)**

### Characteristics of JavaScript

* High-level
* Interpreted
* Single-threaded
* Loosely typed
* Dynamic
* Synchronous
* Object-based

### Ways to Add JavaScript

* Internal
* External

### Output Methods

* `console.log()`
* `console.error()`
* `console.warn()`
* `document.write()`
* `alert()`
* `confirm()`
* `prompt()`

### Data Types

* Primitive
* Non-Primitive

### Functions, Scope, DOM, Events, Storage, Promises, Async/Await

## Possible Interview Questions on WEB TECH

### HTML

(List preserved)

### CSS

(List preserved)

### JavaScript

(List preserved)
