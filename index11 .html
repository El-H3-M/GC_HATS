<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>GC_HATS — Streetwear Premium</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Montserrat:wght@300;400;600;700;900&family=Cormorant+Garamond:ital,wght@0,300;0,600;1,300&display=swap" rel="stylesheet"/>
  <style>
    :root {
      --black: #080808;
      --card: #111111;
      --card2: #191919;
      --border: #272727;
      --border2: #333;
      --gold: #c9a84c;
      --gold-light: #e8c96a;
      --gold-dim: rgba(201,168,76,0.14);
      --white: #f0ece4;
      --muted: #7a7a72;
      --red: #e63946;
    }
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body { background: var(--black); color: var(--white); font-family: 'Montserrat', sans-serif; overflow-x: hidden; }

    /* SPLASH */
    #splash { position:fixed;inset:0;z-index:9999;background:var(--black);display:flex;flex-direction:column;align-items:center;justify-content:center;cursor:pointer;transition:opacity 0.7s ease,transform 0.7s ease; }
    #splash.hide { opacity:0;transform:scale(1.05);pointer-events:none; }
    .splash-glow { position:absolute;inset:0;background:radial-gradient(ellipse 60% 45% at 50% 50%,rgba(201,168,76,0.1) 0%,transparent 70%);animation:pulseGlow 2.8s ease-in-out infinite; }
    @keyframes pulseGlow { 0%,100%{opacity:0.5}50%{opacity:1} }
    .splash-logo { font-family:'Bebas Neue',sans-serif;font-size:clamp(5rem,20vw,13rem);letter-spacing:0.1em;color:var(--white);line-height:0.85;text-align:center;position:relative;animation:splashPulse 2.2s ease-in-out infinite; }
    .splash-logo span { color:var(--gold);display:block; }
    @keyframes splashPulse { 0%,100%{transform:scale(1)}50%{transform:scale(1.015)} }
    .splash-rule { width:60px;height:1px;background:var(--gold);margin:1.8rem auto;opacity:0.4; }
    .splash-hint { font-size:0.58rem;font-weight:700;letter-spacing:0.4em;text-transform:uppercase;color:var(--muted);animation:blinkHint 1.8s ease-in-out infinite; }
    @keyframes blinkHint { 0%,100%{opacity:0.3}50%{opacity:1} }
    .splash-timer { position:absolute;bottom:2.5rem;display:flex;align-items:center;gap:1rem; }
    .splash-timer-bar { width:100px;height:1px;background:var(--border2);overflow:hidden; }
    .splash-timer-fill { height:100%;background:var(--gold);animation:fillTimer 15s linear forwards; }
    @keyframes fillTimer { from{width:0%}to{width:100%} }
    .splash-timer-txt { font-size:0.52rem;font-weight:700;letter-spacing:0.22em;text-transform:uppercase;color:var(--muted); }

    /* ONLINE VIEWERS BANNER */
    .viewers-bar { background:#0d0d0d;border-bottom:1px solid var(--border);padding:7px 5%;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:0.5rem; }
    .viewers-live { display:flex;align-items:center;gap:0.5rem;font-size:0.58rem;font-weight:700;letter-spacing:0.18em;text-transform:uppercase;color:var(--muted); }
    .viewers-dot { width:7px;height:7px;border-radius:50%;background:#22c55e;box-shadow:0 0 6px #22c55e;animation:pulseDot 1.4s ease-in-out infinite; }
    @keyframes pulseDot { 0%,100%{opacity:1;transform:scale(1)}50%{opacity:0.6;transform:scale(0.85)} }
    .viewers-count { color:var(--gold);font-size:0.7rem; }
    .viewers-updated { font-size:0.5rem;letter-spacing:0.12em;color:var(--border2); }

    /* PAGES */
    .page { display:none;min-height:100vh;animation:fadeIn 0.4s ease; }
    .page.active { display:block; }
    @keyframes fadeIn { from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:translateY(0)} }

    /* TICKER */
    .ticker-wrap { background:var(--gold);overflow:hidden;padding:8px 0; }
    .ticker-track { display:flex;width:max-content;animation:ticker 35s linear infinite; }
    .ticker-item { font-family:'Bebas Neue',sans-serif;font-size:1rem;letter-spacing:0.28em;color:var(--black);padding:0 2.5rem;white-space:nowrap; }
    @keyframes ticker { 0%{transform:translateX(0)}100%{transform:translateX(-50%)} }

    /* NAV */
    nav { background:rgba(8,8,8,0.98);backdrop-filter:blur(16px);border-bottom:1px solid var(--border);position:sticky;top:0;z-index:99;padding:0 5%;display:flex;align-items:center;justify-content:space-between;height:64px; }
    .nav-logo { font-family:'Bebas Neue',sans-serif;font-size:1.7rem;letter-spacing:0.18em;color:var(--gold);cursor:pointer;flex-shrink:0; }
    .nav-links { display:flex;gap:1.2rem;list-style:none;flex-wrap:nowrap; }
    .nav-links a { font-size:0.58rem;font-weight:700;letter-spacing:0.15em;text-transform:uppercase;color:var(--muted);cursor:pointer;transition:color 0.2s;white-space:nowrap;position:relative;padding-bottom:2px; }
    .nav-links a::after { content:'';position:absolute;bottom:0;left:0;width:0;height:1px;background:var(--gold);transition:width 0.25s; }
    .nav-links a:hover { color:var(--gold); }
    .nav-links a:hover::after { width:100%; }
    .nav-back { display:none;align-items:center;gap:0.5rem;font-size:0.62rem;font-weight:800;letter-spacing:0.2em;text-transform:uppercase;color:var(--black);cursor:pointer;border:none;font-family:'Montserrat',sans-serif;background:var(--gold);padding:0.5rem 1.2rem 0.5rem 0.9rem;transition:background 0.2s,transform 0.2s; }
    .nav-back:hover { background:var(--gold-light);transform:translateY(-1px); }
    .nav-back .back-arrow { animation:arrowBounce 1.5s ease-in-out infinite;display:inline-block; }
    @keyframes arrowBounce { 0%,100%{transform:translateX(0)}50%{transform:translateX(-3px)} }
    .nav-back.show { display:flex; }

    /* HERO */
    .hero { min-height:88vh;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:5rem 5%;position:relative;overflow:hidden; }
    .hero::before { content:'';position:absolute;inset:0;background:radial-gradient(ellipse 75% 55% at 50% 40%,rgba(201,168,76,0.06) 0%,transparent 65%); }
    .hero::after { content:'';position:absolute;bottom:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,var(--border2),transparent); }
    .hero-eyebrow { font-size:0.58rem;font-weight:700;letter-spacing:0.5em;text-transform:uppercase;color:var(--gold);margin-bottom:1.5rem;position:relative;display:inline-flex;align-items:center;gap:1rem; }
    .hero-eyebrow::before,.hero-eyebrow::after { content:'';width:30px;height:1px;background:var(--gold);opacity:0.5; }
    .hero-title { font-family:'Bebas Neue',sans-serif;font-size:clamp(5.5rem,15vw,12rem);line-height:0.85;letter-spacing:0.06em;color:var(--white);position:relative; }
    .hero-title span { color:var(--gold);display:block; }
    .hero-sub { font-family:'Cormorant Garamond',serif;font-size:clamp(1rem,2vw,1.3rem);font-style:italic;color:var(--muted);margin-top:1.5rem;position:relative;letter-spacing:0.04em; }
    .hero-rule { width:1px;height:50px;background:var(--gold);margin:2rem auto;opacity:0.4; }
    .hero-cta { display:inline-flex;gap:1rem;flex-wrap:wrap;justify-content:center;position:relative; }
    .hero-ig-strip { display:flex;gap:1rem;align-items:center;justify-content:center;margin-top:2.5rem;position:relative;flex-wrap:wrap; }
    .hero-ig-card { display:flex;align-items:center;gap:0.8rem;background:rgba(255,255,255,0.03);border:1px solid var(--border);padding:0.65rem 1.1rem 0.65rem 0.65rem;text-decoration:none;transition:border-color 0.25s,background 0.25s,transform 0.25s; }
    .hero-ig-card:hover { border-color:var(--gold);background:var(--gold-dim);transform:translateY(-2px); }
    .hero-ig-avatar { width:36px;height:36px;border-radius:50%;object-fit:cover;border:1.5px solid var(--gold); }
    .hero-ig-handle { font-size:0.7rem;font-weight:700;color:var(--gold);letter-spacing:0.04em;display:block; }
    .hero-ig-label { font-size:0.52rem;font-weight:600;letter-spacing:0.2em;text-transform:uppercase;color:var(--muted);display:block;margin-top:1px; }
    .hero-ig-logo { width:18px;height:18px;flex-shrink:0; }
    .hero-tagline-wrap { margin-top:2.5rem;display:flex;flex-direction:column;align-items:center;gap:0;position:relative; }
    .hero-founders-badge { display:inline-flex;align-items:center;gap:0.5rem;background:rgba(201,168,76,0.04);border:1px solid rgba(201,168,76,0.2);padding:0.5rem 1.5rem;font-size:0.6rem;font-weight:700;letter-spacing:0.25em;text-transform:uppercase;color:var(--muted);position:relative; }
    .hero-founders-badge::before { content:'';position:absolute;left:0;top:0;bottom:0;width:2px;background:var(--gold); }
    .hero-founders-badge em { color:var(--white);font-style:normal; }
    .hero-impossible { font-family:'Bebas Neue',sans-serif;font-size:clamp(1.6rem,4.5vw,3rem);letter-spacing:0.18em;line-height:1;margin-top:0.6rem;background:linear-gradient(90deg,var(--gold) 0%,var(--gold-light) 45%,var(--gold) 100%);background-size:200% 100%;-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;animation:shimmerText 4s ease-in-out infinite; }
    @keyframes shimmerText { 0%{background-position:100% 50%}100%{background-position:-100% 50%} }

    /* BUTTONS */
    .btn-gold { background:var(--gold);color:var(--black);font-size:0.65rem;font-weight:800;letter-spacing:0.25em;text-transform:uppercase;padding:1rem 2.4rem;cursor:pointer;border:none;transition:background 0.2s,transform 0.2s;font-family:'Montserrat',sans-serif;position:relative;overflow:hidden; }
    .btn-gold::before { content:'';position:absolute;inset:0;background:rgba(255,255,255,0.15);transform:translateX(-100%);transition:transform 0.3s; }
    .btn-gold:hover::before { transform:translateX(0); }
    .btn-gold:hover { background:var(--gold-light);transform:translateY(-2px); }
    .btn-outline { border:1px solid rgba(201,168,76,0.5);color:var(--gold);font-size:0.65rem;font-weight:800;letter-spacing:0.25em;text-transform:uppercase;padding:1rem 2.4rem;cursor:pointer;background:none;transition:all 0.2s;font-family:'Montserrat',sans-serif; }
    .btn-outline:hover { background:var(--gold);color:var(--black);border-color:var(--gold);transform:translateY(-2px); }

    /* SECTION */
    .section-label { font-size:0.58rem;font-weight:700;letter-spacing:0.4em;text-transform:uppercase;color:var(--gold);margin-bottom:0.6rem; }
    .section-title { font-family:'Bebas Neue',sans-serif;font-size:clamp(2.5rem,5vw,4.5rem);letter-spacing:0.07em;color:var(--white);line-height:1; }
    .section-divider { width:30px;height:1px;background:var(--gold);margin:1.2rem 0 2.8rem; }

    /* HOME COLLECTION */
    .home-collection { padding:7rem 5%; }
    .collection-header { margin-bottom:3.5rem; }

    /* CATEGORIES GRID — fully responsive */
    .categories-grid {
      display: grid;
      gap: 3px;
      grid-template-columns: 1fr 1fr;
      grid-template-rows: auto;
    }

    /* Sudaderas & Playeras: tall cards */
    .cat-card { position:relative;overflow:hidden;cursor:pointer;background:var(--card); }
    .cat-card-tall { aspect-ratio: 3/4; }

    /* Gorras, Cadenas, Perfumes: shorter */
    .cat-card-short { aspect-ratio: 4/3; }

    /* On desktop: perfumes spans 2 cols */
    .cat-perfumes { grid-column: span 2; }
    /* Override aspect ratio for perfumes desktop */
    @media (min-width: 769px) {
      .cat-perfumes { aspect-ratio: unset; height: 220px; }
    }

    /* On mobile: all single column */
    @media (max-width: 600px) {
      .categories-grid { grid-template-columns: 1fr; }
      .cat-perfumes { grid-column: span 1; height: auto; aspect-ratio: 16/7; }
      .cat-card-tall { aspect-ratio: 4/3; }
      .cat-card-short { aspect-ratio: 16/7; }
    }

    .cat-bg { position:absolute;inset:0;background-size:cover;background-position:center;filter:brightness(0.45);transition:transform 0.8s cubic-bezier(0.25,0.46,0.45,0.94),filter 0.7s ease,opacity 0.6s ease; }
    .cat-card:hover .cat-bg { transform:scale(1.05);filter:brightness(0.3); }
    .cat-overlay { position:absolute;inset:0;background:linear-gradient(0deg,rgba(0,0,0,0.92) 0%,rgba(0,0,0,0.2) 40%,transparent 70%); }
    .cat-info { position:absolute;bottom:0;left:0;right:0;padding:1.4rem 1.5rem;transform:translateY(4px);transition:transform 0.3s; }
    .cat-card:hover .cat-info { transform:translateY(0); }
    .cat-tag { font-size:0.52rem;font-weight:700;letter-spacing:0.3em;text-transform:uppercase;color:var(--gold);margin-bottom:0.4rem; }
    .cat-name { font-family:'Bebas Neue',sans-serif;font-size:clamp(1.8rem,3.5vw,2.8rem);letter-spacing:0.07em;color:var(--white);line-height:1; }
    .cat-cta { display:inline-flex;align-items:center;gap:0.5rem;font-size:0.55rem;font-weight:700;letter-spacing:0.2em;text-transform:uppercase;color:var(--gold);margin-top:0.6rem;opacity:0;transform:translateX(-8px);transition:opacity 0.3s,transform 0.3s; }
    .cat-card:hover .cat-cta { opacity:1;transform:translateX(0); }
    .cat-cta::after { content:'→'; }

    /* PRODUCT PAGE HEADER */
    .product-page-header { padding:4.5rem 5% 3rem;border-bottom:1px solid var(--border); }
    .breadcrumb { font-size:0.58rem;font-weight:700;letter-spacing:0.22em;text-transform:uppercase;color:var(--muted);margin-bottom:1rem;cursor:pointer; }
    .breadcrumb span { color:var(--gold); }
    .products-wrap { padding:4.5rem 5%; }
    .product-grid { display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:2px; }

    /* PRODUCT CARD */
    .product-card { background:var(--card);border:1px solid var(--border);overflow:hidden;transition:border-color 0.3s,transform 0.3s;cursor:pointer; }
    .product-card:hover { border-color:rgba(201,168,76,0.45);transform:translateY(-3px); }
    .product-img-wrap { aspect-ratio:1/1;overflow:hidden;position:relative;background:#131313; }
    .product-img-wrap img { width:100%;height:100%;object-fit:cover;display:block;transition:transform 0.7s cubic-bezier(0.25,0.46,0.45,0.94);filter:brightness(0.95); }
    .product-card:hover .product-img-wrap img { transform:scale(1.04);filter:brightness(1); }
    .product-badge { position:absolute;top:0;left:0;background:var(--gold);color:var(--black);font-size:0.52rem;font-weight:800;letter-spacing:0.2em;text-transform:uppercase;padding:0.3rem 0.8rem; }
    .product-badge-sale { position:absolute;top:0;right:0;background:var(--red);color:#fff;font-size:0.52rem;font-weight:800;letter-spacing:0.12em;text-transform:uppercase;padding:0.3rem 0.8rem; }
    .product-info { padding:1.6rem 1.4rem;border-top:1px solid var(--border); }
    .product-label { font-size:0.55rem;font-weight:700;letter-spacing:0.3em;text-transform:uppercase;color:var(--gold);margin-bottom:0.25rem; }
    .product-name { font-family:'Bebas Neue',sans-serif;font-size:1.6rem;letter-spacing:0.06em;color:var(--white);margin-bottom:0.35rem;line-height:1; }
    .product-color-tag { font-size:0.62rem;font-weight:600;color:var(--muted);margin-bottom:1.1rem;display:flex;align-items:center;gap:0.45rem; }
    .color-dot { width:9px;height:9px;border-radius:50%;border:1px solid var(--border2);flex-shrink:0; }
    .product-price-row { display:flex;align-items:baseline;gap:0.5rem;margin-bottom:0.2rem; }
    .product-price { font-family:'Bebas Neue',sans-serif;font-size:1.9rem;color:var(--gold);letter-spacing:0.04em; }
    .product-price-original { font-family:'Bebas Neue',sans-serif;font-size:1.2rem;color:var(--muted);text-decoration:line-through; }
    .product-price-meta { font-size:0.58rem;font-weight:600;color:var(--muted);letter-spacing:0.1em;margin-bottom:1.1rem; }
    .btn-buy { width:100%;background:transparent;border:1px solid var(--gold);color:var(--gold);font-family:'Montserrat',sans-serif;font-size:0.6rem;font-weight:800;letter-spacing:0.25em;text-transform:uppercase;padding:0.85rem;cursor:pointer;transition:background 0.2s,color 0.2s;margin-top:0.2rem; }
    .btn-buy:hover { background:var(--gold);color:var(--black); }
    .btn-view-detail { width:100%;background:rgba(255,255,255,0.02);border:1px solid var(--border2);color:var(--muted);font-family:'Montserrat',sans-serif;font-size:0.58rem;font-weight:700;letter-spacing:0.2em;text-transform:uppercase;padding:0.65rem;cursor:pointer;transition:all 0.2s;margin-top:0.5rem; }
    .btn-view-detail:hover { border-color:var(--gold);color:var(--gold);background:var(--gold-dim); }

    /* DETAIL PAGE */
    .detail-wrap { display:grid;grid-template-columns:1fr 1fr;gap:5rem;padding:5rem 5%;align-items:start; }
    .detail-gallery { position:sticky;top:88px; }
    .detail-main-img { aspect-ratio:1/1;background:#0e0e0e;border:1px solid var(--border);overflow:hidden;margin-bottom:0.8rem; }
    .detail-main-img img { width:100%;height:100%;object-fit:cover;display:block;transition:opacity 0.3s; }
    .detail-thumbs { display:flex;gap:0.5rem;flex-wrap:wrap; }
    .detail-thumb { width:68px;height:68px;border:1px solid var(--border);overflow:hidden;cursor:pointer;transition:border-color 0.2s,transform 0.2s;background:#0e0e0e; }
    .detail-thumb:hover,.detail-thumb.active { border-color:var(--gold);transform:translateY(-2px); }
    .detail-thumb img { width:100%;height:100%;object-fit:cover;display:block; }
    .detail-info { padding-top:0.5rem; }
    .detail-label { font-size:0.56rem;font-weight:700;letter-spacing:0.35em;text-transform:uppercase;color:var(--gold);margin-bottom:0.5rem; }
    .detail-name { font-family:'Bebas Neue',sans-serif;font-size:clamp(2.5rem,5vw,3.8rem);letter-spacing:0.05em;color:var(--white);line-height:0.92;margin-bottom:0.8rem; }
    .detail-price-wrap { margin-bottom:0.3rem; }
    .detail-price { font-family:'Bebas Neue',sans-serif;font-size:2.8rem;color:var(--gold);letter-spacing:0.04em;display:inline; }
    .detail-price-original { font-family:'Bebas Neue',sans-serif;font-size:1.6rem;color:var(--muted);text-decoration:line-through;margin-right:0.5rem; }
    .detail-price-meta { font-size:0.6rem;font-weight:600;color:var(--muted);letter-spacing:0.12em;margin-bottom:0.4rem; }
    .detail-divider { height:1px;background:var(--border);margin:1.8rem 0; }
    .detail-section-title { font-size:0.58rem;font-weight:700;letter-spacing:0.3em;text-transform:uppercase;color:var(--muted);margin-bottom:0.9rem; }
    .color-selector { display:flex;gap:0.7rem;flex-wrap:wrap;margin-bottom:1.6rem; }
    .color-btn { display:flex;flex-direction:column;align-items:center;gap:0.3rem;cursor:pointer;border:none;background:none;padding:0; }
    .color-swatch { width:34px;height:34px;border-radius:50%;border:2px solid var(--border);transition:border-color 0.2s,transform 0.2s;position:relative; }
    .color-btn:hover .color-swatch,.color-btn.active .color-swatch { border-color:var(--gold);transform:scale(1.1); }
    .color-btn.active .color-swatch::after { content:'✓';position:absolute;inset:0;display:flex;align-items:center;justify-content:center;font-size:0.75rem;color:var(--gold);font-weight:900; }
    .color-btn span { font-size:0.52rem;font-weight:700;letter-spacing:0.12em;text-transform:uppercase;color:var(--muted); }
    .color-btn.active span { color:var(--gold); }
    .size-selector { display:flex;gap:0.5rem;flex-wrap:wrap;margin-bottom:1.6rem; }
    .size-btn { min-width:44px;height:44px;border:1px solid var(--border);background:transparent;color:var(--muted);font-family:'Montserrat',sans-serif;font-size:0.68rem;font-weight:700;letter-spacing:0.08em;cursor:pointer;transition:all 0.2s;padding:0 0.6rem; }
    .size-btn:hover { border-color:var(--gold);color:var(--gold); }
    .size-btn.active { border-color:var(--gold);background:var(--gold);color:var(--black); }

    .size-required-msg { display:none;align-items:center;gap:0.5rem;font-size:0.65rem;font-weight:800;letter-spacing:0.15em;text-transform:uppercase;color:#fff;background:var(--red);padding:0.7rem 1rem;margin-bottom:0.8rem;border-left:3px solid #fff;animation:fadeInMsg 0.3s ease; }
    .size-required-msg.show { display:flex; }
    @keyframes fadeInMsg { from{opacity:0;transform:translateY(-4px)}to{opacity:1;transform:translateY(0)} }

    .btn-buy-lg { background:var(--gold);color:var(--black);font-family:'Montserrat',sans-serif;font-size:0.68rem;font-weight:800;letter-spacing:0.25em;text-transform:uppercase;padding:1.15rem 2rem;cursor:pointer;border:none;transition:background 0.2s,transform 0.2s,opacity 0.2s;width:100%;position:relative;overflow:hidden; }
    .btn-buy-lg::before { content:'';position:absolute;inset:0;background:rgba(255,255,255,0.15);transform:translateX(-100%);transition:transform 0.3s; }
    .btn-buy-lg:hover:not(:disabled)::before { transform:translateX(0); }
    .btn-buy-lg:hover:not(:disabled) { background:var(--gold-light);transform:translateY(-2px); }
    .btn-buy-lg:disabled { background:#2a2a2a;color:var(--muted);cursor:not-allowed;transform:none;border:1px solid var(--border2); }

    .detail-note { font-size:0.6rem;color:var(--muted);margin-top:0.8rem;line-height:1.7; }

    /* LOCATION BADGE in detail */
    .location-badge { display:flex;align-items:center;gap:0.5rem;background:rgba(201,168,76,0.06);border:1px solid rgba(201,168,76,0.2);padding:0.5rem 0.9rem;margin-top:0.8rem;font-size:0.6rem;color:var(--muted);font-weight:600;letter-spacing:0.1em; }
    .location-badge span { color:var(--gold); }

    /* Specs */
    .specs-table { width:100%;border-collapse:collapse;margin-bottom:1.5rem; }
    .specs-table tr { border-bottom:1px solid var(--border); }
    .specs-table td { padding:0.7rem 0;font-size:0.72rem; }
    .specs-table td:first-child { color:var(--muted);font-weight:600;letter-spacing:0.08em;width:44%; }
    .specs-table td:last-child { color:var(--white);font-weight:500; }

    /* COMING SOON */
    .cs-fullpage { min-height:60vh;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:4rem 5%;position:relative;overflow:hidden; }
    .cs-fullpage::before { content:'';position:absolute;inset:0;background:radial-gradient(ellipse 55% 45% at 50% 50%,rgba(201,168,76,0.07) 0%,transparent 70%); }
    .cs-prox-label { font-size:0.68rem;font-weight:700;letter-spacing:0.42em;text-transform:uppercase;color:var(--gold);border:1px solid rgba(201,168,76,0.5);padding:0.5rem 1.4rem;margin-bottom:1.5rem;position:relative;background:rgba(201,168,76,0.06); }
    .cs-prox-title { font-family:'Bebas Neue',sans-serif;font-size:clamp(4rem,14vw,11rem);letter-spacing:0.04em;line-height:0.85;color:var(--white);position:relative;margin-bottom:1.5rem;text-shadow:0 0 60px rgba(201,168,76,0.15); }
    .cs-prox-title .cs-prox-filled { display:block;color:var(--gold); }
    .cs-icon-big { font-size:3rem;margin-bottom:1rem;position:relative;filter:drop-shadow(0 0 20px rgba(201,168,76,0.3)); }
    .cs-prox-sub { font-family:'Cormorant Garamond',serif;font-size:clamp(0.9rem,2vw,1.1rem);font-style:italic;color:var(--white);max-width:400px;line-height:1.85;margin-bottom:1.8rem;position:relative;opacity:0.8; }
    .cs-prox-ig { display:flex;gap:0.8rem;flex-wrap:wrap;justify-content:center;position:relative; }
    .cs-prox-ig a { display:inline-flex;align-items:center;gap:0.5rem;border:1px solid rgba(201,168,76,0.5);padding:0.65rem 1.4rem;font-size:0.65rem;font-weight:700;letter-spacing:0.15em;text-transform:uppercase;color:var(--gold);text-decoration:none;transition:border-color 0.2s,background 0.2s,transform 0.2s;background:rgba(201,168,76,0.04); }
    .cs-prox-ig a:hover { border-color:var(--gold);background:var(--gold-dim);transform:translateY(-2px); }
    .cs-ig-logo { width:16px;height:16px; }

    /* CONTACT */
    .contact-section { padding:7rem 5%;border-top:1px solid var(--border); }
    .contact-grid { display:grid;grid-template-columns:1fr 1fr;gap:4rem;margin-top:3.5rem; }
    .contact-block h3 { font-family:'Bebas Neue',sans-serif;font-size:1.5rem;letter-spacing:0.08em;color:var(--gold);margin-bottom:1.5rem; }
    .contact-person-card { display:flex;align-items:center;gap:1.1rem;background:var(--card2);border:1px solid var(--border);padding:1.1rem 1.2rem;margin-bottom:0.8rem;transition:border-color 0.25s,background 0.25s; }
    .contact-person-card:hover { border-color:rgba(201,168,76,0.4);background:rgba(201,168,76,0.03); }
    .contact-avatar { width:52px;height:52px;border-radius:50%;object-fit:cover;border:1.5px solid var(--gold);flex-shrink:0; }
    .contact-person-info { flex:1; }
    .c-label { font-size:0.52rem;font-weight:700;letter-spacing:0.25em;text-transform:uppercase;color:var(--muted);margin-bottom:0.2rem; }
    .c-name { font-size:0.88rem;font-weight:700;color:var(--white);margin-bottom:0.4rem; }
    .contact-actions { display:flex;gap:0.5rem;flex-wrap:wrap; }
    .btn-wa { display:inline-flex;align-items:center;gap:0.35rem;background:#25d366;color:#fff;font-family:'Montserrat',sans-serif;font-size:0.55rem;font-weight:800;letter-spacing:0.15em;text-transform:uppercase;padding:0.4rem 0.85rem;text-decoration:none;border:none;cursor:pointer;transition:background 0.2s,transform 0.2s; }
    .btn-wa:hover { background:#1ebe5a;transform:translateY(-1px); }
    .btn-ig { display:inline-flex;align-items:center;gap:0.35rem;background:transparent;color:var(--gold);font-family:'Montserrat',sans-serif;font-size:0.55rem;font-weight:800;letter-spacing:0.15em;text-transform:uppercase;padding:0.4rem 0.85rem;text-decoration:none;border:1px solid rgba(201,168,76,0.4);cursor:pointer;transition:all 0.2s; }
    .btn-ig:hover { background:var(--gold);color:var(--black);border-color:var(--gold);transform:translateY(-1px); }
    .btn-ig-logo { width:13px;height:13px; }
    .contact-msg { background:var(--card2);border:1px solid var(--border);padding:2.5rem; }
    .contact-msg p { font-family:'Cormorant Garamond',serif;font-size:1rem;font-style:italic;color:var(--muted);line-height:2; }
    .contact-msg strong { color:var(--white);font-style:normal;font-family:'Montserrat',sans-serif;font-size:0.82rem;font-weight:700; }

    /* FOOTER */
    footer { border-top:1px solid var(--border);padding:2.5rem 5%;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:1rem; }
    .footer-logo { font-family:'Bebas Neue',sans-serif;font-size:1.4rem;letter-spacing:0.18em;color:var(--gold); }
    .footer-copy { font-size:0.58rem;color:var(--muted);letter-spacing:0.12em; }

    /* MODAL */
    .modal-overlay { position:fixed;inset:0;background:rgba(0,0,0,0.92);backdrop-filter:blur(8px);z-index:1000;display:flex;align-items:center;justify-content:center;opacity:0;pointer-events:none;transition:opacity 0.25s;padding:1rem; }
    .modal-overlay.active { opacity:1;pointer-events:all; }
    .modal-box { background:var(--card);border:1px solid rgba(201,168,76,0.3);padding:2.5rem 2rem;text-align:center;max-width:460px;width:100%;transform:translateY(16px);transition:transform 0.25s;max-height:90vh;overflow-y:auto; }
    .modal-overlay.active .modal-box { transform:translateY(0); }
    .modal-rule { width:30px;height:1px;background:var(--gold);margin:0 auto 1rem; }
    .modal-title { font-family:'Bebas Neue',sans-serif;font-size:2.4rem;color:var(--gold);letter-spacing:0.12em;margin-bottom:0.5rem; }
    .modal-sub { font-size:0.72rem;color:var(--muted);line-height:1.8;margin-bottom:1.2rem; }
    .modal-product-info { background:rgba(201,168,76,0.06);border:1px solid rgba(201,168,76,0.25);padding:0.9rem 1.2rem;margin-bottom:1rem;text-align:left; }
    .modal-product-info-title { font-size:0.52rem;font-weight:800;letter-spacing:0.28em;text-transform:uppercase;color:var(--gold);display:block;margin-bottom:0.5rem; }
    .modal-product-info p { font-size:0.72rem;color:var(--white);line-height:1.7;font-weight:500; }
    .modal-product-info span.highlight { color:var(--gold);font-weight:700; }
    .modal-location-info { background:rgba(34,197,94,0.05);border:1px solid rgba(34,197,94,0.2);padding:0.8rem 1.2rem;margin-bottom:1rem;text-align:left; }
    .modal-location-title { font-size:0.52rem;font-weight:800;letter-spacing:0.28em;text-transform:uppercase;color:#22c55e;display:block;margin-bottom:0.4rem; }
    .modal-location-info p { font-size:0.68rem;color:var(--white);line-height:1.8;font-weight:500; }
    .modal-location-info span { color:#22c55e;font-weight:700; }
    .modal-pay-info { background:rgba(201,168,76,0.04);border:1px solid rgba(201,168,76,0.18);padding:1rem 1.3rem;margin-bottom:1.5rem;text-align:left; }
    .modal-pay-title { font-size:0.55rem;font-weight:800;letter-spacing:0.28em;text-transform:uppercase;color:var(--gold);display:block;margin-bottom:0.6rem; }
    .modal-pay-info p { font-size:0.68rem;color:var(--white);line-height:1.9;font-weight:500; }
    .modal-pay-info span { color:var(--gold);font-weight:700; }
    .modal-wa-btns { display:flex;flex-direction:column;gap:0.6rem;margin-bottom:1rem; }
    .modal-wa-btn { display:flex;align-items:center;justify-content:center;gap:0.6rem;background:#25d366;color:#fff;border:none;font-family:'Montserrat',sans-serif;font-size:0.65rem;font-weight:800;letter-spacing:0.18em;text-transform:uppercase;padding:0.9rem 1.5rem;text-decoration:none;cursor:pointer;transition:background 0.2s; }
    .modal-wa-btn:hover { background:#1ebe5a; }
    .modal-close { background:transparent;color:var(--muted);border:1px solid var(--border2);font-family:'Montserrat',sans-serif;font-size:0.6rem;font-weight:700;letter-spacing:0.22em;text-transform:uppercase;padding:0.7rem 1.8rem;cursor:pointer;transition:all 0.2s; }
    .modal-close:hover { background:var(--gold);color:var(--black);border-color:var(--gold); }

    /* RESPONSIVE */
    @media (max-width:768px) {
      .contact-grid { grid-template-columns:1fr;gap:2.5rem; }
      .nav-links { gap:0.7rem; }
      .nav-links a { font-size:0.5rem; }
      .hero { padding:4rem 5%;min-height:80vh; }
      .home-collection,.contact-section { padding:4rem 5%; }
      .product-page-header { padding:2.5rem 5% 2rem; }
      .products-wrap { padding:2.5rem 5%; }
      .product-grid { grid-template-columns:1fr 1fr;gap:2px; }
      .detail-wrap { grid-template-columns:1fr;gap:2.5rem; }
      .detail-gallery { position:static; }
    }
    @media (max-width:540px) {
      nav { padding:0 4%;height:58px; }
      .nav-logo { font-size:1.35rem; }
      .nav-links { display:none; }
      .product-grid { grid-template-columns:1fr 1fr; }
    }
    @media (max-width:380px) {
      .product-grid { grid-template-columns:1fr; }
    }
  </style>
</head>
<body>

<div id="splash" onclick="dismissSplash()">
  <div class="splash-glow"></div>
  <div class="splash-logo">GC<span>HATS</span></div>
  <div class="splash-rule"></div>
  <div class="splash-hint">Toca para entrar</div>
  <div class="splash-timer">
    <div class="splash-timer-bar"><div class="splash-timer-fill"></div></div>
    <div class="splash-timer-txt">Auto en 15s</div>
  </div>
</div>

<!-- ONLINE VIEWERS -->
<div class="viewers-bar">
  <div class="viewers-live">
    <div class="viewers-dot"></div>
    <span class="viewers-count" id="viewersCount">—</span>&nbsp;personas viendo ahora
  </div>
  <div class="viewers-updated" id="viewersUpdated">Actualizando...</div>
</div>

<div class="ticker-wrap">
  <div class="ticker-track">
    <span class="ticker-item">GC_HATS</span><span class="ticker-item">★ STREETWEAR PREMIUM</span>
    <span class="ticker-item">GC_HATS</span><span class="ticker-item">★ SUDADERAS · PLAYERAS · GORRAS · CADENAS · PERFUMES</span>
    <span class="ticker-item">GC_HATS</span><span class="ticker-item">★ ESSENTIALS COLLECTION 2026</span>
    <span class="ticker-item">GC_HATS</span><span class="ticker-item">★ STREETWEAR PREMIUM</span>
    <span class="ticker-item">GC_HATS</span><span class="ticker-item">★ SUDADERAS · PLAYERAS · GORRAS · CADENAS · PERFUMES</span>
    <span class="ticker-item">GC_HATS</span><span class="ticker-item">★ ESSENTIALS COLLECTION 2026</span>
  </div>
</div>

<nav>
  <span class="nav-logo" onclick="goHome()">GC_HATS</span>
  <ul class="nav-links" id="navLinks">
    <li><a onclick="goPage('sudaderas')">Sudaderas</a></li>
    <li><a onclick="goPage('playeras')">Playeras</a></li>
    <li><a onclick="goPage('gorras')">Gorras</a></li>
    <li><a onclick="goPage('cadenas')">Cadenas</a></li>
    <li><a onclick="goPage('perfumes')">Perfumes</a></li>
    <li><a onclick="goSection('contacto')">Contacto</a></li>
  </ul>
  <button class="nav-back" id="navBack" onclick="navBackAction()">
    <span class="back-arrow">←</span> <span id="navBackLabel">Volver</span>
  </button>
</nav>

<!-- HOME -->
<div class="page active" id="pageHome">
  <section class="hero">
    <div class="hero-eyebrow">Essentials Collection 2026</div>
    <h1 class="hero-title">GC<span>HATS</span></h1>
    <p class="hero-sub">Streetwear premium para quienes se atreven a destacar</p>
    <div class="hero-rule"></div>
    <div class="hero-cta">
      <button class="btn-gold" onclick="goPage('sudaderas')">Ver Colección</button>
      <button class="btn-outline" onclick="goSection('contacto')">Contacto</button>
    </div>
    <div class="hero-ig-strip">
      <a class="hero-ig-card" href="https://www.instagram.com/xz.jxhan/" target="_blank" rel="noopener noreferrer">
        <img class="hero-ig-avatar" src="https://i.imgur.com/Bc3UbT7.jpeg" alt="Johan"/>
        <div>
          <span class="hero-ig-handle" style="display:flex;align-items:center;gap:5px;">
            <img src="https://i.imgur.com/127mFXO.jpeg" class="hero-ig-logo" alt="IG" onerror="this.style.display='none'"/>
            @xz.jxhan
          </span>
          <span class="hero-ig-label">Johan · Fundador</span>
        </div>
      </a>
      <a class="hero-ig-card" href="https://www.instagram.com/elian_ec10" target="_blank" rel="noopener noreferrer">
        <img class="hero-ig-avatar" src="https://i.imgur.com/dnjT4tI.jpeg" alt="Elian"/>
        <div>
          <span class="hero-ig-handle" style="display:flex;align-items:center;gap:5px;">
            <img src="https://i.imgur.com/127mFXO.jpeg" class="hero-ig-logo" alt="IG" onerror="this.style.display='none'"/>
            @elian_ec10
          </span>
          <span class="hero-ig-label">Elian · Fundador</span>
        </div>
      </a>
    </div>
    <div class="hero-tagline-wrap">
      <div class="hero-founders-badge"><em>Emprendedores</em>&nbsp;y&nbsp;<em>revendedores</em>&nbsp;a nuestros&nbsp;<em>16 años</em></div>
      <div class="hero-impossible">— NADA ES IMPOSIBLE —</div>
    </div>
  </section>

  <section class="home-collection">
    <div class="collection-header">
      <div class="section-label">Nuestras Categorías</div>
      <h2 class="section-title">Explora el Catálogo</h2>
      <div class="section-divider"></div>
    </div>
    <div class="categories-grid">
      <!-- Sudaderas -->
      <div class="cat-card cat-card-tall" onclick="goPage('sudaderas')">
        <div class="cat-bg" id="bgSud" style="background-image:url('https://i.imgur.com/llepWFZ.png')"></div>
        <div class="cat-overlay"></div>
        <div class="cat-info"><div class="cat-tag">Essentials · ANTI Social Club</div><div class="cat-name">Sudaderas</div><div class="cat-cta">Ver colección</div></div>
      </div>
      <!-- Playeras -->
      <div class="cat-card cat-card-tall" onclick="goPage('playeras')">
        <div class="cat-bg" id="bgPla" style="background-image:url('https://i.imgur.com/PGWj3hx.png')"></div>
        <div class="cat-overlay"></div>
        <div class="cat-info"><div class="cat-tag">Essentials · Hellstar · AllSaints</div><div class="cat-name">Playeras</div><div class="cat-cta">Ver colección</div></div>
      </div>
      <!-- Gorras -->
      <div class="cat-card cat-card-short" onclick="goPage('gorras')">
        <div class="cat-bg" style="background-image:url('https://i.imgur.com/Y5qPDQ5.jpeg')"></div>
        <div class="cat-overlay"></div>
        <div class="cat-info"><div class="cat-tag">Próximamente</div><div class="cat-name">Gorras</div><div class="cat-cta">Ver más</div></div>
      </div>
      <!-- Cadenas -->
      <div class="cat-card cat-card-short" onclick="goPage('cadenas')">
        <div class="cat-bg" style="background-image:url('https://i.imgur.com/Y5qPDQ5.jpeg')"></div>
        <div class="cat-overlay"></div>
        <div class="cat-info"><div class="cat-tag">Próximamente</div><div class="cat-name">Cadenas</div><div class="cat-cta">Ver más</div></div>
      </div>
      <!-- Perfumes — spans full width, smaller height -->
      <div class="cat-card cat-perfumes" onclick="goPage('perfumes')">
        <div class="cat-bg" style="background-image:url('https://i.imgur.com/Y5qPDQ5.jpeg')"></div>
        <div class="cat-overlay"></div>
        <div class="cat-info"><div class="cat-tag">Próximamente</div><div class="cat-name">Perfumes</div><div class="cat-cta">Ver más</div></div>
      </div>
    </div>
  </section>

  <section class="contact-section" id="contacto">
    <div class="section-label">Comunicación Directa</div>
    <h2 class="section-title">Contacto</h2>
    <div class="section-divider"></div>
    <div class="contact-grid">
      <div class="contact-block">
        <h3>Nuestros Canales</h3>
        <div class="contact-person-card">
          <img class="contact-avatar" src="https://i.imgur.com/Bc3UbT7.jpeg" alt="Johan"/>
          <div class="contact-person-info">
            <div class="c-label">Fundador</div>
            <div class="c-name">Johan</div>
            <div class="contact-actions">
              <a class="btn-wa" href="https://wa.me/525636011176?text=Hola%20Johan%2C%20vi%20el%20cat%C3%A1logo%20de%20GC_HATS%20y%20me%20interesa%20un%20producto." target="_blank" rel="noopener noreferrer">💬 WhatsApp</a>
              <a class="btn-ig" href="https://www.instagram.com/xz.jxhan/" target="_blank" rel="noopener noreferrer">
                <img src="https://i.imgur.com/127mFXO.jpeg" class="btn-ig-logo" alt="IG" onerror="this.style.display='none'"/>
                @xz.jxhan
              </a>
            </div>
          </div>
        </div>
        <div class="contact-person-card">
          <img class="contact-avatar" src="https://i.imgur.com/dnjT4tI.jpeg" alt="Elian"/>
          <div class="contact-person-info">
            <div class="c-label">Fundador</div>
            <div class="c-name">Elian</div>
            <div class="contact-actions">
              <a class="btn-wa" href="https://wa.me/525548290940?text=Hola%20Elian%2C%20vi%20el%20cat%C3%A1logo%20de%20GC_HATS%20y%20me%20interesa%20un%20producto." target="_blank" rel="noopener noreferrer">💬 WhatsApp</a>
              <a class="btn-ig" href="https://www.instagram.com/elian_ec10" target="_blank" rel="noopener noreferrer">
                <img src="https://i.imgur.com/127mFXO.jpeg" class="btn-ig-logo" alt="IG" onerror="this.style.display='none'"/>
                @elian_ec10
              </a>
            </div>
          </div>
        </div>
      </div>
      <div>
        <div class="contact-msg">
          <p>
            <strong>Estimado cliente,</strong><br/><br/>
            En <strong>GC_HATS</strong> nos comprometemos a brindarle la mejor atención. Para dudas sobre disponibilidad, tallas, métodos de pago o envíos, contáctenos directamente por <strong>WhatsApp</strong>.<br/><br/>
            Síguenos en Instagram para conocer <strong>nuevos lanzamientos, promociones exclusivas y novedades</strong> de la marca.<br/><br/>
            <em>Gracias por elegirnos. — Johan &amp; Elian, GC_HATS</em>
          </p>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="footer-logo">GC_HATS</div>
    <div class="footer-copy">© 2026 GC_HATS — Streetwear Premium. Todos los derechos reservados.</div>
  </footer>
</div>

<!-- SUDADERAS -->
<div class="page" id="pageSudaderas">
  <div class="product-page-header">
    <div class="breadcrumb" onclick="goHome()"><span>Inicio</span> <span>/ Sudaderas</span></div>
    <div class="section-label">Categoría</div>
    <h2 class="section-title">Sudaderas</h2>
    <div class="section-divider"></div>
    <p style="font-size:0.75rem;color:var(--muted);max-width:480px;line-height:1.8;">Colección Essentials y modelos exclusivos — materiales premium para el máximo confort y estilo.</p>
  </div>
  <div class="products-wrap">
    <div class="product-grid">
      <div class="product-card" onclick="openDetail('sud-blanca')">
        <div class="product-img-wrap">
          <img src="https://i.imgur.com/llepWFZ.png" alt="Sudadera Blanca" loading="lazy"/>
          <span class="product-badge">Disponible</span>
        </div>
        <div class="product-info">
          <div class="product-label">Essentials</div>
          <div class="product-name">Sudadera Blanca</div>
          <div class="product-color-tag"><span class="color-dot" style="background:#f5f5f5;border-color:#ccc;"></span>Color: Blanco</div>
          <div class="product-price-row"><span class="product-price">$1,000</span></div>
          <div class="product-price-meta">MXN · IVA incluido</div>
          <button class="btn-buy" onclick="event.stopPropagation();openDetail('sud-blanca')">Comprar ahora</button>
          <button class="btn-view-detail" onclick="event.stopPropagation();openDetail('sud-blanca')">Ver detalles →</button>
        </div>
      </div>
      <div class="product-card" onclick="openDetail('sud-negra')">
        <div class="product-img-wrap">
          <img src="https://i.imgur.com/APvuGAL.png" alt="Sudadera Negra" loading="lazy"/>
          <span class="product-badge">Disponible</span>
        </div>
        <div class="product-info">
          <div class="product-label">Essentials</div>
          <div class="product-name">Sudadera Negra</div>
          <div class="product-color-tag"><span class="color-dot" style="background:#111;"></span>Color: Negro</div>
          <div class="product-price-row"><span class="product-price">$1,000</span></div>
          <div class="product-price-meta">MXN · IVA incluido</div>
          <button class="btn-buy" onclick="event.stopPropagation();openDetail('sud-negra')">Comprar ahora</button>
          <button class="btn-view-detail" onclick="event.stopPropagation();openDetail('sud-negra')">Ver detalles →</button>
        </div>
      </div>
      <div class="product-card" onclick="openDetail('sud-gris')">
        <div class="product-img-wrap">
          <img src="https://i.imgur.com/jqoYUGn.png" alt="Sudadera Gris" loading="lazy"/>
          <span class="product-badge">Disponible</span>
        </div>
        <div class="product-info">
          <div class="product-label">Essentials</div>
          <div class="product-name">Sudadera Gris</div>
          <div class="product-color-tag"><span class="color-dot" style="background:#888;"></span>Color: Gris</div>
          <div class="product-price-row"><span class="product-price">$1,000</span></div>
          <div class="product-price-meta">MXN · IVA incluido</div>
          <button class="btn-buy" onclick="event.stopPropagation();openDetail('sud-gris')">Comprar ahora</button>
          <button class="btn-view-detail" onclick="event.stopPropagation();openDetail('sud-gris')">Ver detalles →</button>
        </div>
      </div>
      <div class="product-card" onclick="openDetail('sud-ati')">
        <div class="product-img-wrap">
          <img src="https://i.imgur.com/wvvKLtw.png" alt="ANTI Social Club Rico O M Hoodie" loading="lazy"/>
          <span class="product-badge" style="background:#0e0e0e;color:var(--gold);border-right:1px solid var(--border);border-bottom:1px solid var(--border);">Nuevo</span>
          <span class="product-badge-sale">% Oferta</span>
        </div>
        <div class="product-info">
          <div class="product-label">ANTI Social Club</div>
          <div class="product-name">Rico O M Hoodie</div>
          <div class="product-color-tag"><span class="color-dot" style="background:#111;"></span>Color: Negro</div>
          <div class="product-price-row"><span class="product-price-original">$1,500</span><span class="product-price">$1,200</span></div>
          <div class="product-price-meta">MXN · IVA incluido</div>
          <button class="btn-buy" onclick="event.stopPropagation();openDetail('sud-ati')">Comprar ahora</button>
          <button class="btn-view-detail" onclick="event.stopPropagation();openDetail('sud-ati')">Ver detalles →</button>
        </div>
      </div>
    </div>
  </div>
  <footer><div class="footer-logo">GC_HATS</div><div class="footer-copy">© 2026 GC_HATS — Streetwear Premium.</div></footer>
</div>

<!-- PLAYERAS -->
<div class="page" id="pagePlayeras">
  <div class="product-page-header">
    <div class="breadcrumb" onclick="goHome()"><span>Inicio</span> <span>/ Playeras</span></div>
    <div class="section-label">Categoría</div>
    <h2 class="section-title">Playeras</h2>
    <div class="section-divider"></div>
    <p style="font-size:0.75rem;color:var(--muted);max-width:480px;line-height:1.8;">Colección Essentials y modelos exclusivos — 100% algodón premium con identidad GC impresa en alta definición.</p>
  </div>
  <div class="products-wrap">
    <div class="product-grid">
      <div class="product-card" onclick="openDetail('pla-blanca')">
        <div class="product-img-wrap">
          <img src="https://i.imgur.com/PGWj3hx.png" alt="Playera Blanca" loading="lazy"/>
          <span class="product-badge">Disponible</span>
        </div>
        <div class="product-info">
          <div class="product-label">Essentials</div>
          <div class="product-name">Playera Blanca</div>
          <div class="product-color-tag"><span class="color-dot" style="background:#f5f5f5;border-color:#ccc;"></span>Color: Blanco</div>
          <div class="product-price-row"><span class="product-price">$1,000</span></div>
          <div class="product-price-meta">MXN · IVA incluido</div>
          <button class="btn-buy" onclick="event.stopPropagation();openDetail('pla-blanca')">Comprar ahora</button>
          <button class="btn-view-detail" onclick="event.stopPropagation();openDetail('pla-blanca')">Ver detalles →</button>
        </div>
      </div>
      <div class="product-card" onclick="openDetail('pla-negra')">
        <div class="product-img-wrap">
          <img src="https://i.imgur.com/wOnSb29.png" alt="Playera Negra" loading="lazy"/>
          <span class="product-badge">Disponible</span>
        </div>
        <div class="product-info">
          <div class="product-label">Essentials</div>
          <div class="product-name">Playera Negra</div>
          <div class="product-color-tag"><span class="color-dot" style="background:#111;"></span>Color: Negro</div>
          <div class="product-price-row"><span class="product-price">$1,000</span></div>
          <div class="product-price-meta">MXN · IVA incluido</div>
          <button class="btn-buy" onclick="event.stopPropagation();openDetail('pla-negra')">Comprar ahora</button>
          <button class="btn-view-detail" onclick="event.stopPropagation();openDetail('pla-negra')">Ver detalles →</button>
        </div>
      </div>
      <div class="product-card" onclick="openDetail('pla-gris')">
        <div class="product-img-wrap">
          <img src="https://i.imgur.com/p4rc2mU.png" alt="Playera Gris" loading="lazy"/>
          <span class="product-badge">Disponible</span>
        </div>
        <div class="product-info">
          <div class="product-label">Essentials</div>
          <div class="product-name">Playera Gris</div>
          <div class="product-color-tag"><span class="color-dot" style="background:#888;"></span>Color: Gris</div>
          <div class="product-price-row"><span class="product-price">$1,000</span></div>
          <div class="product-price-meta">MXN · IVA incluido</div>
          <button class="btn-buy" onclick="event.stopPropagation();openDetail('pla-gris')">Comprar ahora</button>
          <button class="btn-view-detail" onclick="event.stopPropagation();openDetail('pla-gris')">Ver detalles →</button>
        </div>
      </div>
      <div class="product-card" onclick="openDetail('pla-hellstar')">
        <div class="product-img-wrap">
          <img src="https://i.imgur.com/cWh30eg.png" alt="Hellstar" loading="lazy"/>
          <span class="product-badge" style="background:#0e0e0e;color:var(--gold);border-right:1px solid var(--border);border-bottom:1px solid var(--border);">Nuevo</span>
          <span class="product-badge-sale">% Oferta</span>
        </div>
        <div class="product-info">
          <div class="product-label">Hellstar</div>
          <div class="product-name">Hellstar</div>
          <div class="product-color-tag"><span class="color-dot" style="background:#111;"></span>Color: Negro</div>
          <div class="product-price-row"><span class="product-price-original">$1,200</span><span class="product-price">$1,000</span></div>
          <div class="product-price-meta">MXN · IVA incluido</div>
          <button class="btn-buy" onclick="event.stopPropagation();openDetail('pla-hellstar')">Comprar ahora</button>
          <button class="btn-view-detail" onclick="event.stopPropagation();openDetail('pla-hellstar')">Ver detalles →</button>
        </div>
      </div>
      <div class="product-card" onclick="openDetail('pla-allsaints')">
        <div class="product-img-wrap">
          <img src="https://i.imgur.com/dNtKag5.png" alt="AllSaints" loading="lazy"/>
          <span class="product-badge" style="background:#0e0e0e;color:var(--gold);border-right:1px solid var(--border);border-bottom:1px solid var(--border);">Nuevo</span>
          <span class="product-badge-sale">% Oferta</span>
        </div>
        <div class="product-info">
          <div class="product-label">AllSaints</div>
          <div class="product-name">AllSaints</div>
          <div class="product-color-tag"><span class="color-dot" style="background:#1a1a1a;"></span>Color: Negro</div>
          <div class="product-price-row"><span class="product-price-original">$1,200</span><span class="product-price">$1,000</span></div>
          <div class="product-price-meta">MXN · IVA incluido</div>
          <button class="btn-buy" onclick="event.stopPropagation();openDetail('pla-allsaints')">Comprar ahora</button>
          <button class="btn-view-detail" onclick="event.stopPropagation();openDetail('pla-allsaints')">Ver detalles →</button>
        </div>
      </div>
    </div>
  </div>
  <footer><div class="footer-logo">GC_HATS</div><div class="footer-copy">© 2026 GC_HATS — Streetwear Premium.</div></footer>
</div>

<!-- GORRAS -->
<div class="page" id="pageGorras">
  <div class="product-page-header">
    <div class="breadcrumb" onclick="goHome()"><span>Inicio</span> <span>/ Gorras</span></div>
    <div class="section-label">Próximos Lanzamientos</div>
    <h2 class="section-title">Gorras</h2>
    <div class="section-divider"></div>
  </div>
  <div class="cs-fullpage">
    <div class="cs-icon-big">🧢</div>
    <div class="cs-prox-label">✦ Nueva Categoría ✦</div>
    <div class="cs-prox-title"><span class="cs-prox-filled">PRÓXI</span>MAMENTE</div>
    <p class="cs-prox-sub">Estamos trabajando en una colección exclusiva de gorras GC_HATS. Diseños únicos e inéditos llegarán muy pronto.</p>
    <div class="cs-prox-ig">
      <a href="https://www.instagram.com/xz.jxhan/" target="_blank" rel="noopener noreferrer">
        <img src="https://i.imgur.com/127mFXO.jpeg" class="cs-ig-logo" alt="IG" onerror="this.style.display='none'"/> @xz.jxhan
      </a>
      <a href="https://www.instagram.com/elian_ec10" target="_blank" rel="noopener noreferrer">
        <img src="https://i.imgur.com/127mFXO.jpeg" class="cs-ig-logo" alt="IG" onerror="this.style.display='none'"/> @elian_ec10
      </a>
    </div>
  </div>
  <footer><div class="footer-logo">GC_HATS</div><div class="footer-copy">© 2026 GC_HATS.</div></footer>
</div>

<!-- CADENAS -->
<div class="page" id="pageCadenas">
  <div class="product-page-header">
    <div class="breadcrumb" onclick="goHome()"><span>Inicio</span> <span>/ Cadenas</span></div>
    <div class="section-label">Próximos Lanzamientos</div>
    <h2 class="section-title">Cadenas</h2>
    <div class="section-divider"></div>
  </div>
  <div class="cs-fullpage">
    <div class="cs-icon-big">⛓️</div>
    <div class="cs-prox-label">✦ Nueva Línea ✦</div>
    <div class="cs-prox-title"><span class="cs-prox-filled">PRÓXI</span>MAMENTE</div>
    <p class="cs-prox-sub">Próximamente dispondremos de una línea de cadenas premium GC_HATS.</p>
    <div class="cs-prox-ig">
      <a href="https://www.instagram.com/xz.jxhan/" target="_blank" rel="noopener noreferrer">
        <img src="https://i.imgur.com/127mFXO.jpeg" class="cs-ig-logo" alt="IG" onerror="this.style.display='none'"/> @xz.jxhan
      </a>
      <a href="https://www.instagram.com/elian_ec10" target="_blank" rel="noopener noreferrer">
        <img src="https://i.imgur.com/127mFXO.jpeg" class="cs-ig-logo" alt="IG" onerror="this.style.display='none'"/> @elian_ec10
      </a>
    </div>
  </div>
  <footer><div class="footer-logo">GC_HATS</div><div class="footer-copy">© 2026 GC_HATS.</div></footer>
</div>

<!-- PERFUMES -->
<div class="page" id="pagePerfumes">
  <div class="product-page-header">
    <div class="breadcrumb" onclick="goHome()"><span>Inicio</span> <span>/ Perfumes</span></div>
    <div class="section-label">Próximos Lanzamientos</div>
    <h2 class="section-title">Perfumes</h2>
    <div class="section-divider"></div>
  </div>
  <div class="cs-fullpage">
    <div class="cs-icon-big">🌹</div>
    <div class="cs-prox-label">✦ Nueva Fragancia ✦</div>
    <div class="cs-prox-title"><span class="cs-prox-filled">PRÓXI</span>MAMENTE</div>
    <p class="cs-prox-sub">Estamos desarrollando una línea de fragancias exclusivas GC_HATS. Aromas únicos que complementan tu estilo.</p>
    <div class="cs-prox-ig">
      <a href="https://www.instagram.com/xz.jxhan/" target="_blank" rel="noopener noreferrer">
        <img src="https://i.imgur.com/127mFXO.jpeg" class="cs-ig-logo" alt="IG" onerror="this.style.display='none'"/> @xz.jxhan
      </a>
      <a href="https://www.instagram.com/elian_ec10" target="_blank" rel="noopener noreferrer">
        <img src="https://i.imgur.com/127mFXO.jpeg" class="cs-ig-logo" alt="IG" onerror="this.style.display='none'"/> @elian_ec10
      </a>
    </div>
  </div>
  <footer><div class="footer-logo">GC_HATS</div><div class="footer-copy">© 2026 GC_HATS.</div></footer>
</div>

<!-- DETAIL -->
<div class="page" id="pageDetail">
  <div class="product-page-header">
    <div class="breadcrumb" id="detailBreadcrumb" onclick="goBackFromDetail()">
      <span>Inicio</span> <span id="detailBreadcrumbCat">/ Sudaderas</span> <span id="detailBreadcrumbName">/ Producto</span>
    </div>
    <div class="section-label" id="detailLabel"></div>
    <h2 class="section-title" id="detailTitle">Producto</h2>
    <div class="section-divider"></div>
  </div>
  <div class="detail-wrap">
    <div class="detail-gallery">
      <div class="detail-main-img"><img id="detailMainImg" src="" alt="Producto"/></div>
      <div class="detail-thumbs" id="detailThumbs"></div>
    </div>
    <div class="detail-info">
      <div class="detail-label" id="detailInfoLabel">—</div>
      <div class="detail-name" id="detailInfoName">—</div>
      <div id="detailPriceWrap" class="detail-price-wrap"></div>
      <div class="detail-price-meta" id="detailPriceMeta">MXN · IVA incluido</div>
      <div class="detail-divider"></div>
      <div id="detailColorBlock">
        <div class="detail-section-title">Color</div>
        <div class="color-selector" id="detailColorSelector"></div>
      </div>
      <div class="detail-section-title">Talla <span id="tallaSelectorHint" style="color:var(--red);font-size:0.55rem;letter-spacing:0.1em;font-weight:800;margin-left:0.5rem;display:none;">← Selecciona una talla</span></div>
      <div class="size-selector" id="detailSizeSelector"></div>
      <div class="size-required-msg" id="sizeRequiredMsg">⚠️ Debes elegir una talla para continuar</div>
      <div class="detail-divider"></div>
      <div class="detail-section-title">Especificaciones</div>
      <table class="specs-table" id="detailSpecs"></table>
      <div class="detail-divider"></div>
      <!-- Location badge -->
      <div class="location-badge" id="locationBadge">
        📍 Ubicación: <span id="locationText">Solicitando permiso...</span>
      </div>
      <div class="detail-actions" style="margin-top:1rem;">
        <button class="btn-buy-lg" id="detailBuyBtn" onclick="openModalFromDetail()" disabled>
          💬 Selecciona una talla para comprar
        </button>
      </div>
      <p class="detail-note">Las compras se realizan directamente con nuestros fundadores vía WhatsApp. Tu ubicación se usa para calcular el costo de envío.</p>
    </div>
  </div>
  <footer><div class="footer-logo">GC_HATS</div><div class="footer-copy">© 2026 GC_HATS — Streetwear Premium.</div></footer>
</div>

<!-- MODAL -->
<div class="modal-overlay" id="modalOverlay" onclick="closeModalOutside(event)">
  <div class="modal-box">
    <div class="modal-rule"></div>
    <div class="modal-title">Contáctanos</div>
    <p class="modal-sub">Escríbenos por <strong style="color:#25d366">WhatsApp</strong> para adquirir este producto:</p>
    <div class="modal-product-info" id="modalProductInfo" style="display:none;">
      <span class="modal-product-info-title">🛍️ Tu selección</span>
      <p id="modalProductText"></p>
    </div>
    <div class="modal-location-info" id="modalLocationInfo">
      <span class="modal-location-title">📍 Tu ubicación (para envío)</span>
      <p id="modalLocationText">Detectando...</p>
    </div>
    <div class="modal-pay-info">
      <span class="modal-pay-title">📋 Información de compra</span>
      <p>
        <span>✅ Se aceptan transferencias</span><br/>
        <span>🚚 Envíos a todo México</span> — <em style="font-size:0.62rem;color:var(--muted);">el precio varía según el estado</em><br/>
        <span>🤝 Entrega personal:</span> Naucalpan · CBachilleres 5 · Satélite
      </p>
    </div>
    <div class="modal-wa-btns">
      <a class="modal-wa-btn" id="modalBtnJohan" href="#" target="_blank" rel="noopener noreferrer">💬 WhatsApp — Johan</a>
      <a class="modal-wa-btn" id="modalBtnElian" href="#" target="_blank" rel="noopener noreferrer">💬 WhatsApp — Elian</a>
    </div>
    <button class="modal-close" onclick="closeModal()">Cerrar</button>
  </div>
</div>

<script>
// ── PRODUCTS DATA ────────────────────────────────────────────────
var PRODUCTS = {
  'sud-blanca': { category:'sudaderas', categoryName:'Sudaderas', name:'Sudadera Blanca', label:'Essentials Collection 2022', isEssentials:true, images:['https://i.imgur.com/llepWFZ.png','https://i.imgur.com/M0EqOS6.png'], colorKey:'blanca', priceDisplay:'$1,000', priceOriginal:null, sizes:['XS','S','M','L','XL'], specs:[['Tipo','Sudadera con capucha'],['Colección','Essentials 2022'],['Material','80% Algodón / 20% Poliéster'],['Estampado','Serigrafía premium GC'],['Ajuste','Regular fit'],['Cuidado','Lavar a máx. 30°C'],['Tallas','XS · S · M · L · XL'],['Envío','CDMX y República Mexicana']] },
  'sud-negra':  { category:'sudaderas', categoryName:'Sudaderas', name:'Sudadera Negra',  label:'Essentials Collection 2022', isEssentials:true, images:['https://i.imgur.com/APvuGAL.png','https://i.imgur.com/R2dJB3b.png'], colorKey:'negra', priceDisplay:'$1,000', priceOriginal:null, sizes:['XS','S','M','L','XL'], specs:[['Tipo','Sudadera con capucha'],['Colección','Essentials 2022'],['Material','80% Algodón / 20% Poliéster'],['Estampado','Serigrafía premium GC'],['Ajuste','Regular fit'],['Cuidado','Lavar a máx. 30°C'],['Tallas','XS · S · M · L · XL'],['Envío','CDMX y República Mexicana']] },
  'sud-gris':   { category:'sudaderas', categoryName:'Sudaderas', name:'Sudadera Gris',   label:'Essentials Collection 2022', isEssentials:true, images:['https://i.imgur.com/jqoYUGn.png','https://i.imgur.com/C7hsDDW.png'], colorKey:'gris',  priceDisplay:'$1,000', priceOriginal:null, sizes:['XS','S','M','L','XL'], specs:[['Tipo','Sudadera con capucha'],['Colección','Essentials 2022'],['Material','80% Algodón / 20% Poliéster'],['Estampado','Serigrafía premium GC'],['Ajuste','Regular fit'],['Cuidado','Lavar a máx. 30°C'],['Tallas','XS · S · M · L · XL'],['Envío','CDMX y República Mexicana']] },
  'sud-ati':    { category:'sudaderas', categoryName:'Sudaderas', name:'ANTI Social Club Rico O M Hoodie', label:'ANTI Social Club', isEssentials:false, images:['https://i.imgur.com/wvvKLtw.png','https://i.imgur.com/CsOCYKn.png'], colorKey:null, priceDisplay:'$1,200', priceOriginal:'$1,500', sizes:['S','M','G','EXG'], specs:[['Tipo','Hoodie / Sudadera'],['Colección','ANTI Social Club'],['Color','Negro'],['Ajuste','Oversize fit'],['Tallas','S · M · G · EXG'],['Envío','CDMX y República Mexicana']] },
  'pla-blanca': { category:'playeras',  categoryName:'Playeras',  name:'Playera Blanca',  label:'Essentials Collection 2022', isEssentials:true, images:['https://i.imgur.com/PGWj3hx.png','https://i.imgur.com/kCpErs6.png'], colorKey:'blanca', priceDisplay:'$1,000', priceOriginal:null, sizes:['XS','S','M','L','XL'], specs:[['Tipo','Playera cuello redondo'],['Colección','Essentials 2022'],['Material','100% Algodón ring-spun'],['Estampado','Serigrafía premium GC'],['Ajuste','Regular / Oversize fit'],['Cuidado','Lavar a máx. 30°C'],['Tallas','XS · S · M · L · XL'],['Envío','CDMX y República Mexicana']] },
  'pla-negra':  { category:'playeras',  categoryName:'Playeras',  name:'Playera Negra',   label:'Essentials Collection 2022', isEssentials:true, images:['https://i.imgur.com/wOnSb29.png','https://i.imgur.com/L3Edwaw.png'], colorKey:'negra', priceDisplay:'$1,000', priceOriginal:null, sizes:['XS','S','M','L','XL'], specs:[['Tipo','Playera cuello redondo'],['Colección','Essentials 2022'],['Material','100% Algodón ring-spun'],['Estampado','Serigrafía premium GC'],['Ajuste','Regular / Oversize fit'],['Cuidado','Lavar a máx. 30°C'],['Tallas','XS · S · M · L · XL'],['Envío','CDMX y República Mexicana']] },
  'pla-gris':   { category:'playeras',  categoryName:'Playeras',  name:'Playera Gris',    label:'Essentials Collection 2022', isEssentials:true, images:['https://i.imgur.com/p4rc2mU.png','https://i.imgur.com/z9Dot37.png'], colorKey:'gris',  priceDisplay:'$1,000', priceOriginal:null, sizes:['XS','S','M','L','XL'], specs:[['Tipo','Playera cuello redondo'],['Colección','Essentials 2022'],['Material','100% Algodón ring-spun'],['Estampado','Serigrafía premium GC'],['Ajuste','Regular / Oversize fit'],['Cuidado','Lavar a máx. 30°C'],['Tallas','XS · S · M · L · XL'],['Envío','CDMX y República Mexicana']] },
  'pla-hellstar':  { category:'playeras', categoryName:'Playeras', name:'Playera Hellstar',  label:'Hellstar',   isEssentials:false, images:['https://i.imgur.com/cWh30eg.png','https://i.imgur.com/lwVvUk0.png'], colorKey:null, priceDisplay:'$1,000', priceOriginal:'$1,200', sizes:['S','M','G','EXG'],    specs:[['Tipo','Playera'],['Colección','Hellstar'],['Color','Negro'],['Tallas','S · M · G · EXG'],['Envío','CDMX y República Mexicana']] },
  'pla-allsaints': { category:'playeras', categoryName:'Playeras', name:'Playera AllSaints', label:'AllSaints', isEssentials:false, images:['https://i.imgur.com/dNtKag5.png','https://i.imgur.com/vStoHr4.png'], colorKey:null, priceDisplay:'$1,000', priceOriginal:'$1,200', sizes:['XS','S','M','G','EXG'], specs:[['Tipo','Playera'],['Colección','AllSaints'],['Color','Negro'],['Tallas','XS · S · M · G · EXG'],['Envío','CDMX y República Mexicana']] }
};

var COLOR_VARIANTS = {
  sudaderas: [
    { key:'sud-blanca', label:'Blanco', swatch:'#f0ede3', border:'#ccc' },
    { key:'sud-negra',  label:'Negro',  swatch:'#111',    border:'#444' },
    { key:'sud-gris',   label:'Gris',   swatch:'#888',    border:'#666' }
  ],
  playeras: [
    { key:'pla-blanca', label:'Blanco', swatch:'#f0ede3', border:'#ccc' },
    { key:'pla-negra',  label:'Negro',  swatch:'#111',    border:'#444' },
    { key:'pla-gris',   label:'Gris',   swatch:'#888',    border:'#666' }
  ]
};

// ── ONLINE VIEWERS (simulated, updates every 30s) ──────────────
var viewerBase = Math.floor(Math.random() * 6) + 3; // 3-8 base
function updateViewers() {
  var jitter = Math.floor(Math.random() * 5) - 2;
  var count = Math.max(1, viewerBase + jitter);
  document.getElementById('viewersCount').textContent = count;
  var now = new Date();
  var h = now.getHours().toString().padStart(2,'0');
  var m = now.getMinutes().toString().padStart(2,'0');
  var s = now.getSeconds().toString().padStart(2,'0');
  document.getElementById('viewersUpdated').textContent = 'Actualizado: ' + h + ':' + m + ':' + s;
}
updateViewers();
setInterval(function() {
  // Drift base slightly over time for realism
  viewerBase = Math.max(1, viewerBase + (Math.random() > 0.5 ? 1 : -1));
  updateViewers();
}, 30000);

// ── GEOLOCATION ─────────────────────────────────────────────────
var userLocation = null; // { city, state, country, lat, lon }

function requestLocation() {
  var locText = document.getElementById('locationText');
  if (!navigator.geolocation) {
    if (locText) locText.textContent = 'No disponible en tu navegador';
    return;
  }
  navigator.geolocation.getCurrentPosition(
    function(pos) {
      var lat = pos.coords.latitude.toFixed(4);
      var lon = pos.coords.longitude.toFixed(4);
      // Reverse geocode using open API
      fetch('https://nominatim.openstreetmap.org/reverse?format=json&lat=' + lat + '&lon=' + lon + '&accept-language=es')
        .then(function(r){ return r.json(); })
        .then(function(data) {
          var addr = data.address || {};
          var city   = addr.city || addr.town || addr.village || addr.municipality || '';
          var state  = addr.state || '';
          var country= addr.country || 'México';
          userLocation = { city: city, state: state, country: country, lat: lat, lon: lon };
          var label = [city, state].filter(Boolean).join(', ') || country;
          if (locText) locText.textContent = label;
        })
        .catch(function() {
          userLocation = { city: '', state: '', country: 'México', lat: lat, lon: lon };
          if (locText) locText.textContent = 'Lat ' + lat + ', Lon ' + lon;
        });
    },
    function(err) {
      if (locText) locText.textContent = 'Permiso denegado — se pedirá al comprar';
    },
    { timeout: 8000 }
  );
}

function getLocationString() {
  if (!userLocation) return null;
  if (userLocation.city && userLocation.state) return userLocation.city + ', ' + userLocation.state;
  if (userLocation.state) return userLocation.state;
  if (userLocation.city) return userLocation.city;
  return userLocation.country || 'México';
}

// ── SPLASH ──────────────────────────────────────────────────────
var splashTimer = setTimeout(dismissSplash, 15000);
function dismissSplash() {
  var s = document.getElementById('splash');
  s.classList.add('hide');
  clearTimeout(splashTimer);
  setTimeout(function(){ s.style.display = 'none'; }, 720);
  // Request location after splash
  setTimeout(requestLocation, 800);
}

// ── CATEGORY BG ROTATOR ─────────────────────────────────────────
function startRotator(id, imgs) {
  var el = document.getElementById(id); if (!el) return; var i = 0;
  setInterval(function() {
    i = (i + 1) % imgs.length;
    el.style.opacity = '0';
    setTimeout(function(){ el.style.backgroundImage = "url('" + imgs[i] + "')"; el.style.opacity = '1'; }, 600);
  }, 3500);
}
startRotator('bgSud', ['https://i.imgur.com/llepWFZ.png','https://i.imgur.com/APvuGAL.png','https://i.imgur.com/jqoYUGn.png','https://i.imgur.com/wvvKLtw.png']);
startRotator('bgPla', ['https://i.imgur.com/PGWj3hx.png','https://i.imgur.com/wOnSb29.png','https://i.imgur.com/p4rc2mU.png','https://i.imgur.com/cWh30eg.png']);

// ── NAVIGATION ──────────────────────────────────────────────────
var PAGE_MAP = { home:'pageHome', sudaderas:'pageSudaderas', playeras:'pagePlayeras', gorras:'pageGorras', cadenas:'pageCadenas', perfumes:'pagePerfumes', detail:'pageDetail' };
var currentPage = 'home', prevPage = 'home';

function showPage(key) {
  Object.values(PAGE_MAP).forEach(function(id){ document.getElementById(id).classList.remove('active'); });
  document.getElementById(PAGE_MAP[key]).classList.add('active');
  window.scrollTo({ top:0, behavior:'smooth' });
  currentPage = key;
  var back = document.getElementById('navBack'), links = document.getElementById('navLinks'), lbl = document.getElementById('navBackLabel');
  if (key === 'home') { back.classList.remove('show'); links.style.display = 'flex'; }
  else if (key === 'detail') { back.classList.add('show'); links.style.display = 'none'; lbl.textContent = 'Volver'; }
  else { back.classList.add('show'); links.style.display = 'none'; lbl.textContent = 'Inicio'; }
}
function goHome() { prevPage = 'home'; showPage('home'); }
function goPage(k) { prevPage = k; showPage(k); history.pushState({ page:k }, '', '#'+k); }
function goSection(id) { goHome(); setTimeout(function(){ var el = document.getElementById(id); if (el) el.scrollIntoView({ behavior:'smooth' }); }, 120); }
function navBackAction() { if (currentPage === 'detail') { showPage(prevPage !== 'detail' ? prevPage : 'home'); } else { goHome(); } }
function goBackFromDetail() { var p = PRODUCTS[currentDetailKey]; if (p) showPage(p.category); else goHome(); }
window.addEventListener('popstate', function(e){ if (e.state && e.state.page) showPage(e.state.page); else goHome(); });

// ── DETAIL PAGE ─────────────────────────────────────────────────
var currentDetailKey = '';
var selectedSize = '';

function updateBuyButton() {
  var btn = document.getElementById('detailBuyBtn');
  var hint = document.getElementById('tallaSelectorHint');
  if (selectedSize) {
    btn.disabled = false;
    btn.textContent = '💬 Comprar por WhatsApp';
    if (hint) hint.style.display = 'none';
  } else {
    btn.disabled = true;
    btn.textContent = '💬 Selecciona una talla para comprar';
    if (hint) hint.style.display = 'inline';
  }
}

function openDetail(key) {
  var p = PRODUCTS[key]; if (!p) return;
  currentDetailKey = key;
  selectedSize = '';
  prevPage = p.category;

  document.getElementById('detailBreadcrumbCat').textContent  = '/ ' + p.categoryName;
  document.getElementById('detailBreadcrumbName').textContent = '/ ' + p.name;
  document.getElementById('detailTitle').textContent    = p.name;
  document.getElementById('detailInfoLabel').textContent = p.label;
  document.getElementById('detailInfoName').textContent  = p.name;

  var dlEl = document.getElementById('detailLabel');
  dlEl.textContent = p.isEssentials ? 'Essentials Collection 2022' : '';
  dlEl.style.display = p.isEssentials ? 'block' : 'none';

  var pw = document.getElementById('detailPriceWrap');
  if (p.priceOriginal) {
    pw.innerHTML = '<span class="detail-price-original">' + p.priceOriginal + '</span><span class="detail-price" style="color:var(--red);">' + p.priceDisplay + '</span>';
    document.getElementById('detailPriceMeta').innerHTML = 'MXN · IVA incluido &nbsp;<span style="font-size:0.58rem;font-weight:800;color:var(--red);letter-spacing:0.12em;">OFERTA</span>';
  } else {
    pw.innerHTML = '<span class="detail-price">' + p.priceDisplay + '</span>';
    document.getElementById('detailPriceMeta').textContent = 'MXN · IVA incluido';
  }

  // Gallery
  var mainImg = document.getElementById('detailMainImg');
  mainImg.src = p.images[0]; mainImg.alt = p.name;
  var thumbsWrap = document.getElementById('detailThumbs'); thumbsWrap.innerHTML = '';
  p.images.forEach(function(src, idx) {
    var div = document.createElement('div');
    div.className = 'detail-thumb' + (idx === 0 ? ' active' : '');
    var img = document.createElement('img'); img.src = src; img.alt = p.name;
    div.appendChild(img);
    div.addEventListener('click', function() {
      mainImg.style.opacity = '0';
      setTimeout(function(){ mainImg.src = src; mainImg.style.opacity = '1'; }, 180);
      document.querySelectorAll('.detail-thumb').forEach(function(t){ t.classList.remove('active'); });
      div.classList.add('active');
    });
    thumbsWrap.appendChild(div);
  });

  // Color selector
  var colorBlock = document.getElementById('detailColorBlock');
  var colorWrap  = document.getElementById('detailColorSelector'); colorWrap.innerHTML = '';
  var variants = (p.colorKey && COLOR_VARIANTS[p.category]) ? COLOR_VARIANTS[p.category] : [];
  colorBlock.style.display = variants.length ? 'block' : 'none';
  variants.forEach(function(v) {
    var btn = document.createElement('button');
    btn.className = 'color-btn' + (v.key === key ? ' active' : '');
    btn.innerHTML = '<div class="color-swatch" style="background:' + v.swatch + ';border-color:' + v.border + ';"></div><span>' + v.label + '</span>';
    btn.addEventListener('click', function(){ openDetail(v.key); });
    colorWrap.appendChild(btn);
  });

  // Size selector
  var sw = document.getElementById('detailSizeSelector'); sw.innerHTML = '';
  document.getElementById('sizeRequiredMsg').classList.remove('show');
  p.sizes.forEach(function(sz) {
    var btn = document.createElement('button');
    btn.className = 'size-btn';
    btn.textContent = sz;
    btn.addEventListener('click', function(){ selectSize(btn, sz); });
    sw.appendChild(btn);
  });

  // Specs
  var st = document.getElementById('detailSpecs'); st.innerHTML = '';
  p.specs.forEach(function(row) {
    var tr = document.createElement('tr');
    tr.innerHTML = '<td>' + row[0] + '</td><td>' + row[1] + '</td>';
    st.appendChild(tr);
  });

  // Update location badge
  var locText = document.getElementById('locationText');
  if (locText) {
    var ls = getLocationString();
    locText.textContent = ls || 'Solicitando permiso...';
    if (!ls && navigator.geolocation) requestLocation();
  }

  updateBuyButton();
  showPage('detail');
  history.pushState({ page:'detail', key:key }, '', '#detail-' + key);
}

function selectSize(el, sz) {
  document.querySelectorAll('.size-btn').forEach(function(b){ b.classList.remove('active'); });
  el.classList.add('active');
  selectedSize = sz;
  document.getElementById('sizeRequiredMsg').classList.remove('show');
  updateBuyButton();
}

// ── WHATSAPP MESSAGE BUILDER ────────────────────────────────────
function buildWAMessage(productKey, size) {
  var p = PRODUCTS[productKey];
  if (!p) return { johan: 'https://wa.me/525636011176', elian: 'https://wa.me/525548290940' };

  var locStr = getLocationString();
  var locationLine = locStr
    ? 'Soy de: ' + locStr
    : 'Soy de el Estado de: (Escribe tu estado y ciudad)';

  var msg =
    '¡Hola! Vi el catálogo de *GC_HATS* y quiero comprar lo siguiente:\n\n' +
    '🛍️ *Producto:* ' + p.name + '\n' +
    '🏷️ *Colección:* ' + p.label + '\n' +
    '📐 *Talla:* ' + size + '\n' +
    '💰 *Precio:* ' + p.priceDisplay + ' MXN\n' +
    '📍 *' + locationLine + '*\n\n' +
    '¿Está disponible? ¿Cómo procedo con el pago?';

  return {
    johan: 'https://wa.me/525636011176?text=' + encodeURIComponent(msg),
    elian: 'https://wa.me/525548290940?text=' + encodeURIComponent(msg)
  };
}

// ── MODAL ───────────────────────────────────────────────────────
function openModalFromDetail() {
  if (!selectedSize) {
    document.getElementById('sizeRequiredMsg').classList.add('show');
    document.getElementById('detailSizeSelector').scrollIntoView({ behavior:'smooth', block:'center' });
    return;
  }
  var p = PRODUCTS[currentDetailKey];
  if (!p) return;

  // Show product info in modal
  var infoEl = document.getElementById('modalProductInfo');
  var textEl = document.getElementById('modalProductText');
  infoEl.style.display = 'block';
  textEl.innerHTML =
    'Modelo: <span class="highlight">' + p.name + '</span><br/>' +
    'Colección: <span class="highlight">' + p.label + '</span><br/>' +
    'Talla: <span class="highlight">' + selectedSize + '</span><br/>' +
    'Precio: <span class="highlight">' + p.priceDisplay + ' MXN</span>';

  // Location in modal
  var locStr = getLocationString();
  var modalLocText = document.getElementById('modalLocationText');
  if (locStr) {
    modalLocText.innerHTML = 'Ubicación detectada: <span>' + locStr + '</span><br/><em style="font-size:0.6rem;color:var(--muted);">Se incluirá en el mensaje de WhatsApp para calcular tu envío.</em>';
  } else {
    modalLocText.innerHTML = 'Permiso denegado o no disponible.<br/><em style="font-size:0.6rem;color:var(--muted);">Por favor escribe tu ciudad/estado en el mensaje de WhatsApp.</em>';
  }

  var urls = buildWAMessage(currentDetailKey, selectedSize);
  document.getElementById('modalBtnJohan').href = urls.johan;
  document.getElementById('modalBtnElian').href = urls.elian;

  document.getElementById('modalOverlay').classList.add('active');
  document.body.style.overflow = 'hidden';
}

function closeModal() { document.getElementById('modalOverlay').classList.remove('active'); document.body.style.overflow = ''; }
function closeModalOutside(e) { if (e.target === document.getElementById('modalOverlay')) closeModal(); }

// Shake animation
var shakeStyle = document.createElement('style');
shakeStyle.textContent = '@keyframes shakeSizes{0%{transform:translateX(0)}20%{transform:translateX(-6px)}40%{transform:translateX(6px)}60%{transform:translateX(-4px)}80%{transform:translateX(4px)}100%{transform:translateX(0)}}';
document.head.appendChild(shakeStyle);
</script>
</body>
</html>
