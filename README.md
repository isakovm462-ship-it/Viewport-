# Viewport-
My first HTML/CSS project created to learn Git and GitHub.
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta
      name="description"
      content="Portfolio website for a creative developer and designer."
    />
    <title>Your Name | Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="page-shell">
      <header class="site-header">
        <div class="container nav-wrapper">
          <a href="#home" class="brand" aria-label="Go to homepage">
            <span class="brand-mark">Y</span>
            <span>Your Name</span>
          </a>

          <nav class="main-nav" aria-label="Main navigation">
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact</a>
          </nav>

          <a href="#contact" class="button button-primary">Hire Me</a>
        </div>
      </header>

      <main id="home">
        <section class="hero section">
          <div class="container hero-grid">
            <div class="hero-copy">
              <p class="eyebrow">Front-end developer • UI designer</p>
              <h1>
                I build clean,
                <span class="highlight">modern digital experiences</span>
                that people remember.
              </h1>
              <p class="lead">
                I’m a creative developer focused on turning thoughtful ideas into
                polished interfaces, engaging products, and seamless user
                experiences.
              </p>

              <div class="cta-row">
                <a href="#projects" class="button button-primary">View Projects</a>
                <a href="#contact" class="button button-secondary">Let’s Talk</a>
              </div>

              <ul class="mini-stats" aria-label="Key achievements">
                <li><strong>5+</strong><span>Years experience</span></li>
                <li><strong>25</strong><span>Projects shipped</span></li>
                <li><strong>9</strong><span>Clients served</span></li>
              </ul>
            </div>

            <div class="hero-visual" aria-label="Profile illustration">
              <div class="profile-card">
                <div class="profile-glow"></div>
                <div class="profile-image-wrap">
                  <div class="profile-image">
                    <span>YN</span>
                  </div>
                </div>
                <div class="profile-badge badge-top">Available for work</div>
                <div class="profile-badge badge-bottom">Based in London</div>
              </div>
            </div>
          </div>
        </section>

        <section id="about" class="section section-muted">
          <div class="container two-column">
            <div>
              <p class="section-kicker">About me</p>
              <h2>Designing products that feel effortless to use.</h2>
            </div>
            <div>
              <p>
                I specialize in creating accessible, high-converting digital
                experiences for startups, creative teams, and small businesses.
                My process blends visual thinking, technical implementation, and
                product strategy to deliver work that is both beautiful and
                practical.
              </p>
              <p>
                From concept to launch, I enjoy building interfaces that are fast,
                intuitive, and memorable — whether it’s a portfolio, landing
                page, SaaS app, or brand experience.
              </p>
            </div>
          </div>
        </section>

        <section id="projects" class="section">
          <div class="container">
            <div class="section-heading">
              <p class="section-kicker">Selected work</p>
              <h2>Recent projects</h2>
            </div>

            <div class="project-grid">
              <article class="project-card">
                <div class="project-thumb thumb-one" aria-hidden="true"></div>
                <div class="project-body">
                  <span class="project-tag">Branding</span>
                  <h3>Nova Studio</h3>
                  <p>
                    A premium creative studio website focused on positioning,
                    storytelling, and conversion-ready design.
                  </p>
                  <a href="#contact">Case study</a>
                </div>
              </article>

              <article class="project-card">
                <div class="project-thumb thumb-two" aria-hidden="true"></div>
                <div class="project-body">
                  <span class="project-tag">SaaS</span>
                  <h3>FlowPilot</h3>
                  <p>
                    A dashboard concept designed to simplify team operations,
                    reporting, and task visibility.
                  </p>
                  <a href="#contact">Case study</a>
                </div>
              </article>

              <article class="project-card">
                <div class="project-thumb thumb-three" aria-hidden="true"></div>
                <div class="project-body">
                  <span class="project-tag">E-commerce</span>
                  <h3>Northlane</h3>
                  <p>
                    A modern storefront experience tailored for a lifestyle brand
                    with a strong visual identity.
                  </p>
                  <a href="#contact">Case study</a>
                </div>
              </article>
            </div>
          </div>
        </section>

        <section id="skills" class="section section-muted">
          <div class="container">
            <div class="section-heading">
              <p class="section-kicker">Capabilities</p>
              <h2>Tools and expertise</h2>
            </div>

            <div class="skills-grid">
              <div class="skill-card">
                <h3>Design</h3>
                <ul>
                  <li>UI / UX Design</li>
                  <li>Wireframing</li>
                  <li>Brand Systems</li>
                </ul>
              </div>

              <div class="skill-card">
                <h3>Development</h3>
                <ul>
                  <li>HTML / CSS</li>
                  <li>JavaScript</li>
                  <li>Responsive Layouts</li>
                </ul>
              </div>

              <div class="skill-card">
                <h3>Workflow</h3>
                <ul>
                  <li>Figma</li>
                  <li>Git & GitHub</li>
                  <li>Performance Optimization</li>
                </ul>
              </div>
            </div>
          </div>
        </section>

        <section class="section testimonial-wrap">
          <div class="container quote-box">
            <p>
              “Your Name helped us turn a rough concept into a polished digital
              experience that immediately felt premium and professional.”
            </p>
            <span>— Client testimonial</span>
          </div>
        </section>
      </main>

      <footer id="contact" class="site-footer">
        <div class="container footer-grid">
          <div>
            <p class="section-kicker">Let’s build something great</p>
            <h2>Ready to bring your next idea to life?</h2>
          </div>

          <div class="contact-box">
            <a href="mailto:hello@yourname.dev">hello@yourname.dev</a>
            <a href="https://www.linkedin.com" target="_blank" rel="noreferrer">
              LinkedIn
            </a>
            <a href="https://github.com" target="_blank" rel="noreferrer">
              GitHub
            </a>
          </div>
        </div>

        <div class="footer-bottom">
          <div class="container">
            <p>© <span id="year"></span> Your Name. All rights reserved.</p>
          </div>
        </div>
      </footer>
    </div>

    <script src="script.js"></script>
  </body>
</html>

















































































							
								
									
																
																																																																																																																																																																																																																																																																																										----------------------------------------------------------------------------
a
																																																																																																																																												te
																																																																																																																									/: 
																																																																																																																																																																																																																							test																																																																																																																																																																																																																																																	test
																																																																																																																																																																																																																																												test
																																																																																																																																																																																																																																																																																																" 
  },{
