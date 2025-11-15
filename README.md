# 47th-landlord-

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>47th Landlord Real Estate — Imikan James</title>
  <meta name="description" content="47th Landlord Real Estate — Luxury properties and investments in Dubai, Miami & London. Contact Imikan James on WhatsApp." />
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="header">
    <div class="wrap">
      <div class="brand">
        <div class="logo">47</div>
        <div>
          <div class="brand-title">47th Landlord</div>
          <div class="brand-sub">Real Estate</div>
        </div>
      </div>
      <nav class="nav">
        <a href="#home">Home</a>
        <a href="#markets">Markets</a>
        <a href="#listings">Listings</a>
        <a href="#about">About</a>
        <a href="#contact" class="cta">Contact</a>
      </nav>
    </div>
  </header>

  <main id="home">
    <section class="hero">
      <div class="wrap hero-grid">
        <div class="hero-left">
          <h1>Premium property advisory</h1>
          <p class="sub">Dubai • Miami • London</p>
          <p class="lead">Luxury acquisitions, off-market sourcing, investor advisory and seller campaigns — fast responses on WhatsApp.</p>
          <div class="actions">
            <a class="btn primary" href="https://wa.me/07070274775">Chat on WhatsApp</a>
            <a class="btn ghost" href="#listings">View Listings</a>
          </div>
          <ul class="features">
            <li>Off-market & exclusive opportunities</li>
            <li>Local coordination & legal support</li>
            <li>Investor due diligence & reporting</li>
          </ul>
        </div>
        <div class="hero-right" aria-hidden="true"></div>
      </div>
    </section>

    <section id="markets" class="section">
      <div class="wrap">
        <h2>Markets</h2>
        <div class="grid markets">
          <article class="card">
            <h3>Dubai</h3>
            <p>Waterfront, off-plan and luxury investment opportunities.</p>
            <a class="link" href="https://wa.me/07070274775?text=Hi%20Imikan%2C%20I%27m%20interested%20in%20Dubai%20listings">Message →</a>
          </article>
          <article class="card">
            <h3>Miami</h3>
            <p>Beachfront condos and high-yield investor homes.</p>
            <a class="link" href="https://wa.me/07070274775?text=Hi%20Imikan%2C%20I%27m%20interested%20in%20Miami%20listings">Message →</a>
          </article>
          <article class="card">
            <h3>London</h3>
            <p>Prime central residences and long-term value assets.</p>
            <a class="link" href="https://wa.me/07070274775?text=Hi%20Imikan%2C%20I%27m%20interested%20in%20London%20listings">Message →</a>
          </article>
        </div>
      </div>
    </section>

    <section id="listings" class="section dark">
      <div class="wrap">
        <h2>Featured Listings</h2>
        <div class="grid listings">
          <article class="property">
            <img src="https://images.unsplash.com/photo-1560448204-e02f11c3d0e2?auto=format&fit=crop&w=1200&q=60" alt="Skyline Penthouse Dubai">
            <div class="p-body">
              <h4>Skyline Penthouse — Dubai</h4>
              <div class="meta">4 bd • 5 ba</div>
              <div class="price">AED 12,500,000</div>
              <div class="p-actions">
                <button onclick="openWhatsApp('I am interested in the Skyline Penthouse — Dubai')">WhatsApp</button>
                <button class="outline" onclick="saveShortlist(1)">Save</button>
              </div>
            </div>
          </article>

          <article class="property">
            <img src="https://images.unsplash.com/photo-1505691723518-36a1fb0b1e9e?auto=format&fit=crop&w=1200&q=60" alt="Oceanfront Condo Miami">
            <div class="p-body">
              <h4>Oceanfront Condo — Miami</h4>
              <div class="meta">3 bd • 3 ba</div>
              <div class="price">$1,950,000</div>
              <div class="p-actions">
                <button onclick="openWhatsApp('I am interested in the Oceanfront Condo — Miami')">WhatsApp</button>
                <button class="outline" onclick="saveShortlist(2)">Save</button>
              </div>
            </div>
          </article>

          <article class="property">
            <img src="https://images.unsplash.com/photo-1572120360610-d971b9c0f8f9?auto=format&fit=crop&w=1200&q=60" alt="Classic Townhouse London">
            <div class="p-body">
              <h4>Classic Townhouse — London</h4>
              <div class="meta">2 bd • 2 ba</div>
              <div class="price">£1,200,000</div>
              <div class="p-actions">
                <button onclick="openWhatsApp('I am interested in the Classic Townhouse — London')">WhatsApp</button>
                <button class="outline" onclick="saveShortlist(3)">Save</button>
              </div>
            </div>
          </ar
        :root{
  --bg:#080808;
  --card:#0f0f0f;
  --gold:#c9a34a;
  --muted:#bfb6a1;
  --accent:#e9d9b3;
  --glass: rgba(255,255,255,0.03);
  --radius:12px;
  --max:1100px;
  font-family: "Montserrat", system-ui, -apple-system, "Segoe UI", Roboto, Arial, sans-serif;
}

*{box-sizing:border-box}
html,body{height:100%;margin:0;background:var(--bg);color:var(--muted);-webkit-font-smoothing:antialiased}
.wrap{max-width:var(--max);margin:0 auto;padding:0 18px}
.header{position:fixed;top:0;left:0;right:0;background:linear-gradient(180deg, rgba(0,0,0,0.6), transparent);padding:14px 0;z-index:60}
.brand{display:flex;align-items:center;gap:12px}
.logo{width:46px;height:46px;border-radius:10px;background:linear-gradient(135deg,var(--gold),#b38f39);display:flex;align-items:center;justify-content:center;color:#080808;font-weight:700}
.brand-title{font-weight:700;color:#fff}
.brand-sub{font-size:12px;color:var(--muted)}
.nav{display:flex;gap:18px;align-items:center}
.nav a{color:var(--muted);font-weight:600}
.cta{padding:8px 12px;border-radius:10px;border:1px solid rgba(201,163,74,0.12);color:var(--gold)}

.hero{padding:90px 0 40px}
.hero-grid{display:grid;grid-template-columns:1fr 420px;gap:36px;align-items:center}
.hero-left h1{font-size:34px;color:var(--accent);margin:0}
.sub{color:var(--muted);margin-top:8px}
.lead{margin-top:12px;color:#d6cfa8}
.actions{margin-top:18px;display:flex;gap:12px}
.btn{display:inline-block;padding:10px 16px;border-radius:10px;font-weight:700;text-decoration:none;border:none;cursor:pointer}
.primary{background:linear-gradient(90deg,var(--gold),#e1cb79);color:#080808}
.ghost{background:transparent;border:1px solid rgba(255,255,255,0.04);color:var(--muted)}
.features{display:flex;gap:14px;color:var(--muted);margin-top:18px;list-style:none;padding:0}

.section{padding:60px 0}
.section.dark{background:var(--card)}
.grid{display:grid;gap:20px}
.markets{grid-template-columns:repeat(auto-fit,minmax(220px,1fr))}
.card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:18px;border-radius:12px;border:1px solid var(--glass)}
.card h3{color:var(--gold);margin:0 0 10px}

.listings{grid-template-columns:repeat(auto-fit,minmax(260px,1fr))}
.property{background:var(--card);border-radius:12px;overflow:hidden;border:1px solid var(--glass)}
.property img{width:100%;height:170px;object-fit:cover;display:block}
.p-body{padding:12px}
.p-body h4{color:var(--accent);margin:0}
.meta{color:var(--muted);font-size:13px;margin-top:6px}
.price{color:var(--gold);font-weight:700;margin-top:8px}
.p-actions{display:flex;gap:10px;margin-top:12px}
.p-actions button{padding:8px 12px;border-radius:8px;border:none;cursor:pointer}
.p-actions .outline{background:transparent;border:1px solid rgba(255,255,255,0.04);color:var(--muted)}

.about-grid{display:grid;grid-template-columns:1fr 380px;gap:28px}
.contact-card{padding:18px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border:1px solid rgba(255,255,255,0.03)}

.contact-wrap{display:flex;justify-content:center}
.contact-form{max-width:640px;display:grid;gap:12px}
.contact-form input, .contact-form textarea{padding:12px;border-radius:10px;border:1px solid var(--glass);background:transparent;color:var(--muted)}

.footer{padding:32px 0;text-align:center;color:var(--muted);border-top:1px solid var(--glass)}

.whatsapp-fab{position:fixed;right:18px;bottom:18px;background:var(--gold);color:#080808;padding:12px 18px;border-radius:999px;font-weight:700;text-decoration:none}
// small utilities
document.getElementById('year').textContent = new Date().getFullYear();

function openWhatsApp(message){
  const text = encodeURIComponent(message || "Hello Imikan, I'm interested in a listing.");
  const url = `https://wa.me/07070274775?text=${text}`;
  window.open(url, '_blank');
}

function submitContact(e){
  e.preventDefault();
  const name = document.getElementById('name').value.trim();
  const email = document.getElementById('email').value.trim();
  const message = document.getElementById('message').value.trim();
  if(!name || !message){ alert('Please enter name and message.'); return; }
  const text = encodeURIComponent(`Hi Imikan, I'm ${name}. ${message}${email ? ' (Email: ' + email + ')' : ''}`);
  window.open(`https://wa.me/07070274775?text=${text}`, '_blank');
}

function saveShortlist(id){
  alert('Saved to shortlist (id:' + id + '). Imikan will follow up.');
}

function saveContact(){
  alert('Contact saved locally. Imikan will follow up via WhatsApp.');
}
@media(max-width:900px){
  .hero-grid{grid-template-columns:1fr;gap:18px}
  .about-grid{grid-template-columns:1fr}
  .wrap{padding:0 14px}
  .nav{display:none}
}
