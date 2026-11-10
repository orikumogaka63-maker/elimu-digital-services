# elimu-digital-services

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Elimu Digital Services</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:Arial,sans-serif;background:#f5f7fb;color:#172033;line-height:1.6}
header{background:#102b50;color:white;padding:18px 7%;display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:12px}
.logo{font-size:21px;font-weight:bold}
nav{display:flex;gap:16px;flex-wrap:wrap}
nav a{color:white;text-decoration:none;font-size:14px}
.hero{background:linear-gradient(130deg,#102b50,#087e9c);color:white;text-align:center;padding:85px 20px}
.hero h1{font-size:clamp(30px,6vw,48px);margin-bottom:15px}
.hero p{max-width:650px;margin:auto auto 25px}
.btn{display:inline-block;background:#ffbd35;color:#172033;padding:13px 22px;border-radius:7px;text-decoration:none;font-weight:bold}
section{padding:60px 7%}
.heading{text-align:center;margin-bottom:35px}
.heading h2{font-size:30px;color:#102b50}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:22px}
.card{background:white;padding:25px;border-radius:12px;box-shadow:0 4px 15px #0000000c}
.card h3{color:#087e9c;margin:12px 0}
.symbol{font-size:35px}
.card p{color:#596579}
.about{background:#e8f2f8}
.price{color:#087e9c;font-weight:bold;margin-top:12px}
.steps{max-width:700px;margin:auto}
.steps p{padding:12px 0}
.contact{background:#102b50;color:white;text-align:center}
.contact h2{color:white}
.contact p{margin:12px auto 22px;max-width:600px}
.contact a{margin:7px}
footer{text-align:center;background:#091b31;color:white;padding:22px;font-size:14px}
@media(max-width:600px){
header{justify-content:center}
nav{justify-content:center}
.hero{padding:65px 18px}
section{padding:45px 6%}
}
</style>
</head>
<body>

<header>
<div class="logo">ELIMU DIGITAL SERVICES</div>
<nav>
<a href="#home">Home</a>
<a href="#services">Services</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>
</header>

<main>
<section class="hero" id="home">
<h1>Your Ideas. Our Digital Solutions.</h1>
<p>Welcome to Elimu Digital Services. We help individuals and small businesses with creative designs, websites and professional typing services.</p>
<a class="btn" href="#services">Explore Our Services</a>
</section>

<section id="services">
<div class="heading">
<h2>Our Services</h2>
<p>Simple, affordable digital solutions.</p>
</div>
<div class="cards">
<div class="card">
<div class="symbol">🎨</div>
<h3>Graphic Design</h3>
<p>We create attractive posters, flyers, invitations and promotional designs for your events and business.</p>
<p class="price">Request a quotation</p>
</div>
<div class="card">
<div class="symbol">💻</div>
<h3>Website Creation</h3>
<p>We create simple, modern and mobile-friendly websites for small businesses and individuals.</p>
<p class="price">Request a quotation</p>
</div>
<div class="card">
<div class="symbol">📝</div>
<h3>Typing Services</h3>
<p>Get help with typing, document formatting, letters and other general document preparation.</p>
<p class="price">Request a quotation</p>
</div>
</div>
</section>

<section class="about" id="about">
<div class="heading">
<h2>About Us</h2>
</div>
<div class="steps">
<p>Elimu Digital Services is a growing digital service initiative focused on helping people access useful and affordable digital solutions.</p>
<p>Our goal is to make digital services simple, accessible and reliable for individuals and small businesses.</p>
<p><strong>Our values:</strong> Creativity, reliability, affordability and good customer service.</p>
</div>
</section>

<section>
<div class="heading">
<h2>How It Works</h2>
<p>Getting started is easy.</p>
</div>
<div class="steps">
<p>📌 <strong>1. Choose:</strong> Select the service you need.</p>
<p>💬 <strong>2. Contact:</strong> Tell us what you want.</p>
<p>📋 <strong>3. Agree:</strong> Confirm the price, requirements and delivery time.</p>
<p>✅ <strong>4. Receive:</strong> Review and receive your completed work.</p>
</div>
</section>

<section class="contact" id="contact">
<div class="heading">
<h2>Let's Work Together!</h2>
</div>
<p>Have a project or need a digital service? Contact us to discuss your requirements and get a quotation.</p>
<a class="btn" href="#" id="whatsapp">Contact Us on WhatsApp</a>
<p>We look forward to working with you!</p>
</section>
</main>

<footer>
<p>© 2026 Elimu Digital Services. All rights reserved.</p>
<p>Creative solutions. Digital opportunities.</p>
</footer>

<script>
// Replace this with your WhatsApp number,
// including Kenya's country code 254.
const WHATSAPP_NUMBER = "YOUR_WHATSAPP_NUMBER";

document.getElementById("whatsapp").addEventListener("click", function(e){
e.preventDefault();

if(WHATSAPP_NUMBER === "YOUR_WHATSAPP_NUMBER"){
alert("Please add your WhatsApp number in the website code first.");
return;
}

const message = encodeURIComponent(
"Hello Elimu Digital Services! I would like to inquire about your services."
);

window.open(
"https://wa.me/" + WHATSAPP_NUMBER + "?text=" + message,
"_blank"
);
});
</script>

</body>
</html>
