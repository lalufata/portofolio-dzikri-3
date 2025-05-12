<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Portfolio Dzikir</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #00796B;
      color: white;
      overflow-x: hidden;
    }
    *,*::before, *::after{
      box-sizing: border-box;
    }

    section {
      min-height: 100vh;
      padding: 50px 20px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      border-bottom: 1px solid white;
    }

    h1, h2, h3 {
      margin-bottom: 20px;
    }

    .navbar {
      position: fixed;
      bottom: 0;
      width: 100%;
      background: #004D40;
      color: white;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
      font-size: 14px;
    }

    .navbar a {
      color: white;
      text-decoration: none;
    }

    .profile-img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      margin-bottom: 20px;
      object-fit: cover;
    }

    .skill-box {
      margin-bottom: 15px;
      background-color: #004D40;
      padding: 10px;
      border-radius: 8px;
      width: 80%;
    }

    .contact-icon {
      margin: 10px;
    }

    .contact-info {
      margin-top: 10px;
    }
  </style>
</head>
<body>
<!-- Frame 1: Home -->
  <section id="home">
    <img src="Dzikri.jpg" alt="Dzikri" class="profile-img" />
    <h1>Muhammad Dzikri Imaduddin</h1>
    <p>Making the best use of technology</p>
  </section>

  <div class="navbar">
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#portfolio">Portfolio & Education</a>
    <a href="#skills">Skill</a>
    <a href="#contact">Contact Person</a>
  </div>

  <!-- Frame 2: About Me -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      My name is Muhammad Dzikri Imaduddin. I was born in Jakarta on November 1st, 2004. I enjoy swimming in my free time.<br/>
      Currently, I am a student at Tazkia University, majoring in Sharia Economics.<br/>
      I am interested in how Islamic principles are applied in the field of economics.
    </p>
  </section>

  <!-- Frame 3: Portfolio & Education -->
  <section id="portfolio">
    <h2>Portfolio & Education</h2>
    <p><strong>Name:</strong> Muhammad Dzikri Imaduddin</p>
    <p><strong>Birth Date:</strong> Jakarta, 01/11/2004</p>
    <p><strong>Address:</strong> Jl H. Baka, No. 96, RT.13/7 RW9, Jagakarsa, Jakarta Selatan</p>
    <h3>Pendidikan</h3>
    <ul style="text-align: left; max-width: 600px;">
      <li>SDN 09 Lenteng Agung, Jakarta Selatan (2010–2016)</li>
      <li>MTsN 34, Kota Padang (2016–2019)</li>
      <li>MA Darul Hijrah, Kota Padang (2019–2022)</li>
      <li>Cairo University Exchange Program (2023–2024)</li>
    </ul>
  </section>

  <!-- Frame 6: Skills -->
  <section id="skills">
    <h2>Skill</h2>
    <div class="skill-box">
      <strong>Budgeting: 75%</strong><br/>
      Kemampuan dalam merencanakan, mengelola, dan mengontrol pengeluaran.
    </div>
    <div class="skill-box">
      <strong>Financial Planning: 90%</strong><br/>
      Kemampuan menyusun strategi keuangan yang efisien.
    </div>
    <div class="skill-box">
      <strong>Financial Reporting: 80%</strong><br/>
      Kemampuan menyusun laporan keuangan.
    </div>
    <div class="skill-box">
      <strong>Data Analysis: 70%</strong><br/>
      Kemampuan mengolah data menggunakan data management tools.
    </div>
  </section>

    <!-- Frame 7: Contact Person -->
  <section id="contact">
    <h2>Contact Person</h2>
    <div class="contact-icon">📸 IG: @dziky._muhammad</div>
    <div class="contact-icon">✉ Email: muhammadzikryimaduddin@gmail.com</div>
    <div class="contact-icon">📱 WA: 082288301164</div>
  </section>
   
  <div class="navbar">
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#portfolio">Portfolio & Education</a>
    <a href="#skills">Skill</a>
    <a href="#contact">Contact Person</a>
  </div>

</body>
</html>
