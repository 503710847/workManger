# 起源

本项目用于学校内部的管理，用于代替先前的手工管理模式，改变资料存放不集中，杂乱无章法、无规范的流程，主要要实现以下几个功能：
- 教师、学生基本信息管理
- 教师、学生的成长记录管理
- 学生操行管理
- 学生考勤管理
- 学生成绩管理
- 学校内部校讯通功能
- 学校内部各种固定资产的登记、外借、回收管理
- 学校微信公众平台的基础管理、普通消息群发，模板消息发送等常用功能
- 教师、家长微信端基本功能查询  成绩查询  工资查询 电话号码查询

## 技术栈

laravel5.5 + vuejs 2.5.2 + vue-router + vuex +element ui 2.0 + easywechat

- 后端模块 backend目录  使用[laravel5.5](http://laravelacademy.org/)框架 利用laravel passport来实现oauth 2.0认证，后端只负责开发api，
  实现主流意义上的前后端分离开发，并配置有相关的接口文档
  
- 前端模块 frontend目录  使用相关开源框架 [vueAdmin-template](https://github.com/PanJiaChen/vueAdmin-template) 
  并结合自己的需求改进而来  项目基于element ui 2.0 并使用了前端的权限管理
  
- 微信端 wx目录  计划中  使用开源微信SDK--[easywechat](https://www.easywechat.com/)主要给家长、教师提供更好的查询页面  查找各类信息

## 知识点
虽然项目暂不涉及到高大上的高并发、大数据等内容，但下面的内容或许会是你需要的：
>- 前后端分离的代码编写方式  项目发布方式
>- laravel中oauth2.0的认证
>- vue.js中如何结合后台api进行开发 如何在前端控制用户的登陆以及对数据的访问的权限
>- 结合实际开发中的webpack的各种配置方式
  

## 项目测试
- 后端使用了laravel 可以参考backend中的相关资料进行发布与测试  后端只提供api接口和api文档
- 前端使用了vue.js 技术  可以参考vue.js的项目流程来进行发布与测试

# 说明

>  如果对您有帮助，您可以点右上角 "Star" 支持一下 谢谢！ ^_^

>  或者您可以 "follow" 一下，我会不断完善该项目

>  开发环境 windows 7  Chrome 63  PHP 7.1.7

>  如有问题请直接在 Issues 中提，或者您发现问题并有非常好的解决方案，欢迎 PR 👍

>  项目交流群：106822531(QQ)

# License

[MIT](https://github.com/wmhello/workManger/LICENSE)

