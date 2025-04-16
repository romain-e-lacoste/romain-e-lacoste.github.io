---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
redirect_from:
  - /resume
---

<style>
  .btnCtrl { display: none; }

  .display-status {
    cursor: pointer;
    font-size: 1.2em;
    margin-left: 0.5em;
  }

  .plus { display: inline; }
  .minus { display: none; }

  .btnCtrl:checked + .display-status .plus { display: none; }
  .btnCtrl:checked + .display-status .minus { display: inline; }

  .summary-text {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 0.5em;
  }

  .summary-text p { margin: 0; }

  .full-desc {
    display: none;
    margin-top: 0.5em;
  }

  .btnCtrl:checked ~ .summary-text { display: none; }
  .btnCtrl:checked ~ .full-desc { display: block; }

  .full-desc ul {
    padding-left: 1.2em;
  }

  .full-desc code {
    background-color: #f6f8fa;
    padding: 2px 4px;
    border-radius: 4px;
  }

  .project {
    background-color: #f0f0f0;
    border-radius: 8px;
    margin: 1em;
    padding: 1em;
    width: 95%;
    box-sizing: border-box;
  }

  .top-row {
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
  }

  .title-section {
    display: flex;
    align-items: center;
    gap: 1em;
    flex-wrap: wrap;
  }

  .title {
    font-size: 1.25em;
    font-weight: bold;
  }

  .meta a {
    margin-right: 0.7em;
    text-decoration: none;
    color: #0366d6;
    font-size: 0.95em;
  }

  .date {
    color: #666;
    font-size: 0.9em;
    margin-left: 0.5em;
    font-style: italic;
  }

  .logo img {
    max-width: 80px;
    border-radius: 6px;
  }
</style>

<div class="project">
  <div class="top-row">
    <div class="title-section">
      <span class="title">Sparklen</span>
      <span class="meta">
        <a href="https://github.com/romain-e-lacoste/sparklen" target="_blank">
          <i class="fa fa-fw fa-github"></i> GitHub
        </a>
        <a href="https://arxiv.org/abs/2502.18979" target="_blank">
          <i class="ai ai-arxiv ai-fw"></i> arXiv
        </a>
        <span class="date">Feb 2025</span>
      </span>
    </div>
    <div class="logo">
      <img src="https://raw.githubusercontent.com/romain-e-lacoste/sparklen/main/doc/logos/sparklen-logo-black.svg" alt="Logo">
    </div>
  </div>

  <input type="checkbox" class="btnCtrl" id="proj1" />
  <label class="btn display-status" for="proj1">
    <i class="fa fa-plus-circle plus"></i>
    <i class="fa fa-minus-circle minus"></i>
  </label>

  <div class="summary-text">
    <p>Toolkit for Hawkes Processes in Python.</p>
  </div>

  <div class="full-desc">
    <p>It notably features:</p>
    <ul>
      <li>A efficient cluster-based simulation method for generating events.</li>
      <li>A highly versatile and flexible framework for performing inference of multivariate Hawkes process.</li>
      <li>Novel approaches to address the challenge of multiclass classification within the supervised learning framework.</li>
    </ul>
  </div>
</div>
