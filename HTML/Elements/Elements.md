# 📘 Commonly Used HTML Tags and Their Usages

This is a list of the most commonly used HTML tags, categorized for better understanding.

---

## 🔹 Document Structure Tags

| Tag         | Description                                     |
|--------------|-------------------------------------------------|
| `<!DOCTYPE>` | Declares the document type and HTML version     |
| `<html>`     | Root element of an HTML document                |
| `<head>`     | Contains meta-information about the document    |
| `<body>`     | Contains the content of the web page            |

---

## 🔹 Metadata Tags (inside `<head>`)

| Tag         | Description                                      |
|--------------|--------------------------------------------------|
| `<title>`    | Sets the title in the browser tab                |
| `<meta>`     | Provides metadata like charset, viewport, etc.   |
| `<link>`     | Links external files like CSS                    |
| `<style>`    | Embeds CSS styles                                |
| `<script>`   | Embeds or references JavaScript code             |
| `<base>`     | Sets a base URL for relative links               |

---

## 🔹 Text Content Tags

| Tag       | Description                             |
|------------|-----------------------------------------|
| `<h1>` to `<h6>` | Headings from largest to smallest      |
| `<p>`      | Paragraph                               |
| `<br>`     | Line break                              |
| `<hr>`     | Horizontal rule                          |
| `<strong>` | Important/bold text                     |
| `<em>`     | Emphasized/italic text                  |
| `<blockquote>` | Quoted section of text                |

---

## 🔹 List Tags

| Tag       | Description                              |
|------------|------------------------------------------|
| `<ul>`     | Unordered (bulleted) list                |
| `<ol>`     | Ordered (numbered) list                  |
| `<li>`     | List item                                |
| `<dl>`     | Description list                         |
| `<dt>`     | Term in a description list               |
| `<dd>`     | Description of the term                  |

---

## 🔹 Link and Media Tags

| Tag        | Description                             |
|-------------|-----------------------------------------|
| `<a>`       | Creates hyperlinks                      |
| `<img>`     | Embeds images                           |
| `<video>`   | Embeds video content                    |
| `<audio>`   | Embeds audio content                    |
| `<source>`  | Defines media resource                  |
| `<iframe>`  | Embeds another HTML document            |

---

## 🔹 Table Tags

| Tag       | Description                              |
|------------|------------------------------------------|
| `<table>`  | Defines a table                          |
| `<tr>`     | Table row                                |
| `<td>`     | Table cell                               |
| `<th>`     | Table header cell                        |
| `<thead>`  | Table header section                     |
| `<tbody>`  | Table body section                       |
| `<tfoot>`  | Table footer section                     |
| `<caption>`| Table title/caption                      |
| `<colgroup>` | Group of columns                       |
| `<col>`    | Column properties                        |

---

## 🔹 Form Tags

| Tag        | Description                              |
|-------------|------------------------------------------|
| `<form>`    | Creates an input form                    |
| `<input>`   | Input field                              |
| `<textarea>`| Multi-line text input                    |
| `<button>`  | Clickable button                         |
| `<select>`  | Drop-down list                           |
| `<option>`  | Option in a drop-down list               |
| `<label>`   | Label for a form input                   |
| `<fieldset>`| Groups related form elements             |
| `<legend>`  | Title for `<fieldset>`                   |

---

## 🔹 Semantic Tags (HTML5)

| Tag           | Description                              |
|----------------|------------------------------------------|
| `<header>`     | Header section of a document/page        |
| `<footer>`     | Footer section of a document/page        |
| `<nav>`        | Navigation links                         |
| `<section>`    | Defines a section in the document        |
| `<article>`    | Defines independent, self-contained content |
| `<aside>`      | Content aside from the main content      |
| `<main>`       | Main content of the document             |
| `<figure>`     | Self-contained media content             |
| `<figcaption>` | Caption for `<figure>`                   |

---

## 🔹 Inline Tags

| Tag        | Description                             |
|-------------|-----------------------------------------|
| `<span>`    | Generic inline container                |
| `<b>`       | Bold text                               |
| `<i>`       | Italic text                             |
| `<u>`       | Underlined text                         |
| `<small>`   | Smaller text                            |
| `<mark>`    | Highlighted text                        |
| `<sup>`     | Superscript text                        |
| `<sub>`     | Subscript text                          |




# List of All Self-Closing / Singleton Tags in HTML

| Tag       | Description                                                   |
|-----------|---------------------------------------------------------------|
| `<area>`  | Defines an area inside an image-map                           |
| `<base>`  | Specifies the base URL for relative URLs                      |
| `<br>`    | Inserts a single line break                                   |
| `<col>`   | Specifies column properties for table columns                 |
| `<embed>` | Embeds external content (like videos, PDFs, etc.)             |
| `<hr>`    | Inserts a horizontal rule (thematic break)                    |
| `<img>`   | Embeds an image                                               |
| `<input>` | Creates an input field (text, checkbox, radio, etc.)         |
| `<link>`  | Links external resources (like CSS) to the document           |
| `<meta>`  | Provides metadata (like charset, viewport, etc.)              |
| `<source>`| Specifies multiple media resources for elements               |
| `<track>` | Provides text tracks for `<video>` or `<audio>`              |
| `<wbr>`   | Suggests a word break opportunity                             |

> ⚠️ Do **not** try to "close" them like `<img></img>` – it's incorrect.

---

## Important Points

1. HTML tags are **not case sensitive**: `<P>` means the same as `<p>`.
2. In HTML5, the `/` at the end is optional, but allowed (e.g., `<br>` or `<br />` both work).
3. UTF-8: A variable-width encoding where characters are represented by 1 to 4 bytes, making it efficient for storing text in memory and transmitting it over networks. 
4. UTF-16: A variable-width encoding that uses 2 or 4 bytes to represent characters. 
5. UTF-32: A fixed-width encoding that uses 4 bytes (32 bits) for each character. 
6. Meta tag -
            name="viewport" content="width=device-width, initial-scale=1"
            name="title" property="og:title" content="W3Schools.com"
            name="Keywords" content="HTML, Python, CSS, SQL, Java"
            name="Description" content="Well organized and easy to understand Web"
7. "semantic" refers to using tags that accurately reflect the meaning and structure of the content, rather than just its presentation, enhancing readability for both developers and search engines
examples : <header>, <nav>, <article>, <aside>, <main>, <footer> , <fig> , <figcaption>
8. Nesting a <button> inside <a> is not valid HTML. Use one or the other, not both.
9. <q> is meant for inline quotations and usually auto-wraps with quotation marks.
10. <span> is inline-only, and shouldn’t wrap block-level tags like <p>, <h1>, etc.



