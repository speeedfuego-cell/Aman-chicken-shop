<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Aman Chicken Shop | Fresh Chicken & Fish since 2007</title>
  <style>
    body {margin:0;font-family:Arial,Helvetica,sans-serif;background:#fff;color:#222;}
    header {background:#b30000;color:#fff;text-align:center;padding:2rem 1rem;}
    header h1 {margin:0;font-size:2rem;}
    header p {margin:.3rem 0 0;font-style:italic;}
    nav {background:#fff;border-bottom:2px solid #b30000;text-align:center;}
    nav a {display:inline-block;color:#b30000;padding:1rem;text-decoration:none;font-weight:bold;}
    nav a:hover {background:#b30000;color:#fff;}
    section {padding:2rem 1rem;max-width:900px;margin:auto;}
    .hero {background:url('A_high-resolution_digital_photograph_features_raw_.png') center/cover no-repeat;
           color:#fff;text-shadow:1px 1px 4px #000;padding:6rem 1rem;text-align:center;}
    .hero h2 {font-size:2rem;margin:0;}
    .menu-table {width:100%;border-collapse:collapse;margin-top:1rem;}
    .menu-table td, .menu-table th {border:1px solid #ddd;padding:.6rem;text-align:left;}
    .menu-table th {background:#b30000;color:#fff;}
    .gallery img {width:100%;max-width:280px;margin:.5rem;border-radius:10px;box-shadow:0 0 5px rgba(0,0,0,.3);}
    footer {background:#b30000;color:#fff;text-align:center;padding:1rem;font-size:.9rem;}
    #langModal {position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,.8);
                display:flex;justify-content:center;align-items:center;z-index:1000;}
    #langModal div {background:#fff;padding:2rem;border-radius:10px;text-align:center;}
    #langModal button {margin:.5rem;padding:.6rem 1.2rem;border:none;border-radius:5px;
                       background:#b30000;color:#fff;font-weight:bold;cursor:pointer;}
    #langModal button:hover {background:#900;}
    @media(max-width:600px){header h1{font-size:1.5rem;}.hero h2{font-size:1.3rem;}}
  </style>
</head>
<body>

<!-- Language selection -->
<div id="langModal">
  <div>
    <h2>Select Language</h2>
    <div id="langBtns"></div>
  </div>
</div>

<header>
  <h1>Aman Chicken Shop</h1>
  <p>Fresh Chicken & Fish since 2007 • Gurugram, Haryana</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#products">Products & Prices</a>
  <a href="#gallery">Gallery</a>
  <a href="#location">Location</a>
  <a href="#contact">Contact</a>
</nav>

<section id="home" class="hero">
  <h2>Freshly Cut Chicken – Quality You Can Trust</h2>
</section>

<section id="about">
  <h2>About Us</h2>
  <p>
    Aman Chicken Shop has been proudly serving Gurugram since 2007. 
    We specialize in fresh, hygienically cut chicken and quality fish. 
    Our commitment is simple: deliver the freshest meat every day with honesty and care.
  </p>
</section>

<section id="products">
  <h2>Products & Prices</h2>
  <table class="menu-table">
    <tr><th>Item</th><th>Price</th></tr>
    <tr><td>Fresh Chicken</td><td>₹240 / kg</td></tr>
    <tr><td>Fresh Fish</td><td>Visit shop for updated price</td></tr>
  </table>
</section>

<section id="gallery">
  <h2>Our Shop</h2>
  <div class="gallery">
    <img src="shop1.jpg" alt="Aman Chicken Shop exterior">
    <img src="shop2.jpg" alt="Inside Aman Chicken Shop">
    <img src="A_high-resolution_digital_photograph_features_raw_.png" alt="Fresh chicken cuts">
  </div>
</section>

<section id="location">
  <h2>Location</h2>
  <p>Find us here:</p>
  <iframe
    src="https://www.google.com/maps?q=G22H+JG7+Gurugram,+Haryana&output=embed"
    width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy">
  </iframe>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Phone / WhatsApp: (Add later)</p>
  <p>Visit us at: G22H+JG7 Gurugram, Haryana</p>
</section>

<footer>
  © 2025 Aman Chicken Shop | Fresh Taste Daily
</footer>

<script>
  // Language options
  const langs = ["English","Hindi","Tamil","Telugu","Bengali","Marathi","Gujarati","Punjabi"];
  const container = document.getElementById('langBtns');
  langs.forEach(l=>{
    const btn=document.createElement('button');
    btn.textContent=l;
    btn.onclick=()=>{document.getElementById('langModal').style.display='none';};
    container.appendChild(btn);
  });
</script>

</body>
</html>
