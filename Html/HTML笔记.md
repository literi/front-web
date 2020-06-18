HTML 指的是超文本标记语言（英语：HyperText Markup Language），是用来描述网页的一种语言。

- HTML 不是一种编程语言，而是一种标记语言，它有一套标记标签 。
- HTML 使用标记标签来描述网页。
- HTML 文档包含了 HTML 标签及文本内容，HTML文档也叫做 Web 页面。

----------
### HTML发展史 ###

HTML没有1.0，因为关于它的初版存在争议，1995年HTML 2.0面世，1997年由国际官方组织W3C推出了HTML 3.2以及HTML 4.0标准，后面W3C(万维网联盟)也渐渐变成Web技术领域的权威，经过漫长的演变，2014年，HTML 5标准最终面世。

- HTML 2.0——1995年11月，RFC 1866发布
- HTML 3.2——1997年1月14日，W3C发布推荐标准
- HTML 4.0——1997年12月18日，W3C发布推荐标准
- HTML 4.01——1999年12月24日，W3C发布推荐标准
- HTML 5——2014年10月28日，W3C发布推荐标准

----------
### HTML结构 ###

HTML的结构一般包括<head>标签和<body>标签，<head>和<body>这2个标记符分别表示网页的头部和正文。头部中可包含页面的标题、关键词、描述说明等内容，它本身不作为内容来显示，但影响网页显示的效果。<body></body>当中是网页实际显示的内容，正文标记符又被称为实体标记。页面当中通常包含有很多指向其他相关页面或其他节点的指针，通过点击，可以很方便地获取新的网页，这是HTML获得广泛推广运用最重要的原因之一，而由这些相互之间存在关联的页面组成的有机集合便是网站。

究竟HTML为什么会被普及?这就要归功于互联网的高速发展，对于编程语言的需求直线上升。而HTML5具有超集方式的简易性、运用广泛的可拓展性、灵活应变的平台适应性以及简单的通用性。凭借着这些特性，HTML越来越受到人们的喜爱。

----------
### HTML5编辑规范 ###

1. 文件拓展名默认使用htm或者html，便于操作系统或者程序辨认文件，而图片则基本上存为gif或jpg
2. 浏览器默认忽视回车符，不过为了方便阅览，人们还是会习惯地在写完一段代码后进行回车
3. 标记符号用尖括号括起来，带斜杠的元素表示该标记说明结束，大多数标记符必须成对使用，用以说明起始和结束。
4. 必须使用半角而不是全角字符
5. HTML注释<!--注释内容-->的内容不给予显示。

----------
### HTML 基础 ###

HTML 元素语法

- HTML 元素以开始标签起始
- HTML 元素以结束标签终止
- 元素的内容是开始标签与结束标签之间的内容
- 某些 HTML 元素具有空内容（empty content）
- 空元素在开始标签中进行关闭（以开始标签的结束而结束）
- 大多数 HTML 元素可拥有属性

HTML 属性

- HTML元素可以设置属性
- 属性可以在元素中添加附加信息
- 属性一般描述于开始标签
- 属性总是以名称/值对的形式出现，比如：name="value"。

----------
### HTML标题 ###

HTML标题（Heading）是通过`<h1> - <h6>` 标签来定义的。 `<h1>`定义最大的标题。`<h6>` 定义最小的标题。

----------
### HTML 水平线 ###

HTML 水平线 ：`<hr>` 标签在 HTML 页面中创建水平线。

----------
### HTML 注释 ###

HTML 注释 ：可以将注释插入 HTML 代码中，这样可以提高其可读性，使代码更易被人理解。浏览器会忽略注释，也不会显示它们。`<!-- 这是一个注释 -->`

----------
### HTML段落 ###

HTML段落是通过标签`<p>`来定义的。（</ p>是块级元素）

----------
### HTML折行 ###

HTML折行 ：`<br />`标签定义为一个换行符，它可以理解为简单的输入一个空行，而不是用来对内容进行拆分

----------
### HTML 文本格式化 ###

HTML 文本格式化 ：HTML 中存在一些格式化文本的标签，它们可以被直接使用，而不用您再去写样式进行调整。HTML 使用标签 `<b>`("bold") 与 `<i>`("italic") 对输出的文本进行格式，如：**粗体** or *斜体*

	通常标签 <strong> 替换加粗标签 <b> 来使用，<em> 替换 <i>标签使用。
	然而，这些标签的含义是不同的：
	<b> 与<i> 定义粗体或斜体文本。
	<strong> 或者 <em> 意味着你要呈现的文本是重要的，所以要突出显示。

	HTML文本格式化标签
	标签			描述
	<b>			定义粗体文本
	<em>		定义着重文字
	<i>			定义斜体字
	<small>		定义小号字
	<strong>	定义加重语气
	<sub>		定义下标字
	<sup>		定义上标字
	<ins>		定义插入字
	<del>		定义删除字

	HTML "计算机输出" 标签
	标签			描述
	<code>		定义计算机代码
	<kbd>		定义键盘码
	<samp>		定义计算机代码样本
	<var>		定义变量
	<pre>		定义预格式文本
	
	HTML 引文, 引用, 及标签定义
	标签				描述
	<abbr>			定义缩写
	<address>		定义地址
	<bdo>			定义文字方向
	<blockquote>	定义长的引用
	<q>				定义短的引用语
	<cite>			定义引用、引证
	<dfn>			定义一个定义项目。

----------
### HTML 链接 ###

HTML 链接是通过标签`<a>`来定义的。可以从一个页面指向另一个目的端的链接。超链接可以是一个字，一个词，或者一组词，也可以是一幅图像，您可以点击这些内容来跳转到新的文档或者当前文档中的某个部分。在标签`<a>`中使用了href属性来描述链接的地址。

	HTML 空链接：指指向链接后，鼠标变成手形，但单击后仍停留在当前页面。
	<a href="#">链接文字</a>
	
HTML 链接 - **target 属性**

	使用 Target 属性，你可以定义被链接的文档在何处显示（在新的窗口打开，还是在原有的窗口中打开）。
	如果将 target 属性设置为 "_blank" 则文档就会在新窗口打开, "_self"(当前页面打开）
	HTML 链接语法 : <a href="//www.baidu.com/" target="_blank">百度</a>

HTML 链接 - **id 属性**

	id 属性可用于在一个 HTML 文档中创建书签标记。

	在HTML文档中插入ID:   
	<a id="tips">Useful Tips Section</a>
	在HTML文档中创建一个链接到"有用的提示部分(id="tips"）"：    
	<a href="#tips">Visit the Useful Tips Section</a>
	或者，从另一个页面创建一个链接到"有用的提示(id="tips"）部分"：  
	<a href="//网页地址#tips"> Visit the Useful Tips Section</a>

----------
### HTML头部 ###

**HTML `<head>` 元素** ：`<head>` 元素包含了所有的头部标签元素。在 <head>元素中你可以插入脚本（scripts）, 样式文件（CSS），及各种 meta 信息。可以添加在头部区域的元素标签为: `<title>, <style>, <meta>, <link>, <script>, <noscript> `和 `<base>`。`<head> `元素描述了文档的各种属性和信息，其中包括文档的标题、在 Web 中的位置以及和其他文档的关系等。

**HTML `<title>` 元素** ：`<title>` 标签定义了不同文档的标题。`<title>` 在 HTML/XHTML 文档中是必须的。`<title>` 元素 ：

- 定义了浏览器工具栏的标题
- 当网页添加到收藏夹时，显示在收藏夹中的标题
- 显示在搜索引擎结果页面的标题

**HTML `<base>` 元素** ：`<base>` 标签描述了基本的链接地址/链接目标，该标签作为HTML文档中所有的链接标签的默认链接

**HTML `<link>` 元素** ：`<link>` 标签定义了文档与外部资源之间的关系。`<link>` 标签通常用于链接到样式表: 
     
	<link rel="stylesheet" type="text/css" href="mystyle.css">

**HTML `<style>` 元素** ：`<style>` 标签定义了HTML文档的样式文件引用地址。在`<style>` 元素中你需要指定样式文件来渲染HTML文档:

	<style type="text/css">
		body {background-color:yellow}
		p {color:blue}
	</style>

**HTML `<meta>` 元素** ：meta标签描述了一些基本的元数据。`<meta>` 标签提供了元数据。元数据也不显示在页面上，但会被浏览器解析。META元素通常用于指定网页的描述，关键词，文件的最后修改时间，作者，和其他元数据。元数据可以使用于浏览器（如何显示内容或重新加载页面），搜索引擎（关键词），或其他Web服务。`<meta>`一般放置于 `<head>`区域

`<meta>` 标签- 使用实例

	为搜索引擎定义关键词:
	<meta name="keywords" content="HTML, CSS, XML, XHTML, JavaScript">
	为网页定义描述内容:
	<meta name="description" content="Web tutorials on HTML">
	定义网页作者:
	<meta name="author" content="Author">
	每30秒钟刷新当前页面:
	<meta http-equiv="refresh" content="30">

**HTML `<script>` 元素** ：`<script>`标签用于加载脚本文件，如：JavaScript。

----------
### HTML空格 ###

**HTML中的空格**: 在代码中可能包含了很多的空格——这是没有必要的。无论你用了多少空格（包括空格字符，包括换行），当渲染这些代码的时候，HTML解释器会将连续出现的空格字符减少为一个单独的空格符。代码中空格可以用`&nbsp;`实现

----------
### HTML 图像 ###

HTML 图像是通过标签`<img>`来定义的。使用img元素来为你的网站添加图片，使用src 属性指向一个图片的具体地址。请注意：img元素是自关闭元素，不需要结束标记。

图像标签（`<img>`）和**源属性（Src）**

`<img>`是空标签，意思是说，它只包含属性，并且没有闭合标签。要在页面上显示图像，你需要使用源属性（src）。src指 "source"。源属性的值是图像的 URL 地址。

**Alt属性** ：alt属性用来为图像定义一串预备的可替换的文本。在浏览器无法载入图像时，替换文本属性告诉读者他们失去的信息。此时，浏览器将显示这个替代性的文本而不是图像。为页面上的图像都加上替换文本属性是个好习惯，这样有助于更好的显示信息，并且对于那些使用纯文本浏览器的人来说是非常有用的。

	定义图像的语法是：
	<img src="url" alt="some_text">

**设置图像的高度与宽度** ：height（高度）与width（宽度）属性用于设置图像的高度与宽度。（属性值默认单位为像素）

	<img src="pulpit.jpg" alt="Pulpit rock" width="304" height="228">
**提示**: 指定图像的高度和宽度的一个很好的习惯。如果图像指定了高度宽度，页面加载时就会保留指定的尺寸。如果没有指定图片的大小，加载页面时有可能会破坏HTML页面的整体布局。

**设置图像边框** ：在`<img>`标签中您可以使用border属性以像素为单位指定边框粗细。厚度为 0 表示图片周围没有边框。

	<img src="/statics/images/course/pulpit.jpg" alt="Pulpit rock" border = "3">

**设置图像对齐** ：默认情况下，图像在页面中将显示为左侧对齐，在<img>标签中您可以使用align属性将设置图像的对齐方式：center(居中)或right(右侧)。

	<img src="/statics/images/course/pulpit.jpg" alt="Pulpit rock" align="right">
**注意:** 

1. 假如某个 HTML 文件包含十个图像，那么为了正确显示这个页面，需要加载 11 个文件。加载图片是需要时间的，所以我们的建议是：慎用图片。
2. 加载页面时，要注意插入页面图像的路径，如果不能正确设置图像的位置，浏览器无法加载图片，图像标签就会显示一个破碎的图片。

------
### HTML 表格 ###

表格由`<table>`标签来定义。每个表格均有若干行（由`<tr>`标签定义），每行被分割为若干单元格（由`<td>`标签定义）。字母 td 指表格数据（table data），即数据单元格的内容。数据单元格可以包含文本、图片、列表、段落、表单、水平线、表格等等。

	HTML 表格的基本结构： 
	<table>…</table>：定义表格
	<th>…</th>：定义表格的标题栏（文字加粗） 
	<tr>…</tr>：定义表格的行
	<td>…</td>：定义表格的列

**HTML 表格和边框属性** ：如果不定义边框属性，表格将不显示边框。有时这很有用，但是大多数时候，我们希望显示边框。使用边框属性**border**来显示一个带有边框的表格

**HTML 表格表头单元格** ：表格的表头单元格使用`<th>`标签进行定义。表格的表头单元格属性主要是一些公共属性，如：align、dir、width、height。大多数浏览器会把表头显示为粗体居中的文本

**表格标题`<caption>`** ：在`<table>`标签中我们可以使用`<caption> ... </ caption>`标签作为标题，并在表的顶部显示出来。注：此标签在较新版本的HTML / XHTML中已弃用

**HTML表格高度和宽度** ：在`<table>`标签中您可以使用width（宽）和height（高）属性设置表格宽度和高度。您可以按像素或可用屏幕区域的百分比来指定表格宽度或高度。

**HTML表格背景** ：您可以使用以下方法之一设置HTML表格的背景 

	bgcolor属性 - 可以为整个表格或仅为一个单元格设置背景颜色。
	background属性 - 可以为整个表设置背景图像或仅为一个单元设置背景图像。
	bordercolor属性 - 可以设置边框颜色。

	注：HTML5中不推荐使用bgcolor，background和bordercolor属性。不要使用这些属性。 

**HTML表格空间** ：有以下两个属性，用于调整HTML表格中单元格的空间：

	cellspacing属性-定义表格单元格之间的空间 
	cellpadding属性-表示单元格边框与单元格内容之间的距离

**HTML合并单元格** ：如果要将两个或多个列合并为一个列，将使用colspan属性。如果要合并两行或更多行，则将使用rowspan属性。

**HTML表格头部、主体、页脚** ：表格可以分为三个部分 ：头部，主体和页脚，如同word文档中页面的页眉、正文、页脚。每个页面保持相同，而正文是表格的主要内容持有者。

	头部，主体和页脚的对应的三个标签是：
	<thead> - 创建单独的表头。
	<tbody> - 表示表格的主体。
	<tfoot> - 创建一个单独的表页脚。
表可以包含多个`<tbody>`元素以指示不同的页面。但值得注意的是`<thead>`和`<tfoot>`标签应出现在`<tbody>`之前

**HTML表格的嵌套** ：您可以在另一个表中使用一个表。可以使用<table>内的几乎所有标签。

**HTML 表格标签**

	标签				描述
	<table> 		定义表格
	<th> 			定义表格的表头
	<tr> 			定义表格的行
	<td> 			定义表格单元
	<caption> 		定义表格标题
	<colgroup> 		定义表格列的组
	<col> 			定义用于表格列的属性
	<thead> 		定义表格的页眉
	<tbody> 		定义表格的主体
	<tfoot> 		定义表格的页脚

----------
### HTML 列表 ###

HTML 支持有序、无序和定义列表:

**HTML无序列表** ：无序列表是一个项目的列表，此列项目使用粗体圆点（典型的小黑圆圈）进行标记。 无序列表适合成员之间无级别顺序关系的情况。无序列表使用 `<ul>` 标签
	
	 <ul>
		 <li>Coffee</li>
		 <li>Milk</li>
	 </ul>

**HTML 有序列表** ：同样，有序列表也是一列项目，列表项目使用数字进行标记。 有序列表始于 `<ol>` 标签。每个列表项始于 `<li>` 标签。有序列表适合各项目之间存在顺序关系的情况。列表项项使用数字来标记。

	 <ol>
		 <li>Coffee</li>
		 <li>Milk</li>
	 </ol> 

**HTML 自定义列表** ：自定义列表不仅仅是一列项目，而是项目及其注释的组合。自定义列表以 `<dl>` 标签开始。每个自定义列表项以 `<dt>` 开始。每个自定义列表项的定义以 `<dd>` 开始。自定义列表中的一个术语名可以对应多重定义或者多个术语名对应同一个定义，如果只有也术语名或者只有定义也是可行的，也就是说 `<dt>` 与 `<dd>` 在其中数量不限、对应关系不限。

	 <dl>
		 <dt>Coffee</dt>
		 <dd>- black hot drink</dd>
		 <dt>Milk</dt>
		 <dd>- white cold drink</dd>
	 </dl> 

浏览器显示如下：

![](https://s1.ax1x.com/2020/06/17/NExVqf.png)

提示: 列表项内部可以使用段落、换行符、图片、链接以及其他列表等等

**HTML列表标签**

	标签			描述
	<ol>		定义有序列表
	<ul>		定义无序列表
	<li>		定义列表项
	<dl>		定义列表
	<dt>		自定义列表项目
	<dd>		定义自定义列表的描述

----------
### HTML 区块 ###

HTML `<div>` 和`<span>` : HTML可以通过 `<div>` 和 `<span>` 将元素组合起来。

HTML 区块元素  
大多数 HTML 元素被定义为块级元素或内联元素。块级元素在浏览器显示时，通常会以新行来开始（和结束）。实例: `<h1>, <p>, <ul>, <table>` 

HTML 内联元素  
内联元素在显示时通常不会以新行开始。实例: `<b>, <td>, <a>, <img>`

HTML `<div>` 元素  
`<div>` 标签可以把文档分割为独立的、不同的部分。  
HTML `<div>` 元素是块级元素，它是可用于组合其他 HTML 元素的容器。  
`<div>` 元素没有特定的含义。除此之外，由于它属于块级元素，浏览器会在其前后显示折行。  
如果与 CSS 一同使用，`<div>` 元素可用于对大的内容块设置样式属性。  
`<div> `元素的另一个常见的用途是文档布局。它取代了使用表格定义布局的老式方法。使用 `<table>` 元素进行文档布局不是表格的正确用法。`<table>` 元素的作用是显示表格化的数据。  

HTML `<span>` 与元素  
HTML `<span>` 元素是内联元素，可用作文本的容器  
`<span>` 元素也没有特定的含义。  
当与 CSS 一同使用时，`<span>` 元素可用于为部分文本设置样式属性。  

----------
### HTML 布局 ###

大多数网站可以使用 `<div>` 或者 `<table>` 元素来创建多列。CSS 用于对元素进行定位，或者为页面创建背景以及色彩丰富的外观。

虽然我们可以使用HTML table标签来设计出漂亮的布局，但是table标签是不建议作为布局工具使用的 - 表格不是布局工具。

Tip: 使用 CSS 最大的好处是，如果把 CSS 代码存放到外部样式表中，那么站点会更易于维护。通过编辑单一的文件，就可以改变所有页面的布局。  
由于创建高级的布局非常耗时，使用模板是一个快速的选项。通过搜索引擎可以找到很多免费的网站模板（您可以使用这些预先构建好的网站布局，并优化它们）。

----------
### HTML 表单和输入 ###

HTML 表单用于收集不同类型的用户输入。  
表单是一个包含表单元素的区域。表单元素是允许用户在表单中输入内容，比如：文本域(textarea)、下拉列表、单选框(radio-buttons)、复选框(checkboxes)等等。表单使用表单标签 `<form>` 来设置。

**输入元素**

多数情况下被用到的表单标签是输入标签（`<input>`）。`<input>` 元素是最重要的表单元素。  
输入类型是由类型属性（type）定义的。大多数经常被用到的输入类型如下：  
**文本域（Text Fields）** ：文本域通过`<input type="text">` 标签来设定，当用户要在表单中键入字母、数字等内容时，就会用到文本域。  
注意 : 表单本身并不可见。同时，在大多数浏览器中，文本域的缺省宽度是20个字符。  
**密码字段** ：密码字段通过标签`<input type="password">` 来定义  
注意 : 密码字段字符不会明文显示，而是以星号或圆点替代。  
**单选按钮（Radio Buttons）** ： `<input type="radio">` 标签定义了表单单选框选项。

	<form>
		<input type="radio" name="sex" value="male">Male<br>
		<input type="radio" name="sex" value="female">Female
	</form>
注意 ：同一组的name属性的值要保持一致  
**复选框（Checkboxes）** ： `<input type="checkbox">` 定义了复选框. 用户需要从若干给定的选择中选取一个或若干选项。

	<form>
		<input type="checkbox" name="vehicle" value="Bike">I have a bike<br>
		<input type="checkbox" name="vehicle" value="Car">I have a car 
	</form> 
注意 ：同一组的name属性的值要保持一致  
**提交按钮(Submit Button)** ：`<input type="submit">` 定义了提交按钮.当用户单击确认按钮时，表单的内容会被传送到另一个文件。表单的动作属性定义了目的文件的文件名。由动作属性定义的这个文件通常会对接收到的输入数据进行相关的处理。

	<form name="input" action="html_form_action.php" method="get">
		Username: <input type="text" name="user">
		<input type="submit" value="Submit">
	</form> 
展示结果：  
Username: <input type="text" name="user">
<input type="submit" value="Submit">  

HTML表单标签

	标签					描述
	<form>				定义供用户输入的表单
	<input>				定义输入域
	<textarea>			定义文本域 (一个多行的输入控件)
	<label>				定义了 <input> 元素的标签，一般为输入标题
	<fieldset>			定义了一组相关的表单元素，并使用外框包含起来
	<legend>			定义了 <fieldset> 元素的标题
	<select>			定义了下拉选项列表
	<optgroup>			定义选项组
	<option>			定义下拉列表中的选项
	<button>			定义一个点击按钮
	<datalist>	New		指定一个预先定义的输入控件选项列表
	<keygen>	New		定义了表单的密钥对生成器字段
	<output>	New		定义一个计算结果
	New:HTML5新标签

----------
### HTML 框架 ###

`<iframe>`标签规定一个内联框架。  
一个内联框架被用来在当前 HTML 文档中嵌入另一个文档。  
通过使用框架，你可以在同一个浏览器窗口中显示不止一个页面。  
iframe语法:   

	<iframe src="URL"></iframe>
该URL指向不同的网页。将窗口内容显示为URL地址指向页面。

**Iframe - 设置高度与宽度**

height和width属性用来定义iframe标签的高度与宽度。  
属性默认以像素为单位, 但是你可以指定其按比例显示 (如："80%").  

	<iframe src="URL" width="200" height="200"></iframe>

**Iframe - 移除边框**

frameborder属性用于定义iframe表示是否显示边框。  
设置属性值为 "0" 移除iframe的边框:
	
	<iframe src="URL" frameborder="0"></iframe>

**使用iframe来显示目录链接页面**

iframe可以显示一个目标链接的页面  
目标链接的属性必须使用iframe的属性，如下实例:

	<iframe src="URL" name="iframe_a"></iframe> 
	<p><a href="http://www.baidu.com" target="iframe_a">百度</a></p>

iframe 标准属性

	属性 				说明
	class 			规定元素的类名（classname） 
	id 				规定元素的唯一 id 
	style 			规定元素的行内样式（inline style） 
	title 			规定元素的额外信息（可在工具提示中显示）

----------
### HTML 颜色 ###

HTML 颜色采用的是 RGB 颜色，是通过对红(R)、绿(G)、蓝(B)三个颜色通道的变化以及它们相互之间的叠加来得到各式各样的颜色的，RGB即是代表红、绿、蓝三个通道的颜色。   
HTML 颜色由一个十六进制符号来定义，这个符号由红色、绿色和蓝色的值组成（RGB）。 
每种颜色的最小值是0（十六进制：#00）。最大值是255（十六进制：#FF）。   
三种颜色 红，绿，蓝的组合从0到255，一共有1600万种不同颜色(256 x 256 x 256)。  
 
Web安全色?   
数年以前，当大多数计算机仅支持 256 种颜色的时候，一系列 216 种 Web 安全色作为 Web 标准被建议使用。其中的原因是，微软和 Mac 操作系统使用了 40 种不同的保留的固定系统颜色（双方大约各使用 20 种）。   
我们不确定如今这么做的意义有多大，因为越来越多的计算机有能力处理数百万种颜色，不过做选择还是你自己。  
最初，216 跨平台 web 安全色被用来确保：当计算机使用 256 色调色板时，所有的计算机能够正确地显示所有的颜色。

**HTML 颜色名**

目前所有浏览器都支持以下颜色名。  
141个颜色名称是在HTML和CSS颜色规范定义的（17标准颜色，再加124）。  
17标准颜色：黑色，蓝色，水，紫红色，灰色，绿色，石灰，栗色，海军，橄榄，橙，紫，红，白，银，蓝绿色，黄色。

**颜色值**

颜色值由十六进制来表示红、绿、蓝（RGB）。  
每个颜色的最低值为0(十六进制为00)，最高值为255(十六进制为FF)。  
十六进制值的写法为#号后跟三个或六个十六进制字符。  
三位数表示法为：#RGB，转换为6位数表示为：#RRGGBB。  

![](https://s1.ax1x.com/2020/06/17/NVyCAe.png)

----------
### HTML 脚本 ###

JavaScript 是可插入 HTML 页面的编程代码。  
JavaScript 使 HTML 页面具有更强的动态和交互性。  
JavaScript 插入 HTML 页面后，可由所有的现代浏览器执行。  

**HTML `<script>` 标签**

`<script>` 标签用于定义客户端脚本，比如 JavaScript。  
`<script>` 元素既可包含脚本语句，也可通过 src 属性指向外部脚本文件。  
JavaScript 最常用于图片操作、表单验证以及内容动态更新。  
注释：如果使用 "src" 属性，则 `<script>` 元素必须是空的。

**HTML`<noscript>` 标签**

`<noscript>` 标签提供无法使用脚本时的替代内容，比方在浏览器禁用脚本时，或浏览器不支持客户端脚本时。  
`<noscript>`元素可包含普通 HTML 页面的 body 元素中能够找到的所有元素。  
只有在浏览器不支持脚本或者禁用脚本时，才会显示 `<noscript>` 元素中的内容

	<script>
		document.write("Hello World!")
	</script>
	<noscript>Sorry, your browser does not support JavaScript!</noscript>

>JavaScript实例代码:  
>
	JavaScript可以直接在HTMl输出: 
	document.write("<p>This is a paragraph</p>"); 
>
	JavaScript事件响应: 
	<button type="button" onclick="myFunction()">Click Me!</button>
>
	JavaScript处理 HTML 样式: 
	document.getElementById("demo").style.color="#ff0000";

----------
### HTML 字符实体 ### 

HTML 中的预留字符必须被替换为字符实体。  
一些在键盘上找不到的字符也可以使用字符实体来替换。

**HTML 实体**

在 HTML 中，某些字符是预留的。您不能使用包含这些字符的文本。  
在 HTML 中不能使用小于号（<）和大于号（>），这是因为浏览器会误认为它们是标签。  
如果希望正确地显示预留字符，我们必须在 HTML 源代码中使用字符实体（character entities）。  
如需显示小于号，我们必须这样写：`&lt; 或 &#60; 或 &#060;`   
提示： 使用实体名而不是数字的好处是，名称易于记忆。不过坏处是，浏览器也许并不支持所有实体名称（对实体数字的支持却很好）。

**不间断空格(Non-breaking Space)**

HTML 中的常用字符实体是不间断空格( )。  
浏览器总是会截短 HTML 页面中的空格。如果您在文本中写 10 个空格，在显示该页面之前，浏览器会删除它们中的 9 个。如需在页面中增加空格的数量，您需要使用`&nbsp;`字符实体。

**结合音标符**

发音符号是加到字母上的一个"glyph(字形)"。  
一些变音符号, 如 尖音符 ( ̀ ) 和 抑音符 ( ́ )。  
变音符号可以出现字母的上面和下面，或者字母里面，或者两个字母间。  
变音符号可以与字母、数字字符的组合来使用。

**HTML字符实体**
 
注意 ：实体名称对大小写敏感！

![](https://s1.ax1x.com/2020/06/17/NV5qlF.png)

----------
### HTML URL ###

HTML 统一资源定位器(Uniform Resource Locators) 

URL是一个网页地址。  
URL可以由字母组成，如"www.baidu.com"，或互联网协议（IP）地址： 192.68.20.50。大多数人进入网站使用网站域名来访问，因为名字比数字更容易记住。

**URL - 统一资源定位器**

Web浏览器通过URL从Web服务器请求页面。  
当您点击 HTML 页面中的某个链接时，对应的 `<a>` 标签指向万维网上的一个地址。  
一个统一资源定位器(URL) 用于定位万维网上的文档。      
语法规则:

	scheme://host.domain:port/path/filename 
>说明 :  
>scheme - 定义因特网服务的类型。最常见的类型是 http  
>host - 定义域主机（http 的默认主机是 www）  
>domain - 定义因特网域名，比如 baidu.com  
>:port - 定义主机上的端口号（http 的默认端口号是 80）  
>path - 定义服务器上的路径（如果省略，则文档必须位于网站的根目录中）。  
>filename - 定义文档/资源的名称

常见的 URL Schemes

	Scheme			访问								用于...
	http		超文本传输协议				以 http:// 开头的普通网页。不加密。
	https		安全超文本传输协议			安全网页，加密所有信息交换。
	ftp			文件传输协议					用于将文件下载或上传至网站。
	file										您计算机上的文件。

**URL 字符编码**  

URL 只能使用 ASCII 字符集。  
URL 编码会将字符转换为可通过因特网传输的格式。来通过因特网进行发送，由于 URL 常常会包含 ASCII 集合之外的字符，URL 必须转换为有效的 ASCII 格式。  
URL 编码使用 "%" 其后跟随两位的十六进制数来替换非 ASCII 字符。  
URL 不能包含空格。URL 编码通常使用 + 来替换空格。

----------
### HTML 速查列表 ### 

**HTML 基本文档**

	<!DOCTYPE html>
	<html>
	<head>
	<title>文档标题</title>
	</head>
	<body> 可见文本... </body>
	</html>

**基本标签（Basic Tags）**

	<h1>最大的标题</h1>
	<h2> . . . </h2>
	<h3> . . . </h3>
	<h4> . . . </h4>
	<h5> . . . </h5>
	<h6>最小的标题</h6>
	 
	<p>这是一个段落。</p>
	<br> （换行）
	<hr> （水平线）
	<!-- 这是注释 -->

**文本格式化（Formatting）**

	<b>粗体文本</b>
	<code>计算机代码</code>
	<em>强调文本</em>
	<i>斜体文本</i>
	<kbd>键盘输入</kbd> 
	<pre>预格式化文本</pre>
	<small>更小的文本</small>
	<strong>重要的文本</strong>
 
	<abbr> （缩写）
	<address> （联系信息）
	<bdo> （文字方向）
	<blockquote> （从另一个源引用的部分）
	<cite> （工作的名称）
	<del> （删除的文本）
	<ins> （插入的文本）
	<sub> （下标文本）
	<sup> （上标文本）

**链接（Links）**

	普通的链接：<a href="链接地址">链接文本</a>
	图像链接： <a href="http://www.example.com/"><img src="URL" alt="替换文本"></a> 
	邮件链接： <a href="mailto:webmaster@example.com">发送e-mail</a>
	书签： <a id="tips">
	提示部分</a> <a href="#tips">跳到提示部分</a>

**图片（Images）**

	<img src="URL" alt="替换文本" height="42" width="42">
	
**样式/区块（Styles/Sections）**
	
	<style type="text/css">
	   h1 {color:red;}
	   p {color:blue;}
	 </style>
	 
	 <div>文档中的块级元素</div>
	 <span>文档中的内联元素</span>

**无序列表**

	<ul>
	   <li>项目</li>
	   <li>项目</li>
	 </ul>

**有序列表**

	<ol>
	   <li>第一项</li>
	   <li>第二项</li>
	 </ol>

**定义列表**

	<dl>
	   <dt>项目 1</dt>
	     <dd>描述项目 1</dd>
	   <dt>项目 2</dt>
	     <dd>描述项目 2</dd>
	 </dl>

**表格（Tables）**

	<table border="1">
	  <tr>
	    <th>表格标题</th>
	    <th>表格标题</th>
	  </tr>
	  <tr>
	    <td>表格数据</td>
	    <td>表格数据</td>
	  </tr>
	</table>

**框架（Iframe）**

	<iframe src="demo_iframe.htm"></iframe>

**表单（Forms）**

	<form action="demo_form.php" method="post/get">
	
		<input type="text" name="email" size="40" maxlength="50"> 
		<input type="password"> 
		<input type="checkbox" checked="checked"> 
		<input type="radio" checked="checked"> 
		<input type="submit" value="Send"> 
		<input type="reset"> 
		<input type="hidden"> 
		
		<select> 
			<option>苹果</option> 
			<option selected="selected">香蕉</option> 
			<option>樱桃</option> 
		</select>
		
		<textarea name="comment" rows="60" cols="20">
		</textarea> 
	</form>

**实体（Entities）**

	&lt; 等同于 <
	&gt; 等同于 >
	&copy; 等同于 ©

----------
### HTML 媒体(Media) ###

**HTML 多媒体** 

Web 上的多媒体指的是音效、音乐、视频和动画。  
现代网络浏览器已支持很多多媒体格式。

**什么是多媒体？**  
多媒体来自多种不同的格式。它可以是您听到或看到的任何内容，文字、图片、音乐、音效、录音、电影、动画等等。  
在因特网上，您会经常发现嵌入网页中的多媒体元素，现代浏览器已支持多种多媒体格式。     

**浏览器支持**  
第一款因特网浏览器只支持文本，而且即使是对文本的支持也仅限于单一字体和单一颜色。随后诞生了支持颜色、字体和文本样式的浏览器，图片支持也被加入。  
不同的浏览器以不同的方式处理对音效、动画和视频的支持。某些元素能够以内联的方式处理，而某些则需要额外的插件。  

**多媒体格式**  
格式 多媒体元素（比如视频和音频）存储于媒体文件中。  
确定媒体类型的最常用的方法是查看文件扩展名。当浏览器得到文件扩展名 .htm 或 .html 时，它会假定该文件是 HTML 页面。.xml 扩展名指示 XML 文件，而 .css 扩展名指示样式表。图片格式则通过 .gif 或 .jpg 来识别。  
多媒体元素也拥有带有不同扩展名的文件格式，比如 .swf、.wmv、.mp3 以及 .mp4。

**视频格式**
![](https://s1.ax1x.com/2020/06/18/Nmebg1.png)   
最新的 HTML5 标准只支持 MP4, WebM, 和 Ogg 视频格式。

**声音格式**  
MP3是一种音频压缩技术，其全称是动态影像专家压缩标准音频层面3（Moving Picture Experts Group Audio Layer III），简称为MP3。它被设计用来大幅度地降低音频数据量。如果你的站点是音乐类型的，你可以选择mp3格式。HTML5 的最新标准支持 MP3, WAV, 和 Ogg 音频格式。
![](https://s1.ax1x.com/2020/06/18/NmmM2n.png)

**HTML 插件** ： 插件的功能是扩展 HTML 浏览器的功能。

**HTML 助手（插件）**  
辅助应用程序（helper application）是可由浏览器启动的程序。辅助应用程序也称为插件。  
辅助程序可用于播放音频和视频（以及其他）。辅助程序是使用 `<object>` 标签来加载的。  
使用辅助程序播放视频和音频的一个优势是，您能够允许用户来控制部分或全部播放设置。  
插件可以通过 `<object>` 标签或者 `<embed>` 标签添加在页面中。object 和 embed 元素都通过添加对浏览器不直接支持的插件的支持来扩展浏览器的功能。   
大多数辅助应用程序允许对音量设置和播放功能（比如后退、暂停、停止和播放）的手工（或程序的）控制。  
我们可以使用 `<video>` 和 `<audio>` 标签来显示视频和音频

**object元素**  
所有主流浏览器都支持 `<object>` 标签。  
`<object>` 元素定义了在 HTML 文档中嵌入的对象。  
`<object>` 元素具有局部属性:data，type，height，width，usemap，name，form。  
该标签用于插入对象 (例如在网页中嵌入 Java 小程序, PDF 阅读器, Flash 播放器) 。  
	
	实例	<object width="400" height="50" data="bookmark.swf"></object>

`<object>` 元素同样可用于包含HTML文件：

	实例 <object width="100%" height="500px" data="snippet.html"></object>

或者插入一张图片:

	实例 <object data="logo.png"></object>

**embed 元素**   
所有主流浏览器都支持 `<embed>` 元素。`<embed>` 元素实现与 `<object>` 元素相同的结果。  
`<embed>` 元素表示一个 HTML Embed 对象 。  
`<embed>` 元素已经出现很长一段时间了，但是在 HTML5 前并未被详细说明，该元素在 HTML 5 页面上会被验证，在 HTML 4 上不会。    
注意 `<embed> `元素没有关闭标签。 不能使用替代文本。

	实例 <embed width="400" height="50" src="bookmark.swf">

`<embed>` 元素同样可用于包含 HTML 文件：

	实例 <embed width="100%" height="500px" src="snippet.html">

或者插入一张图片:

	实例 <embed src="logo.png"> 

**HTML 音频(Audio)**   
声音在HTML中可以以不同的方式播放.

**问题以及解决方法**  
在 HTML 中播放音频并不容易！  
您需要谙熟大量技巧，以确保您的音频文件在所有浏览器中（Internet Explorer, Chrome, Firefox, Safari, Opera）和所有硬件上（PC, Mac , iPad, iPhone）都能够播放。  

**使用插件**  
浏览器插件是一种扩展浏览器标准功能的小型计算机程序。  
插件可以使用 `<object>` 标签 或者 `<embed>` 标签添加在页面上.  
这些标签定义资源（通常非 HTML 资源）的容器，根据类型，它们即会由浏览器显示，也会由外部插件显示。

**使用插件**  
浏览器插件是一种扩展浏览器标准功能的小型计算机程序。  
插件可以使用 `<object>` 标签 或者 `<embed>` 标签添加在页面上.   
这些标签定义资源（通常非 HTML 资源）的容器，根据类型，它们即会由浏览器显示，也会由外部插件显示。

**使用 `<embed>` 元素**   
`<embed>`标签定义外部（非 HTML）内容的容器。（这是一个 HTML5 标签，在 HTML4 中是非法的，但是所有浏览器中都有效）。  
下面的代码片段能够显示嵌入网页中的 MP3 文件：

	实例 <embed height="50" width="100" src="horse.mp3">

**使用 `<object>` 元素**  
`<object>` 标签也可以定义外部（非 HTML）内容的容器。  
下面的代码片段能够显示嵌入网页中的 MP3 文件：  

	实例 <object height="50" width="100" data="horse.mp3"></object>

问题:  

- `<embed>` 标签在 HTML 4 中是无效的。页面无法通过 HTML 4 验证。
- 不同的浏览器对音频格式的支持也不同。
- 如果浏览器不支持该文件格式，没有插件的话就无法播放该音频。
- 如果用户的计算机未安装插件，无法播放音频。
- 如果把该文件转换为其他格式，仍然无法在所有浏览器中播放。

**使用 HTML5 `<audio>` 元素**  
HTML5 `<audio>` 元素是一个 HTML5 元素，在 HTML 4 中是非法的，但在所有浏览器中都有效。  
`<audio>`元素适用于所有现代浏览器。  
以下我们将使用 `<audio> `标签来描述 MP3 文件(Internet Explorer、Chrome 以及 Safari 中是有效的), 同样添加了一个 OGG 类型文件(Firefox 和 Opera浏览器中有效).如果失败，它会显示一个错误文本信息:

	实例
	<audio controls>
	  <source src="horse.mp3" type="audio/mpeg">
	  <source src="horse.ogg" type="audio/ogg">
	  Your browser does not support this audio format.
	</audio>

问题:  

- <audio> 标签在 HTML 4 中是无效的。您的页面无法通过 HTML 4 验证。
- 您必须把音频文件转换为不同的格式。
- <audio> 元素在老式浏览器中不起作用。

**最好的 HTML 解决方法**  
下面的例子使用了两个不同的音频格式。HTML5 `<audio>` 元素会尝试以 mp3 或 ogg 来播放音频。如果失败，代码将回退尝试 `<embed>` 元素。

	实例
	<audio controls height="100" width="100">
	  <source src="horse.mp3" type="audio/mpeg">
	  <source src="horse.ogg" type="audio/ogg">
	  <embed height="50" width="100" src="horse.mp3">
	</audio>

**雅虎媒体播放器 - 一个简单的添加音频到你网站上的方式**  
使用雅虎播放器是免费的。如需使用它，您需要把这段 JavaScript 插入网页底部：  
雅虎播放器可以播放MP3以及其他各种格式。你只需添加一行代码到你的页面或 博客中就可以轻松地将您的HTML页面制作成 专业的播放列表：  

	实例
	<a href="horse.mp3">Play Sound</a>
	
	<script src="http://mediaplayer.yahoo.com/latest"></script>

如果你要使用它，您需要把这段 JavaScript 插入网页底部：

	<script src="http://mediaplayer.yahoo.com/latest"></script>

然后只需简单地把 MP3 文件链接到您的 HTML 中，JavaScript 会自动地为每首歌创建播放按钮：

	<a href="song1.mp3">Play Song 1</a> 
	<a href="song2.wav">Play Song 2</a>
	...  
	...  

雅虎媒体播放器为您的用户提供的是一个小型的播放按钮，而不是完整的播放器。不过，当您点击该按钮，会弹出完整的播放器。  
请注意，这个播放器始终停靠在窗框底部。只需点击它，就可将其滑出。  

**使用超链接**  
如果网页包含指向媒体文件的超链接，大多数浏览器会使用"辅助应用程序"来播放文件。  
以下代码片段显示指向 mp3 文件的链接。如果用户点击该链接，浏览器会启动"辅助应用程序"来播放该文件：  

	实例	<a href="horse.mp3">Play the sound</a>

**内联的声音说明**  
当您在网页中包含声音，或者作为网页的组成部分时，它被称为内联声音。  
如果您打算在 web 应用程序中使用内联声音，您需要意识到很多人都觉得内联声音令人恼火。同时请注意，用户可能已经关闭了浏览器中的内联声音选项。  
我们最好的建议是只在用户希望听到内联声音的地方包含它们。一个正面的例子是，在用户需要听到录音并点击某个链接时，会打开页面然后播放录音。

**HTML 视频（Videos）**  
在 HTML 中播放视频的方法有很多种。  
可以使用 `<embed>` 标签、`<object>` 标签以及 `<video>` 标签（HTML 5中启用）。

**使用 HTML5 <video> 元素**  
HTML5 <video> 标签定义了一个视频或者影片.  
<video> 元素在所有现代浏览器中都支持。  
以下 HTML 片段会显示一段嵌入网页的 ogg、mp4 或 webm 格式的视频：  

	实例 
	<video width="320" height="240" controls>
	  <source src="movie.mp4" type="video/mp4">
	  <source src="movie.ogg" type="video/ogg">
	  <source src="movie.webm" type="video/webm">
	Your browser does not support the video tag.
	</video> 

Tip:   
ogg：带有 Theora 视频编码和 Vorbis 音频编码的 Ogg 文件  
mp4：带有 H.264 视频编码和 AAC 音频编码的 mp4 文件   
webm：带有 VP8 视频编码和 Vorbis 音频编码的 webm 文件   
问题:  
您必须把视频转换为很多不同的格式。  
`<video> `元素在老式浏览器中无效。

**最好的 HTML 解决方法**  
以下实例中使用了4种不同的视频格式。HTML 5 `<video>` 元素会尝试播放以 mp4、ogg 或 webm 格式中的一种来播放视频。如果均失败，则回退到 `<embed>` 元素。

	HTML 5 + <object> + <embed> :
	<video width="320" height="240" controls>
	  <source src="movie.mp4" type="video/mp4">
	  <source src="movie.ogg" type="video/ogg">
	  <source src="movie.webm" type="video/webm">
	  <object data="movie.mp4" width="320" height="240">
	    <embed src="movie.swf" width="320" height="240">
	  </object> 
	</video> 