The flexible box layout module (usually referred to as flexbox) is a one-dimensional layout model for distributing space between items  and includes numerous alignment capabilities.
    When we describe flexbox as being one-dimensional we are describing the fact that flexbox deals with layout in one dimension at a time — either as a row or as a column. This can be contrasted with the two-dimensional model of CSS Grid Layout, which controls columns and rows together.

display keyboard of flexbox:
![alt text](image-2.png)

The two axes of flexbox
    When working with flexbox you need to think in terms of two axes — the main axis and the cross axis. The main axis is defined by the flex-direction property, and the cross axis runs perpendicular to it. Everything we do with flexbox refers back to these axes, so it is worth understanding how they work from the outset.

The main axis
The main axis is defined by flex-direction, which has four possible values:
    - row
    - row-reverse
    - column
    - column-reverse

Should you choose row or row-reverse, your main axis will run along the row in the inline direction.
Choose column or column-reverse and your main axis will run in the block direction, from the top of the page to the bottom.

![alt text](image-1.png)

flex-wrap => By default, flex items will all try to fit onto one line. You can change that and allow the items to wrap as needed with this property.
![alt text](image-3.png)
![alt text](image-4.png)

flex-flow => This is a shorthand for the flex-direction and flex-wrap properties, which together define the flex container’s main and cross axes. The default value is row nowrap.
![alt text](image-5.png)

Official Documentation: https://css-tricks.com/snippets/css/a-guide-to-flexbox/