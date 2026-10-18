<html lang="en-IN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#101a2c">
<meta name="description" content="MK Enterprises, Hazratbal, Srinagar. Online digital services, printing, scanning, applications and document assistance.">
<meta name="color-scheme" content="light">
<title>MK Enterprises | Professional Digital Services</title>

<style>
:root {
    --navy: #101a2c;
    --navy2: #182943;
    --navy3: #223653;
    --gold: #d9b878;
    --gold2: #f3e3bd;
    --white: #ffffff;
    --bg: #f6f7fa;
    --text: #1b2638;
    --muted: #68758a;
    --border: #e3e7ee;
    --shadow: 0 15px 45px rgba(16, 26, 44, .09);
    --radius: 14px;
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html {
    scroll-behavior: smooth;
    scroll-padding-top: 85px;
    overflow-x: clip;
}

body {
    width: 100%;
    min-width: 320px;
    overflow-x: clip;
    font-family: Inter, "Segoe UI", Arial, sans-serif;
    background: var(--bg);
    color: var(--text);
    line-height: 1.7;
    -webkit-font-smoothing: antialiased;
}

a {
    color: inherit;
    text-decoration: none;
}

button, input, select, textarea {
    font: inherit;
}

button {
    -webkit-tap-highlight-color: transparent;
}

img, svg {
    max-width: 100%;
}

.container {
    width: min(1160px, calc(100% - 48px));
    margin-inline: auto;
}

.topbar {
    background: #080f1c;
    color: #d5dbe5;
    font-size: 11px;
    letter-spacing: .7px;
}

.topbar-inner {
    min-height: 36px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 15px;
}

.topbar strong {
    color: var(--gold2);
    font-weight: 600;
}

header {
    position: sticky;
    top: 0;
    z-index: 1000;
    background: rgba(16, 26, 44, .97);
    border-bottom: 1px solid #ffffff17;
    backdrop-filter: blur(14px);
}

.header-inner {
    min-height: 78px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 25px;
}

.brand {
    display: inline-flex;
    align-items: center;
    gap: 13px;
    flex-shrink: 0;
}

.brand-logo {
    width: 48px;
    height: 48px;
    border: 1px solid var(--gold);
    color: var(--gold2);
    display: grid;
    place-items: center;
    font-size: 19px;
    font-weight: 900;
    letter-spacing: -1.5px;
    position: relative;
}

.brand-logo::after {
    content: "";
    position: absolute;
    inset: 4px;
    border: 1px solid #d9b87855;
}

.brand-name {
    color: white;
    font-weight: 800;
    letter-spacing: 1.5px;
    font-size: 15px;
    display: block;
    line-height: 1.5;
}

.brand-subtitle {
    color: var(--gold);
    font-size: 9px;
    letter-spacing: 1.6px;
    display: block;
}

.nav {
    display: flex;
    align-items: center;
    justify-content: flex-end;
    gap: clamp(12px, 2vw, 26px);
    color: #dbe1ec;
    font-size: 12px;
}

.nav a {
    transition: color .2s;
}

.nav a:hover {
    color: var(--gold2);
}

.nav .nav-cta {
    border: 1px solid var(--gold);
    color: var(--gold2);
    padding: 10px 15px;
}

.menu-button {
    display: none;
    border: 1px solid #ffffff45;
    background: transparent;
    color: white;
    padding: 9px 13px;
    cursor: pointer;
    border-radius: 6px;
    font-size: 19px;
}

.hero {
    position: relative;
    overflow: hidden;
    background:
        radial-gradient(ellipse at 85% 18%, #3b4f70 0%, transparent 37%),
        linear-gradient(125deg, var(--navy), #172742 72%, #20334f);
    color: white;
}

.hero::before {
    content: "";
    position: absolute;
    inset: 0;
    background-image:
        linear-gradient(#ffffff08 1px, transparent 1px),
        linear-gradient(90deg, #ffffff08 1px, transparent 1px);
    background-size: 44px 44px;
    pointer-events: none;
}

.hero-inner {
    position: relative;
    z-index: 1;
    display: grid;
    grid-template-columns: minmax(0, 1.1fr) minmax(0, .9fr);
    align-items: center;
    gap: clamp(28px, 5vw, 65px);
    padding-block: clamp(45px, 7vw, 85px);
}

.eyebrow {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    color: var(--gold2);
    letter-spacing: 2px;
    font-size: 10px;
    font-weight: 700;
}

.eyebrow::before {
    content: "";
    width: 25px;
    height: 1px;
    background: var(--gold);
}

.hero h1 {
    font-size: clamp(38px, 5.1vw, 68px);
    line-height: 1.08;
    letter-spacing: -2.5px;
    margin: 23px 0;
    overflow-wrap: anywhere;
}

.hero h1 span {
    color: var(--gold2);
}

.hero-description {
    max-width: 520px;
    font-size: 14px;
    color: #c5cedd;
    line-height: 2;
}

.actions {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    margin-top: 29px;
}

.btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 9px;
    min-height: 46px;
    padding: 12px 19px;
    border: 1px solid transparent;
    font-size: 12px;
    font-weight: 700;
    text-align: center;
    cursor: pointer;
    transition: transform .2s, background .2s;
}

.btn:hover {
    transform: translateY(-2px);
}

.btn-gold {
    background: var(--gold2);
    color: var(--navy);
}

.btn-gold:hover {
    background: white;
}

.btn-outline {
    color: white;
    border-color: #ffffff50;
}

.btn-outline:hover {
    border-color: var(--gold);
    color: var(--gold2);
}

.hero-points {
    display: flex;
    flex-wrap: wrap;
    gap: 12px 20px;
    color: #c7d0de;
    font-size: 10px;
    margin-top: 30px;
}

.hero-points span::first-letter {
    color: var(--gold);
}

.service-preview {
    min-width: 0;
    background: white;
    color: var(--text);
    padding: clamp(20px, 3vw, 32px);
    box-shadow: 0 25px 75px #0004;
    border-radius: 3px;
}

.preview-head {
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 10px;
    border-bottom: 1px solid var(--border);
    padding-bottom: 19px;
}

.preview-head strong {
    font-size: 11px;
    letter-spacing: 1px;
}

.badge {
    background: #f5efdf;
    color: #85652d;
    font-size: 9px;
    padding: 6px 9px;
}

.service-preview h2 {
    font-size: clamp(23px, 2.5vw, 30px);
    line-height: 1.3;
    margin-top: 22px;
    letter-spacing: -.6px;
}

.preview-description {
    color: var(--muted);
    font-size: 11px;
    margin: 8px 0 20px;
}

.preview-item {
    display: flex;
    align-items: center;
    gap: 13px;
    padding: 13px 0;
    border-top: 1px solid var(--border);
}

.preview-icon {
    width: 40px;
    height: 40px;
    display: grid;
    place-items: center;
    background: #f4efe5;
    color: #98763b;
    flex-shrink: 0;
    font-size: 18px;
}

.preview-item strong {
    display: block;
    font-size: 12px;
}

.preview-item small {
    display: block;
    color: var(--muted);
    font-size: 10px;
    margin-top: 3px;
}

.preview-footer {
    background: var(--navy);
    color: #dbe1ec;
    padding: 13px;
    margin: 18px calc(clamp(20px, 3vw, 32px) * -1) calc(clamp(20px, 3vw, 32px) * -1);
    text-align: center;
    font-size: 10px;
}

.preview-footer span {
    color: var(--gold2);
}

.section {
    padding-block: clamp(55px, 7vw, 88px);
}

.section-label {
    color: #99763a;
    font-size: 10px;
    font-weight: 800;
    letter-spacing: 2px;
}

.section-title {
    color: var(--navy);
    font-size: clamp(29px, 3.7vw, 43px);
    line-height: 1.2;
    letter-spacing: -1.4px;
    margin-top: 12px;
    overflow-wrap: anywhere;
}

.section-title span {
    color: #a17d40;
}

.section-description {
    max-width: 560px;
    color: var(--muted);
    font-size: 13px;
    line-height: 1.9;
    margin-top: 15px;
}

.section-heading {
    display: flex;
    align-items: end;
    justify-content: space-between;
    gap: 30px;
    margin-bottom: 35px;
}

.section-heading .section-description {
    max-width: 450px;
    margin-bottom: 3px;
}

.services {
    background: white;
}

.services-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 18px;
}

.service-card {
    min-width: 0;
    background: white;
    border: 1px solid var(--border);
    padding: 25px;
    transition: transform .2s, box-shadow .2s, border-color .2s;
}

.service-card:hover {
    transform: translateY(-4px);
    border-color: var(--gold);
    box-shadow: var(--shadow);
}

.service-card-head {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 22px;
}

.service-icon {
    width: 45px;
    height: 45px;
    display: grid;
    place-items: center;
    background: #f5efe3;
    color: #98753a;
    font-size: 21px;
}

.service-number {
    color: #a5adba;
    font-size: 10px;
    letter-spacing: .7px;
}

.service-card h3 {
    font-size: 15px;
    line-height: 1.5;
    margin-bottom: 9px;
}

.service-card p {
    font-size: 12px;
    color: var(--muted);
    line-height: 1.9;
}

.service-select {
    border: none;
    background: none;
    color: #8d6c36;
    font-size: 11px;
    font-weight: 800;
    margin-top: 17px;
    cursor: pointer;
    text-align: left;
}

.service-select:hover {
    color: var(--navy);
}

.notice {
    margin-top: 25px;
    padding: 17px 20px;
    background: #f8f3e8;
    border-left: 3px solid var(--gold);
    color: #75684e;
    font-size: 11px;
    line-height: 1.9;
}

.process {
    background: var(--bg);
}

.steps {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    margin-top: 35px;
    border-top: 1px solid #dfe4eb;
}

.step {
    min-width: 0;
    padding: 27px 25px 0 0;
}

.step + .step {
    border-left: 1px solid #dfe4eb;
    padding-left: 25px;
}

.step-number {
    color: #a17d40;
    font-size: 11px;
    font-weight: 800;
    letter-spacing: 1px;
}

.step h3 {
    font-size: 18px;
    margin: 12px 0 8px;
}

.step p {
    color: var(--muted);
    font-size: 12px;
    line-height: 1.9;
    max-width: 290px;
}

.contact {
    background:
        radial-gradient(ellipse at 15% 10%, #293d59 0, transparent 40%),
        var(--navy);
    color: white;
}

.contact-grid {
    display: grid;
    grid-template-columns: minmax(0, .85fr) minmax(0, 1.15fr);
    gap: clamp(25px, 5vw, 65px);
    align-items: start;
}

.contact .section-title {
    color: white;
}

.contact .section-title span {
    color: var(--gold2);
}

.contact .section-description {
    color: #c2ccdc;
}

.email-card {
    display: flex;
    align-items: center;
    gap: 15px;
    border: 1px solid #ffffff25;
    padding: 18px;
    margin-top: 27px;
    min-width: 0;
}

.email-icon {
    width: 43px;
    height: 43px;
    display: grid;
    place-items: center;
    flex-shrink: 0;
    border: 1px solid #d9b87880;
    color: var(--gold2);
    font-size: 18px;
}

.email-card small {
    display: block;
    color: #b9c4d5;
    font-size: 9px;
    letter-spacing: 1px;
}

.email-card a {
    display: block;
    color: var(--gold2);
    font-size: 12px;
    font-weight: 700;
    overflow-wrap: anywhere;
}

.privacy-note {
    margin-top: 22px;
    color: #b9c4d5;
    font-size: 11px;
    line-height: 1.9;
}

.privacy-note strong {
    color: white;
}

.form-card {
    min-width: 0;
    background: white;
    color: var(--text);
    padding: clamp(20px, 3vw, 32px);
    box-shadow: 0 20px 60px #0002;
}

.form-heading {
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 10px;
    padding-bottom: 18px;
    border-bottom: 1px solid var(--border);
}

.form-heading strong {
    font-size: 12px;
    letter-spacing: .7px;
}

.form-heading small {
    color: var(--muted);
    font-size: 10px;
}

.form-field {
    margin-top: 17px;
}

.form-field label {
    display: block;
    margin-bottom: 7px;
    font-size: 11px;
    font-weight: 700;
}

.required {
    color: #9a7538;
}

.form-field input,
.form-field select,
.form-field textarea {
    display: block;
    width: 100%;
    min-width: 0;
    padding: 12px 13px;
    border: 1px solid #dce1e9;
    border-radius: 3px;
    background: white;
    color: var(--text);
    font-size: 12px;
}

.form-field input:focus,
.form-field select:focus,
.form-field textarea:focus {
    outline: 2px solid #d9b878;
    outline-offset: 1px;
}

.form-field textarea {
    resize: vertical;
    min-height: 100px;
}

.phone-box {
    display: flex;
    width: 100%;
    min-width: 0;
    border: 1px solid #dce1e9;
}

.phone-box span {
    display: flex;
    align-items: center;
    background: #f2eee5;
    padding: 0 12px;
    white-space: nowrap;
    font-size: 12px;
}

.phone-box input {
    flex: 1;
    width: 0;
    border: 0;
}

.consent {
    display: flex;
    align-items: flex-start;
    gap: 9px;
    margin-top: 19px;
    color: var(--muted);
    font-size: 11px;
    line-height: 1.8;
}

.consent input {
    flex-shrink: 0;
    margin-top: 5px;
    accent-color: #9a7538;
}

.submit-button {
    width: 100%;
    margin-top: 20px;
}

.form-note,
.form-status {
    margin-top: 12px;
    font-size: 10px;
    color: var(--muted);
    line-height: 1.8;
    overflow-wrap: anywhere;
}

.form-status {
    font-size: 12px;
}

.about {
    background: white;
}

.about-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    align-items: center;
    gap: clamp(25px, 5vw, 65px);
}

.about-copy {
    color: var(--muted);
    font-size: 13px;
    line-height: 2;
    margin-top: 18px;
}

.about-box {
    background: var(--navy);
    color: white;
    padding: clamp(24px, 4vw, 38px);
    border-bottom: 3px solid var(--gold);
}

.about-box h3 {
    color: var(--gold2);
    font-size: 22px;
    margin-bottom: 13px;
}

.about-box p {
    color: #c3cddd;
    font-size: 12px;
    line-height: 2;
}

footer {
    background: #080f1c;
    color: #b9c3d2;
    padding-block: 28px;
}

.footer-grid {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 20px;
}

.footer-brand {
    color: var(--gold2);
    font-size: 12px;
    font-weight: 800;
    letter-spacing: 1.3px;
}

footer p {
    font-size: 10px;
    line-height: 1.9;
}

footer a {
    color: var(--gold2);
    font-size: 11px;
}

@media (min-width: 1500px) {
    .container {
        max-width: 1280px;
    }

    .hero-inner {
        padding-block: 95px;
    }
}

@media (max-width: 1000px) {
    .nav {
        gap: 13px;
        font-size: 11px;
    }

    .brand-name {
        font-size: 13px;
    }

    .brand-subtitle {
        font-size: 8px;
        letter-spacing: 1px;
    }

    .services-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
    }
}

@media (max-width: 760px) {
    .container {
        width: calc(100% - 36px);
    }

    .header-inner {
        min-height: 70px;
    }

    .menu-button {
        display: block;
    }

    .nav {
        display: none;
        position: absolute;
        top: 100%;
        left: 0;
        right: 0;
        padding: 22px 18px;
        background: var(--navy);
        border-top: 1px solid #ffffff20;
        flex-direction: column;
        align-items: stretch;
        gap: 0;
    }

    .nav.open {
        display: flex;
    }

    .nav a {
        padding: 12px 8px;
    }

    .nav .nav-cta {
        margin-top: 8px;
        text-align: center;
    }

    .hero-inner {
        grid-template-columns: minmax(0, 1fr);
        gap: 35px;
        padding-block: 50px;
    }

    .hero h1 {
        font-size: clamp(39px, 8vw, 58px);
    }

    .section-heading {
        display: block;
    }

    .section-heading .section-description {
        margin-top: 14px;
    }

    .contact-grid,
    .about-grid {
        grid-template-columns: minmax(0, 1fr);
        gap: 32px;
    }

    .steps {
        grid-template-columns: minmax(0, 1fr);
    }

    .step,
    .step + .step {
        padding: 23px 0;
        border-left: 0;
        border-bottom: 1px solid #dfe4eb;
    }

    .section {
        padding-block: 58px;
    }
}

@media (max-width: 480px) {
    .container {
        width: calc(100% - 28px);
    }

    .topbar-inner {
        min-height: 34px;
        font-size: 9px;
        gap: 6px;
    }

    .topbar-inner span:last-child {
        text-align: right;
    }

    .brand {
        gap: 9px;
    }

    .brand-logo {
        width: 39px;
        height: 39px;
        font-size: 17px;
    }

    .brand-name {
        font-size: 11px;
        letter-spacing: .9px;
    }

    .brand-subtitle {
        font-size: 7px;
        letter-spacing: .7px;
    }

    .hero-inner {
        padding-block: 42px;
    }

    .hero h1 {
        letter-spacing: -1.5px;
        margin-block: 19px;
    }

    .hero-description {
        font-size: 13px;
    }

    .actions {
        flex-direction: column;
    }

    .actions .btn {
        width: 100%;
    }

    .hero-points {
        gap: 10px 13px;
    }

    .service-preview {
        padding: 20px;
    }

    .preview-footer {
        margin: 18px -20px -20px;
    }

    .services-grid {
        grid-template-columns: minmax(0, 1fr);
    }

    .service-card {
        padding: 22px;
    }

    .section-title {
        font-size: clamp(28px, 8vw, 36px);
    }

    .form-card {
        padding: 21px 16px;
    }

    .email-card {
        padding: 14px;
    }

    .footer-grid {
        align-items: flex-start;
        flex-direction: column;
    }
}

@media (prefers-reduced-motion: reduce) {
    html {
        scroll-behavior: auto;
    }

    *,
    *::before,
    *::after {
        animation-duration: .01ms !important;
        transition-duration: .01ms !important;
    }
}
</style>
</head>

<body>

<div class="topbar">
    <div class="container topbar-inner">
        <span>PROFESSIONAL DIGITAL ASSISTANCE</span>
        <span><strong>HAZRATBAL, SRINAGAR</strong> · INDIA</span>
    </div>
</div>

<header>
    <div class="container header-inner">

        <a href="#home" class="brand" aria-label="MK Enterprises home">
            <span class="brand-logo">MK</span>
            <span>
                <span class="brand-name">MK ENTERPRISES</span>
                <span class="brand-subtitle">ONLINE DIGITAL SERVICES</span>
            </span>
        </a>

        <button
            type="button"
            class="menu-button"
            id="menuButton"
            aria-label="Open navigation"
            aria-expanded="false"
            aria-controls="navigation"
        >☰</button>

        <nav class="nav" id="navigation" aria-label="Main navigation">
            <a href="#home">Home</a>
            <a href="#services">Services</a>
            <a href="#process">How It Works</a>
            <a href="#about">About Us</a>
            <a href="#contact" class="nav-cta">Request Service ↗</a>
        </nav>

    </div>
</header>

<main>

<section class="hero" id="home">
    <div class="container hero-inner">

        <div>
            <div class="eyebrow">YOUR DIGITAL SERVICE PARTNER</div>

            <h1>Smart Digital<br><span>Solutions.</span></h1>

            <p class="hero-description">
                From online applications to document services,
                MK Enterprises helps make everyday digital tasks
                simpler, clearer and more convenient. Based in
                Hazratbal, Srinagar, Jammu & Kashmir, India.
            </p>

            <div class="actions">
                <a href="#contact" class="btn btn-gold">
                    Request a Service ↗
                </a>

                <a href="#services" class="btn btn-outline">
                    Explore Services
                </a>
            </div>

            <div class="hero-points">
                <span>✓ Clear communication</span>
                <span>✓ Email-based requests</span>
                <span>✓ India-focused assistance</span>
            </div>
        </div>

        <aside class="service-preview">
            <div class="preview-head">
                <strong>MK SERVICE DESK</strong>
                <span class="badge">DIGITAL ASSISTANCE</span>
            </div>

            <h2>Your task.<br>Our assistance.</h2>

            <p class="preview-description">
                Tell us what you need help with.
            </p>

            <div class="preview-item">
                <span class="preview-icon">▤</span>
                <div>
                    <strong>Forms & Applications</strong>
                    <small>Application and registration assistance</small>
                </div>
            </div>

            <div class="preview-item">
                <span class="preview-icon">▧</span>
                <div>
                    <strong>Documents & Printing</strong>
                    <small>Scanning, printing and PDF support</small>
                </div>
            </div>

            <div class="preview-item">
                <span class="preview-icon">◎</span>
                <div>
                    <strong>Digital Services</strong>
                    <small>Practical online assistance</small>
                </div>
            </div>

            <div class="preview-footer">
                <span>MK ENTERPRISES</span> · HAZRATBAL, SRINAGAR
            </div>
        </aside>

    </div>
</section>

<section class="section services" id="services">
    <div class="container">

        <div class="section-heading">
            <div>
                <div class="section-label">OUR SERVICES</div>
                <h2 class="section-title">
                    Digital support.<br><span>Made simple.</span>
                </h2>
            </div>

            <p class="section-description">
                Choose a service to begin your request. Availability,
                eligibility, official fees and approvals depend on the
                relevant service provider or authority.
            </p>
        </div>

        <div class="services-grid">

            <article class="service-card">
                <div class="service-card-head">
                    <span class="service-icon">▤</span>
                    <span class="service-number">01 / FORMS</span>
                </div>
                <h3>Online Forms & Applications</h3>
                <p>Assistance with online forms, admissions, examination applications and registrations.</p>
                <button class="service-select" type="button" data-service="Online forms and applications">Select service ↗</button>
            </article>

            <article class="service-card">
                <div class="service-card-head">
                    <span class="service-icon">▧</span>
                    <span class="service-number">02 / DOCUMENTS</span>
                </div>
                <h3>Printing & Document Services</h3>
                <p>Printing, scanning, photocopying, lamination, PDF conversion and document formatting.</p>
                <button class="service-select" type="button" data-service="Printing and document services">Select service ↗</button>
            </article>

            <article class="service-card">
                <div class="service-card-head">
                    <span class="service-icon">◎</span>
                    <span class="service-number">03 / PHOTOS</span>
                </div>
                <h3>Photo Services</h3>
                <p>Passport-size photo preparation, photo editing and photo-frame requests.</p>
                <button class="service-select" type="button" data-service="Photo services">Select service ↗</button>
            </article>

            <article class="service-card">
                <div class="service-card-head">
                    <span class="service-icon">▣</span>
                    <span class="service-number">04 / APPLICATIONS</span>
                </div>
                <h3>PAN & Passport Assistance</h3>
                <p>Application guidance and document preparation for eligible services.</p>
                <button class="service-select" type="button" data-service="PAN and passport assistance">Select service ↗</button>
            </article>

            <article class="service-card">
                <div class="service-card-head">
                    <span class="service-icon">⌘</span>
                    <span class="service-number">05 / PORTALS</span>
                </div>
                <h3>Government & Transport Portals</h3>
                <p>Assistance navigating relevant official government and Parivahan portals.</p>
                <button class="service-select" type="button" data-service="Government and transport portals">Select service ↗</button>
            </article>

            <article class="service-card">
                <div class="service-card-head">
                    <span class="service-icon">▣</span>
                    <span class="service-number">06 / REGISTRATION</span>
                </div>
                <h3>Business Registration Assistance</h3>
                <p>Guidance with eligible business registrations and online applications.</p>
                <button class="service-select" type="button" data-service="Business registration assistance">Select service ↗</button>
            </article>

            <article class="service-card">
                <div class="service-card-head">
                    <span class="service-icon">▤</span>
                    <span class="service-number">07 / PDF</span>
                </div>
                <h3>PDF & File Services</h3>
                <p>PDF conversion, document resizing, file preparation and downloading assistance.</p>
                <button class="service-select" type="button" data-service="PDF and file services">Select service ↗</button>
            </article>

            <article class="service-card">
                <div class="service-card-head">
                    <span class="service-icon">▧</span>
                    <span class="service-number">08 / DOCUMENTS</span>
                </div>
                <h3>Document Scanning & Downloading</h3>
                <p>Document scanning, digital copies, downloading and basic file organisation.</p>
                <button class="service-select" type="button" data-service="Scanning and downloading services">Select service ↗</button>
            </article>

            <article class="service-card">
                <div class="service-card-head">
                    <span class="service-icon">＋</span>
                    <span class="service-number">09 / OTHER</span>
                </div>
                <h3>Other Digital Services</h3>
                <p>Need assistance with another online task? Send your request for review.</p>
                <button class="service-select" type="button" data-service="Other digital services">Select service ↗</button>
            </article>

        </div>

        <div class="notice">
            <strong>Service notice:</strong>
            MK Enterprises is an independent digital-assistance business,
            not a government department. Government services, official
            fees, eligibility and approvals remain subject to the relevant
            authority. No government authorisation is implied.
        </div>

    </div>
</section>

<section class="section process" id="process">
    <div class="container">

        <div class="section-label">HOW IT WORKS</div>
        <h2 class="section-title">Three steps.<br><span>One simple process.</span></h2>

        <div class="steps">
            <article class="step">
                <span class="step-number">STEP 01</span>
                <h3>Choose your service</h3>
                <p>Select the digital service you need assistance with.</p>
            </article>

            <article class="step">
                <span class="step-number">STEP 02</span>
                <h3>Enter your details</h3>
                <p>Provide your name, Indian mobile number and basic request details.</p>
            </article>

            <article class="step">
                <span class="step-number">STEP 03</span>
                <h3>Send your email</h3>
                <p>Review the prepared email in Gmail and press Send to submit your request.</p>
            </article>
        </div>

    </div>
</section>

<section class="section contact" id="contact">
    <div class="container contact-grid">

        <div>
            <div class="section-label">CONTACT OUR SERVICE DESK</div>

            <h2 class="section-title">
                How can we<br><span>help you today?</span>
            </h2>

            <p class="section-description">
                Complete the request form. Gmail will open with your
                service details and our email address already filled in.
            </p>

            <div class="email-card">
                <span class="email-icon">✉</span>
                <div>
                    <small>OFFICIAL CONTACT EMAIL</small>
                    <a href="mailto:limitedmk67@gmail.com">limitedmk67@gmail.com</a>
                </div>
            </div>

            <div class="privacy-note">
                <strong>Privacy reminder</strong><br>
                Never include passwords, OTPs, bank details or sensitive
                identity information in the request form. This static
                website does not send form data to a website server.
            </div>
        </div>

        <form class="form-card" id="serviceForm">

            <div class="form-heading">
                <strong>NEW SERVICE REQUEST</strong>
                <small>* Required fields</small>
            </div>

            <div class="form-field">
                <label for="fullName">Full Name <span class="required">*</span></label>
                <input id="fullName" name="fullName" type="text" maxlength="80" autocomplete="name" required>
            </div>

            <div class="form-field">
                <label for="phone">Indian Mobile Number <span class="required">*</span></label>
                <div class="phone-box">
                    <span>+91 🇮🇳</span>
                    <input
                        id="phone"
                        name="phone"
                        type="tel"
                        inputmode="numeric"
                        autocomplete="tel-national"
                        maxlength="10"
                        pattern="[6-9][0-9]{9}"
                        title="Enter a 10-digit Indian mobile number beginning with 6, 7, 8 or 9."
                        placeholder="10-digit mobile number"
                        required
                    >
                </div>
            </div>

            <div class="form-field">
                <label for="service">Service Required <span class="required">*</span></label>
                <select id="service" name="service" required>
                    <option value="">Choose a service</option>
                    <option>Online forms and applications</option>
                    <option>Printing and document services</option>
                    <option>Photocopy and lamination</option>
                    <option>Photo services</option>
                    <option>PAN and passport assistance</option>
                    <option>Government and transport portals</option>
                    <option>Business registration assistance</option>
                    <option>PDF and file services</option>
                    <option>Scanning and downloading services</option>
                    <option>Admissions and examination forms</option>
                    <option>Other digital services</option>
                </select>
            </div>

            <div class="form-field">
                <label for="details">Request Details</label>
                <textarea id="details" name="details" maxlength="1000" rows="4" placeholder="Briefly describe the assistance you need."></textarea>
            </div>

            <label class="consent" for="consent">
                <input type="checkbox" id="consent" required>
                <span>I confirm that my details are correct and agree to open my email application to send this request.</span>
            </label>

            <button type="submit" class="btn btn-gold submit-button">
                Prepare Email Request ↗
            </button>

            <p class="form-note">
                Your browser will open Gmail to prepare the message.
                You must review and send the email yourself.
            </p>

            <p class="form-status" id="status" role="status" aria-live="polite"></p>

        </form>

    </div>
</section>

<section class="section about" id="about">
    <div class="container about-grid">

        <div>
            <div class="section-label">ABOUT MK ENTERPRISES</div>

            <h2 class="section-title">
                Local assistance.<br><span>Professional approach.</span>
            </h2>

            <p class="about-copy">
                MK Enterprises is an online digital-service assistance
                business based in Hazratbal, Srinagar, Jammu & Kashmir,
                India. Our aim is to make common digital tasks easier
                through practical assistance and clear communication.
            </p>
        </div>

        <div class="about-box">
            <h3>Your digital tasks, made easier.</h3>
            <p>
                From document preparation to online application assistance,
                contact our service desk to discuss your requirements.
                Service availability and processing remain subject to
                the relevant provider or authority.
            </p>
        </div>

    </div>
</section>

</main>

<footer>
    <div class="container footer-grid">

        <div>
            <div class="footer-brand">MK ENTERPRISES</div>
            <p>Online Digital Services · Hazratbal, Srinagar, India</p>
        </div>

        <p>
            Email: limitedmk67@gmail.com<br>
            © <span id="year"></span> MK Enterprises. All rights reserved.
        </p>

        <a href="#home">Back to top ↑</a>

    </div>
</footer>

<script>
"use strict";

const form = document.getElementById("serviceForm");
const statusBox = document.getElementById("status");
const menuButton = document.getElementById("menuButton");
const navigation = document.getElementById("navigation");

document.getElementById("year").textContent = new Date().getFullYear();

menuButton.addEventListener("click", function () {
    const isOpen = navigation.classList.toggle("open");

    menuButton.setAttribute("aria-expanded", String(isOpen));
    menuButton.setAttribute(
        "aria-label",
        isOpen ? "Close navigation" : "Open navigation"
    );

    menuButton.textContent = isOpen ? "✕" : "☰";
});

navigation.querySelectorAll("a").forEach(function (link) {
    link.addEventListener("click", function () {
        navigation.classList.remove("open");
        menuButton.setAttribute("aria-expanded", "false");
        menuButton.setAttribute("aria-label", "Open navigation");
        menuButton.textContent = "☰";
    });
});

document.querySelectorAll("[data-service]").forEach(function (button) {
    button.addEventListener("click", function () {
        const serviceSelect = document.getElementById("service");
        const requestedService = button.dataset.service;

        for (const option of serviceSelect.options) {
            if (option.text === requestedService) {
                serviceSelect.value = option.value;
                break;
            }
        }

        document.getElementById("contact").scrollIntoView({
            behavior: window.matchMedia("(prefers-reduced-motion: reduce)").matches
                ? "auto"
                : "smooth"
        });

        serviceSelect.focus({ preventScroll: true });
    });
});

form.addEventListener("submit", function (event) {
    event.preventDefault();
    statusBox.textContent = "";

    if (!form.reportValidity()) {
        return;
    }

    const name = document.getElementById("fullName").value.trim();
    const phone = document.getElementById("phone").value.trim();
    const service = document.getElementById("service").value;
    const details = document.getElementById("details").value.trim();

    if (name.length < 2) {
        statusBox.textContent = "Please enter your full name.";
        document.getElementById("fullName").focus();
        return;
    }

    if (!/^[6-9][0-9]{9}$/.test(phone)) {
        statusBox.textContent =
            "Enter a valid 10-digit Indian mobile number.";
        document.getElementById("phone").focus();
        return;
    }

    const subject = "New Service Request - " + service;

    const body = [
        "NEW CUSTOMER SERVICE REQUEST",
        "",
        "Business: MK ENTERPRISES",
        "Location: Hazratbal, Srinagar, Jammu & Kashmir, India",
        "Customer Name: " + name,
        "Mobile Number: +91 " + phone,
        "Requested Service: " + service,
        "",
        "Request Details:",
        details || "No additional details provided."
    ].join("\n");

    const gmailURL = new URL("https://mail.google.com/mail/");
    gmailURL.searchParams.set("view", "cm");
    gmailURL.searchParams.set("fs", "1");
    gmailURL.searchParams.set("to", "limitedmk67@gmail.com");
    gmailURL.searchParams.set("su", subject);
    gmailURL.searchParams.set("body", body);

    const emailWindow = window.open(
        gmailURL.toString(),
        "_blank",
        "noopener,noreferrer"
    );

    if (emailWindow) {
        statusBox.textContent =
            "Gmail has been requested in a new tab. Review your email and press Send.";
    } else {
        statusBox.innerHTML =
            'Your browser blocked the new tab. <a href="' +
            gmailURL.toString().replace(/&/g, "&amp;").replace(/"/g, "&quot;") +
            '" target="_blank" rel="noopener noreferrer">Click here to open your prepared Gmail message.</a>';
    }
});
</script>

</body>
</html>

