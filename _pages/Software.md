---
title: "Software"
permalink: /Software/
layout: single
toc: true
author_profile: false
---

<style>
/* 轻量美化：不改主题，只增强排版 */
.card-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:18px;margin:18px 0 28px;}
.card{border:1px solid rgba(0,0,0,.08);border-radius:14px;padding:16px 16px 14px;background:rgba(255,255,255,.6);}
.card h3{margin:0 0 10px;}
.meta{opacity:.75;font-size:.95em;margin-top:2px;}
.two-col{display:grid;grid-template-columns:220px 1fr;gap:18px;align-items:start;}
@media (max-width:640px){.two-col{grid-template-columns:1fr;}}
.logo{max-width:220px;border-radius:12px;border:1px solid rgba(0,0,0,.08);background:#fff;}
.cert{max-width:720px;border-radius:12px;border:1px solid rgba(0,0,0,.08);background:#fff;}
.btnrow{display:flex;flex-wrap:wrap;gap:10px;margin-top:12px;}
hr.sep{margin:26px 0;}
</style>

## Software Tools

<div class="card">
  <div class="two-col">
    <div>
      <img class="logo" src="{{ '/images/yourpackage.png' | relative_url }}" alt="R package logo">
    </div>

    <div>
      <h3>📦 R Package: <strong>YourPackageName</strong></h3>
      <div class="meta">Keywords: XXX, XXX, XXX</div>

      <p>
        <strong>YourPackageName</strong> is an R package for <em>一句话核心功能</em>。
        It provides <em>两三个亮点</em> and supports <em>典型应用场景</em>.
      </p>

      <ul>
        <li><strong>What it solves:</strong> 用一句话说明痛点/问题</li>
        <li><strong>Main features:</strong> Feature A; Feature B; Feature C</li>
      </ul>

      <div class="btnrow">
        <a class="btn btn--primary" href="https://your-tutorial-link">Tutorial</a>
        <a class="btn" href="https://github.com/your-repo">GitHub</a>
        <a class="btn" href="https://cran.r-project.org/package=YourPackageName">CRAN</a>
      </div>
    </div>
  </div>
</div>

<hr class="sep">

## Intellectual Property

<div class="card-grid">

  <div class="card">
    <h3>🧾 Software Copyright</h3>
    <div class="meta">Registration No.: XXXX-XXXX · Year: 2024</div>

    <p>
      <strong>Software Name</strong><br>
      Owner: XXX Lab / Institution
    </p>

    <p class="meta">
      Short note: one sentence about what the software does / why it matters.
    </p>

    <div class="btnrow">
      <a class="btn btn--info" href="{{ '/images/software-copyright-certificate.png' | relative_url }}">
        View Certificate
      </a>
      <a class="btn" href="{{ '/files/software-copyright-certificate.pdf' | relative_url }}">
        Download PDF
      </a>
    </div>
  </div>

  <div class="card">
    <h3>📄 Certificate Preview</h3>
    <img class="cert" src="{{ '/images/software-copyright-certificate.png' | relative_url }}"
         alt="Software Copyright Certificate">
    <div class="meta">Tip: keep image width ≤ 1200px for faster loading.</div>
  </div>

</div>
