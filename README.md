<!DOCTYPE html>
<html lang="en">
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale1.0">
	<title>Nebula Nexus</title>
	<link rel="stylesheet" type="text/css" href="NebulaNexusCSS.css">
</head>
<body>
	<div class="Container">
		<nav>
			<div class="dot"></div>
			<ul>
				<li><a href="#Home">Home</a></li>
				<li><a href="#Services">Services</a></li>
				<li><a href="#AboutUs">About Us</a></li>
				<li><a href="#ContactUs">Contact Us</a></li>
			</ul>
		</nav>
		<div class="main">
			<h2>Welcome to</h2>
			<h1>Nebula Nexus </h1>
			<h1 class="spc">Innovation</h1>
			<p>"Welcome to our educational hub, where we believe<br>in a hands-on approach to learning. Our programs go<br>
				beyond theory, focusing on practical knowledge that<br>prepares student for real world challnges. Immerse yourself<br>in an educational experience that empowers you with the skills<br>needed to thrive in today's dynamic industries."</p>
			<a class="btn" href="#AboutUs">About Us</a>
		</div>
		<div class="imge">
			<img class="girls" src="C:\Users\Nilesh\Pictures\Nebula\student image.jpg">
		</div>
	</div>
</body>
</html>


*{
	margin: 0;
	padding: 0;
	font-family: sans-serif;
}
.container{
	position: relative;
	width: 100%;
	height: 100vh;
}
nav{
	display: flex;
	width: 84%;
	margin: auto;
	padding: 20px 0;
	align-items: center;
	justify-content: space-between;	
}
.dot{
	height: 40px;
	width: 40px;
	background-color: black;
	border: 2px solid black;
	border-radius: 50%;
}
.dot:hover{
	height: 40px;
	width: 40px;
	background-color: red;
	border: 2px solid white;
	border-radius: 50%;
}
li{
	display: inline-block;
	list-style: none;
	margin: 10px 20px;
}
a{
	text-decoration: none;
	color: black;
	font-size: 18px;
}
a:hover{
	text-decoration: none;
	color: red;
	font-size: 18px;
}
.main{
	margin-left: 8%;
	margin-top: 12%;
}
h2{
	font-size: 28px;
}
h1{
	font-size: 50px;
}
p{
	padding-top: 15px;
	padding-bottom: 18px;
	font-size: 18px;
}
.btn{
	color: white;
	background-color: black;
	padding: 7px;
	margin-left: 5px;
	margin-right: 5px;
	border: 2px solid black;
	border-radius: 12px;
}
.btn:hover{
	color: black;
	background-color: white;
	padding: 7px;
	margin-left: 5px;
	margin-right: 5px;
	border: 2px solid black;
	border-radius: 12px;
}
.imge{
	width: 45%;
	height: 80%;
	position: absolute;
	bottom: 0;
	right: 100px;
}
.girls{
	height: 520px;
	margin-left: 200px;

}





