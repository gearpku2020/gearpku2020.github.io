---
title: "Resources"
permalink: /Resources/
layout: single
toc: true
author_profile: false
---

<style>
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
      <img class="logo" src="{{ '/images/easyEWAS.png' | relative_url }}" alt="R package logo">
    </div>

    <div>
      <h3>R Package: <strong>easyEWAS</strong></h3>
      <p>
        This is an R package for conducting epigenome-wide association studies (EWAS).
        With easyEWAS, we provide a battery of statistical methods to support differential methylation position analysis across various scenarios, as well as differential methylation region analysis based on the DMRcate method.
      </p>

      <div class="btnrow">
        <a class="btn btn--primary" href="https://easyewas.github.io/index.html">Tutorial</a>
        <a class="btn" href="https://github.com/ytwangZero/easyEWAS">GitHub</a>
        <a class="btn" href="https://academic.oup.com/bioinformaticsadvances/article/5/1/vbaf026/8011369">Paper</a>
        <a class="btn" href="{{ '/files/easyEWAS-manual.pdf' | relative_url }}">PDF Guide</a>
      </div>
    </div>
  </div>
</div>

<hr class="sep">

## Intellectual Property

<div class="card-grid">

  <div class="card">
    <h3>🧾 Software Copyright</h3>
    <div class="meta">Registration No. 16541871   Year: 2025</div>

    <p>
      <strong>An Integrated Pipeline for Epigenome-Wide Association Analysis V1.0</strong><br>
      Owner: GEAR Lab, Peking University
    </p>

    <p class="meta">
      This Analysis System for Epigenome-Wide Association Studies (EWAS) V1.0 is a one-stop tool for Illumina DNA methylation arrays. It integrates data preprocessing, differential methylation analysis, and downstream functional annotation, and supports cohort, intervention, and longitudinal study designs.
    </p>

    <div class="btnrow">
      <a class="btn btn--info" href="{{ '/images/easyEWAS-copyright.png' | relative_url }}">
        View Certificate
      </a>
    </div>
  </div>

  <div class="card">
    <h3>📄 Certificate Preview</h3>
    <img class="cert" src="{{ '/images/easyEWAS-copyright.png' | relative_url }}"
         style="max-width:100%; width:100%; height:auto;">
  </div>

</div>
