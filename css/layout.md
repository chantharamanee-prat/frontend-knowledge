# CSS Layout

## Table of contents
1. [Flex Box](#flex-box)
1. [Grid](#grid)
1. [Learning By Doing](#learning-by-doing)

## Flex Box
CSS Flex, or Flexible Box Layout, is a layout model in Cascading Style Sheets (CSS) that provides an efficient way to design and structure complex web layouts. It aims to distribute space along a single axis (either horizontally or vertically) and allows items within a container to be dynamically arranged, resized, and aligned.

Key features of CSS Flex include:

1. **Flex Container:**
   - To enable Flex layout, a container needs to be defined with `display: flex;` or `display: inline-flex;` property.
   - The container becomes a flex container, and its children become flex items.

2. **Flex Direction:**
   - Determines the primary axis of the flex container. Common values include `row` (horizontal), `column` (vertical), `row-reverse`, and `column-reverse`.

3. **Flex Items:**
   - Children of a flex container are automatically treated as flex items.
   - Each flex item can have its own sizing, alignment, and order within the container.

4. **Flex Wrap:**
   - Determines whether flex items should wrap onto multiple lines or stay on a single line.
   - Values include `nowrap`, `wrap`, and `wrap-reverse`.

5. **Flex Flow:**
   - A shorthand property combining `flex-direction` and `flex-wrap` to set both properties in a single declaration.

6. **Justify Content:**
   - Defines how extra space is distributed along the main axis.
   - Values include `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, and `space-evenly`.

7. **Align Items:**
   - Specifies how flex items are aligned along the cross axis.
   - Values include `flex-start`, `flex-end`, `center`, `baseline`, and `stretch`.

8. **Align Self:**
   - Allows individual flex items to override the `align-items` property for their own alignment.

9. **Align Content:**
   - Determines how multiple lines of flex items are aligned within the flex container along the cross axis.

10. **Flex Basis, Grow, and Shrink:**
    - `flex-basis` sets the initial size of a flex item.
    - `flex-grow` controls the ability of a flex item to grow.
    - `flex-shrink` controls the ability of a flex item to shrink.

CSS Flex is widely used to create responsive and dynamic layouts, making it easier to build interfaces that adapt to different screen sizes and orientations. It is a powerful tool for creating both simple and complex designs with more predictable behavior than traditional layout methods.

## Grid
CSS Grid is a layout model in Cascading Style Sheets (CSS) that enables the creation of two-dimensional grid-based layouts on a webpage. It provides precise control over the placement and sizing of elements in both rows and columns. Here are key features of CSS Grid:

1. **Grid Container:**
   - To enable Grid layout, a container needs to be defined with `display: grid;` property.
   - The container becomes a grid container, and its children become grid items.

2. **Grid Lines:**
   - The grid is defined by horizontal and vertical lines, creating rows and columns.
   - Grid lines are numbered starting from 1, and they can be referred to by their line numbers.

3. **Grid Template Rows and Columns:**
   - Grid layout allows you to define the size of rows and columns explicitly using properties like `grid-template-rows` and `grid-template-columns`.
   - Sizes can be set in pixels, percentages, or using other flexible units.

4. **Grid Template Areas:**
   - Allows the definition of named grid areas in the layout, making it easy to create complex arrangements.
   - Grid items can be placed into specific areas using the `grid-area` property.

5. **Grid Gap:**
   - Sets the spacing between rows and columns in the grid.
   - The `grid-row-gap` and `grid-column-gap` properties can be used to define different gap sizes for rows and columns.

6. **Grid Auto Rows and Columns:**
   - Automatically sizes rows and columns based on content or available space using properties like `grid-auto-rows` and `grid-auto-columns`.

7. **Grid Auto Flow:**
   - Determines the placement of items in the grid when there is extra space or when items are smaller than the grid container.
   - Values include `row`, `column`, `row dense`, and `column dense`.

8. **Justify and Align Properties:**
   - `justify-content` and `align-content` properties control the placement of the grid within the grid container.
   - `justify-items` and `align-items` properties control the alignment of items within each grid cell.

9. **Grid Line-based Placement:**
   - Items can be placed on the grid by specifying the start and end grid lines using `grid-row` and `grid-column` properties.

10. **Fractional Units:**
    - Allows the creation of flexible grid layouts by using fractional units like `fr` to distribute available space among columns or rows.

CSS Grid is widely used for building complex and responsive layouts, providing a powerful and intuitive system for handling both simple and intricate design requirements. It works well alongside other layout models, such as Flexbox, and is particularly effective for creating grid-based designs that adapt to various screen sizes and orientations.

## Learning By Doing
- Flex: https://flexboxfroggy.com/
- Grid: https://codepip.com/games/grid-garden/