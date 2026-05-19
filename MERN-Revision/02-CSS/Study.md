# CSS Study Notes

CSS means Cascading Style Sheets. It controls layout, colors, spacing, typography, and responsive design.

Important topics:

- Box model: content, padding, border, margin
- Display: `block`, `inline`, `inline-block`, `none`, `flex`, `grid`
- Position: `static`, `relative`, `absolute`, `fixed`, `sticky`
- Flexbox: one-dimensional layout
- Grid: two-dimensional layout
- Specificity: inline style, id, class, tag
- z-index: stacking order
- Responsive design: media queries, fluid units, flexible layouts

Real-world example:

- Navbar: Flexbox
- Dashboard layout: Grid
- Modal: fixed position and z-index
- Mobile layout: media queries

Internal working:

- Browser builds CSSOM from CSS.
- CSSOM combines with DOM to create render tree.
- Browser calculates layout and paints pixels.

Common mistakes:

- Confusing margin and padding.
- Using `position: absolute` for full page layout.
- z-index not working because position is missing.
- Writing too many fixed widths.
- Not testing mobile layout.

Mini task:

- Build a responsive card grid: 3 columns desktop, 2 tablet, 1 mobile.

