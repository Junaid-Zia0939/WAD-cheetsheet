**Collapsing Margins:**

When vertical margins collapse, they do not add, rather the larger margin wins.(Sibling Boxes)

When horizontal margins collapse, they add with each other.



**Gradient:**

Gradients are always applied to background image or background not background color.



**Types of Gradient:**

**Linear Gradient:** Moves from one side/corner to another.  **Syntax: linear-gradient(direction, color-1, color-2, ...)**

**Radial Gradient:** (Circular/Elliptical):Radiates outward from a specific point.  **Syntax: radial-gradient(shape at position, color-1, color-2)**

**Repeating Gradient:** Repeats a gradient pattern**. Syntax: repeating-linear-gradient(direction, color-1 start, color-1 end, color-2 start, color-2 end, ...)**



**Border-Boxing:** setting the width of element, the padding and border is fit on the top of it. To avoid this, we  set **border-sizing:border-box using \*.**



**Liquid Layouts:** The use of relative percentage units allows the element to occupy the space on the screen relative to the screen size or relative parent.

This allows to stretch and compress the layout of an element according to the screen or window size.

* **max-width:** A certain maximum width specified in pixels for an element beyond which it does not stretch even when the window size increases.
* **min-width:** A certain minimum width specified in pixels for an element beyond which it does not compress even when the window size become smaller.



**Overflow \& Scrollbars(overflow:auto(other options in place of auto:visible,scroll,hidden):**The scroll bar appears when the text overflow the size of the box.

* The auto works only when the height of the box is already set.



**Custom Fonts (@import):**It is used to download the font family of our choice in the user browser.

**Example:** @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700\&display=swap');

* The ('Poppins') inside the quotes can be used in font-family. **Example:** font-family: 'Poppins', sans-serif;



**Font Units \& Ancestry (px, em, rem):** How size changes when elements are nested inside one another?

* **px->** Exact pixel font size **for a specific text.**
* **em->** child font size becomes the multiple/division of parent size(Nesting follow the rule deep inside).
* **rem->** The child font size multiplies with or changes according to the root element size i-e font size defined in the HTML tag.



**Shadows (Box \& Text): Note:** Shadow become completely solid when blur=0px**.**

**Syntax:** 

* **Box Shadow:** box-shadow: \[X] \[Y] \[Blur] \[Spread] \[Color] \[inset];
* **Text Shadow:** text-shadow: \[X] \[Y] \[Blur] \[Color];
* Y: **positive Y**:moves shadow right behind the box  **Negative Y:**moves shadow left behind the box
* X: **positive X**:moves shadow down behind the box  **Negative X:**moves shadow top behind the box
* Use rgba(red, green, blue, alpha) for coloring to have control over the opacity.



**CSS Variables:** 

* **The Syntax (Declaration):** The syntax always starts with --. Example: --main-color: blue;
* Variable function (**var()**)is used to call variable: **var(--main-color);**
* **Declaring Global Variable:** It is declared using pseudo class **:root** which is actually the html root tag.
* :root { --main-color: blue; }































