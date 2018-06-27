Chrome DevTools

### Shortcuts

* Ctrl + Shift + I (Mac上为 Cmd+Opt+I)打开DevTools。
* Ctrl + Shift + J (Mac上为 Cmd+Opt+J)打开DevTools中的控制台
* Ctrl + Shift + C (Mac上为 Cmd+Shift+C)打开DevTools的审查元素模式。
* Ctrl+[ 和 Ctrl+] 快捷键在不同面板之间进行切换
* Ctrl+L （Mac、Windows、Linux）清除历史记录
- - -
* Ctrl + O (Windows, Linux)、Cmd + F (Mac OS X) 查找文件
* Ctrl + Shift + F (Windows, Linux) 、 Cmd + Opt + F (Max OS X) 全局搜索
* Ctrl + Shift + O(Windows, Linux)、Cmd + Shift + O (Mac OS X) 快速定位
* Ctrl + L (Windows)、Cmd + L(Mac OS X)、Ctrl + G (Linux) 跳转到特定行号

### Console

* console.log：普kk通信息
* console.dir：以JavaScript对象的形式输出到控制台
* console.trace：跟踪相关调用
* console.count：统计某段代码执行了多少次
* console.time & console.timeEnd：时间统计，考量一段代码执行的耗时情况
* console.table：更是直接以表格的形式将数据输出
* console.assert：代码满足某些条件时才输出信息到控制台
- - -
* console.info：提示类信息
* console.error：错误信息
* console.warn：警示信息
* console.group & console.groupEnd：将各自的log信息分组到以各自命名空间为名称的组里面
* console.profile & console.profileEnd：查看CPU使用相关的信息
* console.timeLine & console.timeLineEnd：开始记录一段时间轴

### Command Line

* keys(obj) & values(obj) : 前者返回传入对象所有属性名组成的数据类似 Object.keys()，后者返回所有属性值组成的数组类似 Object.values()
* copy(dom): 通过此命令可以将在控制台获取到的内容复制到剪贴板
* $(selector): 是原生JavaScript document.querySelector() 的封装
* $$(selector)：返回的是所有满足选择条件的元素的一个集合，是对document.querySelectorAll() 的封装
* $x()： 返回满足指定XPath的所有元素
* $_: 返回最近一次表达式执行的结果，功能跟按向上的方向键再回车是一样的
* $0~$4: 最近5个选择过的DOM节点
* monitor(function): 比如function a,每次a被执行了，都会在控制台输出一条信息，里面包含了函数的名称a及执行时所传入的参数
* unmonitor(function) 便是用来停止这一监听
* monitorEvents(dom, [event])：会输出指定监控目标的事件信息
* unmonitorEvents(dom): 指定对象的监控移除