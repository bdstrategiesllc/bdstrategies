<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>B&D Strategies</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #ffffff;
      color: #000000;
    }
    header {
      background: #000;
      color: #fff;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1, header p {
      margin: 0;
    }
    nav a {
      color: #fff;
      margin-left: 20px;
      text-decoration: none;
    }
    .hero {
      padding: 100px 20px;
      text-align: center;
    }
    .section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .section h2 {
      margin-bottom: 20px;
    }
    .logo-placeholder {
      width: 80px;
      height: 80px;
      background: #ccc;
      display: inline-block;
      border-radius: 50%;
      margin-right: 10px;
    }
    footer {
      background: #000;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #000;
    }
    form button {
      background: #000;
      color: #fff;
      padding: 10px 20px;
      border: none;
    }
  </style>
</head>
<body>
  <header>
    <div style="display: flex; align-items: center;">
      <div class="logo-placeholder"></div>
      <div>
        <h1>B&D Strategies</h1>
        <p>Empowering Growth Inspiring Success</p>
      </div>
    </div>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h2>Welcome to B&D Strategies</h2>
    <p>Your partner in business and development success.</p>
  </section>

  <section class="section" id="about">
    <h2>About Us</h2>
    <p>B&D Strategies is dedicated to empowering businesses to grow and thrive. We combine experience with innovation to deliver strategic results that matter.</p>
  </section>

  <section class="section" id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Business Consultation</li>
      <li>Strategic Development Planning</li>
      <li>Market Research and Analysis</li>
      <li>Growth Strategy Implementation</li>
    </ul>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    &copy; 2025 B&D Strategies. All rights reserved.
  </footer>
</body>
</html>
