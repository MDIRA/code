# code
Verified


<?php include ('server.php') ?>

<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
	background-image:url("assets/img/salon2.jpg");
	background-repeat:no-repeat;
	
    font-family: "Lato", sans-serif;
    transition: background-color .5s;
}
.navbar{
overflow:hidden;
background-color:black;
position:fixed;
top:0;
width:100%;
height:70px;
left: 0px;
}
.navbar a{
float:right;
display:block;
color:white;
text-align:center;
padding:14px 16px;
text-decoration:none;
}
.navbar a:hover{
background-color:red;
color:white;
border-radius: 20px;
}
.read{
position:left;
z-index:999;
margin-left:10px;;
text-align:left;
height:50px;
width:500px;
margin-top:150px;
font-size:20px;

}
.main {
  position: absolute;
    top:21%;
    right: 7%;
    z-index: 999;
	margin-top:-60px;
}
.booking-form-head-agile h3 {
    color: #f5f5f5;
    text-align: center;
}
.main h1{
	text-align: center;
    color: #fff;
    font-size: 3em;
    margin-bottom: 1em;
}
.w3layouts_main_grid {
    width: 100%;
    padding: 2em;
    margin: 0 auto;
    background:rgba(8, 8, 8, 0.32);
}
.w3layouts_main_grid  {
    padding: 2em;
    display: block;
}
.w3layouts_main_grid h5{
    color: #FFFFFF;
    font-size: 16px;
    font-style: normal;
    margin: .8em 0 0;
	padding-bottom: 0.5em;
	opacity: 0.9;
}

.w3layouts_main_grid input[type="text"]{
    outline: none;
    width: 92%;
    background: #fff;
    color:#4B4B4B;
    padding: 10px;
    font-size: 14px;
    border: 1px solid #E7E7E7;
}
.w3layouts_main_grid input[type="email"] {
    outline: none;
    width: 100%;
    background: #fff;
    color:#4B4B4B;
    padding: 10px;
    font-size: 14px;
    border: 1px solid #E7E7E7;
}
#category{
    outline: none;
    width: 100%;
    background: #fff;
    color: #4B4B4B;
    padding: 10px;
    font-size: 14px;
    border: 1px solid #E7E7E7;
}
#category1 {
    outline: none;
    width:17%;
    background: #fff;
    color: #4B4B4B;
    padding: 10px;
    font-size: 14px;
    border: 1px solid #E7E7E7;
}
::-webkit-input-placeholder{
	color:#4B4B4B !important;
}
.agileits_w3layouts_main_gridl{
	float:left;
	width:68%;
}
.agileits_w3layouts_main_gridl input[type="text"],.agileits_w3layouts_main_gridr input[type="time"]{
	width:90% !important;
}
.agileits_w3layouts_main_gridr input[type="time"] {
    padding: 7.5px !important;
}
.agileits_w3layouts_main_gridr{
	float:right;
	width:32%;
}
.w3_main_grid{
	margin:2em 0 0;
	padding:2em 0 0;
	border-top:1px solid #fff;
}
.w3_main_grid_left{
	float:left;
	margin: 0.5em 0 0;
}
.w3_main_grid_left a{
	font-size: 1em;
    color: #FFFFFF;
    text-transform: capitalize;
}
.w3_main_grid_left a:hover{
	color:#FF0F75;
}
.w3_main_grid_right{
	float:right;
	width: 30%;
}
.w3_main_grid_right input[type="submit"]{
	outline:none;
	padding:1em;
	width:100%;
	text-transform:uppercase;
	font-size:14px;
	color:#fff;
	background:#e25111;
	border:none;
	cursor:pointer;
	margin-top:-25px;
}
.w3_main_grid_right input[type="submit"]:hover{
	color:#0fab0d;
	background:#fff;
}
.nam1 {
    float: left;
    width: 49%;
    margin-left: 2%;
}
.nam {
    float: left;
    width: 49%;
}
.agileits_grid {
    margin-bottom: 14px;
}
.agileits_w3layouts_main_grid.w3ls_main_grid {
    margin-bottom: 16px;
}
.agileits_main_grid.w3_agileits_main_grid {
    margin-bottom: 16px;
}
.banner-agile-top {
    margin: 1em 0 0 0;
}
@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}
.footer{
background-color: #191919;
color: #fff;
font-family: "Roboto Light";
font-size: 12px;
margin-top:400px;
width: 100%;
height: 50px;
margin-bottom:-10px;
}
.copyright{
	float:left;
	padding-left: 10%;
	padding-top: 5px;
}
.atisda{
	float: right;
	padding-right: 10%;
	padding-top: 5px;
	text-decoration: none;
}
.copyright>a{
	color: #fff;
	border: 0px;
}
.copyright>a:hover{
 text-decoration: none;
}
.atisda>a{
	color: #d99735;
	border: 0px;
}
.atisda>a:hover{
	text-decoration: none;
}
 
@media screen and (max-width:600px){
	.footer{
		margin-top: 15px;
	}
	.copyright{
		float: none;
	text-align: center;
	padding: 0;
	padding-top: 5px;
	margin-bottom: 7px;
}
.atisda{
	float: none;
	text-align: center;
	padding: 0;
}
	 
	.footer>a:hover{
		color: #F97906;
	}
	.footer{
 
		height: 55px;
 
}
}
</style>
</head>
<body>

<div class="navbar">

	<a href="Contact.html">Contact Us</a>
	<a href="index.html">About Us</a>
	<a href="order.html">Order</a>
	<a href="index.html">Gallery</a>
	<a href="index.html">Home</a>
	<p style="text-align: left;color: white;font-size: 20px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>VICKY STORE</strong> </p>
</div>
<div class="read">
	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<h1 style="font-family:font-awesome; text-transform:uppercase;font-weight:600;color:white;font-size:28px;">Hair Product Supply Chain Automation</h1>
<p style="font-weight:100px;color:blue;">Our mission at SAVICKY is to care for the world we live in, from the products we make to the ways in which we can give back to society. At SAVIKCKY we strive to set an example for the environmental leadership and responsibility, not just in the world of beauty but around the world.</p>
<center><button onclick="alert('A successful salon experience to ensure style and fashion through awareness and self examination with communication (ask, then listen) communication with knowledge with passion, passion with integrity and ethics. Integrity and ethics with fun and reinvention transcending into a spirit of positive atmosphere that inspires trust and creativity on anyone we touch and gives us a stable and rewarding career working together as a supportive team.')"style="color: white; margin-bottom:100px;background-color: red; height: 50px; font-size: 18px; border-radius: 50px; width: 150px;color: green;"><b>READ MORE<b></button></center>
					</div>		
<div class="main" id="main">
		<div class="w3layouts_main_grid">
		<div class="booking-form-head-agile">
		<h3>Salon Order form</h3>
		</div>
			<form action="#" method="post" class="w3_form_post">
				<div class="w3_agileits_main_grid w3l_main_grid">
					<div class="agileits_grid">
						<h5>Name * </h5>
						<div class="nam">
							<input type="text" name="First_name" placeholder="First Name" required="">
						</div>
						<div class="nam1">
							<input type="text" name="Last_name" placeholder="Last Name" required="">
						</div>
						<div class="clearfix"></div>
					</div>
				</div>
				<div class="w3_agileits_main_grid w3l_main_grid">
					<div class="agileits_grid">
						<h5>E-mail </h5>
							<input type="email" name="Email" placeholder="ex : vickymdira@savicktorah.com" required="" >
					</div>
				</div>
				<div class="agileits_main_grid w3_agileits_main_grid">
					<div class="wthree_grid">
						<h5>Hair Type</h5>
						<select id="category" name="category" required="">
							<option value=" ">None</option>
							<option value="category1">Wig </option>
							<option value="category2">Weave</option>
							<option value="category3">Abuja</option>
							
						</select>
					</div>
				</div>
				<div class="agileits_w3layouts_main_grid w3ls_main_grid">
					<div class="agileinfo_grid">
					<h5>Delivery Date *</h5>
						
						<div class="agileits_w3layouts_main_gridl">
							<input class="date" id="datepicker" name="Text" type="text" value="mm/dd/yyyy" onfocus="this.value = '';" onblur="if (this.value == '') {this.value = '04/19/2018';}" required="">
						</div>
						<div class="clearfix"> </div>
					</div>
				</div><br>
				<div class="agileinfo_main_grid">
					<div class="agileits_w3layouts_grid">
						<h5>Salon Location *</h5>
						<select id="category1" name="category1" required="" style="width:313px;">
							<option value=" ">None&nbsp&nbsp</option>
							<option value="category2">Nairobi</option>
							<option value="category3">Mombasa</option>
							<option value="category4">Kisumu</option>
							<option value="category2">Machakos</option>
							<option value="category3">Nakuru</option>
						</select>
					</div>
				</div>
				<div class="w3_main_grid">
					
					<div class="w3_main_grid_right">
						<input type="submit" value="Order Now">
					</div>
					<div class="clearfix"> </div>
				</div>
			</form>
		</div>
</div>


<script>
function openNav() {
    document.getElementById("mySidenav").style.width = "250px";
    document.getElementById("main").style.marginLeft = "250px";
    document.body.style.backgroundColor = "rgba(0,0,0,0.4)";
}
function closeNav() {
    document.getElementById("mySidenav").style.width = "0";
    document.getElementById("main").style.marginLeft= "0";
    document.body.style.backgroundColor = "white";
}
</script>
     
</body>
</html> 
