🌈 1. What is CSS?
CSS (Cascading Style Sheets) is used to style HTML elements — controlling layout, colors, fonts, spacing, animations, and responsiveness.

✨ 2. Ways to Apply CSS
- Inline CSS
html
Copy
Edit
<p style="color:red;">Hello</p>
- Internal CSS
html
Copy
Edit
<style>
  p { color: red; }
</style>
- External CSS
html
Copy
Edit
<link rel="stylesheet" href="styles.css">
🔗 3. Selectors

Selector	Description	Example
*	Universal selector	* {margin: 0}
element	Tag selector	p {}
.class	Class selector	.btn {}
#id	ID selector	#header {}
element1, element2	Grouping	h1, h2 {}
parent > child	Direct child	div > p {}
parent descendant	All children	div p {}
element:hover	Pseudo-class	a:hover {}
element::before	Pseudo-element	p::before {content: "*"}
🎨 4. Styling Properties (Grouped)
📏 Box Model
margin, border, padding, width, height

div {
  margin: 10px;
  padding: 20px;
  border: 1px solid black;
  width: 100px;
}
🎨 Color & Background
color, background-color, background-image, background-size

body {
  background-color: #f4f4f4;
  color: #333;
}
🅰️ Text & Fonts
font-size, font-family, text-align, line-height, letter-spacing, text-transform, text-decoration

h1 {
  font-size: 24px;
  text-align: center;
  text-transform: uppercase;
}
📐 Layout & Display
display, position, float, clear, z-index, top/right/bottom/left

.box {
  position: absolute;
  top: 10px;
  left: 20px;
}
🧱 Flexbox
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
🔲 Grid
.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
}
📱 5. Responsive Design
Media Queries
@media (max-width: 768px) {
  body {
    background-color: lightblue;
  }
}
🎬 6. Animations & Transitions
Transitions
a {
  transition: color 0.3s ease;
}
a:hover {
  color: red;
}
Keyframe Animations
@keyframes fadeIn {
  from {opacity: 0;}
  to {opacity: 1;}
}
.box {
  animation: fadeIn 2s ease-in;
}
🛠️ 7. Useful Units
px (pixels)

em (relative to font-size)

rem (root em)

%, vw, vh (responsive)

fr (grid fraction)

🔤 8. Inheritance & Specificity
Inline > ID > Class > Tag

Use !important to override

p {
  color: red !important;
}
🎯 9. Positioning Techniques
static (default), relative, absolute, fixed, sticky

📦 10. Shorthand Properties
margin: 10px 20px 30px 40px;
padding: 10px 15px;
border: 1px solid black;
🎯 11. CSS Variables
:root {
  --main-color: #333;
}
p {
  color: var(--main-color);
}
📚 12. Advanced Topics (for extra prep)
calc(), clamp(), grid-template-areas

CSS functions: min(), max()

object-fit, aspect-ratio

Logical properties: margin-inline, padding-block