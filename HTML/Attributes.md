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
