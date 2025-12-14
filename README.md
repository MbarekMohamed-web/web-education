<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Your Business — Premium Web Solutions</title>
  <meta name="description" content="Empower your online presence with creative design, performance and seamless user experience." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    :root {
      --bg: #0f172a;
      --card: #1e293b;
      --accent: #06b6d4;
      --text: #f8fafc;
      --muted: #94a3b8;
      --radius: 14px;
      font-family: 'Poppins', sans-serif;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{background:var(--bg);color:var(--text);line-height:1.6;overflow-x:hidden;scroll-behavior:smooth;}
    header{position:fixed;top:0;left:0;width:100%;background:rgba(15,23,42,0.9);backdrop-filter:blur(8px);padding:18px 48px;display:flex;align-items:center;justify-content:space-between;z-index:10;transition:background 0.3s}
    header.scrolled{background:#0f172a;}
    .logo{font-size:1.4rem;font-weight:700;color:var(--accent)}
    nav a{margin:0 12px;color:var(--muted);text-decoration:none;font-weight:500;transition:color .3s}
    nav a:hover{color:var(--accent)}
    .cta{background:var(--accent);color:var(--bg);padding:10px 18px;border-radius:var(--radius);text-decoration:none;font-weight:700;transition:all .3s}
    .cta:hover{transform:scale(1.05);}

    .hero{display:flex;flex-direction:column;align-items:center;justify-content:center;min-height:100vh;text-align:center;background:radial-gradient(circle at top right, #06b6d4 0%, #0f172a 60%);padding:0 20px;}
    .hero h1{font-size:clamp(2rem,5vw,3.5rem);font-weight:700;animation:fadeInUp 1.3s ease both}
    .hero p{max-width:600px;margin:16px auto 28px;color:var(--muted);animation:fadeInUp 1.5s ease both}
    .hero .cta{animation:fadeInUp 1.8s ease both}
    @keyframes fadeInUp{0%{opacity:0;transform:translateY(40px)}100%{opacity:1;transform:translateY(0)}}

    section{padding:80px 20px;max-width:1100px;margin:auto}
    h2{text-align:center;margin-bottom:40px;font-size:2rem;color:var(--accent)}

    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:24px}
    .card{background:var(--card);padding:24px;border-radius:var(--radius);box-shadow:0 4px 20px rgba(0,0,0,0.3);transition:transform .4s,box-shadow .4s;}
    .card:hover{transform:translateY(-6px);box-shadow:0 8px 24px rgba(0,0,0,0.5)}
    .card i{font-size:2rem;color:var(--accent);margin-bottom:12px}

    .testimonial{display:flex;flex-direction:column;align-items:center;text-align:center;gap:10px;background:var(--card);padding:28px;border-radius:var(--radius)}
    .testimonial img{width:64px;height:64px;border-radius:50%;border:2px solid var(--accent)}

    form{display:grid;gap:14px;max-width:500px;margin:auto}
    input,textarea,button{font:inherit;padding:12px 14px;border:none;border-radius:var(--radius)}
    input,textarea{background:#1e293b;color:var(--text)}
    button{background:var(--accent);color:var(--bg);font-weight:700;cursor:pointer;transition:background .3s}
    button:hover{background:#0891b2}

    footer{background:#020617;color:var(--muted);padding:24px;text-align:center;font-size:14px}

    @media(max-width:700px){header{padding:12px 24px;flex-direction:column;gap:10px}}
  </style>
</head>
<body>
  <header id="header">
    <div class="logo">YourBusiness</div>
    <nav>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#testimonials">Testimonials</a>
      <a href="#contact">Contact</a>
    </nav>
    <a href="#contact" class="cta">Get Started</a>
  </header>

  <section class="hero">
    <h1>Grow Your Business with Stunning Web Experiences</h1>
    <p>We craft responsive, SEO-optimized, and visually appealing websites that turn visitors into loyal customers.</p>
    <a href="#contact" class="cta">Let’s Build Together</a>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="grid">
      <div class="card"><i class="fas fa-laptop-code"></i><h3>Web Development</h3><p>modren, fast, and secure websites designed for your business growth.</p></div>
      <div class="card"><i class="fas fa-paint-brush"></i><h3>UI/UX Design</h3><p>Beautiful interfaces and intuitive designs that engage your customers.</p></div>
      <div class="card"><i class="fas fa-bullhorn"></i><h3>Digital Marketing</h3><p>Boost your brand visibility with SEO, ads, and social media strategies.</p></div>
      <div class="card"><i class="fas fa-chart-line"></i><h3>Analytics</h3><p>Data-driven insights to measure performance and maximize ROI.</p></div>
    </div>
  </section>

  <section id="testimonials">
    <h2>What Clients Say</h2>
    <div class="grid">
      <div class="testimonial"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e8/Tigre.jpg/1200px-Tigre.jpg" alt="client"><p>“Amazing experience! My sales grew 40% in just one month.”</p><strong>- Amina B.</strong></div>
      <div class="testimonial"><img src="https://i.pravatar.cc/64?img=2" alt="client"><p>“Creative and professional team, they understood exactly what I wanted.”</p><strong>- Karim M.</strong></div>
      <div class="testimonial"><img src="https://i.pravatar.cc/64?img=3" alt="client"><p>“Excellent support and fast delivery. Highly recommended.”</p><strong>- Leila S.</strong></div>
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <div class="card" style="text-align:center">
      <p>We are a passionate team of developers and designers committed to building powerful online identities. Our mission is to bring creativity and technology together to grow your brand.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form id="contactForm">
      <input type="text" name="name" placeholder="Your name" required />
      <input type="email" name="email" placeholder="Your email" required />
      <textarea name="message" placeholder="Your message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>© <span id="year"></span> Your Business. All rights reserved.</footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
    window.addEventListener('scroll',()=>{document.getElementById('header').classList.toggle('scrolled',window.scrollY>50)});
    const form=document.getElementById('contactForm');
    form.addEventListener('submit',e=>{e.preventDefault();alert('Thank you! Your message has been sent.');form.reset();});
  </script>
</body>
</html>
