---
layout: post
title:  chrome developer
---

Tips:

<h2>1. Filter</h2>

如何通过filter定位到具体的js css文件？

    在source 面板 使用 ctrl+o可以打开filter选择框

如何通过filter定位到具体某个文件的关键字？

    使用ctrl+f打开输入框(在这里可以进行替换replace)

如何在所有文件中检索某关键字？
    
    ctrl+shift+f

在某个文件中检索函数(JS)或选择器(CSS):
    
    ctrl+shift+o

跳到某一行
    
    ctrl+g



<h2>2.source面板</h2>

snippets:片段

    可以在snippets中右键添加一个js/css片段，建立完成之后可以RUN该段代码
    同时可以选中其中某段代码右键“Evaluate in Console”运行选中代码
    
    和source的Local modifications一样可以查看代码修改历史版本


<h2>3.Console面板</h2>

console.log() //可接多个参数

console.error()//输出是红色的

console.warn()//输出背景色是黄色的

console.assert()//assertions 断言 两个参数

    两个参数，第一个参数是一个表达式。当第一个参数执行出错为false
    第二个参数显示。第二个是错误的消息

    console.assert(1>2,'error,1 is smaller then 2');

console.group()/console.groupEnd();
    
    在group和groupEnd内部的console信息属于一组
    可以嵌套

console.table()

    格式化显示数据
    console.table([{a:1, b:2, c:3}, {a:"foo", b:false, c:undefined}]);
    console.table([[1,2,3], [2,3,4]]);

