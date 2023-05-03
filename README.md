
<!DOCTYPE html>
<html>
<head>
	<title>Login Page</title>
	<style>
		body {
			background-color: #F2F2F2;
		}
		
		h1 {
			text-align: center;
			margin-top: 50px;
		}
		
		form {
			margin-top: 30px;
			text-align: center;
		}
		
		input[type=text], input[type=password] {
			padding: 10px;
			margin: 10px;
			border: none;
			border-radius: 5px;
			background-color: #E8E8E8;
		}
		
		input[type=submit] {
			padding: 10px 20px;
			margin: 10px;
			border: none;
			border-radius: 5px;
			background-color: #4CAF50;
			color: white;
			font-weight: bold;
			cursor: pointer;
		}
		
		input[type=submit]:hover {
			background-color: #3E8E41;
		}
	</style>
</head>
<body>
	<h1>Login Page</h1>
	<form>
		<input type="text" name="username" placeholder="Username"><br>
		<input type="password" name="password" placeholder="Password"><br>
		<input type="submit" value="Login">
	</form>
</body>
</html>
