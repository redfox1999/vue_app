# vue_app
使用  electron +  Vue.js + iViewUI 的DEMO 可也可以很方便的换到  Element-UI.  使用方法：  1 . npm install    安装依赖库  2. npm run dev 打开 webpack dev-server 3. npm start 可以启动 electron 界面。  是使用 http://localhost:8080/ 的方式来显示界面。 Release 时，可以先 npm run build 把HTML + JS 生成到 dist 目录，再把 app_src.js 加载文件的地方改一下 注意这里可能有坑。默认的  webpack build后的路径有点问题，需要改成相对路径的。
