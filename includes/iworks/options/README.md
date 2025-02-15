WordPress Options Class
=======================

Options Class for WordPress plugins &amp; themes

Changelog
---------

##### 2.8.0 (2022-01-21)
* Update `image` field to new WP Media API.

##### 2.7.3 (2022-01-18)
* Added maxlenght param to text field.
* Fixed data get for older plugins.
* Added two debug values to better debuging.

##### 2.7.2 (2021-12-30)
* Unify data get - it missed dynamic added options.

##### 2.7.1 (2021-08-16)
* Added check for assets enqueue to avoid unnecessary loads.

##### 2.7.0 (2021-06-24)
* Updated jQuery-UI.
* Shorted ui-slide select to max 150px.
* Added missing icons for datepicker.

##### 2.6.9 (2021-04-29)
* Fixed remove default value from database.
* Added `flush_rewrite_rules` to configuration.
* Added field type `button`.

##### 2.6.8 (2019-11-07)
* Implemented `checked()` function.

##### 2.6.7 (2019-11-07)
* Implemented WordPress PSR.
* Added options to money field.
* Added few checks to avoid wrong key warning.
* Added field type `location`.

##### 2.6.6 (2018-09-24)
* Added CSS for tabs.

##### 2.6.5 (2018-03-15)

* Added 'before' and 'after' strings for input() function.
* Added check for `select()` function. Now we can use array or string as value.
* Added methods: number, button, submit and hidden to allow create those form elements.
* Allow using simple array for radio options.
* Handle "theme" mode to fix assets URL.

##### 2.6.4 (2017-12-22)

* Added ability to produce `hidden` name, prefixed by underscore.
* Fixed prolblem with warning. Props for [Michał](https://wordpress.org/support/users/lupinek/)
* Handle `checkbox`, and `switch_button` fields.
* Improved submenu building.

##### 2.6.3 (2017-10-09)

* Added $option['options'] sanitization.

##### 2.6.2 (2017-05-23)

* Fixed a problem with classes for textarea tag.

##### 2.6.1 (2017-05-20)

* Fixed problem with jQuery UI slider, there was 100 as default for min value.

##### 2.6.0 (2017-05-12)

* IMPROVMENT: added slide for checkboxes.
* IMPROVMENT: added select2.
* IMPROVMENT: added indivudual functions to render elements.

##### 2.4.0 (2015-11-11)

* IMPROVMENT: added ability to create option page in any point of menu
* IMPROVMENT: added meta boxes
* IMPROVMENT: added page load hook
* IMPROVMENT: added script enqueue
* IMPROVMENT: added build-in option page
* IMPROVMENT: integrate tabs display (no more external js in theme or plugin)

##### 2.1.0 (2014-01-11)

* BUGFIX: fix remebering last used tab for theme usage

##### 2.0.0 (2014-01-06)

* IMPROVMENT: init can read both setting: plugin & themes
* IMPROVMENT: add option array filter
* IMPROVMENT: add method to register settings without prefix

##### 1.7.7 (2013-12-27)

* BUGFIX: default value only when is need

##### 1.7.6 (2013-12-18)

* IMPROVMENT: added remove two options to "decativate plugin" function
* IMPROVMENT: added email type input

##### 1.7.5 (2013-12-08)

* BUGFIX: repair some php warnigs

##### 1.7.4 (2013-08-27)

* IMPROVMENT: added filter to change options
* IMPROVMENT: added get_option_group function
* IMPROVMENT: added helper for wp_dropdown_categories
* IMPROVMENT: added helper for wp_dropdown_pages

##### 1.7.3 (2013-06-04)

* BUGFIX: repair get_option, to prevent return always default if null
* IMPROVMENT: added force_default to get_option method

##### 1.7.2 (2013-05-23)

* IMPROVMENT: add min/max attributes to filed type "number"
* IMPROVMENT: add get_option_name method

