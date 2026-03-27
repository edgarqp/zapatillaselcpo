[index (1).html](https://github.com/user-attachments/files/26293673/index.1.html)
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>El Capo | Zapatillas Masculinas Premium – Cusco, Perú</title>
  <meta name="description" content="El Capo – Zapatillas de calidad peruana para el hombre que sabe lo que quiere. Envíos en Cusco. Paga con Yape o efectivo." />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Barlow+Condensed:wght@400;600;700&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet" />

  <style>
    /* ============================================================
       VARIABLES & RESET
    ============================================================ */
    :root {
      --black:   #080808;
      --carbon:  #111111;
      --panel:   #171717;
      --border:  #222222;
      --gold:    #C9A84C;
      --gold-lt: #e0c070;
      --red:     #B5251B;
      --white:   #FFFFFF;
      --gray:    #AAAAAA;
      --gray-lt: #CCCCCC;

      --font-display: 'Bebas Neue', sans-serif;
      --font-head:    'Barlow Condensed', sans-serif;
      --font-body:    'DM Sans', sans-serif;

      --radius: 6px;
      --transition: 0.28s cubic-bezier(0.4,0,0.2,1);
      --shadow: 0 8px 40px rgba(0,0,0,0.6);
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; font-size: 16px; }

    body {
      background: var(--black);
      color: var(--white);
      font-family: var(--font-body);
      line-height: 1.6;
      overflow-x: hidden;
    }

    a { text-decoration: none; color: inherit; }
    ul { list-style: none; }
    img { display: block; max-width: 100%; }

    /* ============================================================
       UTILITIES
    ============================================================ */
    .container { max-width: 1200px; margin: 0 auto; padding: 0 24px; }
    .section { padding: 96px 0; }
    .section-sm { padding: 64px 0; }

    .label {
      display: inline-block;
      font-family: var(--font-head);
      font-size: 12px;
      font-weight: 700;
      letter-spacing: 4px;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 16px;
    }

    h1, h2, h3 { font-family: var(--font-display); line-height: 1.05; }
    h1 { font-size: clamp(56px, 10vw, 120px); }
    h2 { font-size: clamp(36px, 6vw, 72px); }
    h3 { font-size: clamp(22px, 3vw, 32px); }

    /* Scroll animations */
    .reveal {
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.7s ease, transform 0.7s ease;
    }
    .reveal.visible { opacity: 1; transform: translateY(0); }
    .reveal-delay-1 { transition-delay: 0.1s; }
    .reveal-delay-2 { transition-delay: 0.2s; }
    .reveal-delay-3 { transition-delay: 0.3s; }
    .reveal-delay-4 { transition-delay: 0.4s; }

    /* Divider */
    .gold-line {
      width: 60px;
      height: 3px;
      background: var(--gold);
      margin: 20px auto 40px;
    }
    .gold-line.left { margin-left: 0; }

    /* ============================================================
       BUTTONS
    ============================================================ */
    .btn {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      font-family: var(--font-head);
      font-weight: 700;
      font-size: 15px;
      letter-spacing: 2px;
      text-transform: uppercase;
      padding: 14px 32px;
      border-radius: var(--radius);
      border: none;
      cursor: pointer;
      transition: var(--transition);
    }
    .btn-gold {
      background: var(--gold);
      color: var(--black);
    }
    .btn-gold:hover {
      background: var(--red);
      color: var(--white);
      transform: translateY(-2px);
      box-shadow: 0 6px 24px rgba(181,37,27,0.45);
    }
    .btn-outline {
      background: transparent;
      color: var(--white);
      border: 2px solid rgba(255,255,255,0.35);
    }
    .btn-outline:hover {
      border-color: var(--gold);
      color: var(--gold);
      transform: translateY(-2px);
    }
    .btn-sm {
      font-size: 13px;
      padding: 10px 22px;
      letter-spacing: 1.5px;
    }

    /* WhatsApp icon inline SVG replacement */
    .icon-wa::before {
      content: "";
      display: inline-block;
      width: 20px;
      height: 20px;
      background: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='%23000'%3E%3Cpath d='M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z'/%3E%3C/svg%3E") center/contain no-repeat;
    }
    .btn-gold .icon-wa::before { background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='%23080808'%3E%3Cpath d='M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z'/%3E%3C/svg%3E"); }
    .btn-outline .icon-wa::before { background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='%23C9A84C'%3E%3Cpath d='M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z'/%3E%3C/svg%3E"); }

    /* ============================================================
       NAVBAR
    ============================================================ */
    #navbar {
      position: fixed;
      top: 0; left: 0; right: 0;
      z-index: 1000;
      padding: 0;
      transition: background var(--transition), box-shadow var(--transition);
    }
    #navbar.scrolled {
      background: rgba(8,8,8,0.97);
      backdrop-filter: blur(12px);
      box-shadow: 0 1px 0 rgba(201,168,76,0.2);
    }
    .nav-inner {
      display: flex;
      align-items: center;
      justify-content: space-between;
      height: 72px;
    }
    .nav-logo {
      font-family: var(--font-display);
      font-size: 28px;
      letter-spacing: 3px;
      color: var(--white);
      user-select: none;
    }
    .nav-logo span { color: var(--gold); }

    .nav-links {
      display: flex;
      gap: 36px;
    }
    .nav-links a {
      font-family: var(--font-head);
      font-size: 14px;
      font-weight: 600;
      letter-spacing: 2px;
      text-transform: uppercase;
      color: var(--gray-lt);
      transition: color var(--transition);
    }
    .nav-links a:hover { color: var(--gold); }

    .nav-cta { }

    /* Hamburger */
    .hamburger {
      display: none;
      flex-direction: column;
      gap: 5px;
      cursor: pointer;
      padding: 4px;
      background: none;
      border: none;
    }
    .hamburger span {
      display: block;
      width: 26px;
      height: 2px;
      background: var(--white);
      transition: var(--transition);
    }
    .hamburger.open span:nth-child(1) { transform: translateY(7px) rotate(45deg); }
    .hamburger.open span:nth-child(2) { opacity: 0; }
    .hamburger.open span:nth-child(3) { transform: translateY(-7px) rotate(-45deg); }

    .mobile-menu {
      display: none;
      flex-direction: column;
      gap: 0;
      background: rgba(11,11,11,0.98);
      border-top: 1px solid var(--border);
      padding: 20px 24px 32px;
    }
    .mobile-menu.open { display: flex; }
    .mobile-menu a {
      font-family: var(--font-head);
      font-size: 20px;
      font-weight: 700;
      letter-spacing: 2px;
      text-transform: uppercase;
      color: var(--gray-lt);
      padding: 14px 0;
      border-bottom: 1px solid var(--border);
      transition: color var(--transition);
    }
    .mobile-menu a:hover { color: var(--gold); }
    .mobile-menu .btn { margin-top: 20px; width: 100%; justify-content: center; }

    /* ============================================================
       HERO
    ============================================================ */
    #inicio {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      padding-bottom: 80px;
      position: relative;
      overflow: hidden;
    }

    /* 
      REEMPLAZA AQUÍ: background de hero
      Usa una imagen real de zapatillas: background-image: url('images/hero-bg.jpg');
    */
    .hero-bg {
      position: absolute;
      inset: 0;
      background:
        radial-gradient(ellipse 80% 60% at 70% 40%, rgba(201,168,76,0.07) 0%, transparent 60%),
        radial-gradient(ellipse 60% 80% at 20% 80%, rgba(181,37,27,0.06) 0%, transparent 60%),
        linear-gradient(160deg, #0e0e0e 0%, #080808 50%, #0e0a04 100%);
    }

    /* Geometric accent — andean-inspired diagonal lines */
    .hero-bg::after {
      content: "";
      position: absolute;
      inset: 0;
      background-image:
        repeating-linear-gradient(
          -55deg,
          transparent,
          transparent 60px,
          rgba(201,168,76,0.025) 60px,
          rgba(201,168,76,0.025) 61px
        );
    }

    /* Sneaker silhouette placeholder — REEMPLAZA CON IMAGEN REAL */
    .hero-shoe {
      position: absolute;
      right: -40px;
      bottom: 0;
      width: min(620px, 65vw);
      height: min(440px, 46vw);
      display: flex;
      align-items: flex-end;
      justify-content: center;
      opacity: 0.18;
    }
    .hero-shoe svg { width: 100%; height: 100%; }

    .hero-content {
      position: relative;
      z-index: 2;
      max-width: 760px;
    }

    .hero-eyebrow {
      font-family: var(--font-head);
      font-size: 13px;
      font-weight: 700;
      letter-spacing: 5px;
      text-transform: uppercase;
      color: var(--gold);
      display: flex;
      align-items: center;
      gap: 12px;
      margin-bottom: 20px;
    }
    .hero-eyebrow::before {
      content: "";
      display: block;
      width: 40px;
      height: 2px;
      background: var(--gold);
    }

    .hero-title {
      font-size: clamp(64px, 12vw, 140px);
      line-height: 0.92;
      letter-spacing: -1px;
      color: var(--white);
      text-transform: uppercase;
    }
    .hero-title .accent { color: var(--gold); }

    .hero-sub {
      font-family: var(--font-body);
      font-size: clamp(15px, 2vw, 18px);
      color: var(--gray);
      max-width: 500px;
      margin: 24px 0 40px;
      line-height: 1.7;
    }

    .hero-ctas {
      display: flex;
      flex-wrap: wrap;
      gap: 14px;
    }

    /* Scroll indicator */
    .scroll-hint {
      position: absolute;
      bottom: 32px;
      left: 50%;
      transform: translateX(-50%);
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 8px;
      opacity: 0.4;
      animation: bounceDown 1.8s ease-in-out infinite;
    }
    .scroll-hint span {
      font-family: var(--font-head);
      font-size: 11px;
      letter-spacing: 3px;
      text-transform: uppercase;
    }
    .scroll-hint svg { width: 20px; height: 20px; }
    @keyframes bounceDown {
      0%, 100% { transform: translateX(-50%) translateY(0); }
      50% { transform: translateX(-50%) translateY(8px); }
    }

    /* ============================================================
       VALUE PROPS
    ============================================================ */
    #propuestas {
      background: var(--panel);
      border-top: 1px solid var(--border);
      border-bottom: 1px solid var(--border);
      padding: 56px 0;
    }
    .props-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 0;
    }
    .prop-item {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      padding: 32px 28px;
      border-right: 1px solid var(--border);
      transition: background var(--transition);
    }
    .prop-item:last-child { border-right: none; }
    .prop-item:hover { background: rgba(201,168,76,0.04); }

    .prop-icon {
      font-size: 36px;
      margin-bottom: 16px;
      line-height: 1;
    }
    .prop-title {
      font-family: var(--font-head);
      font-size: 18px;
      font-weight: 700;
      letter-spacing: 1px;
      text-transform: uppercase;
      color: var(--white);
      margin-bottom: 8px;
    }
    .prop-desc {
      font-size: 14px;
      color: var(--gray);
      line-height: 1.6;
    }

    /* ============================================================
       CATALOG
    ============================================================ */
    #catalogo { background: var(--black); }
    .section-header { text-align: center; }

    .catalog-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 24px;
      margin-top: 56px;
    }

    .product-card {
      background: var(--panel);
      border: 1px solid var(--border);
      border-radius: 8px;
      overflow: hidden;
      transition: transform var(--transition), box-shadow var(--transition), border-color var(--transition);
      cursor: pointer;
    }
    .product-card:hover {
      transform: translateY(-6px);
      box-shadow: 0 20px 60px rgba(0,0,0,0.7), 0 0 0 1px var(--gold);
      border-color: var(--gold);
    }

    /* REEMPLAZA: img src con imagen real del producto */
    .card-img {
      width: 100%;
      aspect-ratio: 4/3;
      background: linear-gradient(135deg, #1a1a1a 0%, #111 100%);
      display: flex;
      align-items: center;
      justify-content: center;
      position: relative;
      overflow: hidden;
    }
    .card-img::before {
      content: "";
      position: absolute;
      inset: 0;
      background: radial-gradient(circle at 60% 40%, rgba(201,168,76,0.08) 0%, transparent 70%);
    }
    .card-img-placeholder {
      width: 70%;
      height: 70%;
      opacity: 0.25;
    }
    .card-badge {
      position: absolute;
      top: 12px;
      left: 12px;
      background: var(--red);
      color: var(--white);
      font-family: var(--font-head);
      font-size: 11px;
      font-weight: 700;
      letter-spacing: 1.5px;
      text-transform: uppercase;
      padding: 4px 10px;
      border-radius: 3px;
    }

    .card-body { padding: 20px; }
    .card-category {
      font-family: var(--font-head);
      font-size: 11px;
      font-weight: 700;
      letter-spacing: 3px;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 6px;
    }
    .card-name {
      font-family: var(--font-head);
      font-size: 20px;
      font-weight: 700;
      letter-spacing: 1px;
      text-transform: uppercase;
      color: var(--white);
      margin-bottom: 4px;
    }
    .card-desc {
      font-size: 13px;
      color: var(--gray);
      margin-bottom: 16px;
      line-height: 1.5;
    }
    .card-footer {
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    .card-price {
      font-family: var(--font-display);
      font-size: 28px;
      color: var(--white);
    }
    .card-price span {
      font-size: 16px;
      color: var(--gold);
      font-family: var(--font-head);
      font-weight: 700;
      letter-spacing: 1px;
    }

    /* ============================================================
       WHY EL CAPO
    ============================================================ */
    #nosotros {
      background: var(--panel);
      border-top: 1px solid var(--border);
    }
    .why-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 80px;
      align-items: center;
    }
    .why-text { }
    .why-text p {
      color: var(--gray-lt);
      font-size: 16px;
      line-height: 1.8;
      margin-bottom: 20px;
    }
    .why-features {
      display: flex;
      flex-direction: column;
      gap: 16px;
      margin-top: 32px;
    }
    .why-feat {
      display: flex;
      align-items: flex-start;
      gap: 16px;
      padding: 16px;
      background: rgba(201,168,76,0.05);
      border: 1px solid rgba(201,168,76,0.15);
      border-radius: var(--radius);
      transition: border-color var(--transition);
    }
    .why-feat:hover { border-color: rgba(201,168,76,0.4); }
    .why-feat-icon {
      font-size: 22px;
      min-width: 28px;
    }
    .why-feat-copy strong {
      font-family: var(--font-head);
      font-size: 15px;
      font-weight: 700;
      letter-spacing: 1px;
      text-transform: uppercase;
      color: var(--white);
      display: block;
      margin-bottom: 4px;
    }
    .why-feat-copy span {
      font-size: 13px;
      color: var(--gray);
    }

    /* Sello / badge */
    .why-visual {
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .sello {
      width: 280px;
      height: 280px;
      border-radius: 50%;
      border: 3px solid var(--gold);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 40px;
      background: radial-gradient(circle at center, rgba(201,168,76,0.08) 0%, transparent 70%);
      position: relative;
      animation: selloRotate 20s linear infinite;
    }
    @keyframes selloRotate {
      0% { box-shadow: 0 0 30px rgba(201,168,76,0.1); }
      50% { box-shadow: 0 0 60px rgba(201,168,76,0.25); }
      100% { box-shadow: 0 0 30px rgba(201,168,76,0.1); }
    }
    .sello::before {
      content: "★ ★ ★ ★ ★ ★ ★ ★";
      position: absolute;
      width: 100%;
      height: 100%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 9px;
      letter-spacing: 8px;
      color: rgba(201,168,76,0.3);
      border-radius: 50%;
    }
    .sello-icon { font-size: 40px; margin-bottom: 12px; }
    .sello-title {
      font-family: var(--font-display);
      font-size: 26px;
      line-height: 1.1;
      color: var(--gold);
      text-transform: uppercase;
      letter-spacing: 2px;
    }
    .sello-sub {
      font-family: var(--font-head);
      font-size: 11px;
      font-weight: 700;
      letter-spacing: 3px;
      text-transform: uppercase;
      color: var(--gray);
      margin-top: 8px;
    }

    /* ============================================================
       TESTIMONIALS
    ============================================================ */
    #testimonios { background: var(--black); }

    .testimonios-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 24px;
      margin-top: 56px;
    }
    .testi-card {
      background: var(--panel);
      border: 1px solid var(--border);
      border-radius: 8px;
      padding: 28px;
      position: relative;
      transition: border-color var(--transition), transform var(--transition);
    }
    .testi-card:hover {
      border-color: rgba(201,168,76,0.3);
      transform: translateY(-4px);
    }
    .testi-card::before {
      content: """;
      position: absolute;
      top: 16px;
      right: 20px;
      font-family: Georgia, serif;
      font-size: 80px;
      line-height: 1;
      color: rgba(201,168,76,0.12);
    }
    .testi-stars {
      display: flex;
      gap: 3px;
      margin-bottom: 16px;
    }
    .testi-stars span { font-size: 16px; color: var(--gold); }
    .testi-text {
      font-size: 15px;
      color: var(--gray-lt);
      line-height: 1.7;
      margin-bottom: 20px;
      font-style: italic;
    }
    .testi-author {
      display: flex;
      align-items: center;
      gap: 12px;
    }
    .testi-avatar {
      width: 42px;
      height: 42px;
      border-radius: 50%;
      background: linear-gradient(135deg, rgba(201,168,76,0.3) 0%, rgba(181,37,27,0.3) 100%);
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: var(--font-display);
      font-size: 18px;
      color: var(--gold);
      border: 1px solid rgba(201,168,76,0.3);
    }
    .testi-name {
      font-family: var(--font-head);
      font-weight: 700;
      font-size: 15px;
      letter-spacing: 1px;
      text-transform: uppercase;
      color: var(--white);
    }
    .testi-loc {
      font-size: 12px;
      color: var(--gray);
    }

    /* ============================================================
       HOW TO BUY
    ============================================================ */
    #como-comprar {
      background: var(--panel);
      border-top: 1px solid var(--border);
    }
    .steps-grid {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 0;
      margin-top: 56px;
      position: relative;
    }
    /* connector line */
    .steps-grid::before {
      content: "";
      position: absolute;
      top: 36px;
      left: calc(12.5% + 8px);
      right: calc(12.5% + 8px);
      height: 2px;
      background: linear-gradient(90deg, var(--gold), rgba(201,168,76,0.3));
      z-index: 0;
    }
    .step {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      padding: 0 20px;
      position: relative;
      z-index: 1;
    }
    .step-num {
      width: 72px;
      height: 72px;
      border-radius: 50%;
      background: var(--black);
      border: 2px solid var(--gold);
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: var(--font-display);
      font-size: 32px;
      color: var(--gold);
      margin-bottom: 24px;
      position: relative;
      transition: background var(--transition), transform var(--transition);
    }
    .step:hover .step-num {
      background: var(--gold);
      color: var(--black);
      transform: scale(1.1);
    }
    .step-icon {
      position: absolute;
      top: -6px;
      right: -6px;
      width: 24px;
      height: 24px;
      background: var(--red);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 12px;
    }
    .step-title {
      font-family: var(--font-head);
      font-size: 16px;
      font-weight: 700;
      letter-spacing: 1px;
      text-transform: uppercase;
      color: var(--white);
      margin-bottom: 10px;
    }
    .step-desc {
      font-size: 14px;
      color: var(--gray);
      line-height: 1.6;
    }

    .steps-cta {
      text-align: center;
      margin-top: 56px;
    }

    /* ============================================================
       CONTACT / FOOTER
    ============================================================ */
    #contacto {
      background: var(--black);
      border-top: 1px solid rgba(201,168,76,0.25);
      padding-top: 72px;
    }

    .footer-top {
      display: grid;
      grid-template-columns: 2fr 1fr 1fr;
      gap: 48px;
      padding-bottom: 56px;
      border-bottom: 1px solid var(--border);
    }

    .footer-brand .nav-logo {
      font-size: 36px;
      display: inline-block;
      margin-bottom: 16px;
    }
    .footer-brand p {
      font-size: 14px;
      color: var(--gray);
      line-height: 1.8;
      max-width: 320px;
    }
    .footer-social {
      display: flex;
      gap: 12px;
      margin-top: 24px;
    }
    .social-link {
      width: 40px;
      height: 40px;
      border: 1px solid var(--border);
      border-radius: var(--radius);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 18px;
      transition: border-color var(--transition), background var(--transition);
    }
    .social-link:hover {
      border-color: var(--gold);
      background: rgba(201,168,76,0.1);
    }

    .footer-col h4 {
      font-family: var(--font-head);
      font-size: 13px;
      font-weight: 700;
      letter-spacing: 3px;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 20px;
    }
    .footer-col ul { display: flex; flex-direction: column; gap: 12px; }
    .footer-col ul li {
      font-size: 14px;
      color: var(--gray);
      display: flex;
      align-items: center;
      gap: 8px;
      transition: color var(--transition);
    }
    .footer-col ul li:hover { color: var(--gray-lt); }
    .footer-col ul li a { color: inherit; }

    .payment-icons {
      display: flex;
      flex-direction: column;
      gap: 10px;
      margin-top: 4px;
    }
    .payment-badge {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 8px 14px;
      border: 1px solid var(--border);
      border-radius: var(--radius);
      font-family: var(--font-head);
      font-size: 13px;
      font-weight: 700;
      letter-spacing: 1px;
      color: var(--gray-lt);
      width: fit-content;
      transition: border-color var(--transition);
    }
    .payment-badge:hover { border-color: var(--gold); }
    .payment-badge .icon { font-size: 20px; }

    .footer-bottom {
      padding: 24px 0;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 12px;
    }
    .footer-bottom p {
      font-size: 13px;
      color: var(--gray);
    }
    .footer-bottom p span { color: var(--gold); }

    /* ============================================================
       FLOATING WHATSAPP BUTTON
    ============================================================ */
    .wa-float {
      position: fixed;
      bottom: 28px;
      right: 28px;
      z-index: 999;
      width: 60px;
      height: 60px;
      background: #25D366;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 4px 24px rgba(37,211,102,0.45);
      transition: transform var(--transition), box-shadow var(--transition);
      animation: waPulse 2.5s ease-in-out infinite;
    }
    .wa-float:hover {
      transform: scale(1.12);
      box-shadow: 0 8px 32px rgba(37,211,102,0.6);
      animation: none;
    }
    .wa-float svg {
      width: 30px;
      height: 30px;
    }
    @keyframes waPulse {
      0%, 100% { box-shadow: 0 4px 24px rgba(37,211,102,0.45); }
      50% { box-shadow: 0 4px 40px rgba(37,211,102,0.75), 0 0 0 8px rgba(37,211,102,0.1); }
    }
    .wa-tooltip {
      position: absolute;
      right: 72px;
      background: rgba(8,8,8,0.92);
      border: 1px solid rgba(37,211,102,0.4);
      color: var(--white);
      font-family: var(--font-head);
      font-size: 12px;
      font-weight: 600;
      letter-spacing: 1px;
      text-transform: uppercase;
      padding: 6px 12px;
      border-radius: 4px;
      white-space: nowrap;
      opacity: 0;
      pointer-events: none;
      transition: opacity var(--transition);
    }
    .wa-float:hover .wa-tooltip { opacity: 1; }

    /* ============================================================
       RESPONSIVE
    ============================================================ */
    @media (max-width: 900px) {
      .catalog-grid { grid-template-columns: repeat(2, 1fr); }
      .why-grid { grid-template-columns: 1fr; gap: 48px; }
      .why-visual { order: -1; }
      .sello { width: 220px; height: 220px; }
      .testimonios-grid { grid-template-columns: 1fr; }
      .steps-grid { grid-template-columns: repeat(2, 1fr); gap: 40px; }
      .steps-grid::before { display: none; }
      .footer-top { grid-template-columns: 1fr 1fr; }
      .footer-brand { grid-column: 1 / -1; }
      .props-grid { grid-template-columns: 1fr; }
      .prop-item { border-right: none; border-bottom: 1px solid var(--border); }
      .prop-item:last-child { border-bottom: none; }
    }

    @media (max-width: 640px) {
      .section { padding: 72px 0; }
      .catalog-grid { grid-template-columns: 1fr; }
      .steps-grid { grid-template-columns: 1fr; }
      .footer-top { grid-template-columns: 1fr; }
      .nav-links, .nav-cta { display: none; }
      .hamburger { display: flex; }
      .hero-shoe { display: none; }
      h1 { font-size: 72px; }
      .footer-bottom { flex-direction: column; text-align: center; }
    }
  </style>
</head>
<body>

  <!-- ============================================================
       NAVBAR
  ============================================================ -->
  <header id="navbar">
    <div class="container">
      <nav class="nav-inner">
        <a href="#inicio" class="nav-logo">EL <span>CAPO</span></a>

        <ul class="nav-links">
          <li><a href="#inicio">Inicio</a></li>
          <li><a href="#catalogo">Catálogo</a></li>
          <li><a href="#nosotros">Nosotros</a></li>
          <li><a href="#contacto">Contacto</a></li>
        </ul>

        <a href="#catalogo" class="btn btn-gold btn-sm nav-cta">Ver Catálogo</a>

        <button class="hamburger" id="hamburger" aria-label="Menú">
          <span></span><span></span><span></span>
        </button>
      </nav>
    </div>
    <div class="mobile-menu" id="mobileMenu">
      <a href="#inicio" class="mobile-nav-link">Inicio</a>
      <a href="#catalogo" class="mobile-nav-link">Catálogo</a>
      <a href="#nosotros" class="mobile-nav-link">Nosotros</a>
      <a href="#contacto" class="mobile-nav-link">Contacto</a>
      <a href="#catalogo" class="btn btn-gold">Ver Catálogo</a>
    </div>
  </header>

  <!-- ============================================================
       HERO
  ============================================================ -->
  <section id="inicio">
    <div class="hero-bg"></div>

    <!-- REEMPLAZA: Silueta SVG con imagen real de zapatilla -->
    <div class="hero-shoe">
      <svg viewBox="0 0 600 300" xmlns="http://www.w3.org/2000/svg">
        <!-- Silueta estilizada de zapatilla -->
        <path d="M50,220 Q80,140 160,110 Q240,80 340,90 Q420,95 500,130 Q540,148 560,175 Q575,195 560,210 L500,215 Q460,218 420,220 Q300,230 200,225 Q110,220 50,220Z" fill="white"/>
        <path d="M160,110 Q200,70 250,60 Q290,52 320,70 Q340,80 340,90" fill="none" stroke="white" stroke-width="3"/>
        <path d="M500,130 Q520,120 540,125 Q560,130 560,175" fill="none" stroke="white" stroke-width="2"/>
        <ellipse cx="120" cy="220" rx="60" ry="18" fill="white" opacity="0.6"/>
        <ellipse cx="480" cy="215" rx="65" ry="18" fill="white" opacity="0.6"/>
      </svg>
    </div>

    <div class="container">
      <div class="hero-content">
        <div class="hero-eyebrow reveal">Cusco · Perú · Desde 2023</div>
        <h1 class="hero-title reveal reveal-delay-1">
          El Estilo<br><span class="accent">Que Manda</span>
        </h1>
        <p class="hero-sub reveal reveal-delay-2">
          Zapatillas de calidad peruana para el hombre que sabe lo que quiere. Exclusivas, duraderas, tuyas.
        </p>
        <div class="hero-ctas reveal reveal-delay-3">
          <a href="#catalogo" class="btn btn-gold">
            Ver Colección
          </a>
          <a href="https://wa.me/51999882825?text=Hola,%20vi%20su%20catálogo%20en%20El%20Capo%20y%20quiero%20más%20información" target="_blank" class="btn btn-outline">
            <span class="icon-wa"></span> WhatsApp
          </a>
        </div>
      </div>
    </div>

    <div class="scroll-hint">
      <span>Scroll</span>
      <svg viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M10 4v12M4 10l6 6 6-6" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </div>
  </section>

  <!-- ============================================================
       VALUE PROPS
  ============================================================ -->
  <section id="propuestas">
    <div class="container">
      <div class="props-grid">
        <div class="prop-item reveal">
          <div class="prop-icon">🇵🇪</div>
          <div class="prop-title">Calidad Peruana</div>
          <p class="prop-desc">Cada par fabricado con orgullo en Perú, con materiales cuidadosamente seleccionados.</p>
        </div>
        <div class="prop-item reveal reveal-delay-1">
          <div class="prop-icon">🚚</div>
          <div class="prop-title">Entrega en Cusco</div>
          <p class="prop-desc">Enviamos directo a tu puerta en toda la ciudad del Cusco. Rápido y seguro.</p>
        </div>
        <div class="prop-item reveal reveal-delay-2">
          <div class="prop-icon">💳</div>
          <div class="prop-title">Pago Fácil</div>
          <p class="prop-desc">Acepta Yape y efectivo. Simple, sin complicaciones, sin costos extra.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- ============================================================
       CATALOG
  ============================================================ -->
  <section id="catalogo" class="section">
    <div class="container">
      <div class="section-header">
        <div class="label reveal">Colección 2025</div>
        <h2 class="reveal reveal-delay-1">Nuestros Modelos</h2>
        <div class="gold-line reveal reveal-delay-2" style="margin: 16px auto 0;"></div>
      </div>

      <div class="catalog-grid">

        <!-- CARD 1 -->
        <!-- REEMPLAZA: img src con la imagen real del modelo -->
        <div class="product-card reveal">
          <div class="card-img">
            <svg class="card-img-placeholder" viewBox="0 0 200 130" xmlns="http://www.w3.org/2000/svg">
              <path d="M20,90 Q40,50 80,40 Q120,30 150,45 Q170,55 180,75 Q185,85 178,90 L140,93 Q110,96 80,94 Q45,92 20,90Z" fill="rgba(201,168,76,0.5)"/>
              <ellipse cx="50" cy="91" rx="25" ry="8" fill="rgba(201,168,76,0.3)"/>
              <ellipse cx="155" cy="90" rx="28" ry="8" fill="rgba(201,168,76,0.3)"/>
            </svg>
            <span class="card-badge">Nuevo</span>
          </div>
          <div class="card-body">
            <div class="card-category">Urbano</div>
            <div class="card-name">Capo Classic</div>
            <p class="card-desc">Diseño limpio, suela resistente y cuero genuino. El básico que nunca falla.</p>
            <div class="card-footer">
              <div class="card-price"><span>S/.</span> 189</div>
              <a href="https://wa.me/51999882825?text=Hola,%20quiero%20consultar%20por%20el%20modelo%20Capo%20Classic" target="_blank" class="btn btn-gold btn-sm">Consultar</a>
            </div>
          </div>
        </div>

        <!-- CARD 2 -->
        <div class="product-card reveal reveal-delay-1">
          <div class="card-img" style="background: linear-gradient(135deg, #1a1208 0%, #111 100%);">
            <svg class="card-img-placeholder" viewBox="0 0 200 130" xmlns="http://www.w3.org/2000/svg">
              <path d="M15,85 Q35,45 75,35 Q120,22 155,42 Q175,54 182,72 Q188,85 180,90 L140,93 Q110,96 75,94 Q40,92 15,85Z" fill="rgba(181,37,27,0.5)"/>
              <ellipse cx="45" cy="88" rx="23" ry="7" fill="rgba(181,37,27,0.3)"/>
              <ellipse cx="155" cy="90" rx="27" ry="7" fill="rgba(181,37,27,0.3)"/>
            </svg>
          </div>
          <div class="card-body">
            <div class="card-category">Premium</div>
            <div class="card-name">Inca High</div>
            <p class="card-desc">Caña alta con acabado premium. Inspirado en el espíritu guerrero andino.</p>
            <div class="card-footer">
              <div class="card-price"><span>S/.</span> 249</div>
              <a href="https://wa.me/51999882825?text=Hola,%20quiero%20consultar%20por%20el%20modelo%20Inca%20High" target="_blank" class="btn btn-gold btn-sm">Consultar</a>
            </div>
          </div>
        </div>

        <!-- CARD 3 -->
        <div class="product-card reveal reveal-delay-2">
          <div class="card-img" style="background: linear-gradient(135deg, #0d1012 0%, #151a1e 100%);">
            <svg class="card-img-placeholder" viewBox="0 0 200 130" xmlns="http://www.w3.org/2000/svg">
              <path d="M25,88 Q50,48 90,38 Q125,30 155,48 Q172,58 180,78 Q184,88 176,92 L138,95 Q108,97 78,95 Q48,93 25,88Z" fill="rgba(180,180,180,0.35)"/>
              <ellipse cx="52" cy="91" rx="24" ry="7" fill="rgba(180,180,180,0.2)"/>
              <ellipse cx="154" cy="92" rx="26" ry="7" fill="rgba(180,180,180,0.2)"/>
            </svg>
            <span class="card-badge" style="background: var(--gold); color: var(--black);">Top Venta</span>
          </div>
          <div class="card-body">
            <div class="card-category">Casual</div>
            <div class="card-name">Cusco Runner</div>
            <p class="card-desc">Ligera, cómoda y versátil. Perfecta para el día a día en la ciudad imperial.</p>
            <div class="card-footer">
              <div class="card-price"><span>S/.</span> 169</div>
              <a href="https://wa.me/51999882825?text=Hola,%20quiero%20consultar%20por%20el%20modelo%20Cusco%20Runner" target="_blank" class="btn btn-gold btn-sm">Consultar</a>
            </div>
          </div>
        </div>

        <!-- CARD 4 -->
        <div class="product-card reveal">
          <div class="card-img" style="background: linear-gradient(135deg, #120a08 0%, #111 100%);">
            <svg class="card-img-placeholder" viewBox="0 0 200 130" xmlns="http://www.w3.org/2000/svg">
              <path d="M18,88 Q38,48 78,38 Q118,27 152,44 Q172,56 180,75 Q186,88 178,92 L138,95 Q108,97 75,95 Q42,93 18,88Z" fill="rgba(139,90,43,0.55)"/>
              <ellipse cx="46" cy="91" rx="24" ry="7" fill="rgba(139,90,43,0.3)"/>
              <ellipse cx="152" cy="92" rx="27" ry="7" fill="rgba(139,90,43,0.3)"/>
            </svg>
          </div>
          <div class="card-body">
            <div class="card-category">Clásico</div>
            <div class="card-name">Señor del Estilo</div>
            <p class="card-desc">Cuero marrón envejecido, costura visible. El zapato del hombre con clase.</p>
            <div class="card-footer">
              <div class="card-price"><span>S/.</span> 219</div>
              <a href="https://wa.me/51999882825?text=Hola,%20quiero%20consultar%20por%20el%20modelo%20Señor%20del%20Estilo" target="_blank" class="btn btn-gold btn-sm">Consultar</a>
            </div>
          </div>
        </div>

        <!-- CARD 5 -->
        <div class="product-card reveal reveal-delay-1">
          <div class="card-img" style="background: linear-gradient(135deg, #050a10 0%, #0a0f15 100%);">
            <svg class="card-img-placeholder" viewBox="0 0 200 130" xmlns="http://www.w3.org/2000/svg">
              <path d="M22,86 Q45,46 85,36 Q122,27 153,44 Q173,55 181,73 Q187,85 179,91 L140,94 Q110,97 78,95 Q44,93 22,86Z" fill="rgba(50,100,180,0.4)"/>
              <ellipse cx="50" cy="90" rx="24" ry="7" fill="rgba(50,100,180,0.2)"/>
              <ellipse cx="153" cy="92" rx="27" ry="7" fill="rgba(50,100,180,0.2)"/>
            </svg>
          </div>
          <div class="card-body">
            <div class="card-category">Sport</div>
            <div class="card-name">Altiplano X</div>
            <p class="card-desc">Deportivo de alto rendimiento. Suela reforzada para terreno andino exigente.</p>
            <div class="card-footer">
              <div class="card-price"><span>S/.</span> 199</div>
              <a href="https://wa.me/51999882825?text=Hola,%20quiero%20consultar%20por%20el%20modelo%20Altiplano%20X" target="_blank" class="btn btn-gold btn-sm">Consultar</a>
            </div>
          </div>
        </div>

        <!-- CARD 6 -->
        <div class="product-card reveal reveal-delay-2">
          <div class="card-img" style="background: linear-gradient(135deg, #111008 0%, #0e0c08 100%);">
            <svg class="card-img-placeholder" viewBox="0 0 200 130" xmlns="http://www.w3.org/2000/svg">
              <path d="M20,87 Q42,47 82,37 Q122,26 153,44 Q173,55 181,74 Q186,86 178,91 L139,94 Q109,97 77,95 Q43,93 20,87Z" fill="rgba(201,168,76,0.4)"/>
              <path d="M82,37 Q100,20 118,24 Q132,30 140,42" stroke="rgba(201,168,76,0.6)" stroke-width="2" fill="none"/>
              <ellipse cx="48" cy="91" rx="24" ry="7" fill="rgba(201,168,76,0.2)"/>
              <ellipse cx="152" cy="92" rx="27" ry="7" fill="rgba(201,168,76,0.2)"/>
            </svg>
            <span class="card-badge">Edición Limitada</span>
          </div>
          <div class="card-body">
            <div class="card-category">Limited</div>
            <div class="card-name">Capo Gold</div>
            <p class="card-desc">Edición exclusiva. Detalles dorados, piel premium. Solo para los que mandan.</p>
            <div class="card-footer">
              <div class="card-price"><span>S/.</span> 299</div>
              <a href="https://wa.me/51999882825?text=Hola,%20quiero%20consultar%20por%20la%20edición%20limitada%20Capo%20Gold" target="_blank" class="btn btn-gold btn-sm">Consultar</a>
            </div>
          </div>
        </div>

      </div><!-- /catalog-grid -->

      <div style="text-align:center; margin-top: 48px;" class="reveal">
        <a href="https://wa.me/51999882825?text=Hola,%20quisiera%20ver%20más%20modelos%20disponibles%20en%20El%20Capo" target="_blank" class="btn btn-outline">
          <span class="icon-wa"></span> Ver Más Modelos por WhatsApp
        </a>
      </div>

    </div>
  </section>

  <!-- ============================================================
       WHY EL CAPO
  ============================================================ -->
  <section id="nosotros" class="section">
    <div class="container">
      <div class="why-grid">
        <div class="why-text">
          <div class="label reveal">¿Por qué El Capo?</div>
          <h2 class="reveal reveal-delay-1">Orgullo Peruano<br>en Cada Par</h2>
          <div class="gold-line left reveal reveal-delay-2"></div>
          <p class="reveal reveal-delay-2">
            En El Capo creemos que el hombre peruano merece calidad sin tener que gastar fortunas. Cada par de zapatillas que vendemos pasa por un riguroso control de calidad antes de llegar a tus manos.
          </p>
          <p class="reveal reveal-delay-3">
            Somos una marca nacida en el corazón del Cusco, con el objetivo de vestir al hombre moderno que valora lo hecho en casa. No importa si vas al trabajo, a la calle o a una salida: con El Capo, siempre mandas.
          </p>

          <div class="why-features">
            <div class="why-feat reveal">
              <div class="why-feat-icon">👟</div>
              <div class="why-feat-copy">
                <strong>Solo para hombres</strong>
                <span>Diseños masculinos, exclusivos, pensados para el estilo de vida peruano.</span>
              </div>
            </div>
            <div class="why-feat reveal reveal-delay-1">
              <div class="why-feat-icon">🔒</div>
              <div class="why-feat-copy">
                <strong>Calidad garantizada</strong>
                <span>Si no estás satisfecho, te asesoramos hasta encontrar el modelo ideal.</span>
              </div>
            </div>
            <div class="why-feat reveal reveal-delay-2">
              <div class="why-feat-icon">📦</div>
              <div class="why-feat-copy">
                <strong>Stock disponible en Cusco</strong>
                <span>Sin esperas largas. Entregamos en la ciudad cuando tú lo necesitas.</span>
              </div>
            </div>
          </div>
        </div>

        <div class="why-visual reveal">
          <div class="sello">
            <div class="sello-icon">🏆</div>
            <div class="sello-title">Hecho con Orgullo</div>
            <div class="sello-sub">Cusqueño · Perú</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ============================================================
       TESTIMONIALS
  ============================================================ -->
  <section id="testimonios" class="section">
    <div class="container">
      <div class="section-header">
        <div class="label reveal">Lo que dicen</div>
        <h2 class="reveal reveal-delay-1">Clientes Satisfechos</h2>
        <div class="gold-line reveal reveal-delay-2" style="margin: 16px auto 0;"></div>
      </div>

      <div class="testimonios-grid">

        <div class="testi-card reveal">
          <div class="testi-stars">
            <span>★</span><span>★</span><span>★</span><span>★</span><span>★</span>
          </div>
          <p class="testi-text">
            "Me compré el Capo Classic hace dos meses y siguen como el primer día. La calidad es real, no exageran. Además la entrega fue super rápida, llegaron al día siguiente."
          </p>
          <div class="testi-author">
            <div class="testi-avatar">R</div>
            <div>
              <div class="testi-name">Rodrigo Mamani</div>
              <div class="testi-loc">Cusco, Perú · Comprador verificado</div>
            </div>
          </div>
        </div>

        <div class="testi-card reveal reveal-delay-1">
          <div class="testi-stars">
            <span>★</span><span>★</span><span>★</span><span>★</span><span>★</span>
          </div>
          <p class="testi-text">
            "Llevé el Inca High a Lima y la gente me preguntaba dónde las había comprado. Son distintas a todo lo que ves en las tiendas. Me siento con estilo sin gastar una locura."
          </p>
          <div class="testi-author">
            <div class="testi-avatar">D</div>
            <div>
              <div class="testi-name">Diego Huallpa</div>
              <div class="testi-loc">Cusco / Lima · Comprador verificado</div>
            </div>
          </div>
        </div>

        <div class="testi-card reveal reveal-delay-2">
          <div class="testi-stars">
            <span>★</span><span>★</span><span>★</span><span>★</span><span>★</span>
          </div>
          <p class="testi-text">
            "Pagué por Yape y fue rapidísimo. Me mandaron fotos del pedido antes de enviar para que esté seguro. Así se hace bien el servicio. Ya compré mi segunda vez en El Capo."
          </p>
          <div class="testi-author">
            <div class="testi-avatar">C</div>
            <div>
              <div class="testi-name">Carlos Quispe</div>
              <div class="testi-loc">San Sebastián, Cusco · Comprador verificado</div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ============================================================
       HOW TO BUY
  ============================================================ -->
  <section id="como-comprar" class="section">
    <div class="container">
      <div class="section-header">
        <div class="label reveal">Simple y Directo</div>
        <h2 class="reveal reveal-delay-1">¿Cómo Comprar?</h2>
        <div class="gold-line reveal reveal-delay-2" style="margin: 16px auto 0;"></div>
      </div>

      <div class="steps-grid">
        <div class="step reveal">
          <div class="step-num">
            1
            <span class="step-icon">👟</span>
          </div>
          <div class="step-title">Elige tu Modelo</div>
          <p class="step-desc">Revisa nuestro catálogo y elige el par que más te guste. Tenemos estilos para cada ocasión.</p>
        </div>
        <div class="step reveal reveal-delay-1">
          <div class="step-num">
            2
            <span class="step-icon">💬</span>
          </div>
          <div class="step-title">Escríbenos</div>
          <p class="step-desc">Contáctanos por WhatsApp al 999 882 825. Te respondemos rápido con tallas y disponibilidad.</p>
        </div>
        <div class="step reveal reveal-delay-2">
          <div class="step-num">
            3
            <span class="step-icon">💳</span>
          </div>
          <div class="step-title">Paga Fácil</div>
          <p class="step-desc">Paga con Yape o en efectivo al recibir. Sin complicaciones ni pasos extra.</p>
        </div>
        <div class="step reveal reveal-delay-3">
          <div class="step-num">
            4
            <span class="step-icon">📦</span>
          </div>
          <div class="step-title">Recibe en Cusco</div>
          <p class="step-desc">Entregamos en toda la ciudad del Cusco. Rapido, seguro y directo a tu puerta.</p>
        </div>
      </div>

      <div class="steps-cta reveal">
        <a href="https://wa.me/51999882825?text=Hola,%20quiero%20hacer%20un%20pedido%20en%20El%20Capo" target="_blank" class="btn btn-gold" style="font-size: 16px; padding: 16px 40px;">
          <span class="icon-wa"></span> Pedir Ahora por WhatsApp
        </a>
      </div>

    </div>
  </section>

  <!-- ============================================================
       FOOTER / CONTACT
  ============================================================ -->
  <footer id="contacto">
    <div class="container">
      <div class="footer-top">

        <div class="footer-brand reveal">
          <a href="#inicio" class="nav-logo" style="font-size:36px; display:inline-block; margin-bottom:16px;">EL <span>CAPO</span></a>
          <p>Zapatillas masculinas de calidad peruana. Orgullosamente fabricadas en Cusco para el hombre que sabe lo que quiere.</p>
          <div class="footer-social">
            <!-- REEMPLAZA href con tu link real de Instagram -->
            <a href="#" class="social-link" aria-label="Instagram">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <rect x="2" y="2" width="20" height="20" rx="5" stroke="currentColor" stroke-width="1.5"/>
                <circle cx="12" cy="12" r="4" stroke="currentColor" stroke-width="1.5"/>
                <circle cx="17.5" cy="6.5" r="1" fill="currentColor"/>
              </svg>
            </a>
            <!-- REEMPLAZA href con tu link real de TikTok -->
            <a href="#" class="social-link" aria-label="TikTok">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M9 12a4 4 0 1 0 4 4V4a5 5 0 0 0 5 5" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </a>
            <a href="https://wa.me/51999882825" target="_blank" class="social-link" aria-label="WhatsApp">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
              </svg>
            </a>
          </div>
        </div>

        <div class="footer-col reveal reveal-delay-1">
          <h4>Contacto</h4>
          <ul>
            <li>
              <svg width="16" height="16" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M22 16.92v3a2 2 0 01-2.18 2 19.79 19.79 0 01-8.63-3.07A19.5 19.5 0 013.09 9.81a19.79 19.79 0 01-3.07-8.67A2 2 0 012 .99h3a2 2 0 012 1.72 12.84 12.84 0 00.7 2.81 2 2 0 01-.45 2.11L6.09 8.91a16 16 0 006 6l1.27-1.27a2 2 0 012.11-.45 12.84 12.84 0 002.81.7A2 2 0 0122 16.92z" stroke="currentColor" stroke-width="1.5"/></svg>
              <a href="https://wa.me/51999882825" target="_blank">999 882 825</a>
            </li>
            <li>
              <svg width="16" height="16" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z" stroke="currentColor" stroke-width="1.5"/><circle cx="12" cy="10" r="3" stroke="currentColor" stroke-width="1.5"/></svg>
              Cusco, Perú
            </li>
            <li>
              <svg width="16" height="16" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><rect x="2" y="4" width="20" height="16" rx="2" stroke="currentColor" stroke-width="1.5"/><path d="M2 8l10 6 10-6" stroke="currentColor" stroke-width="1.5"/></svg>
              elcapocusco@gmail.com
            </li>
          </ul>
        </div>

        <div class="footer-col reveal reveal-delay-2">
          <h4>Métodos de Pago</h4>
          <div class="payment-icons">
            <div class="payment-badge">
              <span class="icon">💜</span> Yape
            </div>
            <div class="payment-badge">
              <span class="icon">💵</span> Efectivo
            </div>
          </div>
          <div style="margin-top: 20px;">
            <h4>Horarios</h4>
            <ul>
              <li>🕘 Lun – Sáb: 9am – 8pm</li>
              <li>🕑 Dom: 10am – 4pm</li>
            </ul>
          </div>
        </div>

      </div>

      <div class="footer-bottom">
        <p>© 2025 <span>El Capo</span>. Todos los derechos reservados.</p>
        <p>Hecho con ❤️ en <span>Cusco, Perú</span></p>
      </div>
    </div>
  </footer>

  <!-- ============================================================
       FLOATING WHATSAPP BUTTON
  ============================================================ -->
  <a
    href="https://wa.me/51999882825?text=Hola,%20vi%20su%20catálogo%20en%20El%20Capo%20y%20quiero%20más%20información"
    class="wa-float"
    target="_blank"
    aria-label="Contactar por WhatsApp"
  >
    <div class="wa-tooltip">¡Escríbenos!</div>
    <svg viewBox="0 0 24 24" fill="white" xmlns="http://www.w3.org/2000/svg">
      <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
    </svg>
  </a>

  <!-- ============================================================
       JAVASCRIPT
  ============================================================ -->
  <script>
    // ----- Sticky navbar -----
    const navbar = document.getElementById('navbar');
    window.addEventListener('scroll', () => {
      navbar.classList.toggle('scrolled', window.scrollY > 40);
    });

    // ----- Hamburger menu -----
    const hamburger = document.getElementById('hamburger');
    const mobileMenu = document.getElementById('mobileMenu');
    hamburger.addEventListener('click', () => {
      hamburger.classList.toggle('open');
      mobileMenu.classList.toggle('open');
    });
    // close on link click
    document.querySelectorAll('.mobile-nav-link, .mobile-menu .btn').forEach(link => {
      link.addEventListener('click', () => {
        hamburger.classList.remove('open');
        mobileMenu.classList.remove('open');
      });
    });

    // ----- Scroll reveal -----
    const revealObserver = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('visible');
          revealObserver.unobserve(entry.target);
        }
      });
    }, { threshold: 0.12, rootMargin: '0px 0px -40px 0px' });

    document.querySelectorAll('.reveal').forEach(el => revealObserver.observe(el));

    // ----- Hero text immediate reveal -----
    document.querySelectorAll('#inicio .reveal').forEach(el => {
      setTimeout(() => el.classList.add('visible'), 100);
    });

    // ----- Smooth scroll for nav links -----
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
          e.preventDefault();
          const offset = 72;
          const top = target.getBoundingClientRect().top + window.pageYOffset - offset;
          window.scrollTo({ top, behavior: 'smooth' });
        }
      });
    });
  </script>

</body>
</html>
