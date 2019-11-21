# vue_app

> A Vue.js project

使用  electron +  Vue.js + iViewUI 的DEMO.

也可以很方便的换到  Element-UI.  

需要 electron-forge

使用方法：

1. npm install    安装依赖库

2. npm run dev 打开 webpack dev-server 

3. npm start 可以启动 electron 界面。  

是使用 http://localhost:8080/ 的方式来显示界面。 Release 时，可以先 npm run build 把HTML + JS 生成到 dist 目录，再把 app_src.js 加载文件的地方改一下 注意这里可能有坑。默认的  webpack build后的路径有点问题，需要改成相对路径的。

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# open electron UI
npm start

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
