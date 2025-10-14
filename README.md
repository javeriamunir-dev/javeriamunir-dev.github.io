

      <!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Javeria Munir — Applied AI & Machine Learning Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
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
            </div>
            <nav>
                <a href="#projects">Projects</a>
                <a href="#cert">Certification</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
        <div class="hero">
            <div class="avatar">
                <img src="https://avatars.dicebear.com/api/identicon/javeria-munir.svg" alt="Javeria Munir Avatar" />
            </div>
            <div class="intro">
                <h2>Applied AI & Machine Learning Engineer</h2>
                <p>Hands-on experience with Python, TensorFlow, and Scikit-learn, focused on building robust models and evaluating performance using key metrics.</p>
                <div class="cta">
                    <a class="btn" href="#projects">View Projects</a>
                    <a class="btn" href="/Javeria_Munir_Resume.pdf" target="_blank">Download Resume</a> 
                </div>
            </div>
        </div>
    </div>
</header>

<section id="projects" class="container">
    <h3 class="section-title">Applied Machine Learning Portfolio</h3>
    <div class="projects-grid">
        
        <article class="card">
            <h4>1. RL Agent: Adaptive RPS</h4>
            <div class="tools"><span class="badge">Python</span><span class="badge">Reinforcement Learning</span><span class="badge">Q-Learning</span></div>
            <p>**Core RL Implementation:** Built an **Adaptive Agent** using **Q-Learning** that learns optimal strategy via reward maximization. Project includes a **visualization of the learning progress** (Win Rate over time).</p>
            <div class="links">
                <a class="link-btn" href="https://github.com/javeriamunir-dev/rock-paper-scissors" target="_blank">View Code</a> 
                </div>
        </article>

        <article class="card">
            <h4>2. Cat vs Dog Image Classifier</h4>
            <div class="tools"><span class="badge">TensorFlow</span><span class="badge">CNN</span><span class="badge">Computer Vision</span></div>
            <p>**Achieved 94% Accuracy** on image classification using a custom-built **CNN** model. Demonstrated proficiency in **Transfer Learning** and essential **Data Augmentation** techniques to ensure model robustness.</p>
            <div class="links">
                <a class="link-btn" href="#" target="_blank">View Code</a>
            </div>
        </article>

        <article class="card">
            <h4>3. Predict Housing Prices</h4>
            <div class="tools"><span class="badge">Scikit-learn</span><span class="badge">Regression</span><span class="badge">Pandas</span></div>
            <p>Solved a **Regression** problem by predicting housing prices with a low **RMSE** (Root Mean Square Error). Focus on **Feature Engineering** and tuning **Ridge Regression** to maximize model stability.</p>
            <div class="links">
                <a class="link-btn" href="#" target="_blank">View Code</a>
            </div>
        </article>

        <article class="card">
            <h4>4. Book Recommendation Engine</h4>
            <div class="tools"><span class="badge">KNN</span><span class="badge">Cosine Similarity</span><span class="badge">Unsupervised</span></div>
            <p>Developed a **Collaborative Filtering** system for book recommendations. Utilized **K-Nearest Neighbors (KNN)** and **Cosine Similarity** on sparse matrices, addressing scalability challenges inherent in large user-item datasets.</p>
            <div class="links">
                <a class="link-btn" href="#" target="_blank">View Code</a>
            </div>
        </article>
        
        <article class="card">
            <h4>5. Stock Price Predictor (Time Series)</h4>
            <div class="tools"><span class="badge">LSTM</span><span class="badge">Keras</span><span class="badge">Time Series</span></div>
            <p>Built a **Time-Series Forecasting** model using **LSTM** to predict stock prices. Implemented data scaling and windowing for sequence data, focusing on minimizing **MAPE** (Mean Absolute Percentage Error).</p>
            <div class="links">
                <a class="link-btn" href="#" target="_blank">View Code</a>
            </div>
        </article>

        <article class="card">
            <h4>6. Chatbot using NLP</h4>
            <div class="tools"><span class="badge">NLTK</span><span class="badge">NLP</span><span class="badge">Python</span></div>
            <p>Created an FAQ Chatbot demonstrating **Natural Language Processing (NLP)** fundamentals. Used **Tokenization** and **Intent Classification** to categorize user queries and generate accurate, rule-based responses.</p>
            <div class="links">
                <a class="link-btn" href="#" target="_blank">View Code</a>
            </div>
        </article>

    </div>
</section>

<section id="cert" class="container">
    <h3 class="section-title">Certification & Skills</h3>
    <div class="card">
        <h4>FreeCodeCamp — Machine Learning with Python</h4>
        <p class="muted">Verified certification with 5 hands-on projects demonstrating applied ML skills and mastery of fundamental concepts.</p>
        <div style="margin-top:12px">
            <a class="link-btn" href="https://www.freecodecamp.org/certification/javeriamunir/machine-learning-with-python-v7" target="_blank">View Certification</a>
        </div>
        <h4 style="margin-top:16px">Core Tools & Technologies</h4>
        <div class="skills" style="margin-top:8px">
            <span class="badge">Python</span>
            <span class="badge">TensorFlow</span>
            <span class="badge">Keras</span>
            <span class="badge">Scikit-learn</span>
            <span class="badge">Pandas</span>
            <span class="badge">NumPy</span>
            <span class="badge">Streamlit (For Deployment)</span>
        </div>
    </div>
</section>

<section id="contact" class="container">
    <h3 class="section-title">Connect with Me</h3>
    <div class="card">
        <p>I'm open to collaborations on practical AI solutions and MLOps challenges. Let's connect:</p>
        <div style="display:flex;gap:8px;align-items:center;flex-wrap:wrap;margin-top:8px">
            <a class="link-btn" href="https://github.com/javeriamunir-dev" target="_blank">GitHub</a>
            <a class="link-btn" href="#" target="_blank">LinkedIn</a> 
            <a class="link-btn" href="mailto:your.email@example.com" target="_blank">Email</a>
        </div>
    </div>
</section>

<footer>
    <div class="container">
        © **Javeria Munir** — Applied AI Portfolio. Built for GitHub Pages.
    </div>
</footer>

</body>
</html>
