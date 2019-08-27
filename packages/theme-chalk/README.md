# @deepexi-devops/element-theme
devops 自定义 element 主题

## Installation
```shell
yarn add @deepexi-devops/element-theme
```

## Usage

在 nuxt 中使用
```javascript
// 修改 nuxt.config.js
babel: {
  plugins: [
    [
      'component',
      {
        libraryName: 'element-ui',
        styleLibraryName: '~node_modules/@deepexi-devops/element-theme/lib'
      }
    ]
  ]
}
```
在 vue 项目中使用
```javascript
import Vue from "vue";
import ElementUI from 'element-ui';
import '@deepexi-devops/element-theme';
Vue.use(ElementUI);
```