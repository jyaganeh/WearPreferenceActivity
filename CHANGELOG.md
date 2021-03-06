# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## 0.5.0 - 2015-09-30
- Now parses preference resource files (in `res/xml`), rather than layout resource files (in `res/layout`).
    - Preferences xml files can now be reused between mobile and wearable apps.
    - Attributes specific to wearable apps now use a `wear_` prefix
- Added support for nested `PreferenceScreen` tags in preferences xml files
- An array of icons can now be specified for `ListPreference` corresponding to specific icons for each list item.
- Design changes to resemble Android Wear system settings pages

## 0.4.0 - 2015-03-25
- Added Setter methods for `ListItemLayout`, to adjust the circle colours/radii after creation
- Summary text is now smaller than the title text

## 0.3.1 - 2015-03-06
- Added `pref_icon_circle_color_selected` attribute to `ListItemLayout`

## 0.3.0 - 2015-03-05
- All attribute names now start with `pref_` to avoid conflicting with other libraries

## 0.2.0 - 2015-03-03
- `ListItemLayout` is now reusable in other lists, by specifying a layout resource to inflate.

## 0.1.0 - 2015-02-26
- Initial release (unstable)