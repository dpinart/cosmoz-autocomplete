[![Build Status](https://travis-ci.org/Neovici/cosmoz-autocomplete.svg?branch=master)](https://travis-ci.org/Neovici/cosmoz-autocomplete)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/owner/my-element)

# &lt;cosmoz-autocomplete&gt;

`cosmoz-autocomplete` is a Polymer Component to combine drop-down like behaviour with searchable filtering behaviour. 
Supports both single and multiple selections.

## Installation

To install, run: `bower install --save Neovici/cosmoz-autocomplete`

## Usage

For example, we have the following `data` array:
```js
data = ["Red", "Green", "Blue", "White", "Black"]
```

And an array for storing selected items:
```js
selected = []
```

The following code will create `cosmoz-autocomplete` with multiple selection feature:
<!---
```
<custom-element-demo>
  <template is="dom-bind">
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="cosmoz-autocomplete.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<cosmoz-autocomplete 
  items='[ "Red", "Green", "Blue", "White", "Black" ]'
  selected-items="{{ selected }}"
  placeholder="Search"
  multi-selection>
</cosmoz-autocomplete>
```

## Docs

See http://neovici.github.io/cosmoz-autocomplete
