# [fit] *Flexbox*

![inline](css3_logo.png)

^ Audio is on the next slide

---

![autoplay](flex.mp4)

The CSS3 Flexible Box, or flexbox, is a layout mode providing for the arrangement of elements on a page such that the elements behave predictably when the page layout must accommodate different screen sizes and different display devices. For many applications, the flexible box model provides an improvement over the block model in that it does not use floats, nor do the flex container's margins collapse with the margins of its contents.

---

The main idea is to give the container the ability to change the width and height of its children in order to fill the blank spaces better and to prevent layout issues

---

# [fit] `display: flex`
^ Show demo1

---

## Container
## Items
## Direction
## Properties

---

# Flex Container
```html
<ul style="display: flex"> <!-- container -->
    <li>Love</li>
    <li>Me</li>
    <li>Some</li>
    <li>Flexbox</li>
</ul>
```

---

# Flex Items
Immediate descendants are automatically flex items

```html
<ul style="display: flex">
    <li>Love</li> <!-- item -->
    <li>Me</li> <!-- item -->
    <li>Some</li> <!-- item -->
    <li>Flexbox</li> <!-- item -->
</ul>
```

---

# Direction and Axis
~~X/Y Axis~~

Main/Cross Axis

---

# Main Axis
`flex-direction: row`

![fit inline](flexbox-flex-direction-row.jpg)

[^1]

---

# Main Axis
`flex-direction: column`

![fit inline](flexbox-flex-direction-column.jpg)

[^1]

---

# [fit] Properties
# [fit] A non-exhaustive overview of flex properties

---

# Flex Container Properties
- flex-direction (shorthand flex-flow)
- flex-wrap (shorthand flex-flow)
- justify-content
- align-items
- align-content

---

# Flex Item Properties
- order
- flex-grow (shorthand flex)
- flex-shrink (shorthand flex)
- flex-basis (shorthand flex)
- align-self


--- 

# [fit] DEMOS

---

# Navigation
Simple horizontal navigation that evenly distributes space amongst all of the nav items

^ Try to get responses about how this would normally be pulled off

---

# Vertical Centering
lfldf*(explitive)*jldfsl;jklfdg*(explitive)*sio;lfjfsoi;dfgkj;
# [fit] JUST CENTER!

^ Try to get responses about how this would normally be pulled off

---

# Header Area w/ Logo
Logo on the left with a fixed width and variable content on the right(menu, search, etc)

![inline fit] (headerLogo.png)

^ Try to get responses about how this would normally be pulled off

---

# Media Object
Think Facebook comments.  Small image on the left and content area to the right

![inline fit] (comment.png)

^ Try to get responses about how this would normally be pulled off

---

# Sticky Footer Thing

---

# Form Fields

---

# Holy Grail
Simple horizontal navigation that evenly distributes space amongst all of the nav items

![inline fit] (holy-grail.png)

^ Try to get responses about how this would normally be pulled off


















[^1]: Image credit - [scotch.io](https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties).





^ NOTES
- holy grail, media object, header/logo, navigation, vertical centering

Left to do
- 1 comprehensive-esque demo of properties with boxes with comments for defaults, etc
- Navigation slide image
- Comment code out properly and make sure there is a good safety net
- Sticky footer, form fields, holy grail(not live)
- Make choice on media object image
- Ending slide - talk about how using flex box as needed and not automatically for everything, browser support, simple things like ordering
- Links to learning resources
- Pre-slides
- Timer