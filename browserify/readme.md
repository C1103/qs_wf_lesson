## JS模块化及 前端构建工具
 1. JS模块化支持的不好，一直到es6 出现了
 import(es6模块化) require(CommonJS node原生支持的模块化)
 > 模块化是组织代码的语法功能
 > require 引入 输出 module.exports 
 > 前端不支持require node 后端环境，前端 dom环境
 > 一统江湖 browserify
   一份代码，就可以在前端后端都可以运行。
   一个类，或者一个模块，作为前后端通用的js语言，
   不应该有分别，提高了前后端代码的复用性
   前端构建工具