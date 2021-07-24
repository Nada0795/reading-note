# Layout

## Controlling the Position of Elements

1. ### Normal flow
Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one.
Even if you specify the width of the boxes and there is space for two elements to sit side-byside, they will not appear next
to each other. This is the default behavior (unless you tell the browser to do something else).


2. ### Relative Positioning
This moves an element from the position it would be in normal flow, shifting it to the top, right,
bottom, or left of where it would have been placed. This does not affect the position of
surrounding elements; they stay in the position they would be in in normal flow.


3. ### Absolute positioning
This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it
does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up).
Absolutely positioned elements move as users scroll up and down the page.


## Box Offset

1. ### Fixed Positioning
This is a form of absolute positioning that positions the element in relation to the browser window, as opposed
to the containing element. Elements with fixed positioning do not affect the position of surrounding elements and they
do not move when the user scrolls up or down the page.

2. ### Floating Elements
Floating an element allows you to take that element out
of normal flow and position it to the far left or right of a containing box. The floated
element becomes a block-level element around which other
content can flow.


## * position:static
In normal flow, each block-level element sits on top of the next one. Since this is the default
way in which browsers treat HTML elements, you do not need a CSS property to indicate
that elements should appear in normal flow, but the syntax
would be:
position: static;

## * position:relative
Relative positioning moves an element in relation to where it would have been in normal flow

## * position:absolute
When the position property is given a value of absolute, the box is taken out of normal
flow and no longer affects the position of other elements on the page


## * position:fixed
Fixed positioning is a type of absolute positioning that requires the position property
to have a value of fixed.


# float
The float property allows you to take an element in normal flow and place it as far to the left or right of the containing
element as possible. Anything else that sits inside the containing element will
flow around the element that is floated.