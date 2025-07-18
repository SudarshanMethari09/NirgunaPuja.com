# NirgunaPuja.com
Spritual Store and services 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>NirgunaPuja - Divine Store & Services</title>
  <style>
    :root {
      --saffron: #FF9933;
      --gold: #FFD700;
      --dark: #2e2e2e;
      --white: #fff;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--white);
      color: var(--dark);
    }

    header {
      background: var(--saffron);
      color: var(--white);
      padding: 1rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2rem;
      letter-spacing: 1px;
    }

    nav {
      display: flex;
      justify-content: center;
      background: var(--gold);
      padding: 0.5rem;
    }

    nav a {
      color: var(--dark);
      text-decoration: none;
      margin: 0 1rem;
      font-weight: bold;
    }

    .hero {
      background: url('https://i.imgur.com/zUEHcLq.jpg') center/cover no-repeat;
      color: var(--white);
      padding: 5rem 1rem;
      text-align: center;
    }

    .hero h2 {
      font-size: 2.5rem;
      background: rgba(0, 0, 0, 0.5);
      display: inline-block;
      padding: 0.5rem 1rem;
      border-radius: 10px;
    }

    section {
      padding: 2rem 1rem;
      max-width: 1000px;
      margin: auto;
    }

    .products, .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .card {
      border: 1px solid #ddd;
      border-radius: 12px;
      padding: 1rem;
      background: #fff8e7;
      box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.1);
      text-align: center;
    }

    .card img {
      max-width: 100%;
      border-radius: 8px;
      height: 150px;
      object-fit: cover;
    }

    .card h3 {
      margin-top: 1rem;
      font-size: 1.2rem;
    }

    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 0.75rem;
      margin: 0.5rem 0;
      border-radius: 8px;
      border: 1px solid #ccc;
    }

    .contact-form button {
      background: var(--saffron);
      border: none;
      padding: 0.75rem 1.5rem;
      color: white;
      font-weight: bold;
      cursor: pointer;
      border-radius: 8px;
    }

    footer {
      background: var(--dark);
      color: var(--white);
      text-align: center;
      padding: 1rem;
    }

    @media (max-width: 600px) {
      .hero h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>🕉 NirgunaPuja</h1>
    <p>Spiritual Products • Yantras • Astrology • Guidance</p>
  </header>

  <nav>
    <a href="#products">Products</a>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>Awaken the Divine Within</h2>
  </section>

  <section id="products">
    <h2>🛍️ Puja Products</h2>
    <div class="products">
      <div class="card">
        <img src="https://i.imgur.com/LkqCWyH.jpg" alt="Yantra" />
        <h3>Baglamukhi Yantra</h3>
        <p>Powerful protection and victory energy</p>
      </div>
      <div class="card">
        <img src="https://i.imgur.com/MnZ5o6O.jpg" alt="Murti" />
        <h3>Brass Puja Idols</h3>
        <p>Finely crafted murti of deities</p>
      </div>
      <div class="card">
        <img src="https://i.imgur.com/Ey2kpqL.jpg" alt="Book" />
        <h3>Tantra Books</h3>
        <p>Ancient sadhana guides & mantras</p>
      </div>
    </div>
  </section>

  <section id="services">
    <h2>🔮 Our Services</h2>
    <div class="services">
      <div class="card">
        <h3>Astrology</h3>
        <p>Personal horoscope, remedies, match-making, & guidance</p>
      </div>
      <div class="card">
        <h3>Custom Yantras</h3>
        <p>Designed by sadhaks with energized mantras</p>
      </div>
      <div class="card">
        <h3>Spiritual Coaching</h3>
        <p>One-on-one guidance from experienced practitioners</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h2>🕯️ About NirgunaPuja</h2>
    <p>NirgunaPuja is a humble initiative to bring spiritual seekers closer to divine energies through authentic puja items, books, yantras, and astrological services. We believe in tradition, devotion, and energy alignment for life transformation.</p>
  </section>

  <section id="contact">
    <h2>📩 Contact Us</h2>
    <form class="contact-form" onsubmit="sendForm(); return false;">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Email Address" required />
      <textarea rows="4" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 NirgunaPuja. All Rights Reserved.</p>
  </footer>

  <script>
    function sendForm() {
      alert("Thank you for contacting NirgunaPuja. We'll get back to you soon.");
      document.querySelector('.contact-form').reset();
    }
  </script>

</body>
</html>
