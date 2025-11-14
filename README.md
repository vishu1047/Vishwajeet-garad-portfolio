<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Vishwajeet Sunil Garad — Portfolio</title>

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --accent:#5f695e;
      --accent-2:#d4b806;
      --muted:#6b7280;
      --bg:#f7fbff;
      --card:#ffffff;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family:"Poppins",sans-serif;
      background:linear-gradient(180deg, #eef6ff 0%, var(--bg) 100%);
      color:#0f172a;
      scroll-behavior:smooth;
    }

    header{
      position:sticky;
      top:0;
      background:rgba(255,255,255,0.8);
      backdrop-filter:blur(6px);
      border-bottom:1px solid rgba(15,23,42,0.06);
      z-index:50;
    }
    .nav-wrap{
      max-width:1100px;
      margin:0 auto;
      display:flex;
      align-items:center;
      justify-content:space-between;
      padding:14px 20px;
    }
    .brand{
      display:flex;
      gap:12px;
      align-items:center;
    }
    .logo{
      height:44px;
      width:44px;
      border-radius:10px;
      background:linear-gradient(135deg,var(--accent),var(--accent-2));
      display:grid;
      place-items:center;
      color:white;
      font-weight:700;
      font-size:18px;
      box-shadow:0 6px 18px rgba(19, 79, 207, 0.231);
    }
    nav a{
      color:var(--muted);
      text-decoration:none;
      margin-left:18px;
      font-weight:600;
      font-size:14px;
    }
    nav a:hover{ color:var(--accent); }

    .hero{
      max-width:1100px;
      margin:36px auto;
      padding:28px 20px;
      display:flex;
      gap:30px;
      align-items:center;
      flex-wrap:wrap;
    }

    .photo{
      width:200px;
      height:200px;
      border-radius:50%;
      object-fit:cover;
      border:6px solid rgba(195, 212, 6, 0.227);
      box-shadow:0 12px 30px rgba(2,6,23,0.08);
      transition:transform .35s ease;
    }

    .photo:hover{
      transform:translateY(-6px) scale(1.02);
      box-shadow:0 20px 40px rgba(2,6,23,0.12);
    }

    .intro{
      flex:1 1 360px;
      min-width:260px;
    }
    .name{
      font-size:28px;
      font-weight:700;
      color:var(--accent);
      margin-bottom:6px;
    }
    .sub{
      color:#0f172a;
      font-weight:600;
      margin-bottom:8px;
    }
    .bio{
      color:var(--muted);
      line-height:1.6;
      margin-bottom:14px;
    }

    .chips{
      display:flex;
      gap:10px;
      flex-wrap:wrap;
      margin-top:8px;
    }
    .chip{
      background:linear-gradient(90deg, rgba(37,99,235,0.09), rgba(6,182,212,0.06));
      color:var(--accent);
      padding:8px 12px;
      border-radius:999px;
      font-weight:600;
      font-size:13px;
      border:1px solid rgba(37,99,235,0.06);
    }

    section.card{
      max-width:1100px;
      margin:14px auto;
      padding:22px;
      background:var(--card);
      border-radius:12px;
      box-shadow:0 8px 28px rgba(15,23,42,0.04);
      border:1px solid rgba(15,23,42,0.03);
    }

    .section-title{
      display:flex;
      align-items:center;
      gap:12px;
      margin-bottom:12px;
    }
    .section-title h3{ margin:0; color:var(--accent); font-size:18px; }

    .grid{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
      gap:12px;
      margin-top:12px;
    }
    .pill{
      background:#f5faff;
      padding:12px;
      border-radius:10px;
      border:1px solid rgba(6,182,212,0.06);
      font-weight:600;
      color:#0f172a;
    }

    /* social section */
    .social-section{
      text-align:center;
      margin-top:24px;
    }
    .social-title{
      font-size:20px;
      margin-bottom:10px;
      font-weight:700;
      color:var(--accent);
    }
    .social-links{
      display:flex;
      justify-content:center;
      gap:20px;
      flex-wrap:wrap;
      margin-top:10px;
    }
    .social-box{
      padding:12px 16px;
      background:#eef6ff;
      border-radius:12px;
      border:1px solid rgba(37,99,235,0.12);
      font-weight:600;
      min-width:160px;
    }
    .social-box a{
      text-decoration:none;
      color:var(--accent);
      font-weight:700;
    }

    footer{
      text-align:center;
      padding:20px 10px;
      color:var(--muted);
      margin-top:20px;
      font-size:14px;
    }
  </style>
</head>
<body>

<header>
  <div class="nav-wrap">
    <div class="brand">
      <div class="logo">VG</div>
      <div>
        <div style="font-weight:700">Vishwajeet Sunil Garad</div>
        <div style="font-size:12px;color:var(--muted)">DTU • CSE ' 29</div>
      </div>
    </div>

    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#interests">Interests</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </div>
</header>


<main class="hero" id="about">
  <img class="photo" src="25a06061profilepic.jpg" alt="Vishwajeet Sunil Garad" />

  <div class="intro">
    <div class="name">Vishwajeet Sunil Garad</div>
    <div class="sub">CSE Student • Delhi Technological University (DTU)</div>
    <div class="bio">
      Hi! I’m Vishwajeet from Dharashiv, Maharashtra. I completed my 10<sup>th</sup> from cbse school and studies of 11<sup>th</sup> and 12<sup>th</sup> had competed from Maharashtra board. I have intrest in both tech and non-tech fields. Passionate about Web Development, Intrested in ML, Speaking & Creativity.
      <br><br><strong>Mobile:</strong> 9975128499
      <br><br><strong>Email:</strong>vishwajeet.garad2007@gmail.com
    </div>

    <div class="chips">
      <div class="chip">Web Dev</div>
      <div class="chip">Machine Learning</div>
      <div class="chip">Creativity</div>
    </div>
  </div>
</main>

<section class="card" id="skills">
  <div class="section-title">
    <h3>Skills </h3>
  </div>

  <div style="color:var(--muted)">| C | Python | HTML | CSS | </div>
</section>

<section class="card" id="interests">
  <div class="section-title">
    <h3>Interests & Strengths</h3>
  </div>

  <div class="grid">
    <div class="pill">💻 Web Development</div>
    <div class="pill">🤖 Machine Learning</div>
    <div class="pill">⚙️ Technology Exploration</div>
    <div class="pill">📝 Creative Writing</div>
  </div>
</section>

<section class="card" id="projects">
  <div class="section-title">
    <h3>Projects</h3>
  </div>

  <div style="color:var(--muted)">I am working on my skills and I will fill this spot with various projects as soon as possible.</div>
</section>

<section class="card" id="contact">
  <div class="section-title">
    <h3>Connect With Me</h3>
  </div>

  <div class="social-section">

    <div class="social-links">

      <div class="social-box">
        Instagram: <br>
        <a href="https://www.instagram.com/vishu_2047_/" target="_blank">insta handle</a>
      </div>

      <div class="social-box">
        LinkedIn: <br>
        <a href="https://www.linkedin.com/in/vishwajeet-garad-bb9244378/" target="_blank">linked in profile</a>
      </div>

      <div class="social-box">
        Github: <br>
        <a href="https://github.com/vishu1047" target="_blank">github account</a>
      </div>

      <div class="social-box">
        Mobile / WhatsApp: <br>
        <a href="tel:9975128499">9975128499</a>
      </div>

      
      

    </div>
  </div>
</section>

<footer>
  © 2025 Vishwajeet Sunil Garad • Made with passion & creativity
</footer>

</body>
</html>
