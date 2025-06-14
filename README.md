# emilyhowell030.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Eloheh | Meet Our Team</title>
  <style>
    body {
      background-color: #f0f8ff;
      font-family: 'Arial', sans-serif;
      margin: 20px;
      color: #333;
    }

    h1, h2 {
      color: #4b0082; /* Purple */
      font-family: 'Georgia', serif;
    }

    .highlight {
      font-style: italic;
      font-weight: bold;
      font-size: 18px;
      color: #228b22; /* Green */
    }

    .team-section {
      font-size: 16px;
      font-family: 'Courier New', monospace;
      color: #1e90ff; /* Blue */
    }

    .underline {
      text-decoration: underline;
    }

    .footer {
      margin-top: 40px;
      font-size: 12px;
      font-style: italic;
    }

    img {
      width: 200px;
      border-radius: 10px;
    }

    a {
      color: #4b0082;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <h1>Welcome to <span class="underline">Eloheh</span></h1>
  <p class="highlight">A healthcare company built on trust, care, and innovation.</p>

  <h2>Meet Our Leadership Team</h2>

  <div class="team-section">
    <h3>Dr. Maria Johnson – CEO</h3>
    <img src="maria.jpg" alt="Dr. Maria Johnson">
    <p><b>Maria</b> has over 25 years of experience in healthcare administration. <i>Her passion for patient care guides our company’s mission.</i></p>
    <p>Email: <a href="mailto:maria@eloheh.com">Contact Maria</a></p>
  </div>

  <div class="team-section">
    <h3>David Lee – CTO</h3>
    <img src="david.jpg" alt="David Lee">
    <p><b>David</b> leads Eloheh’s digital transformation with over 15 years in medical tech. <i>He's the architect of our secure patient systems.</i></p>
    <p>Email: <a href="mailto:david@eloheh.com">Contact David</a></p>
  </div>

  <h2>Our Values</h2>
  <ol>
    <li>Integrity in every action</li>
    <li>Compassion for all patients</li>
    <li>Innovation in our products and services</li>
  </ol>

  <h2>Why People Love Working at Eloheh</h2>
  <ul>
    <li>Flexible, family-first policies</li>
    <li>Cutting-edge medical technologies</li>
    <li>Supportive and diverse workplace</li>
  </ul>

  <p>Learn more about modern healthcare at <a href="https://www.mayoclinic.org" target="_blank">Mayo Clinic</a>.</p>

  <p>Download our <a href="eloheh-brochure.pdf" download>Eloheh Company Brochure</a>.</p>

  <div class="footer">
    <p>Page last modified: <span id="last-modified"></span></p>
  </div>

  <script>
    // Automatically insert the last modified date
    document.getElementById("last-modified").textContent = document.lastModified;
  </script>

</body>
</html>
