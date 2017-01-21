# Scaffold.css  /  脚手架CSS

<a href="https://travis-ci.org/77Vincent/scaffold.css"><img src="https://travis-ci.org/77Vincent/scaffold.css.svg?branch=master"></a>
<a href="https://www.npmjs.com/package/scaffold.css"><img src="https://img.shields.io/badge/npm-v1.1.0-blue.svg"></a>
<a href="https://github.com/77Vincent/scaffold.css/blob/master/LICENSE"><img src="https://img.shields.io/badge/lisence-MIT-blue.svg"></a>

#### An all in one normalize CSS with enhancements and helpers. / 增强的初始化CSS

## Including ／ 包括

* Nomalizing / 跨浏览器样式还原
* Useful enhancements / 实用的增强
* Common helpers / 辅助Class

## Installation / 安装
#### NPM

```sh
npm install --save scaffold.css
```

#### Import in Javascript (Recommended) / 在JS里引入 (推荐方式)

```js
import 'scaffold.css';
```

#### Import in Sass / 在Sass里引入

```scss
@import 'path/to/node_modules/scaffold.css/scaffold.css';
```

#### Or / 或直接引入

```html
<link rel="stylesheet" href="https://raw.githubusercontent.com/77Vincent/scaffold.css/master/scaffold.css">
```

## Enhancemens / 增强特性

```css
html {
  font-size: 1em;
}
 
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

## Helpers / 辅助Class

#### 12-column grids class / 12纵列网格class
```css
.col-1 { width: 8.33%; }
.col-2 { width: 16.66%; }
.col-3 { width: 25%; }
...
.col-12 { width: 100%; }
```

#### Clearing float / 清除浮动
```css
.clearfix {
    content: "";
    display: block;
    clear: both;
}
```

#### Alignment / 对齐
```css
.text-center { text-align: center; }
.text-right { text-align: right; }
```

## Normalizing / 标准化
Mostly fork from <a href="https://github.com/necolas/normalize.css">necolas/normalize.css</a>

## Browser support / 浏览器支持
Internet Explorer 8+
