# @femessage/element-theme-devops
devops 自定义 element 主题

## Installation
```shell
yarn add @femessage/element-theme-devops --registry http://levy.ren:4873
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
        styleLibraryName: '~node_modules/@femessage/element-theme-devops/lib'
      }
    ]
  ]
}
```
在 vue 项目中使用
```javascript
import Vue from "vue";
import ElementUI from 'element-ui';
import '@femessage/element-theme-devops/lib/index.css';
Vue.use(ElementUI);
```