# ProgressBar

[back to view list](View_list.md#ProgressBar)

class: `android.widget.ProgressBar`

API level: `API 1`

parent: [View](View.md)

direct childs:

**API 1**

* [AbsSeekBar](AbsSeekBar.md)

**API support_v4**

* [ContentLoadingProgressBar](ContentLoadingProgressBar.md)

## Attributes

API list:

* [API_1](#api_1)
* [API_11](#api_11)
* [API_18](#api_18)
* [API_21](#api_21)

### <a name="api_1"></a>API 1

[back to API list](#api_list)

attributes:

* [android:indeterminate](#android_indeterminate)
* [android:indeterminateBehavior](#android_indeterminateBehavior)
* [android:indeterminateDrawable](#android_indeterminateDrawable)
* [android:indeterminateDuration](#android_indeterminateDuration)
* [android:indeterminateOnly](#android_indeterminateOnly)
* [android:interpolator](#android_interpolator)
* [android:max](#android_max)
* [android:maxHeight](#android_maxHeight)
* [android:maxWidth](#android_maxWidth)
* [android:minHeight](#android_minHeight)
* [android:minWidth](#android_minWidth)
* [android:progress](#android_progress)
* [android:progressDrawable](#android_progressDrawable)
* [android:secondaryProgress](#android_secondaryProgress)

#### <a name="android_indeterminate"></a>android:indeterminate

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Allows to enable the indeterminate mode. In this mode the progress bar plays an infinite looping animation.

#### <a name="android_indeterminateBehavior"></a>android:indeterminateBehavior

[back to attribute list](#api_1)

format: [indeterminateBehavior](../Formats.md#indeterminateBehavior)

Defines how the indeterminate mode should behave when the progress reaches max.

#### <a name="android_indeterminateDrawable"></a>android:indeterminateDrawable

[back to attribute list](#api_1)

format: [reference](../Formats.md#reference)

Drawable used for the indeterminate mode.

#### <a name="android_indeterminateDuration"></a>android:indeterminateDuration

[back to attribute list](#api_1)

format: [integer](../Formats.md#integer) | [reference](../Formats.md#reference)

Duration of the indeterminate animation.

#### <a name="android_indeterminateOnly"></a>android:indeterminateOnly

[back to attribute list](#api_1)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Restricts to ONLY indeterminate mode (state-keeping progress mode will not work).

#### <a name="android_interpolator"></a>android:interpolator

[back to attribute list](#api_1)

format: 

#### <a name="android_max"></a>android:max

[back to attribute list](#api_1)

format: [integer](../Formats.md#integer) | [reference](../Formats.md#reference)

Defines the maximum value the progress can take.

#### <a name="android_maxHeight"></a>android:maxHeight

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

An optional argument to supply a maximum height for this view. See {see android.widget.ImageView#setMaxHeight} for details.

#### <a name="android_maxWidth"></a>android:maxWidth

[back to attribute list](#api_1)

format: [dimemsion](../Formats.md#dimemsion) | [reference](../Formats.md#reference)

An optional argument to supply a maximum width for this view. See {see android.widget.ImageView#setMaxWidth} for details.

#### <a name="android_minHeight"></a>android:minHeight

[back to attribute list](#api_1)

format: 

#### <a name="android_minWidth"></a>android:minWidth

[back to attribute list](#api_1)

format: 

#### <a name="android_progress"></a>android:progress

[back to attribute list](#api_1)

format: [integer](../Formats.md#integer) | [reference](../Formats.md#reference)

Defines the default progress value, between 0 and max.

#### <a name="android_progressDrawable"></a>android:progressDrawable

[back to attribute list](#api_1)

format: [reference](../Formats.md#reference)

Drawable used for the progress mode.

#### <a name="android_secondaryProgress"></a>android:secondaryProgress

[back to attribute list](#api_1)

format: [integer](../Formats.md#integer) | [reference](../Formats.md#reference)

Defines the secondary progress value, between 0 and max. This progress is drawn between the primary progress and the background. It can be ideal for media scenarios such as showing the buffering progress while the default progress shows the play progress.

### <a name="api_11"></a>API 11

[back to API list](#api_list)

attributes:

* [android:animationResolution](#android_animationResolution)

#### <a name="android_animationResolution"></a>android:animationResolution

[back to attribute list](#api_11)

format: [integer](../Formats.md#integer) | [reference](../Formats.md#reference)

Timeout between frames of animation in milliseconds

### <a name="api_18"></a>API 18

[back to API list](#api_list)

attributes:

* [android:mirrorForRtl](#android_mirrorForRtl)

#### <a name="android_mirrorForRtl"></a>android:mirrorForRtl

[back to attribute list](#api_18)

format: [boolean](../Formats.md#boolean) | [reference](../Formats.md#reference)

Defines if the associated drawables need to be mirrored when in RTL mode. Default is false

### <a name="api_21"></a>API 21

[back to API list](#api_list)

attributes:

* [android:indeterminateTint](#android_indeterminateTint)
* [android:indeterminateTintMode](#android_indeterminateTintMode)
* [android:progressBackgroundTint](#android_progressBackgroundTint)
* [android:progressBackgroundTintMode](#android_progressBackgroundTintMode)
* [android:progressTint](#android_progressTint)
* [android:progressTintMode](#android_progressTintMode)
* [android:secondaryProgressTint](#android_secondaryProgressTint)
* [android:secondaryProgressTintMode](#android_secondaryProgressTintMode)

#### <a name="android_indeterminateTint"></a>android:indeterminateTint

[back to attribute list](#api_21)

format: [color](../Formats.md#color) | [reference](../Formats.md#reference)

Tint to apply to the indeterminate progress indicator.

#### <a name="android_indeterminateTintMode"></a>android:indeterminateTintMode

[back to attribute list](#api_21)

format: [tintMode](../Formats.md#tintMode)

Blending mode used to apply the indeterminate progress indicator tint.

#### <a name="android_progressBackgroundTint"></a>android:progressBackgroundTint

[back to attribute list](#api_21)

format: [color](../Formats.md#color) | [reference](../Formats.md#reference)

Tint to apply to the progress indicator background.

#### <a name="android_progressBackgroundTintMode"></a>android:progressBackgroundTintMode

[back to attribute list](#api_21)

format: [tintMode](../Formats.md#tintMode)

Blending mode used to apply the progress indicator background tint.

#### <a name="android_progressTint"></a>android:progressTint

[back to attribute list](#api_21)

format: [color](../Formats.md#color) | [reference](../Formats.md#reference)

Tint to apply to the progress indicator.

#### <a name="android_progressTintMode"></a>android:progressTintMode

[back to attribute list](#api_21)

format: [tintMode](../Formats.md#tintMode)

Blending mode used to apply the progress indicator tint.

#### <a name="android_secondaryProgressTint"></a>android:secondaryProgressTint

[back to attribute list](#api_21)

format: [color](../Formats.md#color) | [reference](../Formats.md#reference)

Tint to apply to the secondary progress indicator.

#### <a name="android_secondaryProgressTintMode"></a>android:secondaryProgressTintMode

[back to attribute list](#api_21)

format: [tintMode](../Formats.md#tintMode)

Blending mode used to apply the secondary progress indicator tint.