# <a name="View"></a>View

class: `android.view.View`

direct childs: [AnalogClock](#AnalogClock), [ViewStub](#ViewStub), [ImageView](#ImageView), [ProgressBar](#ProgressBar), [SurfaceView](#SurfaceView), [TextView](#TextView), [ViewGroup](#ViewGroup), [TextureView](#TextureView)

--

**API 1**

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

**API 3**

* [android:hapticFeedbackEnabled](#android_hapticFeedbackEnabled)
* [android:isScrollContainer](#android_isScrollContainer)

**API 4**

* [android:contentDescription](#android_contentDescription)
* [android:onClick](#android_onClick)

**API 5**

* [android:fadeScrollbars](#android_fadeScrollbars)
* [android:scrollbarDefaultDelayBeforeFade](#android_scrollbarDefaultDelayBeforeFade)
* [android:scrollbarFadeDuration](#android_scrollbarFadeDuration)

**API 9**

* [android:filterTouchesWhenObscured](#android_filterTouchesWhenObscured)

**API 11**

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

**API 14**

* [android:requiresFadingEdge](#android_requiresFadingEdge)

**API 16**

* [android:importantForAccessibility](#android_importantForAccessibility)

**API 17**

* [android:layoutDirection](#android_layoutDirection)
* [android:paddingEnd](#android_paddingEnd)
* [android:paddingStart](#android_paddingStart)
* [android:textAlignment](#android_textAlignment)
* [android:textDirection](#android_textDirection)

**API 19**

* [android:accessibilityLiveRegion](#android_accessibilityLiveRegion)

**API 21**

* [android:backgroundTint](#android_backgroundTint)
* [android:backgroundTintMode](#android_backgroundTintMode)
* [android:elevation](#android_elevation)
* [android:stateListAnimator](#android_stateListAnimator)
* [android:translationZ](#android_translationZ)
* [android:transitionName](#android_transitionName)

## <a name="AnalogClock"></a>AnalogClock

class: `android.widget.AnalogClock`

parent: [View](#View)

--

**API 1**

* [android:dial](#android_dial)
* [android:hand_hour](#android_hand_hour)
* [android:hand_minute](#android_hand_minute)

## <a name="ViewStub"></a>ViewStub

class: `android.view.ViewStub`

parent: [View](#View)

--

**API 1**

* [android:inflatedId](#android_inflatedId)
* [android:layout](#android_layout)

## <a name="ImageView"></a>ImageView

class: `android.widget.ImageView`

parent: [View](#View)

direct childs: [ImageButton](#ImageButton), [QuickContactBadge](#QuickContactBadge)

--

**API 1**

* [android:adjustViewBounds](#android_adjustViewBounds)
* [android:baselineAlignBottom](#android_baselineAlignBottom)
* [android:cropToPadding](#android_cropToPadding)
* [android:maxHeight](#android_maxHeight)
* [android:maxWidth](#android_maxWidth)
* [android:scaleType](#android_scaleType)
* [android:src](#android_src)
* [android:tint](#android_tint)

**API 11**

* [android:baseline](#android_baseline)

**API 21**

* [android:tintMode](#android_tintMode)

### <a name="ImageButton"></a>ImageButton

class: `android.widget.ImageButton`

parent: [ImageView](#ImageView)

direct childs: [ZoomButton](#ZoomButton)

--

#### <a name="ZoomButton"></a>ZoomButton

class: `android.widget.ZoomButton`

parent: [ImageButton](#ImageButton)

--

### <a name="QuickContactBadge"></a>QuickContactBadge

class: `android.widget.QuickContactBadge`

parent: [ImageView](#ImageView)

--

## <a name="ProgressBar"></a>ProgressBar

class: `android.widget.ProgressBar`

parent: [View](#View)

direct childs: [AbsSeekBar](#AbsSeekBar)

--

**API 1**

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

**API 11**

* [android:animationResolution](#android_animationResolution)

**API 18**

* [android:mirrorForRtl](#android_mirrorForRtl)

**API 21**

* [android:indeterminateTint](#android_indeterminateTint)
* [android:indeterminateTintMode](#android_indeterminateTintMode)
* [android:progressBackgroundTint](#android_progressBackgroundTint)
* [android:progressBackgroundTintMode](#android_progressBackgroundTintMode)
* [android:progressTint](#android_progressTint)
* [android:progressTintMode](#android_progressTintMode)
* [android:secondaryProgressTint](#android_secondaryProgressTint)
* [android:secondaryProgressTintMode](#android_secondaryProgressTintMode)

### <a name="AbsSeekBar"></a>AbsSeekBar

class: `android.widget.AbsSeekBar`

parent: [ProgressBar](#ProgressBar)

direct childs: [RatingBar](#RatingBar), [SeekBar](#SeekBar)

--

#### <a name="RatingBar"></a>RatingBar

class: `android.widget.RatingBar`

parent: [AbsSeekBar](#AbsSeekBar)

--

**API 1**

* [android:isIndicator](#android_isIndicator)
* [android:numStars](#android_numStars)
* [android:rating](#android_rating)
* [android:stepSize](#android_stepSize)

#### <a name="SeekBar"></a>SeekBar

class: `android.widget.SeekBar`

parent: [AbsSeekBar](#AbsSeekBar)

--

**API 1**

* [android:thumb](#android_thumb)

## <a name="SurfaceView"></a>SurfaceView

class: `android.view.SurfaceView`

parent: [View](#View)

direct childs: [VideoView](#VideoView), [GLSurfaceView](#GLSurfaceView)

--

### <a name="VideoView"></a>VideoView

class: `android.widget.VideoView`

parent: [SurfaceView](#SurfaceView)

--

### <a name="GLSurfaceView"></a>GLSurfaceView

class: `android.opengl.GLSurfaceView`

parent: [SurfaceView](#SurfaceView)

--

## <a name="TextView"></a>TextView

class: `android.widget.TextView`

parent: [View](#View)

direct childs: [CheckedTextView](#CheckedTextView), [Chronometer](#Chronometer), [Button](#Button), [EditText](#EditText)

--

**API 1**

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

**API 2**

* [android:marqueeRepeatLimit](#android_marqueeRepeatLimit)

**API 3**

* [android:editorExtras](#android_editorExtras)
* [android:imeActionId](#android_imeActionId)
* [android:imeActionLabel](#android_imeActionLabel)
* [android:imeOptions](#android_imeOptions)
* [android:inputType](#android_inputType)
* [android:privateImeOptions](#android_privateImeOptions)

**API 11**

* [android:textIsSelectable](#android_textIsSelectable)

**API 14**

* [android:drawableEnd](#android_drawableEnd)
* [android:drawableStart](#android_drawableStart)
* [android:textAllCaps](#android_textAllCaps)

**API 16**

* [android:fontFamily](#android_fontFamily)

**API 21**

* [android:fontFeatureSettings](#android_fontFeatureSettings)
* [android:letterSpacing](#android_letterSpacing)
* [android:elegantTextHeight](#android_elegantTextHeight)

### <a name="CheckedTextView"></a>CheckedTextView

class: `android.widget.CheckedTextView`

parent: [TextView](#TextView)

--

**API 1**

* [android:checkMark](#android_checkMark)
* [android:checked](#android_checked)

**API 21**

* [android:checkMarkTint](#android_checkMarkTint)
* [android:checkMarkTintMode](#android_checkMarkTintMode)

### <a name="Chronometer"></a>Chronometer

class: `android.widget.Chronometer`

parent: [TextView](#TextView)

--

**API 1**

* [android:format](#android_format)

### <a name="Button"></a>Button

class: `android.widget.Button`

parent: [TextView](#TextView)

direct childs: [CompoundButton](#CompoundButton)

--

#### <a name="CompoundButton"></a>CompoundButton

class: `android.widget.CompoundButton`

parent: [Button](#Button)

direct childs: [CheckBox](#CheckBox), [RadioButton](#RadioButton), [ToggleButton](#ToggleButton), [Switch](#Switch)

--

**API 21**

* [android:buttonTint](#android_buttonTint)
* [android:buttonTintMode](#android_buttonTintMode)

##### <a name="CheckBox"></a>CheckBox

class: `android.widget.CheckBox`

parent: [CompoundButton](#CompoundButton)

--

##### <a name="RadioButton"></a>RadioButton

class: `android.widget.RadioButton`

parent: [CompoundButton](#CompoundButton)

--

##### <a name="ToggleButton"></a>ToggleButton

class: `android.widget.ToggleButton`

parent: [CompoundButton](#CompoundButton)

--

**API 1**

* [android:disabledAlpha](#android_disabledAlpha)
* [android:textOff](#android_textOff)
* [android:textOn](#android_textOn)

##### <a name="Switch"></a>Switch

class: `android.widget.Switch`

parent: [CompoundButton](#CompoundButton)

--

**API 1**

* [android:textOff](#android_textOff)
* [android:textOn](#android_textOn)
* [android:textStyle](#android_textStyle)
* [android:thumb](#android_thumb)
* [android:typeface](#android_typeface)

**API 14**

* [android:switchMinWidth](#android_switchMinWidth)
* [android:switchPadding](#android_switchPadding)
* [android:switchTextAppearance](#android_switchTextAppearance)
* [android:thumbTextPadding](#android_thumbTextPadding)
* [android:track](#android_track)

**API 21**

* [android:showText](#android_showText)
* [android:splitTrack](#android_splitTrack)

### <a name="EditText"></a>EditText

class: `android.widget.EditText`

parent: [TextView](#TextView)

direct childs: [AutoCompleteTextView](#AutoCompleteTextView), [ExtractEditText](#ExtractEditText)

--

#### <a name="AutoCompleteTextView"></a>AutoCompleteTextView

class: `android.widget.AutoCompleteTextView`

parent: [EditText](#EditText)

direct childs: [MultiAutoCompleteTextView](#MultiAutoCompleteTextView)

--

**API 1**

* [android:completionHint](#android_completionHint)
* [android:completionHintView](#android_completionHintView)
* [android:completionThreshold](#android_completionThreshold)
* [android:dropDownSelector](#android_dropDownSelector)
* [android:popupBackground](#android_popupBackground)

**API 3**

* [android:dropDownAnchor](#android_dropDownAnchor)
* [android:dropDownWidth](#android_dropDownWidth)

**API 4**

* [android:dropDownHeight](#android_dropDownHeight)

**API 5**

* [android:dropDownHorizontalOffset](#android_dropDownHorizontalOffset)
* [android:dropDownVerticalOffset](#android_dropDownVerticalOffset)

##### <a name="MultiAutoCompleteTextView"></a>MultiAutoCompleteTextView

class: `android.widget.MultiAutoCompleteTextView`

parent: [AutoCompleteTextView](#AutoCompleteTextView)

--

#### <a name="ExtractEditText"></a>ExtractEditText

class: `android.inputmethodservice.ExtractEditText`

parent: [EditText](#EditText)

--

## <a name="ViewGroup"></a>ViewGroup

class: `android.view.ViewGroup`

parent: [View](#View)

direct childs: [AdapterView](#AdapterView), [FrameLayout](#FrameLayout), [LinearLayout](#LinearLayout), [RelativeLayout](#RelativeLayout)

--

**API 1**

* [android:addStatesFromChildren](#android_addStatesFromChildren)
* [android:alwaysDrawnWithCache](#android_alwaysDrawnWithCache)
* [android:animationCache](#android_animationCache)
* [android:clipChildren](#android_clipChildren)
* [android:clipToPadding](#android_clipToPadding)
* [android:descendantFocusability](#android_descendantFocusability)
* [android:layoutAnimation](#android_layoutAnimation)
* [android:persistentDrawingCache](#android_persistentDrawingCache)

**API 11**

* [android:animateLayoutChanges](#android_animateLayoutChanges)
* [android:splitMotionEvents](#android_splitMotionEvents)

**API 18**

* [android:layoutMode](#android_layoutMode)

### <a name="AdapterView"></a>AdapterView

class: `android.widget.AdapterView`

parent: [ViewGroup](#ViewGroup)

direct childs: [AbsListView](#AbsListView), [AbsSpinner](#AbsSpinner), [AdapterViewAnimator](#AdapterViewAnimator)

--

#### <a name="AbsListView"></a>AbsListView

class: `android.widget.AbsListView`

parent: [AdapterView](#AdapterView)

direct childs: [GridView](#GridView), [ListView](#ListView)

--

**API 1**

* [android:cacheColorHint](#android_cacheColorHint)
* [android:choiceMode](#android_choiceMode)
* [android:drawSelectorOnTop](#android_drawSelectorOnTop)
* [android:listSelector](#android_listSelector)
* [android:scrollingCache](#android_scrollingCache)
* [android:stackFromBottom](#android_stackFromBottom)
* [android:textFilterEnabled](#android_textFilterEnabled)
* [android:transcriptMode](#android_transcriptMode)

**API 3**

* [android:fastScrollEnabled](#android_fastScrollEnabled)
* [android:smoothScrollbar](#android_smoothScrollbar)

##### <a name="GridView"></a>GridView

class: `android.widget.GridView`

parent: [AbsListView](#AbsListView)

--

**API 1**

* [android:columnWidth](#android_columnWidth)
* [android:gravity](#android_gravity)
* [android:horizontalSpacing](#android_horizontalSpacing)
* [android:numColumns](#android_numColumns)
* [android:stretchMode](#android_stretchMode)
* [android:verticalSpacing](#android_verticalSpacing)

##### <a name="ListView"></a>ListView

class: `android.widget.ListView`

parent: [AbsListView](#AbsListView)

direct childs: [ExpandableListView](#ExpandableListView)

--

**API 1**

* [android:divider](#android_divider)
* [android:dividerHeight](#android_dividerHeight)
* [android:entries](#android_entries)

**API 3**

* [android:footerDividersEnabled](#android_footerDividersEnabled)
* [android:headerDividersEnabled](#android_headerDividersEnabled)

###### <a name="ExpandableListView"></a>ExpandableListView

class: `android.widget.ExpandableListView`

parent: [ListView](#ListView)

--

**API 1**

* [android:childDivider](#android_childDivider)
* [android:childIndicator](#android_childIndicator)
* [android:childIndicatorLeft](#android_childIndicatorLeft)
* [android:childIndicatorRight](#android_childIndicatorRight)
* [android:groupIndicator](#android_groupIndicator)
* [android:indicatorLeft](#android_indicatorLeft)
* [android:indicatorRight](#android_indicatorRight)

**API 18**

* [android:childIndicatorEnd](#android_childIndicatorEnd)
* [android:childIndicatorStart](#android_childIndicatorStart)
* [android:indicatorEnd](#android_indicatorEnd)
* [android:indicatorStart](#android_indicatorStart)

#### <a name="AbsSpinner"></a>AbsSpinner

class: `android.widget.AbsSpinner`

parent: [AdapterView](#AdapterView)

direct childs: [Spinner](#Spinner)

--

**API 1**

* [android:entries](#android_entries)

##### <a name="Spinner"></a>Spinner

class: `android.widget.Spinner`

parent: [AbsSpinner](#AbsSpinner)

--

**API 1**

* [android:dropDownSelector](#android_dropDownSelector)
* [android:gravity](#android_gravity)
* [android:popupBackground](#android_popupBackground)
* [android:prompt](#android_prompt)

**API 11**

* [android:spinnerMode](#android_spinnerMode)

**API 3**

* [android:dropDownWidth](#android_dropDownWidth)

**API 5**

* [android:dropDownHorizontalOffset](#android_dropDownHorizontalOffset)
* [android:dropDownVerticalOffset](#android_dropDownVerticalOffset)

#### <a name="AdapterViewAnimator"></a>AdapterViewAnimator

class: `android.widget.AdapterViewAnimator`

parent: [AdapterView](#AdapterView)

direct childs: [AdapterViewFlipper](#AdapterViewFlipper), [StackView](#StackView)

--

**API 1**

* [android:inAnimation](#android_inAnimation)
* [android:outAnimation](#android_outAnimation)

**API 11**

* [android:animateFirstView](#android_animateFirstView)
* [android:loopViews](#android_loopViews)

##### <a name="AdapterViewFlipper"></a>AdapterViewFlipper

class: `android.widget.AdapterViewFlipper`

parent: [AdapterViewAnimator](#AdapterViewAnimator)

--

**API 1**

* [android:flipInterval](#android_flipInterval)

**API 7**

* [android:autoStart](#android_autoStart)

##### <a name="StackView"></a>StackView

class: `android.widget.StackView`

parent: [AdapterViewAnimator](#AdapterViewAnimator)

--

### <a name="FrameLayout"></a>FrameLayout

class: `android.widget.FrameLayout`

parent: [ViewGroup](#ViewGroup)

direct childs: [DatePicker](#DatePicker), [TimePicker](#TimePicker), [MediaController](#MediaController), [ScrollView](#ScrollView), [ViewAnimator](#ViewAnimator), [TabHost](#TabHost), [AppWidgetHostView](#AppWidgetHostView), [HorizontalScrollView](#HorizontalScrollView), [GestureOverlayView](#GestureOverlayView), [CalendarView](#CalendarView)

--

**API 1**

* [android:foreground](#android_foreground)
* [android:foregroundGravity](#android_foregroundGravity)
* [android:measureAllChildren](#android_measureAllChildren)

**API 21**

* [android:foregroundTint](#android_foregroundTint)
* [android:foregroundTintMode](#android_foregroundTintMode)

#### <a name="DatePicker"></a>DatePicker

class: `android.widget.DatePicker`

parent: [FrameLayout](#FrameLayout)

--

**API 1**

* [android:endYear](#android_endYear)
* [android:headerBackground](#android_headerBackground)
* [android:startYear](#android_startYear)

**API 11**

* [android:calendarViewShown](#android_calendarViewShown)
* [android:firstDayOfWeek](#android_firstDayOfWeek)
* [android:maxDate](#android_maxDate)
* [android:minDate](#android_minDate)
* [android:spinnersShown](#android_spinnersShown)

**API 21**

* [android:calendarTextColor](#android_calendarTextColor)
* [android:dayOfWeekBackground](#android_dayOfWeekBackground)
* [android:dayOfWeekTextAppearance](#android_dayOfWeekTextAppearance)
* [android:headerDayOfMonthTextAppearance](#android_headerDayOfMonthTextAppearance)
* [android:headerMonthTextAppearance](#android_headerMonthTextAppearance)
* [android:headerYearTextAppearance](#android_headerYearTextAppearance)
* [android:yearListItemTextAppearance](#android_yearListItemTextAppearance)
* [android:yearListSelectorColor](#android_yearListSelectorColor)

#### <a name="TimePicker"></a>TimePicker

class: `android.widget.TimePicker`

parent: [FrameLayout](#FrameLayout)

--

#### <a name="MediaController"></a>MediaController

class: `android.widget.MediaController`

parent: [FrameLayout](#FrameLayout)

--

#### <a name="ScrollView"></a>ScrollView

class: `android.widget.ScrollView`

parent: [FrameLayout](#FrameLayout)

--

**API 1**

* [android:fillViewport](#android_fillViewport)

#### <a name="ViewAnimator"></a>ViewAnimator

class: `android.widget.ViewAnimator`

parent: [FrameLayout](#FrameLayout)

direct childs: [ViewFlipper](#ViewFlipper), [ViewSwitcher](#ViewSwitcher)

--

**API 1**

* [android:inAnimation](#android_inAnimation)
* [android:outAnimation](#android_outAnimation)

**API 11**

* [android:animateFirstView](#android_animateFirstView)

##### <a name="ViewFlipper"></a>ViewFlipper

class: `android.widget.ViewFlipper`

parent: [ViewAnimator](#ViewAnimator)

--

**API 1**

* [android:flipInterval](#android_flipInterval)

**API 7**

* [android:autoStart](#android_autoStart)

##### <a name="ViewSwitcher"></a>ViewSwitcher

class: `android.widget.ViewSwitcher`

parent: [ViewAnimator](#ViewAnimator)

direct childs: [ImageSwitcher](#ImageSwitcher), [TextSwitcher](#TextSwitcher)

--

###### <a name="ImageSwitcher"></a>ImageSwitcher

class: `android.widget.ImageSwitcher`

parent: [ViewSwitcher](#ViewSwitcher)

--

###### <a name="TextSwitcher"></a>TextSwitcher

class: `android.widget.TextSwitcher`

parent: [ViewSwitcher](#ViewSwitcher)

--

#### <a name="TabHost"></a>TabHost

class: `android.widget.TabHost`

parent: [FrameLayout](#FrameLayout)

--

#### <a name="AppWidgetHostView"></a>AppWidgetHostView

class: `android.appwidget.AppWidgetHostView`

parent: [FrameLayout](#FrameLayout)

--

#### <a name="HorizontalScrollView"></a>HorizontalScrollView

class: `android.widget.HorizontalScrollView`

parent: [FrameLayout](#FrameLayout)

--

**API 1**

* [android:fillViewport](#android_fillViewport)

#### <a name="GestureOverlayView"></a>GestureOverlayView

class: `android.gesture.GestureOverlayView`

parent: [FrameLayout](#FrameLayout)

--

**API 1**

* [android:orientation](#android_orientation)

**API 4**

* [android:eventsInterceptionEnabled](#android_eventsInterceptionEnabled)
* [android:fadeDuration](#android_fadeDuration)
* [android:fadeEnabled](#android_fadeEnabled)
* [android:fadeOffset](#android_fadeOffset)
* [android:gestureColor](#android_gestureColor)
* [android:gestureStrokeAngleThreshold](#android_gestureStrokeAngleThreshold)
* [android:gestureStrokeLengthThreshold](#android_gestureStrokeLengthThreshold)
* [android:gestureStrokeSquarenessThreshold](#android_gestureStrokeSquarenessThreshold)
* [android:gestureStrokeType](#android_gestureStrokeType)
* [android:gestureStrokeWidth](#android_gestureStrokeWidth)
* [android:uncertainGestureColor](#android_uncertainGestureColor)

#### <a name="CalendarView"></a>CalendarView

class: `android.widget.CalendarView`

parent: [FrameLayout](#FrameLayout)

--

**API 11**

* [android:dateTextAppearance](#android_dateTextAppearance)
* [android:firstDayOfWeek](#android_firstDayOfWeek)
* [android:focusedMonthDateColor](#android_focusedMonthDateColor)
* [android:maxDate](#android_maxDate)
* [android:minDate](#android_minDate)
* [android:selectedDateVerticalBar](#android_selectedDateVerticalBar)
* [android:selectedWeekBackgroundColor](#android_selectedWeekBackgroundColor)
* [android:showWeekNumber](#android_showWeekNumber)
* [android:shownWeekCount](#android_shownWeekCount)
* [android:unfocusedMonthDateColor](#android_unfocusedMonthDateColor)
* [android:weekDayTextAppearance](#android_weekDayTextAppearance)
* [android:weekNumberColor](#android_weekNumberColor)
* [android:weekSeparatorLineColor](#android_weekSeparatorLineColor)

### <a name="LinearLayout"></a>LinearLayout

class: `android.widget.LinearLayout`

parent: [ViewGroup](#ViewGroup)

direct childs: [RadioGroup](#RadioGroup), [TabWidget](#TabWidget), [TableLayout](#TableLayout), [TableRow](#TableRow), [ZoomControls](#ZoomControls), [NumberPicker](#NumberPicker), [SearchView](#SearchView), [ActionMenuView](#ActionMenuView)

--

**API 1**

* [android:baselineAligned](#android_baselineAligned)
* [android:baselineAlignedChildIndex](#android_baselineAlignedChildIndex)
* [android:divider](#android_divider)
* [android:gravity](#android_gravity)
* [android:orientation](#android_orientation)
* [android:weightSum](#android_weightSum)

**API 11**

* [android:measureWithLargestChild](#android_measureWithLargestChild)

#### <a name="RadioGroup"></a>RadioGroup

class: `android.widget.RadioGroup`

parent: [LinearLayout](#LinearLayout)

--

**API 1**

* [android:checkedButton](#android_checkedButton)

#### <a name="TabWidget"></a>TabWidget

class: `android.widget.TabWidget`

parent: [LinearLayout](#LinearLayout)

--

**API 1**

* [android:divider](#android_divider)
* [android:tabStripEnabled](#android_tabStripEnabled)
* [android:tabStripLeft](#android_tabStripLeft)
* [android:tabStripRight](#android_tabStripRight)

#### <a name="TableLayout"></a>TableLayout

class: `android.widget.TableLayout`

parent: [LinearLayout](#LinearLayout)

--

**API 1**

* [android:collapseColumns](#android_collapseColumns)
* [android:shrinkColumns](#android_shrinkColumns)
* [android:stretchColumns](#android_stretchColumns)

#### <a name="TableRow"></a>TableRow

class: `android.widget.TableRow`

parent: [LinearLayout](#LinearLayout)

--

#### <a name="ZoomControls"></a>ZoomControls

class: `android.widget.ZoomControls`

parent: [LinearLayout](#LinearLayout)

--

#### <a name="NumberPicker"></a>NumberPicker

class: `android.widget.NumberPicker`

parent: [LinearLayout](#LinearLayout)

--

#### <a name="SearchView"></a>SearchView

class: `android.widget.SearchView`

parent: [LinearLayout](#LinearLayout)

--

**API 1**

* [android:imeOptions](#android_imeOptions)
* [android:inputType](#android_inputType)
* [android:maxWidth](#android_maxWidth)

**API 11**

* [android:iconifiedByDefault](#android_iconifiedByDefault)
* [android:queryHint](#android_queryHint)

#### <a name="ActionMenuView"></a>ActionMenuView

class: `android.widget.ActionMenuView`

parent: [LinearLayout](#LinearLayout)

--

### <a name="RelativeLayout"></a>RelativeLayout

class: `android.widget.RelativeLayout`

parent: [ViewGroup](#ViewGroup)

direct childs: [DialerFilter](#DialerFilter)

--

**API 1**

* [android:gravity](#android_gravity)
* [android:ignoreGravity](#android_ignoreGravity)

#### <a name="DialerFilter"></a>DialerFilter

class: `android.widget.DialerFilter`

parent: [RelativeLayout](#RelativeLayout)

--

**API 3**

* [android:keyBackground](#android_keyBackground)
* [android:keyPreviewLayout](#android_keyPreviewLayout)
* [android:keyPreviewOffset](#android_keyPreviewOffset)
* [android:keyTextColor](#android_keyTextColor)
* [android:keyTextSize](#android_keyTextSize)
* [android:labelTextSize](#android_labelTextSize)
* [android:popupLayout](#android_popupLayout)
* [android:verticalCorrection](#android_verticalCorrection)

## <a name="TextureView"></a>TextureView

class: `android.view.TextureView`

parent: [View](#View)

--

# Attributes

## API list

* [API 1](#api_1)
* [API 2](#api_2)
* [API 3](#api_3)
* [API 4](#api_4)
* [API 5](#api_5)
* [API 7](#api_7)
* [API 9](#api_9)
* [API 11](#api_11)
* [API 14](#api_14)
* [API 16](#api_16)
* [API 17](#api_17)
* [API 18](#api_18)
* [API 19](#api_19)
* [API 21](#api_21)

## <a name="api_1"></a>API 1

### Attribute list

* [android:addStatesFromChildren](#android_addStatesFromChildren)
* [android:adjustViewBounds](#android_adjustViewBounds)
* [android:alwaysDrawnWithCache](#android_alwaysDrawnWithCache)
* [android:animationCache](#android_animationCache)
* [android:autoLink](#android_autoLink)
* [android:autoText](#android_autoText)
* [android:background](#android_background)
* [android:baselineAlignBottom](#android_baselineAlignBottom)
* [android:baselineAligned](#android_baselineAligned)
* [android:baselineAlignedChildIndex](#android_baselineAlignedChildIndex)
* [android:bufferType](#android_bufferType)
* [android:cacheColorHint](#android_cacheColorHint)
* [android:capitalize](#android_capitalize)
* [android:checkMark](#android_checkMark)
* [android:checked](#android_checked)
* [android:checkedButton](#android_checkedButton)
* [android:childDivider](#android_childDivider)
* [android:childIndicator](#android_childIndicator)
* [android:childIndicatorLeft](#android_childIndicatorLeft)
* [android:childIndicatorRight](#android_childIndicatorRight)
* [android:choiceMode](#android_choiceMode)
* [android:clickable](#android_clickable)
* [android:clipChildren](#android_clipChildren)
* [android:clipToPadding](#android_clipToPadding)
* [android:collapseColumns](#android_collapseColumns)
* [android:columnWidth](#android_columnWidth)
* [android:completionHint](#android_completionHint)
* [android:completionHintView](#android_completionHintView)
* [android:completionThreshold](#android_completionThreshold)
* [android:cropToPadding](#android_cropToPadding)
* [android:cursorVisible](#android_cursorVisible)
* [android:descendantFocusability](#android_descendantFocusability)
* [android:dial](#android_dial)
* [android:digits](#android_digits)
* [android:disabledAlpha](#android_disabledAlpha)
* [android:divider](#android_divider)
* [android:dividerHeight](#android_dividerHeight)
* [android:drawSelectorOnTop](#android_drawSelectorOnTop)
* [android:drawableBottom](#android_drawableBottom)
* [android:drawableLeft](#android_drawableLeft)
* [android:drawablePadding](#android_drawablePadding)
* [android:drawableRight](#android_drawableRight)
* [android:drawableTop](#android_drawableTop)
* [android:drawingCacheQuality](#android_drawingCacheQuality)
* [android:dropDownSelector](#android_dropDownSelector)
* [android:duplicateParentState](#android_duplicateParentState)
* [android:editable](#android_editable)
* [android:ellipsize](#android_ellipsize)
* [android:ems](#android_ems)
* [android:endYear](#android_endYear)
* [android:entries](#android_entries)
* [android:fadingEdgeLength](#android_fadingEdgeLength)
* [android:fillViewport](#android_fillViewport)
* [android:fitsSystemWindows](#android_fitsSystemWindows)
* [android:flipInterval](#android_flipInterval)
* [android:focusable](#android_focusable)
* [android:focusableInTouchMode](#android_focusableInTouchMode)
* [android:foreground](#android_foreground)
* [android:foregroundGravity](#android_foregroundGravity)
* [android:format](#android_format)
* [android:freezesText](#android_freezesText)
* [android:gravity](#android_gravity)
* [android:groupIndicator](#android_groupIndicator)
* [android:hand_hour](#android_hand_hour)
* [android:hand_minute](#android_hand_minute)
* [android:headerBackground](#android_headerBackground)
* [android:height](#android_height)
* [android:hint](#android_hint)
* [android:horizontalSpacing](#android_horizontalSpacing)
* [android:id](#android_id)
* [android:ignoreGravity](#android_ignoreGravity)
* [android:inAnimation](#android_inAnimation)
* [android:includeFontPadding](#android_includeFontPadding)
* [android:indeterminate](#android_indeterminate)
* [android:indeterminateBehavior](#android_indeterminateBehavior)
* [android:indeterminateDrawable](#android_indeterminateDrawable)
* [android:indeterminateDuration](#android_indeterminateDuration)
* [android:indeterminateOnly](#android_indeterminateOnly)
* [android:indicatorLeft](#android_indicatorLeft)
* [android:indicatorRight](#android_indicatorRight)
* [android:inflatedId](#android_inflatedId)
* [android:inputMethod](#android_inputMethod)
* [android:interpolator](#android_interpolator)
* [android:isIndicator](#android_isIndicator)
* [android:keepScreenOn](#android_keepScreenOn)
* [android:layout](#android_layout)
* [android:layoutAnimation](#android_layoutAnimation)
* [android:lineSpacingExtra](#android_lineSpacingExtra)
* [android:lineSpacingMultiplier](#android_lineSpacingMultiplier)
* [android:lines](#android_lines)
* [android:linksClickable](#android_linksClickable)
* [android:listSelector](#android_listSelector)
* [android:longClickable](#android_longClickable)
* [android:max](#android_max)
* [android:maxEms](#android_maxEms)
* [android:maxHeight](#android_maxHeight)
* [android:maxLength](#android_maxLength)
* [android:maxLines](#android_maxLines)
* [android:maxWidth](#android_maxWidth)
* [android:measureAllChildren](#android_measureAllChildren)
* [android:minEms](#android_minEms)
* [android:minHeight](#android_minHeight)
* [android:minLines](#android_minLines)
* [android:minWidth](#android_minWidth)
* [android:nextFocusDown](#android_nextFocusDown)
* [android:nextFocusLeft](#android_nextFocusLeft)
* [android:nextFocusRight](#android_nextFocusRight)
* [android:nextFocusUp](#android_nextFocusUp)
* [android:numColumns](#android_numColumns)
* [android:numStars](#android_numStars)
* [android:numeric](#android_numeric)
* [android:orientation](#android_orientation)
* [android:outAnimation](#android_outAnimation)
* [android:padding](#android_padding)
* [android:paddingBottom](#android_paddingBottom)
* [android:paddingLeft](#android_paddingLeft)
* [android:paddingRight](#android_paddingRight)
* [android:paddingTop](#android_paddingTop)
* [android:password](#android_password)
* [android:persistentDrawingCache](#android_persistentDrawingCache)
* [android:phoneNumber](#android_phoneNumber)
* [android:popupBackground](#android_popupBackground)
* [android:progress](#android_progress)
* [android:progressDrawable](#android_progressDrawable)
* [android:prompt](#android_prompt)
* [android:rating](#android_rating)
* [android:saveEnabled](#android_saveEnabled)
* [android:scaleType](#android_scaleType)
* [android:scrollHorizontally](#android_scrollHorizontally)
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
* [android:scrollingCache](#android_scrollingCache)
* [android:secondaryProgress](#android_secondaryProgress)
* [android:selectAllOnFocus](#android_selectAllOnFocus)
* [android:shadowColor](#android_shadowColor)
* [android:shadowDx](#android_shadowDx)
* [android:shadowDy](#android_shadowDy)
* [android:shadowRadius](#android_shadowRadius)
* [android:shrinkColumns](#android_shrinkColumns)
* [android:singleLine](#android_singleLine)
* [android:soundEffectsEnabled](#android_soundEffectsEnabled)
* [android:src](#android_src)
* [android:stackFromBottom](#android_stackFromBottom)
* [android:startYear](#android_startYear)
* [android:stepSize](#android_stepSize)
* [android:stretchColumns](#android_stretchColumns)
* [android:stretchMode](#android_stretchMode)
* [android:tabStripEnabled](#android_tabStripEnabled)
* [android:tabStripLeft](#android_tabStripLeft)
* [android:tabStripRight](#android_tabStripRight)
* [android:tag](#android_tag)
* [android:text](#android_text)
* [android:textAppearance](#android_textAppearance)
* [android:textColor](#android_textColor)
* [android:textColorHighlight](#android_textColorHighlight)
* [android:textColorHint](#android_textColorHint)
* [android:textColorLink](#android_textColorLink)
* [android:textFilterEnabled](#android_textFilterEnabled)
* [android:textOff](#android_textOff)
* [android:textOn](#android_textOn)
* [android:textScaleX](#android_textScaleX)
* [android:textSize](#android_textSize)
* [android:textStyle](#android_textStyle)
* [android:thumb](#android_thumb)
* [android:tint](#android_tint)
* [android:transcriptMode](#android_transcriptMode)
* [android:typeface](#android_typeface)
* [android:verticalSpacing](#android_verticalSpacing)
* [android:visibility](#android_visibility)
* [android:weightSum](#android_weightSum)
* [android:width](#android_width)

### <a name="android_addStatesFromChildren"></a>android:addStatesFromChildren

format: 

API level: [API 1](#api_1)

related styles: [ViewGroup](#ViewGroup)

--

### <a name="android_adjustViewBounds"></a>android:adjustViewBounds

format: 

API level: [API 1](#api_1)

related styles: [ImageView](#ImageView)

--

### <a name="android_alwaysDrawnWithCache"></a>android:alwaysDrawnWithCache

format: 

API level: [API 1](#api_1)

related styles: [ViewGroup](#ViewGroup)

--

### <a name="android_animationCache"></a>android:animationCache

format: 

API level: [API 1](#api_1)

related styles: [ViewGroup](#ViewGroup)

--

### <a name="android_autoLink"></a>android:autoLink

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_autoText"></a>android:autoText

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_background"></a>android:background

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_baselineAlignBottom"></a>android:baselineAlignBottom

format: 

API level: [API 1](#api_1)

related styles: [ImageView](#ImageView)

--

### <a name="android_baselineAligned"></a>android:baselineAligned

format: 

API level: [API 1](#api_1)

related styles: [LinearLayout](#LinearLayout)

--

### <a name="android_baselineAlignedChildIndex"></a>android:baselineAlignedChildIndex

format: 

API level: [API 1](#api_1)

related styles: [LinearLayout](#LinearLayout)

--

### <a name="android_bufferType"></a>android:bufferType

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_cacheColorHint"></a>android:cacheColorHint

format: 

API level: [API 1](#api_1)

related styles: [AbsListView](#AbsListView)

--

### <a name="android_capitalize"></a>android:capitalize

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_checkMark"></a>android:checkMark

format: 

API level: [API 1](#api_1)

related styles: [CheckedTextView](#CheckedTextView)

--

### <a name="android_checked"></a>android:checked

format: 

API level: [API 1](#api_1)

related styles: [CheckedTextView](#CheckedTextView)

--

### <a name="android_checkedButton"></a>android:checkedButton

format: 

API level: [API 1](#api_1)

related styles: [RadioGroup](#RadioGroup)

--

### <a name="android_childDivider"></a>android:childDivider

format: 

API level: [API 1](#api_1)

related styles: [ExpandableListView](#ExpandableListView)

--

### <a name="android_childIndicator"></a>android:childIndicator

format: 

API level: [API 1](#api_1)

related styles: [ExpandableListView](#ExpandableListView)

--

### <a name="android_childIndicatorLeft"></a>android:childIndicatorLeft

format: 

API level: [API 1](#api_1)

related styles: [ExpandableListView](#ExpandableListView)

--

### <a name="android_childIndicatorRight"></a>android:childIndicatorRight

format: 

API level: [API 1](#api_1)

related styles: [ExpandableListView](#ExpandableListView)

--

### <a name="android_choiceMode"></a>android:choiceMode

format: 

API level: [API 1](#api_1)

related styles: [AbsListView](#AbsListView)

--

### <a name="android_clickable"></a>android:clickable

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_clipChildren"></a>android:clipChildren

format: 

API level: [API 1](#api_1)

related styles: [ViewGroup](#ViewGroup)

--

### <a name="android_clipToPadding"></a>android:clipToPadding

format: 

API level: [API 1](#api_1)

related styles: [ViewGroup](#ViewGroup)

--

### <a name="android_collapseColumns"></a>android:collapseColumns

format: 

API level: [API 1](#api_1)

related styles: [TableLayout](#TableLayout)

--

### <a name="android_columnWidth"></a>android:columnWidth

format: 

API level: [API 1](#api_1)

related styles: [GridView](#GridView)

--

### <a name="android_completionHint"></a>android:completionHint

format: 

API level: [API 1](#api_1)

related styles: [AutoCompleteTextView](#AutoCompleteTextView)

--

### <a name="android_completionHintView"></a>android:completionHintView

format: 

API level: [API 1](#api_1)

related styles: [AutoCompleteTextView](#AutoCompleteTextView)

--

### <a name="android_completionThreshold"></a>android:completionThreshold

format: 

API level: [API 1](#api_1)

related styles: [AutoCompleteTextView](#AutoCompleteTextView)

--

### <a name="android_cropToPadding"></a>android:cropToPadding

format: 

API level: [API 1](#api_1)

related styles: [ImageView](#ImageView)

--

### <a name="android_cursorVisible"></a>android:cursorVisible

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_descendantFocusability"></a>android:descendantFocusability

format: 

API level: [API 1](#api_1)

related styles: [ViewGroup](#ViewGroup)

--

### <a name="android_dial"></a>android:dial

format: 

API level: [API 1](#api_1)

related styles: [AnalogClock](#AnalogClock)

--

### <a name="android_digits"></a>android:digits

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_disabledAlpha"></a>android:disabledAlpha

format: 

API level: [API 1](#api_1)

related styles: [ToggleButton](#ToggleButton)

--

### <a name="android_divider"></a>android:divider

format: 

API level: [API 1](#api_1)

related styles: [ListView](#ListView), [LinearLayout](#LinearLayout), [TabWidget](#TabWidget)

--

### <a name="android_dividerHeight"></a>android:dividerHeight

format: 

API level: [API 1](#api_1)

related styles: [ListView](#ListView)

--

### <a name="android_drawSelectorOnTop"></a>android:drawSelectorOnTop

format: 

API level: [API 1](#api_1)

related styles: [AbsListView](#AbsListView)

--

### <a name="android_drawableBottom"></a>android:drawableBottom

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_drawableLeft"></a>android:drawableLeft

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_drawablePadding"></a>android:drawablePadding

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_drawableRight"></a>android:drawableRight

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_drawableTop"></a>android:drawableTop

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_drawingCacheQuality"></a>android:drawingCacheQuality

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_dropDownSelector"></a>android:dropDownSelector

format: 

API level: [API 1](#api_1)

related styles: [AutoCompleteTextView](#AutoCompleteTextView), [Spinner](#Spinner)

--

### <a name="android_duplicateParentState"></a>android:duplicateParentState

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_editable"></a>android:editable

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_ellipsize"></a>android:ellipsize

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_ems"></a>android:ems

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_endYear"></a>android:endYear

format: 

API level: [API 1](#api_1)

related styles: [DatePicker](#DatePicker)

--

### <a name="android_entries"></a>android:entries

format: 

API level: [API 1](#api_1)

related styles: [ListView](#ListView), [AbsSpinner](#AbsSpinner)

--

### <a name="android_fadingEdgeLength"></a>android:fadingEdgeLength

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_fillViewport"></a>android:fillViewport

format: 

API level: [API 1](#api_1)

related styles: [ScrollView](#ScrollView), [HorizontalScrollView](#HorizontalScrollView)

--

### <a name="android_fitsSystemWindows"></a>android:fitsSystemWindows

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_flipInterval"></a>android:flipInterval

format: 

API level: [API 1](#api_1)

related styles: [AdapterViewFlipper](#AdapterViewFlipper), [ViewFlipper](#ViewFlipper)

--

### <a name="android_focusable"></a>android:focusable

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_focusableInTouchMode"></a>android:focusableInTouchMode

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_foreground"></a>android:foreground

format: 

API level: [API 1](#api_1)

related styles: [FrameLayout](#FrameLayout)

--

### <a name="android_foregroundGravity"></a>android:foregroundGravity

format: 

API level: [API 1](#api_1)

related styles: [FrameLayout](#FrameLayout)

--

### <a name="android_format"></a>android:format

format: 

API level: [API 1](#api_1)

related styles: [Chronometer](#Chronometer)

--

### <a name="android_freezesText"></a>android:freezesText

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_gravity"></a>android:gravity

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView), [GridView](#GridView), [Spinner](#Spinner), [LinearLayout](#LinearLayout), [RelativeLayout](#RelativeLayout)

--

### <a name="android_groupIndicator"></a>android:groupIndicator

format: 

API level: [API 1](#api_1)

related styles: [ExpandableListView](#ExpandableListView)

--

### <a name="android_hand_hour"></a>android:hand_hour

format: 

API level: [API 1](#api_1)

related styles: [AnalogClock](#AnalogClock)

--

### <a name="android_hand_minute"></a>android:hand_minute

format: 

API level: [API 1](#api_1)

related styles: [AnalogClock](#AnalogClock)

--

### <a name="android_headerBackground"></a>android:headerBackground

format: 

API level: [API 1](#api_1)

related styles: [DatePicker](#DatePicker)

--

### <a name="android_height"></a>android:height

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_hint"></a>android:hint

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_horizontalSpacing"></a>android:horizontalSpacing

format: 

API level: [API 1](#api_1)

related styles: [GridView](#GridView)

--

### <a name="android_id"></a>android:id

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_ignoreGravity"></a>android:ignoreGravity

format: 

API level: [API 1](#api_1)

related styles: [RelativeLayout](#RelativeLayout)

--

### <a name="android_inAnimation"></a>android:inAnimation

format: 

API level: [API 1](#api_1)

related styles: [AdapterViewAnimator](#AdapterViewAnimator), [ViewAnimator](#ViewAnimator)

--

### <a name="android_includeFontPadding"></a>android:includeFontPadding

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_indeterminate"></a>android:indeterminate

format: 

API level: [API 1](#api_1)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_indeterminateBehavior"></a>android:indeterminateBehavior

format: 

API level: [API 1](#api_1)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_indeterminateDrawable"></a>android:indeterminateDrawable

format: 

API level: [API 1](#api_1)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_indeterminateDuration"></a>android:indeterminateDuration

format: 

API level: [API 1](#api_1)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_indeterminateOnly"></a>android:indeterminateOnly

format: 

API level: [API 1](#api_1)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_indicatorLeft"></a>android:indicatorLeft

format: 

API level: [API 1](#api_1)

related styles: [ExpandableListView](#ExpandableListView)

--

### <a name="android_indicatorRight"></a>android:indicatorRight

format: 

API level: [API 1](#api_1)

related styles: [ExpandableListView](#ExpandableListView)

--

### <a name="android_inflatedId"></a>android:inflatedId

format: 

API level: [API 1](#api_1)

related styles: [ViewStub](#ViewStub)

--

### <a name="android_inputMethod"></a>android:inputMethod

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_interpolator"></a>android:interpolator

format: 

API level: [API 1](#api_1)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_isIndicator"></a>android:isIndicator

format: 

API level: [API 1](#api_1)

related styles: [RatingBar](#RatingBar)

--

### <a name="android_keepScreenOn"></a>android:keepScreenOn

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_layout"></a>android:layout

format: 

API level: [API 1](#api_1)

related styles: [ViewStub](#ViewStub)

--

### <a name="android_layoutAnimation"></a>android:layoutAnimation

format: 

API level: [API 1](#api_1)

related styles: [ViewGroup](#ViewGroup)

--

### <a name="android_lineSpacingExtra"></a>android:lineSpacingExtra

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_lineSpacingMultiplier"></a>android:lineSpacingMultiplier

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_lines"></a>android:lines

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_linksClickable"></a>android:linksClickable

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_listSelector"></a>android:listSelector

format: 

API level: [API 1](#api_1)

related styles: [AbsListView](#AbsListView)

--

### <a name="android_longClickable"></a>android:longClickable

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_max"></a>android:max

format: 

API level: [API 1](#api_1)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_maxEms"></a>android:maxEms

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_maxHeight"></a>android:maxHeight

format: 

API level: [API 1](#api_1)

related styles: [ImageView](#ImageView), [ProgressBar](#ProgressBar), [TextView](#TextView)

--

### <a name="android_maxLength"></a>android:maxLength

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_maxLines"></a>android:maxLines

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_maxWidth"></a>android:maxWidth

format: 

API level: [API 1](#api_1)

related styles: [ImageView](#ImageView), [ProgressBar](#ProgressBar), [TextView](#TextView), [SearchView](#SearchView)

--

### <a name="android_measureAllChildren"></a>android:measureAllChildren

format: 

API level: [API 1](#api_1)

related styles: [FrameLayout](#FrameLayout)

--

### <a name="android_minEms"></a>android:minEms

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_minHeight"></a>android:minHeight

format: 

API level: [API 1](#api_1)

related styles: [View](#View), [ProgressBar](#ProgressBar), [TextView](#TextView)

--

### <a name="android_minLines"></a>android:minLines

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_minWidth"></a>android:minWidth

format: 

API level: [API 1](#api_1)

related styles: [View](#View), [ProgressBar](#ProgressBar), [TextView](#TextView)

--

### <a name="android_nextFocusDown"></a>android:nextFocusDown

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_nextFocusLeft"></a>android:nextFocusLeft

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_nextFocusRight"></a>android:nextFocusRight

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_nextFocusUp"></a>android:nextFocusUp

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_numColumns"></a>android:numColumns

format: 

API level: [API 1](#api_1)

related styles: [GridView](#GridView)

--

### <a name="android_numStars"></a>android:numStars

format: 

API level: [API 1](#api_1)

related styles: [RatingBar](#RatingBar)

--

### <a name="android_numeric"></a>android:numeric

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_orientation"></a>android:orientation

format: 

API level: [API 1](#api_1)

related styles: [GestureOverlayView](#GestureOverlayView), [LinearLayout](#LinearLayout)

--

### <a name="android_outAnimation"></a>android:outAnimation

format: 

API level: [API 1](#api_1)

related styles: [AdapterViewAnimator](#AdapterViewAnimator), [ViewAnimator](#ViewAnimator)

--

### <a name="android_padding"></a>android:padding

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_paddingBottom"></a>android:paddingBottom

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_paddingLeft"></a>android:paddingLeft

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_paddingRight"></a>android:paddingRight

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_paddingTop"></a>android:paddingTop

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_password"></a>android:password

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_persistentDrawingCache"></a>android:persistentDrawingCache

format: 

API level: [API 1](#api_1)

related styles: [ViewGroup](#ViewGroup)

--

### <a name="android_phoneNumber"></a>android:phoneNumber

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_popupBackground"></a>android:popupBackground

format: 

API level: [API 1](#api_1)

related styles: [AutoCompleteTextView](#AutoCompleteTextView), [Spinner](#Spinner)

--

### <a name="android_progress"></a>android:progress

format: 

API level: [API 1](#api_1)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_progressDrawable"></a>android:progressDrawable

format: 

API level: [API 1](#api_1)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_prompt"></a>android:prompt

format: 

API level: [API 1](#api_1)

related styles: [Spinner](#Spinner)

--

### <a name="android_rating"></a>android:rating

format: 

API level: [API 1](#api_1)

related styles: [RatingBar](#RatingBar)

--

### <a name="android_saveEnabled"></a>android:saveEnabled

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_scaleType"></a>android:scaleType

format: 

API level: [API 1](#api_1)

related styles: [ImageView](#ImageView)

--

### <a name="android_scrollHorizontally"></a>android:scrollHorizontally

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_scrollX"></a>android:scrollX

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_scrollY"></a>android:scrollY

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_scrollbarAlwaysDrawHorizontalTrack"></a>android:scrollbarAlwaysDrawHorizontalTrack

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_scrollbarAlwaysDrawVerticalTrack"></a>android:scrollbarAlwaysDrawVerticalTrack

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_scrollbarSize"></a>android:scrollbarSize

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_scrollbarStyle"></a>android:scrollbarStyle

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_scrollbarThumbHorizontal"></a>android:scrollbarThumbHorizontal

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_scrollbarThumbVertical"></a>android:scrollbarThumbVertical

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_scrollbarTrackHorizontal"></a>android:scrollbarTrackHorizontal

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_scrollbarTrackVertical"></a>android:scrollbarTrackVertical

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_scrollbars"></a>android:scrollbars

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_scrollingCache"></a>android:scrollingCache

format: 

API level: [API 1](#api_1)

related styles: [AbsListView](#AbsListView)

--

### <a name="android_secondaryProgress"></a>android:secondaryProgress

format: 

API level: [API 1](#api_1)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_selectAllOnFocus"></a>android:selectAllOnFocus

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_shadowColor"></a>android:shadowColor

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_shadowDx"></a>android:shadowDx

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_shadowDy"></a>android:shadowDy

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_shadowRadius"></a>android:shadowRadius

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_shrinkColumns"></a>android:shrinkColumns

format: 

API level: [API 1](#api_1)

related styles: [TableLayout](#TableLayout)

--

### <a name="android_singleLine"></a>android:singleLine

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_soundEffectsEnabled"></a>android:soundEffectsEnabled

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_src"></a>android:src

format: 

API level: [API 1](#api_1)

related styles: [ImageView](#ImageView)

--

### <a name="android_stackFromBottom"></a>android:stackFromBottom

format: 

API level: [API 1](#api_1)

related styles: [AbsListView](#AbsListView)

--

### <a name="android_startYear"></a>android:startYear

format: 

API level: [API 1](#api_1)

related styles: [DatePicker](#DatePicker)

--

### <a name="android_stepSize"></a>android:stepSize

format: 

API level: [API 1](#api_1)

related styles: [RatingBar](#RatingBar)

--

### <a name="android_stretchColumns"></a>android:stretchColumns

format: 

API level: [API 1](#api_1)

related styles: [TableLayout](#TableLayout)

--

### <a name="android_stretchMode"></a>android:stretchMode

format: 

API level: [API 1](#api_1)

related styles: [GridView](#GridView)

--

### <a name="android_tabStripEnabled"></a>android:tabStripEnabled

format: 

API level: [API 1](#api_1)

related styles: [TabWidget](#TabWidget)

--

### <a name="android_tabStripLeft"></a>android:tabStripLeft

format: 

API level: [API 1](#api_1)

related styles: [TabWidget](#TabWidget)

--

### <a name="android_tabStripRight"></a>android:tabStripRight

format: 

API level: [API 1](#api_1)

related styles: [TabWidget](#TabWidget)

--

### <a name="android_tag"></a>android:tag

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_text"></a>android:text

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_textAppearance"></a>android:textAppearance

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_textColor"></a>android:textColor

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_textColorHighlight"></a>android:textColorHighlight

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_textColorHint"></a>android:textColorHint

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_textColorLink"></a>android:textColorLink

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_textFilterEnabled"></a>android:textFilterEnabled

format: 

API level: [API 1](#api_1)

related styles: [AbsListView](#AbsListView)

--

### <a name="android_textOff"></a>android:textOff

format: 

API level: [API 1](#api_1)

related styles: [ToggleButton](#ToggleButton), [Switch](#Switch)

--

### <a name="android_textOn"></a>android:textOn

format: 

API level: [API 1](#api_1)

related styles: [ToggleButton](#ToggleButton), [Switch](#Switch)

--

### <a name="android_textScaleX"></a>android:textScaleX

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_textSize"></a>android:textSize

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

### <a name="android_textStyle"></a>android:textStyle

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView), [Switch](#Switch)

--

### <a name="android_thumb"></a>android:thumb

format: 

API level: [API 1](#api_1)

related styles: [SeekBar](#SeekBar), [Switch](#Switch)

--

### <a name="android_tint"></a>android:tint

format: 

API level: [API 1](#api_1)

related styles: [ImageView](#ImageView)

--

### <a name="android_transcriptMode"></a>android:transcriptMode

format: 

API level: [API 1](#api_1)

related styles: [AbsListView](#AbsListView)

--

### <a name="android_typeface"></a>android:typeface

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView), [Switch](#Switch)

--

### <a name="android_verticalSpacing"></a>android:verticalSpacing

format: 

API level: [API 1](#api_1)

related styles: [GridView](#GridView)

--

### <a name="android_visibility"></a>android:visibility

format: 

API level: [API 1](#api_1)

related styles: [View](#View)

--

### <a name="android_weightSum"></a>android:weightSum

format: 

API level: [API 1](#api_1)

related styles: [LinearLayout](#LinearLayout)

--

### <a name="android_width"></a>android:width

format: 

API level: [API 1](#api_1)

related styles: [TextView](#TextView)

--

## <a name="api_2"></a>API 2

### Attribute list

* [android:marqueeRepeatLimit](#android_marqueeRepeatLimit)

### <a name="android_marqueeRepeatLimit"></a>android:marqueeRepeatLimit

format: 

API level: [API 2](#api_2)

related styles: [TextView](#TextView)

--

## <a name="api_3"></a>API 3

### Attribute list

* [android:dropDownAnchor](#android_dropDownAnchor)
* [android:dropDownWidth](#android_dropDownWidth)
* [android:editorExtras](#android_editorExtras)
* [android:fastScrollEnabled](#android_fastScrollEnabled)
* [android:footerDividersEnabled](#android_footerDividersEnabled)
* [android:hapticFeedbackEnabled](#android_hapticFeedbackEnabled)
* [android:headerDividersEnabled](#android_headerDividersEnabled)
* [android:imeActionId](#android_imeActionId)
* [android:imeActionLabel](#android_imeActionLabel)
* [android:imeOptions](#android_imeOptions)
* [android:inputType](#android_inputType)
* [android:isScrollContainer](#android_isScrollContainer)
* [android:keyBackground](#android_keyBackground)
* [android:keyPreviewLayout](#android_keyPreviewLayout)
* [android:keyPreviewOffset](#android_keyPreviewOffset)
* [android:keyTextColor](#android_keyTextColor)
* [android:keyTextSize](#android_keyTextSize)
* [android:labelTextSize](#android_labelTextSize)
* [android:popupLayout](#android_popupLayout)
* [android:privateImeOptions](#android_privateImeOptions)
* [android:smoothScrollbar](#android_smoothScrollbar)
* [android:verticalCorrection](#android_verticalCorrection)

### <a name="android_dropDownAnchor"></a>android:dropDownAnchor

format: 

API level: [API 3](#api_3)

related styles: [AutoCompleteTextView](#AutoCompleteTextView)

--

### <a name="android_dropDownWidth"></a>android:dropDownWidth

format: 

API level: [API 3](#api_3)

related styles: [AutoCompleteTextView](#AutoCompleteTextView), [Spinner](#Spinner)

--

### <a name="android_editorExtras"></a>android:editorExtras

format: 

API level: [API 3](#api_3)

related styles: [TextView](#TextView)

--

### <a name="android_fastScrollEnabled"></a>android:fastScrollEnabled

format: 

API level: [API 3](#api_3)

related styles: [AbsListView](#AbsListView)

--

### <a name="android_footerDividersEnabled"></a>android:footerDividersEnabled

format: 

API level: [API 3](#api_3)

related styles: [ListView](#ListView)

--

### <a name="android_hapticFeedbackEnabled"></a>android:hapticFeedbackEnabled

format: 

API level: [API 3](#api_3)

related styles: [View](#View)

--

### <a name="android_headerDividersEnabled"></a>android:headerDividersEnabled

format: 

API level: [API 3](#api_3)

related styles: [ListView](#ListView)

--

### <a name="android_imeActionId"></a>android:imeActionId

format: 

API level: [API 3](#api_3)

related styles: [TextView](#TextView)

--

### <a name="android_imeActionLabel"></a>android:imeActionLabel

format: 

API level: [API 3](#api_3)

related styles: [TextView](#TextView)

--

### <a name="android_imeOptions"></a>android:imeOptions

format: 

API level: [API 3](#api_3)

related styles: [TextView](#TextView), [SearchView](#SearchView)

--

### <a name="android_inputType"></a>android:inputType

format: 

API level: [API 3](#api_3)

related styles: [TextView](#TextView), [SearchView](#SearchView)

--

### <a name="android_isScrollContainer"></a>android:isScrollContainer

format: 

API level: [API 3](#api_3)

related styles: [View](#View)

--

### <a name="android_keyBackground"></a>android:keyBackground

format: 

API level: [API 3](#api_3)

related styles: [DialerFilter](#DialerFilter)

--

### <a name="android_keyPreviewLayout"></a>android:keyPreviewLayout

format: 

API level: [API 3](#api_3)

related styles: [DialerFilter](#DialerFilter)

--

### <a name="android_keyPreviewOffset"></a>android:keyPreviewOffset

format: 

API level: [API 3](#api_3)

related styles: [DialerFilter](#DialerFilter)

--

### <a name="android_keyTextColor"></a>android:keyTextColor

format: 

API level: [API 3](#api_3)

related styles: [DialerFilter](#DialerFilter)

--

### <a name="android_keyTextSize"></a>android:keyTextSize

format: 

API level: [API 3](#api_3)

related styles: [DialerFilter](#DialerFilter)

--

### <a name="android_labelTextSize"></a>android:labelTextSize

format: 

API level: [API 3](#api_3)

related styles: [DialerFilter](#DialerFilter)

--

### <a name="android_popupLayout"></a>android:popupLayout

format: 

API level: [API 3](#api_3)

related styles: [DialerFilter](#DialerFilter)

--

### <a name="android_privateImeOptions"></a>android:privateImeOptions

format: 

API level: [API 3](#api_3)

related styles: [TextView](#TextView)

--

### <a name="android_smoothScrollbar"></a>android:smoothScrollbar

format: 

API level: [API 3](#api_3)

related styles: [AbsListView](#AbsListView)

--

### <a name="android_verticalCorrection"></a>android:verticalCorrection

format: 

API level: [API 3](#api_3)

related styles: [DialerFilter](#DialerFilter)

--

## <a name="api_4"></a>API 4

### Attribute list

* [android:contentDescription](#android_contentDescription)
* [android:dropDownHeight](#android_dropDownHeight)
* [android:eventsInterceptionEnabled](#android_eventsInterceptionEnabled)
* [android:fadeDuration](#android_fadeDuration)
* [android:fadeEnabled](#android_fadeEnabled)
* [android:fadeOffset](#android_fadeOffset)
* [android:gestureColor](#android_gestureColor)
* [android:gestureStrokeAngleThreshold](#android_gestureStrokeAngleThreshold)
* [android:gestureStrokeLengthThreshold](#android_gestureStrokeLengthThreshold)
* [android:gestureStrokeSquarenessThreshold](#android_gestureStrokeSquarenessThreshold)
* [android:gestureStrokeType](#android_gestureStrokeType)
* [android:gestureStrokeWidth](#android_gestureStrokeWidth)
* [android:onClick](#android_onClick)
* [android:uncertainGestureColor](#android_uncertainGestureColor)

### <a name="android_contentDescription"></a>android:contentDescription

format: 

API level: [API 4](#api_4)

related styles: [View](#View)

--

### <a name="android_dropDownHeight"></a>android:dropDownHeight

format: 

API level: [API 4](#api_4)

related styles: [AutoCompleteTextView](#AutoCompleteTextView)

--

### <a name="android_eventsInterceptionEnabled"></a>android:eventsInterceptionEnabled

format: 

API level: [API 4](#api_4)

related styles: [GestureOverlayView](#GestureOverlayView)

--

### <a name="android_fadeDuration"></a>android:fadeDuration

format: 

API level: [API 4](#api_4)

related styles: [GestureOverlayView](#GestureOverlayView)

--

### <a name="android_fadeEnabled"></a>android:fadeEnabled

format: 

API level: [API 4](#api_4)

related styles: [GestureOverlayView](#GestureOverlayView)

--

### <a name="android_fadeOffset"></a>android:fadeOffset

format: 

API level: [API 4](#api_4)

related styles: [GestureOverlayView](#GestureOverlayView)

--

### <a name="android_gestureColor"></a>android:gestureColor

format: 

API level: [API 4](#api_4)

related styles: [GestureOverlayView](#GestureOverlayView)

--

### <a name="android_gestureStrokeAngleThreshold"></a>android:gestureStrokeAngleThreshold

format: 

API level: [API 4](#api_4)

related styles: [GestureOverlayView](#GestureOverlayView)

--

### <a name="android_gestureStrokeLengthThreshold"></a>android:gestureStrokeLengthThreshold

format: 

API level: [API 4](#api_4)

related styles: [GestureOverlayView](#GestureOverlayView)

--

### <a name="android_gestureStrokeSquarenessThreshold"></a>android:gestureStrokeSquarenessThreshold

format: 

API level: [API 4](#api_4)

related styles: [GestureOverlayView](#GestureOverlayView)

--

### <a name="android_gestureStrokeType"></a>android:gestureStrokeType

format: 

API level: [API 4](#api_4)

related styles: [GestureOverlayView](#GestureOverlayView)

--

### <a name="android_gestureStrokeWidth"></a>android:gestureStrokeWidth

format: 

API level: [API 4](#api_4)

related styles: [GestureOverlayView](#GestureOverlayView)

--

### <a name="android_onClick"></a>android:onClick

format: 

API level: [API 4](#api_4)

related styles: [View](#View)

--

### <a name="android_uncertainGestureColor"></a>android:uncertainGestureColor

format: 

API level: [API 4](#api_4)

related styles: [GestureOverlayView](#GestureOverlayView)

--

## <a name="api_5"></a>API 5

### Attribute list

* [android:dropDownHorizontalOffset](#android_dropDownHorizontalOffset)
* [android:dropDownVerticalOffset](#android_dropDownVerticalOffset)
* [android:fadeScrollbars](#android_fadeScrollbars)
* [android:scrollbarDefaultDelayBeforeFade](#android_scrollbarDefaultDelayBeforeFade)
* [android:scrollbarFadeDuration](#android_scrollbarFadeDuration)

### <a name="android_dropDownHorizontalOffset"></a>android:dropDownHorizontalOffset

format: 

API level: [API 5](#api_5)

related styles: [AutoCompleteTextView](#AutoCompleteTextView), [Spinner](#Spinner)

--

### <a name="android_dropDownVerticalOffset"></a>android:dropDownVerticalOffset

format: 

API level: [API 5](#api_5)

related styles: [AutoCompleteTextView](#AutoCompleteTextView), [Spinner](#Spinner)

--

### <a name="android_fadeScrollbars"></a>android:fadeScrollbars

format: 

API level: [API 5](#api_5)

related styles: [View](#View)

--

### <a name="android_scrollbarDefaultDelayBeforeFade"></a>android:scrollbarDefaultDelayBeforeFade

format: 

API level: [API 5](#api_5)

related styles: [View](#View)

--

### <a name="android_scrollbarFadeDuration"></a>android:scrollbarFadeDuration

format: 

API level: [API 5](#api_5)

related styles: [View](#View)

--

## <a name="api_7"></a>API 7

### Attribute list

* [android:autoStart](#android_autoStart)

### <a name="android_autoStart"></a>android:autoStart

format: 

API level: [API 7](#api_7)

related styles: [AdapterViewFlipper](#AdapterViewFlipper), [ViewFlipper](#ViewFlipper)

--

## <a name="api_9"></a>API 9

### Attribute list

* [android:filterTouchesWhenObscured](#android_filterTouchesWhenObscured)

### <a name="android_filterTouchesWhenObscured"></a>android:filterTouchesWhenObscured

format: 

API level: [API 9](#api_9)

related styles: [View](#View)

--

## <a name="api_11"></a>API 11

### Attribute list

* [android:alpha](#android_alpha)
* [android:animateFirstView](#android_animateFirstView)
* [android:animateLayoutChanges](#android_animateLayoutChanges)
* [android:animationResolution](#android_animationResolution)
* [android:baseline](#android_baseline)
* [android:calendarViewShown](#android_calendarViewShown)
* [android:dateTextAppearance](#android_dateTextAppearance)
* [android:firstDayOfWeek](#android_firstDayOfWeek)
* [android:focusedMonthDateColor](#android_focusedMonthDateColor)
* [android:iconifiedByDefault](#android_iconifiedByDefault)
* [android:layerType](#android_layerType)
* [android:loopViews](#android_loopViews)
* [android:maxDate](#android_maxDate)
* [android:measureWithLargestChild](#android_measureWithLargestChild)
* [android:minDate](#android_minDate)
* [android:nextFocusForward](#android_nextFocusForward)
* [android:queryHint](#android_queryHint)
* [android:rotation](#android_rotation)
* [android:rotationX](#android_rotationX)
* [android:rotationY](#android_rotationY)
* [android:scaleX](#android_scaleX)
* [android:scaleY](#android_scaleY)
* [android:selectedDateVerticalBar](#android_selectedDateVerticalBar)
* [android:selectedWeekBackgroundColor](#android_selectedWeekBackgroundColor)
* [android:showWeekNumber](#android_showWeekNumber)
* [android:shownWeekCount](#android_shownWeekCount)
* [android:spinnerMode](#android_spinnerMode)
* [android:spinnersShown](#android_spinnersShown)
* [android:splitMotionEvents](#android_splitMotionEvents)
* [android:textIsSelectable](#android_textIsSelectable)
* [android:transformPivotX](#android_transformPivotX)
* [android:transformPivotY](#android_transformPivotY)
* [android:translationX](#android_translationX)
* [android:translationY](#android_translationY)
* [android:unfocusedMonthDateColor](#android_unfocusedMonthDateColor)
* [android:weekDayTextAppearance](#android_weekDayTextAppearance)
* [android:weekNumberColor](#android_weekNumberColor)
* [android:weekSeparatorLineColor](#android_weekSeparatorLineColor)

### <a name="android_alpha"></a>android:alpha

format: 

API level: [API 11](#api_11)

related styles: [View](#View)

--

### <a name="android_animateFirstView"></a>android:animateFirstView

format: 

API level: [API 11](#api_11)

related styles: [AdapterViewAnimator](#AdapterViewAnimator), [ViewAnimator](#ViewAnimator)

--

### <a name="android_animateLayoutChanges"></a>android:animateLayoutChanges

format: 

API level: [API 11](#api_11)

related styles: [ViewGroup](#ViewGroup)

--

### <a name="android_animationResolution"></a>android:animationResolution

format: 

API level: [API 11](#api_11)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_baseline"></a>android:baseline

format: 

API level: [API 11](#api_11)

related styles: [ImageView](#ImageView)

--

### <a name="android_calendarViewShown"></a>android:calendarViewShown

format: 

API level: [API 11](#api_11)

related styles: [DatePicker](#DatePicker)

--

### <a name="android_dateTextAppearance"></a>android:dateTextAppearance

format: 

API level: [API 11](#api_11)

related styles: [CalendarView](#CalendarView)

--

### <a name="android_firstDayOfWeek"></a>android:firstDayOfWeek

format: 

API level: [API 11](#api_11)

related styles: [DatePicker](#DatePicker), [CalendarView](#CalendarView)

--

### <a name="android_focusedMonthDateColor"></a>android:focusedMonthDateColor

format: 

API level: [API 11](#api_11)

related styles: [CalendarView](#CalendarView)

--

### <a name="android_iconifiedByDefault"></a>android:iconifiedByDefault

format: 

API level: [API 11](#api_11)

related styles: [SearchView](#SearchView)

--

### <a name="android_layerType"></a>android:layerType

format: 

API level: [API 11](#api_11)

related styles: [View](#View)

--

### <a name="android_loopViews"></a>android:loopViews

format: 

API level: [API 11](#api_11)

related styles: [AdapterViewAnimator](#AdapterViewAnimator)

--

### <a name="android_maxDate"></a>android:maxDate

format: 

API level: [API 11](#api_11)

related styles: [DatePicker](#DatePicker), [CalendarView](#CalendarView)

--

### <a name="android_measureWithLargestChild"></a>android:measureWithLargestChild

format: 

API level: [API 11](#api_11)

related styles: [LinearLayout](#LinearLayout)

--

### <a name="android_minDate"></a>android:minDate

format: 

API level: [API 11](#api_11)

related styles: [DatePicker](#DatePicker), [CalendarView](#CalendarView)

--

### <a name="android_nextFocusForward"></a>android:nextFocusForward

format: 

API level: [API 11](#api_11)

related styles: [View](#View)

--

### <a name="android_queryHint"></a>android:queryHint

format: 

API level: [API 11](#api_11)

related styles: [SearchView](#SearchView)

--

### <a name="android_rotation"></a>android:rotation

format: 

API level: [API 11](#api_11)

related styles: [View](#View)

--

### <a name="android_rotationX"></a>android:rotationX

format: 

API level: [API 11](#api_11)

related styles: [View](#View)

--

### <a name="android_rotationY"></a>android:rotationY

format: 

API level: [API 11](#api_11)

related styles: [View](#View)

--

### <a name="android_scaleX"></a>android:scaleX

format: 

API level: [API 11](#api_11)

related styles: [View](#View)

--

### <a name="android_scaleY"></a>android:scaleY

format: 

API level: [API 11](#api_11)

related styles: [View](#View)

--

### <a name="android_selectedDateVerticalBar"></a>android:selectedDateVerticalBar

format: 

API level: [API 11](#api_11)

related styles: [CalendarView](#CalendarView)

--

### <a name="android_selectedWeekBackgroundColor"></a>android:selectedWeekBackgroundColor

format: 

API level: [API 11](#api_11)

related styles: [CalendarView](#CalendarView)

--

### <a name="android_showWeekNumber"></a>android:showWeekNumber

format: 

API level: [API 11](#api_11)

related styles: [CalendarView](#CalendarView)

--

### <a name="android_shownWeekCount"></a>android:shownWeekCount

format: 

API level: [API 11](#api_11)

related styles: [CalendarView](#CalendarView)

--

### <a name="android_spinnerMode"></a>android:spinnerMode

format: 

API level: [API 11](#api_11)

related styles: [Spinner](#Spinner)

--

### <a name="android_spinnersShown"></a>android:spinnersShown

format: 

API level: [API 11](#api_11)

related styles: [DatePicker](#DatePicker)

--

### <a name="android_splitMotionEvents"></a>android:splitMotionEvents

format: 

API level: [API 11](#api_11)

related styles: [ViewGroup](#ViewGroup)

--

### <a name="android_textIsSelectable"></a>android:textIsSelectable

format: 

API level: [API 11](#api_11)

related styles: [TextView](#TextView)

--

### <a name="android_transformPivotX"></a>android:transformPivotX

format: 

API level: [API 11](#api_11)

related styles: [View](#View)

--

### <a name="android_transformPivotY"></a>android:transformPivotY

format: 

API level: [API 11](#api_11)

related styles: [View](#View)

--

### <a name="android_translationX"></a>android:translationX

format: 

API level: [API 11](#api_11)

related styles: [View](#View)

--

### <a name="android_translationY"></a>android:translationY

format: 

API level: [API 11](#api_11)

related styles: [View](#View)

--

### <a name="android_unfocusedMonthDateColor"></a>android:unfocusedMonthDateColor

format: 

API level: [API 11](#api_11)

related styles: [CalendarView](#CalendarView)

--

### <a name="android_weekDayTextAppearance"></a>android:weekDayTextAppearance

format: 

API level: [API 11](#api_11)

related styles: [CalendarView](#CalendarView)

--

### <a name="android_weekNumberColor"></a>android:weekNumberColor

format: 

API level: [API 11](#api_11)

related styles: [CalendarView](#CalendarView)

--

### <a name="android_weekSeparatorLineColor"></a>android:weekSeparatorLineColor

format: 

API level: [API 11](#api_11)

related styles: [CalendarView](#CalendarView)

--

## <a name="api_14"></a>API 14

### Attribute list

* [android:drawableEnd](#android_drawableEnd)
* [android:drawableStart](#android_drawableStart)
* [android:requiresFadingEdge](#android_requiresFadingEdge)
* [android:switchMinWidth](#android_switchMinWidth)
* [android:switchPadding](#android_switchPadding)
* [android:switchTextAppearance](#android_switchTextAppearance)
* [android:textAllCaps](#android_textAllCaps)
* [android:thumbTextPadding](#android_thumbTextPadding)
* [android:track](#android_track)

### <a name="android_drawableEnd"></a>android:drawableEnd

format: 

API level: [API 14](#api_14)

related styles: [TextView](#TextView)

--

### <a name="android_drawableStart"></a>android:drawableStart

format: 

API level: [API 14](#api_14)

related styles: [TextView](#TextView)

--

### <a name="android_requiresFadingEdge"></a>android:requiresFadingEdge

format: 

API level: [API 14](#api_14)

related styles: [View](#View)

--

### <a name="android_switchMinWidth"></a>android:switchMinWidth

format: 

API level: [API 14](#api_14)

related styles: [Switch](#Switch)

--

### <a name="android_switchPadding"></a>android:switchPadding

format: 

API level: [API 14](#api_14)

related styles: [Switch](#Switch)

--

### <a name="android_switchTextAppearance"></a>android:switchTextAppearance

format: 

API level: [API 14](#api_14)

related styles: [Switch](#Switch)

--

### <a name="android_textAllCaps"></a>android:textAllCaps

format: 

API level: [API 14](#api_14)

related styles: [TextView](#TextView)

--

### <a name="android_thumbTextPadding"></a>android:thumbTextPadding

format: 

API level: [API 14](#api_14)

related styles: [Switch](#Switch)

--

### <a name="android_track"></a>android:track

format: 

API level: [API 14](#api_14)

related styles: [Switch](#Switch)

--

## <a name="api_16"></a>API 16

### Attribute list

* [android:fontFamily](#android_fontFamily)
* [android:importantForAccessibility](#android_importantForAccessibility)

### <a name="android_fontFamily"></a>android:fontFamily

format: 

API level: [API 16](#api_16)

related styles: [TextView](#TextView)

--

### <a name="android_importantForAccessibility"></a>android:importantForAccessibility

format: 

API level: [API 16](#api_16)

related styles: [View](#View)

--

## <a name="api_17"></a>API 17

### Attribute list

* [android:layoutDirection](#android_layoutDirection)
* [android:paddingEnd](#android_paddingEnd)
* [android:paddingStart](#android_paddingStart)
* [android:textAlignment](#android_textAlignment)
* [android:textDirection](#android_textDirection)

### <a name="android_layoutDirection"></a>android:layoutDirection

format: 

API level: [API 17](#api_17)

related styles: [View](#View)

--

### <a name="android_paddingEnd"></a>android:paddingEnd

format: 

API level: [API 17](#api_17)

related styles: [View](#View)

--

### <a name="android_paddingStart"></a>android:paddingStart

format: 

API level: [API 17](#api_17)

related styles: [View](#View)

--

### <a name="android_textAlignment"></a>android:textAlignment

format: 

API level: [API 17](#api_17)

related styles: [View](#View)

--

### <a name="android_textDirection"></a>android:textDirection

format: 

API level: [API 17](#api_17)

related styles: [View](#View)

--

## <a name="api_18"></a>API 18

### Attribute list

* [android:childIndicatorEnd](#android_childIndicatorEnd)
* [android:childIndicatorStart](#android_childIndicatorStart)
* [android:indicatorEnd](#android_indicatorEnd)
* [android:indicatorStart](#android_indicatorStart)
* [android:layoutMode](#android_layoutMode)
* [android:mirrorForRtl](#android_mirrorForRtl)

### <a name="android_childIndicatorEnd"></a>android:childIndicatorEnd

format: 

API level: [API 18](#api_18)

related styles: [ExpandableListView](#ExpandableListView)

--

### <a name="android_childIndicatorStart"></a>android:childIndicatorStart

format: 

API level: [API 18](#api_18)

related styles: [ExpandableListView](#ExpandableListView)

--

### <a name="android_indicatorEnd"></a>android:indicatorEnd

format: 

API level: [API 18](#api_18)

related styles: [ExpandableListView](#ExpandableListView)

--

### <a name="android_indicatorStart"></a>android:indicatorStart

format: 

API level: [API 18](#api_18)

related styles: [ExpandableListView](#ExpandableListView)

--

### <a name="android_layoutMode"></a>android:layoutMode

format: 

API level: [API 18](#api_18)

related styles: [ViewGroup](#ViewGroup)

--

### <a name="android_mirrorForRtl"></a>android:mirrorForRtl

format: 

API level: [API 18](#api_18)

related styles: [ProgressBar](#ProgressBar)

--

## <a name="api_19"></a>API 19

### Attribute list

* [android:accessibilityLiveRegion](#android_accessibilityLiveRegion)

### <a name="android_accessibilityLiveRegion"></a>android:accessibilityLiveRegion

format: 

API level: [API 19](#api_19)

related styles: [View](#View)

--

## <a name="api_21"></a>API 21

### Attribute list

* [android:backgroundTint](#android_backgroundTint)
* [android:backgroundTintMode](#android_backgroundTintMode)
* [android:buttonTint](#android_buttonTint)
* [android:buttonTintMode](#android_buttonTintMode)
* [android:calendarTextColor](#android_calendarTextColor)
* [android:checkMarkTint](#android_checkMarkTint)
* [android:checkMarkTintMode](#android_checkMarkTintMode)
* [android:dayOfWeekBackground](#android_dayOfWeekBackground)
* [android:dayOfWeekTextAppearance](#android_dayOfWeekTextAppearance)
* [android:elegantTextHeight](#android_elegantTextHeight)
* [android:elevation](#android_elevation)
* [android:fontFeatureSettings](#android_fontFeatureSettings)
* [android:foregroundTint](#android_foregroundTint)
* [android:foregroundTintMode](#android_foregroundTintMode)
* [android:headerDayOfMonthTextAppearance](#android_headerDayOfMonthTextAppearance)
* [android:headerMonthTextAppearance](#android_headerMonthTextAppearance)
* [android:headerYearTextAppearance](#android_headerYearTextAppearance)
* [android:indeterminateTint](#android_indeterminateTint)
* [android:indeterminateTintMode](#android_indeterminateTintMode)
* [android:letterSpacing](#android_letterSpacing)
* [android:progressBackgroundTint](#android_progressBackgroundTint)
* [android:progressBackgroundTintMode](#android_progressBackgroundTintMode)
* [android:progressTint](#android_progressTint)
* [android:progressTintMode](#android_progressTintMode)
* [android:secondaryProgressTint](#android_secondaryProgressTint)
* [android:secondaryProgressTintMode](#android_secondaryProgressTintMode)
* [android:showText](#android_showText)
* [android:splitTrack](#android_splitTrack)
* [android:stateListAnimator](#android_stateListAnimator)
* [android:tintMode](#android_tintMode)
* [android:transitionName](#android_transitionName)
* [android:translationZ](#android_translationZ)
* [android:yearListItemTextAppearance](#android_yearListItemTextAppearance)
* [android:yearListSelectorColor](#android_yearListSelectorColor)

### <a name="android_backgroundTint"></a>android:backgroundTint

format: 

API level: [API 21](#api_21)

related styles: [View](#View)

--

### <a name="android_backgroundTintMode"></a>android:backgroundTintMode

format: 

API level: [API 21](#api_21)

related styles: [View](#View)

--

### <a name="android_buttonTint"></a>android:buttonTint

format: 

API level: [API 21](#api_21)

related styles: [CompoundButton](#CompoundButton)

--

### <a name="android_buttonTintMode"></a>android:buttonTintMode

format: 

API level: [API 21](#api_21)

related styles: [CompoundButton](#CompoundButton)

--

### <a name="android_calendarTextColor"></a>android:calendarTextColor

format: 

API level: [API 21](#api_21)

related styles: [DatePicker](#DatePicker)

--

### <a name="android_checkMarkTint"></a>android:checkMarkTint

format: 

API level: [API 21](#api_21)

related styles: [CheckedTextView](#CheckedTextView)

--

### <a name="android_checkMarkTintMode"></a>android:checkMarkTintMode

format: 

API level: [API 21](#api_21)

related styles: [CheckedTextView](#CheckedTextView)

--

### <a name="android_dayOfWeekBackground"></a>android:dayOfWeekBackground

format: 

API level: [API 21](#api_21)

related styles: [DatePicker](#DatePicker)

--

### <a name="android_dayOfWeekTextAppearance"></a>android:dayOfWeekTextAppearance

format: 

API level: [API 21](#api_21)

related styles: [DatePicker](#DatePicker)

--

### <a name="android_elegantTextHeight"></a>android:elegantTextHeight

format: 

API level: [API 21](#api_21)

related styles: [TextView](#TextView)

--

### <a name="android_elevation"></a>android:elevation

format: 

API level: [API 21](#api_21)

related styles: [View](#View)

--

### <a name="android_fontFeatureSettings"></a>android:fontFeatureSettings

format: 

API level: [API 21](#api_21)

related styles: [TextView](#TextView)

--

### <a name="android_foregroundTint"></a>android:foregroundTint

format: 

API level: [API 21](#api_21)

related styles: [FrameLayout](#FrameLayout)

--

### <a name="android_foregroundTintMode"></a>android:foregroundTintMode

format: 

API level: [API 21](#api_21)

related styles: [FrameLayout](#FrameLayout)

--

### <a name="android_headerDayOfMonthTextAppearance"></a>android:headerDayOfMonthTextAppearance

format: 

API level: [API 21](#api_21)

related styles: [DatePicker](#DatePicker)

--

### <a name="android_headerMonthTextAppearance"></a>android:headerMonthTextAppearance

format: 

API level: [API 21](#api_21)

related styles: [DatePicker](#DatePicker)

--

### <a name="android_headerYearTextAppearance"></a>android:headerYearTextAppearance

format: 

API level: [API 21](#api_21)

related styles: [DatePicker](#DatePicker)

--

### <a name="android_indeterminateTint"></a>android:indeterminateTint

format: 

API level: [API 21](#api_21)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_indeterminateTintMode"></a>android:indeterminateTintMode

format: 

API level: [API 21](#api_21)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_letterSpacing"></a>android:letterSpacing

format: 

API level: [API 21](#api_21)

related styles: [TextView](#TextView)

--

### <a name="android_progressBackgroundTint"></a>android:progressBackgroundTint

format: 

API level: [API 21](#api_21)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_progressBackgroundTintMode"></a>android:progressBackgroundTintMode

format: 

API level: [API 21](#api_21)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_progressTint"></a>android:progressTint

format: 

API level: [API 21](#api_21)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_progressTintMode"></a>android:progressTintMode

format: 

API level: [API 21](#api_21)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_secondaryProgressTint"></a>android:secondaryProgressTint

format: 

API level: [API 21](#api_21)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_secondaryProgressTintMode"></a>android:secondaryProgressTintMode

format: 

API level: [API 21](#api_21)

related styles: [ProgressBar](#ProgressBar)

--

### <a name="android_showText"></a>android:showText

format: 

API level: [API 21](#api_21)

related styles: [Switch](#Switch)

--

### <a name="android_splitTrack"></a>android:splitTrack

format: 

API level: [API 21](#api_21)

related styles: [Switch](#Switch)

--

### <a name="android_stateListAnimator"></a>android:stateListAnimator

format: 

API level: [API 21](#api_21)

related styles: [View](#View)

--

### <a name="android_tintMode"></a>android:tintMode

format: 

API level: [API 21](#api_21)

related styles: [ImageView](#ImageView)

--

### <a name="android_transitionName"></a>android:transitionName

format: 

API level: [API 21](#api_21)

related styles: [View](#View)

--

### <a name="android_translationZ"></a>android:translationZ

format: 

API level: [API 21](#api_21)

related styles: [View](#View)

--

### <a name="android_yearListItemTextAppearance"></a>android:yearListItemTextAppearance

format: 

API level: [API 21](#api_21)

related styles: [DatePicker](#DatePicker)

--

### <a name="android_yearListSelectorColor"></a>android:yearListSelectorColor

format: 

API level: [API 21](#api_21)

related styles: [DatePicker](#DatePicker)

--
