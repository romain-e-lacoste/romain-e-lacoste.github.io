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
    font-weight: bold;
    font-size: 1.2em;
    margin: 0.5em 0;
    display: inline-block;
  }

  .plus { display: inline; }
  .minus { display: none; }

  .btnCtrl:checked + .display-status .plus { display: none; }
  .btnCtrl:checked + .display-status .minus { display: inline; }

  .summary-text { display: block; }
  .full-desc { display: none; }

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
    border: 1px solid #ccc;
    border-radius: 8px;
    padding: 1em;
    margin-bottom: 1.5em;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
  }

  .logo img {
    max-width: 100px;
    border-radius: 6px;
  }

  .title {
    font-size: 1.25em;
    font-weight: bold;
  }
</style>

<div class="project">
  <div class="project_item">
    <span class="title">Sparklen</span><br>

    <a href="https://github.com/romain-e-lacoste/sparklen" target="_blank">
      <i class="fa fa-fw fa-github"></i> GitHub
    </a>

    <a href="https://arxiv.org/abs/2502.18979" target="_blank">
      <i class="ai ai-arxiv ai-fw"></i> arXiv
    </a>

    <span class="date">Feb 2025</span>

    <div class="logo">
      <img src="https://raw.githubusercontent.com/romain-e-lacoste/sparklen/main/doc/logos/sparklen-logo-black.svg" alt="Logo">
    </div>

    <input type="checkbox" class="btnCtrl" id="proj1" />
    <label class="btn display-status" for="proj1">
      <span class="plus">+</span>
      <span class="minus">−</span>
    </label>

    <div class="summary-text">
      <p>Toolkit for Hawkes Processes in Python.</p>
    </div>

    <div class="full-desc">
      <p> A statistical learning toolkit for high-dimensional Hawkes processes in Python.</p>
    </div>
      <p>The purpose of <code>Sparklen</code> package is to provide the <code>Python</code> community with a complete suite of cutting-edge tools specifically tailored for the study of exponential Hawkes processes, with a particular focus on high-dimensional framework. It notably features:</p>
      <ul>
        <li>A efficient cluster-based simulation method for generating events.</li>
        <li>A highly versatile and flexible framework for performing inference of multivariate Hawkes process.</li>
        <li>Novel approaches to address the challenge of multiclass classification within the supervised learning framework./li>
      </ul>
    </div>
  </div>
