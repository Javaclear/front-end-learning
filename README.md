# 全栈开发技术指南————个人学习经历总结
## 目录
1. #### 什么是全栈开发者？
2. #### 成为一个全栈开发者需要具备哪些技术？
3. #### 具体学习进阶指南
    * 入门篇
    * 进阶篇(#first)
    * 项目篇

### 1、什么是全栈开发者？
* 全栈开发者是指同时具备前端、后端和移动端技术的开发人员。

* 前端通常是指应用程序中用户所看到或将交互的部分。

* 后端是指应用程序中处理逻辑、数据库交互、用户认证、服务器配置的部分。

* 移动端，顾名思义是指手机等移动终端开发技术，在web开发中主要包括移动端界面和交互部分。
>全栈工程师是指掌握多种技能，并能利用多种技能独立完成产品的人。也叫全端工程师(同时具备前端和后台能力)，英文Full Stack developer。——引自百度百科

### 2、成为一个全栈开发者需要具备哪些技术？
`依据全栈开发者定义，我们不难确定其所需具备的技术点。`
* 首先得具备前端技术，包括但不限于HTML、CSS、Javascript（ES6等）、浏览器相关知识（如BOM、兼容性等）、文档对象模型（DOM） 等

* 其次得具备后端技术，包括但不限于Linux知识、服务器相关知识（Apache、Nginx、IIS等）、数据库技术（SQL、MySQL、postgresql，mongodb、redis等）、后端编程语言（PHP、Python、Java）、RESTful API、web存储、Http知识 等

### 3、具体学习进阶指南
#### 入门篇
`前端技术入门易，精通难。这里给大家奉上入门指南，供大家参考。`

（1）HTML/CSS
这两者为web的基石，要学习web开发技术，必先学习二者。简单地说，HTML用来给网站添加内容，CSS则是给内容添加样式使其美观
* 掌握HTML标签，必须掌握的常用标签：`div, p, a, h1-h6, span, table, ul, ol, dl, form, input, button, img, audio, video`等。

* 掌握HTML标签的属性，HTML标签可以设置属性。下面四个适用于大多数标签：
>class	为html元素定义一个或多个类名（classname）(类名从样式文件引入)
id	定义元素的唯一id
style	规定元素的行内样式（inline style）
title	描述了元素的额外信息 (作为工具条使用)

* CSS使用方法，外部样式表引用（link标签）、内部样式（style标签）、内联样式（style属性）。

    外部样式：
```
<head>
<link rel="stylesheet" type="text/css" href="mystyle.css">
</head>
```

    内部样式：
```<head>
<style>
hr {color:sienna;}
p {margin-left:20px;}
body {background-image:url("images/back40.gif");}
</style>
</head>
```

    内联样式：
```
<p style="color:sienna;margin-left:20px">这是一个段落。</p>
```


* 掌握CSS选择器，最简单的 id 和 class 选择器，其他更复杂同时更高效的选择器，大家自己深入学习，本指南不做详解。

* 掌握CSS最常用的样式属性（style attribute），背景、文本、链接、图像、表格、表单、列表、边框、边距、显示、浮动、对齐等。

* 掌握CSS盒模型。必须掌握！

（2）Javascript
Javascript是前端开发者必须学习和掌握的编程语言，它是浏览器唯一支持的原生语言。
* Javascript使用方法。

    HTML内部书写：
```
<script>
function myFunction()
{
    document.getElementById("demo").innerHTML="我的第一个 JavaScript 函数";
}
</script>
```

    引入外部文件：
```
<script src="myScript.js"></script>
```

（3）后端技术
作为入门，你得对后端技术有如下了解：

* 学习并掌握一门后端编程语言。
>Node.js：这是一门基于Javascript的后端语言，选择它意味着你可以不用学习新的语言，可以快速上手。
Ruby：用于web开发的框架有 Rails 和 Sinatra 。
Python：最受欢迎的 web 开发框架有 Django 和 Flask。Python是一门值得学习的语言，它应用广发：数据分析、人工智能、web开发。
Java：现在仍有一些公司使用 Java 作为后端语言。一门经典级的web后端语言。
PHP：网络发展的基石，值得学习。



#### 进阶篇{#first}
`当你掌握了一些基本的前端和后端技术，便可以深入学习了。`

（1）前端进阶
* 综合运用HTML和CSS和Javascript，实现一些小功能，比如网页背景变换、网页课程表显示等。

* 学习div+css布局，熟练运用盒模型。

* 学习Ajax技术。

* 学习一些前端框架，页面布局：Bootstrap、Semantic-ui等，js库和框架：jQuery、React、AngularJS、vue.js。

* 更深入的，学习 webpack、browserify技术和 glup构建工具。

* 学习一些测试框架的知识。

（2）后端进阶
* 深入学习所选的编程语言，实现一些小程序、小功能。

* 学习并掌握多种后端开发框架，如python的django、flask，PHP的thinkphp，等。

* 了解常用服务器操作系统并掌握其基本操作（Linux的常用命令及程序安装、服务器web配置、数据库配置等），市场上现有的服务器主要采用Linux系统（Ubuntu、Centos等），也有一些Windows server系统。
>服务器，也称伺服器，是提供计算服务的设备。由于服务器需要响应服务请求，并进行处理，因此一般来说服务器应具备承担服务并且保障服务的能力。

    >服务器的构成包括处理器、硬盘、内存、系统总线等，和通用的计算机架构类似，但是由于需要提供高可靠的服务，因此在处理能力、稳定性、可靠性、安全性、可扩展性、可管理性等方面要求较高。

    >在网络环境下，根据服务器提供的服务类型不同，分为文件服务器，数据库服务器，应用程序服务器，WEB服务器等。
     ——引自百度百科

* 了解SQL语言，学习并使用一种数据库，如MySQL、PostgreSql，Mongodb，redis、memcached等。

* web存储技术。

* HTTP & RESTful
HTTP是应用于互联网的一项无状态应用协议——它规范了客户端连接到服务器的行为。你应该学习如下内容：
>什么是HTTP，它的应用逻辑？
什么是REST，它为什么对HTTP协议和web应用来说很重要？
设计 RESTful API 的最佳实践。
SSL证书是什么？
HTTP/2.
WebSocket、Web Worker。

（3）其他技术（为了长远发展，以下技术必学）
* Git ，版本控制系统。了解其原理，掌握其常用命令。

* 基本算法和数据结构。

* Web应用架构。学习如何高效组织代码，如何分割文件，如何结构化数据库数据，学习应用和浏览器性能优化，掌握 模型-视图-控制器 编程模式（MVC）。

* 不断实践，不断学习，不断交流。

学习资源链接：<https://github.com/JacksonTian/fks>


#### 项目篇
相关内容正在整理···
