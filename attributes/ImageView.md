# ImageView

[back to view list](View_list.md#ImageView)

class: `android.widget.ImageView`

API level: `API 1`

parent: [View](View.md)

direct childs:

**API 1**

* [ImageButton](ImageButton.md)

**API 5**

* [QuickContactBadge](QuickContactBadge.md)

## Attributes

<a name="api_list"></a>API list:

* [API_1](#api_1)
* [API_11](#api_11)
* [API_21](#api_21)

### <a name="api_1"></a>API 1

[back to API list](#api_list)

attributes:

* [android:adjustViewBounds](#android_adjustViewBounds)
* [android:baselineAlignBottom](#android_baselineAlignBottom)
* [android:cropToPadding](#android_cropToPadding)
* [android:maxHeight](#android_maxHeight)
* [android:maxWidth](#android_maxWidth)
* [android:scaleType](#android_scaleType)
* [android:src](#android_src)
* [android:tint](#android_tint)

#### <a name="android_adjustViewBounds"></a>android:adjustViewBounds

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Set this to true if you want the ImageView to adjust its bounds to preserve the aspect ratio of its drawable.

#### <a name="android_baselineAlignBottom"></a>android:baselineAlignBottom

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

The offset of the baseline within this view. See {see android.view.View#getBaseline} for details

#### <a name="android_cropToPadding"></a>android:cropToPadding

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

If true, the image will be cropped to fit within its padding.

#### <a name="android_maxHeight"></a>android:maxHeight

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

An optional argument to supply a maximum height for this view. See {see android.widget.ImageView#setMaxHeight} for details.

#### <a name="android_maxWidth"></a>android:maxWidth

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

An optional argument to supply a maximum width for this view. See {see android.widget.ImageView#setMaxWidth} for details.

#### <a name="android_scaleType"></a>android:scaleType

[back to attribute list](#api_1)

format: [scaleType](../Formats.md#scaleType)

Controls how the image should be resized or moved to match the size of this ImageView.

#### <a name="android_src"></a>android:src

[back to attribute list](#api_1)

format: [color](../Formats.md#color) | [reference](../Formats.md#reference)

Sets a drawable as the content of this ImageView.

#### <a name="android_tint"></a>android:tint

[back to attribute list](#api_1)

format: [color](../Formats.md#color) | [reference](../Formats.md#reference)

Set a tinting color for the image. By default, the tint will blend using SRC_ATOP mode.

### <a name="api_11"></a>API 11

[back to API list](#api_list)

attributes:

* [android:baseline](#android_baseline)

#### <a name="android_baseline"></a>android:baseline

[back to attribute list](#api_11)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

The offset of the baseline within this view. See {see android.view.View#getBaseline} for details

### <a name="api_21"></a>API 21

[back to API list](#api_list)

attributes:

* [android:tintMode](#android_tintMode)

#### <a name="android_tintMode"></a>android:tintMode

[back to attribute list](#api_21)

format: [tintMode](../Formats.md#tintMode)

Blending mode used to apply the image tint.