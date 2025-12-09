# <!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Urban Thread — Home</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <a class="logo" href="index.html"><img src="assets/logo.png" alt="Urban Thread logo" /></a>
      <nav class="main-nav">
        <a href="index.html">Home</a>
        <a href="shop.html">Shop</a>
        <a href="categories.html">Categories</a>
        <a href="blog.html">Blog</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
      </nav>
      <div class="header-actions">
        <a class="icon" href="account.html">Account</a>
        <a class="icon" href="cart.html">Cart (0)</a>
      </div>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container hero-inner">
        <div class="hero-text">
          <h1>Wear your confidence.</h1>
          <p>Seasonal drops · sustainable fabrics · free shipping over $75</p>
          <a class="btn" href="shop.html">Shop New Arrivals</a>
        </div>
      </div>
    </section>

    <section class="featured container">
      <h2>Featured Collections</h2>
      <div class="grid cards-3">
        <article class="card">
          <img src="assets/featured1.jpg" alt="">
          <h3>Everyday Essentials</h3>
          <p>Soft tees and comfortable fits</p>
          <a href="categories.html">Browse</a>
        </article>
        <article class="card">
          <img src="assets/featured2.jpg" alt="">
          <h3>Weekend Wear</h3>
          <p>Casual, chill & stylish</p>
          <a href="categories.html">Browse</a>
        </article>
        <article class="card">
          <img src="assets/featured3.jpg" alt="">
          <h3>Outerwear</h3>
          <p>Coats and jackets for every season</p>
          <a href="categories.html">Browse</a>
        </article>
      </div>
    </section>

    <section class="container newsletter">
      <h2>Get 10% off — Join our email list</h2>
      <form class="newsletter-form" onsubmit="event.preventDefault(); alert('Thanks!')">
        <input type="email" placeholder="Your email" required>
        <button class="btn">Subscribe</button>
      </form>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-inner">
      <div>
        <strong>Urban Thread</strong>
        <p>Quality clothing, conscious choices.</p>
      </div>
      <nav class="footer-nav">
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
        <a href="blog.html">Blog</a>
        <a href="shop.html">Shop</a>
      </nav>
    </div>
    <div class="copyright">© <span id="year"></span> Urban Thread</div>
  </footer>

  <script src="js/main.js"></script>
</body>
</html>
