<!DOCTYPE html>
<html>

	<head>
		<meta charset="UTF-8">
		<title>Web开发项目考核</title>
		<style type="text/css">
			/*整体内外边距0，字体颜色、大小，背景色*/
			body {
				margin: 0;
				padding: 0;
				border: 0;
				font-family: "宋体";
				font-size: 16px;
				background: #b0e0e6;
			}
			/*头部区背景,内边距*/
			header {
				background: gray;
				height: 50px;
				padding: 10px;
			}
			/*logo大小*/
			.logo {
				width: 120px;
				
			}
			/*导航区居右*/
			nav  {
				float: right;
			}
			/*导航列表项：浮动横排，间距*/
			.links li {
				float: right;
				margin: 15px;
			}
			/*导航颜色及变换，去下划线*/
			.links a {
				color: greenyellow;
				text-decoration:none;
			}
			
			/*内容区外边距*/
			article {
				margin: 10px;
			}
			/*内容区块内外边距、背景、阴影*/
			section {
				margin: 10px;
				padding: 20px;
				background:white ;
				color: grey;
				height: 800px;
			    box-shadow:5px 5px 10px 0px #636363 ;
			}
			/*区块标题大小、颜色*/
			section h2 {
				font-size: 20px;
				color: orange;
			}
			section h3 {
				font-size: 18px;
				color: darkgrey;
			}
			/*段落首行缩进*/
			section p {
				text-indent: 2em;
				color: grey;
			}
			/*作者 时间：颜色、间距*/
			.author,.addtime {
				color: darkgray;
				padding: 10px;
			}
			.content-header span {
				letter-spacing: 1px;
			}
			/*图片边框、阴影、鼠标悬停变形角度*/
			section img{
				width: 600px;
				border-radius: 20px;
				border: 2px dashed #f00;
				display: block;
				margin: auto;
				box-shadow:8px 8px 10px 0px #636363 ;
			}
			section img:hover{
				-webkit-transform:rotate(30deg);
			}
			/*内容区块一链接处理*/
			section #lj{
				text-decoration: none;
				color:	#458B00;
				font-size:20px;
			}
			/*首字母大小*/
			section p:first-letter{
				font-size: 35px;
			}
			/*有序列表第三子项颜色*/
			#lb {
				color: red;
			}
			/*视频剧中*/
			#advideo {
				text-align: center;
				margin: 50px auto;
			}
			/*表格长度、边框*/
			table {
				border: 1px solid lightgray ;
				border-collapse: collapse;
				width: 1000px;
				color: gray;
				
			}
			/*表头设置*/
			th {
				background: #424242;
				color: white;
				text-align: left;
			}
			/*最后一行单元格颜色、背景色*/
			#zj{
				background: #7ccd7c;
				font-weight: bold;
			}
			/*表格标题居左、加粗*/
			table caption {
				text-align: left;
				font-weight: bold;
			}
			/*侧边栏边距、背景、阴影*/
			aside {
				margin: 20px;
				margin-bottom: 10px;
				padding: 20px;
				background:white ;
				height: 450px;
			    box-shadow:5px 5px 10px 0px #636363 ;
			    color: #515151;
			}
			/*表格内边距*/
			#sider-form {
				padding: 5px;
			}
			/*左侧文字区*/
			aside .form-left {
				display: inline-block;
				text-align: right;
				width: 30%;
				margin-right: .5em;
				margin-top: .5em;
			}
			/*右侧输入区*/
			aside .form-right {
				display: inline-block;
			}
			/*文本框对齐*/
			textarea {
				vertical-align: text-top;
			}
			/*表格提交按钮样式*/
			aside button {
				width: 100%;
				height: 35px;
				background: #009ACD;
				margin: 10px;
				border: 1px;
				border-radius: 8px;
				color: white;
				font-size: 20px;
				
			}
			/*表格提交按钮变换*/
			aside button:hover{
				background: orange;
			}
			/*页脚设置*/
			footer {
				line-height: 70px;
				background: #696969;
				text-align: center;
				color: white;
				font-weight: bold;
			}
		</style>
	</head>

	<body>
		<header>
			<img class="logo" src="baidu-logo.png" />
			<nav>
				<ul class="links">
					<li><a href="#1">导航链接四</a></li>
					<li><a href="#2">导航链接三</a></li>
					<li><a href="#3">导航链接二</a></li>
					<li><a href="#4">导航链接一</a></li>
				</ul>
			</nav>
		</header>
		<main>
			<article>
				<section>
					<h2>文章一级标题 </h2>
					<h3> 文章二级标题</h3>
					<div class="content-header">
						<span class="author">文章作者 </span>
						<span class="addtime"> 文章发表时间</span>
					</div>
					<p>
						web开发项目考核web开发项目考核web开发项目考核web开发项目考核web开发项目考核web开发项目考核该换行了<br>web开发项目考核web开发项目考核
							<a id="lj" href="http://www.baidu.com">
								这里有个链接，链接到http://www.baidu.com
							</a>
							web开发项目考核web开发项目考核web开发项目考核
							<b>这里有个粗体字</b>
							web开发项目考核web开发项目考核
					</p>
					<img src="wp.jpg"/>
					<p>
						web开发项目考核web开发项目考核web开发项目考核
						<a id="lj" href="http://www.baidu.com" target="_blank">
							这里有个链接，会在新窗口打开Baidu.com
						</a>
						web开发项目考核web开发项目考核web开发项目考核web开发项目考核
					</p>
				</section>
				<section>
					<h2>另一篇文章的一级标题</h2>
					<h3>文章二级标题</h3>
					<div class="content-header">
						<span class="author"> 文章作者</span>
						<span class="addtime"> 文章发表时间</span>
					</div>
					<!--有序列表-->
					<ol>
						<li>排名1</li>
						<li>排名2</li>
						<li id="lb">排名3</li>
						<li>排名4</li>
					</ol>
					<div id="advideo">
						<div>请欣赏视频：</div>
						<!--引入视频控件及封面-->
						<video src="sample.mp4" poster="sample.jpg" width="500px" controls>
							
						</video>
					</div>
					<!--书写表格，最后两格合并-->
					<table border="1">
						<caption>下面是一个表格</caption>
						<tr>
							<th>表头</th>
							<th>表头</th>
							<th>表头</th>
						</tr>
						<tr>
							<td>单元格</td>
							<td>单元格</td>
							<td><a href="#5">操作</a></td>
						</tr>
						<tr>
							<td>单元格</td>
							<td>单元格</td>
							<td><a href="#5">操作</td>
						</tr>
						<tr>
							<td>单元格</td>
							<td>单元格</td>
							<td><a href="#5">操作</td>
						</tr>
						<tr>
							<td>单元格</td>
							<td>单元格</td>
							<td><a href="#5">操作</td>
						</tr>
						<tr>
							<td>单元格</td>
							<td>单元格</td>
							<td><a href="#5">操作</td>
						</tr>
						<tr id="zj">
							<td>总计</td>
							<td colspan="2">1000</td>
						</tr>
					</table>
				</section>
			</article>
		</main>
		<aside>
			<div id="sider-form">
				<b>注册窗口</b>
				<!--书写表单-->
				<form>
					<!--邮箱地址-->
					<p class="form-left">请输入邮箱地址： </p>
					<input type="text" name="mail address"  value="这是一个文本输入框" onFocus="if(value==defaultValue){value='';this.style.color='#000'}" onBlur="if(!value){value=defaultValue;this.style.color='#999'}" style="color:#999999"/><i>邮箱地址请按要求格式输入</i>
					<div>
						<!--绑定标签与输入框-->
						<div class="form-right">
						</div>
					</div>
					<!--输入密码-->
					<p class="form-left">请输入密码：</p>
					<input type="password" name="password" /><i>密码应为6-16位英文数字</i>
					<div>
						<!--绑定标签与输入框-->
						<div class="form-right">
						</div>
					</div>
					<!--再输入密码-->
					<p class="form-left">请重复输入密码：</p>
					<input type="password" name="password" />
					<div>
						<!--绑定标签与输入框-->
						<div class="form-right">
						</div>
					</div>
					<!--性别单选-->
					<div>
						<p class="form-left">性别：</p>
						<div class="form-right">
							<input type="radio" name="sex" value="男" checked/>
							男
							<input type="radio" name="sex" value="女" />
							女
						</div>
					</div>
					<!--城市下拉列表-->
					<div>
						<p class="form-left">城市：</p>
						<select class="form-right" autofocus size=1>
							<option value="北京">北京</option>
							<option value="上海">上海</option>
							<option value="南京">南京</option>
							<option value="香港">香港</option>
						</select>
					</div>
					<div>
					<!--爱好复选-->
					<p class="form-left">爱好：</p>
					<input type="checkbox" name="hobby" value="运动"/>运动
					<input type="checkbox" name="hobby" value="艺术"/>艺术
					<input type="checkbox" name="hobby" value="科学"/>科学
					</div>
					<!--个人描述，绑定标签-->
					<div>
					<p class="form-left">个人描述：</p>
					<textarea name="infor"style="height: 60px;width: 250px;"    onfocus="if(value==defaultValue){value='';this.style.color='#000'}" onBlur="if(!value){value=defaultValue;this.style.color='#999'}" style="color:#999999" >这是一个多行输入框，输入您的个人描述</textarea>
					</div>
					<!--提交按钮-->
					<button>确认提交</button>
				</form>
			</div>
		</aside>
		<footer>版权所有</footer>
	</body>

</html>
