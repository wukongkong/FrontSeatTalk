## HTML5基础大纲

### 标签和对象

语义化元素

-	`<header>`
-	`<footer>`
-	`<section>`
-	...

`<video>`

-	支持的三种格式
-	可通过DOM操作来实现暂停/播放/画面的大小

`<audio>`

-	支持三种格式

`<drag>`和`<drop>`


-	三个步骤：
	-	拖动什么
	-	放在哪里
	-	推动处理			

**`<canvas>`**

-	本身只是设定一块画布区域
-	与js结合完成绘图
	-	基本事例
	-	`context`对象

**`<svg>`**

-	是什么
-	基础事例
-	与其他图像格式的区别与优势
-	有`<canvas>`的区别和不同的应用场景

`Geolocation对象`

-	`.getCurrentPosition(callback1,callback2)`
	-	返回对象
	-	callback1
		-	成功获取地理位置后的操作
	-	callback2
		-	为获取地理位置后的错误返回		
-	其余方法

存储数据

-	localStorage
-	sessionStorage
-	与cookie的区别和不同的应用场景

### 表单

input

-	新增类型

新增标签

-	datalist
-	keygen
-	output

input和form新属性

-	input
-	form

### 数据推送
-	webSocket
-	SSE
-	区别于应用场景

### HTML5推荐工具
-	Modernizr
-	...
