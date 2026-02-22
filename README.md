<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Narayana Construction | Building Trust, Shaping Spaces</title>
  <meta name="description" content="Narayana Construction delivers quality construction, interiors, and infrastructure solutions with modern design, timely delivery, and transparency." />

  <!-- Font (modern sans-serif) -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <style>
 :root{
  --navy:#1e293b;       /* main text */
  --navy-2:#0f2b46;     /* headings */
  --white:#ffffff;
  --muted:#64748b;
  --line:#e5e7eb;
  --yellow:#f7c600;     /* CTA */
  --orange:#fb923c;     /* underline accent */
  --shadow: 0 10px 26px rgba(2,6,23,.10);
  --shadow-soft: 0 8px 18px rgba(2,6,23,.08);
  --radius: 16px;
  --max: 1160px;
}

    *{ box-sizing:border-box; }
    html{ scroll-behavior:smooth; }
    body{
      margin:0;
      font-family: "Inter", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      color:#0f172a;
      background: var(--white);
      line-height:1.6;
    }

    /* Utilities */
    .container{
      max-width: var(--max);
      margin: 0 auto;
      padding: 0 20px;
    }
    .section{
      padding: 84px 0;
    }
    .section-title{
      font-size: clamp(24px, 2.4vw, 34px);
      font-weight: 800;
      letter-spacing: -0.02em;
      margin: 0 0 14px;
    }
    .underline{
      width: 70px;
      height: 4px;
      background: var(--orange);
      border-radius: 999px;
      margin: 10px 0 24px;
    }
    .muted{ color: var(--muted); }
    .btn{
      display:inline-flex;
      align-items:center;
      justify-content:center;
      gap:10px;
      padding: 12px 18px;
      border-radius: 14px;
      border: 0;
      cursor:pointer;
      font-weight: 700;
      text-decoration:none;
      transition: transform .15s ease, box-shadow .15s ease, opacity .15s ease;
      user-select:none;
      white-space:nowrap;
    }
    .btn:active{ transform: translateY(1px); }
    .btn-yellow{
      background: var(--yellow);
      color: #1f2a37;
      box-shadow: 0 10px 24px rgba(255, 210, 0, .25);
    }
    .btn-yellow:hover{ transform: translateY(-1px); box-shadow: 0 14px 28px rgba(255, 210, 0, .30); }
    .btn-blue{
      background: var(--navy-2);
      color: var(--white);
      box-shadow: 0 10px 22px rgba(14, 42, 82, .25);
    }
    .btn-blue:hover{ transform: translateY(-1px); box-shadow: 0 14px 28px rgba(14, 42, 82, .30); }

    /* Navbar */
  .navbar{
  position: sticky;
  top:0;
  z-index: 1000;
  background: rgba(255,255,255,.92);
  backdrop-filter: blur(10px);
  border-bottom: 1px solid rgba(2,6,23,.08);
}
    .nav-inner{
      height: 74px;
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:16px;
    }
    .logo{
      width: 44px;
      height: 44px;
      border-radius: 50%;
      background: radial-gradient(circle at 30% 30%, #ffffff 0%, #dbeafe 35%, #93c5fd 70%, #3b82f6 100%);
      box-shadow: 0 10px 24px rgba(0,0,0,.22);
      border: 2px solid rgba(255,255,255,.2);
      position: relative;
      overflow:hidden;
    }
    .logo::after{
      content:"NC";
      position:absolute;
      inset:0;
      display:flex;
      align-items:center;
      justify-content:center;
      font-weight: 900;
      color: rgba(11,31,59,.95);
      font-size: 15px;
      letter-spacing: .04em;
    }
    .nav-links{
      display:flex;
      align-items:center;
      gap: 22px;
    }
   .nav-links a{
  color: var(--navy);
  text-decoration:none;
  font-weight: 600;
  font-size: 14px;
  padding: 10px 10px;
  border-radius: 12px;
  transition: background .15s ease, color .15s ease, transform .15s ease;
}
   .nav-links a:hover{
  background: rgba(2,6,23,.06);
  color: var(--navy);
  transform: translateY(-1px);
}

    /* Mobile nav */
.hamburger{
  display:none;
  width: 44px;
  height: 44px;
  border-radius: 12px;
  border: 1px solid rgba(2,6,23,.14);
  background: rgba(2,6,23,.03);
  color: var(--navy);
  cursor:pointer;
}
.hamburger span{
  display:block;
  width: 18px;
  height: 2px;
  background: var(--navy);
  margin: 4px auto;
  border-radius: 99px;
}
    .mobile-panel{
  display:none;
  padding: 10px 0 18px;
  border-top: 1px solid rgba(2,6,23,.08);
  background: #ffffff;
}
.mobile-panel a{
  display:block;
  padding: 12px 20px;
  color: var(--navy);
  text-decoration:none;
  font-weight: 600;
  border-radius: 12px;
  margin: 6px 0;
}
.mobile-panel a:hover{
  background: rgba(2,6,23,.06);
}

    /* Hero */
   .hero{
  position: relative;
  min-height: calc(92vh - 74px);
  display:flex;
  align-items:center;
  color: #0f172a;
  background:
  linear-gradient(180deg, rgba(255,255,255,.55), rgba(255,255,255,.70)),
  url("hero.png");
  background-size: cover;
  background-position: center;
  overflow:hidden;
}
    .hero-inner{
      padding: 84px 0;
      text-align:center;
      max-width: 900px;
      margin: 0 auto;
    }
    .hero h1{
      font-size: clamp(34px, 4.2vw, 56px);
      margin: 0 0 14px;
      font-weight: 900;
      letter-spacing: -0.03em;
      text-shadow: 0 10px 30px rgba(0,0,0,.25);
    }
   .hero p{
  margin: 0 auto 26px;
  max-width: 720px;
  font-size: clamp(15px, 1.4vw, 18px);
  color: rgba(15,23,42,.75);
}
    .hero .btn{
      padding: 14px 22px;
      border-radius: 16px;
    }

    /* About */
    .about-grid{
      display:grid;
      grid-template-columns: 1.1fr .9fr;
      gap: 34px;
      align-items:center;
    }
    .about-card{
      background:#fff;
      border: 1px solid var(--line);
      border-radius: var(--radius);
      padding: 28px;
      box-shadow: var(--shadow-soft);
    }
    .about-text{
      font-size: 15.5px;
      color:#111827;
    }
    .about-text strong{
      color: var(--navy-2);
    }
    .about-image{
      border-radius: var(--radius);
      overflow:hidden;
      box-shadow: var(--shadow);
      border: 1px solid rgba(2,6,23,.08);
      aspect-ratio: 4 / 3;
      background:
        linear-gradient(180deg, rgba(11,31,59,.15), rgba(11,31,59,.45)),
        url("about.png");
      background-size: cover;
      background-position:center;
    }

    /* Vision/Mission/Priority */
    .triple{
      display:grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
      margin-top: 26px;
    }
    .pill{
      background: #fff;
      border: 1px solid var(--line);
      border-radius: var(--radius);
      padding: 22px;
      box-shadow: var(--shadow-soft);
      position: relative;
      overflow:hidden;
    }
    .pill::before{
      content:"";
      position:absolute;
      top:0; left:0;
      width:100%;
      height: 5px;
      background: linear-gradient(90deg, var(--orange), var(--yellow));
      opacity:.95;
    }
    .pill h3{
      margin: 8px 0 10px;
      font-size: 18px;
      font-weight: 800;
      color: var(--navy-2);
    }
    .pill p, .pill ul{
      margin:0;
      color:#374151;
      font-size: 14.5px;
    }
    .pill ul{
      padding-left: 18px;
    }

    /* Services */
    .services-grid{
      display:grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
      margin-top: 22px;
    }
    .service-card{
      border-radius: var(--radius);
      overflow:hidden;
      background:#fff;
      border: 1px solid var(--line);
      box-shadow: var(--shadow-soft);
      transition: transform .18s ease, box-shadow .18s ease;
    }
    .service-card:hover{
      transform: translateY(-4px);
      box-shadow: 0 18px 40px rgba(2, 6, 23, .14);
    }
    .service-img{
      height: 170px;
      background-size: cover;
      background-position:center;
      position: relative;
    }
    .service-img::after{
      content:"";
      position:absolute;
      inset:0;
      background: linear-gradient(180deg, rgba(11,31,59,.10), rgba(11,31,59,.55));
    }
    .service-body{
      padding: 18px 18px 20px;
    }
    .service-body h3{
      margin: 0 0 10px;
      font-size: 18px;
      font-weight: 800;
      color: var(--navy-2);
    }
    .service-body ul{
      margin:0;
      padding-left: 18px;
      color:#374151;
      font-size: 14.5px;
    }

    /* Contact */
    .contact-wrap{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap: 22px;
      margin-top: 22px;
      align-items:start;
    }
    .contact-info, .contact-form{
      background:#fff;
      border: 1px solid var(--line);
      border-radius: var(--radius);
      padding: 22px;
      box-shadow: var(--shadow-soft);
    }
    .info-row{
      display:flex;
      gap: 12px;
      align-items:flex-start;
      padding: 12px 0;
      border-bottom: 1px dashed rgba(17,24,39,.12);
    }
    .info-row:last-child{ border-bottom:0; padding-bottom:0; }
    .icon{
      width: 38px;
      height: 38px;
      border-radius: 12px;
      background: rgba(255, 122, 24, .12);
      display:flex;
      align-items:center;
      justify-content:center;
      flex: 0 0 auto;
      border: 1px solid rgba(255, 122, 24, .22);
      color: var(--orange);
      font-weight: 900;
    }
    .info-row strong{
      display:block;
      color: var(--navy-2);
      font-size: 13px;
      margin-bottom: 2px;
    }
    .info-row span{
      display:block;
      color:#111827;
      font-size: 14.5px;
    }

    .form-grid{
      display:grid;
      gap: 12px;
    }
    label{
      font-size: 12.5px;
      font-weight: 700;
      color:#334155;
      margin-bottom: 6px;
      display:block;
    }
    input, textarea{
      width:100%;
      border: 1px solid rgba(15,23,42,.16);
      border-radius: 14px;
      padding: 12px 12px;
      font-family: inherit;
      font-size: 14.5px;
      outline:none;
      transition: border .15s ease, box-shadow .15s ease;
      background:#fff;
    }
    input:focus, textarea:focus{
      border-color: rgba(14,42,82,.55);
      box-shadow: 0 0 0 4px rgba(14,42,82,.12);
    }
    textarea{
      min-height: 120px;
      resize: vertical;
    }
    .form-note{
      font-size: 12.5px;
      color: var(--muted);
      margin-top: 8px;
    }
    .success{
      display:none;



      margin-top: 12px;
      padding: 12px 14px;
      border-radius: 14px;
      border: 1px solid rgba(34,197,94,.25);
      background: rgba(34,197,94,.08);
      color:#166534;
      font-weight: 600;
      font-size: 13.5px;
    }

    /* Footer */
    footer{
      background: #07162b;
      color: rgba(255,255,255,.85);
      padding: 28px 0;
      border-top: 1px solid rgba(255,255,255,.08);
    }
    .footer-inner{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap: 14px;
      flex-wrap: wrap;
    }
    .footer-inner small{ color: rgba(255,255,255,.75); }

    /* Animations */
    .fade-up{
      opacity:0;
      transform: translateY(14px);
      transition: opacity .7s ease, transform .7s ease;
    }
    .fade-up.in{
      opacity:1;
      transform: translateY(0);
    }
    .hero .fade-up{ transition-delay: .12s; }

    /* Responsive */
    @media (max-width: 980px){
      .about-grid{ grid-template-columns: 1fr; }
      .triple{ grid-template-columns: 1fr; }
      .services-grid{ grid-template-columns: 1fr; }
      .contact-wrap{ grid-template-columns: 1fr; }
      .about-image{ order:-1; }
    }
    @media (max-width: 760px){
      .nav-links{ display:none; }
      .hamburger{ display:inline-block; }
      .mobile-panel.show{ display:block; }
      .hero-inner{ padding: 70px 0; }
    }
/* ===== FIX: Brand Logo + Text (LIGHT THEME) ===== */
.brand{
  display:flex;
  align-items:center;
  gap:12px;
  text-decoration:none;
  color: var(--navy);   /* DARK TEXT for light navbar */
}

.brand-text{
  display:flex;
  flex-direction:column;
  justify-content:center;
  line-height:1.15;
}

.brand-name{
  font-size:14px;
  font-weight:800;
  line-height:1.1;
  color: var(--navy);
}

.brand-tagline{
  font-size:12px;
  font-weight:600;
  color: rgba(30,41,59,.70); /* dark gray */
  margin-top: 2px;
}

/* Logo size balanced with navbar height */
.logo-img{
  width: 48px;     /* 58 -> 48 (fit perfect) */
  height: 48px;
  object-fit: contain;
  background: #ffffff;
  padding: 6px;
  border-radius: 8px;
  box-shadow: 0 8px 18px rgba(0,0,0,.18);
  display:block;
}

  </style>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
</head>

<body>
  <!-- NAVBAR -->
  <header class="navbar">
    <div class="container nav-inner">
     <a class="brand" href="#home" aria-label="Narayana Construction Home">
  <img src="logo.png" alt="Narayana Construction Logo" class="logo-img">
  <div class="brand-text">
    <div class="brand-name">Narayana Construction</div>
    <div class="brand-tagline">Construction • Interior • Infrastructure</div>
  </div>
</a>

      <nav class="nav-links" aria-label="Primary navigation">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
      </nav>

      <button class="hamburger" id="hamburger" aria-label="Open menu" aria-expanded="false">
        <span></span><span></span><span></span>
      </button>
    </div>

    <div class="container mobile-panel" id="mobilePanel" aria-label="Mobile navigation">
      <a href="#home" class="mobile-link">Home</a>
      <a href="#about" class="mobile-link">About</a>
      <a href="#services" class="mobile-link">Services</a>
      <a href="#contact" class="mobile-link">Contact</a>
    </div>
  </header>

  <!-- HERO -->
  <section class="hero" id="home">
    <div class="container hero-inner">
      <h1 class="fade-up">Your Region, Our Expertise</h1>
      <p class="fade-up">
        Quality Construction with Modern Design, Timely Delivery &amp; Transparency
      </p>
      <a class="btn btn-yellow fade-up" href="#services" aria-label="Explore Our Services">
        Explore Our Services
        <span aria-hidden="true">→</span>
      </a>
    </div>
  </section>

  <!-- ABOUT -->
  <section class="section" id="about">
    <div class="container">
      <div class="fade-up">
        <div class="section-title">About Us</div>
        <div class="underline"></div>
      </div>

      <div class="about-grid">
        <div class="about-card fade-up">
          <div class="about-text">
            Narayana Construction is a reliable and professional construction company known for delivering
            quality projects with modern design, strong execution, and timely completion.
            <br/><br/>
            We focus on understanding our clients’ requirements and providing practical, cost-effective,
            and sustainable solutions.
            <br/><br/>
            <strong>OUR GOAL IS SIMPLE:</strong> To deliver excellence in every project with transparency and commitment.
          </div>
        </div>

        <div class="about-image fade-up" role="img" aria-label="Construction and building development image"></div>
      </div>

      <div class="triple">
        <div class="pill fade-up">
          <h3>Our Vision</h3>
          <p>To become a trusted name in the construction industry by delivering quality, innovation, and long-term value.</p>
        </div>
        <div class="pill fade-up">
          <h3>Our Mission</h3>
          <p>To provide reliable construction and interior solutions while building strong and lasting client relationships.</p>
        </div>
        <div class="pill fade-up">
          <h3>Our Priority</h3>
          <ul>
            <li>High-quality materials</li>
            <li>Budget-friendly solutions</li>
            <li>100% Customer satisfaction</li>
          </ul>
        </div>
      </div>
    </div>
  </section>
<!-- WHY CHOOSE US -->
<section class="section" style="background:#f8fafc;">
  <div class="container">

    <div class="fade-up">
      <div class="section-title">Why Choose Us</div>
      <div class="underline"></div>
    </div>

    <div class="triple">
      <div class="pill fade-up">
        <h3>Experienced Professional Team</h3>
        <p>We have a skilled and experienced team to handle projects efficiently.</p>
      </div>

      <div class="pill fade-up">
        <h3>On-Time Project Delivery</h3>
        <p>We strictly follow timelines and deliver projects on time.</p>
      </div>

      <div class="pill fade-up">
        <h3>High-Quality Materials</h3>
        <p>Only trusted and durable materials are used in our projects.</p>
      </div>

      <div class="pill fade-up">
        <h3>Budget-Friendly Solutions</h3>
        <p>We provide cost-effective solutions without compromising quality.</p>
      </div>

      <div class="pill fade-up">
        <h3>Customer Satisfaction</h3>
        <p>Client satisfaction is our top priority in every project.</p>
      </div>
    </div>

  </div>
</section>

  <!-- SERVICES -->
  <section class="section" id="services" style="background:#f8fafc;">
    <div class="container">
      <div class="fade-up">
        <div class="section-title">Our Services</div>
        <div class="underline"></div>
      </div>

      <div class="services-grid">
        <article class="service-card fade-up">
          <div class="service-img" style="background-image:url('interior.png');"></div>
          <div class="service-body">
            <h3>Interior Services</h3>
            <ul>
              <li>Residential interior design</li>
              <li>Office and commercial interiors</li>
              <li>Modular kitchen</li>
              <li>False ceiling, lighting &amp; woodwork</li>
            </ul>
          </div>
        </article>

        <article class="service-card fade-up">
          <div class="service-img" style="background-image:url('https://images.unsplash.com/photo-1541888946425-d81bb19240f5?auto=format&fit=crop&w=1400&q=80');"></div>
          <div class="service-body">
            <h3>Medium Scale Building Construction</h3>
            <ul>
              <li>Residential buildings</li>
              <li>Commercial buildings</li>
              <li>Apartments &amp; flats</li>
              <li>Structural design and execution</li>
              <li>Maintenance &amp; renovation</li>
            </ul>
          </div>
        </article>

        <article class="service-card fade-up">
          <div class="service-img" style="background-image:url('horiculture.png');"></div>
          <div class="service-body">
            <h3>Horticulture</h3>
            <ul>
              <li>Garden development</li>
              <li>Plantation work</li>
              <li>Green area maintenance</li>
              <li>Irrigation systems</li>
            </ul>
          </div>
        </article>

       <article class="service-card fade-up">
  <div class="service-img" style="background-image:url('landscaping.png');"></div>
  <div class="service-body">
    <h3>Landscaping</h3>
    <ul>
      <li>Park and garden design</li>
      <li>Resort & farmhouse landscaping</li>
      <li>Walkways and water features</li>
      <li>Open space development</li>
    </ul>
  </div>
</article>

<article class="service-card fade-up">
  <div class="service-img" style="background-image:url('turnkey.png');"></div>
  <div class="service-body">
    <h3>Turnkey Projects</h3>
    <ul>
      <li>Planning</li>
      <li>Designing</li>
      <li>Material supply</li>
      <li>Labor management</li>
      <li>Execution</li>
      <li>Final handover</li>
    </ul>
  </div>
</article>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section class="section" id="contact">
    <div class="container">
      <div class="fade-up">
        <div class="section-title">Get In Touch</div>
        <div class="underline"></div>
      </div>

      <div class="contact-wrap">
        <!-- Left: Contact Info -->
        <div class="contact-info fade-up">
          <div class="info-row">
            <div class="icon">☎</div>
            <div>
              <strong>Phone</strong>
              <span>
  <a href="tel:+917545090789," class="link">+91 7545090789,</a>
  <a href="tel:+919654626766" class="link">+91-9654626766</a>
</span>
            </div>
          </div>

          <div class="info-row">
  <div class="icon">
    <i class="fa-brands fa-instagram"></i>
  </div>
  <div>
    <strong>Instagram</strong>
    <span>
      <a href="https://www.instagram.com/narayana.construction/" target="_blank" style="color:#1e293b; font-weight:600;">
        narayana. construction
      </a>
    </span>
  </div>
</div>

          <div class="info-row">
            <div class="icon">@</div>
            <div>
              <strong>Email</strong>
              <span>
  <a href="mailto:narayanaofficial@hotmail.com" class="link">narayanaofficial@hotmail.com</a>
</span>
            </div>
          </div>

          <div class="info-row">
            <div class="icon">⌁</div>
            <div>
              <strong>Location</strong>
              <span>
  <a href="https://www.google.com/maps/search/?api=1&query=Delhi%2C%20India" target="_blank" class="link">
    India, Delhi,West Vinod Nagar
  </a>
</span>
            </div>
          </div>

          <p style="margin:16px 0 0; color:#374151; font-weight:600;">
            We would love to discuss your next project!
          </p>
        </div>

        <!-- Right: Form -->
        <div class="contact-form fade-up">
          <form id="contactForm">
            <div class="form-grid">
              <div>
                <label for="name">Name</label>
                <input id="name" name="name" type="text" placeholder="Your full name" required />
              </div>
              <div>
                <label for="email">Email</label>
                <input id="email" name="email" type="email" placeholder="you@example.com" required />
              </div>
              <div>
                <label for="phone">Phone</label>
                <input id="phone" name="phone" type="tel" placeholder="+91 98765 43210" required />
              </div>
              <div>
                <label for="message">Message</label>
                <textarea id="message" name="message" placeholder="Tell us about your project..." required></textarea>
              </div>

              <button class="btn btn-blue" type="submit">Send Message</button>
              <div class="success" id="successBox">✅ Thanks! Your message has been submitted. We’ll contact you soon.</div>
              <div class="form-note">Note: This demo form shows a success message (no database storage).</div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <div class="container footer-inner">
      <div style="display:flex; align-items:center; gap:12px;">
        <img src="logo.png" alt="Narayana Construction Logo" class="logo-img" style="width:42px;height:42px;padding:5px;">
        <div>
          <div style="font-weight:800;">Narayana Construction</div>
          <small>Construction • Interior • Building &amp; Infrastructure</small>
        </div>
      </div>
      <small>© <span id="year"></span> Narayana Construction. All rights reserved.</small>
    </div>
  </footer>

  <script>
    // Mobile menu toggle
    const hamburger = document.getElementById("hamburger");
    const mobilePanel = document.getElementById("mobilePanel");
    const mobileLinks = document.querySelectorAll(".mobile-link");

    hamburger.addEventListener("click", () => {
      const isOpen = mobilePanel.classList.toggle("show");
      hamburger.setAttribute("aria-expanded", String(isOpen));
    });

    mobileLinks.forEach(link => {
      link.addEventListener("click", () => {
        mobilePanel.classList.remove("show");
        hamburger.setAttribute("aria-expanded", "false");
      });
    });

    // Fade-in on scroll
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if(entry.isIntersecting){
          entry.target.classList.add("in");
          observer.unobserve(entry.target);
        }
      });
    }, { threshold: 0.15 });

    document.querySelectorAll(".fade-up").forEach(el => observer.observe(el));

    // Footer year
    document.getElementById("year").textContent = new Date().getFullYear();

    // Contact form demo submit (success message only)
    const form = document.getElementById("contactForm");
    const successBox = document.getElementById("successBox");

    form.addEventListener("submit", (e) => {
      e.preventDefault();
      successBox.style.display = "block";
      form.reset();
      setTimeout(() => { successBox.style.display = "none"; }, 4500);
    });
  </script>
</body>
</html># final_website.github.io
