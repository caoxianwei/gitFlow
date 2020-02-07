vh/vw、rem/em、dpr是什么，有什么区别
rem的实现原理和方式	
3	CSS	1	
实现水平、垂直居中有哪些方式	

栅格布局实现原理	
5	JavaScript	1	
call、apply、bind区别
事件代理（委派）的作用,使用场景和实现原理
是否使用过事件代理
为什么react和vue不推荐做事件代理，它们怎么实现的
vue 对不同dom绑定同一事件,不存在性能问题
react 自行实现了合成事件

简述下盒模型
从外到内 margin,outline,border,padding,content
伸延：box-sizing中border-box和content-box的区别

BFC是什么
怎么实现一个BFC
BFC有什么用
基本概念和使用场景	

伸延
有哪些情况默认会创建BFC
2	JavaScript	3	3	防抖和节流	
基本概念和使用场景
核心实现,实现的方式
lodash如何实现

3	JavaScript	3	3	webpack如何转换es6/7/8/9至es5的	
转换过程
loader实现
使用babel-loader编译es6，使用babylon
将代码解析成AST抽象语法树并根据插件配置转换生成es5

伸延：是否写过babel插件
AST visitor作用
babel7 和babel6有什么区别,做了哪些改进

Node.js多线程写文件的解决	



2	javascript	4	4	
深拷贝和浅拷贝有什么区别
深拷贝实现
深拷贝要怎么处理 function,Symbol,object,array


基本数据类型和引用类型内存存放地址
堆和栈的区别
基本数据类型和引用类型比较
赋值，传值和传址
lodash 深拷贝实现，是否阅读过源码并了解实现
赋值只是传址，不是真正的拷贝




伸延：深拷贝使用场景
3	浏览器	

垃圾回收机制

如何分析并解决浏览器内存泄漏问题

垃圾回收流程
内存泄漏定义，原因
怎么避免内存泄漏
新生代回收 老生代回收 全停顿 相关算法
不再使用，失去控制，未能释放
缓存，全局变量，计时器，闭包
Chrome 导出导入Heap Snapshot进行分析

伸延：如何手动触发垃圾回收行为