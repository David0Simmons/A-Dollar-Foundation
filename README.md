<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>A Dollar Foundation - It only takes a dollar to change a life</title>
  <style>
    /* === General Styles === */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
    }
    .container {
      width: 90%;
      max-width: 1100px;
      margin: auto;
    }

    /* === Header & Navigation === */
    header {
      background: #f4f4f4;
      padding: 10px 0;
      border-bottom: 2px solid #004080;
    }
    .header-container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }
    .logo {
      display: flex;
      align-items: center;
    }
    .logo svg {
      margin-right: 10px;
    }
    .logo-text h1 {
      font-size: 24px;
      color: #004080;
    }
    .logo-text p {
      font-size: 14px;
      color: #666;
    }
    nav ul {
      list-style: none;
      display: flex;
    }
    nav ul li {
      margin-left: 20px;
    }
    nav ul li a {
      text-decoration: none;
      color: #004080;
      font-weight: bold;
    }

    /* === Hero Section === */
    .hero {
      background: url('hero-image.jpg') center/cover no-repeat;
      background-color: #004080; /* fallback color */
      color: #fff;
      text-align: center;
      padding: 100px 0;
    }
    .hero h2 {
      font-size: 48px;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 24px;
      margin-bottom: 20px;
    }

    /* === Buttons === */
    .btn {
      display: inline-block;
      background: #32CD32;
      color: #fff;
      padding: 10px 20px;
      text-decoration: none;
      font-size: 18px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    /* === Sections === */
    section {
      padding: 60px 0;
      text-align: center;
    }

    /* Family Card */
    .family-card {
      background: #f4f4f4;
      border: 1px solid #ddd;
      padding: 20px;
      margin: 20px auto;
      max-width: 400px;
      border-radius: 5px;
    }

    /* === Forms === */
    form {
      max-width: 500px;
      margin: auto;
      text-align: left;
    }
    form label {
      display: block;
      margin: 10px 0 5px;
    }
    form input[type="text"],
    form input[type="email"],
    form textarea {
      width: 100%;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 5px;
      margin-bottom: 10px;
    }
    form input[type="submit"],
    form button {
      background: #32CD32;
      color: #fff;
      border: none;
      padding: 10px 20px;
      cursor: pointer;
      border-radius: 5px;
    }

    /* === Sidebar === */
    .sidebar-container {
      display: flex;
      justify-content: space-between;
      margin-top: 20px;
    }
    .sidebar {
      width: 48%;
      padding: 20px;
      background: #f4f4f4;
      border: 1px solid #ddd;
      border-radius: 5px;
    }
    .sidebar h3 {
      color: #004080;
      font-size: 24px;
      margin-bottom: 15px;
    }
    .sidebar p {
      font-size: 16px;
      color: #333;
      line-height: 1.5;
    }

    /* === Footer === */
    footer {
      background: #004080;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }

    /* === Donate Section Styles === */
    #donate {
      text-align: center;
    }

    .donate-button-container {
      margin-top: 20px; /* Add space between text and button */
      display: flex;
      justify-content: center; /* Center the button horizontally */
    }

    /* === Responsive Navigation === */
    @media (max-width: 768px) {
      .header-container {
        flex-direction: column;
      }
      nav ul {
        flex-direction: column;
        align-items: center;
      }
      nav ul li {
        margin: 10px 0;
      }
      .sidebar-container {
        flex-direction: column;
      }
      .sidebar {
        width: 100%;
        margin-top: 20px;
      }
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <div class="container header-container">
      <div class="logo">
        <!-- Logo SVG -->
        <svg width="60" height="60" xmlns="http://www.w3.org/2000/svg">
          <circle cx="30" cy="30" r="28" stroke="#004080" stroke-width="2" fill="none" />
          <path d="M30 24
                   C26 18, 18 18, 18 24
                   A12 12 0 0 0 30 36
                   A12 12 0 0 0 42 24
                   C42 18, 34 18, 30 24 Z" fill="#32CD32"/>
          <text x="30" y="31" text-anchor="middle" fill="white" font-family="Arial" font-size="20" font-weight="bold">$</text>
        </svg>
        <div class="logo-text">
          <h1>A Dollar Foundation</h1>
          <p>It only takes a dollar to change a life</p>
        </div>
      </div>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#families">Families</a></li>
          <li><a href="#donate">Donate</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Main Content -->
  <main>
    <!-- Home / Hero Section -->
    <section id="home" class="hero">
      <div class="container">
        <h2>Welcome To A Dollar Foundation</h2>
        <p>Changing lives one dollar at a time. Join us in making a difference.</p>
        <a href="#donate" class="btn">Donate Now</a>
      </div>
    </section>

    <!-- Sidebar Section -->
    <section id="sidebar">
      <div class="container sidebar-container">
        <!-- First Sidebar Box -->
        <div class="sidebar">
          <h3>Our Future Vision</h3>
          <p>The future of this organization is to support those in need by just donating one dollar per person. That's it!! All we ask is that you consider donating just One Dollar, nothing more and nothing less.</p>
        </div>

        <!-- Second Sidebar Box -->
        <div class="sidebar">
          <h3>The Power of One Dollar</h3>
          <p>Your Dollar could mean the world to someone else, embrace that joy of giving just One Dollar to a greater cause.</p>
        </div>
      </div>
    </section>

    <!-- Families Section -->
    <section id="families">
      <div class="container">
        <h2>Families in Need</h2>
        <p>Learn about the families we're supporting and how your donation can make an impact.</p>
        <!-- Example Family Card (Duplicate for each family as needed) -->
        <div class="family-card">
          <h3>Family Name</h3>
          <p>A brief story about the family and why they need support.</p>
          <a href="#donate" class="btn">Donate $1</a>
        </div>
        <!-- Add more family cards here -->
      </div>
    </section>

    <!-- Donate Section -->
    <section id="donate">
      <div class="container">
        <h2>Donate $1</h2>
        <p>Your dollar can help change a life. Click below to donate.</p>

        <!-- PayPal Donation Button -->
        <div class="donate-button-container">
          <form action="https://www.paypal.com/donate" method="post" target="_top">
            <!-- Replace YOUR_BUTTON_ID with your actual PayPal Button ID -->
            <input type="hidden" name="hosted_button_id" value="YOUR_BUTTON_ID" />
            <input type="submit" value="Donate $1" class="btn" />
          </form>
               </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
      <div class="container">
        <h2>Contact Us</h2>
        <p>Have questions or need more information? Send us a message!</p>
        <!-- Contact form using Formspree -->
        <!-- Replace "your-form-id" with your actual Formspree ID -->
        <form action="https://formspree.io/f/mjkgjnyp" method="POST">
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" placeholder="Your name" required />

          <label for="email">Email:</label>
          <input type="email" id="email" name="email" placeholder="Your email" required />

          <label for="message">Message:</label>
          <textarea id="message" name="message" placeholder="Your message" required></textarea>

          <input type="submit" value="Send Message" class="btn" />
        </form>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 A Dollar Foundation. All rights reserved.</p>
  </footer>
</body>
</html>
