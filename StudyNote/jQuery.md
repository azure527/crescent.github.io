#jQuery学习

[toc]

##定义
jQuery是 轻量级的JavaScript库
优势：
- 容易上手
- 强大的选择器
- 解决浏览器兼容
- 完善的事件机制
- 出色的Ajax封装
- 丰富的UI
本教程分为四个部分
- 样式
- DOM
- 事件
- 动画

##环境搭建

进入官方网站获取最新的版本 <http://jquery.com/download/>
这里需要注意 jQuery 分 2 个系列版本 1.x 与 2.x
主要的区别在于 2.x 不再兼容 IE6、7、8浏览器
这样做的目的是为了兼容移动端开发
由于减少了一些代码
使得该版本比 jQuery 1.x 更小、更快

如果开发者比较在意老版本 IE 用户
只能使用 jQuery 1.9 及之前的版本了
我们这本课程为了兼容性问题使用的是 1.9 版本
jQuery 每一个系列版本分为：压缩版(compressed) 与 开发版(development)
我们在开发过程中使用开发版（开发版本便于代码修改及调试）
项目上线发布使用压缩版（因为压缩版本体积更小，效率更快）

jQuery是一个JavaScript脚本库 不需要特别的安装只需要我们在页面 <head> 标签内中通过 script 标签引入 jQuery 库即可：
` <script type="text/javascript" src="http://libs.baidu.com/jquery/1.9.1/jquery.js"></script> `
用以验证：
' <script type="text/javascript"> alert($) </script> '













1
