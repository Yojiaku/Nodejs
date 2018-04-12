# Node.js与CommonJS

JS缺少模块管理机制来管理，CommonJS就是一套规范，来约定JavaScript应该怎么组织。

一个模块分为：定义，规范，引用

核心模块：http fs path

文件模块

第三方模块：var promise = require\('xxx'\)



模块的流程

创建模块：teacher.js

导出模块：exports.add = function\(\){}

加载模块：var teacher = require\('teacher.js'\)

使用模块：teacher.add\('Yojiaku'\)

