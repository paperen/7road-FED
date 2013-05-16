# 7Road web前端开发模块化 初稿
- pubdate: 2013-04-15
- tags:module,html,css,javascript
----
## 我们前端开发遇到的问题

1. 需求不断增多与变化，页面转化率低
2. 文件版本不统一，维护成本高
3. 单兵作战，团队效能未能发挥到最大化
4. bug重复检测或者边做边检测，效率低
5. 网站性能优化靠后，要总体权衡
6. 没有统一[强制性]开发规范

## 我们要怎样解决我们面临的问题
### 前端知识积累+bug解决方案列表+前端模块化解决方案

## 切图
1. 工具：ps 
2. 图片格式：png/gif/jpeg
3. 图片sprite(应该模块化区分，不要过分强调http请求数，加大维护成本)
4. 图片压缩工具
5. 减少图片http链接数[lazyload解决方案]
6. 图片性能img属性src与容器背景background区别，图片预加载，图片动态加载
.....

## Html
1. 语义化的HTML			**[前端知识积累+模块化解决方案]**
2. 规范和合理html结构 	**[前端知识积累+模块化解决方案]**
3. 会做一个专题讲解		**[语义化的HTML,规范和合理html结构]**

## Css
1. 重构reset.css 规范 文字排版规范   参考 (https://github.com/sofish)        **[前端知识积累+模块化解决方案]**
2. 命名规范:(可以参考 http://aliceui.org/)   **[前端知识积累+模块化解决方案]**
3. css书写顺序规范:
	```css
	/*
		第一步：位置 display,position,float,margin,padding,top,left,right,bottom
		第二步: 自身 background,width,height
		第三步：文本 text-indent,text-decoration....
		第四步：文字 font
		第五步：ie hack或者其他游览器hack
		第六部：css3属性
		可以参考 Mozilla官方推荐CSS书写顺序 http://www.mozilla.org/css/base/content.css
	*/
	```
4. 做一个游览器bug大全(包括bug/bug解决方案) 参考 https://github.com/sofish alice项目 http://sofish.de/1400 
5. 通用模块化解决方案 (demo包括 html结构 与 css)   解决再次出现游览器bug  参考http://www.w3cplus.com/solution/index/index.html **[前端知识积累+模块化解决方案]**
6. css三步走: reset.css=>module.css=>extend_module.css  **[前端知识积累+模块化解决方案]**
7. css性能专题[选择符，属性，兼容性,游览器工作原理]

## Javascript
1. 命名规范与开发规范 参考 https://github.com/sofish/idiomatic.js
2. 用seajs 作为 模块化加载器与模块化管理器 [module,export,seajs.use...]
3. 用原生js 开发一个 base.js (dom操作，事件兼容，ajax封装，多属性的运动框架) 追求性能或者一些活动页面使用
4. 范好模块化书写的规范与性能优化 重用性 防止过度封装 注意权衡 （每一个版本的更新会标注文字说明 更新日期）
5. js性能优化/jquery性能优化(专题)

## 周会
每周 必须抽一个下午 起码3个小时， 大家聊一聊开发中遇到问题，怎样解决 以及模块化遇到哪些问题 （必须的，说说大家是怎样欺骗游览器的）

## 参考资料
* 支付宝团队:              http://aliceui.org/             http://aralejs.org/
* google html/css规范：    http://chajn.org/htmlcssguide/htmlcssguide.html
* google js规范：          http://chajn.org/jsguide/javascriptguide.html
* 人人FED CSS编码规范：    http://fed.renren.com/archives/1212
* Bootstrap 中文:          http://www.bootcss.com/
* css 解决 方案:           http://www.w3cplus.com/solution/index/index.html

## 博客推荐
* 张鑫旭:     http://www.zhangxinxu.com/wordpress/
* Ria之家：   http://www.36ria.com/
* 王子墨 ：   http://julying.com/blog/
* Snandy：    http://www.cnblogs.com/snandy/
