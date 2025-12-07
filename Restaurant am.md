<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>algharbawy — Fine Dining</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin:0;
      background:#0f1115;
      color:#eaeaea;
      font-family:"Inter", sans-serif;
      line-height:1.7;
    }
    header {
      text-align:center;
      padding:30px 20px;
      border-bottom:1px solid rgba(176,137,104,0.3);
    }
    .brand {
      font-family:"Playfair Display", serif;
      font-size:32px;
      font-weight:700;
      color:#b08968;
    }
    nav a {
      margin:0 8px;
      color:#eaeaea;
      text-decoration:none;
      border:1px solid rgba(176,137,104,0.3);
      padding:6px 12px;
      border-radius:8px;
    }
    main {
      max-width:1000px;
      margin:30px auto;
      padding:0 20px;
    }
    section {
      margin-bottom:30px;
      padding:20px;
      border:1px solid rgba(176,137,104,0.3);
      border-radius:12px;
      background:rgba(255,255,255,0.02);
    }
    h2 {
      font-family:"Playfair Display", serif;
      color:#b08968;
      margin-top:0;
    }
    h3 {margin:10px 0 6px;}
    .desc {color:#b7bdc5;}
    .img {
      width:100%;
      border-radius:12px;
      margin-top:10px;
    }
    footer {
      text-align:center;
      padding:20px;
      border-top:1px solid rgba(176,137,104,0.3);
      color:#b7bdc5;
    }
    .cta {
      display:inline-block;
      margin-top:10px;
      padding:10px 16px;
      border-radius:10px;
      border:1px solid rgba(176,137,104,0.45);
      color:#eaeaea;
      text-decoration:none;
      background:rgba(176,137,104,0.1);
    }
  </style>
</head>
<body>

<header>
  <div class="brand">algharbawy</div>
  <p>Rustic spirit with fine dining elegance</p>
  <nav>
    <a href="#menu">Menu</a>
    <a href="#contact">Contact</a>
    <a href="https://www.instagram.com/algharbawy_official?igsh=MWd1amIzam9mZjdseA==" target="_blank">Instagram</a>
  </nav>
</header>

<main id="menu">
  <section>
    <h2>Appetizer</h2>
    <h3>Seafood Salad with Citrus and Herbs</h3>
    <p class="desc">Shrimp, calamari, and octopus with fennel, cucumber ribbons, and greens in a lemon vinaigrette.</p>
    <img class="img" src="https://source.unsplash.com/1200x800/?seafood,salad" alt="Seafood Salad"/>
  </section>

  <section>
    <h2>Main Course</h2>
    <h3>Basmati Rice with Local Bone-in Chicken Thighs</h3>
    <p class="desc">Chicken thighs stuffed with vegetables, served over fragrant basmati rice with silky lemon butter sauce.</p>
    <img class="img" src="https://source.unsplash.com/1200x800/?basmati,rice,chicken" alt="Basmati Rice and Chicken"/>
  </section>

  <section>
    <h2>Desserts</h2>
    <h3>Cheesecakes with Professional Design</h3>
    <ul>
      <li>Vanilla bean cheesecake with gold leaf</li>
      <li>Rose & pistachio cheesecake with praline</li>
      <li>Honey-date caramel cheesecake with almond crust</li>
      <li>Dark chocolate tahini cheesecake with sesame brittle</li>
    </ul>
    <img class="img" src="https://source.unsplash.com/1200x800/?cheesecake,dessert" alt="Cheesecake"/>
  </section>
</main>

<footer id="contact">
  <p>For reservations call: +2001096898224</p>
  <p>Open 24 hours daily</p>
  <!-- Quick WhatsApp link -->
  <a class="cta" href="https://wa.me/2001096898224" target="_blank">Message us on WhatsApp</a>
</footer>

</body>
</html>
