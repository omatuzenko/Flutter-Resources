Flutter / Android / iOS corresponding widgets

## Table Of Contents
- [Basic widgets](#basic-widgets)
- [Compound widgets](#compound-widgets)
- [Containers](#containers)

## Basic widgets

| Flutter | Android  | iOS |
|:--------:|:--------:|:--------:|
| [Text](https://docs.flutter.io/flutter/widgets/Text-class.html) | [TextView](https://developer.android.com/reference/android/widget/TextView) | [UILabel](https://developer.apple.com/documentation/uikit/uilabel) |
| [TextField](https://docs.flutter.io/flutter/material/TextField-class.html) | [EditText](https://developer.android.com/reference/android/widget/EditText) | [UITextField](https://developer.apple.com/documentation/uikit/uitextfield) |
| [RaisedButton](https://docs.flutter.io/flutter/material/RaisedButton-class.html) | [Button](https://developer.android.com/reference/android/widget/Button.html) | [Button](https://developer.apple.com/documentation/uikit/uibutton)
| [FlatButton](https://docs.flutter.io/flutter/material/FlatButton-class.html) | [BorderlessButton](https://developer.android.com/guide/topics/ui/controls/button#Borderless) | ? |
| [Checkbox](https://docs.flutter.io/flutter/material/Checkbox-class.html) | [CheckBox](https://developer.android.com/reference/android/widget/CheckBox) | ? |
| [RaisedButton](https://docs.flutter.io/flutter/material/RaisedButton-class.html)/[FlatButton](https://docs.flutter.io/flutter/material/FlatButton-class.html) | [ImageButton](https://developer.android.com/reference/android/widget/ImageButton) | ? |
| [Image](https://docs.flutter.io/flutter/widgets/Image-class.html) | [ImageView](https://developer.android.com/reference/android/widget/ImageView) | [UIImageView](https://developer.apple.com/documentation/uikit/UIImageView) |
| [Switch](https://docs.flutter.io/flutter/material/Switch-class.html) | [Switch](https://developer.android.com/reference/android/widget/Switch) | [UISwitch](https://developer.apple.com/documentation/uikit/UISwitch) |

## Compound widgets
| Flutter | Android  | iOS |
|:--------:|:--------:|:--------:|
| [Slider](https://docs.flutter.io/flutter/material/Slider-class.html) | [SeekBar](https://developer.android.com/reference/android/widget/SeekBar) | [UISlider](https://developer.apple.com/documentation/uikit/UISlider) |
| [LinearProgressIndicator](https://docs.flutter.io/flutter/material/LinearProgressIndicator-class.html) | [ProgressBar](https://developer.android.com/reference/android/widget/ProgressBar) | [UIProgressView](https://developer.apple.com/documentation/uikit/UIProgressView), [UIActivityIndicatorView](https://developer.apple.com/documentation/uikit/UIActivityIndicatorView)
| [Radio](https://docs.flutter.io/flutter/material/Radio-class.html) | [RadioButton](https://docs.flutter.io/flutter/material/Radio-class.html)/[RadioGroup](https://developer.android.com/reference/android/widget/RadioGroup) | [UISegmentedControl](https://developer.apple.com/documentation/uikit/UISegmentedControl) |


## Containers

| Flutter | Android  | iOS |
|:--------:|:--------:|:--------:|
| [DropDownButton](https://docs.flutter.io/flutter/material/DropdownButton-class.html) | [Spinner](https://developer.android.com/reference/android/widget/Spinner) | [UIPickerView](https://developer.apple.com/documentation/uikit/UIPickerView) |
| [BottomNavigationBar](https://docs.flutter.io/flutter/material/BottomNavigationBar-class.html) | [BottomNavigationView](https://developer.android.com/reference/android/support/design/widget/BottomNavigationView) | [UIToolbar](https://developer.apple.com/documentation/uikit/uitoolbar) |
| [fluttertoast](https://pub.dartlang.org/packages/fluttertoast) | [Toast](https://developer.android.com/reference/android/widget/Toast) | - |
| [ListView](https://docs.flutter.io/flutter/widgets/ListView-class.html) + [ExpansionTile](https://flutter.io/docs/catalog/samples/expansion-tile-sample) | [ExpandableListView](https://developer.android.com/reference/android/widget/ExpandableListView) | - |
| ? | [CalendarView](https://developer.android.com/reference/android/widget/CalendarView) | ? 
| [DatePicker](https://developer.android.com/reference/android/widget/DatePicker) | [showDatePicker](https://docs.flutter.io/flutter/material/showDatePicker.html) | ? |
| [Stack](https://docs.flutter.io/flutter/widgets/Stack-class.html) | [FrameLayout](https://developer.android.com/reference/android/widget/FrameLayout) | ? |
| [GridView](https://docs.flutter.io/flutter/widgets/GridView-class.html) | [GridView](https://developer.android.com/guide/topics/ui/layout/gridview) | ? |
|[HorizontalScrollView](https://developer.android.com/reference/android/widget/HorizontalScrollView) | [ListView](https://flutter.io/docs/cookbook/lists/horizontal-list) | ? |
|[LinearLayout](https://developer.android.com/reference/android/widget/LinearLayout) | [Column](https://docs.flutter.io/flutter/widgets/Column-class.html)/[Row](https://docs.flutter.io/flutter/widgets/Row-class.html) | ? |
|[ListView](https://developer.android.com/reference/android/widget/ListView) | [ListView](https://docs.flutter.io/flutter/widgets/ListView-class.html) | ? |
|[NumberPicker](https://developer.android.com/reference/android/widget/NumberPicker) | [Custom Widget](https://pub.dartlang.org/packages/numberpicker) | ? |
|[PopupMenu](https://developer.android.com/reference/android/widget/PopupMenu)| [PopupMenuButton](https://docs.flutter.io/flutter/material/PopupMenuButton-class.html) | ? |
|[PopupView](https://developer.android.com/reference/android/widget/PopupWindow) | [PopupMenuButton](https://docs.flutter.io/flutter/material/PopupMenuButton-class.html) | ? |
|[RatingBar](https://developer.android.com/reference/android/widget/RatingBar) | [How to create rating bar](https://stackoverflow.com/questions/46637566/how-to-create-rating-star-bar-properly) | ? |
|[RelativeLayout](https://developer.android.com/reference/android/widget/RelativeLayout) | ? |
|[ScrollView](https://developer.android.com/reference/android/widget/ScrollView) | [ListView](https://docs.flutter.io/flutter/widgets/ListView-class.html) | ? |
|[TableLayout](https://developer.android.com/reference/android/widget/TableLayout) | [Table](https://docs.flutter.io/flutter/widgets/Table-class.html) | ? |
|[TimePicker](https://developer.android.com/reference/android/widget/TimePicker) | [showDatePicker](https://docs.flutter.io/flutter/material/showDatePicker.html) | ? |
[Toolbar](https://developer.android.com/reference/android/widget/Toolbar) | [AppBar](https://docs.flutter.io/flutter/material/AppBar-class.html) | ? |
[RecyclerView](https://developer.android.com/reference/android/support/v7/widget/RecyclerView.html) | [ListView with ListView.builder()](https://docs.flutter.io/flutter/widgets/ListView-class.html) | ? |
[ViewPager](https://developer.android.com/reference/android/support/v4/view/ViewPager) | [PageView](https://docs.flutter.io/flutter/widgets/PageView-class.html)([Tutorial](https://iirokrankka.com/2017/09/23/bringing-the-pagetransformer-from-android-to-flutter/)) | ? |
[SwipeRefreshLayout](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout) | [RefreshIndicator](https://docs.flutter.io/flutter/material/RefreshIndicator-class.html)([Tutorial](https://medium.com/flutterpub/adding-swipe-to-refresh-to-flutter-app-b234534f39a7)) | ? |
[CardView](https://docs.flutter.io/flutter/material/Card-class.html) | [Card](https://docs.flutter.io/flutter/material/Card-class.html) | ? |
[ConstraintLayout](https://developer.android.com/reference/android/support/constraint/ConstraintLayout) | ? |
[CoordinatorLayout](https://developer.android.com/reference/android/support/design/widget/CoordinatorLayout) | [Scaffold](https://docs.flutter.io/flutter/material/Scaffold-class.html) | ? |
[AppBarLayout](https://developer.android.com/reference/android/support/design/widget/AppBarLayout) | [AppBar](https://docs.flutter.io/flutter/material/Scaffold-class.html) within [Scaffold](https://docs.flutter.io/flutter/material/AppBar-class.html) | ? |
[ExpandableWidget](https://developer.android.com/reference/com/google/android/material/expandable/ExpandableWidget) | [ExpansionTile](https://flutter.io/docs/catalog/samples/expansion-tile-sample) | ? |
[FloatingActionButton](https://developer.android.com/guide/topics/ui/floating-action-button) | [FloatingActionButton](https://docs.flutter.io/flutter/material/Scaffold-class.html) within [Scaffold](https://docs.flutter.io/flutter/material/FloatingActionButton-class.html) | ? |
[DrawerLayout](https://developer.android.com/reference/android/support/v4/widget/DrawerLayout) | [Drawer](https://docs.flutter.io/flutter/material/Scaffold-class.html) within [Scaffold](https://docs.flutter.io/flutter/material/Drawer-class.html) | ? |
[TabLayout](https://developer.android.com/reference/android/support/design/widget/TabLayout.html) | [TabBar](https://docs.flutter.io/flutter/material/TabBar-class.html) in conjunction with [TabBarView](https://docs.flutter.io/flutter/material/TabBarView-class.html) | ? |
[TextInputLayout](https://developer.android.com/reference/com/google/android/material/textfield/package-summary) | [TextFormFiled](https://docs.flutter.io/flutter/material/TextFormField-class.html) | ? |
[SnackBar](https://developer.android.com/reference/android/support/design/widget/Snackbar) | [SnackBar](https://docs.flutter.io/flutter/material/SnackBar-class.html) | ? |
