Flutter / Android / iOS corresponding widgets

## Table Of Contents
- [Basic widgets](#basic-widgets)
- [Scrolling widgets](#scrolling-widgets)
- [Compound widgets](#compound-widgets)
- [Navigation](#navigation)
- [Containers](#containers)
- [Alerts](#alerts)

## Basic widgets

| Flutter | Android  | iOS |
|:--------:|:--------:|:--------:|
| [Text](https://docs.flutter.io/flutter/widgets/Text-class.html) | [TextView](https://developer.android.com/reference/android/widget/TextView) | [UILabel](https://developer.apple.com/documentation/uikit/uilabel) |
| [TextField](https://docs.flutter.io/flutter/material/TextField-class.html) | [EditText](https://developer.android.com/reference/android/widget/EditText) | [UITextField](https://developer.apple.com/documentation/uikit/uitextfield) |
| [Checkbox](https://docs.flutter.io/flutter/material/Checkbox-class.html) | [CheckBox](https://developer.android.com/reference/android/widget/CheckBox) | [UISwitch](https://developer.apple.com/documentation/uikit/UISwitch) |
| [RaisedButton](https://docs.flutter.io/flutter/material/RaisedButton-class.html), [FlatButton](https://docs.flutter.io/flutter/material/FlatButton-class.html), [MaterialButton](https://docs.flutter.io/flutter/material/MaterialButton-class.html) | [Button](https://developer.android.com/reference/android/widget/Button.html) | [Button](https://developer.apple.com/documentation/uikit/uibutton) |
| [Image](https://docs.flutter.io/flutter/widgets/Image-class.html) | [ImageView](https://developer.android.com/reference/android/widget/ImageView) | [UIImageView](https://developer.apple.com/documentation/uikit/UIImageView) |
| [Switch](https://docs.flutter.io/flutter/material/Switch-class.html) | [Switch](https://developer.android.com/reference/android/widget/Switch) | [UISwitch](https://developer.apple.com/documentation/uikit/UISwitch) |
| [TextFormFiled](https://docs.flutter.io/flutter/material/TextFormField-class.html) | [TextInputLayout](https://developer.android.com/reference/com/google/android/material/textfield/package-summary) | N/A |
| [Chip](https://docs.flutter.io/flutter/material/Chip-class.html) | [Chip](https://developer.android.com/reference/com/google/android/material/chip/Chip) | N/A |

## Scrolling widgets
| Flutter | Android  | iOS |
|:--------:|:--------:|:--------:|
| [ListView](https://docs.flutter.io/flutter/widgets/ListView-class.html) | [ListView](https://developer.android.com/reference/android/widget/ListView), [RecyclerView](https://developer.android.com/reference/android/support/v7/widget/RecyclerView.html) | [UITableView](https://developer.apple.com/documentation/uikit/uitableview) |
| [ListView](https://docs.flutter.io/flutter/widgets/ListView-class.html) with [ExpansionTile](https://flutter.io/docs/catalog/samples/expansion-tile-sample) | [ExpandableListView](https://developer.android.com/reference/android/widget/ExpandableListView) | [UITableView](https://developer.apple.com/documentation/uikit/uitableview) |
| [ListView](https://docs.flutter.io/flutter/widgets/ListView-class.html) | [ScrollView](https://developer.android.com/reference/android/widget/ScrollView), [HorizontalScrollView](https://developer.android.com/reference/android/widget/HorizontalScrollView) | [UIScrollView](https://developer.apple.com/documentation/uikit/uiscrollview) |
| [PageView](https://docs.flutter.io/flutter/widgets/PageView-class.html) | [ViewPager](https://developer.android.com/reference/android/support/v4/view/ViewPager) | [UIPageViewController](https://developer.apple.com/documentation/uikit/uipageviewcontroller) |

## Compound widgets
| Flutter | Android  | iOS |
|:--------:|:--------:|:--------:|
| [Slider](https://docs.flutter.io/flutter/material/Slider-class.html) | [SeekBar](https://developer.android.com/reference/android/widget/SeekBar) | [UISlider](https://developer.apple.com/documentation/uikit/UISlider) |
| [LinearProgressIndicator](https://docs.flutter.io/flutter/material/LinearProgressIndicator-class.html) | [ProgressBar](https://developer.android.com/reference/android/widget/ProgressBar) | [UIProgressView](https://developer.apple.com/documentation/uikit/UIProgressView), [UIActivityIndicatorView](https://developer.apple.com/documentation/uikit/UIActivityIndicatorView)
| [Radio](https://docs.flutter.io/flutter/material/Radio-class.html) | [RadioButton](https://docs.flutter.io/flutter/material/Radio-class.html), [RadioGroup](https://developer.android.com/reference/android/widget/RadioGroup) | [UISegmentedControl](https://developer.apple.com/documentation/uikit/UISegmentedControl) |
| [How to create rating bar](https://stackoverflow.com/questions/46637566/how-to-create-rating-star-bar-properly) | [RatingBar](https://developer.android.com/reference/android/widget/RatingBar) | N/A |
| [showDatePicker](https://docs.flutter.io/flutter/material/showDatePicker.html) | [TimePicker](https://developer.android.com/reference/android/widget/TimePicker), [DatePicker](https://developer.android.com/reference/android/widget/DatePicker). [CalendarView]([CalendarView](https://developer.android.com/reference/android/widget/CalendarView)) | [UIDatePicker](https://developer.apple.com/documentation/uikit/uidatepicker) |
| [Custom Widget](https://pub.dartlang.org/packages/numberpicker) | [NumberPicker](https://developer.android.com/reference/android/widget/NumberPicker) | [UIPickerView](https://developer.apple.com/documentation/uikit/uipickerview) |
| [DropDownButton](https://docs.flutter.io/flutter/material/DropdownButton-class.html) | [Spinner](https://developer.android.com/reference/android/widget/Spinner) | [UIPickerView](https://developer.apple.com/documentation/uikit/UIPickerView) |
| [ExpansionTile](https://flutter.io/docs/catalog/samples/expansion-tile-sample) | [ExpandableWidget](https://developer.android.com/reference/com/google/android/material/expandable/ExpandableWidget) | N/A |

## Navigation
| Flutter | Android  | iOS |
|:--------:|:--------:|:--------:|
| [AppBar](https://docs.flutter.io/flutter/material/AppBar-class.html) | [Toolbar](https://developer.android.com/reference/android/widget/Toolbar), [AppBarLayout](https://developer.android.com/reference/android/support/design/widget/AppBarLayout) | [UIToolbar](https://developer.apple.com/documentation/uikit/uitoolbar) |
| [BottomNavigationBar](https://docs.flutter.io/flutter/material/BottomNavigationBar-class.html) | [BottomNavigationView](https://developer.android.com/reference/android/support/design/widget/BottomNavigationView) | [UITabbar](https://developer.apple.com/documentation/uikit/uitabbar) |
| [FloatingActionButton](https://docs.flutter.io/flutter/material/Scaffold-class.html) in [Scaffold](https://docs.flutter.io/flutter/material/FloatingActionButton-class.html) | [FloatingActionButton](https://developer.android.com/guide/topics/ui/floating-action-button) | N/A |
| [Drawer](https://docs.flutter.io/flutter/material/Scaffold-class.html) within [Scaffold](https://docs.flutter.io/flutter/material/Drawer-class.html) | [DrawerLayout](https://developer.android.com/reference/android/support/v4/widget/DrawerLayout) | N/A, [3d party libs](https://github.com/vsouza/awesome-ios#navigation-bar) |
| [TabBar](https://docs.flutter.io/flutter/material/TabBar-class.html) with [TabBarView](https://docs.flutter.io/flutter/material/TabBarView-class.html) | [TabLayout](https://developer.android.com/reference/android/support/design/widget/TabLayout.html) | N/A, [UISegmentedControl](https://developer.apple.com/documentation/uikit/uisegmentedcontrol) |

## Containers
| Flutter | Android  | iOS |
|:--------:|:--------:|:--------:|
| [Row](https://docs.flutter.io/flutter/widgets/Row-class.html), [Column](https://docs.flutter.io/flutter/widgets/Column-class.html) | [LinearLayout](https://developer.android.com/reference/android/widget/LinearLayout) | | [UIStackView](https://developer.apple.com/documentation/uikit/uistackview) |
| N/A | [RelativeLayout](https://developer.android.com/reference/android/widget/RelativeLayout), ConstraintLayout](https://developer.android.com/reference/android/support/constraint/ConstraintLayout) | [Auto Layout](https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/AutolayoutPG/index.html) |
| [Table](https://docs.flutter.io/flutter/widgets/Table-class.html) | [TableLayout](https://developer.android.com/reference/android/widget/TableLayout) | [UITableViewCell](https://developer.apple.com/documentation/uikit/UITableViewCell) |
| [GridView](https://docs.flutter.io/flutter/widgets/GridView-class.html) | [GridView](https://developer.android.com/guide/topics/ui/layout/gridview) | [UIColectionView](https://developer.apple.com/documentation/uikit/uicollectionview) |
| [RefreshIndicator](https://docs.flutter.io/flutter/material/RefreshIndicator-class.html)[SwipeRefreshLayout](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout) | [UIRefreshControl](https://developer.apple.com/documentation/uikit/UIRefreshControl) |
| [Scaffold](https://docs.flutter.io/flutter/material/Scaffold-class.html) | [CoordinatorLayout](https://developer.android.com/reference/android/support/design/widget/CoordinatorLayout) | [Auto Layout](https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/AutolayoutPG/index.html) |
| [Card](https://docs.flutter.io/flutter/material/Card-class.html) | [CardView](https://docs.flutter.io/flutter/material/Card-class.html) | N/A |
| [Stack](https://docs.flutter.io/flutter/widgets/Stack-class.html) | [FrameLayout](https://developer.android.com/reference/android/widget/FrameLayout) | [UIStackView](https://developer.apple.com/documentation/uikit/uistackview) |

## Alerts
| Flutter | Android  | iOS |
|:--------:|:--------:|:--------:|
| [fluttertoast](https://pub.dartlang.org/packages/fluttertoast) | [Toast](https://developer.android.com/reference/android/widget/Toast) | N/A |
| [SnackBar](https://docs.flutter.io/flutter/material/SnackBar-class.html) | [SnackBar](https://developer.android.com/reference/android/support/design/widget/Snackbar) | N/A |
| [PopupMenuButton](https://docs.flutter.io/flutter/material/PopupMenuButton-class.html) | [PopupMenu](https://developer.android.com/reference/android/widget/PopupMenu), [PopupView](https://developer.android.com/reference/android/widget/PopupWindow) | N/A |
