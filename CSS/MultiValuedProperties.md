📦 padding and margin
padding: 10px 20px;

Syntax	Meaning
padding: 10px;	All four sides get 10px
padding: 10px 20px;	Top & Bottom = 10px
Left & Right = 20px
padding: 10px 20px 30px;	Top = 10px
Left & Right = 20px
Bottom = 30px
padding: 10px 20px 30px 40px;	Top = 10px
Right = 20px
Bottom = 30px
Left = 40px
📌 Mnemonic: TRouBLe → Top Right Bottom Left

Same structure applies for:

margin

border-width

border-radius (for corner rounding)

🔲 border-radius
border-radius: 10px 20px 30px 40px;

Value Count	Corners
1 value	All 4 corners
2 values	TL & BR = 10px, TR & BL = 20px
4 values	TL = 10px, TR = 20px, BR = 30px, BL = 40px
🔁 You can even use slash syntax to control horizontal / vertical radii:

border-radius: 10px 20px / 30px 40px;
⚡ transition property
transition: color 0.3s ease-in-out 1s;

Order	Value Description
property	What to animate (e.g., color, all)
duration	How long (e.g., 0.3s)
timing-function	Animation curve (e.g., ease, linear)
delay	Start delay (e.g., 1s)
✅ Example:

transition: all 0.5s ease-in;
📐 box-shadow
box-shadow: 2px 4px 6px rgba(0,0,0,0.3);

Part	Description
2px	Horizontal offset (x-axis)
4px	Vertical offset (y-axis)
6px	Blur radius
rgba(...)	Shadow color (with transparency)
👉 Can also include spread and inset:

box-shadow: 2px 2px 5px 0px #000 inset;
🎯 background
background: url("img.jpg") no-repeat center/cover;
Combines multiple shorthand properties:


Value	Role
url()	Image URL
no-repeat	Prevents repeating image
center/cover	Position and size (shorthand of background-position and background-size)
🔁 flex shorthand
flex: 1 0 200px;

Value	Meaning
1	Flex grow factor
0	Flex shrink factor
200px	Base width (flex-basis)
📌 If unsure, start with:

flex: 1; /* auto grow, no shrink, auto basis */
🎯 font shorthand
font: italic small-caps 700 16px/1.5 'Roboto', sans-serif;

Value	Meaning
italic	Font style
small-caps	Font variant
700	Font weight
16px/1.5	Font size / line-height
'Roboto', sans-serif	Font family
👉 Must include font-size and font-family at minimum.

🧠 BONUS: Multi-Value Color Syntax (RGBA & HSLA)
color: rgba(255, 0, 0, 0.5);  /* Red with 50% opacity */
color: hsla(120, 100%, 50%, 0.7); /* Greenish with 70% opacity */