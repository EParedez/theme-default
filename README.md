# element-theme-default
> element component defualt theme.


## Installation
```shell
npm i element-theme-default -S
```

## Usage

Use Sass Or postcss-import
```css
@import 'element-theme-default';
```

Or Use webpack
```javascript
import 'element-theme-default';
```

Or
```html
<link rel="stylesheet" href="path/to/node_modules/element-theme-default/lib/index.css">
```

##  Import your need
```javascript
import 'element-theme-default/lib/input.css';
import 'element-theme-default/lib/select.css';

// ...
```
##  Adding icons
> open element-icons.ttf with FontForge and save as SVG
> open SVG in http://fontello.com/, add custom icons(maybe you should customize the names), download webfont file
> copy webfont file in src/fonts/, and edit icons.css, for example:
```css
@font-face {
    font-family: 'element-icons';
    src: url('fonts/fontello.ttf') format('woff'), /* chrome, firefox */
      url('fonts/fontello.ttf') format('truetype'); /* chrome, firefox, opera, Safari, Android, iOS 4.2+*/
    font-weight: normal;
    font-style: normal;
}
.el-icon-error:before { content: "\e800"; }
