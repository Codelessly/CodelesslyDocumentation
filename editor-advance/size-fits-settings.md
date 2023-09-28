---
description: >-
  Learn about the advanced options of size fits to lay out the nodes exactly how
  you desire.
---

# Size Fits Settings

Certainly, size fits are not limited to just the three basic modes as discussed in the [working-with-size-fits.md](../editor-basics/working-with-size-fits.md "mention")section. You can further play with spacing, flex ratios and even define constraints.

## Spacing

In rows and columns, we often need to add some space in between the children. That's when we use **Spacers**.

You can add a spacer by hovering over a row's child in the _Spacing Section_ and tapping the plus button.

> GIF: Adding a spacer in a row.

Or, if you want equal spacing between all the children, you can define it next to spacing section's header.

> GIF: Define spacing for all children.

Same goes for column.

## Alignment

Alignment is an important aspect of responsiveness, especially when the row/column is set to fill parent. Children can be aligned the following ways:

### Main Axis

1. **Start**: Children are placed at the start of their parent. On the main axis, start means left for rows and top for columns.
2. **Center**: Children are aligned centrally on the horizonal axis for rows and on the vertical axis for columns.
3. **End**: Children are placed at the end of their parent. On the main axis, end means right for rows and bottom for columns.
4. **Space Between**: Children spread across their parent with equal space between them. No space added to both ends of the row/column.
5. **Space Around**: Children spread across their parent with equal space between them. Half of that space is added to both ends of the row/column.
6. **Space Evenly**: Children spread across their parent with equal space between them. Same space is added to both ends of the row/column.

### Cross Axis

1. **Start**: Children are placed at the start of their parent. On the cross axis, start means top for rows and left for columns.
2. **Center**: Children are aligned centrally on the vertical axis for rows and on the horizontal axis for columns.
3. **End**: Children are placed at the end of their parent. On the cross axis, end means bottom for rows and right for columns.
4. **Stretch**: Children expand to take up the entire space on the vertical axis for rows and on the horizontal axis for columns.

### Changing Alignment

Changing alignment is simple. Just select the preferred alignment from the spacing section.

> GIF: Selecting a main axis alignment and a cross axis alignment for a row and children changing their positions visibly.

## Flex Ratios

Flex ratios help us define how much space a node takes with respect to the available space. If
