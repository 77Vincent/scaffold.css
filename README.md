# Scaffold.css / 脚手架CSS

<a href="https://travis-ci.org/77Vincent/scaffold.css"><img src="https://travis-ci.org/77Vincent/scaffold.css.svg?branch=master"></a>

#### An all in one normalizing CSS with enhancements. / 增强的初始化CSS

## Including ／ 包括

##### Nomalizing / 跨浏览器样式还原
##### Useful enhancements / 实用的增强
##### Common helpers / 辅助Class

## Installation / 安装
#### NPM

```sh
npm install --save scaffold.css
```

#### Import in Javascript (Recommended) / 在JS里引入 (推荐方式)

```js
import 'scaffold.css'
```

#### Import in Sass / 在Sass里引入

```scss
@import 'path/to/node_modules/scaffold.css/scaffold.css';
```

#### Or / 或直接引入

```html
<link rel="stylesheet" href="https://raw.githubusercontent.com/77Vincent/scaffold.css/master/scaffold.css">
```

## Key features / 特性

#### All elements including :after & :before are using border-box
##### 所有的元素都使用border-box模型

```css
*,
*:after,
*:before {
    vertical-align: baseline;
    box-sizing: border-box;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
}
```

#### No padding or margin to the body & html
##### 移除body和html的padding与margin
```css
html, body {
    margin: 0px;
    padding: 0px;
}
```

#### 12-column grids class
##### 12纵列网格class
```css
.col-1 { width: 8.33%; }
.col-2 { width: 16.66%; }
.col-3 { width: 25%; }
...
.col-12 { width: 100%; }
```

#### Clearing float
##### 清除浮动


```css
.clearfix {
    content: "";
    display: block;
    clear: both;
}
```

#### Alignment
##### 对齐

```css
.text-center { text-align: center; }
.text-right { text-align: right; }
```

#### No background and border to button
##### 移除button的background和border
```css
button {
    background-color: transparent;
    border: none;
}
```

#### No outline when element is got hover, active or focus
##### 移除outline
```css
:hover,
:active,
:focus {
    outline-width: 0;
}
```

#### Correct color of anchor
##### 修正锚点颜色
```css
a { color: inherit; }
```
