---
layout: index
title: 首页
permalink: /
---

# React 学习指南

## 目录
* [官方网站](#site)
* [技术栈](#tech-stack)
* [实例教程](#demos)
* [相关资源](#relative-resource)
* [辅助工具](#tools)

<a name="site"></a>

## 官网
* [React](https://facebook.github.io/react/index.html)
* [Redux](https://github.com/reactjs/redux)
* [Flux](https://facebook.github.io/flux/)

<a name="tech-stack"></a>

## 技术栈
React + React-Router + Redux + Webpack + ES6 + Mocha

<a name="demos"></a>

## 实例教程 (react-v15.1.0)

<ul class="post-list">
{% for post in site.posts %}
    <li class="post-list-item">
        <a href="{{ site.baseurl }}{{ post.url }}" title="{{ post.title | strip_html }}" class="post-list-content">{{ post.title | strip_html }}</a> 
        <span class="post-list-extra">{{ post.author }} 发布于 {{ post.date | date_to_string}}</span>
    </li>
{% endfor %}
</ul>

<a name="relative-resource"></a>

## 相关资源
* [颠覆式前端UI开发框架——React](http://www.infoq.com/cn/articles/subversion-front-end-ui-development-framework-react)
* [React 入门教程](https://hulufei.gitbooks.io/react-tutorial/content/)
* [React Router 使用教程](http://www.ruanyifeng.com/blog/2016/05/react_router.html)
* [React 测试入门教程](http://www.ruanyifeng.com/blog/2016/02/react-testing-tutorial.html)
* [ReactJS 中文视频教程]( http://react.nodejs-china.org/t/reactjs/584)
* [React 入门实例教程](http://www.ruanyifeng.com/blog/2015/03/react.html)
* [Flux 架构入门教程](http://www.ruanyifeng.com/blog/2016/01/flux.html)
* [深入浅出React（一）：React的设计哲学 - 简单之美]( http://www.infoq.com/cn/articles/react-art-of-simplity)
* [深入浅出React（二）：React开发神器Webpack]( http://www.infoq.com/cn/articles/react-and-webpack)
* [深入浅出React（三）：理解JSX和组件]( http://www.infoq.com/cn/articles/react-* jsx-and-component)
* [深入浅出React（四）：虚拟DOM Diff算法解析]( http://www.infoq.com/cn/articles/react-dom-diff)
* [React+Webpack+ES6+Babel构建模块化JavaScript应用](http://www.csdn.net/article/2015-05-24/2824757-building-modular-javascript-applications-in-es6- with-react-webpack-and-babel)
* [React.js中文文档](http://reactjs.cn/)
* [Redux 中文文档](http://camsong.github.io/redux-in-chinese)
* [React-Native学习指南](https://github.com/reactnativecn/react-native-guide)

<a name="tools"></a>

## 辅助工具
* [New React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)
* [React-webpack-cookbook中文版](http://fakefish.github.io/react-webpack-cookbook/)
* [开源项目持续集成构建工具Travis CI](https://travis-ci.org/)
* [测试代码的覆盖率coveralls.io](coveralls.io)

