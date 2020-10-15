<p align="center"><a href="https://wuchuan123.github.io/vue-ui-demo/" target="_blank" rel="noopener noreferrer"><img width="100" src="./src/images/circle.png" alt="CC UI logo"></a></p>  

<p align="center">
    <a href="https://wuchuan123.github.io/vue-ui-demo/"><img src="https://badge.fury.io/js/init-ui.svg" alt="npm version" height="18"></a>
    <img alt="Travis (.org)" src="https://img.shields.io/travis/wh2887/init-ui">
</p>

作者： CentChuan  

## 介绍
这是我在学习 Vue 的过程中做的一个 UI 框架，希望对你有用。
## 开始使用
1. 添加 CSS 样式
    使用本框架前，请在 CSS 中开启 border-box
    ```css
    *,*::before,*::after{box-sizing:border-box}
    ```
    IE 15 及以上浏览器都支持此样式
    
2. 安装 CC UI
    ```
    npm i --save CC-ui
    ```
3. 引入 CC-ui
    ```javascript
    import {Button, ButtonGroup, Icon,Col, Collapse, CollapseItem, Content, Footer, Header, Input, Layout, Popover
             , Row, Sider, Tabs, TabsHead, TabsBody, TabsItem, TabsPane, Toast,plugin
           } from 'CC-ui'
    import 'CC-ui/dist/index.css'    
    import Vue from 'vue'
    Vue.use(plugin)
    
    export default {
      name: 'app',
      components: {
            'i-button':Button,
            'i-icon':Icon,
            'i-button-group':ButtonGroup,
            'i-col':Col,
            'i-collapse':Collapse,
            'i-collapse-item':CollapseItem,
            'i-content': Content,
            'i-footer': Footer,
            'i-header': Header,
            'i-input': Input,
            'i-layout': Layout,
            'i-popover': Popover,
            'i-row': Row,
            'i-sider': Sider,
            'i-tabs': Tabs,
            'i-tabs-head': TabsHead,
            'i-tabs-body': TabsBody,
            'i-tabs-item': TabsItem,
            'i-tabs-pane': TabsPane,
            'i-toast': Toast,
     }
    }
    ```
## 文档
[CC UI 官网](https://wuchuan123.github.io/vue-ui-demo/)
## 提问
[issues](https://github.com/wuchuan123/vue-ui-demo/issues)
## 变更记录

## 联系方式

## 贡献代码

