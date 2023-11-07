# Second Layout using CSS Properties

In this guide, we will explore different CSS properties that can be used to create effective layouts for your web projects.

#### We will cover the following properties step by step:

## Flexbox

Flexbox is a powerful CSS layout model that allows you to create flexible and responsive layouts. With flexbox, you can easily arrange elements in a row or column, adjust their alignment, spacing, and distribution. Here's a step-by-step guide to using flexbox:

- Set the container's display property to `display: flex;` to enable flexbox layout.
- Use the `flex-direction` property to define whether the elements should be laid out in a row (`row`), column (`column`), row-reverse (`row-reverse`), or column-reverse (`column-reverse`).
- Adjust the alignment of the elements along the main axis using `justify-content` property (e.g., `flex-start`, `flex-end`, `center`, `space-between`, `space-around`).
- Control the alignment of the elements along the cross-axis using `align-items` property (e.g., `flex-start`, `flex-end`, `center`, `baseline`, `stretch`).
- For finer control over individual items, use the `order`, `flex-grow`, `flex-shrink`, and `flex-basis` properties.

## CSS Grid

CSS Grid is another powerful layout model that provides a two-dimensional grid system. It allows you to create complex layouts with ease. Here's a step-by-step guide to using CSS Grid:

- Set the container's display property to `display: grid;` to enable grid layout.
- Define the grid structure using the `grid-template-rows` and `grid-template-columns` properties. You can specify the number of rows and columns and their sizes (e.g., `grid-template-rows: 1fr 2fr 1fr;` `grid-template-columns: 1fr 1fr 1fr;`).
- Place items within the grid using the `grid-row` and `grid-column` properties or the `grid-area` property.
- Adjust the size and spacing of grid tracks using the `grid-gap` property.
- Utilize additional properties like `justify-items`, `align-items`, `justify-content`, and `align-content` to align and distribute items within the grid.

## Positioning

CSS positioning allows you to precisely control the placement of elements on a webpage. Here's a step-by-step guide to using CSS positioning:

- Set the position property of the element to `position: relative;` to establish a positioning context.
- Use the `top`, `bottom`, `left`, and `right` properties to move the element within its positioning context.
- To position an element relative to its closest positioned ancestor, set its position property to `position: absolute;`.
- To position an element relative to the viewport, set its position property to `position: fixed;`.
- For more advanced positioning scenarios, you can also use the `z-index` property to control the stacking order of elements.

## My Second Dashboard Demo Website

#### Highly recommend showcasing my website demo at these specific settings

For the optimal viewing experience, I highly recommend showcasing my website demo at these specific settings. By setting the `zoom level to 110`, the content will be comfortably sized and ensure that every detail is easily visible. Additionally, with a `display resolution of 1920 x 1080`, the website's elements will be displayed in crisp clarity, allowing viewers to appreciate the design and functionality.

These settings will balance visibility and aesthetics perfectly, ensuring that the website demo is presented in its best form.

#### Demo Website :- [Utsav Technical Hub](https://socialmedia-management-dashboard.netlify.app/)

Remember to experiment with these CSS properties and adjust them to suit your specific layout requirements. By mastering flexbox, CSS Grid, and positioning, you'll have the necessary tools to create stunning and responsive layouts for your web projects.

Happy coding!
