Flutter / Android / iOS corresponding widgets

## Table Of Contents
- [Basic widgets](#basic-widgets)
- [Compound widgets](#compound-widgets)
- [Scrolling widgets](#scrolling-widgets)
- [Containers](#containers)

## Basic widgets

| Flutter | Android  | iOS |
|:--------:|:--------:|:--------:|
| [Text](https://docs.flutter.io/flutter/widgets/Text-class.html) | [TextView](https://developer.android.com/reference/android/widget/TextView) | [UILabel](https://developer.apple.com/documentation/uikit/uilabel) |
| [TextField](https://docs.flutter.io/flutter/material/TextField-class.html) | [EditText](https://developer.android.com/reference/android/widget/EditText) | [UITextField](https://developer.apple.com/documentation/uikit/uitextfield) |
| [Checkbox](https://docs.flutter.io/flutter/material/Checkbox-class.html) | [CheckBox](https://developer.android.com/reference/android/widget/CheckBox) | ? |
| [RaisedButton](https://docs.flutter.io/flutter/material/RaisedButton-class.html), [FlatButton](https://docs.flutter.io/flutter/material/FlatButton-class.html), [MaterialButton](https://docs.flutter.io/flutter/material/MaterialButton-class.html) | [Button](https://developer.android.com/reference/android/widget/Button.html) | [Button](https://developer.apple.com/documentation/uikit/uibutton) |
| [Image](https://docs.flutter.io/flutter/widgets/Image-class.html) | [ImageView](https://developer.android.com/reference/android/widget/ImageView) | [UIImageView](https://developer.apple.com/documentation/uikit/UIImageView) |
| [Switch](https://docs.flutter.io/flutter/material/Switch-class.html) | [Switch](https://developer.android.com/reference/android/widget/Switch) | [UISwitch](https://developer.apple.com/documentation/uikit/UISwitch) |

## Scrolling widgets
| Flutter | Android  | iOS |
|:--------:|:--------:|:--------:|
| [ListView](https://docs.flutter.io/flutter/widgets/ListView-class.html) | [ListView](https://developer.android.com/reference/android/widget/ListView), [RecyclerView](https://developer.android.com/reference/android/support/v7/widget/RecyclerView.html) | [UITableView](https://developer.apple.com/documentation/uikit/uitableview) |
| [ListView](https://docs.flutter.io/flutter/widgets/ListView-class.html) | [ScrollView](https://developer.android.com/reference/android/widget/ScrollView), [HorizontalScrollView](https://developer.android.com/reference/android/widget/HorizontalScrollView) | [UIScrollView](https://developer.apple.com/documentation/uikit/uiscrollview) |

## Compound widgets
| Flutter | Android  | iOS |
|:--------:|:--------:|:--------:|
| [Slider](https://docs.flutter.io/flutter/material/Slider-class.html) | [SeekBar](https://developer.android.com/reference/android/widget/SeekBar) | [UISlider](https://developer.apple.com/documentation/uikit/UISlider) |
| [LinearProgressIndicator](https://docs.flutter.io/flutter/material/LinearProgressIndicator-class.html) | [ProgressBar](https://developer.android.com/reference/android/widget/ProgressBar) | [UIProgressView](https://developer.apple.com/documentation/uikit/UIProgressView), [UIActivityIndicatorView](https://developer.apple.com/documentation/uikit/UIActivityIndicatorView)
| [Radio](https://docs.flutter.io/flutter/material/Radio-class.html) | [RadioButton](https://docs.flutter.io/flutter/material/Radio-class.html), [RadioGroup](https://developer.android.com/reference/android/widget/RadioGroup) | [UISegmentedControl](https://developer.apple.com/documentation/uikit/UISegmentedControl) |
| [How to create rating bar](https://stackoverflow.com/questions/46637566/how-to-create-rating-star-bar-properly) | [RatingBar](https://developer.android.com/reference/android/widget/RatingBar) | N/A |
| [showDatePicker](https://docs.flutter.io/flutter/material/showDatePicker.html) | [TimePicker](https://developer.android.com/reference/android/widget/TimePicker), [DatePicker](https://developer.android.com/reference/android/widget/DatePicker) | [UIDatePicker](https://developer.apple.com/documentation/uikit/uidatepicker) |

## Navigation
| Flutter | Android  | iOS |
|:--------:|:--------:|:--------:|
| [AppBar](https://docs.flutter.io/flutter/material/AppBar-class.html) | [Toolbar](https://developer.android.com/reference/android/widget/Toolbar), [AppBarLayout](https://developer.android.com/reference/android/support/design/widget/AppBarLayout) | [UIToolbar](https://developer.apple.com/documentation/uikit/uitoolbar) |
| [BottomNavigationBar](https://docs.flutter.io/flutter/material/BottomNavigationBar-class.html) | [BottomNavigationView](https://developer.android.com/reference/android/support/design/widget/BottomNavigationView) | [UITabbar](https://developer.apple.com/documentation/uikit/uitabbar) |
| [FloatingActionButton](https://docs.flutter.io/flutter/material/Scaffold-class.html) in [Scaffold](https://docs.flutter.io/flutter/material/FloatingActionButton-class.html) | [FloatingActionButton](https://developer.android.com/guide/topics/ui/floating-action-button) | N/A |

## Containers
| Flutter | Android  | iOS |
|:--------:|:--------:|:--------:|
| [Row](https://docs.flutter.io/flutter/widgets/Row-class.html), [Column](https://docs.flutter.io/flutter/widgets/Column-class.html) | [LinearLayout](https://developer.android.com/reference/android/widget/LinearLayout) | | [UIStackView](https://developer.apple.com/documentation/uikit/uistackview) |
|[RelativeLayout](https://developer.android.com/reference/android/widget/RelativeLayout) | ? |
|[TableLayout](https://developer.android.com/reference/android/widget/TableLayout) | [Table](https://docs.flutter.io/flutter/widgets/Table-class.html) | ? |
| [GridView](https://docs.flutter.io/flutter/widgets/GridView-class.html) | [GridView](https://developer.android.com/guide/topics/ui/layout/gridview) | ? |
[SwipeRefreshLayout](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout) | [RefreshIndicator](https://docs.flutter.io/flutter/material/RefreshIndicator-class.html)([Tutorial](https://medium.com/flutterpub/adding-swipe-to-refresh-to-flutter-app-b234534f39a7)) | ? |
[CoordinatorLayout](https://developer.android.com/reference/android/support/design/widget/CoordinatorLayout) | [Scaffold](https://docs.flutter.io/flutter/material/Scaffold-class.html) | ? |


| Flutter | Android  | iOS |
|:--------:|:--------:|:--------:|
| [DropDownButton](https://docs.flutter.io/flutter/material/DropdownButton-class.html) | [Spinner](https://developer.android.com/reference/android/widget/Spinner) | [UIPickerView](https://developer.apple.com/documentation/uikit/UIPickerView) |
| [fluttertoast](https://pub.dartlang.org/packages/fluttertoast) | [Toast](https://developer.android.com/reference/android/widget/Toast) | N/A |
| [ListView](https://docs.flutter.io/flutter/widgets/ListView-class.html) + [ExpansionTile](https://flutter.io/docs/catalog/samples/expansion-tile-sample) | [ExpandableListView](https://developer.android.com/reference/android/widget/ExpandableListView) | - |
| ? | [CalendarView](https://developer.android.com/reference/android/widget/CalendarView) | ? 
| [Stack](https://docs.flutter.io/flutter/widgets/Stack-class.html) | [FrameLayout](https://developer.android.com/reference/android/widget/FrameLayout) | ? |
|[NumberPicker](https://developer.android.com/reference/android/widget/NumberPicker) | [Custom Widget](https://pub.dartlang.org/packages/numberpicker) | ? |
|[PopupMenu](https://developer.android.com/reference/android/widget/PopupMenu)| [PopupMenuButton](https://docs.flutter.io/flutter/material/PopupMenuButton-class.html) | ? |
|[PopupView](https://developer.android.com/reference/android/widget/PopupWindow) | [PopupMenuButton](https://docs.flutter.io/flutter/material/PopupMenuButton-class.html) | ? |
[ViewPager](https://developer.android.com/reference/android/support/v4/view/ViewPager) | [PageView](https://docs.flutter.io/flutter/widgets/PageView-class.html)([Tutorial](https://iirokrankka.com/2017/09/23/bringing-the-pagetransformer-from-android-to-flutter/)) | ? |
[CardView](https://docs.flutter.io/flutter/material/Card-class.html) | [Card](https://docs.flutter.io/flutter/material/Card-class.html) | ? |
[ConstraintLayout](https://developer.android.com/reference/android/support/constraint/ConstraintLayout) | ? |
[ExpandableWidget](https://developer.android.com/reference/com/google/android/material/expandable/ExpandableWidget) | [ExpansionTile](https://flutter.io/docs/catalog/samples/expansion-tile-sample) | ? |
[DrawerLayout](https://developer.android.com/reference/android/support/v4/widget/DrawerLayout) | [Drawer](https://docs.flutter.io/flutter/material/Scaffold-class.html) within [Scaffold](https://docs.flutter.io/flutter/material/Drawer-class.html) | ? |
[TabLayout](https://developer.android.com/reference/android/support/design/widget/TabLayout.html) | [TabBar](https://docs.flutter.io/flutter/material/TabBar-class.html) in conjunction with [TabBarView](https://docs.flutter.io/flutter/material/TabBarView-class.html) | ? |
[TextInputLayout](https://developer.android.com/reference/com/google/android/material/textfield/package-summary) | [TextFormFiled](https://docs.flutter.io/flutter/material/TextFormField-class.html) | ? |
[SnackBar](https://developer.android.com/reference/android/support/design/widget/Snackbar) | [SnackBar](https://docs.flutter.io/flutter/material/SnackBar-class.html) | ? |
