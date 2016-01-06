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
^ Show index page

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

^ Demo properties.php - container section

---

# Flex Item Properties
- order
- flex-grow (shorthand flex)
- flex-shrink (shorthand flex)
- flex-basis (shorthand flex)
- align-self

^ Demo properties.php - items section

--- 

# [fit] DEMOS

---

# Navigation
Simple horizontal navigation that evenly distributes space amongst all of the nav items

![inline fit] (menu.png)

^ Try to get responses about how this would normally be pulled off
`navigation.php`

---

# Vertical Centering
lfldf*(explitive)*jldfsl;jklfdg*(explitive)*sio;lfjfsoi;dfgkj;
# [fit] JUST CENTER!

^ Try to get responses about how this would normally be pulled off
`vcenter.php`

---

# Header Area w/ Logo
Logo on the left with a fixed width and variable content on the right(menu, search, etc)

![inline fit] (headerLogo.png)

^ Try to get responses about how this would normally be pulled off
`header-logo.php`

---

# Media Object
Think Facebook comments.  Small image on the left and content area to the right

![inline fit] (comment.png)

^ Try to get responses about how this would normally be pulled off
`media.php`

---

# Sticky Footer

^ Try to get responses about how this would normally be pulled off
`footer.php`

---

# Form Fields

^ Try to get responses about how this would normally be pulled off
`form.php`

---

# Flex-wrap this up

- ! All || nothing
- Browser Support
- Core Layout
- fine to use in simple and as needed scenarios

---

# Fine Resources
- [CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [flexbox.io](http://flexbox.io/)
- [DevTips YouTube](https://www.youtube.com/watch?v=G7EIAgfkhmg)
- [Flexy Boxes](http://the-echoplex.net/flexyboxes/)
















[^1]: Image credit - [scotch.io](https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties).