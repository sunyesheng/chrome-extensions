## Chrome 浏览器插件开发概述

### 目录结构

#### manifest.json

> 具体字段配置含义参考[链接](https://www.yuque.com/r/goto?url=https%3A%2F%2Fdeveloper.chrome.com%2Fdocs%2Fextensions%2Fmv3%2Fmanifest%2F)

所有的浏览器插件必须在根目录下新建文件 manifest.json 清单记录重要的元数据，定义资源，声明权限，并标识哪些文件在后台和页面上运行。

#### service worker

service worker 作用是处理和监听浏览器事件，相当于是在后台持续运行的脚本，可以使用浏览器的全部 api；但是不能和页面内容直接交互。

#### content scripts

content scripts 是在网页上执行的 javascript，可以读取和修改网页上的 dom 元素，但只能使用部分的浏览器 api，具体请见：content scripts。

### 插件页面

## 原生开发

## 框架开发
