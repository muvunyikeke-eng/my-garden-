# my-garden-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Gardens </title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
<div class="logo">
  <img src="garden.logo.jfif" alt="Garden logo">
  <span class="logo-text">My garden shop</span>
</div>




  <button class="menu-btn" aria-label="Open menu" onclick="toggleMenu()">☰</button>

  <nav id="nav">
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#activities">Activities</a>
    <a href="#boxes">Boxes</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>

<section id="home" class="hero-full">

  <div class="hero-overlay">
    <h1>Gardens – Grow better, naturally</h1>
    <p>Curated gardening boxes for every level. Start growing something beautiful today.</p>
    <a href="#boxes" class="hero-btn">View Boxes</a>
  </div>

</section>



<section id="about">
  <h2>About Gardens</h2>
  <p>
    Gardens is an online company operating in parts of Europe, Asia and New Zealand.
    We provide gardening boxes, activities and expert advice to help people grow and care
    for their gardens.
  </p>
</section>



 <section id="activities" class="activities-section">

  <h2 class="section-title">Our Activities</h2>

  <div class="activities-grid">

    <div class="activity-card">
      <div class="icon-box">🌳</div>
      <h3>Open Gardens</h3>
      <p>Visit stunning member gardens throughout the season and meet fellow enthusiasts.</p>
    </div>

    <div class="activity-card">
      <div class="icon-box">📅</div>
      <h3>Monthly Gardening Checklist</h3>
      <p>Never miss important seasonal tasks. Our checklist keeps your garden thriving.</p>
    </div>

    <div class="activity-card">
      <div class="icon-box">🌡️</div>
      <h3>Greenhouse Tips</h3>
      <p>Expert advice for maximising greenhouse productivity and temperature control.</p>
    </div>

    <div class="activity-card">
      <div class="icon-box">🛠️</div>
      <h3>Garden Maintenance Advice</h3>
      <p>Practical guidance on tools, techniques and timing to keep gardens healthy.</p>
    </div>

    <div class="activity-card">
      <div class="icon-box">🌱</div>
      <h3>Allotment Jobs</h3>
      <p>Seasonal tasks tailored for allotment holders, helping you stay organised.</p>
    </div>

    <div class="activity-card">
      <div class="icon-box">📘</div>
      <h3>Plant Diary & Progress Notes</h3>
      <p>Track successes, challenges and plans for future growing seasons.</p>
    </div>

    <div class="activity-card">
      <div class="icon-box">📷</div>
      <h3>Photographic Competitions</h3>
      <p>Showcase your garden and win exciting prizes in themed competitions.</p>
    </div>

    <div class="activity-card">
      <div class="icon-box">📊</div>
      <h3>Seasonal Surveys</h3>
      <p>Share experiences and help us improve by taking part in surveys.</p>
    </div>

    <div class="activity-card">
      <div class="icon-box">🎥</div>
      <h3>Online Advice Talks</h3>
      <p>Live sessions with experts covering soil health and pruning techniques.</p>
    </div>

  </div>
</section>



  <section id="boxes" class="boxes-section">

  <h2 class="section-title">Our Boxes</h2>

  <div class="boxes-grid">

    <!-- Flourish -->
    <div class="box-card-ui">
      <img src="flourish.jfif" alt="Flourish gardening box">

      <h3>Flourish</h3>

      <ul>
        <li>Four boxes per year</li>
        <li>Seeds & seed trays</li>
        <li>Watering can</li>
        <li>Handmade cruelty-free soap</li>
      </ul>

      <button class="box-btn" onclick="showBox('Flourish')">Read More</button>
    </div>

    <!-- Oddbox -->
    <div class="box-card-ui">
      <img src="oddbox.jfif" alt="Oddbox vegetables box">

      <h3>Oddbox</h3>

      <ul>
        <li>Wonky vegetables</li>
        <li>Weekly deliveries</li>
        <li>Vegetable seeds</li>
        <li>Gardening blog</li>
      </ul>

      <button class="box-btn" onclick="showBox('Oddbox')">Read More</button>
    </div>

    <!-- Cottage -->
    <div class="box-card-ui">
      <img src="cottage.jfif" alt="Cottage gardening box">
     


      <h3>Cottage</h3>

      <ul>
        <li>Monthly box</li>
        <li>Wild flower seeds</li>
        <li>Fact cards</li>
        <li>Seed markers & twine</li>
      </ul>

      <button class="box-btn" onclick="showBox('Cottage')">Read More</button>
    </div>

  </div>

  <p class="custom-note">
    Custom corporate and gift boxes are available. Please contact us to arrange custom boxes.
  </p>

</section>


  

  </div>

 
<section id="contact">
  <h2>Contact Us</h2>

  <form id="contactForm">

    <label for="name">Full name</label>
    <input id="name" type="text" required>

    <label for="email">Email address</label>
    <input id="email" type="email" required>

    <label for="message">Your message</label>
    <textarea id="message" required></textarea>

    <button type="submit">Send message</button>

    <p id="formMessage" role="alert"></p>

  </form>
</section>

</main>


<script src="script.js"></script>
</body>
</html>

<footer class="main-footer">

  <div class="footer-grid">

    <!-- Brand -->
    <div class="footer-brand">
      <img src="garden.logo.jfif" alt="Gardens logo" class="footer-logo">
      <p>
        Curated gardening boxes for every level.
        Start growing something beautiful today.
      </p>
    </div>

    <!-- Quick links -->
   <div>
  <h4>Quick Links</h4>
  <a href="#home">Home</a>
  <a href="#about">About Us</a>
  <a href="#activities">Activities</a>
  <a href="#boxes">Boxes</a>
  <a href="#contact">Contact</a>
</div>


    <!-- Shop -->
    <div>
      <h4>Shop</h4>
      <a href="#boxes">All Boxes</a>
      <a href="#">Beginner Boxes</a>
      <a href="#">Keen Gardener</a>
      <a href="#">Subscriptions</a>
    </div>

    <!-- Support -->
    <div>
      <h4>Support</h4>
      <a href="#contact">Contact Us</a>
      <a href="#">FAQs</a>
      <a href="#">Shipping Info</a>
      <a href="#">Privacy Policy</a>
    </div>

  </div>

</footer>

<style>
  *{
  box-sizing:border-box;
  font-family: Arial, sans-serif;
  .logo{
  display:flex;
  align-items:center;
  gap:10px;
}

.logo-text{
  color:white;
  font-weight:600;
  font-size:1.05rem;
}

}
.logo img{
  height:38px;
  width:auto;
  display:block;
}

.hero{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:30px;
  padding:60px 20px;
  align-items:center;
  background:#e8f5e9;
}

.hero-image img{
  width:100%;
  border-radius:12px;
  object-fit:cover;
}

.hero-btn{
  display:inline-block;
  margin-top:15px;
  padding:10px 18px;
  background:#2f7d32;
  color:white;
  text-decoration:none;
  border-radius:6px;
}

@media(max-width:800px){
  .hero{
    grid-template-columns:1fr;
    text-align:center;
  }
}


body{
  margin:0;
  line-height:1.6;
  background:#f4f7f5;
  color:#222;
}

header{
  display:flex;
  align-items:center;
  justify-content:space-between;
  padding:12px 20px;
  background:#2f7d32;
  color:white;
}

.logo{
  font-size:1.4rem;
  font-weight:bold;
}

nav a{
  color:white;
  text-decoration:none;
  margin-left:15px;
}

.menu-btn{
  display:none;
  font-size:1.5rem;
  background:none;
  border:none;
  color:white;
}

.hero-full{
  min-height:80vh;
  width:100%;
  background-image:url("garden2.jfif");
  background-size:cover;
  background-position:center;
  background-repeat:no-repeat;

  display:flex;
  align-items:center;
  justify-content:center;
}

.hero-overlay{
  background:rgba(0,0,0,0.45);
  color:white;
  padding:40px 30px;
  border-radius:14px;
  text-align:center;
  max-width:700px;
}

.hero-overlay h1{
  margin-bottom:12px;
}

.hero-overlay p{
  margin-bottom:20px;
}

.hero-btn{
  display:inline-block;
  padding:10px 22px;
  background:#f46b5b;
  color:white;
  text-decoration:none;
  border-radius:999px;
}



section{
  padding:40px 20px;
  max-width:1000px;
  margin:auto;
}

.activities-section{
  background:#faf6f4;
  padding:60px 20px;
}

.section-title{
  text-align:center;
  margin-bottom:40px;
}

.activities-grid{
  max-width:1100px;
  margin:auto;
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:25px;
}

.activity-card{
  background:white;
  border-radius:16px;
  padding:25px 22px;
  box-shadow:0 8px 20px rgba(0,0,0,0.05);
}

.icon-box{
  width:44px;
  height:44px;
  border-radius:10px;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:20px;
  background:#e7f7ef;
  margin-bottom:12px;
}

.activity-card h3{
  margin:10px 0 6px;
}

.activity-card p{
  color:#555;
  font-size:0.95rem;
}






.boxes-section{
  background:#faf6f4;
  padding:60px 20px;
}

.boxes-grid{
  max-width:1100px;
  margin:auto;
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:30px;
}

.box-card-ui{
  background:white;
  border-radius:22px;
  padding:20px;
  text-align:center;
  box-shadow:0 12px 25px rgba(0,0,0,0.06);
}

.box-card-ui img{
  width:100%;
  height:180px;
  object-fit:cover;
  border-radius:14px;
  margin-bottom:15px;
}

.box-card-ui h3{
  margin-bottom:12px;
}

.box-card-ui ul{
  list-style:none;
  padding:0;
  margin:0 0 20px 0;
}

.box-card-ui li{
  padding:6px 0;
  color:#555;
}

.box-btn{
  background:#f46b5b;
  color:white;
  border:none;
  padding:10px 22px;
  border-radius:999px;
  cursor:pointer;
  font-size:0.9rem;
}

.box-btn:hover{
  opacity:0.9;
}

.custom-note{
  text-align:center;
  margin-top:30px;
  font-weight:500;
}


  font-weight:bold;
}

form{
  max-width:500px;
  margin:auto;
  background:white;
  padding:20px;
  border-radius:8px;
}

label{
  display:block;
  margin-top:10px;
}

input, textarea{
  width:100%;
  padding:8px;
  margin-top:5px;
}

form button{
  margin-top:15px;
  width:100%;
  padding:10px;
  background:#2f7d32;
  color:white;
  border:none;
  border-radius:5px;
}

footer{
  background:#1b5e20;
  color:white;
  text-align:center;
  padding:15px;
}

/* RESPONSIVE */

@media(max-width:800px){

  .box-grid{
    grid-template-columns:1fr;
  }

  nav{
    display:none;
    flex-direction:column;
    background:#2f7d32;
    position:absolute;
    top:60px;
    right:0;
    width:200px;
  }

  nav a{
    padding:10px;
    border-top:1px solid rgba(255,255,255,0.3);
  }

  .menu-btn{
    display:block;
  }
}
.main-footer{
  background:#111;
  color:#ddd;
  padding:50px 20px;
  margin-top:60px;
}

.footer-grid{
  max-width:1100px;
  margin:auto;
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
  gap:30px;
}

.main-footer h4{
  color:#fff;
  margin-bottom:10px;
}

.footer-brand p{
  color:#bbb;
  margin-top:10px;
  max-width:260px;
}

.main-footer a{
  display:block;
  text-decoration:none;
  color:#ccc;
  margin:6px 0;
  font-size:0.95rem;
}

.main-footer a:hover{
  color:#fff;
}

.footer-logo{
  height:36px;
  width:auto;
}

</style>
<script>
  function toggleMenu(){
  const nav = document.getElementById("nav");

  if(nav.style.display === "flex"){
    nav.style.display = "none";
  }else{
    nav.style.display = "flex";
  }
}

function showBox(boxName){
  alert(boxName + " box is available. Please contact us for more details.");
}

document.getElementById("contactForm").addEventListener("submit", function(e){

  e.preventDefault();

  const message = document.getElementById("formMessage");
  message.textContent = "Thank you! Your message has been sent.";

  this.reset();
});

</script>
