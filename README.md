<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>EstelarPay - Global Payments, Local Settlements</title>
  <style>
    /* Basic reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f8f9fa;
      color: #333;
    }

    header {
      background: #0c487f;
      color: #fff;
      padding: 1.5em 0;
      text-align: center;
    }

    header h1 {
      font-size: 2.5em;
    }

    nav {
      margin-top: 1em;
    }

    nav a {
      color: #fff;
      margin: 0 0.8em;
      text-decoration: none;
      font-weight: bold;
    }

    .container {
      width: 90%;
      max-width: 1200px;
      margin: 2em auto;
    }

    section {
      margin-bottom: 3em;
      padding: 1em;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    section h2 {
      margin-bottom: 0.5em;
      color: #0c487f;
      text-align: center;
    }

    section p {
      margin-bottom: 1em;
      text-align: justify;
    }

    .hero {
      background: url('https://via.placeholder.com/1200x600?text=EstelarPay+Hero') center/cover no-repeat;
      height: 60vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.7);
    }

    .hero h2 {
      font-size: 3em;
      background: rgba(12, 72, 127, 0.8);
      padding: 0.5em 1em;
      border-radius: 4px;
    }

    footer {
      background: #0c487f;
      color: #fff;
      text-align: center;
      padding: 1em 0;
    }

    /* Responsive */
    @media (max-width: 768px) {
      header h1 {
        font-size: 2em;
      }
      
      .hero h2 {
        font-size: 2em;
      }
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h1>EstelarPay</h1>
    <nav>
      <a href="#vision">Vision</a>
      <a href="#objectives">Objectives</a>
      <a href="#integration">Integration</a>
      <a href="#traction">Traction</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  
  <!-- Hero Section -->
  <div class="hero">
    <h2>Global Payments, Local Settlements</h2>
  </div>
  
  <!-- Main Container -->
  <div class="container">
    <!-- Vision Section -->
    <section id="vision">
      <h2>Our Vision</h2>
      <p>
        At EstelarPay, we believe in breaking financial barriers. Our vision is to connect tourists and local businesses, enabling global currency to seamlessly transform into local payments. We build a bridge between traditional systems and blockchain technology to offer a secure, fast, and accessible experience for everyone.
      </p>
    </section>
    
    <!-- Objectives Section -->
    <section id="objectives">
      <h2>Our Objectives</h2>
      <p><strong>Short Term (6-12 months):</strong> Develop and launch an MVP in Buenos Aires and establish strategic partnerships with loading agents and merchants.</p>
      <p><strong>Mid Term (12-24 months):</strong> Expand nationally, integrate new loading methods, and optimize our platform for greater scalability.</p>
      <p><strong>Long Term (2-5 years):</strong> Expand EstelarPay throughout LATAM, becoming the standard for tourist payments in emerging economies.</p>
    </section>
    
    <!-- Integration Section -->
    <section id="integration">
      <h2>Technical Integration</h2>
      <p>
        Our platform integrates directly with the Stellar network to handle USDT transactions at low cost and high speed. We use real-time oracles for currency conversion (USDT to ARS) and establish connections with liquidity providers and physical agents for fund loading. In addition, we implement KYC/AML modules to ensure regulatory compliance and fund security.
      </p>
      <ul>
        <li><strong>Blockchain:</strong> Direct integration with Stellar using official tools and SDKs.</li>
        <li><strong>Real-Time Conversion:</strong> Oracles that fetch reliable pricing data.</li>
        <li><strong>Physical Loading:</strong> Partnerships with exchange houses and crypto kiosks.</li>
        <li><strong>Security:</strong> Identity verification and real-time transaction monitoring.</li>
      </ul>
    </section>
    
    <!-- Traction Section -->
    <section id="traction">
      <h2>Current Traction</h2>
      <p>
        Even though we are in an early stage, we have validated our concept through market studies, focus groups, and letters of intent from exchange agents and merchants. A functional prototype has been developed on Stellar's testnet, and we have established our first strategic contacts within the blockchain industry.
      </p>
    </section>
    
    <!-- Contact Section -->
    <section id="contact">
      <h2>Contact</h2>
      <p>
        Want to learn more or join this revolutionary project?
      </p>
      <p>
        Email: <strong>contact@estelar-pay.com</strong><br>
        Tel: <strong>+54 9 11 3231-1168</strong>
      </p>
    </section>
  </div>
  
  <!-- Footer -->
  <footer>
    <p>&copy; 2025 EstelarPay. All rights reserved.</p>
  </footer>
  
  <!-- Basic Script (optional) -->
  <script>
    // Smooth scrolling for navigation links
    document.querySelectorAll('nav a').forEach(link => {
      link.addEventListener('click', function(e) {
        e.preventDefault();
        const targetId = this.getAttribute('href');
        document.querySelector(targetId).scrollIntoView({
          behavior: 'smooth'
        });
      });
    });
  </script>
</body>
</html>
