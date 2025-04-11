<!DOCTYPE html>
Declares the document type and version of HTML (HTML5 here).

Must be the very first line.

Helps browsers render the page correctly.

<html lang="en" dir="ltr">
<html>: Root element of the HTML document.

lang="en": Sets language of the content to English. Important for accessibility and SEO.

dir="ltr": Text direction is Left-To-Right (used for languages like English).

<head>
Contains meta-information about the document that isn’t displayed on the webpage directly.

<meta charset="UTF-8">
Sets the character encoding to UTF-8, supporting most characters from all languages.

<meta name="description" content="HTML Attributes Example">
Helps search engines understand page content (SEO).

<meta name="viewport" content="width=device-width, initial-scale=1.0">
Makes the page responsive on different screen sizes (mobile-friendly).

<title title="HTML Attributes Demo">All HTML Attributes Demo</title>
Sets the title shown on the browser tab.

(Note: title inside title is redundant and usually not used—it’s a mistake here.)

<base href="https://example.com/" target="_blank">
Sets the base URL for all relative links on the page.

target="_blank": Default behavior is to open links in a new tab.

<link rel="stylesheet" href="styles.css" type="text/css" media="screen">
Links an external CSS file for styling.

media="screen" means it's applied when viewed on screens (not print).

<style type="text/css" media="screen">
Adds inline CSS styles.

css
Copy
Edit
.highlight { color: red; }
Targets elements with class .highlight and makes text red.

<script src="script.js" type="text/javascript" defer async></script>
Links an external JS file.

defer: Loads script after HTML parsing.

async: Loads script asynchronously (often used with external APIs).

Only one (defer or async) is commonly used—not both.

<body class="main-body" id="body1" ...>
class="main-body": Used by CSS/JS to select this body.

id="body1": Unique identifier.

style="...": Inline CSS styling.

data-theme="light": Custom attribute often used by JS.

contenteditable="false": Prevents user editing.

tabindex="1": Allows keyboard navigation.

accesskey="h": Shortcut key for accessibility.

draggable="true": Allows dragging the element.

hidden: Hides the element from rendering.

<a href="..." target="_blank" rel="..." download title="...">
Anchor tag (link).

href: Link destination.

target="_blank": Opens in a new tab.

rel="noopener noreferrer": Security improvement when using _blank.

download: Suggests file download instead of navigation.

title: Tooltip shown on hover.

<img src="..." alt="..." width="..." height="..." loading="lazy" title="..."/>
Displays an image.

src: Image path.

alt: Text shown if image fails (important for accessibility).

width/height: Sets dimensions.

loading="lazy": Delays loading until needed.

title: Tooltip on hover.

<form ...>
action: Where form data is sent.

method: POST sends data securely.

enctype="multipart/form-data": Required for file uploads.

target="_self": Opens result in the same tab.

autocomplete="on": Enables browser autofill.

novalidate: Skips HTML5 validation.

<input ...>
type="text": Text field.

name: Field name (sent to server).

placeholder: Hint text.

value: Pre-filled content.

required: Cannot submit without filling.

readonly: Uneditable.

disabled: Unusable by user.

maxlength/minlength: Limits length.

autofocus: Cursor focuses here on load.

Other input types:
type="number": Accepts numeric input.

min, max, step: Limit values.

type="checkbox": Toggle option.

checked: Default is checked.

type="radio": Select one option in a group.

type="file": File uploader.

multiple: Allows multiple file selection.

<textarea ...>
Multiline input.

rows/cols: Size of box.

placeholder, required: Same as above.

<select name="country" multiple>
Dropdown selection.

multiple: Can select multiple options.

<option value="in" selected>: Pre-selected option.

<button ...>
type="submit": Triggers form submit.

name, value: Sent to server.

disabled: Button is unclickable.

<iframe src="..." width="..." height="..." ...></iframe>
Embeds another page inside the current one.

title: Required for accessibility.

loading="lazy": Performance optimization.

allow="fullscreen": Allows full-screen display.

sandbox: Restricts embedded content for security.

<audio ...></audio>
Embeds audio file with player controls.

controls: Show play/pause.

autoplay: Starts automatically.

loop: Repeats.

muted: Starts muted.

preload: Loads file early (auto/metadata/none).

<video ...></video>
Similar to audio, but for video files.

<table border="1">
Creates a table.

border="1": Adds border around cells.

<caption>Sample Table</caption>
Table title shown above it.

<colgroup span="2" style="background-color: #ccc;"></colgroup>
Styles specific columns.

<thead>, <tbody>, <tr>, <td>, <th>
Structure the rows and cells.

scope="col": Improves accessibility.

align, valign, rowspan: Control layout.

<script>console.log(...)</script>
Inline JavaScript.

Runs when encountered or after DOM is ready.

✅ Summary
You’ve now seen how every HTML attribute works inside real tags with practical examples:

Layout: id, class, style

Forms: required, readonly, disabled, autofocus, placeholder

Media: src, autoplay, muted, preload, controls

Accessibility: title, aria-, tabindex, accesskey, lang

Optimization: lazy, async, defer, loading

