[**Selectize needs your help. I'm looking for maintainers!**](https://github.com/brianreavis/selectize.js/issues/752)

### Theming

```sass
// base styles

$selectize-font-family: inherit !default;
$selectize-font-smoothing: inherit !default;
$selectize-font-size: 13px !default;
$selectize-line-height: 18px !default;

$selectize-color-text: #303030 !default;
$selectize-color-border: #d0d0d0 !default;
$selectize-color-highlight: rgba(125,168,208,0.2) !default;
$selectize-color-input: #fff !default;
$selectize-color-input-full: $selectize-color-input !default;
$selectize-color-disabled: #fafafa !default;
$selectize-color-item: #f2f2f2 !default;
$selectize-color-item-text: $selectize-color-text !default;
$selectize-color-item-border: #d0d0d0 !default;
$selectize-color-item-active: #e8e8e8 !default;
$selectize-color-item-active-text: $selectize-color-text !default;
$selectize-color-item-active-border: #cacaca !default;
$selectize-color-dropdown: #fff !default;
$selectize-color-dropdown-border: $selectize-color-border !default;
$selectize-color-dropdown-border-top: #f0f0f0 !default;
$selectize-color-dropdown-item-active: #f5fafd !default;
$selectize-color-dropdown-item-active-text: #495c68 !default;
$selectize-color-dropdown-item-create-text: rgba(red($selectize-color-text), green($selectize-color-text), blue($selectize-color-text), 0.5) !default;
$selectize-color-dropdown-item-create-active-text: $selectize-color-dropdown-item-active-text !default;
$selectize-color-optgroup: $selectize-color-dropdown !default;
$selectize-color-optgroup-text: $selectize-color-text !default;
$selectize-lighten-disabled-item: 30% !default;
$selectize-lighten-disabled-item-text: 30% !default;
$selectize-lighten-disabled-item-border: 30% !default;
$selectize-opacity-disabled: 0.5 !default;

$selectize-shadow-input: inset 0 1px 1px rgba(0,0,0,0.1) !default;
$selectize-shadow-input-focus: inset 0 1px 2px rgba(0,0,0,0.15) !default;
$selectize-border: 1px solid $selectize-color-border !default;
$selectize-dropdown-border: 1px solid $selectize-color-dropdown-border !default;
$selectize-border-radius: 3px !default;

$selectize-width-item-border: 0 !default;
$selectize-max-height-dropdown: 200px !default;

$selectize-padding-x: 8px !default;
$selectize-padding-y: 8px !default;
$selectize-padding-item-x: 6px !default;
$selectize-padding-item-y: 2px !default;
$selectize-padding-dropdown-item-x: $selectize-padding-x !default;
$selectize-padding-dropdown-item-y: 5px !default;
$selectize-margin-item-x: 3px !default;
$selectize-margin-item-y: 3px !default;

$selectize-arrow-size: 5px !default;
$selectize-arrow-color: #808080 !default;
$selectize-arrow-offset: 15px !default;

$selectize-caret-margin: 0 2px 0 0 !default;
$selectize-caret-margin-rtl: 0 4px 0 -2px !default;
```

### Usage

```js
$('select').selectize(options);
```

The available options are [documented here](docs/usage.md).

## License

Copyright &copy; 2013–2015 [Brian Reavis](http://twitter.com/brianreavis) & [Contributors](https://github.com/brianreavis/selectize.js/graphs/contributors)

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at: http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
