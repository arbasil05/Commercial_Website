# Ex02 Commercial Website
## Date: 07-05-2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
### HTML:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aurora Market</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="topbar">
    <a class="brand" href="#home">Aurora Market</a>
    <nav class="nav">
      <a href="#home">Home</a>
      <a href="#products">Products</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
      <a href="#account">Account</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="hero-copy">
        <span class="eyebrow">Modern essentials for daily life</span>
        <h1>Designed to make everyday shopping feel effortless.</h1>
        <p>
          Aurora Market brings together curated products, reliable service, and a clean buying experience built for busy people.
        </p>
        <div class="hero-actions">
          <a class="button button-primary" href="#products">Shop collection</a>
          <a class="button button-secondary" href="#about">Learn more</a>
        </div>
        <div class="hero-stats">
          <div>
            <strong>120K+</strong>
            <span>happy customers</span>
          </div>
          <div>
            <strong>48h</strong>
            <span>average delivery</span>
          </div>
          <div>
            <strong>4.9/5</strong>
            <span>customer rating</span>
          </div>
        </div>
      </div>

      <div class="hero-visual">
        <img src="https://images.unsplash.com/photo-1491553895911-0055eca6402d?auto=format&fit=crop&w=900&q=80" alt="Retail products arranged for a clean storefront display" width="900" height="1100">
        <div class="floating-card card-one">
          <span>New season drop</span>
          <strong>Up to 30% off</strong>
        </div>
        <div class="floating-card card-two">
          <span>Delivery</span>
          <strong>Tracked and fast</strong>
        </div>
      </div>
    </section>

    <section class="section products-section" id="products">
      <div class="section-heading">
        <span class="eyebrow">Products and services</span>
        <h2>Handpicked categories that cover the essentials.</h2>
      </div>
      <div class="product-grid">
        <article class="product-card">
          <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?auto=format&fit=crop&w=800&q=80" alt="Premium headphones" width="800" height="600">
          <div>
            <h3>Audio gear</h3>
            <p>Headphones, speakers, and accessories built for work and travel.</p>
          </div>
        </article>
        <article class="product-card">
          <img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?auto=format&fit=crop&w=800&q=80" alt="Skincare products" width="800" height="600">
          <div>
            <h3>Wellness care</h3>
            <p>Daily essentials for self-care, comfort, and a balanced routine.</p>
          </div>
        </article>
        <article class="product-card">
          <img src="https://images.unsplash.com/photo-1499951360447-b19be8fe80f5?auto=format&fit=crop&w=800&q=80" alt="Home and office product setup" width="800" height="600">
          <div>
            <h3>Home setup</h3>
            <p>Pieces that make your space cleaner, calmer, and more useful.</p>
          </div>
        </article>
      </div>
    </section>

    <section class="section split-section" id="about">
      <div class="section-heading">
        <span class="eyebrow">About us</span>
        <h2>Built around clarity, quality, and service.</h2>
        <p>
          We focus on a simple promise: make the store easy to browse, easy to trust, and easy to come back to.
        </p>
      </div>
      <div class="about-panel">
        <div class="feature-row">
          <strong>01</strong>
          <div>
            <h3>Curated selection</h3>
            <p>We keep the catalog tight so the experience stays focused and useful.</p>
          </div>
        </div>
        <div class="feature-row">
          <strong>02</strong>
          <div>
            <h3>Responsive support</h3>
            <p>Support is available across common channels whenever you need help.</p>
          </div>
        </div>
        <div class="feature-row">
          <strong>03</strong>
          <div>
            <h3>Secure checkout</h3>
            <p>Transactions are designed to feel straightforward and dependable.</p>
          </div>
        </div>
      </div>
    </section>

    <section class="section contact-account">
      <div class="contact-card" id="contact">
        <span class="eyebrow">Contact details</span>
        <h2>Reach us when you need assistance.</h2>
        <div class="contact-list">
          <p><strong>Email</strong> support@auroramarket.com</p>
          <p><strong>Phone</strong> +1 (555) 018-2480</p>
          <p><strong>Address</strong> 24 Commerce Avenue, New York</p>
        </div>
      </div>

      <div class="account-card" id="account">
        <span class="eyebrow">User account</span>
        <h2>Track orders, manage saved items, and update details.</h2>
        <form class="account-form">
          <label>
            Email address
            <input type="email" name="email" placeholder="you@example.com">
          </label>
          <label>
            Password
            <input type="password" name="password" placeholder="Enter your password">
          </label>
          <button type="submit" class="button button-primary">Sign in</button>
        </form>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div>
      <strong>Aurora Market</strong>
      <p>Fresh collections, clear service, and a store experience that feels calm.</p>
    </div>
    <div class="socials">
      <a href="https://www.facebook.com" target="_blank" rel="noreferrer">Facebook</a>
      <a href="https://www.instagram.com" target="_blank" rel="noreferrer">Instagram</a>
      <a href="https://www.twitter.com" target="_blank" rel="noreferrer">X</a>
    </div>
    <p class="copyright">&copy; 2026 Aurora Market. All rights reserved.</p>
  </footer>
</body>
</html>
```
### CSS:
```css
:root {
  --bg: #ffffff;
  --surface: #f2f2f2;
  --surface-strong: #ffffff;
  --text: #222222;
  --muted: #666666;
  --accent: #d97706;
  --accent-dark: #b45309;
  --line: #cfcfcf;
}

* {
  box-sizing: border-box;
}

html {
  scroll-behavior: auto;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  color: var(--text);
  background: var(--bg);
}

img {
  display: block;
  max-width: 100%;
}

a {
  color: inherit;
  text-decoration: none;
}

.topbar {
  width: min(1180px, calc(100% - 32px));
  margin: 20px auto 0;
  padding: 14px 16px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 20px;
  border: 1px solid var(--line);
  border-radius: 4px;
  background: var(--surface);
}

.brand {
  font-size: 1.2rem;
  font-weight: 700;
}

.nav {
  display: flex;
  flex-wrap: wrap;
  gap: 18px;
}

.nav a {
  color: var(--muted);
  font-weight: 600;
}

main {
  width: min(1180px, calc(100% - 32px));
  margin: 24px auto 0;
}

.hero,
.section,
.contact-account {
  display: flex;
  gap: 20px;
}

.hero {
  align-items: center;
  padding: 32px 0 16px;
}

.hero-copy,
.section-heading,
.about-panel,
.contact-card,
.account-card {
  flex: 1;
}

.hero-copy h1,
.section-heading h2,
.contact-card h2,
.account-card h2 {
  margin: 10px 0 0;
  line-height: 1.02;
  font-weight: 700;
}

.hero-copy h1 {
  max-width: 12ch;
  font-size: clamp(2.2rem, 6vw, 4rem);
}

.section-heading h2,
.contact-card h2,
.account-card h2 {
  font-size: clamp(1.5rem, 3vw, 2.2rem);
}

.hero-copy p,
.section-heading p,
.product-card p,
.feature-row p,
.contact-list p,
.footer p {
  color: var(--muted);
  line-height: 1.65;
}

.eyebrow {
  display: inline-block;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  font-size: 0.75rem;
  font-weight: 800;
  color: var(--accent-dark);
}

.hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 18px;
}

.button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 40px;
  padding: 0 14px;
  border-radius: 2px;
  border: 1px solid #999999;
  font-weight: 700;
}

.button-primary {
  background: var(--accent);
  color: #ffffff;
  border-color: var(--accent-dark);
}

.button-secondary {
  background: #ffffff;
  border-color: var(--line);
}

.hero-stats {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 20px;
}

.hero-stats div {
  min-width: 130px;
  padding: 10px 12px;
  border: 1px solid var(--line);
  border-radius: 2px;
  background: #ffffff;
}

.hero-stats strong {
  display: block;
  font-size: 1.35rem;
}

.hero-stats span {
  color: var(--muted);
  font-size: 0.95rem;
}

.hero-visual {
  position: relative;
  flex: 1;
  min-height: 560px;
}

.hero-visual img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 4px;
  border: 1px solid var(--line);
}

.floating-card {
  position: absolute;
  padding: 10px 12px;
  border-radius: 2px;
  background: #ffffff;
  border: 1px solid var(--line);
}

.floating-card span {
  display: block;
  color: var(--muted);
  font-size: 0.85rem;
}

.floating-card strong {
  display: block;
  margin-top: 4px;
  font-size: 1rem;
}

.card-one {
  left: 8px;
  top: 12px;
}

.card-two {
  right: 8px;
  bottom: 12px;
}

.section {
  align-items: stretch;
  padding: 48px 0 0;
}

.products-section {
  flex-direction: column;
}

.products-section .product-grid {
  width: 100%;
  margin-top: 12px;
}

.section-heading {
  max-width: 560px;
}

.product-grid {
  flex: 1.4;
  display: flex;
  gap: 12px;
}

.product-card {
  flex: 1;
  overflow: hidden;
  border-radius: 4px;
  background: var(--surface-strong);
  border: 1px solid var(--line);
}

.product-card img {
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: cover;
}

.product-card div {
  padding: 12px;
}

.product-card h3,
.feature-row h3 {
  margin: 0 0 8px;
  font-size: 1.2rem;
}

.split-section {
  align-items: flex-start;
}

.about-panel {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.feature-row {
  display: flex;
  gap: 12px;
  padding: 12px;
  border-radius: 4px;
  background: #ffffff;
  border: 1px solid var(--line);
}

.feature-row strong {
  font-size: 0.95rem;
  color: var(--accent-dark);
}

.contact-account {
  padding: 48px 0;
}

.contact-card,
.account-card {
  padding: 16px;
  border-radius: 4px;
  background: #ffffff;
  border: 1px solid var(--line);
}

.contact-list {
  margin-top: 12px;
}

.contact-list p {
  margin: 0 0 12px;
}

.account-form {
  display: flex;
  flex-direction: column;
  gap: 10px;
  margin-top: 12px;
}

.account-form label {
  display: flex;
  flex-direction: column;
  gap: 4px;
  font-weight: 600;
}

.account-form input {
  width: 100%;
  min-height: 36px;
  padding: 0 10px;
  border-radius: 2px;
  border: 1px solid #aaaaaa;
  background: #fff;
  font: inherit;
}

.account-form input:focus {
  outline: 1px solid var(--accent);
  border-color: var(--accent);
}

.footer {
  width: min(1180px, calc(100% - 32px));
  margin: 0 auto;
  padding: 16px 0 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
  border-top: 1px solid var(--line);
}

.footer strong {
  display: block;
  font-size: 1.1rem;
}

.socials {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  font-weight: 600;
}

.socials a {
  color: var(--muted);
}

.copyright {
  margin: 0;
  white-space: nowrap;
}

@media (max-width: 980px) {
  .topbar,
  .hero,
  .section,
  .contact-account,
  .footer {
    flex-direction: column;
    align-items: flex-start;
  }

  .hero-visual {
    width: 100%;
    min-height: 460px;
  }

  .product-grid {
    width: 100%;
    flex-direction: column;
  }

  .copyright {
    white-space: normal;
  }
}

@media (max-width: 640px) {
  .topbar {
    border-radius: 4px;
    padding: 12px;
  }

  .nav {
    gap: 12px;
  }

  .hero,
  .section,
  .contact-account {
    padding-top: 32px;
  }

  .hero-copy h1 {
    font-size: 2.4rem;
  }

  .hero-visual {
    min-height: 360px;
  }

  .floating-card {
    display: none;
  }

  .contact-card,
  .account-card,
  .feature-row,
  .product-card {
    border-radius: 4px;
  }
}
```




## OUTPUT:
<img width="1565" height="825" alt="image" src="https://github.com/user-attachments/assets/b4a04ccb-8396-45ee-9d27-80a806dce17c" />
<img width="1241" height="867" alt="image" src="https://github.com/user-attachments/assets/5623c1ae-d76f-4409-bcd2-dbc7819d9ee1" />
<img width="1276" height="864" alt="image" src="https://github.com/user-attachments/assets/530b9fb6-018b-4091-b7d6-03661a5ef059" />





## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
