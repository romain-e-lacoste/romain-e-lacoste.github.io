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

  .display-status .plus { display: inline; }
  .display-status .minus { display: none; }

  .btnCtrl:checked + .display-status .plus { display: none; }
  .btnCtrl:checked + .display-status .minus { display: inline; }

  .package-desc { display: none; margin-top: 0.5em; }

  .btnCtrl:checked ~ .package-desc { display: block; }

  .project {
    border: 1px solid #ccc;
    border-radius: 8px;
    padding: 1em;
    margin-bottom: 1.5em;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
  }

  .project_item {
    flex: 1;
  }

  .title {
    font-size: 1.25em;
    font-weight: bold;
  }

  .logo img {
    max-width: 100px;
    border-radius: 6px;
  }

  .project_item a {
    margin-right: 10px;
    text-decoration: none;
    color: #0366d6;
  }

  .date {
    font-style: italic;
    color: #666;
    font-size: 0.9em;
    display: inline-block;
    margin-top: 0.5em;
  }
</style>

<div class="project">
  <div class="project_item">
    <span class="title">Sparklen</span><br>

    <a href="https://github.com/romain-e-lacoste/sparklen" target="_blank">
      <i class="fa fa-fw fa-github"></i> GitHub
    </a>

    <a href="https://arxiv.org/abs/1234.56789" target="_blank">
      <i class="fa fa-fw fa-file-pdf-o"></i> arXiv
    </a>

    <span class="date">Feb 2025</span>

    <p>A statistical learning toolkit for high-dimensional Hawkes processes in Python.</p>

    <input type="checkbox" class="btnCtrl" id="proj1" />
    <label class="btn display-status" for="proj1">
      <i class="fa fa-plus-circle plus"></i> Show more
      <i class="fa fa-minus-circle minus"></i> Show less
    </label>

    <div class="package-desc">
      <p>
        The purpose of `Sparklen` package is to provide the `Python` community with 
        a complete suite of cutting-edge tools specifically tailored for 
        the study of exponential Hawkes processes, with a particular focus 
        on high-dimensional framework. It notably features:

        * A efficient cluster-based simulation method for generating events.

        * A highly versatile and flexible framework for performing inference of 
          multivariate Hawkes process.

        * Novel approaches to address the challenge of multiclass 
          classification within the supervised learning framework.
      </p>
    </div>
  </div>

  <div class="logo">
    <img src="https://raw.githubusercontent.com/romain-e-lacoste/sparklen/main/doc/logos/sparklen-logo-black.svg" alt="Sparklen logo" width=250/>
  </div>
</div>

