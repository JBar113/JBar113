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
	
	background-color: lightBlue;
	background-image: linear-gradient(lightBlue,white);
}

div.gallary{
	margin:2px;
	border: 1px solid black;
	float: left;
	width: 24%;
}

div.gallary img{
width:100%;
height: auto;
}

div.vgallary{
	margin:2px;
	border: 1px solid black;
	float: left;
	width: 40%;
}

div.vgallary iframe{
width:100%;
}

div.info{
padding:10px;
text-align:center;
}


enter{
	animation-name: eg;
	animation-duration: 1s;
}


@keyframes eg {
0% {left: 0px;}
100% {left: 50px;}
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

<p align="center" class="enter"<!--style="font-size:18px"-->
<!--<span style="font-size:20px"><b>JOHN L. BARVENIK</b></span><br>-->
<font size="5"> <b>JOHN L. BARVENIK</b></font><br>
<font size="3">Catonsville, MD<br>
(443)-900-8131  |  jbarvenik@gmail.com</font>
</p>

<!-- Begin Nav Bar section -->

<ul id="nav">
	<li id="navList"><a href="index.md" id="navLink" >Home</a></li>
	<li id="navList"><a href="resumePage.md" id="navLink">Resume</a></li>
	<li id="navList"><a href="portfolioPage.md" id="navLink">Portfolio</a></li>
	<li id="navList"><a href="videosPage.md" id="navLink" class="active">Art/Videos</a></li>
</ul>

<p>
<font size="4">
This page showcases the progress for my game "A Grim Day Out". There is a combination of finished content and concept work.
</font>
<br>
</p>

<p>
<font size="4">
This video shows the full gameplay for A Grim Day Out in its current state.
</font>
<br>
</p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/h4xEQmrX4O8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>

<p>
<font size="3">
This video is an animation demo of both used and currently unimplemented animations for the player character.
</font>
<br>
</p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/FCDpmNUAMLo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

<!-- Begin Art section -->
<p>
<font size="3">
These are concept works for creatures and enemies that are not yet implemented. Due to the simple aesthetics of the game, they didn't need much revision before being modeled.
<br>
One of the future game mechanics is picking up and throwing objects (including the boxes and barrels seen through the level). This would also extend to enemies and creatures that are knocked over.
</font>
<br>
</p>

<div class="gallary">
	<img src="bird00.jpg" width="600" height="400"></img>
	<div class="info">Original Sketch for a bird creature.</div>
</div>

<div class="gallary">
	<img src="bandit00.jpg" width="600" height="400"></img>
	<div class="info">Original Sketch for a bandit enemy.</div>
</div>

<div class="gallary">
	<img src="crab00.jpg" width="600" height="400"></img>
	<div class="info">Original Sketch for a crab creature.</div>
</div>
<div class="gallary">
	<img src="wizard00.jpg" width="600" height="400"></img>
	<div class="info">Original Sketch for a floating wizard enemy.</div>
</div>




<div class="gallary">
	<img src="bird01.jpg" width="600" height="400"></img>
	<div class="info">A work in progress bird model.</div>
</div>

<div class="gallary">
	<img src="bandit01.jpg" width="600" height="400"></img>
	<div class="info">A work in progress bandit model.</div>
</div>

<div class="gallary">
	<img src="crab01.jpg" width="600" height="400"></img>
	<div class="info">A work in progress crab model.</div>
</div>

<div class="gallary">
	<img src="wizard01.jpg" width="600" height="400"></img>
	<div class="info">A work in progress wizard model.</div>
</div>

<br>


<!-- VIDEOS -->

<div class="vgallary">
	<iframe width="560" height="315" src="https://www.youtube.com/embed/yBH_koyTpRo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
	<div class="info">Early bird animations. In addition to hopping and flying, it has a "hit" animation where it gets partially flattened. This would be used if an object were thrown at it.</div>
</div>

<div class="vgallary">
	<iframe width="560" height="315" src="https://www.youtube.com/embed/xQlgc-zFqIs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
	<div class="info">Early bandit animations. He features an arm swinging attack as well as a dive. He also has "hit" animations and an idle animation for when he is knocked on his back.</div>
</div>

<div class="vgallary">
	<iframe width="560" height="315" src="https://www.youtube.com/embed/nUos3AsHW4k" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
	<div class="info">Early crab animations. As it was developed more recently, it doesn't have many finished animations. In the final version it will also be able to get hit and flipped over to be picked up by the player.</div>
</div>

<div class="vgallary">
	<iframe width="560" height="315" src="https://www.youtube.com/embed/Nd9OYUd1GeI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
	<div class="info">Early wizard animations. This enemy will not need as many animations as it couldn't be knocked over. Instead it will hover above the ground, cast magic, and only die if hit by a thrown object.</div>
</div>
<div class="clearfix"></div>

</body>

</html>
