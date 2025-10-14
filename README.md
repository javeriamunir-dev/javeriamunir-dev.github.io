
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Javeria Munir — AI & Machine Learning Portfolio</title>
  <meta name="description" content="Portfolio of Javeria Munir — AI & Machine Learning Enthusiast. Projects, certifications and contact." />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{--bg:#f6fbff;--card:#ffffff;--accent:#0b63d6;--muted:#6b7280;--glass:rgba(255,255,255,0.6)}
    *{box-sizing:border-box}
    body{font-family:'Poppins',system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial; margin:0; background:linear-gradient(180deg,#f7fbff 0%,#eef6ff 100%); color:#0f172a}
    header{background:linear-gradient(90deg,var(--accent),#6c5ce7); color:#fff; padding:36px 20px}
    .container{max-width:980px;margin:0 auto;padding:28px}
    .nav{display:flex;align-items:center;justify-content:space-between;gap:12px}
    .brand{display:flex;align-items:center;gap:12px}
    .brand h1{font-size:20px;margin:0}
    nav a{color:rgba(255,255,255,0.95);text-decoration:none;margin-left:14px;font-weight:600}
    .hero{display:flex;gap:24px;align-items:center;margin-top:18px}
    .avatar{width:140px;height:140px;border-radius:12px;box-shadow:0 8px 24px rgba(12,20,40,0.18);flex:0 0 140px;overflow:hidden}
    .avatar img{width:100%;height:100%;object-fit:cover;display:block}
    .intro h2{margin:0 0 8px 0;font-size:28px}
    .intro p{margin:0;color:rgba(255,255,255,0.92)}
    .cta{margin-top:14px}
    .btn{display:inline-block;background:#fff;color:var(--accent);padding:10px 14px;border-radius:8px;text-decoration:none;font-weight:600;margin-right:10px}

    section{padding:36px 20px}
    h3.section-title{font-size:20px;margin:0 0 18px 0;color:#0b1220}

    .projects-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
    .card{background:var(--card);border-radius:12px;padding:16px;box-shadow:0 6px 18px rgba(12,20,40,0.06);display:flex;flex-direction:column;gap:12px}
    .card h4{margin:0;font-size:16px}
    .tools{display:flex;gap:8px;flex-wrap:wrap}
    .badge{background:#eef6ff;color:var(--accent);padding:6px 8px;border-radius:8px;font-weight:600;font-size:12px}
    .card p{margin:0;color:var(--muted);font-size:14px}
    .card .links{margin-top:auto;display:flex;gap:8px}
    .link-btn{background:var(--accent);color:#fff;padding:8px 10px;border-radius:8px;text-decoration:none;font-weight:600;font-size:13px}

    .skills{display:flex;gap:10px;flex-wrap:wrap}
    footer{padding:24px 20px;background:#fff;border-top:1px solid #eef2f7}

    @media (max-width:720px){.hero{flex-direction:column;align-items:flex-start}.avatar{width:110px;height:110px}}
  </style>
</head>
<body>
  <header>
    <div class="container">
      <div class="nav">
        <div class="brand">
          <h1>Javeria Munir</h1>
          <div style="font-size:13px;opacity:0.95">AI & Machine Learning Enthusiast • Python Developer</div>
        </div>
        <nav>
          <a href="#projects">Projects</a>
          <a href="#cert">Certification</a>
          <a href="#about">About</a>
          <a href="#contact">Contact</a>
        </nav>
      </div>

      <div class="hero">
        <div class="avatar">
          <!-- Avatar (DiceBear generated) -->
          <img src="https://avatars.dicebear.com/api/identicon/javeria-munir.svg" alt="Javeria Munir Avatar" />
        </div>
        <div class="intro">
          <h2>AI & Machine Learning Enthusiast</h2>
          <p>Hands-on with Python, Scikit-learn, TensorFlow and practical projects demonstrating applied machine learning techniques. Certified by FreeCodeCamp.</p>
          <div class="cta">
            <a class="btn" href="#projects">View Projects</a>
            <a class="btn" href="/Javeria_Munir_Resume.pdf" target="_blank">Download Resume</a>
          </div>
        </div>
      </div>
    </div>
  </header>

  <main class="container">
    <section id="projects">
      <h3 class="section-title">Selected Projects (Machine Learning with Python)</h3>
      <div class="projects-grid">
        <article class="card">
          <h4>1. Cat vs Dog Image Classifier</h4>
          <div class="tools"><span class="badge">TensorFlow</span><span class="badge">CNN</span><span class="badge">OpenCV</span></div>
          <p>Built a convolutional neural network to classify images of cats and dogs. Implemented data augmentation, transfer learning with a pre-trained model, and evaluated accuracy & confusion matrix.</p>
          <div class="links">
            <a class="link-btn" href="https://www.freecodecamp.org/certification/javeriamunir/machine-learning-with-python-v7" target="_blank">View Certificate</a>
            <a class="link-btn" href="#" target="_blank">View Code</a>
          </div>
        </article>

        <article class="card">
          <h4>2. Predict Housing Prices</h4>
          <div class="tools"><span class="badge">Scikit-learn</span><span class="badge">Regression</span><span class="badge">Pandas</span></div>
          <p>Implemented linear and ridge regression models to predict housing prices from feature-engineered datasets. Performed cross-validation and feature importance analysis.</p>
          <div class="links">
            <a class="link-btn" href="https://www.freecodecamp.org/certification/javeriamunir/machine-learning-with-python-v7" target="_blank">View Certificate</a>
            <a class="link-btn" href="#" target="_blank">View Code</a>
          </div>
        </article>

        <article class="card">
          <h4>3. Book Recommendation Engine</h4>
          <div class="tools"><span class="badge">KNN</span><span class="badge">Cosine</span><span class="badge">NumPy</span></div>
          <p>Created a collaborative filtering based recommender using cosine similarity and KNN on user-item matrices. Evaluated with precision@k and implemented simple UI for demo.</p>
          <div class="links">
            <a class="link-btn" href="https://www.freecodecamp.org/certification/javeriamunir/machine-learning-with-python-v7" target="_blank">View Certificate</a>
            <a class="link-btn" href="#" target="_blank">View Code</a>
          </div>
        </article>

        <article class="card">
          <h4>4. Stock Price Predictor</h4>
          <div class="tools"><span class="badge">LSTM</span><span class="badge">Keras</span><span class="badge">Matplotlib</span></div>
          <p>Developed an LSTM model to forecast stock prices using time-series input sequences. Performed scaling, windowing, and evaluated with MAPE and RMSE metrics.</p>
          <div class="links">
            <a class="link-btn" href="https://www.freecodecamp.org/certification/javeriamunir/machine-learning-with-python-v7" target="_blank">View Certificate</a>
            <a class="link-btn" href="#" target="_blank">View Code</a>
          </div>
        </article>

        <article class="card">
          <h4>5. Chatbot using NLP</h4>
          <div class="tools"><span class="badge">NLTK</span><span class="badge">Regex</span><span class="badge">Python</span></div>
          <p>Built a simple rule-based + ML chatbot for FAQ handling. Implemented tokenization, intent classification and simple response generation.</p>
          <div class="links">
            <a class="link-btn" href="https://www.freecodecamp.org/certification/javeriamunir/machine-learning-with-python-v7" target="_blank">View Certificate</a>
            <a class="link-btn" href="#" target="_blank">View Code</a>
          </div>
        </article>

      </div>
    </section>

    <section id="cert">
      <h3 class="section-title">Certification</h3>
      <div class="card">
        <h4>FreeCodeCamp — Machine Learning with Python</h4>
        <p class="muted">Verified certification with 5 hands-on projects demonstrating applied ML skills.</p>
        <div style="margin-top:12px">
          <a class="link-btn" href="https://www.freecodecamp.org/certification/javeriamunir/machine-learning-with-python-v7" target="_blank">View Certification</a>
        </div>
      </div>
    </section>

    <section id="about">
      <h3 class="section-title">About & Education</h3>
      <div class="card">
        <h4>Education</h4>
        <p>The Islamia University Bahawalpur — B.Sc. (Final Year / Coursework in Computer Science)</p>
        <h4 style="margin-top:12px">Summary</h4>
        <p>I am a motivated AI student building practical ML projects in Python. I focus on applied solutions and reproducible code with clear results and evaluations.</p>
        <div style="margin-top:12px">
          <strong>Tools & Technologies</strong>
          <div class="skills" style="margin-top:8px">
            <span class="badge">Python</span>
            <span class="badge">TensorFlow</span>
            <span class="badge">Keras</span>
            <span class="badge">Scikit-learn</span>
            <span class="badge">Pandas</span>
            <span class="badge">NumPy</span>
          </div>
        </div>
      </div>
    </section>

    <section id="contact">
      <h3 class="section-title">Contact</h3>
      <div class="card">
        <p>Want to collaborate or see my code? Reach out:</p>
        <div style="display:flex;gap:8px;align-items:center;flex-wrap:wrap;margin-top:8px">
          <a class="link-btn" href="https://github.com/javeriamunir" target="_blank">GitHub</a>
          <a class="link-btn" href="https://www.freecodecamp.org/javeriamunir" target="_blank">FreeCodeCamp</a>
          <a class="link-btn" href="#" target="_blank">LinkedIn</a>
        </div>
      </div>
    </section>

  </main>

  <footer>
    <div class="container">
      <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
        <div>© <strong>Javeria Munir</strong> · The Islamia University Bahawalpur</div>
        <div style="font-size:13px;color:var(--muted)">Built for portfolio • Ready for GitHub Pages</div>
      </div>
    </div>
  </footer>

</body>
</html>
