<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>AddunMF_Resume </title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600;800&family=Roboto:wght@300;400;500&display=swap" rel="stylesheet">
  <style>
    :root{
      --accent:#2b8cff;
      --muted:#6b6f76;
      --text:#222;
    }
    *{box-sizing:border-box}
    body{font-family:Roboto, system-ui, -apple-system, 'Segoe UI', Arial; margin:0; color:var(--text); background:#fff}
    .container{max-width:980px; margin:48px auto; padding:40px 60px}
    header{ text-align:center; margin-bottom:28px }
    h1.name{font-family:Montserrat, sans-serif; font-weight:800; letter-spacing:2px; font-size:64px; margin:0; color:#5b5f66}
    .meta{margin-top:12px; color:var(--muted); font-style:italic}
    .contact{margin-top:8px; color:var(--muted); font-weight:400}
    .linkedin{display:inline-block; margin-left:12px; vertical-align:middle; text-decoration:none}
    .linkedin .badge{display:inline-block; padding:6px 10px; background:linear-gradient(180deg,#1e73b7,#0b66a3); color:white; border-radius:6px; font-weight:600; font-size:14px}
    hr.soft{border:none; border-top:1px solid #e7e7e7; margin:28px 0}

    .section-title{font-family:Montserrat, sans-serif; font-weight:600; font-size:20px; margin:0 0 14px; color:#222}
    .summary-box{color:#5b6066; line-height:1.6; font-size:16px}
    .summary-card{background:#fbfbfb; border:1px solid #efefef; padding:22px 28px; border-radius:6px}

    /* layout similar to screenshot with large left margin on header and content below a centered title */
    @media (max-width:720px){
      .container{padding:24px}
      h1.name{font-size:40px}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1 class="name">MYRTHEL FIONNAH I. ADDUN</h1>
      <div class="meta">Polangui, Albay, Philippines</div>
      <div class="contact">Email Address: <span style="font-style:normal;color:var(--text);">myrthelfionnah@gmail.com</span> | Contact: <span style="font-style:normal;color:var(--text);">+639XX XXX XXXX</span>
        <a class="linkedin" href="#" aria-label="LinkedIn">
          <span class="badge">LinkedIn</span>
        </a>
      </div>
    </header>

    <main>
      <section aria-labelledby="summary">
        <h2 id="summary" class="section-title">Professional Summary</h2>
        <div class="summary-card">
          <p class="summary-box">I’m a <strong>third‑year Animation student at Bicol University Polangui</strong> passionate about storytelling and crafting expressive character animation. I enjoy working across both 2D and 3D pipelines — from concept sketches and character design to blocking and final timing. Comfortable using tools like <em>Maya, Photoshop, and After Effects</em>, I’m always learning new techniques and exploring creative ways to convey emotion and movement. I’m enthusiastic about collaborating on projects that challenge my skills and help me grow as an animator and visual storyteller.</p>
        </div>
      </section>

      <hr class="soft">

      <!-- Work experiences removed as requested -->

    </main>
  </div>
</body>
</html>
