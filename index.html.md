<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>PostPilot Aue – Social Media & KI Service</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#111;
      --panel:#1c1c1c;
      --accent:#f5b400;
      --text:#fff;
      --muted:#cfcfcf;
      --shadow: 0 0 20px rgba(245,180,0,0.18);
      --radius: 14px;
      --max: 1100px;
    }

    *{ box-sizing:border-box; }

    body{
      margin:0;
      font-family:'Poppins',sans-serif;
      background:var(--bg);
      color:var(--text);
    }

    .container{
      width:min(100%, var(--max));
      margin:0 auto;
      padding:0 18px;
    }

    .hero{
      background:
        linear-gradient(rgba(0,0,0,0.78), rgba(0,0,0,0.86)),
        url("https://images.unsplash.com/photo-1555992336-03a23c3b0e0b?auto=format&fit=crop&w=2000&q=80");
      background-size:cover;
      background-position:center;
      padding:110px 0 90px;
      text-align:center;
      border-bottom: 1px solid rgba(255,255,255,0.06);
    }

    .hero h1{
      margin:0 0 10px;
      font-size:clamp(34px, 5vw, 54px);
      color:var(--accent);
      letter-spacing:.5px;
    }

    .hero p{
      margin:6px 0;
      color:var(--muted);
      font-size:clamp(15px, 2.2vw, 18px);
    }

    .section{
      padding:62px 0;
      text-align:center;
    }

    .section h2{
      margin:0 0 26px;
      font-size:clamp(22px, 3.2vw, 30px);
    }

    .gallery{
      display:grid;
      grid-template-columns:repeat(auto-fit, minmax(240px, 1fr));
      gap:18px;
      margin-top:18px;
    }

    .post{
      background:var(--panel);
      border-radius:var(--radius);
      overflow:hidden;
      box-shadow:var(--shadow);
      text-align:left;
      border: 1px solid rgba(255,255,255,0.06);
    }

    .post img{
      width:100%;
      height:170px;
      object-fit:cover;
      display:block;
    }

    .post .cap{
      padding:14px 14px 16px;
      color:var(--muted);
      font-size:14px;
      line-height:1.35;
    }

    .pricing{
      display:flex;
      flex-wrap:wrap;
      justify-content:center;
      gap:18px;
      margin-top:18px;
    }

    .card{
      background:var(--panel);
      padding:22px;
      width:min(340px, 100%);
      border-radius:var(--radius);
      box-shadow:var(--shadow);
      text-align:left;
      border: 1px solid rgba(255,255,255,0.06);
    }

    .card h3{
      margin:0 0 8px;
      color:var(--accent);
      font-size:20px;
    }

    .price{
      font-size:28px;
      margin:10px 0 12px;
      color:var(--accent);
      font-weight:700;
    }

    .card p{
      margin:0 0 16px;
      color:var(--muted);
      line-height:1.6;
      font-size:14px;
    }

    .pay-btn{
      background:var(--accent);
      color:#000;
      padding:12px 16px;
      text-decoration:none;
      border-radius:10px;
      font-weight:700;
      display:inline-block;
      transition:transform .12s ease, filter .12s ease;
    }
    .pay-btn:hover{
      transform:translateY(-1px);
      filter:brightness(1.05);
    }

    footer{
      padding:26px 0;
      text-align:center;
      background:#000;
      color:var(--muted);
      font-size:14px;
      border-top:1px solid rgba(255,255,255,0.06);
    }

    .small{
      font-size:12px;
      opacity:.85;
      margin-top:8px;
      text-align:center;
    }
  </style>
</head>

<body>
  <header class="hero">
    <div class="container">
      <h1>PostPilot Aue</h1>
      <p>Social Media & KI-Service für Restaurants</p>
      <p>Mehr Gäste • Mehr Reichweite • Weniger Aufwand</p>
    </div>
  </header>

  <main>
    <section class="section">
      <div class="container">
        <h2>Beispiel Woche</h2>

        <div class="gallery">
          <article class="post">
            <img src="https://images.unsplash.com/photo-1550547660-d9450f859349?auto=format&fit=crop&w=900&q=80" alt="Burger" />
            <div class="cap">Montag – Guten Appetit!</div>
          </article>

          <article class="post">
            <img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?auto=format&fit=crop&w=900&q=80" alt="Burger Special" />
            <div class="cap">Dienstag – Heute Special!</div>
          </article>

          <article class="post">
            <img src="https://images.unsplash.com/photo-1604908177522-040d8a97b6c2?auto=format&fit=crop&w=900&q=80" alt="Food Highlight" />
            <div class="cap">Mittwoch – Wochenhighlight</div>
          </article>

          <article class="post">
            <img src="https://images.unsplash.com/photo-1529042410759-befb1204b468?auto=format&fit=crop&w=900&q=80" alt="Kundenliebe" />
            <div class="cap">Donnerstag – Kundenliebe</div>
          </article>

          <article class="post">
            <img src="https://images.unsplash.com/photo-1540189549336-e6e99c3679fe?auto=format&fit=crop&w=900&q=80" alt="Burger Night" />
            <div class="cap">Freitag – Burger Night</div>
          </article>

          <article class="post">
            <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=900&q=80" alt="Frisch & Lecker" />
            <div class="cap">Samstag – Frisch & Lecker</div>
          </article>

          <article class="post">
            <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&w=900&q=80" alt="Restaurant Genuss" />
            <div class="cap">Sonntag – Genussmoment</div>
          </article>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="container">
        <h2>Unsere Pakete</h2>

        <div class="pricing">
          <div class="card">
            <h3>Basic</h3>
            <div class="price">79€ / Monat</div>
            <p>3 Posts pro Woche<br>Hashtags & Texte<br>KI Content</p>
            <a class="pay-btn" href="https://www.paypal.com/paypalme/denesbaer55/79" target="_blank" rel="noopener">
              Jetzt bezahlen
            </a>
          </div>

          <div class="card">
            <h3>Standard</h3>
            <div class="price">149€ / Monat</div>
            <p>5 Posts pro Woche<br>Bewertungs-Service<br>Wochenplan</p>
            <a class="pay-btn" href="https://www.paypal.com/paypalme/denesbaer55/149" target="_blank" rel="noopener">
              Jetzt bezahlen
            </a>
          </div>

          <div class="card">
            <h3>Premium</h3>
            <div class="price">249€ / Monat</div>
            <p>Tägliche Posts<br>Full Service<br>Antworten auf Bewertungen</p>
            <a class="pay-btn" href="https://www.paypal.com/paypalme/denesbaer55/249" target="_blank" rel="noopener">
              Jetzt bezahlen
            </a>
          </div>
        </div>

        <div class="small">Hinweis: Buttons öffnen PayPal in einem neuen Tab.</div>
      </div>
    </section>
  </main>

  <footer>
    Denes Baer – 09366 Stollberg<br>
    E-Mail: denesbaer55@gmail.com
  </footer>
</body>
</html>