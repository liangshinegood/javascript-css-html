# 1.学习资料 #
	自己购买的资料：
	[http://www.ydma.com/classroom/14/task/66](http://www.ydma.com/classroom/14/task/66)


# 2.学习总结 #
	html中引用方式
		<script type="text/javascript">
			alert("干啥")
		</script>

		<script type="text/javascript" src="./xx.js">

		</script>

----------

	基本语法
		var 定义变量
		alert(),console.log()提示
		/* */ or //注释
		typeof()

----------

	运算符
		+,-,*,/ ,%
		+=,-=,*=,/=,%=
		<> ,>=,!=,===,!===
		&&,||,!

----------

	逻辑判断
		if(){}else{},if(){}else if(){} else{}
		switch(变量){case 1: case 2:}

----------

	循环
		for,while
		for...in,continue,break

----------
 	函数
		function love(){}
		function love(a,b,c){} love(1,2,3)

	
----------
	举例：
		<div id="all"></div>
		var div=document.getElementById("all")
		div.innerHTML = 'I LV Y'
		div.style.width/height/background
		
		var form=document.getElementById("form")
		form.username.value=""
		btn.onclick=function(){}
		

----------
		setTimeout(function(){},2000)
		setInterval(function(){},2000)
		clearTimeout()
		clearInterval()

----------
		表单选择（全选，反选）for,checked
		计算器 switch
		随机颜色 math.floor(math.random()*(n-m+1)+m)
		随机点名：function start setInterval,function end clearInterval

----------
		json数据格式：
		var ovj:{
			name:"李四"，
			age:22,
			height:134,
			sing :function(){}
			dance :function(){}
		}

----------

	正则表达式
		/\w{2}/,/\w{2,5}/,/[a-z,0-9,A-Z,_]/
		\w,\d,\s,.,*,+,?
		/.*\d{11}\w*/
		/^\w+@\w+\.(com|cn|org|gov)$/
		
		举例，form中输入手机号的判断
		取form
		form.name onfocus:function 绑定事件
		form.name.onblur:function(){.value}丧失焦点事件

----------


	其他应用
		jquery $简化访问html
		ajax 异步运行
		bootstrap 简化css


# 3.问题及解决 #