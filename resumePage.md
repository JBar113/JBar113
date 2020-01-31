<!DOCTYPE html>
<html>

<head>

<style>
th.leftAlign{
text-align: left;
}
</style>

<style>
html{
	height: 100%
}
</style>

<style>
body{
	height: 100%
	background-repeat: no-repeat;
	background-attachment: fixed;
	margin-left: 50px;
	margin-right: 50px;
	
	background-color: lightBlue;
	background-image: linear-gradient(lightBlue,white);
}
</style>

<style>

enter{
	animation-name: eg;
	animation-duration: 1s;
}


@keyframes eg {
0% {left: 0px;}
100% {left: 50px;}
}
</style>

<style>
#nav{
border: 1px solid gray;
	list-style-type: none;
	margin: 0;
	padding: 0;
	overflow: hidden;
	background-color: #262626;
	
}
</style>

<style>
#navList{
	float: left;
	align: center;
}
</style>

<style>
#navLink{
	
	display: block;
	border-right: 1px solid DarkCyan;
	color: White;
	
	padding: 16px;
	text-decoration: none;
}

#navLink:hover{
	background-color: DarkCyan;
}
</style>
<style>
.active{
	background-color: CadetBlue;
}
</style>
<meta charset="UTF-8">
<title>JLB Resume Site</title>

</head>

<!-- *****BEGIN MAIN BODY***** -->

<body>

<p align="center" class="enter"<!--style="font-size:18px"-->
<!--<span style="font-size:20px"><b>JOHN L. BARVENIK</b></span><br>-->
<font size="5"> <b>JOHN L. BARVENIK</b></font><br>
<font size="3">Catonsville, MD<br>
(443)-900-8131  |  jbarvenik@gmail.com</font>
</p>

<!-- Begin Nav Bar section -->

<ul id="nav">
	<li id="navList"><a href="index.md" id="navLink">Home</a></li>
	<li id="navList"><a href="resumePage.md" id="navLink" class="active">Resume</a></li>
	<li id="navList"><a href="portfolioPage.md" id="navLink">Portfolio</a></li>
	<li id="navList"><a href="videosPage.md" id="navLink">Art/Videos</a></li>
</ul>



<iframe src="JLB_Resume 1-24-20 WebVer.pdf" width="100%" height="800px" ></iframe>

</body>

</html>
