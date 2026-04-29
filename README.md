<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hành Trình Việt Đức – Hoff | Tiếng Đức & Du học nghề CHLB Đức</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700;900&family=Be+Vietnam+Pro:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }
  :root {
    --bg:#2c3550;--deep:#253048;--card:#344067;--card2:#3a4a78;
    --border:rgba(255,255,255,0.12);--gold:#f0b429;--gold-lt:#ffd060;
    --gold-dim:rgba(240,180,41,0.14);--white:#f0f4ff;--muted:rgba(210,220,255,0.65);
    --green:#2d6a4f;--green2:#356050;--flag-r:#DD0000;--flag-y:#FFCE00;
  }
  html{scroll-behavior:smooth;}
  body{background:var(--bg);color:var(--white);font-family:'Be Vietnam Pro',sans-serif;font-weight:300;overflow-x:hidden;}
  nav{position:fixed;top:0;left:0;right:0;z-index:200;display:flex;justify-content:space-between;align-items:center;padding:1.6rem 5vw;background:transparent;transition:padding 0.4s,background 0.4s,box-shadow 0.4s;}
  nav.scrolled{padding:0.85rem 5vw;background:rgba(36,42,68,0.96);backdrop-filter:blur(18px);box-shadow:0 2px 24px rgba(0,0,0,0.25);border-bottom:1px solid var(--border);}
  .logo{font-family:'Playfair Display',serif;font-weight:900;font-size:1.25rem;letter-spacing:0.02em;color:var(--white);transition:font-size 0.4s;}
  nav.scrolled .logo{font-size:1.05rem;}
  .logo span{color:var(--gold);}
  .nav-links{display:flex;gap:2rem;list-style:none;}
  .nav-links a{color:var(--muted);text-decoration:none;font-size:0.8rem;font-weight:500;letter-spacing:0.08em;text-transform:uppercase;transition:color 0.3s;}
  .nav-links a:hover{color:var(--gold);}
  .nav-cta{background:var(--gold);color:#1a1a00;padding:0.55rem 1.3rem;border-radius:3px;font-size:0.78rem;font-weight:700;letter-spacing:0.06em;text-transform:uppercase;cursor:pointer;border:none;transition:background 0.3s,transform 0.2s;white-space:nowrap;}
  .nav-cta:hover{background:var(--gold-lt);transform:translateY(-1px);}
  .hamburger{display:none;flex-direction:column;gap:5px;cursor:pointer;padding:4px;background:none;border:none;}
  .hamburger span{display:block;width:24px;height:2px;background:var(--white);border-radius:2px;transition:all 0.3s;}
  .mobile-menu{display:none;position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(36,42,68,0.98);backdrop-filter:blur(20px);z-index:300;flex-direction:column;align-items:center;justify-content:center;gap:2rem;}
  .mobile-menu.open{display:flex;}
  .mobile-menu a{color:var(--white);text-decoration:none;font-family:'Playfair Display',serif;font-size:1.8rem;font-weight:700;transition:color 0.3s;}
  .mobile-menu a:hover{color:var(--gold);}
  .mobile-menu-close{position:absolute;top:1.5rem;right:5vw;background:none;border:none;color:var(--white);font-size:2rem;cursor:pointer;line-height:1;}
  .mobile-cta-btn{background:var(--gold);color:#1a1a00;padding:0.85rem 2.5rem;border-radius:3px;font-weight:700;font-size:0.9rem;letter-spacing:0.06em;text-transform:uppercase;cursor:pointer;border:none;margin-top:0.5rem;}
  .hero{min-height:100vh;display:grid;grid-template-columns:1fr 1fr;align-items:center;gap:3rem;padding:7rem 5vw 4rem;position:relative;overflow:hidden;background:linear-gradient(135deg,#2c3550 0%,#1e2a45 60%,#253048 100%);}
  .hero::before{content:'';position:absolute;inset:0;background:radial-gradient(ellipse 55% 65% at 85% 45%,rgba(240,180,41,0.09) 0%,transparent 70%),radial-gradient(ellipse 35% 45% at 5% 85%,rgba(221,0,0,0.07) 0%,transparent 60%);}
  .flag-bar{position:absolute;right:0;top:0;bottom:0;width:5px;display:flex;flex-direction:column;}
  .flag-bar span{flex:1;}
  .flag-bar span:nth-child(1){background:#222;}
  .flag-bar span:nth-child(2){background:var(--flag-r);}
  .flag-bar span:nth-child(3){background:var(--flag-y);}
  .hero-text{position:relative;z-index:2;animation:fadeUp 0.9s ease both;}
  .eyebrow{display:inline-flex;align-items:center;gap:0.6rem;color:var(--gold);font-size:0.73rem;font-weight:600;letter-spacing:0.18em;text-transform:uppercase;margin-bottom:1.6rem;}
  .eyebrow::before{content:'';width:28px;height:1px;background:var(--gold);}
  h1{font-family:'Playfair Display',serif;font-size:clamp(2.6rem,4.8vw,4.5rem);font-weight:900;line-height:1.08;margin-bottom:1.3rem;}
  h1 em{color:var(--gold);font-style:normal;}
  .hero-sub{color:var(--muted);font-size:1rem;line-height:1.75;max-width:460px;margin-bottom:2.4rem;}
  /* FIX 1: Loại bỏ text-shadow phát sáng */
  .brand-hoff{font-weight:700;color:var(--gold);letter-spacing:0.02em;}
  .hero-btns{display:flex;gap:1rem;flex-wrap:wrap;}
  .btn-primary{background:var(--gold);color:#1a1a00;padding:0.85rem 2rem;border-radius:3px;font-weight:700;font-size:0.86rem;letter-spacing:0.06em;text-transform:uppercase;cursor:pointer;border:none;transition:all 0.3s;text-decoration:none;display:inline-block;}
  .btn-primary:hover{background:var(--gold-lt);transform:translateY(-2px);box-shadow:0 8px 22px rgba(240,180,41,0.28);}
  .btn-outline{border:1px solid rgba(240,180,41,0.45);color:var(--gold);padding:0.85rem 2rem;border-radius:3px;font-weight:500;font-size:0.86rem;letter-spacing:0.06em;text-transform:uppercase;cursor:pointer;background:transparent;transition:all 0.3s;text-decoration:none;display:inline-block;}
  .btn-outline:hover{border-color:var(--gold);background:var(--gold-dim);}
  .hero-visual{position:relative;z-index:2;display:flex;flex-direction:column;gap:1rem;animation:fadeUp 0.9s 0.25s ease both;}
  .stat-cards{display:grid;grid-template-columns:1fr 1fr;gap:1rem;}
  .stat-card{background:rgba(52,64,103,0.85);border:1px solid var(--border);padding:1.4rem;border-radius:6px;position:relative;overflow:hidden;transition:transform 0.3s,border-color 0.3s;backdrop-filter:blur(6px);}
  .stat-card:hover{transform:translateY(-3px);border-color:rgba(240,180,41,0.4);}
  .stat-card::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,var(--gold),transparent);}
  .stat-num{font-family:'Playfair Display',serif;font-size:2.2rem;font-weight:900;color:var(--gold);line-height:1;margin-bottom:0.3rem;}
  .stat-label{font-size:0.76rem;color:var(--muted);}
  .level-ticker{background:rgba(52,64,103,0.85);border:1px solid var(--border);padding:1.4rem;border-radius:6px;position:relative;overflow:hidden;backdrop-filter:blur(6px);}
  .level-ticker::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,var(--gold),transparent);}
  .ticker-label{font-size:0.72rem;color:var(--muted);margin-bottom:0.5rem;letter-spacing:0.05em;}
  .ticker-track{display:flex;gap:0.6rem;align-items:center;}
  .ticker-item{font-family:'Playfair Display',serif;font-size:1.5rem;font-weight:900;padding:0.3rem 0.8rem;border-radius:4px;border:2px solid transparent;color:var(--muted);transition:all 0.5s;flex-shrink:0;}
  .ticker-item.active{color:var(--gold);border-color:var(--gold);background:var(--gold-dim);transform:scale(1.12);}
  .ticker-arrow{color:var(--muted);font-size:1rem;}
  .hero-badge{background:rgba(52,64,103,0.85);border:1px solid var(--border);padding:1.1rem 1.4rem;border-radius:6px;display:flex;align-items:center;gap:1rem;backdrop-filter:blur(6px);}
  .badge-icon{font-size:1.8rem;flex-shrink:0;}
  .badge-text strong{display:block;font-size:0.88rem;font-weight:600;}
  .badge-text span{font-size:0.74rem;color:var(--muted);}
  section{padding:5.5rem 5vw;}
  .section-tag{color:var(--gold);font-size:0.7rem;font-weight:600;letter-spacing:0.2em;text-transform:uppercase;display:inline-flex;align-items:center;gap:0.5rem;margin-bottom:0.8rem;}
  .section-tag::before{content:'';width:22px;height:1px;background:var(--gold);}
  h2{font-family:'Playfair Display',serif;font-size:clamp(1.9rem,3.2vw,2.8rem);font-weight:900;line-height:1.15;margin-bottom:0.9rem;}
  h2 em{color:var(--gold);font-style:normal;}
  .section-desc{color:var(--muted);font-size:0.97rem;line-height:1.75;max-width:540px;}
  #dich-vu{background:var(--deep);}
  .services-header{text-align:center;margin-bottom:3.5rem;}
  .services-header .section-desc{margin:0 auto;}
  .services-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:2px;background:var(--border);border:1px solid var(--border);}
  .service-card{background:var(--card);padding:2.8rem 2.2rem;transition:background 0.3s;position:relative;overflow:hidden;}
  .service-card:hover{background:var(--card2);}
  .service-card.featured{background:var(--green);}
  .service-card.featured:hover{background:var(--green2);}
  .service-num{font-family:'Playfair Display',serif;font-size:3.5rem;font-weight:900;color:rgba(240,180,41,0.13);line-height:1;margin-bottom:1.2rem;}
  .service-icon{font-size:1.9rem;margin-bottom:1rem;}
  .service-card h3{font-family:'Playfair Display',serif;font-size:1.35rem;font-weight:700;margin-bottom:0.9rem;color:var(--white);}
  .service-card.featured h3{color:var(--gold-lt);}
  .service-card p{color:var(--muted);font-size:0.88rem;line-height:1.7;margin-bottom:1.3rem;}
  .service-tags{display:flex;flex-wrap:wrap;gap:0.45rem;}
  .tag{padding:0.28rem 0.7rem;border:1px solid var(--border);border-radius:50px;font-size:0.7rem;color:var(--muted);}
  .service-card.featured .tag{border-color:rgba(240,180,41,0.35);color:var(--gold-lt);}
  #tieng-duc{display:grid;grid-template-columns:1fr 1fr;gap:5vw;align-items:center;}
  .levels-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:0.8rem;}
  .level-card{background:var(--card);border:1px solid var(--border);padding:1.4rem 0.8rem;border-radius:6px;text-align:center;transition:all 0.3s;}
  .level-card:hover{border-color:var(--gold);transform:translateY(-3px);}
  .level-card.hl{border-color:var(--gold);background:var(--gold-dim);}
  .level-name{font-family:'Playfair Display',serif;font-size:1.5rem;font-weight:900;color:var(--gold);}
  .level-desc{font-size:0.68rem;color:var(--muted);margin-top:0.25rem;}
  .german-quote{background:var(--card);border-left:3px solid var(--gold);padding:1.4rem 1.6rem;margin-top:1.8rem;border-radius:0 6px 6px 0;}
  .german-quote p{font-family:'Playfair Display',serif;font-size:1.05rem;color:var(--gold);font-style:italic;}
  .german-quote small{color:var(--muted);font-size:0.75rem;margin-top:0.4rem;display:block;}
  .cefr-note{background:var(--gold-dim);border:1px solid rgba(240,180,41,0.3);border-radius:6px;padding:1rem 1.2rem;margin-top:1.2rem;font-size:0.8rem;color:var(--muted);line-height:1.6;}
  .cefr-note strong{color:var(--gold);}
  #lo-trinh{background:var(--deep);}
  .steps{display:flex;flex-direction:column;margin-top:2.8rem;max-width:680px;}
  .step{display:grid;grid-template-columns:70px 1fr;gap:1.8rem;padding:1.8rem 0;border-bottom:1px solid var(--border);}
  .step:last-child{border-bottom:none;}
  .step-num{font-family:'Playfair Display',serif;font-size:2.6rem;font-weight:900;color:var(--gold-dim);line-height:1;transition:color 0.3s;}
  .step:hover .step-num{color:var(--gold);}
  .step h4{font-size:1rem;font-weight:600;margin-bottom:0.45rem;}
  .step p{color:var(--muted);font-size:0.86rem;line-height:1.65;}
  #tai-sao{display:grid;grid-template-columns:1fr 1fr;gap:5vw;align-items:start;}
  .why-list{display:flex;flex-direction:column;gap:1.2rem;margin-top:1.8rem;}
  .why-item{display:flex;gap:1.1rem;align-items:flex-start;padding:1.3rem;background:var(--card);border:1px solid var(--border);border-radius:6px;transition:border-color 0.3s;}
  .why-item:hover{border-color:rgba(240,180,41,0.35);}
  .why-icon{font-size:1.4rem;flex-shrink:0;margin-top:0.1rem;}
  .why-item h4{font-size:0.92rem;font-weight:600;margin-bottom:0.25rem;}
  .why-item p{color:var(--muted);font-size:0.82rem;line-height:1.6;}
  .fact-row{display:flex;justify-content:space-between;align-items:center;padding:1.1rem 0;border-bottom:1px solid var(--border);flex-wrap:wrap;gap:0.4rem;}
  .fact-row:last-child{border-bottom:none;}
  .fact-label{color:var(--muted);font-size:0.83rem;flex:1;min-width:0;padding-right:0.5rem;}
  .fact-value{font-weight:600;color:var(--gold);font-size:0.92rem;white-space:nowrap;}
  #thong-ke{background:var(--deep);}
  .stats-bar{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:1.5rem;margin-top:2.5rem;}
  .stats-bar-card{background:var(--card);border:1px solid var(--border);border-radius:8px;padding:1.8rem 1.4rem;text-align:center;position:relative;overflow:hidden;transition:transform 0.3s,border-color 0.3s;}
  .stats-bar-card::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,var(--gold),transparent);}
  .stats-bar-card:hover{transform:translateY(-4px);border-color:rgba(240,180,41,0.4);}
  .stats-bar-num{font-family:'Playfair Display',serif;font-size:2.4rem;font-weight:900;color:var(--gold);line-height:1;margin-bottom:0.4rem;}
  .stats-bar-label{font-size:0.78rem;color:var(--muted);line-height:1.5;}
  #cam-nhan{background:var(--bg);}
  .reviews-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(270px,1fr));gap:1.3rem;margin-top:2.8rem;}
  .review-card{background:var(--card);border:1px solid var(--border);padding:1.8rem;border-radius:6px;transition:transform 0.3s;}
  .review-card:hover{transform:translateY(-4px);}
  .review-quote{font-size:2.8rem;color:var(--gold);line-height:0.8;font-family:'Playfair Display',serif;margin-bottom:0.8rem;opacity:0.45;}
  .review-text{color:var(--muted);font-size:0.86rem;line-height:1.7;margin-bottom:1.3rem;font-style:italic;}
  .review-author{display:flex;align-items:center;gap:0.75rem;}
  .author-avatar{width:36px;height:36px;border-radius:50%;background:var(--gold-dim);border:1px solid var(--gold);display:flex;align-items:center;justify-content:center;font-size:0.95rem;flex-shrink:0;}
  .author-name{font-weight:600;font-size:0.86rem;}
  .author-meta{color:var(--muted);font-size:0.73rem;}
  #lien-he{display:grid;grid-template-columns:1fr 1fr;gap:5vw;align-items:start;}
  .contact-form{background:var(--card);border:1px solid var(--border);padding:2.3rem;border-radius:8px;}
  .contact-form h3{font-family:'Playfair Display',serif;font-size:1.35rem;margin-bottom:1.6rem;color:var(--gold);}
  .form-group{margin-bottom:1.1rem;}
  .form-group label{display:block;font-size:0.75rem;font-weight:500;letter-spacing:0.08em;text-transform:uppercase;color:var(--muted);margin-bottom:0.45rem;}
  .form-group input,.form-group select,.form-group textarea{width:100%;background:var(--deep);border:1px solid var(--border);border-radius:3px;padding:0.75rem 0.95rem;color:var(--white);font-family:'Be Vietnam Pro',sans-serif;font-size:0.88rem;outline:none;transition:border-color 0.3s;}
  .form-group input:focus,.form-group select:focus,.form-group textarea:focus{border-color:var(--gold);}
  .form-group select option{background:var(--deep);}
  .form-group textarea{resize:vertical;min-height:90px;}
  .submit-btn{width:100%;background:var(--gold);color:#1a1a00;padding:0.95rem;border:none;border-radius:3px;font-family:'Be Vietnam Pro',sans-serif;font-size:0.88rem;font-weight:700;letter-spacing:0.06em;text-transform:uppercase;cursor:pointer;transition:all 0.3s;margin-top:0.4rem;}
  .submit-btn:hover{background:var(--gold-lt);transform:translateY(-1px);}
  .contact-info{padding-top:0.5rem;}
  .contact-info h3{font-family:'Playfair Display',serif;font-size:1.7rem;margin-bottom:0.8rem;}
  .contact-info>p{color:var(--muted);line-height:1.7;margin-bottom:1.8rem;font-size:0.92rem;}
  .contact-channels{display:flex;flex-direction:column;gap:0.85rem;}
  .channel{display:flex;align-items:flex-start;gap:1rem;padding:0.95rem 1.1rem;background:var(--card);border:1px solid var(--border);border-radius:6px;text-decoration:none;color:var(--white);transition:border-color 0.3s,transform 0.2s;}
  .channel:hover{border-color:var(--gold);transform:translateX(4px);}
  .channel-icon{font-size:1.25rem;flex-shrink:0;margin-top:0.1rem;}
  .channel-label{font-size:0.68rem;color:var(--muted);letter-spacing:0.06em;text-transform:uppercase;}
  .channel-val{font-size:0.88rem;font-weight:500;word-break:break-word;}
  footer{background:var(--deep);border-top:1px solid var(--border);padding:2.8rem 5vw;display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:1.5rem;}
  .footer-logo{font-family:'Playfair Display',serif;font-weight:900;font-size:1.05rem;}
  .footer-logo span{color:var(--gold);}
  .footer-since-block{background:linear-gradient(135deg,var(--gold),var(--gold-lt));color:#1a1a00;font-size:0.72rem;font-weight:800;letter-spacing:0.18em;padding:0.3rem 0.85rem;border-radius:3px;font-family:'Be Vietnam Pro',sans-serif;box-shadow:0 2px 12px rgba(240,180,41,0.35);}
  .footer-copy{color:var(--muted);font-size:0.78rem;margin-top:0.35rem;line-height:1.7;}
  .footer-copy a{color:var(--gold);text-decoration:none;}
  .footer-flag{font-size:1.5rem;display:flex;gap:0.3rem;align-items:center;}
  @keyframes fadeUp{from{opacity:0;transform:translateY(24px);}to{opacity:1;transform:translateY(0);}}
  @media(max-width:768px){
    .hero{grid-template-columns:1fr;padding-top:5.5rem;padding-bottom:3.5rem;gap:2.5rem;}
    .nav-links{display:none;}.nav-cta{display:none;}.hamburger{display:flex;}
    #tieng-duc{grid-template-columns:1fr;}#tai-sao{grid-template-columns:1fr;}
    #lien-he{grid-template-columns:1fr;}.stat-cards{grid-template-columns:1fr 1fr;}
    .levels-grid{grid-template-columns:repeat(3,1fr);}.stat-num{font-size:1.6rem;}
    .stat-label{font-size:0.7rem;}h1{font-size:clamp(2rem,8vw,3rem);}
    h2{font-size:clamp(1.6rem,6vw,2.2rem);}.hero-badge{flex-wrap:wrap;}
    .badge-text strong{font-size:0.82rem;}.step{grid-template-columns:50px 1fr;gap:1rem;}
    .step-num{font-size:2rem;}.contact-form{padding:1.5rem;}
    footer{flex-direction:column;align-items:flex-start;}.footer-flag{align-self:flex-end;}
    .services-grid{grid-template-columns:1fr;}.service-card{padding:2rem 1.5rem;}
    .why-item{padding:1rem;}.ticker-item{font-size:1.2rem;padding:0.25rem 0.6rem;}
    section{padding:4rem 4vw;}.fact-row{flex-direction:column;align-items:flex-start;gap:0.2rem;}
  }
  @media(max-width:400px){
    .stat-cards{grid-template-columns:1fr 1fr;}.levels-grid{grid-template-columns:repeat(2,1fr);}
    h1{font-size:1.9rem;}.hero-sub{font-size:0.9rem;}
    .btn-primary,.btn-outline{padding:0.75rem 1.4rem;font-size:0.8rem;}
    .ticker-item{font-size:1rem;padding:0.2rem 0.45rem;}
  }
</style>
</head>
<body>

<div class="mobile-menu" id="mobileMenu">
  <button class="mobile-menu-close" onclick="closeMobileMenu()">✕</button>
  <a href="#dich-vu" onclick="closeMobileMenu()">Dịch Vụ</a>
  <a href="#tieng-duc" onclick="closeMobileMenu()">Tiếng Đức</a>
  <a href="#lo-trinh" onclick="closeMobileMenu()">Lộ Trình</a>
  <a href="#cam-nhan" onclick="closeMobileMenu()">Cảm Nhận</a>
  <a href="#lien-he" onclick="closeMobileMenu()">Liên Hệ</a>
  <button class="mobile-cta-btn" onclick="closeMobileMenu()">Đăng Ký Tư Vấn</button>
</div>

<nav id="mainNav">
  <div class="logo">Hành Trình Việt Đức <span>–</span> Hoff</div>
  <ul class="nav-links">
    <li><a href="#dich-vu">Dịch Vụ</a></li>
    <li><a href="#tieng-duc">Tiếng Đức</a></li>
    <li><a href="#lo-trinh">Lộ Trình</a></li>
    <li><a href="#cam-nhan">Cảm Nhận</a></li>
    <li><a href="#lien-he">Liên Hệ</a></li>
  </ul>
  <button class="nav-cta" onclick="document.getElementById('lien-he').scrollIntoView({behavior:'smooth'})">Đăng Ký Tư Vấn</button>
  <button class="hamburger" onclick="openMobileMenu()" aria-label="Menu">
    <span></span><span></span><span></span>
  </button>
</nav>

<section class="hero" id="hero">
  <div class="flag-bar"><span></span><span></span><span></span></div>
  <div class="hero-text">
    <div class="eyebrow">Từ Việt Nam · Đến Nước Đức</div>
    <h1>Hành trình<br><em>vững chắc</em><br>sang Đức</h1>
    <p class="hero-sub">
      <span class="brand-hoff">Hành Trình Việt Đức – Hoff</span> đồng hành từ buổi học A1 đầu tiên cho đến khi bạn ổn định tại Đức — không để bạn bước đi một mình trên hành trình Việt–Đức.
    </p>
    <div class="hero-btns">
      <a href="#lien-he" class="btn-primary">Bắt Đầu Ngay</a>
      <a href="#dich-vu" class="btn-outline">Xem Dịch Vụ</a>
    </div>
  </div>
  <div class="hero-visual">
    <div class="stat-cards">
      <div class="stat-card"><div class="stat-num">14+</div><div class="stat-label">Năm kinh nghiệm (từ 2011)</div></div>
      <div class="stat-card"><div class="stat-num">500+</div><div class="stat-label">Học viên đã sang Đức thành công</div></div>
      <div class="stat-card"><div class="stat-num">20K+</div><div class="stat-label">Lượt tiếp cận website</div></div>
      <div class="stat-card"><div class="stat-num">6.8K+</div><div class="stat-label">Câu hỏi tư vấn đã hỗ trợ</div></div>
    </div>
    <div class="level-ticker">
      <div class="ticker-label">Lộ trình trình độ theo Khung CEFR</div>
      <div class="ticker-track" id="tickerTrack">
        <div class="ticker-item active" data-i="0">A1</div>
        <div class="ticker-arrow">→</div>
        <div class="ticker-item" data-i="1">A2</div>
        <div class="ticker-arrow">→</div>
        <div class="ticker-item" data-i="2">B1</div>
        <div class="ticker-arrow">→</div>
        <div class="ticker-item" data-i="3">B2</div>
      </div>
    </div>
    <div class="hero-badge">
      <div class="badge-icon">🏛️</div>
      <div class="badge-text">
        <strong>Trung Tâm Đức Ngữ Lila · Khoa Tiếng Đức – Trường TC Bách Khoa Hải Phòng</strong>
        <span>Đơn vị đào tạo chính thức & được công nhận</span>
      </div>
    </div>
  </div>
</section>

<!-- DỊCH VỤ -->
<section id="dich-vu">
  <div class="services-header">
    <div class="section-tag">Dịch Vụ</div>
    <h2>Không chỉ là <em>một nơi học tiếng</em></h2>
    <p class="section-desc">
      <span class="brand-hoff">Hành Trình Việt Đức – Hoff</span> sở hữu sẵn hệ thống đơn vị đào tạo và tư vấn — để học viên được tiếp nhận, đào tạo và định hướng ngay dưới một mái nhà.
    </p>
  </div>
  <div class="services-grid">

    <div class="service-card">
      <div class="service-num">01</div>
      <div class="service-icon">🎓</div>
      <h3>Trung Tâm Đức Ngữ Lila</h3>
      <p>Trung tâm ngoại ngữ chuyên sâu tiếng Đức, đào tạo từ A1 đến B2 theo chuẩn CEFR. Giảng viên có kinh nghiệm thực tế tại Đức, giáo trình cập nhật theo đề thi TELC, Goethe-Prüfung và ÖSD — ba hệ thống chứng chỉ tiếng Đức quốc tế được CHLB Đức công nhận.</p>
      <div class="service-tags">
        <span class="tag">A1 – B2</span>
        <span class="tag">TELC Prep</span>
        <span class="tag">Goethe Prep</span>
        <span class="tag">ÖSD Prep</span>
        <span class="tag">Lớp nhỏ</span>
      </div>
    </div>

    <!-- FIX 2: Thay ngành y khoa → nhà hàng, khách sạn, bếp, IT, kế toán, bán hàng -->
    <div class="service-card featured">
      <div class="service-num">02</div>
      <div class="service-icon">🏫</div>
      <h3>Khoa Tiếng Đức – Trường TC Bách Khoa Hải Phòng</h3>
      <p>Đơn vị đào tạo chính thức, được Sở Giáo dục & Đào tạo công nhận. Trường đào tạo hệ trung cấp các ngành nghề như: Nhà hàng – Khách sạn, Bếp (Đầu bếp chuyên nghiệp), Công nghệ thông tin, Kế toán doanh nghiệp, Bán hàng & Quản lý bán lẻ, Điện công nghiệp, Hàn, Cắt gọt kim loại — với chương trình kết hợp tiếng Đức chuyên ngành ngay trong quá trình học.</p>
      <p style="margin-top:0.6rem;">Học viên hoàn tất chương trình trung cấp nghề tại Việt Nam có thể được hỗ trợ làm hồ sơ <strong>Anerkennung</strong> (công nhận bằng cấp tại Đức) — rút ngắn thời gian Ausbildung từ 2 đến 2,5 năm khi sang CHLB Đức.</p>
      <div class="service-tags">
        <span class="tag">Nhà hàng – Khách sạn</span>
        <span class="tag">Bếp</span>
        <span class="tag">IT</span>
        <span class="tag">Kế toán</span>
        <span class="tag">Bán hàng</span>
        <span class="tag">Anerkennung</span>
        <span class="tag">Chính thức</span>
      </div>
    </div>

    <div class="service-card">
      <div class="service-num">03</div>
      <div class="service-icon">📋</div>
      <h3>Tư Vấn & Hồ Sơ Du Học Nghề</h3>
      <p>Đội ngũ tư vấn am hiểu quy trình Ausbildung — từ chọn ngành, tìm đơn vị đào tạo tại Đức, đến chuẩn bị hồ sơ xin visa và phỏng vấn Đại sứ quán. Tỷ lệ visa đạt trên 90%.</p>
      <div class="service-tags">
        <span class="tag">Ausbildung</span>
        <span class="tag">Hồ sơ visa</span>
        <span class="tag">Phỏng vấn</span>
      </div>
    </div>

    <div class="service-card">
      <div class="service-num">04</div>
      <div class="service-icon">✈️</div>
      <h3>Hỗ Trợ Sau Khi Đến Đức</h3>
      <p>Hoff không dừng lại hợp tác sau khi bạn đến Đức. Hành trình tiếp tục với hỗ trợ Anmeldung, mở tài khoản ngân hàng, tìm chỗ ở, kết nối cộng đồng người Việt tại Đức và đồng hành hội nhập dài hạn.</p>
      <div class="service-tags">
        <span class="tag">Anmeldung</span>
        <span class="tag">Nhà ở</span>
        <span class="tag">Hội nhập</span>
        <span class="tag">Cộng đồng</span>
      </div>
    </div>

  </div>
</section>

<!-- TIẾNG ĐỨC -->
<section id="tieng-duc">
  <div>
    <div class="section-tag">Chương Trình Đào Tạo</div>
    <h2>Tiếng Đức <em>chuẩn quốc tế</em></h2>
    <p class="section-desc">Giảng dạy theo Khung Tham chiếu Ngôn ngữ Chung châu Âu (CEFR) — chuẩn quốc tế được các trường Đức, Áo, Thụy Sĩ công nhận. Mỗi cấp độ được thiết kế để học viên sẵn sàng thi chứng chỉ TELC, Goethe-Prüfung hoặc ÖSD ngay sau khóa học.</p>
    <div class="cefr-note">
      <strong>📐 Khung CEFR là gì?</strong> — CEFR (Common European Framework of Reference for Languages) là hệ thống phân loại trình độ ngôn ngữ từ A1 (sơ cấp) đến C2 (thành thạo), được châu Âu và toàn thế giới sử dụng để đánh giá năng lực ngoại ngữ. Để học nghề tại Đức (Ausbildung), thông thường bạn cần đạt tối thiểu <strong>B1–B2</strong>.
    </div>
    <div class="german-quote">
      <p>„Übung macht den Meister."</p>
      <small>Luyện tập tạo nên bậc thầy — tục ngữ Đức</small>
    </div>
  </div>
  <div>
    <div class="levels-grid">
      <div class="level-card"><div class="level-name">A1</div><div class="level-desc">Sơ cấp 1</div></div>
      <div class="level-card"><div class="level-name">A2</div><div class="level-desc">Sơ cấp 2</div></div>
      <div class="level-card hl"><div class="level-name">B1</div><div class="level-desc">Trung cấp 1</div></div>
      <div class="level-card hl"><div class="level-name">B2</div><div class="level-desc">Trung cấp 2</div></div>
      <div class="level-card"><div class="level-name">C1</div><div class="level-desc">Nâng cao</div></div>
      <div class="level-card"><div class="level-name">C2</div><div class="level-desc">Thành thạo</div></div>
    </div>
    <div style="margin-top:1.5rem;display:flex;flex-direction:column;gap:0.6rem;">
      <div class="fact-row"><span class="fact-label">Chứng chỉ luyện thi</span><span class="fact-value">TELC · Goethe-Prüfung · ÖSD</span></div>
      <div class="fact-row"><span class="fact-label">Chuẩn đề thi Ausbildung</span><span class="fact-value">B1 – B2</span></div>
      <div class="fact-row"><span class="fact-label">Hình thức học</span><span class="fact-value">Trực tiếp · Online</span></div>
      <div class="fact-row"><span class="fact-label">Sĩ số lớp</span><span class="fact-value">Tối đa 12 học viên</span></div>
    </div>
  </div>
</section>

<!-- LỘ TRÌNH -->
<section id="lo-trinh">
  <div class="section-tag">Lộ Trình</div>
  <h2>Từ A1 <em>đến Đức</em> — từng bước</h2>
  <p class="section-desc">Hành trình được thiết kế rõ ràng — bạn luôn biết mình đang ở đâu và bước tiếp theo là gì.</p>
  <div class="steps">
    <div class="step"><div class="step-num">01</div><div><h4>Tư vấn & định hướng ngành nghề</h4><p>Phân tích năng lực, sở thích và điều kiện cá nhân. Lựa chọn ngành Ausbildung phù hợp thị trường lao động Đức và khả năng của bạn.</p></div></div>
    <div class="step"><div class="step-num">02</div><div><h4>Học tiếng Đức A1 → B2</h4><p>Đào tạo bài bản theo lộ trình CEFR tại Trung Tâm Đức Ngữ Lila hoặc Khoa Tiếng Đức — Trường TC Bách Khoa Hải Phòng. Luyện thi chứng chỉ TELC / Goethe.</p></div></div>
    <div class="step"><div class="step-num">03</div><div><h4>Chuẩn bị hồ sơ & nộp đơn</h4><p>Hoàn thiện CV Đức (Lebenslauf), thư động cơ, bằng cấp dịch thuật công chứng. Kết nối trực tiếp với doanh nghiệp đối tác tại Đức.</p></div></div>
    <div class="step"><div class="step-num">04</div><div><h4>Phỏng vấn & xin visa</h4><p>Luyện phỏng vấn với nhà tuyển dụng Đức, hỗ trợ toàn bộ quy trình xin visa Ausbildung tại Đại sứ quán Đức. Tỷ lệ đậu trên 90%.</p></div></div>
    <div class="step"><div class="step-num">05</div><div><h4>Bay sang Đức & hội nhập</h4><p>Hoff không dừng lại hợp tác khi bạn hạ cánh. Hỗ trợ Anmeldung, mở tài khoản, tìm chỗ ở và kết nối cộng đồng — đồng hành dài hạn tại Đức.</p></div></div>
  </div>
</section>

<!-- TẠI SAO -->
<section id="tai-sao">
  <div>
    <div class="section-tag">Tại Sao Hành Trình Việt Đức – Hoff</div>
    <h2>Lý do <em>2.000+ người</em> tin chọn</h2>
    <div class="why-list">
      <div class="why-item"><div class="why-icon">🏛️</div><div><h4>Hệ thống đơn vị sẵn có</h4><p>Trường TC Bách Khoa Hải Phòng sở hữu Trung Tâm Đức Ngữ Lila và Khoa Tiếng Đức chính thức — học viên được tiếp nhận và đào tạo trong cùng một hệ thống, không qua trung gian.</p></div></div>
      <div class="why-item"><div class="why-icon">📅</div><div><h4>14 năm kinh nghiệm (từ 2011)</h4><p>Hơn 14 năm chuyên sâu thị trường lao động Đức — hiểu rõ từng ngành nghề, từng yêu cầu visa và từng biến động của chính sách nhập cư Đức.</p></div></div>
      <div class="why-item"><div class="why-icon">🤝</div><div><h4>Không bỏ rơi sau visa</h4><p><span class="brand-hoff">Hoff</span> không dừng lại hợp tác sau khi bạn đến Đức. Tiếp tục đồng hành Anmeldung, hội nhập, và cuộc sống tại Đức — vì hành trình thật sự bắt đầu khi bạn hạ cánh.</p></div></div>
      <div class="why-item"><div class="why-icon">🎯</div><div><h4>Tỷ lệ visa 90%+</h4><p>Quy trình hồ sơ được chuẩn hóa qua nhiều năm — tỷ lệ đậu visa Ausbildung luôn duy trì trên 90%, thuộc nhóm cao nhất tại Hải Phòng.</p></div></div>
    </div>
  </div>
  <div>
    <div class="section-tag">Dữ Liệu</div>
    <h2>Những <em>con số</em> nói lên</h2>
    <div style="margin-top:1.5rem;">
      <div class="fact-row"><span class="fact-label">Hoạt động từ</span><span class="fact-value">2011</span></div>
      <div class="fact-row"><span class="fact-label">Học viên đã sang Đức</span><span class="fact-value">500+</span></div>
      <div class="fact-row"><span class="fact-label">Tỷ lệ đậu visa</span><span class="fact-value">&gt; 90%</span></div>
      <div class="fact-row"><span class="fact-label">Đối tác doanh nghiệp tại Đức</span><span class="fact-value">80+</span></div>
      <div class="fact-row"><span class="fact-label">Ngành Ausbildung hỗ trợ</span><span class="fact-value">20+</span></div>
      <div class="fact-row"><span class="fact-label">Lượt tiếp cận website</span><span class="fact-value">20,000+</span></div>
      <div class="fact-row"><span class="fact-label">Câu hỏi tư vấn đã giải đáp</span><span class="fact-value">6,800+</span></div>
    </div>
  </div>
</section>

<!-- THỐNG KÊ -->
<section id="thong-ke" style="padding-top:3rem;padding-bottom:3rem;">
  <div class="section-tag" style="margin-bottom:0.4rem;">Tổng Quan</div>
  <h2 style="margin-bottom:0.5rem;">Hành Trình Việt Đức – Hoff : <em>Con Số Thực Tế</em></h2>
  <div class="stats-bar">
    <div class="stats-bar-card"><div class="stats-bar-num">20,000+</div><div class="stats-bar-label">Lượt tiếp cận trang web</div></div>
    <div class="stats-bar-card"><div class="stats-bar-num">6,800+</div><div class="stats-bar-label">Người quan tâm & đặt câu hỏi</div></div>
    <div class="stats-bar-card"><div class="stats-bar-num">500+</div><div class="stats-bar-label">Học viên sang Đức thành công</div></div>
    <div class="stats-bar-card"><div class="stats-bar-num">14+</div><div class="stats-bar-label">Năm kinh nghiệm liên tục</div></div>
  </div>
</section>

<!-- CẢM NHẬN -->
<section id="cam-nhan">
  <div class="section-tag">Cảm Nhận</div>
  <h2>Học viên <em>chia sẻ</em></h2>
  <p class="section-desc">Những câu chuyện thật từ những người đã bước qua hành trình — với sự đồng hành của <span class="brand-hoff">Hành Trình Việt Đức – Hoff</span> — từ bàn học tiếng Đức đến cuộc sống ổn định tại CHLB Đức.</p>
  <div class="reviews-grid">

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Mình học A1 tại <span class="brand-hoff">Hoff</span> năm 2019 không biết gì về tiếng Đức cả. Giờ mình đã hoàn thành Ausbildung ngành điều dưỡng ở Frankfurt, đang làm chính thức với mức lương 3.800€/tháng. <span class="brand-hoff">Hoff</span> đã thay đổi cuộc đời mình thật sự.</p>
      <div class="review-author">
        <div class="author-avatar">🌟</div>
        <div><div class="author-name">Nguyễn Thị Lan Anh</div><div class="author-meta">Điều dưỡng · Frankfurt am Main · 2020</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Trước mình từng thử học qua một trung tâm khác nhưng hồ sơ bị từ chối visa. Sang <span class="brand-hoff">Hoff</span>, đội ngũ làm hồ sơ kỹ lắm, visa được duyệt trong lần đầu. Hiện tại mình đang học nghề cơ điện tử tại Bayern.</p>
      <div class="review-author">
        <div class="author-avatar">⚙️</div>
        <div><div class="author-name">Trần Văn Đức</div><div class="author-meta">Cơ điện tử · Bayern · 2021</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Thi B2 lần đầu đậu luôn nhờ luyện đề sát với đề thật. Qua Đức rồi mà vẫn được <span class="brand-hoff">Hoff</span> hỗ trợ đăng ký Anmeldung, mở tài khoản Sparkasse. Cảm giác không bị bỏ rơi khi ở xứ người.</p>
      <div class="review-author">
        <div class="author-avatar">🏦</div>
        <div><div class="author-name">Phạm Thị Mai</div><div class="author-meta">Kế toán · Hamburg · 2022</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Mình từng nghĩ tiếng Đức quá khó, đã định bỏ cuộc ở A2. Thầy cô <span class="brand-hoff">Hoff</span> kiên nhẫn lắm, không ai bị bỏ lại phía sau. Giờ mình đang hoàn thành năm thứ hai Ausbildung ngành bếp ở Berlin.</p>
      <div class="review-author">
        <div class="author-avatar">👨‍🍳</div>
        <div><div class="author-name">Lê Quang Huy</div><div class="author-meta">Đầu bếp · Berlin · 2021</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Quy trình hồ sơ của <span class="brand-hoff">Hoff</span> rất minh bạch. Mỗi bước đều được giải thích rõ, không có phí ẩn. Gia đình mình yên tâm vì biết con được đồng hành tận nơi, không phải tự bơi khi mới đến Đức.</p>
      <div class="review-author">
        <div class="author-avatar">🔧</div>
        <div><div class="author-name">Ngô Thị Thu Hương</div><div class="author-meta">Kỹ thuật máy · Stuttgart · 2022</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Mình sang Đức năm 2020, lúc dịch COVID cực kỳ khó khăn. <span class="brand-hoff">Hoff</span> vẫn theo sát, giúp mình liên hệ được với chủ Ausbildung và không bị gián đoạn hợp đồng. Ơn này không quên được.</p>
      <div class="review-author">
        <div class="author-avatar">🏥</div>
        <div><div class="author-name">Vũ Minh Khoa</div><div class="author-meta">Y tá · Köln · 2020</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Lớp học nhỏ, thầy chú ý từng người. Mình phát âm kém nhưng được luyện riêng thêm sau giờ học. Thi TELC B1 điểm cao, phỏng vấn với công ty Đức tự tin hẳn.</p>
      <div class="review-author">
        <div class="author-avatar">🎯</div>
        <div><div class="author-name">Đỗ Thị Thanh Vân</div><div class="author-meta">Logistics · Düsseldorf · 2023</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Mình là mẹ đơn thân, lo lắng nhiều lắm khi quyết định sang Đức. <span class="brand-hoff">Hoff</span> không chỉ giúp hồ sơ mà còn kết nối mình với cộng đồng người Việt ở Hannover trước khi bay. Ấm lòng lắm.</p>
      <div class="review-author">
        <div class="author-avatar">🌸</div>
        <div><div class="author-name">Nguyễn Thị Bích Ngọc</div><div class="author-meta">Chăm sóc người già · Hannover · 2022</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Khóa B2 của <span class="brand-hoff">Hoff</span> chạy đúng giáo trình Goethe, luyện kỹ 4 kỹ năng nghe-nói-đọc-viết. Mình đạt B2 sau 8 tháng, nhanh hơn dự kiến. Giờ thu nhập Ausbildung ở Đức hơn 1.200€/tháng.</p>
      <div class="review-author">
        <div class="author-avatar">💼</div>
        <div><div class="author-name">Hoàng Văn Tùng</div><div class="author-meta">IT · München · 2023</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text"><span class="brand-hoff">Hoff</span> dạy tiếng Đức theo hướng ứng dụng thực tế — giao tiếp nơi làm việc, đặt lịch bác sĩ, viết email. Sang Đức là dùng được luôn, không bị sốc ngôn ngữ như nhiều bạn khác.</p>
      <div class="review-author">
        <div class="author-avatar">🌍</div>
        <div><div class="author-name">Trần Thị Hồng Nhung</div><div class="author-meta">Khách sạn · Heidelberg · 2021</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Ba mình gần 40 tuổi vẫn theo học được. Thầy cô kiên nhẫn, giải thích tiếng Việt rõ ràng. Sau 1 năm đạt B1, hiện đang làm thợ hàn ở Dortmund, gửi tiền về nuôi gia đình.</p>
      <div class="review-author">
        <div class="author-avatar">🔩</div>
        <div><div class="author-name">Lê Văn Bình</div><div class="author-meta">Thợ hàn · Dortmund · 2022</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Mình học online vì ở xa Hải Phòng nhưng chất lượng không thua gì học trực tiếp. <span class="brand-hoff">Hoff</span> dạy qua Zoom có tương tác, có bài tập gửi về, có sửa phát âm. Rất chuyên nghiệp và đúng giờ.</p>
      <div class="review-author">
        <div class="author-avatar">💻</div>
        <div><div class="author-name">Phạm Ngọc Anh</div><div class="author-meta">Điện tử · Bremen · 2023</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Mình tự học tiếng Đức 6 tháng trước nhưng không có hệ thống. Vào <span class="brand-hoff">Hoff</span> học lại từ A2, thầy sắp xếp bài bản, ngữ pháp nền tảng rõ ràng. 5 tháng sau thi B1 đậu ngay lần đầu.</p>
      <div class="review-author">
        <div class="author-avatar">📚</div>
        <div><div class="author-name">Đinh Thị Lan</div><div class="author-meta">Dược · Magdeburg · 2023</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Phỏng vấn với chủ Ausbildung bên Đức qua video call, <span class="brand-hoff">Hoff</span> luyện trước với mình đến 5 lần. Hỏi đến đâu trả lời được đến đó. Nhận được hợp đồng ngay buổi phỏng vấn đầu tiên.</p>
      <div class="review-author">
        <div class="author-avatar">🤝</div>
        <div><div class="author-name">Bùi Thanh Long</div><div class="author-meta">Cơ khí · Nürnberg · 2022</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text"><span class="brand-hoff">Hoff</span> kết nối mình với cộng đồng người Việt tại Leipzig trước khi sang. Ngày đầu tiên đến đã có người đón, hướng dẫn đăng ký thành phố. Không bị lạc lõng dù là lần đầu ra nước ngoài.</p>
      <div class="review-author">
        <div class="author-avatar">🏙️</div>
        <div><div class="author-name">Nguyễn Thị Thu</div><div class="author-meta">Siêu thị · Leipzig · 2021</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Mình được học bổng một phần từ doanh nghiệp Đức nhờ <span class="brand-hoff">Hoff</span> kết nối và hỗ trợ viết thư ứng tuyển. Giờ vừa học nghề vừa được nhận lương Ausbildung 1.050€ mỗi tháng.</p>
      <div class="review-author">
        <div class="author-avatar">🎓</div>
        <div><div class="author-name">Cao Văn Hải</div><div class="author-meta">Xây dựng · Dresden · 2023</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Tư vấn của <span class="brand-hoff">Hoff</span> không bao giờ tạo áp lực hay rush hồ sơ. Đợi đúng thời điểm visa phù hợp, kết quả là đợt đó 5 bạn cùng nhóm đều đậu. Cảm giác đi cùng đồng đội rất vui.</p>
      <div class="review-author">
        <div class="author-avatar">👥</div>
        <div><div class="author-name">Trần Thị Ngọc Hà</div><div class="author-meta">Nhà hàng · Bonn · 2022</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Mình là kỹ sư nhưng sang Đức học Ausbildung lại từ đầu theo lĩnh vực mới. <span class="brand-hoff">Hoff</span> tư vấn ngành phù hợp với bằng Việt Nam để được miễn giảm thời gian học — tiết kiệm gần 1 năm so với bình thường.</p>
      <div class="review-author">
        <div class="author-avatar">🧠</div>
        <div><div class="author-name">Lý Văn Phong</div><div class="author-meta">Tự động hóa · Wolfsburg · 2023</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Nhờ có <span class="brand-hoff">Hoff</span> mà mình không bị các trung tâm "ma" lừa. Học phí rõ ràng, hợp đồng minh bạch. Gia đình mình tiết kiệm được một khoản lớn so với các nơi kêu phí trọn gói rồi biến mất.</p>
      <div class="review-author">
        <div class="author-avatar">🛡️</div>
        <div><div class="author-name">Phan Thị Kim Chi</div><div class="author-meta">Y tế · Münster · 2021</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Sau 3 năm Ausbildung mình tốt nghiệp và được nhận vào làm chính thức tại công ty Đức. Thu nhập hiện tại 2.400€/tháng. Hành trình bắt đầu từ lớp A1 của <span class="brand-hoff">Hoff</span> năm 2018 — cảm ơn thầy cô rất nhiều.</p>
      <div class="review-author">
        <div class="author-avatar">🏆</div>
        <div><div class="author-name">Nguyễn Văn Thắng</div><div class="author-meta">Kỹ sư CNC · Hamburg · 2018 → Fulltime 2022</div></div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Mình từng bị một trung tâm khác lấy gần 200 triệu, hứa visa trong 3 tháng rồi im bặt luôn. Mất tiền, mất thời gian, mất niềm tin. May mắn tìm được <span class="brand-hoff">Hoff</span> — không đòi tiền trước, hợp đồng rõ ràng từng điều khoản. Giờ mình đang học Ausbildung ngành bán hàng ở Dortmund, bình yên thật sự.</p>
      <div class="review-author">
        <div class="author-avatar">😤</div>
        <div>
          <div class="author-name">Nguyễn Thị Hồng Loan</div>
          <div class="author-meta">Bán hàng · Dortmund · 2023</div>
        </div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Thi TELC B1 trượt 3 lần liên tiếp, mình gần như bỏ cuộc. Sang <span class="brand-hoff">Hoff</span> học lại, thầy phân tích từng lỗi sai, luyện riêng phần Hörverstehen vốn là điểm yếu nhất. Lần thứ 4 thi là đậu, điểm còn khá nữa. Bây giờ nghĩ lại thấy may mắn vì không bỏ cuộc.</p>
      <div class="review-author">
        <div class="author-avatar">💪</div>
        <div>
          <div class="author-name">Trần Quốc Bảo</div>
          <div class="author-meta">Nhà hàng · Hannover · 2022</div>
        </div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Thật lòng mà nói, mình vào lớp A1 mà không phân biệt nổi "der, die, das". Học cả tuần vẫn không nhớ. Thầy không chê, chỉ bảo: "học ngôn ngữ không có người ngu, chỉ có người chưa tìm đúng cách học". Đúng vậy thật — 14 tháng sau mình thi B2 đậu, đang làm IT Ausbildung ở Köln.</p>
      <div class="review-author">
        <div class="author-avatar">🤯</div>
        <div>
          <div class="author-name">Lê Minh Triết</div>
          <div class="author-meta">IT · Köln · 2023</div>
        </div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Hồ sơ mình nộp qua một đơn vị khác, chờ gần 8 tháng mà họ cứ nói "đang xử lý". Hỏi thêm thì bảo nộp thêm phí. Mình rút ra, tìm đến <span class="brand-hoff">Hoff</span> — chỉ 4 tháng sau là có hợp đồng Ausbildung từ doanh nghiệp Đức. Đừng để người ta om hồ sơ của mình mãi.</p>
      <div class="review-author">
        <div class="author-avatar">⏳</div>
        <div>
          <div class="author-name">Phạm Văn Kiên</div>
          <div class="author-meta">Cơ khí · Essen · 2022</div>
        </div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Mình tự tìm hợp đồng Ausbildung trên mạng gần 1 năm không ra. Nộp hơn 40 đơn, hồi âm được 2 cái mà cũng chẳng đến đâu. Vào <span class="brand-hoff">Hoff</span>, họ có sẵn mạng lưới 80+ đối tác doanh nghiệp Đức — mình được kết nối trực tiếp, phỏng vấn và nhận hợp đồng sau 6 tuần. Khác hoàn toàn so với tự làm.</p>
      <div class="review-author">
        <div class="author-avatar">🔍</div>
        <div>
          <div class="author-name">Đặng Thị Thúy Nga</div>
          <div class="author-meta">Khách sạn · Frankfurt · 2023</div>
        </div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Mình bị Kündigung sau 4 tháng Ausbildung vì công ty phá sản đột ngột. Hoảng loạn không biết làm gì, visa sắp hết hạn. Liên hệ <span class="brand-hoff">Hoff</span> — họ hướng dẫn làm thủ tục báo Jobcenter, tìm công ty mới trong ngành và hỗ trợ chuyển hợp đồng. Chỉ 7 tuần sau mình đã có Ausbildungsvertrag mới. Cảm ơn <span class="brand-hoff">Hoff</span> đã không bỏ mình lại.</p>
      <div class="review-author">
        <div class="author-avatar">🆘</div>
        <div>
          <div class="author-name">Vũ Thị Thu Trang</div>
          <div class="author-meta">Bếp · München · 2022</div>
        </div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Công ty Ausbildung của mình đột ngột gửi Kündigung vì "không phù hợp văn hóa làm việc" — mình không biết quyền của mình là gì. <span class="brand-hoff">Hoff</span> kết nối mình với người hỗ trợ pháp lý, giải thích quyền lợi theo luật lao động Đức và tìm được Ausbildung mới trong 2 tháng. Không có họ chắc mình đã về nước rồi.</p>
      <div class="review-author">
        <div class="author-avatar">⚖️</div>
        <div>
          <div class="author-name">Hoàng Đức Anh</div>
          <div class="author-meta">Điện công nghiệp · Stuttgart · 2021</div>
        </div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Mình nộp gần 150 triệu cho một "đại lý", họ làm giấy tờ không hợp lệ mà mình không biết. Đến sân bay bị phát hiện, phải quay về, bị cấm nhập cảnh 1 năm. Sau đó tìm đến <span class="brand-hoff">Hoff</span> — họ hỗ trợ làm hồ sơ đúng chuẩn từ đầu, giải thích rõ từng loại giấy tờ. Giờ mình sang Đức hợp pháp, học nghề nhà hàng tại Hamburg. Đừng để ham rẻ mà mất cả tương lai.</p>
      <div class="review-author">
        <div class="author-avatar">🚨</div>
        <div>
          <div class="author-name">Ngô Văn Lực</div>
          <div class="author-meta">Nhà hàng · Hamburg · 2023</div>
        </div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Mình thi B1 trượt 2 lần, B2 trượt 1 lần. Đã 28 tuổi, ba mẹ bắt đầu bảo thôi bỏ đi. Nhưng cô giáo ở <span class="brand-hoff">Hoff</span> gọi điện riêng hỏi thăm, nói "em học được, chỉ cần thêm thời gian". Học thêm 3 tháng, thi B2 đậu. Bây giờ mình 30 tuổi, đang làm kế toán Ausbildung ở Düsseldorf. Không bao giờ quên cuộc điện thoại đó.</p>
      <div class="review-author">
        <div class="author-avatar">🌱</div>
        <div>
          <div class="author-name">Trần Thị Ngọc Bích</div>
          <div class="author-meta">Kế toán · Düsseldorf · 2022</div>
        </div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-quote">"</div>
      <p class="review-text">Sang Đức được 6 tháng thì chủ Ausbildung thay đổi chính sách nội bộ, không nhận học viên nước ngoài nữa và gửi Kündigung hàng loạt. Cả nhóm 3 người Việt đều bị. Mình liên hệ <span class="brand-hoff">Hoff</span> dù trước đó chưa từng học ở đây. Họ vẫn hỗ trợ — kết nối đối tác tại Đức, giúp mình chuyển sang công ty mới cùng ngành bếp chỉ sau 5 tuần. Nghĩa cử này mình không quên.</p>
      <div class="review-author">
        <div class="author-avatar">🍽️</div>
        <div>
          <div class="author-name">Lý Thị Mỹ Duyên</div>
          <div class="author-meta">Bếp · Berlin · 2023</div>
        </div>
      </div>
    </div>

  </div>
</section>

<!-- LIÊN HỆ -->
<section id="lien-he">
  <div class="contact-info">
    <div class="section-tag">Liên Hệ</div>
    <h3>Bắt đầu hành trình <em style="color:var(--gold);font-style:normal;">của bạn</em></h3>
    <p>Đặt câu hỏi, đăng ký tư vấn miễn phí hoặc ghé thăm trực tiếp. Đội ngũ <span class="brand-hoff">Hành Trình Việt Đức – Hoff</span> luôn sẵn sàng đồng hành từ bước đầu tiên.</p>
    <div class="contact-channels">
      <a href="tel:+84961679869" class="channel"><div class="channel-icon">📞</div><div><div class="channel-label">Điện Thoại / Zalo / WhatsApp</div><div class="channel-val">0961 679 869</div></div></a>
      <a href="https://facebook.com" class="channel" target="_blank"><div class="channel-icon">📘</div><div><div class="channel-label">Facebook</div><div class="channel-val">Trang Facebook Hành Trình Việt Đức – Hoff</div></div></a>
      <a href="mailto:vertrieb.lilasprachschule@gmail.com" class="channel"><div class="channel-icon">✉️</div><div><div class="channel-label">Email</div><div class="channel-val">vertrieb.lilasprachschule@gmail.com</div></div></a>
      <a href="#" class="channel"><div class="channel-icon">📍</div><div><div class="channel-label">Địa Chỉ</div><div class="channel-val">Trường TC Bách Khoa Hải Phòng – Khoa Tiếng Đức, Hải Phòng</div></div></a>
    </div>
  </div>
  <div class="contact-form">
    <h3>Đăng Ký Tư Vấn Miễn Phí</h3>
    <div class="form-group"><label>Họ và Tên</label><input type="text" placeholder="Nguyễn Văn A"></div>
    <div class="form-group"><label>Số Điện Thoại / Zalo</label><input type="tel" placeholder="09xx xxx xxx"></div>
    <div class="form-group"><label>Trình Độ Hiện Tại</label><select><option value="">— Chọn trình độ —</option><option>Chưa biết tiếng Đức</option><option>A1</option><option>A2</option><option>B1</option><option>B2</option></select></div>
    <div class="form-group"><label>Mục Tiêu</label><select><option value="">— Chọn mục tiêu —</option><option>Du học nghề (Ausbildung)</option><option>Học tiếng Đức thi chứng chỉ</option><option>Làm việc tại Đức</option><option>Đoàn tụ gia đình</option><option>Khác</option></select></div>
    <div class="form-group"><label>Câu Hỏi / Ghi Chú</label><textarea placeholder="Bạn muốn hỏi thêm điều gì?"></textarea></div>
    <button class="submit-btn">Gửi Đăng Ký</button>
  </div>
</section>

<footer>
  <div>
    <div class="footer-logo">Hành Trình Việt Đức <span>–</span> Hoff</div>
    <div class="footer-copy">
      © 2026 · <a href="#">Trung Tâm Đức Ngữ Lila</a> · Trường Trung Cấp Bách Khoa Hải Phòng – Khoa Tiếng Đức<br>
      <span style="color:var(--gold);font-style:italic;">Đồng hành hành trình Việt–Đức từ A1 đến ổn định tại CHLB Đức.</span>
    </div>
  </div>
  <div style="display:flex;flex-direction:column;align-items:flex-end;gap:0.6rem;">
    <div class="footer-since-block">EST. 2011</div>
    <div class="footer-flag">🇻🇳 <span style="color:var(--gold);font-size:0.85rem;margin:0 0.4rem;">→</span> 🇩🇪</div>
  </div>
</footer>

<script>
  const nav = document.getElementById('mainNav');
  window.addEventListener('scroll', () => { nav.classList.toggle('scrolled', window.scrollY > 60); });
  function openMobileMenu() { document.getElementById('mobileMenu').classList.add('open'); document.body.style.overflow='hidden'; }
  function closeMobileMenu() { document.getElementById('mobileMenu').classList.remove('open'); document.body.style.overflow=''; }
  const items = document.querySelectorAll('.ticker-item');
  let current = 0;
  setInterval(() => { items[current].classList.remove('active'); current=(current+1)%items.length; items[current].classList.add('active'); }, 1200);
</script>
</body>
</html>
