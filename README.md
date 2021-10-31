<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.topnav {
  overflow: hidden;
  background-color: #333;
}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #04AA6D;
  color: white;
}

.topnav-right {
  float: right;
}


.fa {
  padding: 10px;
  font-size: 20px;
  width: 30px;
  text-align: centre;
  text-decoration: none;
  margin: 5px 2px;
  
}

.fa:hover {
    opacity: 0.7;
}

.fa-facebook {
 
  color: white;
}

.fa-instagram {
  
  color: white;
}


.fa-twitter {
  
  color: white;
}


/* Slideshow container */
.slideshow-container {
position:absolute;
left:250px;
top:100px;
 margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #000000;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  top:30%;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
  
}
 img { 
      opacity: 0.4;       
            } 

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}

table {
  position:absolute;
  left:250px;
  font-family: arial, sans-serif;
  table-layout:100%;
  border-collapse: collapse;
  width: 50%;
}

td, th {
  border: 1px solid #dddddd;
  text-align: centre;
  padding: 8px;
  width:25%
}
tr:nth-child(odd) {
  background-color:#fffacd;
}
tr:nth-child(even) {
  background-color: #dddddd;
}

* {
  box-sizing: border-box;
}

/* Create three equal columns that floats next to each other */
.c {
  position:relative;
  top:400px;
  left:250px;
  float: left;
  width: 335px;
  padding: 5px;
  height: 220px; /* Should be removed. Only for demonstration */
}

/* Clear floats after the columns */
.r:after {
  content: "";
  display: table;
  clear: both;
}

/* Create four equal columns that floats next to each other */
.column {
position:relative;
  top:550px;
  background-color: #333;
  color:white;
  float: left;
  width: 25%;
  padding: 10px;
  height: 300px; 
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

a {
	
	text-decoration:none;
	 transition-duration: 0.4s;
  cursor: pointer;
	
}

a:link{
	
	color:white;
	
	
}

a:visited {
	
	color:white;

}

a:hover
{ 
color: green;
 }
 
 input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

</style>
</head>
<body>

 <body style="background-color:#00FFFF;">
 
 <div class="topnav">
  <a class="active" >DietiCan</a>
 
  <div class="topnav-right">
    <a href="Main page.html" >Home</a>
    <a href="Blog.html">Blog</a>
	 <a href="About.html">About</a>
  <a href="Feedback.html">Feedback/inquiry</a>
   <a href="Admin.html">Admin</a>
  </div>
</div>
 
<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="pic1.png" width="1000" height="300" />
  <div class="text">Are you suffering from overweight problems?
Having difficulties to overcome obesity?Do you need a diet-planner ? No problem here we are to help you
 <p>Click below the for the Solution</p> 
 <a href="#"><i class="fas fa-robot" style="font-size:50px"></i></a>
</div>
</div>

 
<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="pic2.png" width="1000" height="300">
  <div class="text">What is BMI?
  <p>  Body mass index(BMI) is a convenient,
  inexpensive method to determine health level of a person and expressed by division of body mass by the square of the body height,unit kg/m2.    </p>
</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="pic3.png" width="1000" height="300">
  <div class="text">BMI and it's categories:
  <table>
  <tr>
    <th>BMI</th>
    <th>Category</th>
    
  </tr> 
    <tr>
    <th> less than 18.5 </th>
    <th>Underweight</th>
    
  </tr> 
    <tr>
    <th> 18.5 to 24.9 </th>
    <th>Normal weight</th>
    
  </tr> 
    <tr>
    <th>25 to 29.9</th>
    <th>Overweight</th>
    
  </tr> 
  
   </tr> 
    <tr>
    <th>30 and higher</th>
    <th>Obesity</th>
    
  </tr> 
  </table></div>
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>

<script>
	var BotStar={appId:"se1f86017-12d6-41ae-a6a5-7f4451158743",mode:"livechat"};!function(t,a){var e=function(){(e.q=e.q||[]).push(arguments)};e.q=e.q||[],t.BotStarApi=e;!function(){var t=a.createElement("script");t.type="text/javascript",t.async=1,t.src="https://widget.botstar.com/static/js/widget.js";var e=a.getElementsByTagName("script")[0];e.parentNode.insertBefore(t,e)}();}(window,document)
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>

<div class="r">
  <div class="c" style="background-color:white;" >
   
    <p>'I was recently suffering from obesity since 2017 .
	I don't know what meal plan to follow.After I started to follow  my diet planner and exercise tips from DietiCan,I started to reduce my weight.'</p>
	<p style="position:absolute; top: 150px; left:200px; ">Siti Salmah,</p>
     <p style="position:absolute; top: 170px; left:200px; ">Clerk</p>

  </div>
  <div class="c" style="background-color:white;" >
   <p>'Since I am middle class employee,
   I cannot afford to consult a dietitian and I don't have time for it.Now,with DietiCan,I can check health level and suitable diet planner for free'</p>
	<p style="position:absolute; top: 150px; left:200px; ">Ravi,</p>
     <p style="position:absolute; top:170px; left:200px; "> Factory Worker</p>

  </div>
  <div class="c" style="background-color:white;">
    <p>I am an athlete who got recently injured from last match.
	So,I looked for a suitable diet-planner tool to maintain my BMI,body health and then I found DietiCan,which is a suitable platform to look for</p>
	<p style="position:absolute; top: 150px; left:200px; ">Ah Chong,</p>
     <p style="position:absolute; top:170px; left:200px; ">Athlete</p>
  </div>
</div>



<div class="row">
  <div class="column">
    <h3>Contact</h3>
    <p style ="font-size:15px;">Address:Lot 24,Taman Kuching,71010 Port Dickson,Seremban</p>
	<p style ="font-size:15px;">Phone:017-3456728</p>
	
  </div>
  <div class="column">
 
    <h3>Menu</h3>
  <a href="Main Page.html" >  <p  style ="font-size:15px;" >Home</p></a>
	<a href="Blog.html"><p style ="font-size:15px;">Blog</p></a>
	<a href="About.html"><p style ="font-size:15px;">About</p></a>
	<a href="Feedback.html"><p style ="font-size:15px;">Feedback/Inquiry</p></a>
	
  </div>
  <div class="column" >
    <h3>Social medias</h3>
	<a href="https://www.facebook.com/thanesh.maryadas/" class="fa fa-facebook"></a>
    <a href="https://www.facebook.com/thanesh.maryadas/" class="fa fa-twitter"></a>
    <a href="https://www.instagram.com/thaneshmaryadas/" class="fa fa-instagram"></a>
  </div>
  <div class="column">
    <h3>Others</h3>
    <p style ="font-size:15px;"> Subscribe us to get more updates from us</p>
     <form name="myForm" action="/action_page.php" onsubmit="alert('Thank you for your subscription.');" method="post" required>
  Email address: <input type="text" name="fname">
  <input type="submit" value="Submit">
</form>
<br>
    <p style ="font-size:10px">&#169; DietiCan.All rights Reserved  </p>
	 <a href="privacypolicy.html"> <p style ="font-size:10px;">Privacy Policy</p></a>
  </div>
</div>
<script>var BotStar={appId:"se1f86017-12d6-41ae-a6a5-7f4451158743",mode:"livechat"};!function(t,a){var e=function(){(e.q=e.q||[]).push(arguments)};e.q=e.q||[],t.BotStarApi=e;!function(){var t=a.createElement("script");t.type="text/javascript",t.async=1,t.src="https://widget.botstar.com/static/js/widget.js";var e=a.getElementsByTagName("script")[0];e.parentNode.insertBefore(t,e)}();}(window,document)</script>
</body>
</html> 
