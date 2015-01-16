# TextView

[back to view list](View_list.md#TextView)

class: `android.widget.TextView`

API level: `API 1`

parent: [View](View.md)

direct childs:

**API 1**

* [Button](Button.md)
* [CheckedTextView](CheckedTextView.md)
* [Chronometer](Chronometer.md)
* [DigitalClock](DigitalClock.md)
* [EditText](EditText.md)

**API 17**

* [TextClock](TextClock.md)

**API support_v17**

* [RowHeaderView](RowHeaderView.md)

## Attributes

API list:

* [API_1](#api_1)
* [API_2](#api_2)
* [API_3](#api_3)
* [API_11](#api_11)
* [API_14](#api_14)
* [API_16](#api_16)
* [API_21](#api_21)

### <a name="api_1"></a>API 1

[back to API list](#api_list)

attributes:

* [android:autoLink](#android_autoLink)
* [android:autoText](#android_autoText)
* [android:bufferType](#android_bufferType)
* [android:capitalize](#android_capitalize)
* [android:cursorVisible](#android_cursorVisible)
* [android:digits](#android_digits)
* [android:drawableBottom](#android_drawableBottom)
* [android:drawableLeft](#android_drawableLeft)
* [android:drawablePadding](#android_drawablePadding)
* [android:drawableRight](#android_drawableRight)
* [android:drawableTop](#android_drawableTop)
* [android:editable](#android_editable)
* [android:ellipsize](#android_ellipsize)
* [android:ems](#android_ems)
* [android:freezesText](#android_freezesText)
* [android:gravity](#android_gravity)
* [android:height](#android_height)
* [android:hint](#android_hint)
* [android:includeFontPadding](#android_includeFontPadding)
* [android:inputMethod](#android_inputMethod)
* [android:lineSpacingExtra](#android_lineSpacingExtra)
* [android:lineSpacingMultiplier](#android_lineSpacingMultiplier)
* [android:lines](#android_lines)
* [android:linksClickable](#android_linksClickable)
* [android:maxEms](#android_maxEms)
* [android:maxHeight](#android_maxHeight)
* [android:maxLength](#android_maxLength)
* [android:maxLines](#android_maxLines)
* [android:maxWidth](#android_maxWidth)
* [android:minEms](#android_minEms)
* [android:minHeight](#android_minHeight)
* [android:minLines](#android_minLines)
* [android:minWidth](#android_minWidth)
* [android:numeric](#android_numeric)
* [android:password](#android_password)
* [android:phoneNumber](#android_phoneNumber)
* [android:scrollHorizontally](#android_scrollHorizontally)
* [android:selectAllOnFocus](#android_selectAllOnFocus)
* [android:shadowColor](#android_shadowColor)
* [android:shadowDx](#android_shadowDx)
* [android:shadowDy](#android_shadowDy)
* [android:shadowRadius](#android_shadowRadius)
* [android:singleLine](#android_singleLine)
* [android:text](#android_text)
* [android:textAppearance](#android_textAppearance)
* [android:textColor](#android_textColor)
* [android:textColorHighlight](#android_textColorHighlight)
* [android:textColorHint](#android_textColorHint)
* [android:textColorLink](#android_textColorLink)
* [android:textScaleX](#android_textScaleX)
* [android:textSize](#android_textSize)
* [android:textStyle](#android_textStyle)
* [android:typeface](#android_typeface)
* [android:width](#android_width)

#### <a name="android_autoLink"></a>android:autoLink

[back to attribute list](#api_1)

format: [autoLink](../Formats.md#autoLink)

Controls whether links such as urls and email addresses are automatically found and converted to clickable links. The default value is "none", disabling this feature.

#### <a name="android_autoText"></a>android:autoText

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

If set, specifies that this TextView has a textual input method and automatically corrects some common spelling errors. The default is "false".

#### <a name="android_bufferType"></a>android:bufferType

[back to attribute list](#api_1)

format: [bufferType](../Formats.md#bufferType)

Determines the minimum type that getText() will return. The default is "normal". Note that EditText and LogTextBox always return Editable, even if you specify something less powerful here.

#### <a name="android_capitalize"></a>android:capitalize

[back to attribute list](#api_1)

format: [capitalize](../Formats.md#capitalize)

If set, specifies that this TextView has a textual input method and should automatically capitalize what the user types. The default is "none".

#### <a name="android_cursorVisible"></a>android:cursorVisible

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Makes the cursor visible (the default) or invisible.

#### <a name="android_digits"></a>android:digits

[back to attribute list](#api_1)

format: [string](../Formats.md#string) | [reference](../Formats.md#reference)

If set, specifies that this TextView has a numeric input method and that these specific characters are the ones that it will accept. If this is set, numeric is implied to be true. The default is false.

#### <a name="android_drawableBottom"></a>android:drawableBottom

[back to attribute list](#api_1)

format: [color](../Formats.md#color) | [reference](../Formats.md#reference)

The drawable to be drawn below the text.

#### <a name="android_drawableLeft"></a>android:drawableLeft

[back to attribute list](#api_1)

format: [color](../Formats.md#color) | [reference](../Formats.md#reference)

The drawable to be drawn to the left of the text.

#### <a name="android_drawablePadding"></a>android:drawablePadding

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

The padding between the drawables and the text.

#### <a name="android_drawableRight"></a>android:drawableRight

[back to attribute list](#api_1)

format: [color](../Formats.md#color) | [reference](../Formats.md#reference)

The drawable to be drawn to the right of the text.

#### <a name="android_drawableTop"></a>android:drawableTop

[back to attribute list](#api_1)

format: [color](../Formats.md#color) | [reference](../Formats.md#reference)

The drawable to be drawn above the text.

#### <a name="android_editable"></a>android:editable

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

If set, specifies that this TextView has an input method. It will be a textual one unless it has otherwise been specified. For TextView, this is false by default. For EditText, it is true by default.

#### <a name="android_ellipsize"></a>android:ellipsize

[back to attribute list](#api_1)

format: [ellipsize](../Formats.md#ellipsize)

If set, causes words that are longer than the view is wide to be ellipsized instead of broken in the middle. You will often also want to set scrollHorizontally or singleLine as well so that the text as a whole is also constrained to a single line instead of still allowed to be broken onto multiple lines.

#### <a name="android_ems"></a>android:ems

[back to attribute list](#api_1)

format: [integer](../Formats.md#integer) | [reference](../Formats.md#reference)

Makes the TextView be exactly this many ems wide.

#### <a name="android_freezesText"></a>android:freezesText

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

If set, the text view will include its current complete text inside of its frozen icicle in addition to meta-data such as the current cursor position. By default this is disabled; it can be useful when the contents of a text view is not stored in a persistent place such as a content provider.

#### <a name="android_gravity"></a>android:gravity

[back to attribute list](#api_1)

format: [gravity](../Formats.md#gravity)

Specifies how to align the text by the view's x- and/or y-axis when the text is smaller than the view.

#### <a name="android_height"></a>android:height

[back to attribute list](#api_1)

format: 

#### <a name="android_hint"></a>android:hint

[back to attribute list](#api_1)

format: 

#### <a name="android_includeFontPadding"></a>android:includeFontPadding

[back to attribute list](#api_1)

format: 

#### <a name="android_inputMethod"></a>android:inputMethod

[back to attribute list](#api_1)

format: 

#### <a name="android_lineSpacingExtra"></a>android:lineSpacingExtra

[back to attribute list](#api_1)

format: 

#### <a name="android_lineSpacingMultiplier"></a>android:lineSpacingMultiplier

[back to attribute list](#api_1)

format: 

#### <a name="android_lines"></a>android:lines

[back to attribute list](#api_1)

format: 

#### <a name="android_linksClickable"></a>android:linksClickable

[back to attribute list](#api_1)

format: 

#### <a name="android_maxEms"></a>android:maxEms

[back to attribute list](#api_1)

format: 

#### <a name="android_maxHeight"></a>android:maxHeight

[back to attribute list](#api_1)

format: 

#### <a name="android_maxLength"></a>android:maxLength

[back to attribute list](#api_1)

format: 

#### <a name="android_maxLines"></a>android:maxLines

[back to attribute list](#api_1)

format: 

#### <a name="android_maxWidth"></a>android:maxWidth

[back to attribute list](#api_1)

format: 

#### <a name="android_minEms"></a>android:minEms

[back to attribute list](#api_1)

format: 

#### <a name="android_minHeight"></a>android:minHeight

[back to attribute list](#api_1)

format: 

#### <a name="android_minLines"></a>android:minLines

[back to attribute list](#api_1)

format: 

#### <a name="android_minWidth"></a>android:minWidth

[back to attribute list](#api_1)

format: 

#### <a name="android_numeric"></a>android:numeric

[back to attribute list](#api_1)

format: 

#### <a name="android_password"></a>android:password

[back to attribute list](#api_1)

format: 

#### <a name="android_phoneNumber"></a>android:phoneNumber

[back to attribute list](#api_1)

format: 

#### <a name="android_scrollHorizontally"></a>android:scrollHorizontally

[back to attribute list](#api_1)

format: 

#### <a name="android_selectAllOnFocus"></a>android:selectAllOnFocus

[back to attribute list](#api_1)

format: 

#### <a name="android_shadowColor"></a>android:shadowColor

[back to attribute list](#api_1)

format: 

#### <a name="android_shadowDx"></a>android:shadowDx

[back to attribute list](#api_1)

format: 

#### <a name="android_shadowDy"></a>android:shadowDy

[back to attribute list](#api_1)

format: 

#### <a name="android_shadowRadius"></a>android:shadowRadius

[back to attribute list](#api_1)

format: 

#### <a name="android_singleLine"></a>android:singleLine

[back to attribute list](#api_1)

format: 

#### <a name="android_text"></a>android:text

[back to attribute list](#api_1)

format: 

#### <a name="android_textAppearance"></a>android:textAppearance

[back to attribute list](#api_1)

format: 

#### <a name="android_textColor"></a>android:textColor

[back to attribute list](#api_1)

format: 

#### <a name="android_textColorHighlight"></a>android:textColorHighlight

[back to attribute list](#api_1)

format: 

#### <a name="android_textColorHint"></a>android:textColorHint

[back to attribute list](#api_1)

format: 

#### <a name="android_textColorLink"></a>android:textColorLink

[back to attribute list](#api_1)

format: 

#### <a name="android_textScaleX"></a>android:textScaleX

[back to attribute list](#api_1)

format: 

#### <a name="android_textSize"></a>android:textSize

[back to attribute list](#api_1)

format: 

#### <a name="android_textStyle"></a>android:textStyle

[back to attribute list](#api_1)

format: 

#### <a name="android_typeface"></a>android:typeface

[back to attribute list](#api_1)

format: 

#### <a name="android_width"></a>android:width

[back to attribute list](#api_1)

format: 

### <a name="api_2"></a>API 2

[back to API list](#api_list)

attributes:

* [android:marqueeRepeatLimit](#android_marqueeRepeatLimit)

#### <a name="android_marqueeRepeatLimit"></a>android:marqueeRepeatLimit

[back to attribute list](#api_2)

format: 

### <a name="api_3"></a>API 3

[back to API list](#api_list)

attributes:

* [android:editorExtras](#android_editorExtras)
* [android:imeActionId](#android_imeActionId)
* [android:imeActionLabel](#android_imeActionLabel)
* [android:imeOptions](#android_imeOptions)
* [android:inputType](#android_inputType)
* [android:privateImeOptions](#android_privateImeOptions)

#### <a name="android_editorExtras"></a>android:editorExtras

[back to attribute list](#api_3)

format: [reference](../Formats.md#reference)

Reference to an **<input-extras>** XML resource containing additional data to supply to an input method, which is private to the implementation of the input method. This simply fills in the **EditorInfo.extras** field when the input method is connected.

#### <a name="android_imeActionId"></a>android:imeActionId

[back to attribute list](#api_3)

format: 

#### <a name="android_imeActionLabel"></a>android:imeActionLabel

[back to attribute list](#api_3)

format: 

#### <a name="android_imeOptions"></a>android:imeOptions

[back to attribute list](#api_3)

format: 

#### <a name="android_inputType"></a>android:inputType

[back to attribute list](#api_3)

format: 

#### <a name="android_privateImeOptions"></a>android:privateImeOptions

[back to attribute list](#api_3)

format: 

### <a name="api_11"></a>API 11

[back to API list](#api_list)

attributes:

* [android:textIsSelectable](#android_textIsSelectable)

#### <a name="android_textIsSelectable"></a>android:textIsSelectable

[back to attribute list](#api_11)

format: 

### <a name="api_14"></a>API 14

[back to API list](#api_list)

attributes:

* [android:drawableEnd](#android_drawableEnd)
* [android:drawableStart](#android_drawableStart)
* [android:textAllCaps](#android_textAllCaps)

#### <a name="android_drawableEnd"></a>android:drawableEnd

[back to attribute list](#api_14)

format: [color](../Formats.md#color) | [reference](../Formats.md#reference)

The drawable to be drawn to the end of the text.

#### <a name="android_drawableStart"></a>android:drawableStart

[back to attribute list](#api_14)

format: [color](../Formats.md#color) | [reference](../Formats.md#reference)

The drawable to be drawn to the start of the text.

#### <a name="android_textAllCaps"></a>android:textAllCaps

[back to attribute list](#api_14)

format: 

### <a name="api_16"></a>API 16

[back to API list](#api_list)

attributes:

* [android:fontFamily](#android_fontFamily)

#### <a name="android_fontFamily"></a>android:fontFamily

[back to attribute list](#api_16)

format: [string](../Formats.md#string) | [reference](../Formats.md#reference)

Font family (named by string) for the text.

### <a name="api_21"></a>API 21

[back to API list](#api_list)

attributes:

* [android:elegantTextHeight](#android_elegantTextHeight)
* [android:fontFeatureSettings](#android_fontFeatureSettings)
* [android:letterSpacing](#android_letterSpacing)

#### <a name="android_elegantTextHeight"></a>android:elegantTextHeight

[back to attribute list](#api_21)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Elegant text height, especially for less compacted complex script text.

#### <a name="android_fontFeatureSettings"></a>android:fontFeatureSettings

[back to attribute list](#api_21)

format: [string](../Formats.md#string) | [reference](../Formats.md#reference)

Font feature settings.

#### <a name="android_letterSpacing"></a>android:letterSpacing

[back to attribute list](#api_21)

format: 