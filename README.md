<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Daniel Yumnam — Home</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body{background:#071022;color:#e6eef6;font-family:Inter,system-ui,Segoe UI,Roboto,Arial}
    .site{max-width:1000px;margin:36px auto}
    .logo{width:56px;height:56px;background:linear-gradient(135deg,#06b6d4,#7c3aed);border-radius:10px;display:inline-flex;align-items:center;justify-content:center;font-weight:700;color:#021226}
    header{display:flex;justify-content:space-between;align-items:center;margin-bottom:20px}
    nav a{color:#94a3b8;margin-left:12px;text-decoration:none}
    nav a:hover{color:#06b6d4}
    .card{background:rgba(255,255,255,0.03);padding:18px;border-radius:10px}
  </style>
</head>
<body>
  <div class="site">
    <header>
      <div style="display:flex;align-items:center;gap:12px">
        <div class="logo">DY</div>
        <div>
          <div style="font-weight:700">Daniel Yumnam</div>
          <div style="color:#94a3b8;font-size:13px">PhD · LIDAR & Beam Steering</div>
        </div>
      </div>
      <nav>
        <a href="multi_index.html">Home</a>
        <a href="about.html">About</a>
        <a href="projects.html">Projects</a>
        <a href="gallery.html">Gallery</a>
        <a href="blog.html">Blog</a>
        <a href="contact.html">Contact</a>
      </nav>
    </header>

    <main>
      <div class="card">
        <h1>Hi — I'm Daniel.</h1>
        <p style="color:#94a3b8">I build instrumentation, beam-steering systems and simulations for LIDAR & photonics. Browse the site to see projects, photos, and posts.</p>
        <p>
          <a href="gallery.html" class="btn btn-outline-light btn-sm">View Gallery</a>
          <a href="blog.html" class="btn btn-primary btn-sm ms-2">Read Blog</a>
        </p>
      </div>

      <section style="margin-top:18px">
        <h4 style="margin-bottom:8px">Featured Projects</h4>
        <div class="row g-3">
          <div class="col-md-6">
            <div class="card">
              <h5>Resonance Batch Fitting Tool</h5>
              <p style="color:#94a3b8">A Python script for automated Lorentzian fitting across many measurement files. Exports plots and CSV summaries.</p>
            </div>
          </div>
          <div class="col-md-6">
            <div class="card">
              <h5>To-Do Web App</h5>
              <p style="color:#94a3b8">Single-file Flask application with SQLite and CSV export — useful for personal task management.</p>
            </div>
          </div>
        </div>
      </section>

    </main>

    <footer style="margin-top:28px;color:#94a3b8">© <span id="yr"></span> Daniel Yumnam</footer>
  </div>
  <script>document.getElementById('yr').textContent=new Date().getFullYear();</script>
</body>
</html>
