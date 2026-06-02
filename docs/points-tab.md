---
description: >-
  This guide is for an outdated version of Penpal (1.5.0) - please visit
  https://penpal.docs.animatable.co for the current user guide.
---

# Points tab

![](<img/pointstab (1).png>)

#### ![](img/points - up.svg)Move up,![](img/points - down.svg) Move down, ![](img/points - left.svg)Move left, ![](img/points - right.svg)Move right

These buttons move selected points by 1px, or 10px if you hold `Shift`. If you hold `Alt` when you click them, the tangents that belong to the points will be 'left behind' instead of moved with the points.

!!! warning
    Bear in mind that move, align, distribute and snap to pixels functions will behave parallel to the X and Y axes of whichever Space is active - composition, layer or shape group.

#### Align and Distribute

The Align and Distribute functions all move selected elements into a line, and correspond to panels found in Creative Cloud applications. They work _per path_ - you cannot align or distribute elements from _different paths_.&#x20;

#### ![](img/points - alignH.svg) Align horizontal, ![](img/points - alignL.svg) Align left, ![](img/points - alignR.svg) Align right&#x20;

Move selected points into a line at their horizontal center, leftmost point or rightmost point.

#### ![](img/points - alignV.svg) Align vertical, ![](img/points - alignT.svg) Align top, ![](img/points - alignB.svg) Align bottom

Move selected points into a line at their vertical center, topmost point or bottommost point..

#### ![](img/points - distributeH.svg) Distribute horizontally, ![](img/points - distributeV.svg) Distribute vertically

Distribute the selected points at even spaces between the left and rightmost points, or top and bottommost points.

#### ![](img/points - mirrorX.svg) Mirror points on the X axis, ![](img/points - mirrorY.svg) Mirror points on the Y axis

The mirror buttons require an open path with either the first or last point selected. They will then mirror the shape around that point.

#### ![](img/points - open (1).svg) Toggle open / closed at selected points

Use this button to quickly open a closed path between two points. Select two consecutive points, click the button, and the path will be opened at that segment.

!!! info
    Unlike the [similar button in the Paths tab](path-tab.md#toggle-open), this button opens the path _between selected points_, instead of always doing so at it's first vertex. Using this button can alter the first vertex.

If you select a path that is already open and click this button, it will simply be closed.

#### ![](img/points - split.svg) Break path

This button will break a path into two or more paths, at the selected points. Penpal generates new path objects in your layer, and turns off the old one.

If you select _only one point_ on a _closed_ path and click this button, it works a little differently. Instead of generating new paths, Penpal will **split** the path at the selected point, so that you have an open path which looks the same as the closed one (but has an extra point). This is essentially the same as using the Scissors tool in Adobe Illustrator.

#### ![](img/points - setFirst.svg) Set first vertex

This is exactly the same as After Effect’s native _Set First Vertex_ operation, and will set the selected point to be the first vertex.

#### ![](img/points - snap.svg) Snap to pixels

By default, this button will shift all selected points so that they are located on the nearest whole pixel. If you click the [Set Snap Value](points-tab.md#set-snap-value) button that appears below it, you can change the default snap value.

This snapping is relative to the active [Space](spaces.md), so it might only snap to the _actual composition pixels_ if you are in Comp space.

If you hold `Alt` while you click the snap button, tangents of selected points will also be snapped, as independent elements to the points.

#### ![](img/points - setSnap.svg) Set Snap value

Change the value for pixel snapping. A value of 10 would shift points to the nearest multiple of 10 pixels, eg 10, 20, 30 and so on. The value you enter is permanently stored, even after you restart After Effects.&#x20;
