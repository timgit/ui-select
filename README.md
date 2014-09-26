# This fork of angular-ui-select fixes hidden multi-select controls

For example, When a ui-select control is rendered inside a tab control and isn't initially visible. 

from original readme:
## Installation using [Bower](http://bower.io/)

- `bower install angular-ui-select`
- Inside your HTML add
  - select.js: `<script src="bower_components/angular-ui-select/dist/select.min.js"></script>`
  - select.css: `<link rel="stylesheet" href="bower_components/angular-ui-select/dist/select.min.css">`
- Add the `ui.select` module as a dependency: `angular.module("myApp", ["ui.select"]);`

### Bootstrap theme

If you already use Bootstrap, this theme will save you a lot of CSS code compared to the Select2 and Selectize themes.

Bower:
- `bower install bootstrap`
- `<link rel="stylesheet" href="bower_components/bootstrap/dist/css/bootstrap.css">`
- Or the [LESS](http://lesscss.org/) version: `@import "bower_components/bootstrap/less/bootstrap.less";`

[Bootstrap CDN](http://www.bootstrapcdn.com/):
- `<link rel="stylesheet" href="http://netdna.bootstrapcdn.com/bootstrap/3.1.1/css/bootstrap.css">`

Configuration:
```JavaScript
app.config(function(uiSelectConfig) {
  uiSelectConfig.theme = 'bootstrap';
});
```

### Select2 theme

Bower:
- `bower install select2#~3.4.5`
- `<link rel="stylesheet" href="bower_components/select2/select2.css">`

[cdnjs](http://cdnjs.com/):
- `<link rel="stylesheet" href="http://cdnjs.cloudflare.com/ajax/libs/select2/3.4.5/select2.css">`

Configuration:
```JavaScript
app.config(function(uiSelectConfig) {
  uiSelectConfig.theme = 'select2';
});
```

### Selectize theme

Bower:
- `bower install selectize#~0.8.5`
- `<link rel="stylesheet" href="bower_components/selectize/dist/css/selectize.default.css">`
- Or the [LESS](http://lesscss.org/) version: `@import "bower_components/selectize/dist/less/selectize.default.less";`

[cdnjs](http://cdnjs.com/):
- `<link rel="stylesheet" href="http://cdnjs.cloudflare.com/ajax/libs/selectize.js/0.8.5/css/selectize.default.css">`

Configuration:
```JavaScript
app.config(function(uiSelectConfig) {
  uiSelectConfig.theme = 'selectize';
});
```
