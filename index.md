<!DOCTYPE html>
<html>

<head>

<style>
th.leftAlign{
text-align: left;
}

body{
	height: 100%
	background-repeat: no-repeat;
	background-attachment: fixed;
	margin-left: 50px;
	margin-right: 50px;
	
	background:  url(screenshot02.jpg);
	background-repeat: no-repeat;
	background-size: cover;
	
	background-color: lightBlue;
}



.img-container{
float:left;
width: 31%;
padding: 5px;
}

.cfix::after{
content: "";
clear:both;
display:table;
}

div.tbacktitle{
	padding: 5px;
	background-color: rgba(255,255,255,0.5);
}
div.tback{
	padding: 10px;
	background-color: rgba(255,255,255,0.5);
}


#nav{
border: 1px solid gray;
	list-style-type: none;
	margin: 0;
	padding: 0;
	overflow: hidden;
	background-color: #262626;
	
}

#navList{
	float: left;
	align: center;
}

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

.active{
	background-color: CadetBlue;
}
</style>

<meta charset="UTF-8">
<title>JLB Resume Site</title>

</head>

<!-- *****BEGIN MAIN BODY***** -->

<body>

<div class="tbacktitle">
<p align="center" class="enter"<!--style="font-size:18px"-->
<!--<span style="font-size:20px"><b>JOHN L. BARVENIK</b></span><br>-->
<font size="5"> <b>JOHN L. BARVENIK</b></font><br>
<font size="3">Catonsville, MD<br>
(443)-900-8131  |  jbarvenik@gmail.com</font>
</p>
</div>
<!-- Begin Nav Bar section -->

<ul id="nav">
	<li id="navList"><a href="index.html" id="navLink" class="active">Home</a></li>
	<li id="navList"><a href="resumePage.html" id="navLink">Resume</a></li>
	<li id="navList"><a href="portfolioPage.html" id="navLink">Portfolio</a></li>
	<li id="navList"><a href="videosPage.html" id="navLink">Art/Videos</a></li>
</ul>

<br>

<div class="tback">
<p>
<font size="4">
Hello!<br><br>
My name is John Barvenik. Welcome to my website dedicated to displaying my resume, portfolio, and progress on some of my projects. I have a B.A. in psychology from the University of Maryland Baltimore County and a minor in computer science.<br>

</p>

<p>
Psychology was my primary area of study. While a B.A. gives a great and varied breadth of knowledge in the domain, I have several primary areas of interest. First, I selected courses specific to child development and education due to my interest in developing intelligence and enthusiasm for teaching. In addition, I sought out courses for physiological psychology to bolster my understanding of empirical research on the inner workings of the nervous system.<br>
</p>
<p>
In computer science, I took courses geared particularly towards graphics, animation, and efficient design. As such, I understand the basic principles of the rendering pipeline and have experience creating ray tracers, rasterizers, and generated animation. Most of my work was done in C++, although I also have exposure to C, C#, Java, Haskell, Assembly code, and HTML.<br>
</p>
<p>
<i>
Fun fact: Basic neural network models of image recognition in computer science share many similarities with theories on how the brain parses and identifies visual information. <br>
</i>
</p>

<p>
Beyond formal education, I have also taught myself the fundamentals animation and game design software including the Unity Engine, Blender, Maya, and Mudbox. I am constantly workshopping, discussing, and collaborating on ideas, systematically doing research, and putting in the work towards the goal of producing my game design visions that have arisen over the years. Working on game development is more than just a career goal, it is something I take pride and immense joy in.
<br>
<p>
My goal: to become a professional game developer. It is my central drive is to create stories and experiences through the same medium that captured my heart as a child. I already have a wide variety of relevant capabilities developed through coursework, self-taught skills, teamwork, and board game design. Now I am seeking an avenue to work with a team of like-minded people and put these abilities to use and to build great adventures.<br>
</p>
</font>
</div>

</body>

</html>
