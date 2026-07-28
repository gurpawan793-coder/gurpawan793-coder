<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Gurpawan Singh | Cloud & DevOps Portfolio</title>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<!-- Font Awesome -->
<link rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:'Poppins',sans-serif;
    background:#0f172a;
    color:#fff;
    line-height:1.7;
}

a{
    text-decoration:none;
    color:white;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
}

section{
    padding:80px 0;
}

.title{
    font-size:38px;
    text-align:center;
    margin-bottom:50px;
    color:#38bdf8;
}

/* Navbar */

nav{
    position:fixed;
    width:100%;
    top:0;
    z-index:1000;
    background:#111827;
    padding:18px 0;
}

nav .container{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:28px;
    font-weight:bold;
    color:#38bdf8;
}

nav ul{
    display:flex;
    list-style:none;
    gap:30px;
}

nav ul li a:hover{
    color:#38bdf8;
}

/* Hero */

.hero{
    min-height:100vh;
    display:flex;
    align-items:center;
}

.hero-content{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
    align-items:center;
    gap:60px;
}

.hero-text h1{
    font-size:60px;
}

.hero-text h2{
    color:#38bdf8;
    margin:15px 0;
}

.hero-text p{
    color:#cbd5e1;
    margin:20px 0;
}

.btn{
    display:inline-block;
    background:#38bdf8;
    color:#000;
    padding:14px 35px;
    border-radius:30px;
    font-weight:600;
    transition:.3s;
}

.btn:hover{
    transform:translateY(-4px);
}

.hero-img{
    text-align:center;
}

.hero-img img{
    width:320px;
    border-radius:50%;
    border:5px solid #38bdf8;
}

/* Cards */

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(270px,1fr));
    gap:25px;
}

.card{
    background:#1e293b;
    padding:30px;
    border-radius:15px;
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card i{
    font-size:35px;
    color:#38bdf8;
    margin-bottom:15px;
}

.card h3{
    margin-bottom:15px;
}

/* Skills */

.skills{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:15px;
}

.skill{
    background:#1e293b;
    padding:14px 22px;
    border-radius:40px;
    font-weight:500;
}

/* Projects */

.project{
    background:#1e293b;
    padding:25px;
    border-radius:15px;
}

.project h3{
    color:#38bdf8;
    margin-bottom:15px;
}

.project ul{
    margin-left:20px;
}

/* Footer */

footer{
    background:#111827;
    text-align:center;
    padding:35px;
}

.social{
    margin-top:20px;
}

.social a{
    margin:10px;
    font-size:24px;
}

.social a:hover{
    color:#38bdf8;
}

@media(max-width:768px){

.hero-text h1{
    font-size:42px;
}

nav ul{
    display:none;
}

}

</style>

</head>

<body>

<nav>

<div class="container">

<div class="logo">Gurpawan Singh</div>

<ul>

<li><a href="#about">About</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#contact">Contact</a></li>

</ul>

</div>

</nav>

<!-- Hero -->

<section class="hero">

<div class="container hero-content">

<div class="hero-text">

<h1>Hi 👋<br>I'm <span style="color:#38bdf8;">Gurpawan Singh</span></h1>

<h2>Aspiring Cloud & DevOps Engineer</h2>

<p>

Business Administration graduate passionate about Cloud Computing,
DevOps, Linux, AWS, Docker, Terraform, and Automation.

Currently building real-world cloud projects while continuously
learning modern technologies.

</p>

<a href="#projects" class="btn">View Projects</a>

</div>

<div class="hero-img">

<img src="https://i.imgur.com/QCNbOAo.png" alt="Profile">

</div>

</div>

</section>

<!-- About -->

<section id="about">

<div class="container">

<h2 class="title">About Me</h2>

<div class="card">

<p>

I'm <strong>Gurpawan Singh</strong>, a BBA graduate with an immense
passion for Information Technology and Cloud Computing.

Although my academic background is in Business Administration,
I have dedicated myself to mastering AWS, Linux,
Docker, Terraform, CI/CD, and DevOps practices.

My goal is to become a Cloud & DevOps Engineer capable of building
scalable, secure, and highly available cloud infrastructures.

</p>

</div>

</div>

</section>

<!-- Skills -->

<section id="skills">

<div class="container">

<h2 class="title">Skills</h2>

<div class="skills">

<div class="skill">AWS</div>
<div class="skill">Linux</div>
<div class="skill">Docker</div>
<div class="skill">Terraform</div>
<div class="skill">Jenkins</div>
<div class="skill">Git</div>
<div class="skill">GitHub</div>
<div class="skill">Bash</div>
<div class="skill">Python</div>
<div class="skill">Networking</div>
<div class="skill">CI/CD</div>
<div class="skill">Cloud Security</div>

</div>

</div>

</section>

<!-- Projects -->

<section id="projects">

<div class="container">

<h2 class="title">Projects</h2>

<div class="grid">

<div class="project">

<h3><i class="fa-solid fa-cloud"></i> AWS Cloud Projects</h3>

<ul>

<li>EC2 Deployment</li>
<li>IAM User Management</li>
<li>S3 Storage</li>
<li>VPC Configuration</li>
<li>Route53 DNS</li>

</ul>

</div>

<div class="project">

<h3><i class="fa-brands fa-docker"></i> Docker Projects</h3>

<ul>

<li>Containerized Applications</li>
<li>Docker Networking</li>
<li>Docker Compose</li>
<li>Volumes</li>

</ul>

</div>

<div class="project">

<h3><i class="fa-solid fa-gears"></i> DevOps Automation</h3>

<ul>

<li>Jenkins Pipelines</li>
<li>GitHub Integration</li>
<li>CI/CD Automation</li>
<li>Deployment Workflows</li>

</ul>

</div>

<div class="project">

<h3><i class="fa-solid fa-code"></i> Terraform</h3>

<ul>

<li>Infrastructure as Code</li>
<li>AWS Provisioning</li>
<li>Automated Resources</li>

</ul>

</div>

</div>

</div>

</section>

<!-- Learning -->

<section>

<div class="container">

<h2 class="title">Currently Learning</h2>

<div class="grid">

<div class="card">

<i class="fa-solid fa-book-open"></i>

<h3>Learning</h3>

<p>

AWS • Kubernetes • Terraform • Docker • Jenkins • Linux
Administration • GitHub Actions • Cloud Security

</p>

</div>

<div class="card">

<i class="fa-solid fa-bullseye"></i>

<h3>Career Goal</h3>

<p>

To start my career as a Cloud & DevOps Engineer while building
secure, scalable and automated cloud infrastructures.

</p>

</div>

</div>

</div>

</section>

<!-- Contact -->

<section id="contact">

<div class="container">

<h2 class="title">Contact</h2>

<div class="card" style="text-align:center;">

<h3>Let's Connect</h3>

<p>Feel free to reach out for collaboration or networking.</p>

<div class="social">

<a href="#"><i class="fab fa-github"></i></a>

<a href="#"><i class="fab fa-linkedin"></i></a>

<a href="#"><i class="fas fa-envelope"></i></a>

</div>

</div>

</div>

</section>

<footer>

<p>

© 2026 Gurpawan Singh | Cloud & DevOps Portfolio

</p>

</footer>

</body>
</html>
