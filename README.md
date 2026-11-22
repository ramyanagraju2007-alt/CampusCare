<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CampusCare</title>
<style>
*{box-sizing:border-box}
body{
 margin:0;
 font-family:Arial,sans-serif;
 background:#f4f7ff;
 color:#202b45;
}
header{
 background:#263b80;
 color:white;
 padding:22px;
 text-align:center;
}
nav{
 background:#172554;
 padding:12px;
 text-align:center;
}
nav a{
 color:white;
 text-decoration:none;
 margin:8px;
}
section{
 background:white;
 margin:18px auto;
 padding:20px;
 max-width:850px;
 border-radius:12px;
}
h2{color:#263b80}
input,select,textarea{
 width:100%;
 padding:12px;
 margin:8px 0;
 border:1px solid #bbb;
 border-radius:6px;
}
button{
 background:#263b80;
 color:white;
 border:0;
 padding:12px 20px;
 border-radius:6px;
 cursor:pointer;
}
</style>
</head>
<body>

<header>
<h1>🎓 CampusCare</h1>
<p>Campus Problem Solving System</p>
</header>

<nav>
<a href="#home">Home</a>
<a href="#report">Report Problem</a>
<a href="#track">Track Complaint</a>
<a href="#admin">Admin</a>
</nav>

<section id="home">
<h2>Welcome to CampusCare</h2>
<p>Report your college problems easily.</p>
<p>We help students report campus issues.</p>
</section>

<section id="report">
<h2>Report a Problem</h2>

<label>Problem Category</label>
<select id="category">
<option value="">Select Category</option>
<option>Water Supply</option>
<option>Washroom</option>
<option>Electricity</option>
<option>Cleanliness</option>
<option>Classroom</option>
<option>Furniture</option>
<option>Other</option>
</select>

<label>Problem Location</label>
<input id="place" placeholder="Enter location">

<label>Problem Description</label>
<textarea id="description" placeholder="Describe your problem"></textarea>

<button onclick="submitComplaint()">Submit Complaint</button>
<p id="result"></p>
</section>
