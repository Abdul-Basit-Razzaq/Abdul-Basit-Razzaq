
<style>
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: var(--font-sans); color: var(--color-text-primary); }
.root { padding: 2rem 1rem; max-width: 860px; margin: 0 auto; }
.hero { text-align: center; margin-bottom: 2.5rem; }
.avatar { width: 88px; height: 88px; border-radius: 50%; background: #1e1e2e; border: 3px solid var(--color-border-secondary); display: flex; align-items: center; justify-content: center; font-size: 32px; font-weight: 500; color: #A78BFA; margin: 0 auto 1rem; letter-spacing: -1px; }
.name { font-size: 26px; font-weight: 500; margin-bottom: 4px; }
.role { font-size: 14px; color: var(--color-text-secondary); margin-bottom: 12px; }
.tagline { font-size: 14px; color: var(--color-text-secondary); max-width: 480px; margin: 0 auto 1.25rem; line-height: 1.6; }
.badges { display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; margin-bottom: 1.5rem; }
.badge { font-size: 12px; padding: 4px 12px; border-radius: 20px; border: 0.5px solid; font-weight: 500; }
.badge-purple { background: #EEEDFE; color: #3C3489; border-color: #AFA9EC; }
.badge-teal { background: #E1F5EE; color: #085041; border-color: #5DCAA5; }
.badge-blue { background: #E6F1FB; color: #0C447C; border-color: #85B7EB; }
.links { display: flex; gap: 10px; justify-content: center; }
.link-btn { display: flex; align-items: center; gap: 6px; font-size: 13px; padding: 7px 16px; border-radius: var(--border-radius-md); border: 0.5px solid var(--color-border-secondary); color: var(--color-text-primary); text-decoration: none; cursor: pointer; background: var(--color-background-primary); }
.link-btn:hover { background: var(--color-background-secondary); }
.section-title { font-size: 13px; font-weight: 500; color: var(--color-text-secondary); text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 12px; }
.grid-2 { display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 10px; margin-bottom: 2rem; }
.grid-3 { display: grid; grid-template-columns: repeat(auto-fit, minmax(140px, 1fr)); gap: 10px; margin-bottom: 2rem; }
.card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 1rem 1.25rem; }
.card:hover { border-color: var(--color-border-secondary); }
.proj-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 1.1rem 1.25rem; }
.proj-card:hover { border-color: var(--color-border-secondary); }
.proj-title { font-size: 15px; font-weight: 500; display: flex; align-items: center; gap: 8px; margin-bottom: 6px; }
.proj-desc { font-size: 13px; color: var(--color-text-secondary); line-height: 1.6; margin-bottom: 10px; }
.tag-row { display: flex; flex-wrap: wrap; gap: 6px; }
.tag { font-size: 11px; padding: 3px 9px; border-radius: 12px; border: 0.5px solid var(--color-border-tertiary); color: var(--color-text-secondary); }
.skill-group { margin-bottom: 1.75rem; }
.skill-row { display: flex; flex-wrap: wrap; gap: 8px; }
.skill-chip { font-size: 13px; padding: 5px 12px; border-radius: var(--border-radius-md); border: 0.5px solid var(--color-border-tertiary); color: var(--color-text-primary); background: var(--color-background-secondary); display: flex; align-items: center; gap: 6px; }
.dot { width: 7px; height: 7px; border-radius: 50%; flex-shrink: 0; }
.dot-py { background: #3572A5; }
.dot-js { background: #F7DF1E; }
.dot-java { background: #B07219; }
.dot-cpp { background: #555599; }
.stat-card { background: var(--color-background-secondary); border-radius: var(--border-radius-md); padding: 1rem; text-align: center; }
.stat-num { font-size: 24px; font-weight: 500; margin-bottom: 2px; }
.stat-label { font-size: 12px; color: var(--color-text-secondary); }
.focus-row { display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 10px; margin-bottom: 2rem; }
.focus-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 1rem 1.25rem; }
.focus-icon { font-size: 22px; margin-bottom: 8px; color: #7C3AED; }
.focus-title { font-size: 14px; font-weight: 500; margin-bottom: 4px; }
.focus-desc { font-size: 12px; color: var(--color-text-secondary); line-height: 1.5; }
.divider { border: none; border-top: 0.5px solid var(--color-border-tertiary); margin: 2rem 0; }
.wip-dot { width: 8px; height: 8px; border-radius: 50%; background: #F59E0B; display: inline-block; }
.live-dot { width: 8px; height: 8px; border-radius: 50%; background: #10B981; display: inline-block; }
</style>

<div class="root">
  <h2 class="sr-only" style="position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0,0,0,0)">Abdul Basit — Jr. Software Engineer portfolio</h2>

  <div class="hero">
    <div class="avatar">AB</div>
    <div class="name">Abdul Basit</div>
    <div class="role">Jr. Software Engineer · Lahore, PK</div>
    <div class="tagline">Building scalable backend systems and data-driven platforms with clean architecture and real-world impact.</div>
    <div class="badges">
      <span class="badge badge-purple">Backend Systems</span>
      <span class="badge badge-teal">API Engineering</span>
      <span class="badge badge-blue">Data Platforms</span>
    </div>
    <div class="links">
      <a class="link-btn" href="https://www.linkedin.com/in/abdul-basit-ibn-razzaq"><i class="ti ti-brand-linkedin" aria-hidden="true"></i> LinkedIn</a>
      <a class="link-btn" href="https://github.com/Abdul-Basit-Razzaq"><i class="ti ti-brand-github" aria-hidden="true"></i> GitHub</a>
      <a class="link-btn" href="mailto:ab4382906@gmail.com"><i class="ti ti-mail" aria-hidden="true"></i> Email</a>
    </div>
  </div>

  <hr class="divider">

  <div class="section-title">Featured projects</div>
  <div class="grid-2" style="margin-bottom: 2rem;">
    <div class="proj-card">
      <div class="proj-title">
        <i class="ti ti-building-community" style="font-size:18px; color:#7C3AED;" aria-hidden="true"></i>
        CommunityFixes
        <span class="live-dot" title="completed"></span>
      </div>
      <div class="proj-desc">Final year project — multi-role civic issue reporting system with real-time workflows, admin restrictions, and priority-based routing.</div>
      <div class="tag-row">
        <span class="tag">MongoDB</span>
        <span class="tag">Express</span>
        <span class="tag">React</span>
        <span class="tag">Node.js</span>
        <span class="tag">RBAC</span>
      </div>
    </div>
    <div class="proj-card">
      <div class="proj-title">
        <i class="ti ti-chart-histogram" style="font-size:18px; color:#0D9488;" aria-hidden="true"></i>
        Watchlytics
        <span class="wip-dot" title="in progress"></span>
      </div>
      <div class="proj-desc">Marketplace analytics platform for demand signal detection and product intelligence dashboards. Currently in active development.</div>
      <div class="tag-row">
        <span class="tag">Python</span>
        <span class="tag">FastAPI</span>
        <span class="tag">Data pipelines</span>
        <span class="tag">Dashboards</span>
      </div>
    </div>
  </div>

  <hr class="divider">

  <div class="section-title">Technical skills</div>

  <div class="skill-group">
    <div style="font-size:13px; color: var(--color-text-secondary); margin-bottom: 8px;">Languages</div>
    <div class="skill-row">
      <div class="skill-chip"><span class="dot dot-py"></span>Python</div>
      <div class="skill-chip"><span class="dot dot-java"></span>Java</div>
      <div class="skill-chip"><span class="dot dot-js"></span>JavaScript</div>
      <div class="skill-chip"><span class="dot dot-cpp"></span>C / C++</div>
    </div>
  </div>

  <div class="skill-group">
    <div style="font-size:13px; color: var(--color-text-secondary); margin-bottom: 8px;">Backend</div>
    <div class="skill-row">
      <div class="skill-chip"><i class="ti ti-brand-nodejs" aria-hidden="true"></i>Node.js</div>
      <div class="skill-chip"><i class="ti ti-brand-django" aria-hidden="true"></i>Django</div>
      <div class="skill-chip"><i class="ti ti-bolt" aria-hidden="true"></i>FastAPI</div>
      <div class="skill-chip"><i class="ti ti-api" aria-hidden="true"></i>REST APIs</div>
      <div class="skill-chip"><i class="ti ti-shield-lock" aria-hidden="true"></i>Auth & RBAC</div>
    </div>
  </div>

  <div class="skill-group">
    <div style="font-size:13px; color: var(--color-text-secondary); margin-bottom: 8px;">Databases</div>
    <div class="skill-row">
      <div class="skill-chip">PostgreSQL</div>
      <div class="skill-chip">MySQL</div>
      <div class="skill-chip">SQLite</div>
      <div class="skill-chip">Firebase</div>
    </div>
  </div>

  <div class="skill-group">
    <div style="font-size:13px; color: var(--color-text-secondary); margin-bottom: 8px;">Frontend & tools</div>
    <div class="skill-row">
      <div class="skill-chip"><i class="ti ti-brand-react" aria-hidden="true"></i>React</div>
      <div class="skill-chip"><i class="ti ti-brand-html5" aria-hidden="true"></i>HTML/CSS</div>
      <div class="skill-chip"><i class="ti ti-brand-git" aria-hidden="true"></i>Git</div>
      <div class="skill-chip"><i class="ti ti-terminal" aria-hidden="true"></i>Linux</div>
      <div class="skill-chip">Postman</div>
      <div class="skill-chip">Android</div>
    </div>
  </div>

  <hr class="divider">

  <div class="section-title">Focus areas</div>
  <div class="focus-row">
    <div class="focus-card">
      <div class="focus-icon"><i class="ti ti-server" aria-hidden="true"></i></div>
      <div class="focus-title">Backend systems</div>
      <div class="focus-desc">Robust, scalable server-side architectures with clean separation of concerns.</div>
    </div>
    <div class="focus-card">
      <div class="focus-icon"><i class="ti ti-api" aria-hidden="true"></i></div>
      <div class="focus-title">API engineering</div>
      <div class="focus-desc">RESTful APIs with clean contracts, proper auth layers, and consistent error handling.</div>
    </div>
    <div class="focus-card">
      <div class="focus-icon"><i class="ti ti-chart-bar" aria-hidden="true"></i></div>
      <div class="focus-title">Data platforms</div>
      <div class="focus-desc">Pipelines and dashboards that turn raw data into actionable insights.</div>
    </div>
    <div class="focus-card">
      <div class="focus-icon"><i class="ti ti-code" aria-hidden="true"></i></div>
      <div class="focus-title">Clean code</div>
      <div class="focus-desc">Maintainable, tested, production-grade solutions that scale with the team.</div>
    </div>
  </div>

</div>
