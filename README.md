# 0609
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
	<!-- form 表单 -->
	<!-- action 表单数据提交到哪里 -->
	<!-- method 表单提交的方式 -->
		<!-- get -->
			<!-- 1.数据显示在url商 -->
			<!-- 2.安全性相对较低 -->
			<!-- 3.速度快 -->
			<!-- 4.数据长度有限制 -->
		<!-- post -->
			<!-- 1.数据显示在请求体中 -->
			<!-- 2.安全性相对较高 -->
			<!-- 3.比get请求速度慢 -->
			<!-- 4.数据长度理论上有限制 -->
	<!-- form 表单是前端的最后一站,后端的第一站 -->
	<!-- input控件 -->
		<!-- type 表单控件类型 -->
		<!-- name  控件的名字 -->
		<!-- value 控件的值 -->
		<!-- id js调用 -->
	<form action="test.php" method="get">
		<div>
			<!-- 文本框/明文框 -->
			用户名:<input type="text" name="texts" placeholder="请输入">
		</div>
		<div>
			<!-- 密码框 -->
			密码:<input type="password" name="pass">
		</div>
		<div>
			<!-- 单选框 -->
			<!-- 单选框中name属性会将多个同名单选框变成一个组 -->
			性别:
			男 <input typ	e="radio" name="sex" value="male">
			女 <input type="radio" name="sex" value="female">
			萨瓦迪卡 <input type="radio" name="sex" value="kouniqwa">
		</div>
		<div>
			<!-- 复选框 -->
			<!-- 复选框中name属性会将多个同名复选框变成一个组 -->
			爱好:
			妹子<input type="checkbox" name="hooby" value="girl">
			rap<input type="checkbox" name="hobby" value="ball">
			篮球<input type="checkbox" name="rap">
		</div>
		<div>
			<!-- 下拉框 -->
			籍贯:
			<select name="sheng">
				<option>福建</option>
				<option>黑龙江</option>
				<option>广东</option>
			</select>
		</div>
		<div>
			<!-- 普通按钮 -->
			<input type="button" name="button" value="我是一个可怜无助又能吃的按钮">
			<!-- 提交按钮 -->
			<input type="submit" name="submit" value="提交">
			<!-- 重置按钮 -->
			<input type="reset" name="reset" value="重置">
			<!-- 图片按钮 -->
			<input type="image" src="../1.jpeg">
		</div>
		<div>
			<!-- 文本域 -->
			<!-- cols代表每行多少个字，rows代表总共多少行 -->
			<textarea cols="10" rows="20" >
				
			</textarea>
		</div>
	</form>
</body> 
</html>
