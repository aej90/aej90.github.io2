<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ava Jurkiewicz — Public Health & Athletics</title>
  <link rel="stylesheet" href="styles.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet" />
</head>
<body>

  <!-- NAV -->
  <nav id="navbar">
    <div class="nav-inner">
      <a href="#hero" class="nav-logo">AJ</a>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#service">Service</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact" class="nav-cta">Contact</a></li>
      </ul>
      <button class="hamburger" id="hamburger" aria-label="Menu">
        <span></span><span></span><span></span>
      </button>
    </div>
    <div class="mobile-menu" id="mobile-menu">
      <a href="#about">About</a>
      <a href="#experience">Experience</a>
      <a href="#service">Service</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <!-- HERO -->
  <section id="hero">
    <div class="hero-content">
      <span class="hero-eyebrow">Public Health · Athletics · Leadership</span>
      <h1 class="hero-title">
        <span class="hero-name">Ava</span>
        <span class="hero-name italic">Jurkiewicz</span>
      </h1>
      <p class="hero-sub">
        Division I Student-Athlete &amp; Public Health Scholar at Rutgers University.<br>
        Committed to community, performance, and purposeful work.
      </p>
      <div class="hero-actions">
        <a href="#experience" class="btn-primary">View Experience</a>
        <a href="#contact" class="btn-ghost">Get in Touch</a>
      </div>
    </div>
    <div class="hero-visual">
      <div class="hero-blob"></div>
      <div class="hero-card">
        <div class="hc-line">
          <span class="hc-label">School</span>
          <span class="hc-value">Rutgers University</span>
        </div>
        <div class="hc-line">
          <span class="hc-label">Major</span>
          <span class="hc-value">B.S. Public Health</span>
        </div>
        <div class="hc-line">
          <span class="hc-label">GPA</span>
          <span class="hc-value">3.54</span>
        </div>
        <div class="hc-line">
          <span class="hc-label">Sport</span>
          <span class="hc-value">Swimming &amp; Diving</span>
        </div>
        <div class="hc-line">
          <span class="hc-label">Grad</span>
          <span class="hc-value">May 2027</span>
        </div>
      </div>
    </div>
    <div class="scroll-hint">
      <span>Scroll</span>
      <div class="scroll-line"></div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <div class="section-inner two-col">
      <div class="about-text reveal">
        <span class="section-label">About Me</span>
        <h2>Athlete. Scholar.<br><em>Community Builder.</em></h2>
        <p>
          I'm a Division I swimmer at Rutgers University studying Public Health with a minor in Business Administration.
          Balancing 20+ hours of weekly training and competition with rigorous academics has shaped me into someone who
          thrives under pressure and leads with intention.
        </p>
        <p>
          Beyond the pool, I'm passionate about health equity, youth development, and giving back to the communities
          that have supported me — from coaching young swimmers to volunteering with children with autism.
        </p>
      </div>
      <div class="about-stats reveal">
        <div class="stat-card">
          <div class="stat-num">20+</div>
          <div class="stat-desc">Hours/week of training &amp; competition</div>
        </div>
        <div class="stat-card">
          <div class="stat-num">3.54</div>
          <div class="stat-desc">GPA while competing Division I</div>
        </div>
        <div class="stat-card">
          <div class="stat-num">3+</div>
          <div class="stat-desc">Years of coaching &amp; instructing youth</div>
        </div>
        <div class="stat-card">
          <div class="stat-num">3K</div>
          <div class="stat-desc">Snack bags prepared for food-insecure families</div>
        </div>
      </div>
    </div>
  </section>

  <!-- EXPERIENCE -->
  <section id="experience">
    <div class="section-inner">
      <span class="section-label reveal">Work Experience</span>
      <h2 class="reveal">Where I've Made an Impact</h2>
      <div class="timeline">

        <div class="timeline-item reveal">
          <div class="timeline-dot"></div>
          <div class="timeline-content">
            <div class="ti-header">
              <div>
                <h3>Swimming Coach</h3>
                <span class="ti-org">Scarlet Aquatics · Piscataway, NJ</span>
              </div>
              <span class="ti-date">Jan 2025 – Present</span>
            </div>
            <ul>
              <li>Evaluate skills and provide tailored instruction to young swimmers ages 7–12</li>
              <li>Design ability-matched workouts that introduce new technical skills progressively</li>
            </ul>
            <div class="ti-tags">
              <span>Coaching</span><span>Youth Development</span><span>Curriculum Design</span>
            </div>
          </div>
        </div>

        <div class="timeline-item reveal">
          <div class="timeline-dot"></div>
          <div class="timeline-content">
            <div class="ti-header">
              <div>
                <h3>Lifeguard</h3>
                <span class="ti-org">Northville Swim Club · Northville, MI</span>
              </div>
              <span class="ti-date">May 2022 – Jul 2025</span>
            </div>
            <ul>
              <li>Completed 4.5–6 hour rotational shifts across pool deck, front desk, diving well, and facility</li>
              <li>Coordinated with board members and head guards; managed shift scheduling</li>
              <li>Administered first aid and CPR to patrons when necessary</li>
            </ul>
            <div class="ti-tags">
              <span>CPR / First Aid</span><span>Team Coordination</span><span>Safety</span>
            </div>
          </div>
        </div>

        <div class="timeline-item reveal">
          <div class="timeline-dot"></div>
          <div class="timeline-content">
            <div class="ti-header">
              <div>
                <h3>Private Swim Instructor</h3>
                <span class="ti-org">Independent · Northville, MI</span>
              </div>
              <span class="ti-date">May 2023 – Jul 2025</span>
            </div>
            <ul>
              <li>Instructed co-ed youth ages 6–13 and one adult client across all ability levels</li>
              <li>Maintained ongoing communication with parents on progress and recommended next steps</li>
            </ul>
            <div class="ti-tags">
              <span>1-on-1 Instruction</span><span>Communication</span><span>Client Relations</span>
            </div>
          </div>
        </div>

        <div class="timeline-item reveal">
          <div class="timeline-dot"></div>
          <div class="timeline-content">
            <div class="ti-header">
              <div>
                <h3>Division I Student-Athlete</h3>
                <span class="ti-org">Rutgers Swimming &amp; Diving · New Brunswick, NJ</span>
              </div>
              <span class="ti-date">Aug 2024 – Present</span>
            </div>
            <ul>
              <li>Commit to 20+ hours/week of practice, training, competition, and team travel</li>
              <li>Maintain a 3.54 GPA while managing a demanding athletic schedule</li>
              <li>Participate in year-round service events representing Rutgers Athletics</li>
            </ul>
            <div class="ti-tags">
              <span>Breaststroke / IM</span><span>Time Management</span><span>Leadership</span>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- SERVICE -->
  <section id="service">
    <div class="section-inner">
      <span class="section-label reveal">Service &amp; Leadership</span>
      <h2 class="reveal">Giving Back</h2>
      <div class="service-grid">

        <div class="service-card reveal">
          <div class="sc-icon">
            <svg viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
              <circle cx="20" cy="20" r="18" stroke="currentColor" stroke-width="1.5"/>
              <path d="M13 20c0-3.866 3.134-7 7-7s7 3.134 7 7-3.134 7-7 7" stroke="currentColor" stroke-width="1.5" stroke-linecap="round"/>
              <circle cx="20" cy="20" r="3" fill="currentColor"/>
            </svg>
          </div>
          <h3>Saturdays In Motion</h3>
          <span class="sc-location">Somerset, NJ · Nov 2024 – Present</span>
          <p>Guided children with autism (ages 3–17) through structured gym and pool sessions with engaging, therapeutic activities.</p>
        </div>

        <div class="service-card reveal">
          <div class="sc-icon">
            <svg viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M8 28l4-8 4 4 4-12 4 6 4-2" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
              <rect x="6" y="10" width="28" height="20" rx="3" stroke="currentColor" stroke-width="1.5"/>
            </svg>
          </div>
          <h3>Elijah's Promise</h3>
          <span class="sc-location">New Brunswick, NJ · Sept 2024 &amp; 2025</span>
          <p>Joined 700+ student-athletes to prepare 3,000 snack bags for food-insecure families across the local community.</p>
        </div>

        <div class="service-card reveal">
          <div class="sc-icon">
            <svg viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
              <circle cx="20" cy="14" r="5" stroke="currentColor" stroke-width="1.5"/>
              <path d="M10 32c0-5.523 4.477-10 10-10s10 4.477 10 10" stroke="currentColor" stroke-width="1.5" stroke-linecap="round"/>
            </svg>
          </div>
          <h3>Rutgers Athletics Service</h3>
          <span class="sc-location">New Brunswick, NJ · Aug 2024 – Present</span>
          <p>Participates in year-round community service events on behalf of Rutgers University and Rutgers Athletics.</p>
        </div>

      </div>
    </div>
  </section>

  <!-- SKILLS -->
  <section id="skills">
    <div class="section-inner">
      <span class="section-label reveal">Skills &amp; Interests</span>
      <h2 class="reveal">What I Bring</h2>
      <div class="skills-layout">
        <div class="skills-col reveal">
          <h4>Technical Skills</h4>
          <div class="skill-pills">
            <span>CPR Certified</span>
            <span>Google Workspace</span>
            <span>Microsoft Office</span>
            <span>Windows 10</span>
            <span>ChromeOS</span>
            <span>Adobe Photoshop</span>
            <span>Adobe Acrobat</span>
            <span>Canva</span>
            <span>CapCut</span>
            <span>Social Media Platforms</span>
          </div>
        </div>
        <div class="skills-col reveal">
          <h4>Core Competencies</h4>
          <div class="skill-pills accent">
            <span>Youth Coaching</span>
            <span>Team Leadership</span>
            <span>Time Management</span>
            <span>Communication</span>
            <span>Curriculum Design</span>
            <span>Client Relations</span>
            <span>Community Service</span>
            <span>Emergency Response</span>
          </div>
        </div>
        <div class="skills-col reveal">
          <h4>Interests</h4>
          <div class="skill-pills muted">
            <span>Swimming</span>
            <span>Health &amp; Fitness</span>
            <span>Professional Development</span>
            <span>Public Health</span>
            <span>Youth Athletics</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <div class="section-inner contact-inner">
      <div class="contact-text reveal">
        <span class="section-label">Contact</span>
        <h2>Let's Connect</h2>
        <p>Whether you're looking for a motivated athlete, public health advocate, or passionate coach — I'd love to hear from you.</p>
        <div class="contact-links">
          <a href="mailto:aejurkiewicz6@gmail.com" class="contact-link">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="m2 7 10 7 10-7"/></svg>
            aejurkiewicz6@gmail.com
          </a>
          <a href="tel:7343304450" class="contact-link">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07A19.5 19.5 0 0 1 4.14 13a19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 3.05 2h3a2 2 0 0 1 2 1.72c.127.96.361 1.903.7 2.81a2 2 0 0 1-.45 2.11L7.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.907.339 1.85.573 2.81.7A2 2 0 0 1 21 17z"/></svg>
            734.330.4450
          </a>
          <a href="https://linkedin.com/in/avajurkiewicz" target="_blank" class="contact-link">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"/><rect x="2" y="9" width="4" height="12"/><circle cx="4" cy="4" r="2"/></svg>
            linkedin.com/in/avajurkiewicz
          </a>
        </div>
      </div>
      <div class="contact-form reveal">
        <form id="contact-form" onsubmit="handleSubmit(event)">
          <div class="form-group">
            <label for="name">Name</label>
            <input type="text" id="name" placeholder="Your name" required />
          </div>
          <div class="form-group">
            <label for="email">Email</label>
            <input type="email" id="email" placeholder="your@email.com" required />
          </div>
          <div class="form-group">
            <label for="message">Message</label>
            <textarea id="message" rows="4" placeholder="Tell me what's on your mind…" required></textarea>
          </div>
          <button type="submit" class="btn-primary full-width" id="submit-btn">Send Message</button>
          <p class="form-success" id="form-success">Thanks! I'll be in touch soon.</p>
        </form>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <div class="footer-inner">
      <span>© 2026 Ava Jurkiewicz</span>
      <span>Rutgers University · Class of 2027</span>
    </div>
  </footer>

  <script src="main.js"></script>
</body>
</html>
