
    <style>

      .readme-page {
        --color-text: #24292f;
        --color-muted: #57606a;
        --color-border: #d0d7de;
        --color-surface: #f6f8fa;
        --color-blue: #0969da;
        --color-green: #1a7f37;
        --color-orange: #bc4c00;

        box-sizing: border-box;
        max-width: 860px;
        margin: 0 auto;
        padding: 32px 24px 48px;
        color: var(--color-text);
        font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
        font-size: 15px;
        line-height: 1.65;
      }

      .readme-page *,
      .readme-page *::before,
      .readme-page *::after {
        box-sizing: inherit;
      }

      .readme-page h1,
      .readme-page h2,
      .readme-page h3,
      .readme-page p,
      .readme-page figure {
        margin-top: 0;
      }

      .readme-page .page-header {
        margin-bottom: 28px;
        text-align: center;
      }

      .readme-page h1 {
        margin-bottom: 16px;
        font-size: 32px;
        line-height: 1.2;
      }

      .readme-page .badges {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 8px;
      }

      .readme-page .badge {
        display: inline-flex;
        overflow: hidden;
        border: 1px solid var(--color-border);
        border-radius: 4px;
        font-size: 12px;
        font-weight: 600;
        line-height: 24px;
      }

      .readme-page .badge-label,
      .readme-page .badge-value {
        padding: 0 9px;
      }

      .readme-page .badge-label {
        background: var(--color-surface);
      }

      .readme-page .badge-license {
        color: #fff;
        background: #8250df;
      }

      .readme-page .badge-responsive {
        color: #fff;
        background: var(--color-green);
      }

      .readme-page .badge-seo {
        color: #fff;
        background: var(--color-orange);
      }

      .readme-page .preview-frame {
        max-height: 520px;
        margin: 0 0 24px;
        overflow: auto;
        border: 1px solid var(--color-border);
        border-radius: 4px;
        background: var(--color-surface);
        -webkit-overflow-scrolling: touch;
      }

      .readme-page .preview-frame img {
        display: block;
        width: 100%;
        max-width: 100%;
        height: auto;
      }

      .readme-page .intro p {
        margin-bottom: 14px;
      }

      .readme-page .intro-list,
      .readme-page .feature-list {
        padding: 0;
        list-style: none;
      }

      .readme-page .intro-list {
        margin: 0 0 20px;
      }

      .readme-page .intro-list li,
      .readme-page .feature-list li {
        margin: 6px 0;
      }

      .readme-page .section-heading {
        margin: 36px 0 12px;
        padding-bottom: 8px;
        border-bottom: 1px solid var(--color-border);
        font-size: 22px;
      }

      .readme-page .section-lead {
        margin-bottom: 16px;
        color: var(--color-muted);
      }

      .readme-page .feature-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(min(100%, 260px), 1fr));
        gap: 12px;
      }

      .readme-page .feature-card {
        padding: 16px;
        border: 1px solid var(--color-border);
        border-radius: 4px;
      }

      .readme-page .feature-card h3 {
        margin-bottom: 8px;
        font-size: 16px;
      }

      .readme-page .feature-card p {
        margin-bottom: 8px;
        color: var(--color-muted);
        font-size: 14px;
      }

      .readme-page .feature-list {
        margin: 0;
        font-size: 14px;
      }

      .readme-page .support-section {
        margin-top: 36px;
        padding: 24px;
        border: 1px solid var(--color-border);
        border-radius: 4px;
        text-align: center;
      }

      .readme-page .support-section h2 {
        margin-bottom: 12px;
        font-size: 20px;
      }

      .readme-page .support-links {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 10px;
        margin: 20px 0;
      }

      .readme-page .support-link {
        display: inline-block;
        padding: 8px 12px;
        border: 1px solid var(--color-border);
        border-radius: 4px;
        color: var(--color-text);
        font-size: 14px;
        font-weight: 600;
        text-decoration: none;
      }

      .readme-page .support-link:hover,
      .readme-page .support-link:focus-visible {
        border-color: var(--color-blue);
        color: var(--color-blue);
      }

      .readme-page .support-note {
        margin-bottom: 0;
        color: var(--color-muted);
        font-style: italic;
      }

      @media (max-width: 480px) {
        .readme-page {
          padding: 24px 16px 36px;
        }

        .readme-page h1 {
          font-size: 28px;
        }

        .readme-page .support-section {
          padding: 20px 16px;
        }
      }
    </style>
  </head>
  <body>
    <main class="readme-page">
      <header class="page-header">
        <h1>Blogger Template</h1>
        <div class="badges" aria-label="Template details">
          <span class="badge">
            <span class="badge-label">License</span>
            <span class="badge-value badge-license">MIT</span>
          </span>
          <span class="badge">
            <span class="badge-label">Responsive</span>
            <span class="badge-value badge-responsive">100%</span>
          </span>
          <span class="badge">
            <span class="badge-label">SEO</span>
            <span class="badge-value badge-seo">Optimized</span>
          </span>
        </div>
      </header>

      <figure class="preview-frame">
        <img
          src="tedmxz.blogspot.com_.png"
          alt="Full-page preview of the Blogger template"
        />
      </figure>

      <section class="intro" aria-label="About this template">
        <p>
          Your blog design is the first thing visitors notice when they open
          your website. This <strong>Blogger Template</strong> offers a clean
          and simple design that is easy to customize.
        </p>
        <p>
          Whether you are a blogger, developer, student, or content creator,
          this template helps you build a professional-looking blog that suits
          your needs.
        </p>
        <ul class="intro-list">
          <li>
            ➜ A clean, professional look that keeps your content front and
            center
          </li>
          <li>
            ➜ A layout that adapts nicely to phones, tablets, and desktops
          </li>
          <li>➜ SEO-friendly markup, so search engines can find your posts</li>
          <li>➜ Easy customization, with no coding headaches</li>
        </ul>
        <p>
          Welcome to tedMXZ, your place for coding projects, free source code,
          and hands-on programming tutorials.
        </p>
      </section>

      <section aria-labelledby="features-heading">
        <h2 class="section-heading" id="features-heading">Features</h2>
        <p class="section-lead">
          Everything you need to run a modern, fast, and good-looking blog.
        </p>

        <div class="feature-grid">
          <article class="feature-card">
            <h3>Clean Layout</h3>
            <p>Organized, professional layout built around your content.</p>
            <ul class="feature-list">
              <li>✓ Clear content hierarchy</li>
              <li>✓ Readable typography</li>
              <li>✓ Minimal, distraction-free design</li>
            </ul>
          </article>

          <article class="feature-card">
            <h3>Responsive Design</h3>
            <p>Looks right on every screen, ultra-wide to foldable.</p>
            <ul class="feature-list">
              <li>✓ Mobile, tablet, and desktop ready</li>
              <li>✓ Flexible grid and images</li>
              <li>✓ Tested on modern browsers</li>
            </ul>
          </article>

          <article class="feature-card">
            <h3>SEO-Friendly</h3>
            <p>
              Semantic HTML that helps search engines understand your posts.
            </p>
            <ul class="feature-list">
              <li>✓ Proper heading structure</li>
              <li>✓ Clean, crawlable markup</li>
              <li>✓ Fast-loading, lightweight code</li>
            </ul>
          </article>

          <article class="feature-card">
            <h3>Easy Customization</h3>
            <p>Make the design yours without touching the core.</p>
            <ul class="feature-list">
              <li>✓ Colors and fonts</li>
              <li>✓ Spacing and layout elements</li>
              <li>✓ Blogger theme designer support</li>
            </ul>
          </article>

          <article class="feature-card">
            <h3>Widget Zones</h3>
            <p>Ready-made spots for what matters to your audience.</p>
            <ul class="feature-list">
              <li>✓ Ads and sponsored blocks</li>
              <li>✓ Newsletter signup</li>
              <li>✓ Calls to action</li>
            </ul>
          </article>

          <article class="feature-card">
            <h3>Dark Mode</h3>
            <p>Comfortable reading at any time of day.</p>
            <ul class="feature-list">
              <li>✓ Dark mode fallback in base styles</li>
              <li>✓ Readable contrast</li>
              <li>✓ Respects visitor preference</li>
            </ul>
          </article>

          <article class="feature-card">
            <h3>Accessibility</h3>
            <p>Built with every reader in mind.</p>
            <ul class="feature-list">
              <li>✓ WCAG 2.1 AA focused</li>
              <li>✓ Semantic structure</li>
              <li>✓ Keyboard-friendly navigation</li>
            </ul>
          </article>

          <article class="feature-card">
            <h3>Organized Code</h3>
            <p>Easy to maintain and improve later.</p>
            <ul class="feature-list">
              <li>✓ Atomic CSS approach</li>
              <li>✓ Multi-language ready structure</li>
              <li>✓ Commented, tidy source</li>
            </ul>
          </article>
        </div>
      </section>

      <section class="support-section" aria-labelledby="support-heading">
        <h2 id="support-heading">Support the Project</h2>
        <p>If you like this project, follow me and star this repository.</p>
        <div class="support-links">
          <a
            class="support-link"
            href="YOUR_GITHUB_PROFILE_LINK"
            target="_blank"
            rel="noopener noreferrer"
          >
            Follow on GitHub
          </a>
          <a
            class="support-link"
            href="YOUR_GITHUB_REPO_LINK"
            target="_blank"
            rel="noopener noreferrer"
          >
            Star this repository
          </a>
        </div>
        <p class="support-note">
          Your support keeps this project growing. Thank you!
        </p>
      </section>
    </main>
