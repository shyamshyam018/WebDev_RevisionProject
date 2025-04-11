# ✅ HTML Attributes and Their Usage

This document lists **commonly used HTML attributes**, grouped by their relevant elements and use-cases.

---

## 📌 Global Attributes (Can be used on most HTML elements)

| Attribute     | Description |
|---------------|-------------|
| `id`          | Unique identifier for the element. |
| `class`       | Specifies one or more class names for styling with CSS or JavaScript. |
| `style`       | Inline CSS styling for the element. |
| `title`       | Text to show on mouse hover (tooltip). |
| `hidden`      | Hides the element from view. |
| `data-*`      | Custom data attribute for JavaScript (e.g., `data-user="John"`). |
| `contenteditable` | Makes the element editable. |
| `dir`         | Sets text direction (`ltr`, `rtl`). |
| `lang`        | Specifies language code (e.g., `en`, `fr`). |
| `tabindex`    | Specifies the tab order. |
| `accesskey`   | Defines a keyboard shortcut. |
| `draggable`   | Boolean: makes an element draggable. |

---

## 🧱 `<a>` Anchor Tag

| Attribute     | Description |
|---------------|-------------|
| `href`        | URL of the link. |
| `target`      | Defines how to open the link (`_self`, `_blank`, `_parent`, `_top`). |
| `rel`         | Relationship between the current and linked page. |
| `download`    | Allows file to be downloaded. |

---

## 📷 `<img>` Image Tag

| Attribute     | Description |
|---------------|-------------|
| `src`         | Path to the image file. |
| `alt`         | Alternative text for accessibility. |
| `width`       | Width of image (px or %). |
| `height`      | Height of image. |
| `loading`     | Lazy loading behavior (`lazy`, `eager`). |

---

## 🎧 `<audio>` and `<video>`

| Attribute     | Description |
|---------------|-------------|
| `src`         | Path to media file. |
| `controls`    | Shows playback controls. |
| `autoplay`    | Starts playing automatically. |
| `loop`        | Repeats playback. |
| `muted`       | Starts with no sound. |
| `preload`     | Specifies if/how the media should be loaded. |

---

## 🖊️ `<input>`, `<textarea>`, `<select>`, `<button>`

| Attribute     | Description |
|---------------|-------------|
| `type`        | Type of input (`text`, `email`, `checkbox`, etc). |
| `name`        | Name used in form data. |
| `value`       | Default value. |
| `placeholder` | Hint for input. |
| `required`    | Makes field mandatory. |
| `disabled`    | Disables the input. |
| `readonly`    | Prevents user editing. |
| `checked`     | For `checkbox` or `radio`. |
| `maxlength`   | Max number of characters. |
| `min`, `max`  | Range limits for numbers. |
| `step`        | Step value for numbers. |
| `autofocus`   | Focuses on load. |
| `multiple`    | Allows multiple selections. |

---

## 📑 `<form>`

| Attribute     | Description |
|---------------|-------------|
| `action`      | URL where form submits data. |
| `method`      | HTTP method (`get`, `post`). |
| `enctype`     | Encoding (`application/x-www-form-urlencoded`, `multipart/form-data`). |
| `target`      | Where to display response (`_self`, `_blank`, etc). |
| `autocomplete`| Auto-fills previously entered values. |
| `novalidate`  | Disables form validation. |

---

## 🪟 `<iframe>`

| Attribute     | Description |
|---------------|-------------|
| `src`         | Embedded URL. |
| `width`, `height` | Size of the frame. |
| `title`       | Descriptive text for accessibility. |
| `loading`     | Lazy or eager loading. |
| `allow`       | Permissions (fullscreen, camera, etc). |
| `sandbox`     | Security rules for embedded content. |

---

## 🧾 `<table>`, `<td>`, `<th>`, `<tr>`, `<colgroup>`, `<caption>`

| Attribute     | Description |
|---------------|-------------|
| `border`      | Border width. |
| `colspan`     | Number of columns a cell spans. |
| `rowspan`     | Number of rows a cell spans. |
| `align`       | Horizontal alignment. |
| `valign`      | Vertical alignment. |
| `scope`       | Defines whether `<th>` is for row or col. |

---

## 🧩 `<script>` and `<style>`

| Attribute     | Description |
|---------------|-------------|
| `src`         | External JS file path. |
| `type`        | MIME type (e.g. `text/javascript`). |
| `defer`       | Runs after document parsed. |
| `async`       | Runs immediately, does not block parsing. |
| `media`       | Media queries for style tags. |

---

## 📄 `<meta>`

| Attribute     | Description |
|---------------|-------------|
| `charset`     | Character encoding (UTF-8). |
| `name`        | Name of meta-data (viewport, description, etc). |
| `content`     | Value of the meta-data. |
| `http-equiv`  | Provides HTTP header-like info. |

---

## 🧭 `<link>`

| Attribute     | Description |
|---------------|-------------|
| `rel`         | Relationship (`stylesheet`, `icon`, etc). |
| `href`        | Link to resource. |
| `type`        | MIME type of linked resource. |
| `media`       | Media queries (e.g., `screen`, `print`). |

---

## ⚙️ `<base>`

| Attribute     | Description |
|---------------|-------------|
| `href`        | Base URL for relative links. |
| `target`      | Default target for all links. |

---

✅ This list captures **most essential attributes** used in HTML for:
- Forms
- Media
- Tables
- Links
- Metadata
- Global usage

Let me know if you'd also like:
- Examples for each attribute?
- A cheat sheet for interview prep?
- Advanced tags like ARIA roles, custom elements, or Web Components?
- There can only be one <base> tag in a document. It must be placed inside the <head> tag.
- noopener	Blocks access to window.opener (security protection) 
- noreferrer Hides the referrer info & also blocks window.opener
- defer ensures non-blocking loading, and waits for DOM parsing to finish before executing the script — useful for layout-first strategies.



## ✅ 1. Boolean Attributes

These are **true if present**, **false if absent**. You don’t need to assign a value (e.g., use `required`, not `required="true"`).

| Attribute         | Used In                              | Description                           |
|------------------|---------------------------------------|---------------------------------------|
| `checked`         | `<input type="checkbox">`, `<radio>` | Marks checkbox/radio as selected      |
| `disabled`        | Forms (`<input>`, `<button>`, etc.)  | Disables the element                  |
| `readonly`        | `<input>`, `<textarea>`              | Makes element read-only               |
| `required`        | Form inputs                          | Makes input mandatory                 |
| `multiple`        | `<select>`, `<input type="file">`    | Allows multiple selections            |
| `autofocus`       | Form inputs                          | Focuses on element when page loads    |
| `selected`        | `<option>`                           | Marks option as selected              |
| `hidden`          | Global                               | Hides the element                     |
| `contenteditable` | Global                               | Makes element editable                |
| `draggable`       | Global                               | Enables dragging                      |
| `autoplay`        | `<audio>`, `<video>`                 | Auto-starts playback                  |
| `controls`        | `<audio>`, `<video>`                 | Shows player controls                 |
| `loop`            | `<audio>`, `<video>`                 | Loops playback                        |
| `muted`           | `<audio>`, `<video>`                 | Starts muted                          |
| `novalidate`      | `<form>`                             | Skips built-in validation             |
| `default`         | `<track>`, `<source>`                | Default track/source                  |
| `defer`           | `<script>`                           | Defers script execution               |
| `async`           | `<script>`                           | Executes script asynchronously        |
| `allowfullscreen` | `<iframe>`                           | Allows fullscreen display             |

---

## 📋 2. Regular Attributes (require values)

### 🔹 Global Attributes

| Attribute     | Example Values      |
|---------------|---------------------|
| `id`          | `main`, `nav1`      |
| `class`       | `header`, `btn-lg`  |
| `style`       | `color: red;`       |
| `title`       | `Tooltip text`      |
| `tabindex`    | `1`, `0`, `-1`      |
| `accesskey`   | `s`, `h`, `1`       |
| `lang`        | `en`, `fr`, `ar`    |
| `dir`         | `ltr`, `rtl`        |
| `data-*`      | `data-user="123"`   |

---

### 🔹 Form-Specific Attributes

| Attribute       | Typical Values                   |
|------------------|----------------------------------|
| `type`           | `text`, `number`, `email`, etc. |
| `name`           | `username`, `age`, `gender`     |
| `value`          | Default input value             |
| `placeholder`    | Guide text inside input         |
| `maxlength`      | Maximum characters              |
| `min`, `max`     | For numeric inputs              |
| `step`           | Step value                      |
| `pattern`        | Regex pattern                   |
| `action`         | URL to submit to                |
| `method`         | `GET`, `POST`                   |
| `enctype`        | `multipart/form-data`, etc.     |
| `target`         | `_blank`, `_self`, etc.         |
| `autocomplete`   | `on`, `off`                     |

---

### 🔹 Media Elements

| Element             | Attributes                                |
|---------------------|-------------------------------------------|
| `<img>`             | `src`, `alt`, `width`, `height`, `loading`|
| `<audio>`, `<video>`| `src`, `preload`, `poster`, etc.          |

---

### 🔹 Link, Meta, and Script

| Element     | Attributes                                    |
|-------------|-----------------------------------------------|
| `<a>`       | `href`, `target`, `rel`, `download`, `title`  |
| `<link>`    | `rel`, `href`, `media`, `type`                |
| `<meta>`    | `name`, `content`, `charset`, `http-equiv`    |
| `<script>`  | `src`, `type`, `defer`, `async`               |

---

### 🔹 Table-Specific Attributes

| Attribute    | Element         |
|--------------|-----------------|
| `colspan`    | `<td>`, `<th>`  |
| `rowspan`    | `<td>`, `<th>`  |
| `align`      | `<td>`, `<th>`  |
| `valign`     | `<td>`, `<th>`  |
| `scope`      | `<th>`          |

---

📘 *Tip: Use this sheet for quick reference while coding or preparing for interviews.*





