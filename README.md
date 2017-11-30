# ele

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
# vue-eleme项目学习笔记

// 通过下一行注释使eslint 忽略new实例没有赋值的问题
/* eslint-disable no-new */
new Vue({
  el: '#app',
  template: '<App/>',
  components: { App }
});

---
问题：
vue初始化报错，Cannot read property '$createElement' of undefined

解决：
routes里面components写错应该是component
link: https://segmentfault.com/q/1010000011447867

---
css规范
    display  position width height 写在前面
    字体 颜色的可被继承的属性写在后面

---

手机上调试电脑开发的网页
1. 手机、电脑连接同一局域网
1. 电脑网页链接localhost修改为IP地址
1. 复制url到草料二维码生成二维码
1. 手机微信扫描二维码打开网页

---
json view chrome plugin

---
css3 translate3d样式可以开启硬件加速，动画更加流畅
点击区域加padding可以使样式不变，但是实际点击区域更大，便于点击
---
width: 100%
height: 0
padding-top: 100%
此时相当于是一个宽高相等的盒子

---
CSS秘密花园： Sticky footers
https://www.w3cplus.com/css3/css-secrets/sticky-footers.html
.detail-wrapper 清浮动
    min-height: 100%
    width: 100%
.detail-close
    position: relative
    width: 32px
    height: 32px
    margin: -64px auto 0 auto
    clear: both
    font-size: 32px


