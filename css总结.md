# 1.学习资料 #
	自己购买的资料：
	[http://www.ydma.com/classroom/14/task/66](http://www.ydma.com/classroom/14/task/66)


# 2.学习总结 #
	/* */注释
	
	内部样式
		<stype type="text/css">
			 p{
				 font-size:10cm;
				 font-weight:bold;
				 color:yellow;
						
			  }
		</stype>

----------

	内联样式
		<div style="color:red;font-size=50px">

----------
	外部样式
		<link rel="stylesheet" href="css路径"/>	
		or
		<style>
			 @import"css路径"
		</style>

----------
	定位属性
		top:100px,bottom:100px,left:100px,right:100px,opacity:0.3;position:relative/absolute/fixed/static

----------
	布局属性
		inline/block,display:none,visibility:hidden/visible
		display:inline/block
		overflow-y:scroll
		overflow-x:visible
		float:left/right/none
		clear:left
		

----------

	设置访问方式
		<style type='text/css'>
			   .one{  #类方式
					font-size:30px;
				}
				#one{  # id方式
				    font-size:50px;
				}
				div,hz,#one{ #层级方式
					background-color:red;
				}

				div[title]{ #属性方式
					title="this"/title~="this"/
					background-color:red;

				div:first-line{#伪元素
					background-color:red;
				}
				}
		</style>

----------

	盒子模型及属性

		margin(top/bottom/left/right)
		padding
		border(color,width,style,top)
		background(color,imag,repeat,position,attachment)
		text(indent,align)
		line(height)
		font(style,family,size)
		@media screen and{

		}

# 3.问题及解决 #