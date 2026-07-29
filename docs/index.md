---
layout: splash
title: " "
header:
  overlay_image: /assets/images/cover.jpg
  overlay_filter: 0.1 # Adds 50% black opacity
custom_head: head/custom.html
---

Welcome to the Community Data Workshop's resource site. This site provides all the information you need for upcoming workshops, including **data downloads, software installation instructions, prerequisites, agendas, and additional resources**.  

Use the buttons in the top right or the links below to navigate directly to a workshop.

---
## Upcoming Workshops

<style>
.ticket-grid{list-style:none;margin:0 0 20px;padding:0;display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:22px;}
.ticket-card{display:flex;border:1px solid #d8dcd6;border-radius:12px 12px 0 0;background:#fff;overflow:hidden;box-shadow:0 1px 2px rgba(20,36,48,.06);}
.ticket-stamp{flex:0 0 46px;background:#142430;color:#fff;display:flex;align-items:center;justify-content:center;padding:14px 0;}
.ticket-stamp span{writing-mode:vertical-rl;transform:rotate(180deg);font-family:'IBM Plex Mono',monospace;font-weight:600;letter-spacing:.12em;font-size:.85rem;white-space:nowrap;}
.ticket-body{flex:1;padding:20px 20px 4px;min-width:0;}
.chip{display:inline-block;font-family:'IBM Plex Mono',monospace;font-size:.72rem;font-weight:600;letter-spacing:.06em;text-transform:uppercase;padding:3px 9px;border-radius:999px;margin-bottom:10px;}
.chip--r{background:#dcead9;color:#1f4d2c;}
.chip--qgis{background:#e4ecf5;color:#1d3f66;}
.chip--tableau{background:#f3e3d8;color:#7a3b12;}
.ticket-icon{width:34px;height:34px;margin-bottom:10px;display:block;}
.ticket-title{font-family:'Oswald',sans-serif;font-weight:600;font-size:1.15rem;line-height:1.25;margin:0 0 8px;color:#142430;}
.ticket-meta{font-family:'IBM Plex Mono',monospace;font-size:.85rem;color:#3c4e5c;margin:0 0 4px;}
.ticket-instructor{font-size:.92rem;color:#3c4e5c;margin:0 0 14px;}
.ticket-footer{border:1px solid #d8dcd6;border-top:none;border-radius:0 0 12px 12px;margin-top:-1px;}
.ticket-perf{border-top:2px dashed #d8dcd6;margin:0 20px;}
.ticket-actions{display:flex;flex-direction:column;gap:8px;padding:14px 20px 20px;}
.ticket-btn{display:flex;align-items:center;gap:8px;justify-content:center;font-weight:600;font-size:.92rem;text-decoration:none;border-radius:8px;padding:9px 12px;min-height:40px;border:1.5px solid #142430;}
.ticket-btn svg{width:16px;height:16px;flex:0 0 auto;}
.ticket-btn--primary{background:#142430;color:#fff;}
.ticket-btn--primary:hover{background:#0b1a24;}
.ticket-btn--outline{background:#fff;color:#142430;}
.ticket-btn--outline:hover{background:#f1f4f2;}
.ticket-btn--text{border-color:transparent;color:#3c4e5c;text-decoration:underline;justify-content:flex-start;padding-left:2px;}
.ticket-btn--text:hover{color:#142430;}
.ticket-btn:focus-visible{outline:3px solid #0f6fb3;outline-offset:2px;}
.bundle-note{margin-top:6px;font-size:.92rem;color:#3c4e5c;border-left:3px solid #142430;padding:8px 14px;background:#fbf9f5;}
@media (max-width:520px){
  .ticket-card{flex-direction:column;}
  .ticket-stamp{flex-direction:row;width:100%;padding:8px 0;justify-content:flex-start;padding-left:20px;}
  .ticket-stamp span{writing-mode:horizontal-tb;transform:none;}
  .ticket-perf{margin:0 20px;}
}
</style>

<ul class="ticket-grid">

  <li>
    <article class="ticket-card">
      <div class="ticket-stamp"><span>SEP&nbsp;22</span></div>
      <div class="ticket-body">
        <span class="chip chip--r">R</span>
        <svg class="ticket-icon" viewBox="0 0 40 40" fill="none" aria-hidden="true">
          <circle cx="20" cy="20" r="18" stroke="#1f4d2c" stroke-width="1.5"/>
          <circle cx="13" cy="26" r="2" fill="#1f4d2c"/>
          <circle cx="18" cy="17" r="2" fill="#1f4d2c"/>
          <circle cx="24" cy="22" r="2" fill="#1f4d2c"/>
          <circle cx="29" cy="12" r="2" fill="#1f4d2c"/>
          <path d="M10 29 L30 10" stroke="#1f4d2c" stroke-width="1.5" stroke-dasharray="3 3"/>
        </svg>
        <h3 class="ticket-title">R Fundamentals for Data Exploration and Visualization</h3>
        <p class="ticket-meta"><time datetime="2026-09-22">Tuesday, September 22, 2026</time></p>
        <p class="ticket-instructor">Taught by Jay Maxwell</p>
      </div>
    </article>
    <div class="ticket-footer">
      <div class="ticket-perf"></div>
      <div class="ticket-actions">
        <a class="ticket-btn ticket-btn--outline" href="{{ '/assets/pdf/r_flyer_sept2026.pdf' | relative_url }}">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6"/></svg>
          View flyer <span style="position:absolute;left:-9999px;">for R Fundamentals workshop, PDF</span>
        </a>
        <a class="ticket-btn ticket-btn--primary" href="https://go.iastate.edu/RZEDSG">Register for R Fundamentals</a>
        <a class="ticket-btn ticket-btn--text" href="{{ '/r/overview/' | relative_url }}">Full workshop details →</a>
      </div>
    </div>
  </li>

  <li>
    <article class="ticket-card">
      <div class="ticket-stamp"><span>SEP&nbsp;23</span></div>
      <div class="ticket-body">
        <span class="chip chip--qgis">QGIS</span>
        <svg class="ticket-icon" viewBox="0 0 40 40" fill="none" aria-hidden="true">
          <path d="M20 6 L34 14 L20 22 L6 14 Z" stroke="#1d3f66" stroke-width="1.5" stroke-linejoin="round"/>
          <path d="M6 20 L20 28 L34 20" stroke="#1d3f66" stroke-width="1.5" stroke-linejoin="round"/>
          <path d="M6 26 L20 34 L34 26" stroke="#1d3f66" stroke-width="1.5" stroke-linejoin="round"/>
        </svg>
        <h3 class="ticket-title">Introduction to QGIS Workshop</h3>
        <p class="ticket-meta"><time datetime="2026-09-23">Wednesday, September 23, 2026</time></p>
        <p class="ticket-instructor">Taught by Chris Seeger</p>
      </div>
    </article>
    <div class="ticket-footer">
      <div class="ticket-perf"></div>
      <div class="ticket-actions">
        <a class="ticket-btn ticket-btn--outline" href="{{ '/assets/pdf/qgis_flyer_sept2026.pdf' | relative_url }}">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6"/></svg>
          View flyer <span style="position:absolute;left:-9999px;">for Introduction to QGIS workshop, PDF</span>
        </a>
        <a class="ticket-btn ticket-btn--primary" href="https://go.iastate.edu/B7SRTF">Register for Introduction to QGIS</a>
        <a class="ticket-btn ticket-btn--text" href="{{ '/qgis/overview/' | relative_url }}">Full workshop details →</a>
      </div>
    </div>
  </li>

  <li>
    <article class="ticket-card">
      <div class="ticket-stamp"><span>SEP&nbsp;24</span></div>
      <div class="ticket-body">
        <span class="chip chip--tableau">Tableau</span>
        <svg class="ticket-icon" viewBox="0 0 40 40" fill="none" aria-hidden="true">
          <rect x="6" y="22" width="6" height="12" fill="#7a3b12"/>
          <rect x="17" y="14" width="6" height="20" fill="#7a3b12"/>
          <rect x="28" y="8" width="6" height="26" fill="#7a3b12"/>
        </svg>
        <h3 class="ticket-title">Unlocking the Power of Community Data: Introduction to Tableau Public</h3>
        <p class="ticket-meta"><time datetime="2026-09-24">Thursday, September 24, 2026</time></p>
        <p class="ticket-instructor">Taught by Chris Seeger</p>
      </div>
    </article>
    <div class="ticket-footer">
      <div class="ticket-perf"></div>
      <div class="ticket-actions">
        <a class="ticket-btn ticket-btn--outline" href="{{ '/assets/pdf/tableau_Flyer_sept2026.pdf' | relative_url }}">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6"/></svg>
          View flyer <span style="position:absolute;left:-9999px;">for Introduction to Tableau workshop, PDF</span>
        </a>
        <a class="ticket-btn ticket-btn--primary" href="https://go.iastate.edu/B7SRTF">Register for Introduction to Tableau</a>
        <a class="ticket-btn ticket-btn--text" href="{{ '/tableau/overview/' | relative_url }}">Full workshop details →</a>
      </div>
    </div>
  </li>

</ul>

<p class="bundle-note">Note: the QGIS and Tableau workshops can be bundled during registration for a discounted price.</p>

---

## Additional Resources

Beyond the workshop materials, this site also includes reference guides, helpful tips, and links to software and datasets to support your learning experience. Be sure to explore each workshop page for all the relevant files and instructions.
