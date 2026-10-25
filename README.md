
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#102a43">
  <meta name="description" content="Ranker's Zone Coaching Academy offers school tuition in GIDC Ankleshwar.">
  <title>Ranker's Zone Coaching Academy | Ankleshwar</title>
  <style>
    :root {
      --navy: #102a43;
      --blue: #1769aa;
      --gold: #ffc857;
      --light: #f1f7fc;
      --text: #253746;
    }
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      color: var(--text);
      line-height: 1.65;
    }
    .container { width: min(1100px, 90%); margin: auto; }
    header {
      background: var(--navy);
      color: white;
      padding: 17px 0;
    }
    .nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 16px;
      flex-wrap: wrap;
    }
    .brand { font-size: 1.15rem; font-weight: bold; }
    .brand small {
      display: block;
      color: var(--gold);
      font-size: .78rem;
      letter-spacing: 2px;
      text-transform: uppercase;
    }
    nav { display: flex; gap: 18px; flex-wrap: wrap; }
    nav a { color: white; text-decoration: none; font-weight: bold; }
    nav a:hover { color: var(--gold); }
    .hero {
      background: linear-gradient(135deg, var(--light), white);
      padding: 85px 0;
    }
    .hero-grid {
      display: grid;
      grid-template-columns: 1.2fr .8fr;
      gap: 35px;
      align-items: center;
    }
    .eyebrow {
      color: var(--blue);
      font-weight: bold;
      text-transform: uppercase;
      letter-spacing: 2px;
    }
    h1 {
      color: var(--navy);
      font-size: clamp(2.5rem, 6vw, 4.5rem);
      line-height: 1.08;
      margin: 15px 0;
    }
    h1 span { color: var(--blue); }
    .hero p { font-size: 1.1rem; }
    .hero-card {
      background: white;
      padding: 28px;
      border-radius: 22px;
      box-shadow: 0 12px 45px #102a4320;
      border-top: 5px solid var(--gold);
    }
    .hero-card h2 { color: var(--navy); }
    .button {
      display: inline-block;
      background: var(--gold);
      color: var(--navy);
      padding: 12px 20px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      margin: 8px 8px 8px 0;
    }
    .button:hover { filter: brightness(.95); }
    .button-blue { background: var(--blue); color: white; }
    section { padding: 65px 0; }
    .section-title {
      color: var(--navy);
      font-size: clamp(2rem, 4vw, 2.8rem);
      margin: 0 0 15px;
    }
    .center { text-align: center; }
    .about-grid, .contact-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 30px;
      align-items: center;
    }
    .panel {
      background: var(--light);
      border-radius: 20px;
      padding: 28px;
    }
    .course-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
      margin-top: 30px;
    }
    .course {
      padding: 25px;
      border: 1px solid #dce6ee;
      border-radius: 18px;
      background: white;
    }
    .course h3 { color: var(--navy); }
    .icon { font-size: 2rem; }
    .muted { color: #5d7181; }
    .contact { background: var(--light); }
    .contact-card {
      background: white;
      padding: 26px;
      border-radius: 18px;
      border: 1px solid #dce6ee;
    }
    footer {
      background: #0b1e2e;
      color: white;
      text-align: center;
      padding: 25px 0;
    }
    .whatsapp-float {
      position: fixed;
      bottom: 18px;
      right: 18px;
      z-index: 5;
      background: #20b858;
      color: white;
      text-decoration: none;
      padding: 13px 18px;
      border-radius: 30px;
      font-weight: bold;
      box-shadow: 0 5px 20px #0002;
    }
    @media (max-width: 760px) {
      .hero-grid, .about-grid, .contact-grid, .course-grid {
        grid-template-columns: 1fr;
      }
      .hero { padding: 55px 0; }
      nav { gap: 12px; }
      section { padding: 48px 0; }
    }
  </style>
</head>
<body>

<header>
  <div class="container nav">
    <div class="brand">
      Ranker's Zone
      <small>Coaching Academy</small>
    </div>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#courses">Courses</a>
      <a href="#contact">Contact</a>
    </nav>
  </div>
</header>

<main>
  <section class="hero" id="home">
    <div class="container hero-grid">
      <div>
        <div class="eyebrow">Learn • Practise • Progress</div>
        <h1>Build strong basics.<br><span>Reach your goals.</span></h1>
        <p>
          Welcome to Ranker's Zone Coaching Academy in Ankleshwar.
          We aim to help school students develop clear concepts,
          regular study habits and confidence in learning.
        </p>
        <a class="button"
           href="https://wa.me/919322012555?text=Hello%20Rankers%20Zone%2C%20I%20want%20to%20enquire%20about%20school%20tuition."
           target="_blank" rel="noopener">Enquire on WhatsApp ↗</a>
        <a class="button button-blue" href="#courses">Explore Tuition</a>
      </div>

      <div class="hero-card">
        <div class="icon">🎓 📚</div>
        <h2>Your learning journey starts here</h2>
        <p>Focused school tuition, practice and revision to support your academic journey.</p>
        <hr>
        <p>✓ Concept-focused learning</p>
        <p>✓ Regular practice and revision</p>
        <p>✓ Student-focused guidance</p>
      </div>
    </div>
  </section>

  <section id="about">
    <div class="container about-grid">
      <div>
        <div class="eyebrow">About our academy</div>
        <h2 class="section-title">A place to learn and grow</h2>
        <p>
          At Ranker's Zone Coaching Academy, we believe that clear
          understanding, consistent effort and regular revision are
          important foundations for academic progress.
        </p>
        <p>
          Contact us to discuss the student's class, subjects and
          available tuition options.
        </p>
      </div>
      <div class="panel">
        <h3 style="color:#102a43">Our approach</h3>
        <p>📘 Build strong subject fundamentals</p>
        <p>✍️ Encourage regular study and practice</p>
        <p>🎯 Help students work towards their goals</p>
        <p>🤝 Stay connected with parents and students</p>
      </div>
    </div>
  </section>

  <section id="courses" style="background:#fbfdff">
    <div class="container">
      <div class="center">
        <div class="eyebrow">What we offer</div>
        <h2 class="section-title">School Tuition</h2>
        <p class="muted">Ask us about tuition options for your student's class and subjects.</p>
      </div>

      <div class="course-grid">
        <div class="course">
          <div class="icon">📚</div>
          <h3>School Subject Tuition</h3>
          <p class="muted">Support for school learning and subject requirements.</p>
        </div>
        <div class="course">
          <div class="icon">🧠</div>
          <h3>Concept Building</h3>
          <p class="muted">Focus on understanding key ideas and strengthening basics.</p>
        </div>
        <div class="course">
          <div class="icon">📝</div>
          <h3>Practice & Revision</h3>
          <p class="muted">Build a steady routine of practice and revision.</p>
        </div>
      </div>

      <p class="center muted" style="margin-top:25px">
        Please contact the academy to confirm classes, subjects, batch timings and fees.
      </p>
      <div class="center">
        <a class="button"
           href="https://wa.me/919322012555?text=Hello%2C%20please%20share%20school%20tuition%20details."
           target="_blank" rel="noopener">Ask About Tuition</a>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <div class="container">
      <div class="center">
        <div class="eyebrow">Get in touch</div>
        <h2 class="section-title">Contact Our Academy</h2>
        <p class="muted">Message us on WhatsApp for tuition and admission enquiries.</p>
      </div>

      <div class="contact-grid" style="margin-top:30px">
        <div class="contact-card">
          <h3 style="color:#102a43">Visit us</h3>
          <p><strong>📍 Address</strong><br>
            S46, Ganesh Square,<br>
            GIDC Ankleshwar, Gujarat, India
          </p>
          <p><strong>📱 Phone / WhatsApp</strong><br>
            +91 93220 12555
          </p>
          <p><strong>🎓 Programme</strong><br>School Tuition</p>
          <a class="button button-blue"
             href="https://www.google.com/maps/search/?api=1&query=S46%2C%20Ganesh%20Square%2C%20GIDC%20Ankleshwar"
             target="_blank" rel="noopener">Open Google Maps ↗</a>
        </div>

        <div class="contact-card">
          <h3 style="color:#102a43">Student enquiry</h3>
          <p>Click the button to open WhatsApp. You can add the student's details before sending your message.</p>
          <div class="panel">
            Student name: __________<br>
            Current class: __________<br>
            Subjects required: __________
          </div>
          <a class="button"
             href="https://wa.me/919322012555?text=Hello%20Rankers%20Zone%20Coaching%20Academy.%0AI%20want%20to%20enquire%20about%20school%20tuition.%0AStudent%20name%3A%20%0ACurrent%20class%3A%20%0ASubjects%3A%20"
             target="_blank" rel="noopener">Start WhatsApp Enquiry ↗</a>
        </div>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="container">
    <strong>Ranker's Zone Coaching Academy</strong>
    <p>S46, Ganesh Square, GIDC Ankleshwar</p>
    <p>© <span id="year"></span> Ranker's Zone Coaching Academy</p>
  </div>
</footer>

<a class="whatsapp-float"
   href="https://wa.me/919322012555?text=Hello%20Rankers%20Zone%20Coaching%20Academy%2C%20I%20have%20an%20enquiry."
   target="_blank" rel="noopener">☏ WhatsApp</a>

<script>
  document.getElementById("year").textContent = new Date().getFullYear();
</script>
</body>
</html>
