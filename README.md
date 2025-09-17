<!doctype html>
<html lang="de">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Oussama Guedri – One‑Pager Lebenslauf</title>
  <meta name="description" content="One‑Pager Lebenslauf von Oussama Guedri – Maschinenbau (Fertigungs‑ / Qualitäts‑ / Produktionsingenieur)." />
  <style>
    :root{
      --bg:#0b1736;          /* Dunkelblau */
      --bg-elev:#0f204a;     /* leicht heller für Karten */
      --txt:#e8ecf4;         /* Text hell */
      --muted:#a7b3ce;       /* Sekundärtext */
      --acc:#2dd4bf;         /* Türkis/Grün Akzent */
      --acc-2:#5eead4;       /* heller Akzent */
      --chip:#122a66;        /* Badge-Hintergrund */
      --border:#203869;
      --shadow: 0 10px 30px rgba(0,0,0,.35);
    }
    html{scroll-behavior:smooth}
    body{margin:0;background:linear-gradient(180deg,var(--bg),#0a1a40 30%, #0c1f4d);color:var(--txt);font:16px/1.6 system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,Noto Sans,sans-serif}
    a{color:var(--acc);text-decoration:none}
    a:hover{color:var(--acc-2)}
    .container{max-width:1080px;margin:0 auto;padding:0 20px}
    /* Header */
    header{position:sticky;top:0;backdrop-filter:saturate(140%) blur(8px);background:rgba(11,23,54,.7);border-bottom:1px solid var(--border);z-index:50}
    .nav{display:flex;align-items:center;justify-content:space-between;padding:14px 0}
    .brand{display:flex;gap:12px;align-items:center;font-weight:700;letter-spacing:.3px}
    .brand .dot{width:10px;height:10px;border-radius:50%;background:linear-gradient(135deg,var(--acc),var(--acc-2));box-shadow:0 0 0 3px rgba(45,212,191,.18)}
    nav ul{list-style:none;display:flex;gap:20px;margin:0;padding:0}
    nav a{padding:8px 10px;border-radius:10px}
    nav a:hover{background:rgba(255,255,255,.06)}

    /* Hero */
    .hero{padding:64px 0 28px;border-bottom:1px solid var(--border)}
    .tag{display:inline-flex;gap:8px;align-items:center;background:var(--chip);border:1px solid var(--border);color:var(--acc-2);padding:6px 10px;border-radius:999px;font-size:13px}
    h1{font-size:44px;line-height:1.15;margin:14px 0 8px}
    .subtitle{font-size:18px;color:var(--muted);max-width:760px}
    .cta{display:flex;gap:12px;margin-top:20px;flex-wrap:wrap}
    .btn{display:inline-flex;gap:10px;align-items:center;padding:12px 16px;border-radius:14px;border:1px solid var(--border);background:var(--bg-elev);color:var(--txt);box-shadow:var(--shadow)}
    .btn.primary{background:linear-gradient(135deg,var(--acc),var(--acc-2));color:#04202a;border-color:transparent}
    .btn:hover{transform:translateY(-1px)}

    /* Sections */
    section{padding:50px 0;border-bottom:1px solid var(--border)}
    h2{font-size:28px;margin:0 0 18px}
    .grid{display:grid;gap:16px}
    @media(min-width:900px){.grid.cols-2{grid-template-columns:1.1fr .9fr}}

    /* Cards */
    .card{background:linear-gradient(180deg,var(--bg-elev),#0b214f);border:1px solid var(--border);border-radius:18px;padding:18px;box-shadow:var(--shadow)}
    .card h3{margin:0 0 8px}
    .muted{color:var(--muted)}

    /* Lists */
    .list{display:grid;gap:10px}
    .list li{background:rgba(255,255,255,.03);border:1px solid var(--border);border-radius:14px;padding:12px}

    /* Chips */
    .chips{display:flex;flex-wrap:wrap;gap:10px}
    .chip{background:var(--chip);border:1px solid var(--border);border-radius:999px;padding:8px 12px}

    /* Experience timeline */
    .timeline{position:relative;margin-left:4px}
    .timeline:before{content:"";position:absolute;left:12px;top:0;bottom:0;width:2px;background:linear-gradient(180deg,var(--acc-2),transparent)}
    .t-item{position:relative;margin:0 0 18px 0;padding-left:36px}
    .t-item:before{content:"";position:absolute;left:6px;top:8px;width:12px;height:12px;border-radius:50%;background:linear-gradient(135deg,var(--acc),var(--acc-2));box-shadow:0 0 0 4px rgba(45,212,191,.15)}

    /* Footer */
    footer{padding:28px 0;color:var(--muted);text-align:center}

    /* Print (A4 freundlicher One-Pager) */
    @media print{
      header,.cta,#top{display:none}
      body{background:#fff;color:#000}
      .card,.list li{border-color:#ddd;box-shadow:none}
      a{color:#000}
    }
  </style>
</head>
<body>
  <a id="top"></a>
  <header>
    <div class="container nav">
      <div class="brand"><span class="dot"></span> Oussama Guedri</div>
      <nav aria-label="Hauptnavigation">
        <ul>
          <li><a href="#profil">Profil</a></li>
          <li><a href="#skills">Kompetenzen</a></li>
          <li><a href="#erfahrung">Berufserfahrung</a></li>
          <li><a href="#ausbildung">Ausbildung</a></li>
          <li><a href="#sprachen">Sprachen</a></li>
          <li><a href="#kontakt">Kontakt</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container">
    <!-- Hero -->
    <section class="hero" id="profil">
      <span class="tag" title="Standort & Verfügbarkeit">📍 Hannover · Führerschein Klasse B</span>
      <h1>Oussama Guedri</h1>
      <p class="subtitle">Fertigungs‑, Qualitäts‑ & Produktionsingenieur (Maschinenbau). Fokus auf Simulation (FEM), Konstruktion (CATIA V5), Prozessoptimierung und Qualitätssicherung. Praktische Erfahrung bei BMW, Volkswagen, ILFA und Hanomag Lohnhärterei.</p>
      <div class="cta">
        <a class="btn primary" href="#kontakt">✉️ Kontakt</a>
        <a class="btn" href="https://oussamaguedri.github.io/Oussama-Profil/" target="_blank" rel="noopener">🌐 Portfolio‑Seite</a>
        <a class="btn" href="tel:+491637254664">📞 +49 163 7254664</a>
        <a class="btn" href="mailto:Oussamaguedri@gmail.com">📮 E‑Mail senden</a>
      </div>
    </section>

    <!-- Quick facts -->
    <section>
      <div class="grid cols-2">
        <div class="card">
          <h2>Steckbrief</h2>
          <p><strong>Adresse:</strong> Mendelssohnstraße 26 C, 30419 Hannover</p>
          <p><strong>Geburtsdatum:</strong> 22. Juli 1992</p>
          <p><strong>Verfügbarkeit:</strong> Berufseinstieg · Vollzeit</p>
        </div>
        <div class="card">
          <h2>Stärken</h2>
          <div class="chips">
            <span class="chip">FEM‑Simulation (Ringstauchversuch)</span>
            <span class="chip">CAD‑Konstruktion</span>
            <span class="chip">Prozessoptimierung</span>
            <span class="chip">Qualitätssicherung</span>
            <span class="chip">Datenanalyse (Python/Excel)</span>
          </div>
        </div>
      </div>
    </section>

    <!-- Skills -->
    <section id="skills">
      <h2>Kompetenzen</h2>
      <div class="chips">
        <span class="chip">Solid Edge</span>
        <span class="chip">CATIA V5</span>
        <span class="chip">Simufact</span>
        <span class="chip">ANSYS</span>
        <span class="chip">SAP</span>
        <span class="chip">C++</span>
        <span class="chip">Matlab</span>
        <span class="chip">Java</span>
        <span class="chip">Python</span>
        <span class="chip">MS Excel</span>
        <span class="chip">MS PowerPoint</span>
      </div>
    </section>

    <!-- Experience -->
    <section id="erfahrung">
      <h2>Berufserfahrung</h2>
      <div class="timeline">
        <div class="t-item">
          <div class="card">
            <h3>Bachelorarbeit – IPH Hannover <span class="muted">(02/2024 – 07/2024)</span></h3>
            <p class="muted">Einsatzmöglichkeiten & Grenzen bei der Prozessauslegung am Beispiel des Ringstauchversuchs</p>
            <ul class="list">
              <li>Durchführung von FEM‑Simulationen zur Analyse des Materialverhaltens</li>
              <li>Vergleich manueller vs. automatisierter Simulationen; Fehlersuche & Optimierung</li>
              <li>Parameterstudien & Ableitung von Empfehlungen für die Prozessgestaltung</li>
            </ul>
          </div>
        </div>
        <div class="t-item">
          <div class="card">
            <h3>Praxissemester Konstruktion E‑Getriebe – BMW AG, München <span class="muted">(06/2023 – 11/2023)</span></h3>
            <ul class="list">
              <li>Allgemeine Konstruktionsunterstützung in CATIA V5; Zeichnungserstellung nach Werksnorm</li>
              <li>Zusammenbauuntersuchungen & Toleranzbetrachtungen im Antriebssystem</li>
              <li>Werksbesuch Dingolfing: Analyse Montage‑ & Fertigungsprozesse</li>
              <li>Überprüfung von Fertigungstoleranzen & Prozessfähigkeiten in der Radsatzproduktion</li>
            </ul>
          </div>
        </div>
        <div class="t-item">
          <div class="card">
            <h3>Studentische Hilfskraft (Produktion) – Volkswagen AG, Stöcken <span class="muted">(03/2018 – 12/2020)</span></h3>
          </div>
        </div>
        <div class="t-item">
          <div class="card">
            <h3>Freiwilliges Praktikum – ILFA GmbH, Hannover <span class="muted">(07/2019 – 09/2019)</span></h3>
            <ul class="list">
              <li>Unterstützung in der Leiterplattenfertigung & Qualitätskontrolle</li>
              <li>Prototypenfertigung, Maschinenbedienung & Wartung, Prozessdokumentation</li>
            </ul>
          </div>
        </div>
        <div class="t-item">
          <div class="card">
            <h3>Grundpraktikum – Hanomag Lohnhärterei Gruppe, Hannover <span class="muted">(02/2017 – 03/2017)</span></h3>
            <ul class="list">
              <li>Steuerung/Regelung von Härteöfen, Überwachung von Temperaturprofilen</li>
              <li>Stichprobenprüfungen, Kalibrierung & Wartung, QS‑Dokumentation</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Education -->
    <section id="ausbildung">
      <h2>Ausbildung</h2>
      <div class="grid cols-2">
        <div class="card">
          <h3>Master of Engineering – Präzisionsmaschinenbau</h3>
          <p class="muted">HAWK Göttingen · 10/2024 – 08/2025</p>
        </div>
        <div class="card">
          <h3>Bachelor of Engineering – Ingenieurwissenschaften (Maschinenbau)</h3>
          <p class="muted">HAWK Göttingen · 2018 – 07/2024</p>
        </div>
        <div class="card">
          <h3>DSH – Deutsche Sprachprüfung für den Hochschulzugang</h3>
          <p class="muted">F+U Academy of Languages, Heidelberg · 2016 – 2018</p>
        </div>
        <div class="card">
          <h3>Höheres Techniker Diplom – Maschinenbau</h3>
          <p class="muted">ISET Tunis · 2012 – 2015</p>
        </div>
        <div class="card">
          <h3>Abitur – Baccalauréat Sciences Expérimentales</h3>
          <p class="muted">Tunis · 2007 – 2011</p>
        </div>
      </div>
    </section>

    <!-- Languages & Interests -->
    <section id="sprachen">
      <div class="grid cols-2">
        <div class="card">
          <h2>Sprachen</h2>
          <ul class="list">
            <li>Deutsch – C1 (Fachkundig)</li>
            <li>Arabisch – C2 (Fließend)</li>
            <li>Französisch – C2 (Fließend)</li>
            <li>Englisch – B2 (Kompetent)</li>
            <li>Spanisch – A2 (Grundlagen)</li>
          </ul>
        </div>
        <div class="card">
          <h2>Hobbys & Interessen</h2>
          <div class="chips">
            <span class="chip">Reisen</span>
            <span class="chip">Sport</span>
            <span class="chip">Schwimmen</span>
            <span class="chip">Radfahren</span>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="kontakt">
      <h2>Kontakt</h2>
      <div class="grid cols-2">
        <div class="card">
          <p><strong>Adresse:</strong> Mendelssohnstraße 26 C, 30419 Hannover</p>
          <p><strong>Telefon:</strong> <a href="tel:+491637254664">+49 163 7254664</a></p>
          <p><strong>E‑Mail:</strong> <a href="mailto:Oussamaguedri@gmail.com">Oussamaguedri@gmail.com</a></p>
          <p class="muted">Auf Wunsch sende ich gern vollständige Unterlagen (Zeugnisse, Referenzen) als PDF.</p>
        </div>
        <div class="card">
          <h3>Schnellbewerbung</h3>
          <p class="muted">Klicken Sie auf eine Option unten, um direkt Kontakt aufzunehmen:</p>
          <div class="cta">
            <a class="btn primary" href="mailto:Oussamaguedri@gmail.com?subject=Anfrage%20%7C%20Oussama%20Guedri&body=Hallo%20Herr%20Guedri,%0A%0Awir%20interessieren%20uns%20f%C3%BCr%20Ihr%20Profil...">E‑Mail senden</a>
            <a class="btn" href="https://wa.me/491637254664" target="_blank" rel="noopener">WhatsApp</a>
            <a class="btn" href="#top">Nach oben ↑</a>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">© <span id="year"></span> Oussama Guedri · One‑Pager Lebenslauf</div>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
