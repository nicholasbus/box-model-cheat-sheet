# The CSS Box Model

## Crucial Topics:
- Width & Height
- Border
- Padding
- Margin
- Display Property
- Units (Percentages, EMS & REMS)

## Nice To Have:
- Border Radius

---

### The CSS Box Model
Every element is treated as a box. 

### Width and Height 
- The ```width``` CSS property sets and element's width. By default, it sets the width of the content area but if ```box-sizing``` is set to ```border-box```, it sets the width of the border area.
- The ```height``` CSS property sets and element's height. By default, it sets the height of the content area but if ```box-sizing``` is set to ```border-box```, it sets the height of the border area.

### Border & Border-Radius
- Border Width: Controls the thickness of the border.
- Border-Color: Controls the color of the border.
- Border-Style: Controls the line style - dashed, solid, etc.
- Border-Radius: Rounds the corners of an element's outer border edge.


### Padding
The space between the actual content box and the border of an element.
- Padding-left
- Padding-right
- Padding-bottom
- Padding-top
- Apply to all 4 sides: ```padding: value;```
- Vertical | Horizontal: ```padding: vertical horizontal```
- Top | Horizontal | Bottom: ```padding: top horizontal bottom```
- Top | Right | Bottom | Left: ```padding: top right bottom left```

### Margin
The space outside of an element's border between that element and something else.
- margin-left
- margin-right
- margin-bottom
- margin-top
- Apply to all 4 sides: ```margin: value;```
- Vertical | Horizontal: ```margin: vertical horizontal```
- Top | Horizontal | Bottom: ```margin: top horizontal bottom```
- Top | Right | Bottom | Left: ```margin: top right bottom left```

### Display
Inline elements fit in alongside other elements. Block level elements take up a whole "block" of space.

Display Property:
- Inline: Width and height are ignored. Margin and padding push elements away horizontally but not vertically.
- Block: Block elements break the flow of a document. Width, height, margin, and padding are respected.
- Inline-Block: Behaved like an inline element except witdh, height, margin, and padding are respected.

---

## Units

- Relative Units: EM, REM, VH, VW, %, etc.
- Absolute Units: PX, PT, CM, IN, MM

### Percentages:
Percentages are always relative to some other value. Sometimes the percentage is relative to the parent element and sometimes it is relative to a value from the element itself.

`width: 50%` - half the width of the parent
`line-height: 50%` - half the font-size of the element itself

### EMS
Em's are relative units. With font-size, 1em equals the font-size of the parent. 2em's is twice the size of the font-size of the patent, etc.

With other properties, 1em is equal to the computed font-size of the element itself.

## REMS
Root Ems. Relative to the root html element's font-size. Often easier to work with.

If the root font-size is 20px, 1rem is always 20px, 2rem is always 40px, etc.