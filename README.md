<!doctype html>
<html lang="de">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Oussama Guedri – Referenzen & Skills</title>
  <meta name="description" content="Kompakte One‑Pager‑Übersicht: Referenzen & Skills von Oussama Guedri (Maschinenbau)." />
  <style>
    :root{
      --bg:#ffffff;
      --txt:#1a1a1a;
      --muted:#666;
      --acc:#ff6b35;         /* Orange Akzent */
      --acc-2:#ffa94d;       /* Heller Orange */
      --border:#e0e0e0;
      --chip:#fafafa;
      --shadow: 0 8px 24px rgba(0,0,0,.08);
    }
    body{margin:0;background:var(--bg);color:var(--txt);font:16px/1.6 "Segoe UI",Roboto,Ubuntu,sans-serif}
    .wrap{max-width:880px;margin:0 auto;padding:40px 20px}

    header{text-align:center;padding-bottom:20px;border-bottom:2px solid var(--border)}
    .name{font-size:34px;font-weight:700;margin:0}
    .role{margin:8px 0;color:var(--muted);font-size:18px}
    .contacts{margin-top:10px;font-size:15px}
    .contacts a{color:var(--acc);text-decoration:none;margin:0 8px}
    .contacts a:hover{color:var(--acc-2)}

    section{margin-top:30px}
    h2{font-size:22px;margin-bottom:14px;position:relative}
    h2::after{content:"";display:block;width:40px;height:3px;background:var(--acc);margin-top:6px;border-radius:2px}

    .card{background:#fff;border:1px solid var(--border);border-radius:16px;padding:20px;margin-bottom:20px;box-shadow:var(--shadow);transition:transform .2s}
    .card:hover{transform:translateY(-4px)}

    .tags{display:flex;flex-wrap:wrap;gap:10px}
    .tag{background:var(--chip);border:1px solid var(--border);border-radius:20px;padding:8px 14px;font-size:14px}

    ul{margin:0;padding-left:20px}
    li{margin:6px 0}

    footer{text-align:center;padding:20px;color:var(--muted);font-size:14px;margin-top:20px;border-top:2px solid var(--border)}

    /* Highlight Box */
    .highlight{background:linear-gradient(135deg,var(--acc),var(--acc-2));color:#fff;padding:18px;border-radius:16px;text-align:center;box-shadow:var(--shadow)}
    .highlight a{color:#fff;font-weight:600;text-decoration:none}
    .highlight a:hover{text-decoration:underline}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <h1 class="name">Oussama Guedri</h1>
      <p class="role">Maschinenbau · Fertigungs‑/Qualitäts‑/Produktionsingenieur</p>
      <div class="contacts">
        <a href="mailto:Oussamaguedri@gmail.com">E‑Mail</a> ·
        <a href="tel:+491637254664">Telefon</a> · Hannover
      </div>
    </header>

    <section>
      <div class="card">
        <h2>Skills</h2>
        <div class="tags">
          <span class="tag">FEM · Simufact</span>
          <span class="tag">CATIA V5</span>
          <span class="tag">Solid Edge</span>
          <span class="tag">ANSYS</span>
          <span class="tag">SAP</span>
          <span class="tag">Python</span>
          <span class="tag">C++</span>
          <span class="tag">MATLAB</span>
          <span class="tag">MS Excel</span>
          <span class="tag">PowerPoint</span>
          <span class="tag">Prozessoptimierung</span>
          <span class="tag">Qualitätssicherung</span>
        </div>
      </div>

      <div class="card">
        <h2>Referenzen</h2>
        <ul>
          <li><strong>BMW AG, München</strong> – Praxissemester Konstruktion E‑Getriebe (06/2023–11/2023).</li>
          <li><strong>IPH Hannover</strong> – Bachelorarbeit FEM‑Simulation Ringstauchversuch (02/2024–07/2024).</li>
          <li><strong>Volkswagen AG</strong> – Stud. Hilfskraft Produktion (2018–2020).</li>
          <li><strong>ILFA GmbH</strong> – Praktikum Leiterplattenfertigung (2019).</li>
          <li><strong>Hanomag Lohnhärterei</strong> – Grundpraktikum (2017).</li>
        </ul>
      </div>

      <div class="card">
        <h2>Sprachen</h2>
        <div class="tags">
          <span class="tag">Deutsch C1</span>
          <span class="tag">Arabisch C2</span>
          <span class="tag">Französisch C2</span>
          <span class="tag">Englisch B2</span>
          <span class="tag">Spanisch A2</span>
        </div>
      </div>

      <div class="highlight">
        <p>📩 Direktkontakt: <a href="mailto:Oussamaguedri@gmail.com">Oussamaguedri@gmail.com</a> · 📞 <a href="tel:+491637254664">+49 163 7254664</a></p>
        <p>📍 Mendelssohnstraße 26 C, 30419 Hannover</p>
      </div>
    </section>

    <footer>
      © <span id="year"></span> Oussama Guedri · One‑Pager (QR Landing Page)
    </footer>
  </div>

  <script>document.getElementById('year').textContent=new Date().getFullYear()</script>
</body>
</html>
