---
description: Learn the concept of Size Fits and its role in responsiveness.
---

# Working with Size Fits

Size Fits form the basis of Codelessly's auto-layout system. It's a fundamental concept that helps you achieve that pixel-perfect responsiveness.

To summarize, Size Fits let you define how a node **fits** inside a frame, row, or column. Whether it takes up all the available space or wraps around its children, taking the minimum space possible. Or, you can even provide it a fixed size manually.

Size Fits can be defined per axis, **horizontal** and **vertical**. Simply select the desired Size Fit from the dropdown, or, use the _Size Fit Selector_.

<figure><img src="../.gitbook/assets/Selecting Size Fits.gif" alt=""><figcaption></figcaption></figure>

## Fixed Size

By default, nodes are **fixed in size**. This means that they do not adjust their size according to the parent layout.

So, if a node is fixed size on the horizontal axis, it retains its width.

<figure><img src="../.gitbook/assets/Fixed in row.gif" alt=""><figcaption></figcaption></figure>

If a node is fixed size on the vertical axis, it retains its height.

<figure><img src="../.gitbook/assets/Fixed in column.gif" alt=""><figcaption></figcaption></figure>

## Fill Parent

This fit expands the node to the size of its direct parent.

So, if a node is set to fill parent on the horizontal axis, it expands its width to that of its parent.

<figure><img src="../.gitbook/assets/Fill in row.gif" alt=""><figcaption></figcaption></figure>

If a node is set to fill parent on the vertical axis, it expands its height to that of its parent.

<figure><img src="../.gitbook/assets/Fill in column.gif" alt=""><figcaption></figcaption></figure>

## Wrap Content

Contrary to _**fill parent**_, this fit depends on a node's children rather than its parent. If a node has children, _**wrap content**_ sets the node's dimensions to that of its children.

So, if a node wraps content horizontally, its width shrinks to that of its children.

<figure><img src="../.gitbook/assets/Wrap row.gif" alt=""><figcaption></figcaption></figure>

If a node wraps content vertically, its height shrinks to that of its children.

<figure><img src="../.gitbook/assets/Wrap column.gif" alt=""><figcaption></figcaption></figure>
