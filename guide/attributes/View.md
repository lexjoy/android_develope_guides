# View

[back to view list](View_list.md#View)

class: `android.view.View`

API level: `API 1`

direct childs:

**API 1**

* [ViewStub](ViewStub.md)
* [AnalogClock](AnalogClock.md)
* [ImageView](ImageView.md)
* [ProgressBar](ProgressBar.md)
* [SurfaceView](SurfaceView.md)
* [TextView](TextView.md)
* [ViewGroup](ViewGroup.md)

**API 3**

* [KeyboardView](KeyboardView.md)

**API 14**

* [Space](#Space)
* [TextureView](TextureView.md)

**API support_v7**

* [MediaRouteButton](MediaRouteButton.md)
* [Space_v7](Space_v7)

## Attributes

<a name="api_list"></a>API list:

* [API_1](#api_1)
* [API_3](#api_3)
* [API_4](#api_4)
* [API_5](#api_5)
* [API_9](#api_9)
* [API_11](#api_11)
* [API_14](#api_14)
* [API_16](#api_16)
* [API_17](#api_17)
* [API_19](#api_19)
* [API_21](#api_21)

### <a name="api_1"></a>API 1

[back to API list](#api_list)

attributes:

* [android:background](#android_background)
* [android:clickable](#android_clickable)
* [android:drawingCacheQuality](#android_drawingCacheQuality)
* [android:duplicateParentState](#android_duplicateParentState)
* [android:fadingEdgeLength](#android_fadingEdgeLength)
* [android:fitsSystemWindows](#android_fitsSystemWindows)
* [android:focusable](#android_focusable)
* [android:focusableInTouchMode](#android_focusableInTouchMode)
* [android:id](#android_id)
* [android:keepScreenOn](#android_keepScreenOn)
* [android:longClickable](#android_longClickable)
* [android:minHeight](#android_minHeight)
* [android:minWidth](#android_minWidth)
* [android:nextFocusDown](#android_nextFocusDown)
* [android:nextFocusLeft](#android_nextFocusLeft)
* [android:nextFocusRight](#android_nextFocusRight)
* [android:nextFocusUp](#android_nextFocusUp)
* [android:padding](#android_padding)
* [android:paddingBottom](#android_paddingBottom)
* [android:paddingLeft](#android_paddingLeft)
* [android:paddingRight](#android_paddingRight)
* [android:paddingTop](#android_paddingTop)
* [android:saveEnabled](#android_saveEnabled)
* [android:scrollX](#android_scrollX)
* [android:scrollY](#android_scrollY)
* [android:scrollbarAlwaysDrawHorizontalTrack](#android_scrollbarAlwaysDrawHorizontalTrack)
* [android:scrollbarAlwaysDrawVerticalTrack](#android_scrollbarAlwaysDrawVerticalTrack)
* [android:scrollbarSize](#android_scrollbarSize)
* [android:scrollbarStyle](#android_scrollbarStyle)
* [android:scrollbarThumbHorizontal](#android_scrollbarThumbHorizontal)
* [android:scrollbarThumbVertical](#android_scrollbarThumbVertical)
* [android:scrollbarTrackHorizontal](#android_scrollbarTrackHorizontal)
* [android:scrollbarTrackVertical](#android_scrollbarTrackVertical)
* [android:scrollbars](#android_scrollbars)
* [android:soundEffectsEnabled](#android_soundEffectsEnabled)
* [android:tag](#android_tag)
* [android:visibility](#android_visibility)

#### <a name="android_background"></a>android:background

[back to attribute list](#api_1)

format: [color](../Formats.md#color) | [reference](../Formats.md#reference)

A drawable to use as the background. This can be either a reference to a full drawable resource (such as a PNG image, 9-patch, XML state list description, etc), or a solid color such as "#ff000000" (black).

#### <a name="android_clickable"></a>android:clickable

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Defines whether this view reacts to click events.

#### <a name="android_drawingCacheQuality"></a>android:drawingCacheQuality

[back to attribute list](#api_1)

format: [drawingCacheQuality](../Formats.md#drawingCacheQuality)

Defines the quality of translucent drawing caches. This property is used only when the drawing cache is enabled and translucent. The default value is auto.

#### <a name="android_duplicateParentState"></a>android:duplicateParentState

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

When this attribute is set to true, the view gets its drawable state (focused, pressed, etc.) from its direct parent rather than from itself.

#### <a name="android_fadingEdgeLength"></a>android:fadingEdgeLength

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

Defines the length of the fading edges.

#### <a name="android_fitsSystemWindows"></a>android:fitsSystemWindows

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Boolean internal attribute to adjust view layout based on system windows such as the status bar. If true, adjusts the padding of this view to leave space for the system windows. Will only take effect if this view is in a non-embedded activity.

#### <a name="android_focusable"></a>android:focusable

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Boolean that controls whether a view can take focus. By default the user can not move focus to a view; by setting this attribute to true the view is allowed to take focus. This value does not impact the behavior of directly calling **requestFocus()**, which will always request focus regardless of this view. It only impacts where focus navigation will try to move focus.

#### <a name="android_focusableInTouchMode"></a>android:focusableInTouchMode

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Boolean that controls whether a view can take focus while in touch mode. If this is true for a view, that view can gain focus when clicked on, and can keep focus if another view is clicked on that doesn't have this attribute set to true.

#### <a name="android_id"></a>android:id

[back to attribute list](#api_1)

format: [reference](../Formats.md#reference)

Supply an identifier name for this view, to later retrieve it with **View.findViewById()** or **Activity.findViewById()**. This must be a resource reference; typically you set this using the @+ syntax to create a new ID resources. For example: **android:id="@+id/my_id"** which allows you to later retrieve the view with **findViewById(R.id.my_id)**.

#### <a name="android_keepScreenOn"></a>android:keepScreenOn

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Controls whether the view's window should keep the screen on while visible.

#### <a name="android_longClickable"></a>android:longClickable

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Defines whether this view reacts to long click events.

#### <a name="android_minHeight"></a>android:minHeight

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

Defines the minimum height of the view. It is not guaranteed the view will be able to achieve this minimum height (for example, if its parent layout constrains it with less available height).

#### <a name="android_minWidth"></a>android:minWidth

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

Defines the minimum width of the view. It is not guaranteed the view will be able to achieve this minimum width (for example, if its parent layout constrains it with less available width).

#### <a name="android_nextFocusDown"></a>android:nextFocusDown

[back to attribute list](#api_1)

format: [reference](../Formats.md#reference)

Defines the next view to give focus to when the next focus is **FOCUS_DOWN** If the reference refers to a view that does not exist or is part of a hierarchy that is invisible, a **RuntimeException** will result when the reference is accessed.

#### <a name="android_nextFocusLeft"></a>android:nextFocusLeft

[back to attribute list](#api_1)

format: [reference](../Formats.md#reference)

Defines the next view to give focus to when the next focus is **FOCUS_LEFT**. If the reference refers to a view that does not exist or is part of a hierarchy that is invisible, a **RuntimeException** will result when the reference is accessed.

#### <a name="android_nextFocusRight"></a>android:nextFocusRight

[back to attribute list](#api_1)

format: [reference](../Formats.md#reference)

Defines the next view to give focus to when the next focus is **FOCUS_RIGHT**. If the reference refers to a view that does not exist or is part of a hierarchy that is invisible, a **RuntimeException** will result when the reference is accessed.

#### <a name="android_nextFocusUp"></a>android:nextFocusUp

[back to attribute list](#api_1)

format: [reference](../Formats.md#reference)

Defines the next view to give focus to when the next focus is **FOCUS_UP**. If the reference refers to a view that does not exist or is part of a hierarchy that is invisible, a **RuntimeException** will result when the reference is accessed.

#### <a name="android_padding"></a>android:padding

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

Sets the padding, in pixels, of all four edges. Padding is defined as space between the edges of the view and the view's content. A views size will include it's padding. If a **background** is provided, the padding will initially be set to that (0 if the drawable does not have padding). Explicitly setting a padding value will override the corresponding padding found in the background.

#### <a name="android_paddingBottom"></a>android:paddingBottom

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

Sets the padding, in pixels, of the bottom edge; see [padding](#android_padding).

#### <a name="android_paddingLeft"></a>android:paddingLeft

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

Sets the padding, in pixels, of the left edge; see [padding](#android_padding).

#### <a name="android_paddingRight"></a>android:paddingRight

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

Sets the padding, in pixels, of the right edge; see [padding](#android_padding).

#### <a name="android_paddingTop"></a>android:paddingTop

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

Sets the padding, in pixels, of the top edge; see [padding](#android_padding).

#### <a name="android_saveEnabled"></a>android:saveEnabled

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

If unset, no state will be saved for this view when it is being frozen. The default is true, allowing the view to be saved (however it also must have an ID assigned to it for its state to be saved). Setting this to false only disables the state for this view, not for its children which may still be saved.

#### <a name="android_scrollX"></a>android:scrollX

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

The initial horizontal scroll offset, in pixels.

#### <a name="android_scrollY"></a>android:scrollY

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

The initial vertical scroll offset, in pixels.

#### <a name="android_scrollbarAlwaysDrawHorizontalTrack"></a>android:scrollbarAlwaysDrawHorizontalTrack

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Defines whether the horizontal scrollbar track should always be drawn.

#### <a name="android_scrollbarAlwaysDrawVerticalTrack"></a>android:scrollbarAlwaysDrawVerticalTrack

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Defines whether the vertical scrollbar track should always be drawn.

#### <a name="android_scrollbarSize"></a>android:scrollbarSize

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

Sets the width of vertical scrollbars and height of horizontal scrollbars.

#### <a name="android_scrollbarStyle"></a>android:scrollbarStyle

[back to attribute list](#api_1)

format: [scrollbarStyle](../Formats.md#scrollbarStyle)

Controls the scrollbar style and position. The scrollbars can be overlaid or inset. When inset, they add to the padding of the view. And the scrollbars can be drawn inside the padding area or on the edge of the view. For example, if a view has a background drawable and you want to draw the scrollbars inside the padding specified by the drawable, you can use insideOverlay or insideInset. If you want them to appear at the edge of the view, ignoring the padding, then you can use outsideOverlay or outsideInset.

#### <a name="android_scrollbarThumbHorizontal"></a>android:scrollbarThumbHorizontal

[back to attribute list](#api_1)

format: [reference](../Formats.md#reference)

Defines the horizontal scrollbar thumb drawable.

#### <a name="android_scrollbarThumbVertical"></a>android:scrollbarThumbVertical

[back to attribute list](#api_1)

format: [reference](../Formats.md#reference)

Defines the vertical scrollbar thumb drawable.

#### <a name="android_scrollbarTrackHorizontal"></a>android:scrollbarTrackHorizontal

[back to attribute list](#api_1)

format: [reference](../Formats.md#reference)

Defines the horizontal scrollbar track drawable.

#### <a name="android_scrollbarTrackVertical"></a>android:scrollbarTrackVertical

[back to attribute list](#api_1)

format: [reference](../Formats.md#reference)

Defines the vertical scrollbar track drawable.

#### <a name="android_scrollbars"></a>android:scrollbars

[back to attribute list](#api_1)

format: [scrollbars](../Formats.md#scrollbars)

Defines which scrollbars should be displayed on scrolling or not.

#### <a name="android_soundEffectsEnabled"></a>android:soundEffectsEnabled

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Boolean that controls whether a view should have sound effects enabled for events such as clicking and touching.

#### <a name="android_tag"></a>android:tag

[back to attribute list](#api_1)

format: [string](../Formats.md#string) | [reference](../Formats.md#reference)

Supply a tag for this view containing a String, to be retrieved later with **View.getTag()** or searched for with **View.findViewWithTag()**. It is generally preferable to use IDs (through the android:id attribute) instead of tags because they are faster and allow for compile-time type checking.

#### <a name="android_visibility"></a>android:visibility

[back to attribute list](#api_1)

format: [visibility](../Formats.md#visibility)

Controls the initial visibility of the view.

### <a name="api_3"></a>API 3

[back to API list](#api_list)

attributes:

* [android:hapticFeedbackEnabled](#android_hapticFeedbackEnabled)
* [android:isScrollContainer](#android_isScrollContainer)

#### <a name="android_hapticFeedbackEnabled"></a>android:hapticFeedbackEnabled

[back to attribute list](#api_3)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Boolean that controls whether a view should have haptic feedback enabled for events such as long presses.

#### <a name="android_isScrollContainer"></a>android:isScrollContainer

[back to attribute list](#api_3)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Set this if the view will serve as a scrolling container, meaing that it can be resized to shrink its overall window so that there will be space for an input method. If not set, the default value will be true if "scrollbars" has the vertical scrollbar set, else it will be false.

### <a name="api_4"></a>API 4

[back to API list](#api_list)

attributes:

* [android:contentDescription](#android_contentDescription)
* [android:onClick](#android_onClick)

#### <a name="android_contentDescription"></a>android:contentDescription

[back to attribute list](#api_4)

format: [string](../Formats.md#string) | [reference](../Formats.md#reference)

Defines text that briefly describes content of the view. This property is used primarily for accessibility. Since some views do not have textual representation this attribute can be used for providing such.

#### <a name="android_onClick"></a>android:onClick

[back to attribute list](#api_4)

format: [string](../Formats.md#string) | [reference](../Formats.md#reference)

Name of the method in this View's context to invoke when the view is clicked. This name must correspond to a public method that takes exactly one parameter of type View. For instance, if you specify **android:onClick="sayHello"**, you must declare a **public void sayHello(View v)** method of your context (typically, your Activity).

### <a name="api_5"></a>API 5

[back to API list](#api_list)

attributes:

* [android:fadeScrollbars](#android_fadeScrollbars)
* [android:scrollbarDefaultDelayBeforeFade](#android_scrollbarDefaultDelayBeforeFade)
* [android:scrollbarFadeDuration](#android_scrollbarFadeDuration)

#### <a name="android_fadeScrollbars"></a>android:fadeScrollbars

[back to attribute list](#api_5)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Defines whether to fade out scrollbars when they are not in use.

#### <a name="android_scrollbarDefaultDelayBeforeFade"></a>android:scrollbarDefaultDelayBeforeFade

[back to attribute list](#api_5)

format: [integer](../Formats.md#integer) | [reference](../Formats.md#reference)

Defines the delay in milliseconds that a scrollbar waits before fade out.

#### <a name="android_scrollbarFadeDuration"></a>android:scrollbarFadeDuration

[back to attribute list](#api_5)

format: [integer](../Formats.md#integer) | [reference](../Formats.md#reference)

Defines the delay in milliseconds that a scrollbar takes to fade out.

### <a name="api_9"></a>API 9

[back to API list](#api_list)

attributes:

* [android:filterTouchesWhenObscured](#android_filterTouchesWhenObscured)

#### <a name="android_filterTouchesWhenObscured"></a>android:filterTouchesWhenObscured

[back to attribute list](#api_9)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Specifies whether to filter touches when the view's window is obscured by another visible window. When set to true, the view will not receive touches whenever a toast, dialog or other window appears above the view's window. Refer to the **View** security documentation for more details.

### <a name="api_11"></a>API 11

[back to API list](#api_list)

attributes:

* [android:alpha](#android_alpha)
* [android:layerType](#android_layerType)
* [android:nextFocusForward](#android_nextFocusForward)
* [android:rotation](#android_rotation)
* [android:rotationX](#android_rotationX)
* [android:rotationY](#android_rotationY)
* [android:scaleX](#android_scaleX)
* [android:scaleY](#android_scaleY)
* [android:transformPivotX](#android_transformPivotX)
* [android:transformPivotY](#android_transformPivotY)
* [android:translationX](#android_translationX)
* [android:translationY](#android_translationY)

#### <a name="android_alpha"></a>android:alpha

[back to attribute list](#api_11)

format: [float](../Formats.md#float) | [reference](../Formats.md#reference)

alpha property of the view, as a value between 0 (completely transparent) and 1 (completely opaque).

#### <a name="android_layerType"></a>android:layerType

[back to attribute list](#api_11)

format: [layerType](../Formats.md#layerType)

Specifies the type of layer backing this view. The default value is none. Refer to setLayerType(int, android.graphics.Paint) for more information.

#### <a name="android_nextFocusForward"></a>android:nextFocusForward

[back to attribute list](#api_11)

format: [reference](../Formats.md#reference)

Defines the next view to give focus to when the next focus is **FOCUS_FORWARD** If the reference refers to a view that does not exist or is part of a hierarchy that is invisible, a **RuntimeException** will result when the reference is accessed.

#### <a name="android_rotation"></a>android:rotation

[back to attribute list](#api_11)

format: [float](../Formats.md#float) | [reference](../Formats.md#reference)

rotation of the view, in degrees.

#### <a name="android_rotationX"></a>android:rotationX

[back to attribute list](#api_11)

format: [float](../Formats.md#float) | [reference](../Formats.md#reference)

rotation of the view around the x axis, in degrees.

#### <a name="android_rotationY"></a>android:rotationY

[back to attribute list](#api_11)

format: [float](../Formats.md#float) | [reference](../Formats.md#reference)

rotation of the view around the y axis, in degrees.

#### <a name="android_scaleX"></a>android:scaleX

[back to attribute list](#api_11)

format: [float](../Formats.md#float) | [reference](../Formats.md#reference)

scale of the view in the x direction.

#### <a name="android_scaleY"></a>android:scaleY

[back to attribute list](#api_11)

format: [float](../Formats.md#float) | [reference](../Formats.md#reference)

scale of the view in the y direction.

#### <a name="android_transformPivotX"></a>android:transformPivotX

[back to attribute list](#api_11)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

x location of the pivot point around which the view will rotate and scale. This xml attribute sets the pivotX property of the View.

#### <a name="android_transformPivotY"></a>android:transformPivotY

[back to attribute list](#api_11)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

y location of the pivot point around which the view will rotate and scale. This xml attribute sets the pivotY property of the View.

#### <a name="android_translationX"></a>android:translationX

[back to attribute list](#api_11)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

translation in x of the view. This value is added post-layout to the left property of the view, which is set by its layout.

#### <a name="android_translationY"></a>android:translationY

[back to attribute list](#api_11)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

translation in y of the view. This value is added post-layout to the top property of the view, which is set by its layout.

### <a name="api_14"></a>API 14

[back to API list](#api_list)

attributes:

* [android:requiresFadingEdge](#android_requiresFadingEdge)

#### <a name="android_requiresFadingEdge"></a>android:requiresFadingEdge

[back to attribute list](#api_14)

format: [fadingEdges](../Formats.md#fadingEdges)

Defines which edges should be faded on scrolling.

### <a name="api_16"></a>API 16

[back to API list](#api_list)

attributes:

* [android:importantForAccessibility](#android_importantForAccessibility)

#### <a name="android_importantForAccessibility"></a>android:importantForAccessibility

[back to attribute list](#api_16)

format: [accessImportance](../Formats.md#accessImportance) | [integer](../Formats.md#integer) | [reference](../Formats.md#reference)

Controls how this View is important for accessibility which is if it fires accessibility events and if it is reported to accessibility services that query the screen. Note: While not recommended, an accessibility service may decide to ignore this attribute and operate on all views in the view tree.

### <a name="api_17"></a>API 17

[back to API list](#api_list)

attributes:

* [android:layoutDirection](#android_layoutDirection)
* [android:paddingEnd](#android_paddingEnd)
* [android:paddingStart](#android_paddingStart)
* [android:textAlignment](#android_textAlignment)
* [android:textDirection](#android_textDirection)

#### <a name="android_layoutDirection"></a>android:layoutDirection

[back to attribute list](#api_17)

format: [layoutDirection](../Formats.md#layoutDirection)

Defines the direction of layout drawing. This typically is associated with writing direction of the language script used. The possible values are "ltr" for Left-to-Right, "rtl" for Right-to-Left, "locale" and "inherit" from parent view. If there is nothing to inherit, "locale" is used. "locale" falls back to "en-US". "ltr" is the direction used in "en-US". The default for this attribute is "inherit".

#### <a name="android_paddingEnd"></a>android:paddingEnd

[back to attribute list](#api_17)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

Sets the padding, in pixels, of the end edge; see [padding](#android_padding).

#### <a name="android_paddingStart"></a>android:paddingStart

[back to attribute list](#api_17)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

Sets the padding, in pixels, of the start edge; see [padding](#android_padding).

#### <a name="android_textAlignment"></a>android:textAlignment

[back to attribute list](#api_17)

format: [textAlignment](../Formats.md#textAlignment) | [integer](../Formats.md#integer) | [reference](../Formats.md#reference)

Defines the alignment of the text. A heuristic is used to determine the resolved text alignment.

#### <a name="android_textDirection"></a>android:textDirection

[back to attribute list](#api_17)

format: [textDirection](../Formats.md#textDirection) | [integer](../Formats.md#integer) | [reference](../Formats.md#reference)

Defines the direction of the text. A heuristic is used to determine the resolved text direction of paragraphs.

### <a name="api_19"></a>API 19

[back to API list](#api_list)

attributes:

* [android:accessibilityLiveRegion](#android_accessibilityLiveRegion)

#### <a name="android_accessibilityLiveRegion"></a>android:accessibilityLiveRegion

[back to attribute list](#api_19)

format: [accessLive](../Formats.md#accessLive) | [integer](../Formats.md#integer) | [reference](../Formats.md#reference)

Indicates to accessibility services whether the user should be notified when this view changes.

### <a name="api_21"></a>API 21

[back to API list](#api_list)

attributes:

* [android:backgroundTint](#android_backgroundTint)
* [android:backgroundTintMode](#android_backgroundTintMode)
* [android:elevation](#android_elevation)
* [android:stateListAnimator](#android_stateListAnimator)
* [android:transitionName](#android_transitionName)
* [android:translationZ](#android_translationZ)

#### <a name="android_backgroundTint"></a>android:backgroundTint

[back to attribute list](#api_21)

format: [color](../Formats.md#color) | [reference](../Formats.md#reference)

Tint to apply to the background.

#### <a name="android_backgroundTintMode"></a>android:backgroundTintMode

[back to attribute list](#api_21)

format: [tintMode](../Formats.md#tintMode)

Blending mode used to apply the background tint.

#### <a name="android_elevation"></a>android:elevation

[back to attribute list](#api_21)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

base z depth of the view

#### <a name="android_stateListAnimator"></a>android:stateListAnimator

[back to attribute list](#api_21)

format: [reference](../Formats.md#reference)

Sets the state-based animator for the View.

#### <a name="android_transitionName"></a>android:transitionName

[back to attribute list](#api_21)

format: [string](../Formats.md#string) | [reference](../Formats.md#reference)

Names a View such that it can be identified for Transitions. Names should be unique in the View hierarchy.

#### <a name="android_translationZ"></a>android:translationZ

[back to attribute list](#api_21)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

translation in z of the view. This value is added to its elevation.