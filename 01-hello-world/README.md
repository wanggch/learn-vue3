# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)




使用vite创建vue3应用

# npm 6.x
npm create vite@latest my-vue-app --template vue

# npm 7+, extra double-dash is needed:
npm create vite@latest my-vue-app -- --template vue

# yarn
yarn create vite my-vue-app --template vue


yarn create vite 01-hello-world --template vue


目录结构：

```sh
├── README.md												# 项目说明文件
├── index.html											# 首页入口文件
├── package.json										# 项目配置文件
├── public													# 公共资源目录
│   └── vite.svg										# 网站icon
├── src															# 源代码
│   ├── App.vue											# 项目入口页面
│   ├── assets											# 静态资源目录
│   │   └── vue.svg									# vue icon
│   ├── components									# vue组件目录，自定义组件存放位置
│   │   └── HelloWorld.vue					# 自定义组件示例
│   ├── main.js											# 核心文件，加载组件、初始化等
│   └── style.css										# css样式
├── vite.config.js									# vite配置文件
└── yarn.lock												# 使用yarn后自动生成的文件
```