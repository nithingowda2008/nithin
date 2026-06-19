<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Personal Website</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
font-family:'Segoe UI',sans-serif;
}

body{
background:#f5f7ff;
color:#333;
}

nav{
position:sticky;
top:0;
background:linear-gradient(90deg,#6a11cb,#2575fc);
padding:15px;
z-index:100;
}

nav ul{
display:flex;
justify-content:center;
gap:25px;
list-style:none;
}

nav a{
color:white;
text-decoration:none;
font-weight:bold;
}

.hero{
height:100vh;
background:linear-gradient(135deg,#6a11cb,#2575fc,#00c6ff);
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
color:white;
padding:20px;
}

.hero img{
width:180px;
height:180px;
border-radius:50%;
border:5px solid white;
object-fit:cover;
margin-bottom:20px;
}

.hero h1{
font-size:3rem;
}

.hero p{
font-size:1.3rem;
margin-top:10px;
}

.btn{
margin-top:20px;
padding:12px 25px;
background:white;
color:#2575fc;
border-radius:30px;
text-decoration:none;
font-weight:bold;
}

section{
padding:70px 10%;
}

.section-title{
text-align:center;
font-size:2rem;
margin-bottom:30px;
color:#2575fc;
}

.about,
.contact{
background:white;
border-radius:15px;
padding:30px;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.skills{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.skill-card{
background:linear-gradient(135deg,#2575fc,#6a11cb);
color:white;
padding:25px;
border-radius:15px;
text-align:center;
transition:.3s;
}

.skill-card:hover{
transform:translateY(-8px);
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.gallery img{
width:100%;
height:250px;
object-fit:cover;
border-radius:15px;
transition:.4s;
}

.gallery img:hover{
transform:scale(1.05);
}

footer{
background:#222;
color:white;
text-align:center;
padding:20px;
}

</style>
</head>

<body>

<nav>
<ul>
<li><a href="#about">About</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<section class="hero">
<img src="profile.jpg" alt="Profile">
<h1>Your Name</h1>
<p>Student | Entrepreneur | Creator</p>
<a href="#about" class="btn">Explore My Profile</a>
</section>

<section id="about">
<h2 class="section-title">About Me</h2>

<div class="about">
<p>
Write your biography here.
Tell visitors who you are,
what you do, your goals,
achievements and dreams.
</p>
</div>
</section>

<section id="skills">
<h2 class="section-title">My Skills</h2>

<div class="skills">

<div class="skill-card">
<h3>Web Design</h3>
<p>Add details</p>
</div>

<div class="skill-card">
<h3>Logo Design</h3>
<p>Add details</p>
</div>

<div class="skill-card">
<h3>Video Editing</h3>
<p>Add details</p>
</div>

<div class="skill-card">
<h3>Business</h3>
<p>Add details</p>
</div>

</div>
</section>

<section id="gallery">
<h2 class="section-title">My Photos</h2>

<div class="gallery">
<img src="photo1.jpg">
<img src="photo2.jpg">
<img src="photo3.jpg">
<img src="photo4.jpg">
</div>

</section>

<section id="contact">
<h2 class="section-title">Contact Me</h2>

<div class="contact">

<p><strong>Email:</strong> yourmail@gmail.com</p>

<p><strong>Instagram:</strong> @yourusername</p>

<p><strong>YouTube:</strong> Your Channel</p>

<p><strong>Location:</strong> India</p>

</div>
</section>

<footer>
<h3>Thank You For Visiting My Website ❤️</h3>
</footer>

</body>
</html>
