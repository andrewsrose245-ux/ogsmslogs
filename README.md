<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>ØGSMSLOGS — Digital Services Marketplace</title>
<style>
:root{--blue:#1769e8;--blue2:#0d4fbd;--ink:#14233b;--muted:#65748b;--bg:#f4f7fc;--line:#e5ebf4;--white:#fff;--green:#168653}
*{box-sizing:border-box}body{margin:0;font-family:Inter,ui-sans-serif,system-ui,-apple-system,Segoe UI,Arial;color:var(--ink);background:var(--bg)}
header{background:#fff;border-bottom:1px solid var(--line);position:sticky;top:0;z-index:5}.nav{max-width:1180px;margin:auto;padding:15px 22px;display:flex;align-items:center;justify-content:space-between;gap:16px}
.brand{font-weight:900;font-size:22px;letter-spacing:-.8px;color:var(--blue)}.brand small{display:block;font-size:9px;letter-spacing:2px;color:var(--muted);font-weight:700}
nav{display:flex;gap:20px;align-items:center}nav a{font-size:13px;color:#43536c;text-decoration:none;font-weight:650}
.btn{border:0;border-radius:10px;padding:11px 16px;font-weight:750;cursor:pointer;background:var(--blue);color:white}.btn:hover{background:var(--blue2)}.btn.light{background:#edf4ff;color:var(--blue)}
.wrap{max-width:1180px;margin:auto;padding:26px 22px}.hero{background:linear-gradient(120deg,#0d4fbd,#2786f5);color:white;border-radius:22px;padding:42px;display:grid;grid-template-columns:1.5fr 1fr;gap:25px;overflow:hidden}
.hero h1{font-size:clamp(30px,4vw,48px);line-height:1.05;margin:12px 0}.hero p{color:#e2eeff;max-width:560px;line-height:1.65}.eyebrow{font-size:11px;letter-spacing:1.8px;font-weight:850;text-transform:uppercase;color:#cfe1ff}
.hero-card{align-self:center;background:#fff;color:var(--ink);border-radius:17px;padding:20px;box-shadow:0 20px 50px #073d8a55}.hero-card .big{font-size:30px;font-weight:900;color:var(--blue)}.hero-card p{color:var(--muted);font-size:12px;margin:6px 0}
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-top:18px}.stat{background:#f6f9ff;border:1px solid var(--line);border-radius:12px;padding:12px}.stat b{display:block;font-size:16px}.stat span{font-size:11px;color:var(--muted)}
.section-head{display:flex;align-items:end;justify-content:space-between;margin:32px 0 15px}.section-head h2{margin:0;font-size:22px}.section-head p{margin:5px 0 0;color:var(--muted);font-size:13px}
.grid{display:grid;grid-template-columns:repeat(4,1fr);gap:14px}.tile,.panel{background:#fff;border:1px solid var(--line);border-radius:16px;padding:18px}.tile{cursor:pointer;transition:.15s}.tile:hover{transform:translateY(-2px);border-color:#9fc3ff;box-shadow:0 10px 25px #183a6810}.tile .emoji{font-size:25px}.tile h3{font-size:15px;margin:12px 0 5px}.tile p{font-size:12px;color:var(--muted);margin:0;line-height:1.5}
.content{display:grid;grid-template-columns:1.4fr .8fr;gap:16px}.service{display:flex;align-items:center;justify-content:space-between;padding:14px 0;border-bottom:1px solid var(--line);gap:12px}.service:last-child{border:0}.service b{font-size:13px}.service small{display:block;color:var(--muted);font-size:11px;margin-top:4px}.price{font-weight:850;color:var(--blue);white-space:nowrap}
label{font-size:12px;font-weight:750;display:block;margin:12px 0 6px}select,input{width:100%;border:1px solid #d9e2ef;border-radius:10px;padding:12px;background:white;color:var(--ink);font:inherit}
.notice{background:#fff8e8;border:1px solid #f2dfb5;color:#795519;padding:12px;border-radius:12px;font-size:12px;line-height:1.5;margin-top:14px}
footer{padding:30px 22px;text-align:center;color:var(--muted);font-size:12px}
.modal{display:none;position:fixed;inset:0;background:#10213c88;z-index:10;align-items:center;justify-content:center;padding:18px}.modal.show{display:flex}.dialog{background:#fff;border-radius:18px;padding:22px;max-width:440px;width:100%;box-shadow:0 25px 80px #0003}.dialog h3{margin-top:0}.close{float:right;border:0;background:#edf2f8;border-radius:8px;padding:6px 10px;cursor:pointer}
@media(max-width:800px){nav{display:none}.hero{grid-template-columns:1fr;padding:28px}.grid{grid-template-columns:repeat(2,1fr)}.content{grid-template-columns:1fr}}
@media(max-width:460px){.wrap{padding:18px 14px}.grid{grid-template-columns:1fr 1fr;gap:9px}.tile{padding:13px}.stats{gap:7px}.stat{padding:9px}.stat b{font-size:13px}}
</style>
</head>
<body>
<header><div class="nav"><div class="brand">ØGSMSLOGS<small>DIGITAL SERVICES MARKETPLACE</small></div><nav><a href="#services">Services</a><a href="#numbers">Business numbers</a><a href="#how">How it works</a><a href="#support">Support</a></nav><button class="btn light" onclick="openModal('account')">Sign in</button></div></header>
<main class="wrap">
<section class="hero">
<div><div class="eyebrow">Your digital services hub</div><h1>Grow your digital presence. <span style="color:#cfe1ff">One marketplace.</span></h1><p>Explore digital services, manage orders and keep track of your purchases from one simple dashboard.</p><button class="btn" style="background:#fff;color:#1257c4" onclick="document.querySelector('#services').scrollIntoView({behavior:'smooth'})">Explore services</button></div>
<div class="hero-card"><div class="eyebrow" style="color:#6983a7">CUSTOMER WALLET</div><div class="big">₦0.00</div><p>Demo balance · Live payments are not connected</p><div class="stats"><div class="stat"><b>0</b><span>Orders</span></div><div class="stat"><b>0</b><span>Pending</span></div><div class="stat"><b>24/7</b><span>Portal</span></div></div></div>
</section>
<div class="section-head" id="services"><div><h2>Browse services</h2><p>Choose a category to explore the marketplace.</p></div></div>
<section class="grid">
<div class="tile" onclick="showCategory('Social media services')"><div class="emoji">📣</div><h3>Social media</h3><p>Services for supported social platforms.</p></div>
<div class="tile" onclick="showCategory('VPN services')"><div class="emoji">🛡️</div><h3>VPN services</h3><p>Privacy and secure-connectivity plans.</p></div>
<div class="tile" onclick="document.querySelector('#numbers').scrollIntoView({behavior:'smooth'})"><div class="emoji">🌍</div><h3>Business numbers</h3><p>Legitimate numbers for supported business verification.</p></div>
<div class="tile" onclick="showCategory('Digital tools')"><div class="emoji">✉️</div><h3>Digital tools</h3><p>Productivity and communication tools.</p></div>
</section>
<div class="section-head"><div><h2>Popular services</h2><p>Sample catalogue items for the first design preview.</p></div></div>
<section class="content">
<div class="panel">
<div class="service"><div><b>Instagram account support</b><small>Sample listing · provider connection required</small></div><span class="price">From ₦—</span></div>
<div class="service"><div><b>YouTube channel support</b><small>Sample listing · provider connection required</small></div><span class="price">From ₦—</span></div>
<div class="service"><div><b>TikTok account support</b><small>Sample listing · provider connection required</small></div><span class="price">From ₦—</span></div>
<div class="service"><div><b>VPN subscription</b><small>Sample listing · plan details to be added</small></div><span class="price">From ₦—</span></div>
</div>
<aside class="panel" id="numbers"><h3 style="margin-top:0">Business verification numbers</h3><p style="font-size:12px;color:var(--muted);line-height:1.6">Select a country and supported business use case. Live inventory will appear after an approved provider is connected.</p>
<label for="country">Choose country</label><select id="country"><option>Nigeria</option><option>United States</option><option>United Kingdom</option><option>Canada</option><option>Germany</option><option>France</option><option>India</option><option>South Africa</option></select>
<label for="usecase">Intended use</label><select id="usecase"><option>Business phone verification</option><option>Customer support line</option><option>Account recovery where permitted</option></select>
<button class="btn" style="width:100%;margin-top:14px" onclick="openModal('numbers')">Check availability</button>
<div class="notice">Numbers and SMS codes must be supplied by authorized providers and used only where the receiving platform permits them. This preview does not provide disposable numbers or bypass identity/security checks.</div>
</aside>
</section>
<div class="section-head" id="how"><div><h2>How it works</h2><p>A simple flow from browsing to order tracking.</p></div></div>
<section class="grid">
<div class="tile"><div class="emoji">①</div><h3>Create an account</h3><p>Register securely and access your customer dashboard.</p></div>
<div class="tile"><div class="emoji">②</div><h3>Choose a service</h3><p>Review service details, requirements and pricing.</p></div>
<div class="tile"><div class="emoji">③</div><h3>Pay securely</h3><p>Use an enabled payment provider in Nigerian naira.</p></div>
<div class="tile"><div class="emoji">④</div><h3>Track your order</h3><p>See status updates and contact support when needed.</p></div>
</section>
<div class="section-head" id="support"><div><h2>Need help?</h2><p>Customer support details can be added before launch.</p></div></div>
<section class="panel"><b>ØGSMSLOGS Support</b><p style="font-size:13px;color:var(--muted)">Add your verified WhatsApp number 09131285556, support email ogwirewiremonie6@gmail.com and business hours here.247 active </p></section>
</main>
<footer>© 2026 ØGSMSLOGS. All rights reserved. · Preview only — payments, accounts, inventory and provider APIs are not yet connected.</footer>
<div class="modal" id="modal" onclick="if(event.target===this)closeModal()"><div class="dialog"><button class="close" onclick="closeModal()">✕</button><h3 id="modalTitle">Coming soon</h3><p id="modalText" style="color:#65748b;font-size:13px;line-height:1.6">This is a design preview. The secure backend and live providers will be configured before launch.</p><button class="btn" onclick="closeModal()">Got it</button></div></div>
<script>
function openModal(kind){const t=document.getElementById('modalTitle'),p=document.getElementById('modalText');if(kind==='numbers'){t.textContent='Availability check';p.textContent='Country and use case selected. Live number inventory is not connected yet. We will add an authorized provider after reviewing its API and permitted use.'}else{t.textContent='Customer account';p.textContent='Sign-up and sign-in will be enabled after the secure customer database and authentication service are configured.'}document.getElementById('modal').classList.add('show')}
function closeModal(){document.getElementById('modal').classList.remove('show')}
function showCategory(name){document.getElementById('modalTitle').textContent=name;document.getElementById('modalText').textContent='This category is part of the planned catalogue. Real services, prices and fulfilment rules will be loaded from approved providers.';document.getElementById('modal').classList.add('show')}
</script>
</body></html>