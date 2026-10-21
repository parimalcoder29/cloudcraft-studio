# CloudCraft Studio

## Project Overview
CloudCraft Studio is a simple landing page for a fictional cloud hosting business. The project is designed to showcase a modern, professional website that can be deployed quickly using a static hosting platform.

## Technologies Used
- HTML5
- CSS3
- GitHub Pages

## Selected Hosting Platform
GitHub Pages was selected because it is a simple and free option for hosting static websites directly from a GitHub repository. It is ideal for small projects like this landing page.

## Setup and Configuration Requirements
Before deploying the project, make sure you have:
- A GitHub account
- A public GitHub repository
- Internet access to access the GitHub Pages settings
- A browser to view the deployed website

## Deployment Instructions
1. Create a GitHub repository.
2. Upload the project files (`index.html` and `styles.css`) to the repository.
3. Open the repository in GitHub.
4. Go to Settings.
5. Open the Pages section.
6. Under "Build and deployment", choose "Deploy from a branch".
7. Select the branch (for example, `main`).
8. Set the folder to `/root`.
9. Click Save.
10. Wait a few minutes for GitHub to publish the site.
11. Open the generated URL to view the website.

## Live Website URL
https://parimalcoder29.github.io/cloudcraft-studio/

## Repository
https://github.com/parimalcoder29/cloudcraft-studio

## Notes
This project is intentionally lightweight and easy to deploy. It demonstrates how a simple static website can be published quickly using cloud hosting services.
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta
      name="description"
      content="CloudCraft Studio helps businesses launch faster with modern cloud hosting and digital experiences."
    />
    <title>CloudCraft Studio | Cloud Hosting</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <header class="topbar">
      <div class="container nav">
        <div class="brand">
          <span class="brand-mark">C</span>
          <span>CloudCraft Studio</span>
        </div>
        <nav class="nav-links" aria-label="Main navigation">
          <a href="#features">Features</a>
          <a href="#services">Services</a>
          <a href="#about">About</a>
          <a href="#contact">Contact</a>
        </nav>
        <a class="btn btn-primary" href="#contact">Book a Demo</a>
      </div>
    </header>

    <main>
      <section class="hero">
        <div class="container hero-grid">
          <div class="hero-copy">
            <p class="eyebrow">Cloud hosting for modern teams</p>
            <h1>Launch faster. Scale smarter.</h1>
            <p class="subheading">
              We help startups, founders, and growing businesses build reliable
              digital experiences with secure, scalable cloud hosting.
            </p>
            <div class="hero-actions">
              <a class="btn btn-primary" href="#contact">Get Started</a>
              <a class="btn btn-secondary" href="#features">View Solutions</a>
            </div>
            <ul class="trust-list" aria-label="Highlights">
              <li>99.9% uptime mindset</li>
              <li>Fast setup</li>
              <li>Built for growth</li>
            </ul>
          </div>

          <div class="hero-panel">
            <div class="panel-card large">
              <div class="mini-header">
                <span class="dot green"></span>
                <span class="dot yellow"></span>
                <span class="dot red"></span>
              </div>
              <div class="stats-box">
                <div>
                  <span class="label">Deployments</span>
                  <strong>240+</strong>
                </div>
                <div>
                  <span class="label">Response</span>
                  <strong>24/7</strong>
                </div>
              </div>
              <div class="bars" aria-hidden="true">
                <span style="height: 36%"></span>
                <span style="height: 52%"></span>
                <span style="height: 68%"></span>
                <span style="height: 84%"></span>
                <span style="height: 100%"></span>
              </div>
            </div>

            <div class="mini-row">
              <div class="panel-card small">
                <p>Live traffic</p>
                <strong>4.8k</strong>
                <span>this month</span>
              </div>
              <div class="panel-card small alt">
                <p>Security</p>
                <strong>ISO</strong>
                <span>ready</span>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="features" class="features">
        <div class="container">
          <div class="section-heading">
            <p class="eyebrow">Why teams choose us</p>
            <h2>Everything you need to move faster.</h2>
          </div>

          <div class="card-grid">
            <article class="feature-card">
              <div class="icon">⚡</div>
              <h3>Rapid Deployment</h3>
              <p>
                Get websites and apps live quickly with streamlined deployment
                workflows and minimal setup friction.
              </p>
            </article>
            <article class="feature-card">
              <div class="icon">🔒</div>
              <h3>Secure Infrastructure</h3>
              <p>
                Protect your workloads with trusted access controls, monitoring,
                and best-practice cloud configuration.
              </p>
            </article>
            <article class="feature-card">
              <div class="icon">📈</div>
              <h3>Scalable Growth</h3>
              <p>
                Grow with infrastructure that keeps pace as your traffic,
                traffic needs, and product scope expand.
              </p>
            </article>
          </div>
        </div>
      </section>

      <section id="services" class="services">
        <div class="container service-layout">
          <div>
            <p class="eyebrow">What we deliver</p>
            <h2>Digital infrastructure built for ambitious ideas.</h2>
          </div>

          <div class="service-list">
            <div class="service-item">
              <span>01</span>
              <div>
                <h3>Website Hosting</h3>
                <p>Modern hosting for business sites, portfolios, and product launches.</p>
              </div>
            </div>
            <div class="service-item">
              <span>02</span>
              <div>
                <h3>Cloud Setup</h3>
                <p>Reliable environments for apps, landing pages, and digital tools.</p>
              </div>
            </div>
            <div class="service-item">
              <span>03</span>
              <div>
                <h3>Monitoring & Support</h3>
                <p>Ongoing health checks and support to keep systems stable and efficient.</p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="about" class="about">
        <div class="container about-box">
          <div>
            <p class="eyebrow">Built for real teams</p>
            <h2>Design, deploy, and grow with clarity.</h2>
          </div>
          <p>
            CloudCraft Studio helps founders, creators, and small businesses turn
            ideas into dependable digital experiences with practical cloud hosting
            and simple, scalable architecture.
          </p>
        </div>
      </section>
    </main>

    <footer id="contact" class="footer">
      <div class="container footer-row">
        <div>
          <div class="brand footer-brand">
            <span class="brand-mark">C</span>
            <span>CloudCraft Studio</span>
          </div>
          <p>Cloud infrastructure and digital launch support.</p>
        </div>
        <a class="btn btn-primary" href="mailto:hello@cloudcraftstudio.example">hello@cloudcraftstudio.example</a>
      </div>
    </footer>
  </body>
</html>
