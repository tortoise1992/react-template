# ahui-react-template

## 简介
`ahui-react-template` 是一个快速搭建react项目的解决方案，它是基于[vue-cli](https://github.com/vuejs/vue-cli)。它使用的是开发vue项目的通用配置，能够让开发者在两种项目开发中快速切换并适应，希望本项目能帮到你们。

## 如何使用
- 简单使用：直接使用git克隆本项目到本地`git clone https://github.com/tortoise1992/react-template.git`，然后进入项目本目录`cd react-template`，执行`npm install`，如果使用cnpm，请自行修改安装即可，后续和`vue-cli`的项目用法一致。

- 自定义使用：如果你想自己修改的话，或者项目依赖和webpack有所变动的话，那么请看下面详细教程。

## 手把手教你改造vue-cli
### 准备工作
你的本地环境需要安装 [node](http://nodejs.org/) 和 [git](https://git-scm.com/)，同时确保你已经安装了安装vue-cli。

### 实战开始
- 打开git控制台，新建一个空文件夹`mkdir project`，进入文件夹`cd project`
- 执行`vue init webpack`,不要安装了vue-router,eslint自行选择安装。
- 打开package.json文件，删除全部带有vue的依赖配置。
- 安装我们需要的依赖包：`npm install `


> 未完待续...
