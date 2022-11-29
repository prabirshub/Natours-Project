# Basic resposive design principles

## 1. Fluid Layouts

- To allow webpage to adapt to the current viewport width (or even height)
- Use % (or vh/vw) unit instead of px for elements that should adapt to viewport (usually layout)
- Use max-width instead of width

## 2. Responsive units

- Use rem units instead of px for most lengths
- To make it easy to Scale the entire layout down (or up) automatically

## 3. Flexible Images

- By default, images don't scale automatically as we change the viewport, so need to fix that
- Always use % for image dimesions, together with the max-width property

## 4. Media Queries

- To change CSS system on certain viewport widths (Called breakpoints)

## Layout types

1. Float Layouts
   - the **Old way of building layouts** of all sizes, using the float CSS property. Still used, but getting outdated. (Natours Project is based out of Float Layouts)

2. Flexbox
   - Modern way of laying out elements in a **1-dimensional** row without using floats. Persfect for **component layouts**.

3. CSS Grid
   - For laying out elemts in a fully-fledged **2-dimensional grid** perfect for **page layouts and complex components**
