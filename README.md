<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="HMH Digital Health Clinic - Professional diagnostics, treatment, investigations and health education services in Nigeria.">
<meta name="keywords" content="Clinic in Nigeria, Digital Health, Medical Checkup, Diagnostics, Treatment">
<meta name="author" content="HMH Digital Health Clinic">

<title>HMH Digital Health Clinic</title>

<link rel="icon" type="image/png" href="logo.png">

<style>

body{
margin:0;
font-family:Arial, sans-serif;
background:#f4f9fc;
}

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:15px 40px;
background:white;
box-shadow:0 2px 10px rgba(0,0,0,0.05);
}

.logo img{
height:50px;
}

nav a{
margin:0 15px;
text-decoration:none;
color:#0a6c8e;
font-weight:bold;
}

.hero{
background:linear-gradient(to right,#0a6c8e,#13a8a8);
color:white;
text-align:center;
padding:100px 20px;
}

.hero h1{
font-size:40px;
}

.btn{
background:white;
color:#0a6c8e;
padding:12px 25px;
text-decoration:none;
border-radius:5px;
font-weight:bold;
}

.services{
padding:60px 20px;
text-align:center;
}

.service-box{
display:inline-block;
width:250px;
margin:15px;
padding:20px;
background:white;
border-radius:8px;
box-shadow:0 4px 15px rgba(0,0,0,0.05);
}

.booking{
background:#eaf6fb;
padding:50px 20px;
text-align:center;
}

.booking input, .booking select{
width:250px;
padding:10px;
margin:10px;
}

footer{
background:#0a6c8e;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}

</style>
</head>

<body>

<header>
<div class="logo">
<img src="logo.png" alt="HMH Logo">
</div>
<nav>
<a href="#">Home</a>
<a href="#">Services</a>
<a href="#">Booking</a>
<a href="#">Contact</a>
</nav>
</header>

<section class="hero">
<h1>Your Health, Our Priority</h1>
<p>Professional Digital Healthcare Services</p>
<br>
<a href="#booking" class="btn">Book Appointment</a>
</section>

<section class="services">
<h2>Our Medical Services</h2>

<div class="service-box">Diagnostics & Medical Checkup</div>
<div class="service-box">Treatments</div>
<div class="service-box">Investigations</div>
<div class="service-box">Health Education</div>
<div class="service-box">Disease Surveillance</div>

</section>

<section class="booking" id="booking">
<h2>Book Appointment</h2>

<form action="booking.php" method="POST">
<input type="text" name="name" placeholder="Full Name" required><br>
<input type="email" name="email" placeholder="Email Address" required><br>
<input type="tel" name="phone" placeholder="Phone Number" required><br>

<select name="service" required>
<option value="">Select Service</option>
<option>Diagnostics</option>
<option>Treatment</option>
<option>Investigation</option>
</select><br>

<input type="date" name="date" required><br>

<button type="submit" class="btn">Confirm Booking</button>
</form>

</section>

<footer>
<p>📞 +2349033562110 | ✉️ hussainimuhammadhassan1@gmail.com</p>
<p>© 2025 HMH Digital Health Clinic</p>
</footer>

</body>
</html>
