## 关于
这是 cdnjs.com 的国内镜像，致力于打造一个稳定而又全面的 JS/CSS 库，给前端开发者免费使用。 国内现在有新浪、百度、360、七牛、又拍云等公司提供类似服务，但他们的 JS/CSS 库不是很全，不能全面满足前端开发者的需求。国外 cdnjs.com 所列的 JS/CSS 库较全，但由于 CDN 节点在国外，国内访问速度不理想。所以作者搭建了这个平台，通过七牛镜像存储，将 cdnjs.com 所列 JS/CSS 库存储至国内 CDN 节点。

## 网址
http://www.codefarm.net/

## 使用
```js
<script src="http://libs.cncdn.cn/jquery/2.0.3/jquery.min.js"></script>
<!--CDN 不稳定时，加载本地资源-->
<script>window.jQuery || document.write('<script src="/jquery.min.js"><\/script>');</script>
```
