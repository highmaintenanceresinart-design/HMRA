# HMRA
Kats website
<!-- index.html -->
<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>High Maintenance Resin Art</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>

  <!-- Top utility / announcement -->
  <div class="topbar">
    <div class="container topbar__inner">
      <p class="topbar__msg">Custom resin statement pieces • Crystal edges • Iridescent finishes • Made one-of-one</p>
      <div class="topbar__right">
        <span class="topbar__currency" aria-label="Currency selector">USD ▾</span>
        <span class="topbar__icons" aria-label="Social links">
          <a href="#" aria-label="Instagram" class="icon-link">IG</a>
          <a href="#" aria-label="TikTok" class="icon-link">TT</a>
          <a href="#" aria-label="Etsy" class="icon-link">ET</a>
        </span>
      </div>
    </div>
  </div>

  <!-- Header -->
  <header class="header">
    <div class="container header__inner">
      <nav class="header__nav header__nav--left" aria-label="Primary">
        <a class="navlink" href="#about">About</a>
        <a class="navlink" href="#contact">Contact</a>
        <a class="navlink" href="#faq">FAQ</a>
      </nav>

      <a class="brand" href="#">
        <div class="brand__mark" aria-hidden="true"></div>
        <div class="brand__text">
          <div class="brand__name">High Maintenance Resin Art</div>
          <div class="brand__tag">one-of-one statement pieces</div>
        </div>
      </a>

      <div class="header__actions" aria-label="Site tools">
        <button class="iconbtn" type="button" aria-label="Search">🔎</button>
        <button class="iconbtn" type="button" aria-label="Account">👤</button>
        <button class="iconbtn" type="button" aria-label="Cart">🛒</button>
      </div>
    </div>

    <!-- Secondary nav -->
    <div class="subnav">
      <div class="container subnav__inner">
        <a class="subnav__link" href="#collection">SEA & STONE COLLECTION</a>
        <div class="subnav__divider" aria-hidden="true"></div>
        <a class="subnav__link" href="#shop">SHOP ▾</a>
        <a class="subnav__link" href="#blog">BLOG</a>
      </div>
    </div>
  </header>

  <main>

    <!-- Hero -->
    <section class="hero" aria-label="Hero">
      <div class="hero__bg" aria-hidden="true"></div>
      <div class="container hero__inner">
        <p class="hero__kicker">FUNCTIONAL ART</p>
        <h1 class="hero__title">RESIN FLOWS LIKE CREATIVITY</h1>
        <p class="hero__subtitle">Iridescent. Luxurious. Built to be unrepeatable — every piece is uniquely yours.</p>
        <div class="hero__cta">
          <a class="btn btn--primary" href="#collection">Explore Collection</a>
          <a class="btn btn--ghost" href="#custom">Custom Order Request</a>
        </div>
      </div>
    </section>

    <!-- Collection grid -->
    <section id="collection" class="section section--cream">
      <div class="container">
        <div class="section__heading">
          <h2 class="section__title">SEA & STONE COLLECTION</h2>
        </div>

        <div class="product-grid">
          <article class="product-card">
            <a href="#" class="product-card__media" aria-label="Golden Riverbed">
              <img src="https://via.placeholder.com/640x760" alt="Placeholder product photo: Golden Riverbed resin tray" />
            </a>
            <div class="product-card__meta">
              <h3 class="product-card__name">Golden Riverbed</h3>
              <p class="product-card__price">$289+</p>
            </div>
          </article>

          <article class="product-card">
            <a href="#" class="product-card__media" aria-label="The Gilt Shore">
              <img src="https://via.placeholder.com/640x760" alt="Placeholder product photo: The Gilt Shore resin geode panel" />
            </a>
            <div class="product-card__meta">
              <h3 class="product-card__name">The Gilt Shore</h3>
              <p class="product-card__price">$349+</p>
            </div>
          </article>

          <article class="product-card">
            <a href="#" class="product-card__media" aria-label="The Eternal Tide">
              <img src="https://via.placeholder.com/640x760" alt="Placeholder product photo: The Eternal Tide resin wall art" />
            </a>
            <div class="product-card__meta">
              <h3 class="product-card__name">The Eternal Tide</h3>
              <p class="product-card__price">$399+</p>
            </div>
          </article>

          <article class="product-card">
            <a href="#" class="product-card__media" aria-label="Pink Code Tool Chest">
              <img src="https://via.placeholder.com/640x760" alt="Placeholder product photo: Artified cobalt toolbox" />
            </a>
            <div class="product-card__meta">
              <h3 class="product-card__name">Artified Cobalt Toolbox</h3>
              <p class="product-card__price">$450+</p>
            </div>
          </article>
        </div>
      </div>
    </section>

    <!-- Feature blocks (image + text) -->
    <section class="section section--cream" id="custom">
      <div class="container feature">
        <div class="feature__text">
          <p class="eyebrow">ELEVATE YOUR SPACE</p>
          <h2 class="feature__title">BESPOKE RESIN ART</h2>
          <p class="feature__body">
            High Maintenance Resin Art specializes in statement pieces: geode-inspired trays, wall panels,
            coasters, and functional art objects — including “artified” items like cobalt toolboxes.
            Every build is layered, detailed, and finished to a premium standard.
          </p>
          <ul class="feature__list">
            <li>Crystal edges, iridescents, shimmer & depth</li>
            <li>Gold-leaf detailing (optional)</li>
            <li>Wall-mount, tabletop risers, or black iron stand options</li>
          </ul>
          <a class="btn btn--primary" href="#contact">Start a Custom</a>
        </div>

        <div class="feature__media">
          <img src="https://via.placeholder.com/900x720" alt="Placeholder image: close-up resin geode texture" />
        </div>
      </div>
    </section>

    <section class="section section--cream">
      <div class="container feature feature--reverse">
        <div class="feature__text">
          <p class="eyebrow">FUNCTIONAL MEETS LUXURY</p>
          <h2 class="feature__title">ARTIFIED OBJECTS</h2>
          <p class="feature__body">
            Sometimes art shouldn’t just hang — it should work. We take real-world items (like cobalt toolboxes)
            and transform them into conversation pieces with resin, crystal accents, and high-gloss finishes.
          </p>
          <div class="feature__note">
            <strong>Heads up:</strong> Display props, stands, and frames are not included unless explicitly listed.
          </div>
          <a class="textlink" href="#shop">Browse Shop →</a>
        </div>

        <div class="feature__media">
          <img src="https://via.placeholder.com/900x720" alt="Placeholder image: artified toolbox concept" />
        </div>
      </div>
    </section>

    <!-- Quote band -->
    <section class="quote-band">
      <div class="container quote-band__inner">
        <h2 class="quote-band__title">EVERY POUR TELLS A STORY.</h2>
        <p class="quote-band__subtitle">Every piece is unique. That’s the beauty of resin art.</p>
      </div>
    </section>

    <!-- Testimonials -->
    <section class="section section--blush" id="testimonials">
      <div class="container">
        <div class="section__heading">
          <h2 class="section__title section__title--center">TESTIMONIALS</h2>
        </div>

        <div class="testimonials">
          <article class="tcard">
            <div class="tcard__stars" aria-label="5 stars">★★★★★</div>
            <p class="tcard__text">
              “The depth and sparkle is unreal — looks like a real geode. Packaging was perfect and it arrived flawless.”
            </p>
            <p class="tcard__meta">— Verified Buyer</p>
          </article>

          <article class="tcard tcard--lift">
            <div class="tcard__stars" aria-label="5 stars">★★★★★</div>
            <p class="tcard__text">
              “Custom order came out better than my reference photos. The crystal edge work is next level.”
            </p>
            <p class="tcard__meta">— Custom Client</p>
          </article>

          <article class="tcard">
            <div class="tcard__stars" aria-label="5 stars">★★★★★</div>
            <p class="tcard__text">
              “Functional art that actually feels premium. The finish is glassy and the details catch light from every angle.”
            </p>
            <p class="tcard__meta">— Repeat Customer</p>
          </article>
        </div>
      </div>
    </section>

    <!-- About / Contact / FAQ anchors -->
    <section class="section section--cream" id="about">
      <div class="container split">
        <div class="split__media">
          <img src="https://via.placeholder.com/920x760" alt="Placeholder image: artist at work in studio" />
        </div>
        <div class="split__text">
          <p class="eyebrow">MEET THE BRAND</p>
          <h2 class="split__title">HIGH MAINTENANCE — BY DESIGN</h2>
          <p class="split__body">
            High Maintenance Resin Art is built around detail: layered pours, crystal edges, and finishes that feel
            expensive in-hand. Whether it’s a wall piece, a tray, or an artified toolbox, the goal stays the same —
            create something that can’t be duplicated.
          </p>
          <a class="btn btn--primary" href="#contact">Contact</a>
        </div>
      </div>
    </section>

    <section class="section section--cream" id="faq">
      <div class="container faq">
        <div class="faq__head">
          <h2 class="faq__title">FAQ</h2>
          <p class="faq__sub">Quick answers — keep it simple for buyers.</p>
        </div>

        <div class="faq__grid">
          <details class="faq__item">
            <summary>Do you take custom orders?</summary>
            <p>Yes. Use the contact form and include size, colors, crystals, and whether you want wall-mount or tabletop display.</p>
          </details>

          <details class="faq__item">
            <summary>Are stands/frames included?</summary>
            <p>No — unless the listing explicitly says it includes a stand/frame. We can add black iron stands or risers as an upgrade.</p>
          </details>

          <details class="faq__item">
            <summary>How long does a custom take?</summary>
            <p>Typical lead time is 2–4 weeks depending on size, curing time, and complexity.</p>
          </details>

          <details class="faq__item">
            <summary>How do I care for resin pieces?</summary>
            <p>Keep out of extreme heat, wipe with a soft cloth, and avoid harsh solvents/abrasives.</p>
          </details>
        </div>
      </div>
    </section>

    <section class="section section--cream" id="contact">
      <div class="container contact">
        <div class="contact__text">
          <p class="eyebrow">LET’S BUILD YOUR PIECE</p>
          <h2 class="contact__title">Contact</h2>
          <p class="contact__body">
            Send what you’re thinking: size, colors, crystals, and where it will live (wall/tabletop).
            If you already have inspiration photos, mention it.
          </p>
          <div class="contact__links">
            <a class="textlink" href="#">Instagram →</a>
            <a class="textlink" href="#">TikTok →</a>
            <a class="textlink" href="#">Etsy →</a>
          </div>
        </div>

        <form class="contact__form" action="#" method="post">
          <label class="field">
            <span>Name</span>
            <input type="text" name="name" autocomplete="name" placeholder="Your name" required />
          </label>

          <label class="field">
            <span>Email</span>
            <input type="email" name="email" autocomplete="email" placeholder="you@email.com" required />
          </label>

          <label class="field">
            <span>What are you looking for?</span>
            <textarea name="message" rows="5" placeholder="Size, colors, crystals, wall/tabletop, timeframe..." required></textarea>
          </label>

          <button class="btn btn--primary btn--block" type="submit">Send Request</button>
          <p class="formnote">This form is a template. Hook it to your email service or backend later.</p>
        </form>
      </div>
    </section>

  </main>

  <!-- Footer -->
  <footer class="footer">
    <div class="container footer__grid">
      <div class="footer__col">
        <h3 class="footer__head">High Maintenance Resin Art</h3>
        <p class="footer__muted">One-of-one statement pieces — resin art + artified functional objects.</p>
      </div>

      <div class="footer__col">
        <h3 class="footer__head">Quick Links</h3>
        <a class="footer__link" href="#collection">Collection</a>
        <a class="footer__link" href="#custom">Custom Orders</a>
        <a class="footer__link" href="#testimonials">Testimonials</a>
      </div>

      <div class="footer__col">
        <h3 class="footer__head">Info</h3>
        <a class="footer__link" href="#about">About</a>
        <a class="footer__link" href="#faq">FAQ</a>
        <a class="footer__link" href="#contact">Contact</a>
      </div>

      <div class="footer__col">
        <h3 class="footer__head">Newsletter</h3>
        <p class="footer__muted">Drop launches + one-off drops. No spam.</p>
        <form class="newsletter" action="#" method="post">
          <input class="newsletter__input" type="email" placeholder="Email address" aria-label="Email address" />
          <button class="btn btn--primary" type="submit">Sign Up</button>
        </form>
      </div>
    </div>

    <div class="footer__bottom">
      <div class="container footer__bottom-inner">
        <small>© <span id="year"></span> High Maintenance Resin Art. All rights reserved.</small>
        <small class="footer__muted">United States • USD</small>
      </div>
    </div>

    <script>
      document.getElementById("year").textContent = new Date().getFullYear();
    </script>
  </footer>

</body>
</html>
