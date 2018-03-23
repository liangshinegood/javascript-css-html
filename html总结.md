# 1.学习资料 #
	自己购买的资料：
	[http://www.ydma.com/classroom/14/task/66](http://www.ydma.com/classroom/14/task/66)

----------

# 2.学习总结 #

----------

	固定模式
			<!DOCTYPE HTML>
			<html>
				<head>
				</head>
				<body>
				</body>
			</html>

----------

	处理格式
		<title></title>

		<meta charset="utf-8"/>,<meta name="keywords" content="内容">,<meta name="discription" content="内容">

		<p></p>段落，<h1></h1>标题，<br>换行,<hr />水平线，<del></del>删除线，<strong></strong>强调，<i></i>斜体，<b></b>粗体，<em>强调，<sub>下标，<sup>上标,<small>小号字

		<a href="http://www.runoob.com">这是一个链接</a>

		<img src="/images/logo.png" width="258" height="39" />

		<ul>
				<li></li>
				<li></li>
		<ul>

		<ol>
				<li></li>
				<li></li>
		<ol>

		<detail></detail>

		属性包括：class,id,title,style,name,center,font,bgcolor,backgroud,size,color

----------

	超媒体
		<audio controls>
			<source src="">
		</audio>

		<video controls>
				<source src="">
		</video>

----------

	表格
		<table border="1" width="800">
			<tr align="center">
					<td valign="top"></td>
					<td rowspan="3"></td>
			</tr>
			<tr align="center">
					<td valign="top"></td>
					<td rowspan="3"></td>
			</tr>
		</table>
	
----------	

	框架
		<frameset rows="20%*">
				<frame src="./top.html"/>
				<frameset cols="25%*">
					<frame src="./right.html"/>
				</frameset>
		
		</frameset>

----------
	表单
		<form action="" method="get/post">
			 文字<input type="text" name="user" value=""/><br/>
			 文字<input type="password" name="pwd" value=""/><br/>
			 <input type="submit" value="">
			 <button></button>
			<input type="radio"/>
			<input type="checkbox" name="hobby[]" value="0"/>
			<input type="file" name="pic",value=""/>
			<input type="image" name="" src="路径" width="" value="" alt=""/>
			<input type="reset" name="" value="" />
			<input type="hidden" name="" value=""/>
			<input type="reach"/>
			<textarea name="content"></textarea>
			<select name="">
				<option value="1"></option>
				<option value="1"></option>
			</select>

		</form>
		
		知识点1：为排版方便，表单允许分离
		知识点2：readonly,disabled,selected,autofocus,placeholder,required,multiple,pattern,step,min,max,tabindex,contentEditable

# 3.问题及解决 #