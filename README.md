
<!DOCTYPE html>
<html lang="en-IN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#101a2c">
<meta name="description" content="MK Enterprises, Hazratbal, Srinagar. Professional digital services, online forms, printing, scanning and application assistance.">
<title>MK Enterprises | Your Digital Service Partner</title>

<style>
:root {
    --navy: #101a2c;
    --navy-light: #192942;
    --gold: #d9b878;
    --gold-light: #f1dfb5;
    --white: #ffffff;
    --background: #f7f8fa;
    --text: #192437;
    --muted: #707b8d;
    --border: #e6e9ef;
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html {
    scroll-behavior: smooth;
    scroll-padding-top: 90px;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background: var(--background);
    color: var(--text);
    line-height: 1.7;
}

a {
    text-decoration: none;
    color: inherit;
}

button, input, select, textarea {
    font: inherit;
}

button, a {
    -webkit-tap-highlight-color: transparent;
}

.container {
    width: min(1160px, 90%);
    margin: auto;
}

.topbar {
    background: #0a1220;
    color: #d6dbe4;
    padding: 9px 0;
    font-size: 11px;
    letter-spacing: .5px;
}

.topbar-content {
    display: flex;
    justify-content: space-between;
    gap: 15px;
}

.header {
    background: var(--navy);
    color: white;
    position: sticky;
    top: 0;
    z-index: 100;
    border-bottom: 1px solid #ffffff15;
}

.header-content {
    min-height: 86px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 25px;
}

.brand {
    display: flex;
    align-items: center;
    gap: 13px;
}

.brand-logo {
    height: 49px;
    width: 49px;
    display: grid;
    place-items: center;
    border: 1px solid var(--gold);
    color: var(--gold-light);
    font-size: 20px;
    font-weight: 800;
    letter-spacing: -2px;
    position: relative;
}

.brand-logo::after {
    content: "";
    position: absolute;
    inset: 4px;
    border: 1px solid #d9b87855;
}

.brand-name {
    display: block;
    font-size: 15px;
    letter-spacing: 1.8px;
    font-weight: 800;
    color: white;
}

.brand-subtitle {
    display: block;
    font-size: 9px;
    letter-spacing: 2px;
    color: var(--gold);
    margin-top: 3px;
}

.nav {
    display: flex;
    align-items: center;
    gap: 27px;
    font-size: 12px;
    color: #d9deea;
}

.nav a:hover {
    color: var(--gold-light);
}

.nav .nav-button {
    padding: 12px 17px;
    border: 1px solid var(--gold);
    color: var(--gold-light);
}

.menu-button {
    display: none;
    background: none;
    color: white;
    border: 1px solid #ffffff30;
    padding: 8px 12px;
    cursor: pointer;
}

.hero {
    background:
        radial-gradient(ellipse at 82% 25%, #344562 0, transparent 36%),
        linear-gradient(125deg, #101a2c, #14223a 70%, #1b2a43);
    color: white;
    position: relative;
    overflow: hidden;
}

.hero::before {
    content: "";
    position: absolute;
    inset: 0;
    background-image:
        linear-gradient(#ffffff08 1px, transparent 1px),
        linear-gradient(90deg, #ffffff08 1px, transparent 1px);
    background-size: 48px 48px;
    pointer-events: none;
}

.hero-content {
    position: relative;
    z-index: 1;
    min-height: 570px;
    display: grid;
    grid-template-columns: 1.1fr .9fr;
    align-items: center;
    gap: 75px;
    padding-top: 65px;
    padding-bottom: 80px;
}

.eyebrow {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    color: var(--gold-light);
    letter-spacing: 2px;
    font-size: 10px;
    font-weight: bold;
}

.eyebrow::before {
    content: "";
    width: 23px;
    height: 1px;
    background: var(--gold);
}

.hero h1 {
    font-size: clamp(43px, 5.2vw, 70px);
    line-height: 1.1;
    letter-spacing: -3px;
    margin: 25px 0;
}

.hero h1 span {
    color: var(--gold-light);
}

.hero-description {
    max-width: 510px;
    color: #c0cada;
    font-size: 14px;
    line-height: 2;
}

.hero-actions {
    display: flex;
    align-items: center;
    gap: 15px;
    flex-wrap: wrap;
    margin-top: 32px;
}

.button {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
    padding: 15px 22px;
    font-size: 12px;
    font-weight: bold;
    border: 1px solid transparent;
    cursor: pointer;
    transition: .2s ease;
}

.button:hover {
    transform: translateY(-2px);
}

.button-gold {
    background: var(--gold-light);
    color: var(--navy);
}

.button-gold:hover {
    background: white;
}

.button-outline {
    border-color: #ffffff45;
    color: white;
}

.button-outline:hover {
    border-color: var(--gold);
    color: var(--gold-light);
}

.hero-note {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
    margin-top: 35px;
    font-size: 10px;
    color: #c7cfdd;
}

.hero-note span::first-letter {
    color: var(--gold);
}

.hero-panel {
    background: white;
    color: var(--text);
    padding: 30px;
    box-shadow: 0 30px 90px #0004;
    position: relative;
}

.panel-top {
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 1px solid var(--border);
    padding-bottom: 20px;
}

.panel-top strong {
    font-size: 12px;
    letter-spacing: 1px;
}

.panel-badge {
    font-size: 9px;
    background: #f4eddf;
    color: #8c6b31;
    padding: 7px 10px;
}

.panel-heading {
    font-size: 25px;
    line-height: 1.35;
    margin: 25px 0 9px;
    letter-spacing: -.7px;
}

.panel-description {
    font-size: 11px;
    color: var(--muted);
    margin-bottom: 20px;
}

.panel-service {
    display: flex;
    gap: 14px;
    align-items: center;
    padding: 15px 0;
    border-top: 1px solid var(--border);
}

.panel-icon {
    height: 39px;
    width: 39px;
    display: grid;
    place-items: center;
    background: #f3efe6;
    color: #9b7a3f;
    font-size: 17px;
    flex-shrink: 0;
}

.panel-service strong {
    display: block;
    font-size: 12px;
}

.panel-service small {
    display: block;
    color: var(--muted);
    font-size: 10px;
    margin-top: 3px;
}

.panel-footer {
    background: var(--navy);
    color: #dce2ed;
    padding: 15px;
    margin: 20px -30px -30px;
    font-size: 10px;
    text-align: center;
}

.panel-footer span {
    color: var(--gold-light);
}

.section {
    padding: 90px 0;
}

.section-label {
    color: #96743b;
    font-size: 10px;
    font-weight: bold;
    letter-spacing: 2px;
}

.section-title {
    font-size: clamp(30px, 4vw, 43px);
    line-height: 1.2;
    letter-spacing: -1.5px;
    margin-top: 13px;
    color: var(--navy);
}

.section-title span {
    color: #a17e42;
}

.section-intro {
    color: var(--muted);
    font-size: 13px;
    max-width: 520px;
    line-height: 1.9;
    margin-top: 17px;
}

.section-header {
    display: flex;
    align-items: end;
    justify-content: space-between;
    gap: 35px;
    margin-bottom: 40px;
}

.services-section {
    background: white;
}

.services-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 17px;
}

.service-card {
    border: 1px solid var(--border);
    padding: 27px;
    background: #fff;
    position: relative;
    transition: .25s ease;
}

.service-card:hover {
    transform: translateY(-5px);
    border-color: #d4b575;
    box-shadow: 0 15px 40px #17233a0b;
}

.service-card-top {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 23px;
}

.service-icon {
    width: 45px;
    height: 45px;
    display: grid;
    place-items: center;
    background: #f4efe4;
    color: #94713a;
    font-size: 21px;
}

.service-number {
    color: #aeb4bf;
    font-size: 11px;
}

.service-card h3 {
    font-size: 16px;
    margin-bottom: 10px;
}

.service-card p {
    color: var(--muted);
    font-size: 12px;
    line-height: 1.9;
    min-height: 68px;
}

.service-link {
    display: inline-block;
    margin-top: 17px;
    color: #8b6a34;
    font-size: 11px;
    font-weight: bold;
    background: none;
    border: 0;
    cursor: pointer;
}

.service-link span {
    margin-left: 8px;
}

.disclaimer {
    background: #f7f3e9;
    border-left: 3px solid var(--gold);
    padding: 18px 20px;
    margin-top: 25px;
    color: #716750;
    font-size: 11px;
    line-height: 1.9;
}

.process-section {
    background: var(--background);
}

.steps {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    margin-top: 40px;
    border-top: 1px solid #dfe3ea;
}

.step {
    padding: 30px 28px 10px 0;
}

.step + .step {
    padding-left: 28px;
    border-left: 1px solid #dfe3ea;
}

.step-number {
    color: #a27e3e;
    font-size: 12px;
    font-weight: bold;
}

.step h3 {
    font-size: 19px;
    margin: 15px 0 9px;
}

.step p {
    color: var(--muted);
    font-size: 12px;
    line-height: 1.9;
    max-width: 280px;
}

.contact-section {
    background: var(--navy);
    color: white;
}

.contact-layout {
    display: grid;
    grid-template-columns: .85fr 1.15fr;
    gap: 75px;
    align-items: start;
}

.contact-section .section-title {
    color: white;
}

.contact-section .section-title span {
    color: var(--gold-light);
}

.contact-section .section-intro {
    color: #c0cada;
}

.contact-email {
    margin-top: 30px;
    padding: 20px;
    border: 1px solid #ffffff22;
    display: flex;
    gap: 15px;
    align-items: center;
    overflow-wrap: anywhere;
}

.email-icon {
    height: 43px;
    width: 43px;
    border: 1px solid #d9b87877;
    display: grid;
    place-items: center;
    color: var(--gold-light);
    flex-shrink: 0;
}

.contact-email small {
    display: block;
    color: #b4bfd0;
    font-size: 9px;
    letter-spacing: 1px;
}

.contact-email strong {
    color: var(--gold-light);
    font-size: 12px;
    display: block;
    margin-top: 5px;
}

.privacy-note {
    margin-top: 25px;
    font-size: 11px;
    color: #b4bfd0;
    line-height: 1.9;
}

.privacy-note strong {
    color: white;
}

.request-form {
    background: white;
    color: var(--text);
    padding: 32px;
}

.form-heading {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 10px;
    padding-bottom: 20px;
    border-bottom: 1px solid var(--border);
    margin-bottom: 20px;
}

.form-heading strong {
    font-size: 12px;
    letter-spacing: .8px;
}

.form-heading small {
    font-size: 10px;
    color: var(--muted);
}

.request-form label {
    display: block;
    font-size: 11px;
    font-weight: bold;
    margin: 17px 0 8px;
}

.request-form label span {
    color: #9a7b43;
}

.request-form input:not([type="checkbox"]),
.request-form select,
.request-form textarea {
    width: 100%;
    padding: 13px 14px;
    border: 1px solid #dce1e8;
    background: #fff;
    color: var(--text);
    border-radius: 0;
    font-size: 12px;
}

.request-form input:focus,
.request-form select:focus,
.request-form textarea:focus {
    outline: 2px solid #d9b878;
    outline-offset: 1px;
}

.request-form textarea {
    resize: vertical;
    min-height: 100px;
}

.phone-wrap {
    display: flex;
    border: 1px solid #dce1e8;
}

.phone-prefix {
    background: #f1eee6;
    padding: 12px;
    font-size: 12px;
    white-space: nowrap;
}

.phone-wrap input {
    border: 0 !important;
    min-width: 0;
}

.consent {
    display: flex !important;
    align-items: flex-start;
    gap: 10px;
    font-weight: normal !important;
    color: #687386;
    line-height: 1.8;
}

.consent input {
    margin-top: 4px;
    accent-color: #a17e42;
}

.consent span {
    color: #687386 !important;
    font-weight: normal;
}

.submit-button {
    width: 100%;
    margin-top: 15px;
}

.form-note {
    font-size: 10px;
    color: #737d8e;
    line-height: 1.8;
    margin-top: 13px;
}

.form-status {
    font-size: 12px;
    line-height: 1.7;
    margin-top: 12px;
    overflow-wrap: anywhere;
}

.about-section {
    background: white;
}

.about-layout {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 65px;
    align-items: center;
}

.about-box {
    background: var(--navy);
    color: white;
    padding: 35px;
    border-bottom: 3px solid var(--gold);
}

.about-box h3 {
    color: var(--gold-light);
    font-size: 21px;
    margin-bottom: 15px;
}

.about-box p {
    font-size: 12px;
    color: #c0cada;
    line-height: 2;
}

.about-copy {
    font-size: 13px;
    color: var(--muted);
    line-height: 2;
    margin-top: 18px;
}

footer {
    background: #080f1c;
    color: #b9c2d1;
    padding: 30px 0;
}

.footer-layout {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 25px;
    flex-wrap: wrap;
}

.footer-brand {
    color: var(--gold-light);
    font-weight: bold;
    letter-spacing: 1px;
    font-size: 12px;
}

footer p {
    font-size: 10px;
    line-height: 1.8;
}

footer a:last-child {
    font-size: 11px;
    color: var(--gold-light);
}

@media (max-width: 900px) {
    .hero-content {
        gap: 35px;
    }

    .services-grid {
        grid-template-columns: repeat(2, 1fr);
    }

    .contact-layout {
        gap: 35px;
    }
}

@media (max-width: 650px) {
    .container {
        width: 90%;
    }

    .topbar-content {
        font-size: 9px;
    }

    .topbar-content span:last-child {
        text-align: right;
    }

    .header-content {
        min-height: 74px;
    }

    .brand-logo {
        width: 42px;
        height: 42px;
    }

    .brand-name {
        font-size: 12px;
    }

    .brand-subtitle {
        font-size: 8px;
        letter-spacing: 1.3px;
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
        padding: 22px 5%;
        background: var(--navy);
        flex-direction: column;
        align-items: stretch;
        gap: 18px;
        border-top: 1px solid #ffffff20;
    }

    .nav.open {
        display: flex;
    }

    .nav .nav-button {
        text-align: center;
    }

    .hero-content {
        grid-template-columns: 1fr;
        padding-top: 65px;
        padding-bottom: 65px;
        gap: 45px;
    }

    .hero h1 {
        font-size: 48px;
        letter-spacing: -2px;
    }

    .hero-panel {
        padding: 24px;
    }

    .panel-footer {
        margin: 20px -24px -24px;
    }

    .section {
        padding: 65px 0;
    }

    .section-header {
        display: block;
    }

    .section-header .section-intro {
        margin-top: 15px;
    }

    .services-grid {
        grid-template-columns: 1fr;
    }

    .service-card p {
        min-height: 0;
    }

    .steps {
        grid-template-columns: 1fr;
    }

    .step,
    .step + .step {
        padding: 24px 0;
        border-left: 0;
        border-bottom: 1px solid #dfe3ea;
    }

    .contact-layout,
    .about-layout {
        grid-template-columns: 1fr;
        gap: 35px;
    }

    .request-form {
        padding: 23px 18px;
    }

    .form-heading {
        align-items: flex-start;
        flex-direction: column;
    }

    .footer-layout {
        flex-direction: column;
        align-items: flex-start;
    }
}

@media (prefers-reduced-motion: reduce) {
    html {
        scroll-behavior: auto;
    }

    *,
    *::before,
    *::after {
        transition: none !important;
    }
}
</style>
</head>

<body>

<div class="topbar">
    <div class="container topbar-content">
        <span>PROFESSIONAL DIGITAL ASSISTANCE</span>
        <span>HAZRATBAL, SRINAGAR · INDIA</span>
    </div>
</div>

<header class="header">
    <div class="container header-content">
        <a href="#home" class="brand" aria-label="MK Enterprises home">
            <span class="brand-logo">MK</span>
            <span>
                <span class="brand-name">MK ENTERPRISES</span>
                <span class="brand-subtitle">ONLINE DIGITAL SERVICES</span>
            </span>
        </a>

        <button class="menu-button" id="menuButton"
                aria-label="Open navigation"
                aria-expanded="false"
                aria-controls="navigation">☰</button>

        <nav class="nav" id="navigation" aria-label="Main navigation">
            <a href="#home">Home</a>
            <a href="#services">Services</a>
            <a href="#process">How It Works</a>
            <a href="#about">About Us</a>
            <a href="#contact" class="nav-button">Request Service ↗</a>
        </nav>
    </div>
</header>

<main>
<section class="hero" id="home">
    <div class="container hero-content">
        <div>
            <div class="eyebrow">YOUR DIGITAL SERVICE PARTNER</div>

            <h1>Smart Digital<br><span>Solutions.</span></h1>

            <p class="hero-description">
                From online applications to document services,
                MK Enterprises helps make everyday digital tasks
                simpler, clearer and more convenient.
                Based in Hazratbal, Srinagar, Jammu & Kashmir.
            </p>

            <div class="hero-actions">
                <a href="#contact" class="button button-gold">
                    Request a Service ↗
                </a>

                <a href="#services" class="button button-outline">
                    Explore Services
                </a>
            </div>

            <div class="hero-note">
                <span>✓ Clear communication</span>
                <span>✓ Email-based requests</span>
                <span>✓ India-focused assistance</span>
            </div>
        </div>

        <aside class="hero-panel">
            <div class="panel-top">
                <strong>MK SERVICE DESK</strong>
                <span class="panel-badge">DIGITAL ASSISTANCE</span>
            </div>

            <h2 class="panel-heading">
                Your task.<br>Our assistance.
            </h2>

            <p class="panel-description">
                Tell us what you need help with.
            </p>

            <div class="panel-service">
                <span class="panel-icon">▤</span>
                <div>
                    <strong>Forms & Applications</strong>
                    <small>Application and registration assistance</small>
                </div>
            </div>

            <div class="panel-service">
                <span class="panel-icon">▧</span>
                <div>
                    <strong>Documents & Printing</strong>
                    <small>Scanning, printing and PDF support</small>
                </div>
            </div>

            <div class="panel-service">
                <span class="panel-icon">◎</span>
                <div>
                    <strong>Digital Services</strong>
                    <small>Practical online assistance</small>
                </div>
            </div>

            <div class="panel-footer">
                <span>MK ENTERPRISES</span> · HAZRATBAL, SRINAGAR
            </div>
        </aside>
    </div>
</section>

<section class="section services-section" id="services">
    <div class="container">
        <div class="section-header">
            <div>
                <div class="section-label">OUR SERVICES</div>
                <h2 class="section-title">
                    Everything starts<br><span>with the right support.</span>
                </h2>
            </div>

            <p class="section-intro">
                Select a service to begin your request.
                Actual availability, eligibility, fees and approvals
                depend on the relevant service provider or authority.
            </p>
        </div>

        <div class="services-grid">

            <article class="service-card">
                <div class="service-card-top">
                    <span class="service-icon">▤</span>
                    <span class="service-number">01 / FORMS</span>
                </div>
                <h3>Online Forms & Applications</h3>
                <p>Assistance with online forms, admissions, examination applications and registrations.</p>
                <button class="service-link" data-service="Online forms and applications">
                    Select service <span>↗</span>
                </button>
            </article>

            <article class="service-card">
                <div class="service-card-top">
                    <span class="service-icon">▧</span>
                    <span class="service-number">02 / DOCUMENTS</span>
                </div>
                <h3>Printing & Document Services</h3>
                <p>Printing, scanning, photocopying, lamination, PDF conversion and document formatting.</p>
                <button class="service-link" data-service="Printing and document services">
                    Select service <span>↗</span>
                </button>
            </article>

            <article class="service-card">
                <div class="service-card-top">
                    <span class="service-icon">◎</span>
                    <span class="service-number">03 / PHOTOS</span>
                </div>
                <h3>Photo Services</h3>
                <p>Passport-size photo preparation, photo editing and photo-frame requests.</p>
                <button class="service-link" data-service="Photo services">
                    Select service <span>↗</span>
                </button>
            </article>

            <article class="service-card">
                <div class="service-card-top">
                    <span class="service-icon">▣</span>
                    <span class="service-number">04 / APPLICATIONS</span>
                </div>
                <h3>PAN & Passport Assistance</h3>
                <p>Application guidance and document preparation for eligible services.</p>
                <button class="service-link" data-service="PAN and passport assistance">
                    Select service <span>↗</span>
                </button>
            </article>

            <article class="service-card">
                <div class="service-card-top">
                    <span class="service-icon">⌘</span>
                    <span class="service-number">05 / PORTALS</span>
                </div>
                <h3>Government & Transport Portals</h3>
                <p>Assistance navigating relevant official government and Parivahan portals.</p>
                <button class="service-link" data-service="Government and transport portals">
                    Select service <span>↗</span>
                </button>
            </article>

            <article class="service-card">
                <div class="service-card-top">
                    <span class="service-icon">＋</span>
                    <span class="service-number">06 / OTHER</span>
                </div>
                <h3>Other Digital Services</h3>
                <p>Have another online task? Send your request and we will review it.</p>
                <button class="service-link" data-service="Other digital services">
                    Select service <span>↗</span>
                </button>
            </article>

        </div>

        <div class="disclaimer">
            <strong>Service notice:</strong>
            MK Enterprises is an independent digital-assistance business,
            not a government department. Government services, official fees,
            eligibility and approvals remain subject to the relevant authority.
            Authorisation is not implied.
        </div>
    </div>
</section>

<section class="section process-section" id="process">
    <div class="container">
        <div class="section-label">HOW IT WORKS</div>

        <h2 class="section-title">
            Simple steps.<br><span>Clear communication.</span>
        </h2>

        <div class="steps">
            <article class="step">
                <span class="step-number">STEP 01</span>
                <h3>Choose your service</h3>
                <p>Select the digital service you need help with.</p>
            </article>

            <article class="step">
                <span class="step-number">STEP 02</span>
                <h3>Share your request</h3>
                <p>Enter your name, Indian mobile number and basic request details.</p>
            </article>

            <article class="step">
                <span class="step-number">STEP 03</span>
                <h3>Send your email</h3>
                <p>Review the prepared email and press Send in your email application.</p>
            </article>
        </div>
    </div>
</section>

<section class="section contact-section" id="contact">
    <div class="container contact-layout">
        <div>
            <div class="section-label">CONTACT OUR SERVICE DESK</div>

            <h2 class="section-title">
                How can we<br><span>help you today?</span>
            </h2>

            <p class="section-intro">
                Submit your service request using the form.
                Your email application will open with the details prepared.
            </p>

            <div class="contact-email">
                <span class="email-icon">✉</span>
                <div>
                    <small>OFFICIAL CONTACT EMAIL</small>
                    <strong>limitedmk67@gmail.com</strong>
                </div>
            </div>

            <div class="privacy-note">
                <strong>Privacy reminder</strong><br>
                Do not include passwords, OTPs, Aadhaar numbers,
                bank details or sensitive identity information.
                The form does not upload or store your information on a server.
            </div>
        </div>

        <form class="request-form" id="serviceForm">
            <div class="form-heading">
                <strong>NEW SERVICE REQUEST</strong>
                <small>* Required fields</small>
            </div>

            <label for="fullName">Full Name <span>*</span></label>
            <input
                id="fullName"
                name="fullName"
                type="text"
                maxlength="80"
                autocomplete="name"
                required
            >

            <label for="phone">Indian Mobile Number <span>*</span></label>
            <div class="phone-wrap">
                <span class="phone-prefix">+91 🇮🇳</span>
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

            <label for="service">Service Required <span>*</span></label>
            <select id="service" name="service" required>
                <option value="">Choose a service</option>
                <option>Online forms and applications</option>
                <option>Printing and document services</option>
                <option>Photocopy and lamination</option>
                <option>Photo services</option>
                <option>PAN and passport assistance</option>
                <option>Government and transport portals</option>
                <option>Admissions and examination forms</option>
                <option>Registration assistance</option>
                <option>Other digital services</option>
            </select>

            <label for="details">Request Details</label>
            <textarea
                id="details"
                name="details"
                maxlength="1000"
                rows="4"
                placeholder="Briefly describe the assistance you need."
            ></textarea>

            <label class="consent">
                <input type="checkbox" id="consent" required>
                <span>I confirm my details are correct and agree to open my email application to send this request.</span>
            </label>

            <button type="submit" class="button button-gold submit-button">
                Prepare Email Request ↗
            </button>

            <p class="form-note">
                This form prepares an email; it does not send it automatically.
                Review the message and press Send in your email application.
            </p>

            <p class="form-status" id="status" role="status" aria-live="polite"></p>
        </form>
    </div>
</section>

<section class="section about-section" id="about">
    <div class="container about-layout">
        <div>
            <div class="section-label">ABOUT MK ENTERPRISES</div>

            <h2 class="section-title">
                Local assistance.<br><span>Professional approach.</span>
            </h2>

            <p class="about-copy">
                MK Enterprises is an online digital-service assistance
                business based in Hazratbal, Srinagar, Jammu & Kashmir, India.
                Our aim is to make common digital tasks easier through
                practical assistance and clear communication.
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
    <div class="container footer-layout">
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

```html
<script>
"use strict";

const form = document.getElementById("serviceForm");
const status = document.getElementById("status");

document.getElementById("year").textContent =
    new Date().getFullYear();

document.querySelectorAll("[data-service]").forEach(function(button) {
    button.addEventListener("click", function() {
        document.getElementById("service").value =
            button.dataset.service;

        document.getElementById("contact").scrollIntoView({
            behavior: "smooth"
        });
    });
});

form.addEventListener("submit", function(event) {
    event.preventDefault();

    if (!form.reportValidity()) {
        return;
    }

    const name = document.getElementById("fullName").value.trim();
    const phone = document.getElementById("phone").value.trim();
    const service = document.getElementById("service").value;
    const details = document.getElementById("details").value.trim();

    if (name.length < 2) {
        status.textContent = "Please enter your full name.";
        return;
    }

    if (!/^[6-9][0-9]{9}$/.test(phone)) {
        status.textContent =
            "Enter a valid 10-digit Indian mobile number.";
        return;
    }

    const subject = "New Service Request - " + service;

    const body = [
        "NEW CUSTOMER SERVICE REQUEST",
        "",
        "Business: MK ENTERPRISES",
        "Customer Name: " + name,
        "Mobile Number: +91 " + phone,
        "Requested Service: " + service,
        "",
        "Request Details:",
        details || "No additional details provided."
    ].join("\n");

    const gmailURL =
        "https://mail.google.com/mail/?view=cm&fs=1" +
        "&to=" + encodeURIComponent("limitedmk67@gmail.com") +
        "&su=" + encodeURIComponent(subject) +
        "&body=" + encodeURIComponent(body);

    status.textContent =
        "Opening Gmail with your service request...";

    window.open(gmailURL, "_blank", "noopener,noreferrer");
});
</script>



</body>
</html>

