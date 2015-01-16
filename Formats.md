# <a name="Formats"></a>Formats

<a name="category"></a>category:

* [Common formats](#common_formats)
* [Enum formats](#enum_formats)

## <a name="common_formats"></a>Common formats

[back to category](#category)

format list:

* [boolean](#boolean)
* [color](#color)
* [dimemsion](#dimemsion)
* [float](#float)
* [integer](#integer)
* [string](#string)
* [reference](#reference)

### <a name="boolean"></a>boolean

[back to format list](#common_formats)

Must be a boolean value, either "***true***" or "***false***".

### <a name="color"></a>color

[back to format list](#common_formats)

May be a color value, in the form of "***#rgb***", "***#argb***", "***#rrggbb***", or "***#aarrggbb***".

### <a name="dimemsion"></a>dimemsion

[back to format list](#common_formats)

Must be a dimension value, which is a floating point number appended with a unit such as "***14.5sp***". Available units are: px (pixels), dp (density-independent pixels), sp (scaled pixels based on preferred font size), in (inches), mm (millimeters).

### <a name="float"></a>float

[back to format list](#common_formats)

Must be a floating point value, such as "***1.2***".

### <a name="integer"></a>integer

[back to format list](#common_formats)

May be an integer value, such as "***100***".

### <a name="string"></a>string

[back to format list](#Formats)

Must be a string value, using '\\\\;' to escape characters such as '\\\\n' or '\\\\uxxxx' for a unicode character.

### <a name="reference"></a>reference

[back to format list](#common_formats)

This may also be a reference to a resource (in the form "***@[package:]type:name***") or theme attribute (in the form "***?[package:][type:]name***") containing a value of this type.

## <a name="enum_formats"></a>Enum formats

[back to category](#category)

format list:

* [accessImportance](#accessImportance)
* [accessLive](#accessLive)
* [autoLink](#autoLink)
* [bufferType](#bufferType)
* [capitalize](#capitalize)
* [drawingCacheQuality](#drawingCacheQuality)
* [ellipsize](#ellipsize)
* [fadingEdges](#fadingEdges)
* [gravity](#gravity)
* [indeterminateBehavior](#indeterminateBehavior)
* [layerType](#layerType)
* [layoutDirection](#layoutDirection)
* [scaleType](#scaleType)
* [scrollbars](#scrollbars)
* [scrollbarStyle](#scrollbarStyle)
* [textAlignment](#textAlignment)
* [textDirection](#textDirection)
* [tintMode](#tintMode)
* [visibility](#visibility)

### <a name="accessImportance"></a>accessImportance

[back to format list](#enum_formats)

May be one of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|auto             |0|The system determines whether the view is important for accessibility - default (recommended).|
|yes              |1|The view is important for accessibility.|
|no               |2|The view is not important for accessibility.|
|noHideDescendants|4|The view is not important for accessibility, nor are any of its descendant views.|

### <a name="accessLive"></a>accessLive

[back to format list](#enum_formats)

May be one of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|none     |0|Accessibility services should not announce changes to this view.|
|polite   |1|Accessibility services should announce changes to this view.|
|assertive|2|Accessibility services should interrupt ongoing speech to immediately announce changes to this view.|

### <a name="autoLink"></a>autoLink

[back to format list](#enum_formats)

Must be one or more (separated by '|') of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|none |0x00|Match no patterns (default).|
|web  |0x01|Match Web URLs.|
|email|0x02|Match email addresses.|
|phone|0x04|Match phone numbers.|
|map  |0x08|Match map addresses.|
|all  |0x0f|Match all patterns (equivalent to web|email|phone|map).|

### <a name="bufferType"></a>bufferType

[back to format list](#enum_formats)

Must be one of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|normal   |0|Can return any CharSequence, possibly a Spanned one if the source text was Spanned.|
|spannable|1|Can only return Spannable.|
|editable |2|Can only return Spannable and Editable.|

### <a name="capitalize"></a>capitalize

[back to format list](#enum_formats)

Must be one of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|none      |0|Don't automatically capitalize anything.|
|sentences |1|Capitalize the first word of each sentence.|
|words     |2|Capitalize the first letter of every word.|
|characters|3|Capitalize every character.|

### <a name="drawingCacheQuality"></a>drawingCacheQuality

[back to format list](#enum_formats)

Must be one of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|auto|0|Lets the framework decide what quality level should be used for the drawing cache.|
|low |1|Low quality. When set to low quality, the drawing cache uses a lower color depth, thus losing precision in rendering gradients, but uses less memory.|
|high|2|High quality. When set to high quality, the drawing cache uses a higher color depth but uses more memory.|

### <a name="ellipsize"></a>ellipsize

[back to format list](#enum_formats)

Must be one of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|none   |0||
|start  |1||
|middle |2||
|end    |3||
|marquee|4||

### <a name="fadingEdges"></a>fadingEdges

[back to format list](#enum_formats)

Must be one or more (separated by '|') of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|none      |0x00000000|No edge is faded.|
|horizontal|0x00001000|Fades horizontal edges only.|
|vertical  |0x00002000|Fades vertical edges only.|

### <a name="gravity"></a>gravity

[back to format list](#enum_formats)

### <a name="indeterminateBehavior"></a>indeterminateBehavior

Must be one or more (separated by '|') of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|top              |0x30|Push object to the top of its container, not changing its size.|
|bottom           |0x50|Push object to the bottom of its container, not changing its size.|
|left             |0x03|Push object to the left of its container, not changing its size.|
|right            |0x05|Push object to the right of its container, not changing its size.|
|center_vertical  |0x10|Place object in the vertical center of its container, not changing its size.|
|fill_vertical    |0x70|Grow the vertical size of the object if needed so it completely fills its container.|
|center_horizontal|0x01|Place object in the horizontal center of its container, not changing its size.|
|fill_horizontal  |0x07|Grow the horizontal size of the object if needed so it completely fills its container.|
|center           |0x11|Place the object in the center of its container in both the vertical and horizontal axis, not changing its size.|
|fill             |0x77|Grow the horizontal and vertical size of the object if needed so it completely fills its container.|
|clip_vertical    |0x80|Additional option that can be set to have the top and/or bottom edges of the child clipped to its container's bounds. The clip will be based on the vertical gravity: a top gravity will clip the bottom edge, a bottom gravity will clip the top edge, and neither will clip both edges.|
|clip_horizontal  |0x08|Additional option that can be set to have the left and/or right edges of the child clipped to its container's bounds. The clip will be based on the horizontal gravity: a left gravity will clip the right edge, a right gravity will clip the left edge, and neither will clip both edges.|
|start            |0x00800003|Push object to the beginning of its container, not changing its size.|
|end              |0x00800005|Push object to the end of its container, not changing its size.|

[back to format list](#enum_formats)

Must be one of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|repeat|1|Progress starts over from 0.|
|cycle |2|Progress keeps the current value and goes back to 0.|

### <a name="layerType"></a>layerType

[back to format list](#enum_formats)

Must be one of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|none    |0|Don't use a layer.|
|software|1|Use a software layer. Refer to setLayerType(int, android.graphics.Paint) for more information.|
|hardware|2|Use a hardware layer. Refer to setLayerType(int, android.graphics.Paint) for more information.|

### <a name="layoutDirection"></a>layoutDirection

[back to format list](#enum_formats)

Must be one of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|ltr    |0|Left-to-Right|
|rtl    |1|Right-to-Left|
|inherit|2|Inherit from parent|
|locale |3|Locale|

### <a name="scaleType"></a>scaleType

[back to format list](#enum_formats)

Must be one of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|matrix      |0||
|fitXY       |1||
|fitStart    |2||
|fitCenter   |3||
|fitEnd      |4||
|center      |5||
|centerCrop  |6||
|centerInside|7||

### <a name="scrollbars"></a>scrollbars

[back to format list](#enum_formats)

Must be one or more (separated by '|') of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|none      |0x00000000|No scrollbar is displayed.|
|horizontal|0x00000100|Displays horizontal scrollbar only.|
|vertical  |0x00000200|Displays vertical scrollbar only.|

### <a name="scrollbarStyle"></a>scrollbarStyle

[back to format list](#enum_formats)

Must be one of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|insideOverlay |0x0       |Inside the padding and overlaid|
|insideInset   |0x01000000|Inside the padding and inset|
|outsideOverlay|0x02000000|Edge of the view and overlaid|
|outsideInset  |0x03000000|Edge of the view and inset|

### <a name="textAlignment"></a>textAlignment

[back to format list](#enum_formats)

May be one of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|inherit  |0|Default|
|gravity  |1|Default for the root view. The gravity determines the alignment, ALIGN_NORMAL, ALIGN_CENTER, or ALIGN_OPPOSITE, which are relative to each paragraph’s text direction|
|textStart|2|Align to the start of the paragraph, e.g. ALIGN_NORMAL.|
|textEnd  |3|Align to the end of the paragraph, e.g. ALIGN_OPPOSITE.|
|center   |4|Center the paragraph, e.g. ALIGN_CENTER.|
|viewStart|5|Align to the start of the view, which is ALIGN_LEFT if the view’s resolved layoutDirection is LTR, and ALIGN_RIGHT otherwise.|
|viewEnd  |6|Align to the end of the view, which is ALIGN_RIGHT if the view’s resolved layoutDirection is LTR, and ALIGN_LEFT otherwise|

### <a name="textDirection"></a>textDirection

[back to format list](#enum_formats)

May be one of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|inherit    |0|Default|
|firstStrong|1|Default for the root view. The first strong directional character determines the paragraph direction. If there is no strong directional character, the paragraph direction is the view’s resolved layout direction.|
|anyRtl     |2|The paragraph direction is RTL if it contains any strong RTL character, otherwise it is LTR if it contains any strong LTR characters. If there are neither, the paragraph direction is the view’s resolved layout direction.|
|ltr        |3|The paragraph direction is left to right.|
|rtl        |4|The paragraph direction is right to left.|
|locale     |5|The paragraph direction is coming from the system Locale.|

### <a name="tintMode"></a>tintMode

[back to format list](#enum_formats)

Must be one of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|src_over| 3|The tint is drawn on top of the drawable. [Sa + (1 - Sa)*Da, Rc = Sc + (1 - Sa)*Dc]|
|src_in  | 5|The tint is masked by the alpha channel of the drawable. The drawable’s color channels are thrown out. [Sa * Da, Sc * Da]|
|src_atop| 9|The tint is drawn above the drawable, but with the drawable’s alpha channel masking the result. [Da, Sc * Da + (1 - Sa) * Dc]|
|multiply|14|Multiplies the color and alpha channels of the drawable with those of the tint. [Sa * Da, Sc * Dc]|
|screen  |15|[Sa + Da - Sa * Da, Sc + Dc - Sc * Dc]|
|add     |16|Combines the tint and drawable color and alpha channels, clamping the result to valid color values. Saturate(S + D)|

### <a name="visibility"></a>visibility

[back to format list](#enum_formats)

Must be one of the following constant values.

|Constant|Value|Description|
|:-------|:----|:----------|
|visible  |0|Visible on screen; the default value.|
|invisible|1|Not displayed, but taken into account during layout (space is left for it).|
|gone     |2|Completely hidden, as if the view had not been added.|