---
description: Learn the concept of Size Fits and its role in responsiveness.
---

# Working with Size Fits

Size Fits form the basis of Codelessly's auto-layout system. It's a fundamental concept that helps you achieve that pixel-perfect responsiveness.

To put in short, Size Fits let you define how a node **fits** inside a frame, row, or column. Whether it takes up all the available space or wraps around its children, taking the minimum space possible. Or, you can even provide it a fixed size manually.

Size Fits can be defined per axis, **horizontal** and **vertical**. Just select the desired Size Fit from the dropdown, or, use the _Size Fit Selector_.

> GIF: Selecting Size Fits using the dropdowns and the selector UI.

## Fixed Size

By default, nodes are **fixed size**. This means that they do no adjust their size according to the parent layout.

So, if a node is fixed size on the horizontal axis, it retains its width.

> GIF: Fixed size node inside a row. Row being resized horizontally.

If a node is fixed size on the vertical axis, it retains its height.

> GIF: Fixed size node inside a Column. Column being resized vertically.

## Fill Parent

This fit expands the node to the size of its direct parent.

So, if a node is set to fill parent on the horizontal axis, it expands its width to that of its parent.

> GIF: Horizontally expanded node inside a frame/row. Parent being resized.

If a node is set to fill parent on the vertical axis, it expands its height to that of its parent.

> GIF: Vertically expanded node inside a frame/column. Parent being resized.

## Wrap Content

Contrary to _**fill parent**_, this fit depends on a node's children rather than its parent. If a node has children, _**wrap content**_ sets the node's dimensions to that of its children.

So, if a node wraps content horizontally, its width shrinks to that of its children.

> GIF: Horizontally wrapped row with 3 children. First, row should be fixed size and children should have spacing. Then we select wrap content and the row shrinks.

If a node wraps content vertically, its height shrinks to that of its children.

> GIF: Vertically wrapped column with 3 children. First, column should be fixed size and children should have spacing. Then we select wrap content and the column shrinks.
