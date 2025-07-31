# HB_FINAL_TASK2
1. CSS is a layout model for dynamically arranging elements in a container. float and inline-block are old and require a lot of code, but using flexbox allows the user to arrange, distribute, and center elements together in a convenient way.

2. justify-content: used for alignment along the main axis. align-item: used for alignment along the border axis. align-self: used for right alignment for individual flex items.

3. flex-direction:row for column, flex-direction:column for column


4. according to flex container: display:flex, flex-direction:column or row, justify-content:center, according to flex item: align-self, flex:..., order:1

5. flex-grow:
This property specifies how much a flex item will grow relative to the rest of the flex items inside the container when there is available space.
flex-shrink:
This property specifies how much a flex item will shrink relative to the rest of the flex items inside the container when there is not enough space.
flex-basis:
This property specifies the initial size of a flex item before any growing or shrinking occurs. It can be a length value (e.g., 100px, 50%), or auto (which uses the item's content size).

6. To build a responsive webpage using Flexbox 
Approach:
  -> Planning Structure
  Header: Navigation or branding area.
  Main Section: Content cards organized in a flexible layout.
  Footer: Links or additional info.
  -> Applying Flexbox
  Set display: flex on containers to activate Flexbox.
  Use flex-direction for layout flow (row or column).
  Add flex-wrap: wrap to allow items to shift on small screens.
  Use justify-content and align-items for alignment and spacing.
  Responsive Design
  Add media queries to adjust layout for smaller devices.
  Stack cards vertically or reduce padding/margin when screen width shrinks.



