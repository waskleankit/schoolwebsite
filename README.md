# schoolwebsite
#https://ztr0bqs7ur2x0lyudfeavq-on.drv.tw/kspdhulkot/kspdhulkot.html
<!DOCTYPE html>

<html lang="en">
<head>
	<meta charset="UTF-8">

	<title>the book shop</title>




<!---                 ----             ---js---->
<script>
	  var slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("demo");
  var captionText = document.getElementById("caption");
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
  captionText.innerHTML = dots[slideIndex-1].alt;
}
	</script>











<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<style type="text/css">
                       /*------------header css-----------*/
h1{color:red;}
marquee
{
font-size:30;
font-color:white;
}
body
{
background-size:cover;
background-position:center;
box-sizing:border-box;
font family:sans-serif;
}
#menu-bar .fa
{
margin-right:8px;
}
#menu-bar
{
background:Bisque;
text-align:center;
}

#menu-bar ul
{
display:flex;
list-style:none;
color:#fff;
}
#menu-bar ul li
{
width:100%;
overflow:hidden;
margin:15px;
padding:15px;
}
#menu-bar ul li a
{
text-decoration:none;
color:BLACK;
}
#menu-bar ul li:hover
{
background-color:AliceBlue;
}

dl
{
list-style-type:square;
background-color:AliceBlue;
color:dimgrey;
}



                    /*------------slide css-----------*/


* {
  box-sizing: border-box;
}

/* Position the image container (needed to position the left and right arrows) */
.container {
  position: relative;
}

/* Hide the images by default */
.mySlides {
  display: none;
}

/* Add a pointer when hovering over the thumbnail images */
.cursor {
  cursor: pointer;
}

/* Next & previous buttons */
.prev,
.next {
  cursor: pointer;
  position: absolute;
  top: 40%;
  width: auto;
  padding: 16px;
  margin-top: -50px;
  color: white;
  font-weight: bold;
  font-size: 20px;
  border-radius: 0 3px 3px 0;
  user-select: none;
  -webkit-user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover,
.next:hover {
  background-color: rgba(0, 0, 0, 0.8);
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* Container for image text */
.caption-container {
  text-align: center;
  background-color: #222;
  padding: 2px 16px;
  color: white;
}

.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Six columns side by side */
.column {
  float: left;
  width: 16.66%;
}

/* Add a transparency effect for thumnbail images */
.demo {
  opacity: 0.6;
}

.active,
.demo:hover {
  opacity: 1;
}








/*------------footer css-----------*/
.content-box{
background-image:linear-gradient(rgba(0,0,0,0),rgba(0,0,0,0),url(home.jpg));
background-position:center;
background-size:cover;
width:100%;
height:100%;
}


.footer h1{
	padding-top:50px;
}
.contact-form{
	padding:15px;
}
.form-contact{
	border-radius:0 !important;
	border:none !important;
	box-shadow:none !important;
}
::placeholder{
	font-size:12px;
}
.contact-form button{
	border:none !important;
	background:#ff4d73 !important;
	box-shadow:none !important;
	border-radius:0;
}
.contact-info .follow{
background-color:#fff;
padding:8px;
margin:15px;
}
.contact-info .fa{
margin:10px;
font-size:20px !important;
color:#ff4d73 !important;
font-weight:bold;
padding-right:20px;
}
.copyright{
text-align:center;
font-size:14px;
}
.fa-heart-o{
color:red;
font-size:17px;
}
.footer hr{
margin-top:50px;
background:#ff4d73;
}
</style>
</head>



<body>



<marquee bgcolor="Bisque" height="40">WELCOME TO GOVT. HSS KANYA SHIKSHA PARISAR DHULKOT</marquee>
<div id="menu-bar">
<ul>
	<li><a href="index"><i class="fa fa-home"></i>HOME</a></li>
	<li><a href="aboutus"><i class="fa fa-clone"></i>about us</a></li>
	<li><a href="services"><i class="fa fa-clone"></i>services</a></li>
	<li><a href="contact"><i class="fa fa-phone"></i>contact</a></li>
</ul>
</div>





<!-- Container for the image gallery -->
<div class="container">

  <!-- Full-width images with number text -->
  <div class="mySlides">
    <div class="numbertext">1 / 6</div>
      <img src="img1.jpg" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">2 / 6</div>
      <img src="img2.jpg" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">3 / 6</div>
      <img src="img3.jpg" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">4 / 6</div>
      <img src="img4.jpg" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">5 / 6</div>
      <img src="img5.jpg" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">6 / 6</div>
      <img src="img6.jpg" style="width:100%">
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>

  <!-- Image text -->
  <div class="caption-container">
    <p id="caption"></p>
  </div>

  <!-- Thumbnail images -->
  <div class="row">
    <div class="column">
      <img class="demo cursor" src="img1.jpg" style="width:100%" onclick="currentSlide(1)" alt="img1">
    </div>
    <div class="column">
      <img class="demo cursor" src="img2.jpg" style="width:100%" onclick="currentSlide(2)" alt="img2">
    </div>
    <div class="column">
      <img class="demo cursor" src="img3.jpg" style="width:100%" onclick="currentSlide(3)" alt="img3">
    </div>
    <div class="column">
      <img class="demo cursor" src="img4.jpg" style="width:100%" onclick="currentSlide(4)" alt="img4">
    </div>
    <div class="column">
      <img class="demo cursor" src="img5.jpg" style="width:100%" onclick="currentSlide(5)" alt="img5">
    </div>
    <div class="column">
      <img class="demo cursor" src="img6.jpg" style="width:100%" onclick="currentSlide(6)" alt="img6">
    </div>
  </div>
</div>





<h4>There's much to see here. So, take your time, look around, and learn all there is to know about us. We hope you enjoy our site and take a moment to drop us a line.</h4>


<hr>

<dl>
	<dt>President
		<dd>Mangidas waskle
	<dt>Secratory
		<dd>Gorelal  Mujalde
	
</dl>











<h2>FACULTY LIST</h2>

<table style="width:100%">
  <tr>
    <th>S.No.</th>
    <th>Name</th>
    <th>Post</th>
    <th>Subject</th>
  </tr>
  <tr>
    <td>1</td>
    <td> Mangiadas waskle</td>
    <td>UDT</td>
    <td>Hindi literature</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Gorelal Mujalde</td>
    <td>UDT</td>
    <td>Sanskrit literarture</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Mrs. Fulkunwar Maheshwari</td>
    <td>UDT</td>
    <td>Social science</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Rajaram Patidar </td>
    <td>UPT</td>
    <td>Hindi literature</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Shailesh Wagmore </td>
    <td>UPT</td>
    <td>Sanskrit literature</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Bhagmal Jadhav </td>
    <td>UPT</td>
    <td>Social science</td>
  </tr>

</table>
<hr>





<h2>INFRASTRUCTURE</h2>
<br>
Rooms -6

Residential room -6

laboratory-1

toilates-6

bathrooms-8

Staff room  and pc lab-1

Playground 400*200 mtr




<br>
<h2>HOURS</h2>
<br>
Monday - saturday: 9:30am - 5:30pm
<br>
Sunday: Closed







<h1>Open a PDF file </h1>
<p>TC certificate <a href="tc.pdf">example</a>.</p>
<p>मद  <a href="md.pdf">example</a>.</p>
<p>हा.  से.  मान्यता  <a href="hsc.pdf">example</a>.</p>
<p>fees <a href="mdwar.pdf">example</a>.</p>















<h2>Events</h2>
ENERAL MEETING
<br>
general meetings are held time to time with staff. 
<br>
<br>
SCHOOL MANAGEMENT DEVELOPMENT COMMITTEE
<br>
these meetings are also held time to time
<br>
<br>
ANNUAL FUNCTION
<br>
Every year a very croudful and diciplined program is organised by school.
<br>
<br>
ANNUAL SPORTS
<br>
Every year Sports programs are organised for students like kabbadi kho kho,vollyball,badminton
<br>
<br>
ANNUAL SPORTS
<br>
Every year Sports programs are organised for students like kabbadi kho kho,vollyball,badminton




<section class="footer">
<div class="content-box">
<div class="container">

<h1>get in touch</h1>
<div class="row">
	<div class="col-md-6">
	<form action="." method="post">
		<div class="form-group">
		<input type="text" class="form-control"
		placeholder="your name" name="name">
		</div>
		<div class="form-group">
		<input type="number" class="form-control"
		placeholder="phone number" name="phonenumber">
		</div>
		<div class="form-group">
		<input type="email" class="form-control"
		placeholder="email id" name="email">
		</div>
<!--		<div class="form-group">-->
<!--		<input type="text"  name= "des" class="form-control" rows="4"-->
<!--		placeholder="your message">-->
<!--		</input>-->
<!--		</div>-->
		<button type="submit" class="btn btn-primary">send message</button>
	</form>
	</div>
	<div class="col-md-6 contact-info">
		<div class="follow">
			<i class="fa fa-map-marker"></i><span>Dhulkot,Bhagwanpura,Khargone,MP,India</span>
		</div>
		<div class="follow">
			<i class="fa fa-phone"></i><span>+91 8959269526</span>
		</div>
		<div class="follow">
			<i class="fa fa-envelope-0"></i><span>wasklemangidas123@gmail.com</span>
		</div>
		<div class="follow">
		<i class="fa fa-facebook"></i>
		<i class="fa fa-youtube"></i>
		<i class="fa fa-Instagram"></i>
		<i class="fa fa-twitter"></i>
		</div>
	</div>

</div>
	<hr>
	<p class="copyright">Copyright © 2021 goverment higher secondry school kanya siksha parisar dhulkot - All Rights Reserved               made with <i class="fa fa-heart-o"></i>by Ankit Waskle</p>
</div>
</div>
</section>
</body>
</html>
