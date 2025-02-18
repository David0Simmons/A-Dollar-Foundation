# A-Dollar-Foundation
A Dollar Foundation
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>A Dollar Foundation - It only takes a dollar to change a life</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
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

  <main>
    <!-- Home / Hero Section -->
    <section id="home" class="hero">
      <div class="container">
        <h2>Welcome to A Dollar Foundation</h2>
        <p>Changing lives one dollar at a time. Join us in making a difference.</p>
        <a href="#donate" class="btn">Donate Now</a>
      </div>
    </section>

    <!-- Families Section -->
    <section id="families">
      <div class="container">
        <h2>Families in Need</h2>
        <p>Learn about the families we're supporting and how your donation can make an impact.</p>
        <!-- Example Family Card (Duplicate or modify for each family) -->
        <div class="family-card">
          <h3>Family Name</h3>
          <p>A brief story about the family and why they need support.</p>
          <a href="#donate" class="btn">Donate $1</a>
        </div>
        <!-- Add more family cards as needed -->
      </div>
    </section>

    <!-- Donate Section -->
    <section id="donate">
      <div class="container">
        <h2>Donate $1</h2>
        <p>Your dollar can help change a life. Click below to donate.</p>
        <!-- PayPal Donation Button Example -->
        <form action="https://www.paypal.com/donate" method="post" target="_top">
          <!-- Replace YOUR_BUTTON_ID with your actual PayPal Button ID -->
          <input type="hidden" name="hosted_button_id" value="YOUR_BUTTON_ID" />
          <input type="submit" value="Donate $1" class="btn" />
        </form>
        <!-- You can also link to a different donation processor or page if preferred -->
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
      <div class="container">
        <h2>Contact Us</h2>
        <p>Have questions or need more information? Send us a message!</p>
        <!-- Contact form using Formspree (replace "your-form-id" with your actual Formspree ID) -->
        <form action="https://formspree.io/f/your-form-id" method="POST">
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" placeholder="Your name" required />

          <label for="email">Email:</label>
          <input type="email" id="email" name="email" placeholder="Your email" required />

          <label for="message">Message:</label>
          <textarea id="message" name="message" rows="5" placeholder="Your message" required></textarea>

          <button type="submit" class="btn">Send Message</button>
        </form>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      <p>&copy; 2025 A Dollar Foundation. All Rights Reserved.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
/* General Styles */
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

/* Container */
.container {
  width: 90%;
  max-width: 1100px;
  margin: auto;
}

/* Header & Navigation */
header {
  background: #f4f4f4;
  padding: 10px 0;
  border-bottom: 2px solid #004080;
}

.header-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
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

/* Hero Section */
.hero {
  background: url('hero-image.jpg') center/cover no-repeat;
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

/* Buttons */
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

/* Section Styles */
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

/* Forms */
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

/* Footer */
footer {
  background: #004080;
  color: #fff;
  padding: 20px 0;
  text-align: center;
}

/* Responsive Navigation */
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
}
// Smooth scrolling for navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
  anchor.addEventListener("click", function (e) {
    e.preventDefault();
    document.querySelector(this.getAttribute("href")).scrollIntoView({
      behavior: "smooth"
    });
  });
});
