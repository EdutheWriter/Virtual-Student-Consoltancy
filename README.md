<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Virtual Student Consultancy</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: "Segoe UI", sans-serif;
      background-color: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    ul {
      list-style: none;
    }

    header {
      background-color: #004080;
      padding: 20px 0;
      color: #fff;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .nav-container {
      max-width: 1200px;
      margin: auto;
      padding: 0 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .nav-container h1 {
      font-size: 24px;
    }

    nav ul {
      display: flex;
      gap: 20px;
    }

    nav a:hover {
      color: #ffcc00;
    }

    #hero {
      background: url('https://images.unsplash.com/photo-1588072432836-e10032774350?auto=format&fit=crop&w=1600&q=80') no-repeat center center/cover;
      color: white;
      text-align: center;
      padding: 100px 20px;
      position: relative;
    }

    #hero h2 {
      font-size: 36px;
      margin-bottom: 20px;
    }

    #hero p {
      font-size: 20px;
      margin-bottom: 30px;
    }

    .typed-text {
      color: orangered;
      font-size: 50px;
    }

    .cta-btn {
      background-color: #ffcc00;
      color: #004080;
      padding: 12px 25px;
      border-radius: 5px;
      font-weight: bold;
      transition: background-color 0.3s ease;
    }

    .cta-btn:hover {
      background-color: #ffaa00;
    }

    section {
      max-width: 1200px;
      margin: 60px auto;
      padding: 0 20px;
    }

    .card-grid {
      display: grid;
      gap: 20px;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    }

    .card {
      background: #fff;
      border-radius: 10px;
      padding: 30px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      text-align: center;
      transition: transform 0.3s, background-color 0.3s;
      cursor: pointer;
    }

    .card:hover {
      background-color: #f0f8ff;
      transform: translateY(-5px);
    }

    .card h3 {
      color: #004080;
      margin-bottom: 10px;
    }

    .card p {
      font-size: 15px;
    }

    #contact {
      background: linear-gradient(135deg, #ff7e5f, #feb47b);
      border-radius: 10px;
      padding: 40px 20px;
    }

    .contact h1{
      align-items: center;
    }
    .contact-form {
      max-width: 600px;
      margin: auto;
    }

    .contact-form form {
      display: flex;
      flex-direction: column;
    }

    .contact-form label {
      font-weight: bold;
      margin-bottom: 5px;
    }

    .contact-form input,
    .contact-form select,
    .contact-form textarea {
      margin-bottom: 20px;
      padding: 10px;
      font-size: 16px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .contact-form button {
      background-color: #004080;
      color: #fff;
      padding: 12px;
      font-size: 16px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .contact-form button:hover {
      background-color: #002f5e;
    }

    footer {
      background-color: #004080;
      color: white;
      text-align: center;
      padding: 30px 20px;
      margin-top: 60px;
    }

    footer a {
      color: #ffcc00;
      display: inline-block;
      margin: 5px 10px;
    }

    .whatsapp-float {
      position: fixed;
      bottom: 30px;
      right: 30px;
      background-color: #25d366;
      color: white;
      font-size: 24px;
      padding: 12px 15px;
      border-radius: 50%;
      text-align: center;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
      z-index: 999;
      transition: background-color 0.5s ease;
    }

    .whatsapp-float:hover {
      background-color: #1ebd5a;
    }

    .mode-toggle {
      position: fixed;
      bottom: 90px;
      right: 30px;
      background: #004080;
      color: white;
      padding: 10px 15px;
      border-radius: 30px;
      cursor: pointer;
      z-index: 999;
    }

    .dark-mode {
      background-color: #121212;
      color: #eee;
    }

    .dark-mode header,
    .dark-mode footer {
      background-color: #1a1a1a;
    }
  </style>
</head>

<body>
  <header>
    <div class="nav-container">
      <h1>Virtual Student Consultancy</h1>
      <nav>
        <ul>
          <li><a href="#hero">Home</a></li>
          <li><a href="#about">About Us</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#tips">Campus Updates</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="hero">
    <h2>Your Campus Life, Simplified</h2>
    <p><h3><strong>We streamline:</strong></h3><span class="typed-text"></span></p>
    <a class="cta-btn" href="#services">Explore Our Services</a>
  </section>

  <section id="about">
    <div class="card-grid">
      <div class="card">
        <h3>About Us</h3>
        <p>We bridge the gap between students and campus administration through a digital-first approach.</p>

        <p>Virtual Students suffer alot when it comes to getting direct assistance by the institution. You have to travel from where you are</p>
      </div>
    </div>
  </section>

  <section id="services">
    <div class="card-grid">
      <div class="card"><h3>Registration Office Inquiry</h3><p>Remotely consult on Registration of units related issues.(Thika,MKU: AlumniPlaza Ground Floor)</p></div>
      <div class="card"><h3>Finance Office Inquiry</h3><p>Remotely consult on your academic financing related issues.(Thika,MKU: AlumniPlaza Ground floor)</p></div> 
      <div class="card"><h3>Lecturer Inquiry</h3><p>Remotely consolt your lecturer on issues concerning your course work.</p></div>
      <div class="card"><h3>Odel Office Inquiry</h3><p>Remotely consult on Virtual learning related problems.(Thika,MKU: Alumini Plaza 3rd Floor)</p></div>
      <div class="card"><h3>VLMS Office Inquiry</h3><p>Remotely  access VLMS Office customer care services.(Thika,MKU: Alumini Plaza 6th Floor) </p></div>

    </div>
  </section>

  <section id="tips">
    <div class="card-grid">
      <div class="card">
        <h3>Campus Tips & Stories</h3>
        <p>Get academic hacks and hear from students like you.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <div class="contact-form">
      <form action="contact.php" method="post">
        <label for="name">Name:</label>
        <input id="name" name="name" type="text" required />

        <label for="email">Email:</label>
        <input id="email" name="email" type="email" required />

        <label for="service">Service Needed:</label>
        <select id="service" name="service">
          <option value="registration Office">Registration office Consoltancy</option>
          <option value="Odel Office"></option>
          <option value="finance Office">Finance Office Consoltancy</option>
          <option value="lecturer"></option>
          <option value="VLMS Office">ICT Office Consoltancy.</option>
          <option value="appointment">Odel office consultancy</option>
          <option value="appointment">VLMS Portal Consoltancy</option>
          <option value="appointment">OES Portal Consoltancy</option>
          <option value="appointment">Lecturer Consoltancy</option>
        </select>

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="button" onclick="initiateMpesaPayment()">Pay via MPESA</button><br/><br/>
        <button type="submit">Send Inquiry</button>
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Virtual Student Consultancy. All rights reserved.</p>
    <p>Quick Support: 
      <a href="#contact">Contact</a> | 
      <a href="#services">Services</a> | 
      <a href="#tips">Campus Tips</a> | 
      <a href="mailto:support@campusconsultingpro.com">Email Us</a>
    </p>
  </footer>

  <a class="whatsapp-float" href="https://wa.me/254701872952" target="_blank" title="Chat with us on WhatsApp">✉</a>
  <div class="mode-toggle" onclick="toggleMode()">Toggle Mode</div>

  <script>
    function toggleMode() {
      document.body.classList.toggle("dark-mode");
      localStorage.setItem("theme", document.body.classList.contains("dark-mode") ? "dark" : "light");
    }

    window.onload = function () {
      if (localStorage.getItem("theme") === "dark") {
        document.body.classList.add("dark-mode");
      }

      const typedText = document.querySelector('.typed-text');
      const texts = ["Unit Registration", "Finance Inquiries", "Lecturer Support", "Online Guidance", "Exam Assistance"];
      let index = 0, charIndex = 0;

      function type() {
        if (charIndex < texts[index].length) {
          typedText.textContent += texts[index].charAt(charIndex);
          charIndex++;
          setTimeout(type, 100);
        } else {
          setTimeout(erase, 1500);
        }
      }

      function erase() {
        if (charIndex > 0) {
          typedText.textContent = texts[index].substring(0, charIndex - 1);
          charIndex--;
          setTimeout(erase, 50);
        } else {
          index = (index + 1) % texts.length;
          setTimeout(type, 500);
        }
      }

      type();
    }

    function initiateMpesaPayment() {
      alert("Please Wait to verify your pin. If failed, Please retry again.");
    }
  </script>
</body>
</html>
