# Scaffold.css / 脚手架CSS

#### An all in one normalizing CSS with enhancements. / 增强的初始化CSS

## Including ／ 包括

* Nomalizing / 跨浏览器样式还原
* Useful enhancements / 实用的增强
* Common helpers / 基本辅助Class

## Installation / 安装
#### NPM

    npm install --save scaffold.css

#### Import in Javascript (Recommended) / 在JS里引入 (推荐方式)

    import 'scaffold.css'

#### Import in Sass / 在Sass里引入

    @import 'path/to/node_modules/scaffold.css/scaffold.css';

#### Or / 或直接引入

    <link rel="stylesheet" href="https://raw.githubusercontent.com/77Vincent/scaffold.css/master/scaffold.css">

## Features / 特性

#### All elements are using ／ 所有的元素都使用border-box模型

    box-sizing: border-box;

#### 12-column grids class / 12纵列网格class:

    .col-1 { width: 8.33%; }
    .col-2 { width: 16.66%; }
    .col-3 { width: 25%; }
    ...
    .col-12 { width: 100%; }

#### Clearing float / 清除浮动:

    .clearfix {
        content: "";
        display: block;
        clear: both;
    }

#### Alignment / 对齐:

    .text-align {
        text-align: center;
    }

