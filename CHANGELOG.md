## v0.4.0

* rename `NG_BOOTSTRAP_TABLE_DIRECTIVES` to `BS_TABLE_DIRECTIVES`
* rename `NG_BOOTSTRAP_TABSX_DIRECTIVES` to `BS_TABSX_DIRECTIVES`
* rename `NG_BOOTSTRAP_DIRECTIVES` to `BS_DIRECTIVES`
* add `file-upload` directives

## v0.3.4

* correct wrong totalChange value change in pagination
* correct modal demo button class
* use `totalPages` value from pagination instead calculating it in `table-demo`
* correct back `removeTab` as proposed on PR #23

## v0.3.3

* correct bug of accordion-panel not opening by default

## v0.3.2

* add ability to use complex objects as data input for table component

## v0.3.1

* upgrade `bootstrap_sass` to `v4.0.0-alpha.3+4`
* upgrade `sass_transformer` to `v0.1.1`
* change `sass` to `sass_transformer` in README

## v0.3.0+1

* use `sass_transformer 0.1.0` instead `dart-sass 0.5.0`
* remove packages path from `all.scss`

## v0.3.0

* Rename components to use pattern `Bs<name>Component`
* Rename directives to use pattern `Bs<name>Directive`
* Make `BsTimePickerComponent.writeValue` method `async`
* Make `BsDatePickerComponent.writeValue` method `async`
* Add styling for `bs-pager`
* Add `min-width` to `bs-pagination` components in `bs-pagination-demo`
* Upgrade to `angular 2.0.0-alpha.20`

## v0.2.3

* add `BsTableComponent` and `BsColumnComponent`:
  - no column template supported
  - no complex objects as row input supported
  - no selection
  - no actions (delete, edit, view, ...)
* correct pagination directive totalItems change
* Collapse directive:
  - correct collapsing animation
  - remove `isCollapse` and `isCollapsed attributes`
  - add `bsCollapseChange` and `collapsingChange` event-emitters
* upgrade bootstrap_sass to 4.0.0-alpha.3+1
* use $ling-height-base instead $line-height in _panel.scss
* rename css-class scrollable-menu to scrollable-navbar-menu to avoid crashes with class in _dropdown.scss
* fix collapse_demo.html: collapse not being hidden
* correct panel-title font too big

## v0.2.2

* make `TypeAhead.dropdownMenu` scrollable. Fixes #7.
* add `noResults` and `loading` messages to `TypeAhead.dropdownMenu`
* correct `TypeAhead` case sensitivity results
* remove `TypeAhead._queryStream.distinct` processing, this avoids values not 
  gotten when same value has been typed before after passing debounce time

## v0.2.1

* rename `n2sCollapse` to `bsCollapse`
* fix bug in `accordion` caused when `closeOthers` attribute is null
* remove unneeded code on `DatePickerPopup` (solves #26)
* correct error caused by entering wrong date onto DatePickerPopup-TextBox

## v0.2.0

* upgrade to angular 2.0.0-beta.19
* Fix Removing tabs sometimes didn't work #23
* Added support for typeaheads to specify a `optionField` in complex Objects
* Rename NG_BOOTSTRAP_TABS_DIRECTIVES to NG_BOOTSTRAP_TABSX_DIRECTIVES
* Add NG_BOOTSTRAP_TABS_DIRECTIVES constant
* Remove components.dart and put the code into ng_bootstrap.dart directly
* Rename NGBS_CAROUSEL_DIRECTIVES to NG_BOOTSTRAP_CAROUSEL_DIRECTIVES

## v0.1.1

* correct bug sass not founding files doubt to usage of relative path instead of packages path
* change caret icon of typeahead to font-awesome icon
* Remove Getting Started and Migration links from demo header
* correct visual errors in dropdown demo
* add style display inline-block to bs-dropdown