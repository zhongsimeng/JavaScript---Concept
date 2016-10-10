# JavaScript---Concept

## 什么是JavaScript
JavaScript是一种动态类型、弱类型、基于原型的客户端脚本语言，用来给HTML网页增加动态功能

### 动态
在运行时确定数据类型。变量使用之前不需要类型声明，通常变量的类型是被赋值的那个值的类型。

### 弱类
计算时可以不同类型之间对使用者透明式隐式转换，即使类型不正确，也能通过隐式转换得到正确的类型。

### 原型
新对象继承对象（作为模板），将自身的属性共享给新对象，模板对象称为原型。这样新对象实例化后不但可以享有自己创建时和运行时定义的属性，而且可以享有原型对象的属性

PS：新对象值函数，模板对象是实例对象，实例对象是不能继承原型的，函数才可以。

##JavaScript由三部分组成

### 1.ECMAScript（核心）
作为核心，它规定了语言的组成部分：语法、类型、语句、关键字、保留字、操作符、对象

### 2.DOM（文档对象模型）
DOM把整个页面映射为一个多层节点结果，开发人员可借助DOM提供的API ，轻松地删除、 添加、替换或修改任何节点。

PS：DOM也有级别，分别为DOM1、DOM2、DOM3，拓展不少规范和新接口

### 3.BOM（浏览器对象模型）
支持可以访问和操作浏览器窗口的浏览器对象模型 ，开发人员可以控制浏览器显示的页面以外的部分。

PS： BOM未形成规范
