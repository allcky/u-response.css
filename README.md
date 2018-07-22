# u-response.css
This is a responsive layout Library.


[![npm version](https://img.shields.io/npm/v/u-response.css.svg?style=flat-square)](https://www.npmjs.org/package/u-response.css)
[![npm downloads](https://img.shields.io/npm/dm/u-response.css.svg?style=flat-square)](http://npm-stat.com/charts.html?package=u-response.css)

## 安装(Install)
```
npm install --save u-response.css
```
## 下周(Download)
https://unpkg.com/u-response.css
## Less2Css
```
$ npm start
//lessc u-response.less u-response.css
```
## 文件列表(Files)
```
u-response.css   # 生成css文件
u-response.less  # 响应式核心
u-var.less       # 定义参数
```
## 使用(Use)

```
<link rel="stylesheet" href="u-response.css">
```

### 布局容器
```
# .container 类用于固定宽度并支持响应式布局的容器。
<div class="container">
  ...
</div>

# .container-fluid 类用于 100% 宽度，占据全部视口（viewport）的容器。
<div class="container-fluid">
  ...
</div>
```

### 栅格
栅格用于通过一系列的行（row）与列（column）的组合来创建页面布局.

### 类名

类名 | 描述        
------|------------- 
.col-xs-1 ~ .col-xs-12 | 手机设备(768 > screen )
.col-sm-1 ~ .col-sm-12 | 平板设备(768 < screen < 970)
.col-md-1 ~ .col-md-12 | PC小屏 (970 < screen < 1200)
.col-lg-1 ~ .col-lg-12 | PC大屏 (1200 < screen )
.col-xs-offset-1 ~ .col-xs-offset-12 | 手机设备列偏移
.col-sm-offset-1 ~ .col-sm-offset-12 | 平板设备列偏移
.col-md-offset-1 ~ .col-md-offset-12 | PC小屏列偏移
.col-lg-offset-1 ~ .col-lg-offset-12 | PC大屏列偏移
.hidden-xs | 手机设备隐藏指定列
.hidden-sm | 平板设备隐藏指定列
.hidden-md | PC小屏隐藏指定列
.hidden-lg | PC大屏隐藏指定列

#### 示例
```
# 12列
<div class="container">
	<div class="row">
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	</div>
</div>

# 2列
<div class="container">
	<div class="row">
		<div class="col-md-4">.col-md-4</div>
		<div class="col-md-8">.col-md-8</div>
	</div>
	<div class="row">
		<div class="col-md-6">.col-md-6</div>
		<div class="col-md-6">.col-md-6</div>
	</div>
</div>

# 3列
<div class="container">
	<div class="row">
		<div class="col-md-4">.col-md-4</div>
		<div class="col-md-4">.col-md-4</div>
		<div class="col-md-4">.col-md-4</div>
	</div>
</div>

# 多种设备
<div class="row">
	<div class="col-xs-12 col-sm-6 col-md-8">.col-xs-12 .col-sm-6 .col-md-8</div>
	<div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
</div>
<div class="row">
	<div class="col-xs-6 col-sm-4">.col-xs-6 .col-sm-4</div>
	<div class="col-xs-6 col-sm-4">.col-xs-6 .col-sm-4</div>
	<div class="col-xs-6 col-sm-4">.col-xs-6 .col-sm-4</div>
</div>
```

## 浏览器支持情况(Browser support)

![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![IE](https://raw.github.com/alrra/browser-logos/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) |
--- | --- | --- | --- | --- | --- |
Latest √ | Latest √ | Latest √ | Latest √ | Latest √| 8+ √






