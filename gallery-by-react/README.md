# gallery-by-react
photo gallery project based on react

#慕课网，画廊应用 

v1
  画廊舞台以及静态图片展示已经完成

下载代码后，从控制台进入项目目录
1. 运行npm install（自动安装package.json中的相关依赖包，保持网络畅通，不然会有包安装不上，会导致后面的报错）
2. npm start（即可启动项目）
3. 根据控制台输出的页面网址，在本地浏览器打开，即可看到页面效果。（ http://localhost:8000/webpack-dev-server/或者http://localhost:8000/）


v2
画廊应用基本功能完成，
1. 实现点击任意图片，使其居中显示；
2. 点击已居中图片，可以反转该图片，展示其背面信息；
3. 并为动画完善了相应的效果展示

v3
画廊应用完成，并上传到gh-pages上，供线上访问
1. 在构建时，应先修改cfg/default.js中的public.js，将其从"/assets"修改为"assets"
2. 将src/index.html中的src链接的路径由“/assets”修改为“./assets”
3. 运行npm run dist
4. 如果想要本地看到，发布版本dist文件夹的运行效果，可以使用npm start --dist


在线预览效果地址：https://wjma110.github.io/gallery-by-react/
