# Scaffold.css 脚手架CSS
An all in one normalizing CSS with other enhancements for scaffolding morden websites / 包括还原以及其他增强的初始化CSS

## Including ／ 包括 
* Normalizations / 跨浏览器样式还原
* Useful enhancements / 实用的增强
* Common helpers / 基本辅助Class

## Installation
Through npm / 通过npm安装

    npm install --save scaffold.css
    
Import in Javascript / 在JS里引入
    
    import 'scaffold.css'

Import in Sass / 在Sass里引入

    @import 'path/to/node_modules/scaffold.css/scaffold.css';

Or / 或直接引入
    
    <link rel="stylesheet" href="https://raw.githubusercontent.com/77Vincent/scaffold.css/master/scaffold.css">

## Features / 特性

* All elements are using box-sizing: border-box;

* Helper classes:

    /* 12 columns grid */
    .col-1 { width: 8.33%; }
    .col-2 { width: 16.66%; }
    .col-3 { width: 25%; }
    ...
    .col-12 { width: 100%; }

    /* Clear float */
    .clearfix {
        content: "";
        display: block;
        clear: both;
    }

    /* Alignment */
    .text-align {
        text-align: center;
    }

