# Scaffold.css

[![Build Status](https://travis-ci.org/77Vincent/scaffold.css.svg?branch=master)](https://travis-ci.org/77Vincent/scaffold.css)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

All in one normalize CSS with enhancements and helpers to scaffold mordern websites.
## Including

* Nomalizing
* Useful enhancements
* Common helpers

## Installation
#### NPM

```sh
npm install --save scaffold.css
```

#### Import in Javascript (Recommended)

```js
import 'scaffold.css';
```

#### Import in Sass

```scss
@import 'path/to/node_modules/scaffold.css/scaffold.css';
```

#### Or

```html
<link rel="stylesheet" href="https://raw.githubusercontent.com/77Vincent/scaffold.css/master/scaffold.css">
```

## Enhancemens

```css
html,
body {                      
  margin: 0;
  padding: 0;
}
 
h1,
h2,
h3,
h4,
h5,
h6 {
  font-weight: normal;
  font-style: normal;
}
 
ol,
ul {
  margin: 0;
  padding: 0;
}

*,
*::after,
*::before {
  vertical-align: baseline;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
 
:hover,
:active,                                                                                                                                                      
:focus {
  outline-width: 0;
}
 
a { color: inherit; }
 
button {
  background-color: transparent;
  border: none;
}
 
table {
  border-collapse: collapse;
  border-spacing: 0;
}
```

## Helpers

#### 12-column grids class
```css
.col-1 { width: 8.33%; }
.col-2 { width: 16.66%; }
.col-3 { width: 25%; }
...
.col-12 { width: 100%; }
```

#### Clearing float
```css
.clearfix {
    content: "";
    display: block;
    clear: both;
}
```

#### Alignment
```css
.text-left    { text-align: left; }
.text-center  { text-align: center; }
.text-right   { text-align: right; }
```

## Normalizing
Mostly fork from <a href="https://github.com/necolas/normalize.css">necolas/normalize.css</a>

## Browser support
Internet Explorer 8+
