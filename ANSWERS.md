<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
The specificity of the classes are the same, single they are single class selectors. If there are conflicting styles, the rule that appears last will take priority over the others.

2. Describe the difference between `display: block;` and `display: inline;`.
Display block allows elements to take up the full width, forcing them to be on their own 'line'. When using display inline block, the element will only take up as much space as its content and does not force a new line.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
When using 'align-items: center' you are aligning elements vertically on the y axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
A fixed layout used fixed pixel values, and does not adjust to different screen sizes. An adaptive layout uses fixed-width layouts with different media queries to load the layouts depending on the screen size. Fluid layouts use percentages to scale elements depending on the viewport size. A resposive layout adjusts to all screen sizes, and is a combination of fluid/adaptive design.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
This is to ensure the container does not become too wide on the horizontal axis on different screen sizes.
