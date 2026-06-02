---
description: >-
  This guide is for an outdated version of Penpal (1.5.0) - please visit
  https://penpal.docs.animatable.co for the current user guide.
---

# Tangents tab

![](<img/tangentsstab (1).png>)

!!! warning
    When dealing with tangents, remember that even a ‘zero’ tangent, is treated by Penpal as a selectable element. If you drag a marquee selection over a point with zero tangents, you’ll be selecting both tangents.

#### ![](img/points - up.svg) Move up,![](img/points - down.svg) Move down, ![](img/points - left.svg) Move left, ![](img/points - right.svg) Move right

These buttons move selected tangents by 1px, or 10px if you hold `Shift`

#### ![](img/tangents - copy.svg) Copy

Copies the selected tangents. You can copy _one_ or _both_ tangents _of a pair_. You cannot copy tangents from different points.

#### ![](img/tangents - paste.svg) Paste

Pastes the copied tangents to the selected tangents. You can paste to multiple tangents simultaneously.

If you copy **and** paste both In **and** Out tangents, they will paste in-to-in and out-to-out. If you copied **only one** tangent of a pair, and you paste to **only one** tangent, you will paste the tangent you copied, end of. Also see [Advanced tangent pasting](advanced-tangent-pasting.md) on the next page.

#### ![](img/tangents - zero.svg) Zero

Zero’s out the selected tangents. You can also zero tangents by pressing the `Backspace` (delete) key on your keyboard, when in the Tangents tab.

#### ![](img/tangents - flatV.svg) Flatten to vertical axis, ![](img/tangents - flatH.svg) Flatten to horizontal axis

Rotates selected tangents around their parent point, to the nearest spot on it's vertical or horizontal axis. These axes are in the current [Space](spaces.md).

#### ![](img/tangents - flipV.svg) Flip around vertical axis, ![](img/tangents - flipH.svg) Flip around horizontal axis

Rotates the selected tangents so that they flip over the vertical or horizontal axis of their parent point. These axes are in the current [Space](spaces.md)

#### ![](img/tangents - swap.svg) Swap

This button swaps a pair of tangents with one another.

#### ![](img/tangents - matchLength.svg) Match length

Makes the selected tangents the same length as their opposite. If you only selected _one_ tangent of a pair, it will become the same length as the other. If you select _both_ tangents of a pair, both will be altered to their average length.

#### ![](img/tangents - opposeAngle.svg) Match angle

Rotates a selected tangent so that it is exactly 180º to it's opposite, and set the point to _smooth_ (the tangent handles are linked to one another to maintain a straight line as you drag them around). If you select both tangents of a pair, their angles will be averaged and then each one set to +90º and -90º from this average.

#### &#x20;![](img/tangents - facePoint.svg) Align to point

Rotates a selected tangent so that it aligns directly toward it's neighbouring point. Eg. an In tangent will face toward the previous point and an Out tangent will face toward the next point.

#### ![](img/tangents - rotate.svg) Rotate

This button will rotate tangents by a value, specified in degrees, around their parent point. Holding the `Alt` key will make it rotate in the opposite direction. Hover over the button and click the gear icon to [Set Rotation value](tangents-tab.md#set-rotation-value).

#### ![](img/tangents - setRotate.svg) Set Rotation value

This button sets a value, in degrees, which the [Rotate](tangents-tab.md#rotate) button applies.
