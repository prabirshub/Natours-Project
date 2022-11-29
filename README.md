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
