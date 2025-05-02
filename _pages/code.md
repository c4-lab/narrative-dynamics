---
title: "Code Repositories"
permalink: /code/
layout: single
toc: true
toc_label: "Repository Categories"
toc_icon: "code"
header:
  overlay_color: "#000"
  overlay_filter: "0.4"
  overlay_image: /assets/images/code-banner.jpg
excerpt: "Software and analysis code from our research"
---

# Code Repositories

Our research relies on several custom software tools, all of which are available as open-source repositories under the MIT License.

{% include coming-soon.html title="Public Code Repositories" message="We're currently preparing our code repositories for public release. These will include our simulation frameworks, analysis tools, and experimental platforms." date="Q2 2025" %}

## Simulation Framework

<div class="repo-card">
  <div class="repo-status">Coming Soon</div>
  <h3><i class="fab fa-github"></i> Narrative Simulation Framework</h3>
  <p class="repo-description">This repository contains our agent-based simulation framework for modeling narrative diffusion in social networks. The framework allows researchers to:</p>
  <ul>
    <li>Configure various network topologies</li>
    <li>Set different agent parameters for adoption thresholds</li>
    <li>Define custom narrative structures</li>
    <li>Run simulations with varying temporal dynamics</li>
    <li>Collect and analyze simulation results</li>
  </ul>
  <div class="repo-tech">
    <span class="tech-badge">Python</span>
    <span class="tech-badge">NetworkX</span>
    <span class="tech-badge">NumPy</span>
    <span class="tech-badge">Matplotlib</span>
  </div>
  <div class="repo-links">
    <a href="#" class="repo-link disabled">GitHub Repository</a>
    <a href="#" class="repo-link disabled">Documentation</a>
  </div>
</div>

## Analysis Tools

<div class="repo-card">
  <div class="repo-status">Coming Soon</div>
  <h3><i class="fab fa-github"></i> Narrative Analysis Package</h3>
  <p class="repo-description">This package provides tools for analyzing experimental data from narrative diffusion studies, including:</p>
  <ul>
    <li>Data preprocessing and cleaning functions</li>
    <li>Statistical analysis modules for adoption patterns</li>
    <li>Visualization tools for network-based diffusion</li>
    <li>Model fitting and parameter estimation</li>
    <li>Comparison between experimental data and simulation results</li>
  </ul>
  <div class="repo-tech">
    <span class="tech-badge">R</span>
    <span class="tech-badge">tidyverse</span>
    <span class="tech-badge">lme4</span>
    <span class="tech-badge">ggplot2</span>
  </div>
  <div class="repo-links">
    <a href="#" class="repo-link disabled">GitHub Repository</a>
    <a href="#" class="repo-link disabled">Package Documentation</a>
  </div>
</div>

## Experimental Platform

<div class="repo-card">
  <div class="repo-status">Coming Soon</div>
  <h3><i class="fab fa-github"></i> Narrative Experiment Platform</h3>
  <p class="repo-description">This repository contains the web-based platform used to conduct our narrative diffusion experiments. Features include:</p>
  <ul>
    <li>Real-time participant interaction within networks</li>
    <li>Dynamic visualization of narrative elements</li>
    <li>Survey integration for pre/post assessments</li>
    <li>Researcher dashboard for experiment monitoring</li>
    <li>Data collection and storage modules</li>
  </ul>
  <div class="repo-tech">
    <span class="tech-badge">Node.js</span>
    <span class="tech-badge">Express</span>
    <span class="tech-badge">MongoDB</span>
    <span class="tech-badge">D3.js</span>
    <span class="tech-badge">React</span>
  </div>
  <div class="repo-links">
    <a href="#" class="repo-link disabled">GitHub Repository</a>
    <a href="#" class="repo-link disabled">Setup Guide</a>
  </div>
</div>

## Code Usage Examples

{% include coming-soon.html title="Usage Examples and Tutorials" message="We're developing comprehensive examples and tutorials to help researchers use our tools effectively. These will include step-by-step guides for common analysis tasks and simulation scenarios." %}

## Planned Releases

Below is our timeline for code repository releases:

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
      <h4>Q2 2025</h4>
      <p>Initial release of Narrative Simulation Framework with basic documentation</p>
    </div>
  </div>
  <div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
      <h4>Q3 2025</h4>
      <p>Release of Narrative Analysis Package with example notebooks</p>
    </div>
  </div>
  <div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
      <h4>Q4 2025</h4>
      <p>Release of Experimental Platform code with setup documentation</p>
    </div>
  </div>
  <div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
      <h4>Q1 2026</h4>
      <p>Comprehensive tutorials and integration examples for all repositories</p>
    </div>
  </div>
</div>

---

<div class="code-contact">
  <h2>Questions or Contributions?</h2>
  <p>If you're interested in contributing to our code repositories or have questions about implementing our methods, please <a href="mailto:jeintron@syr.edu">contact us</a>.</p>
</div>

<div class="page-styles">
<style>
.repo-card {
  background-color: #f8f9fa;
  border-radius: 5px;
  padding: 20px;
  margin-bottom: 30px;
  border: 1px solid #eaeaea;
  position: relative;
}

.repo-status {
  position: absolute;
  top: 15px;
  right: 15px;
  background-color: #f8961e;
  color: white;
  padding: 5px 10px;
  border-radius: 3px;
  font-size: 0.8em;
  font-weight: bold;
}

.repo-description {
  margin-top: 10px;
}

.repo-tech {
  margin-top: 15px;
  margin-bottom: 15px;
}

.tech-badge {
  display: inline-block;
  background-color: #e9ecef;
  color: #495057;
  padding: 3px 8px;
  border-radius: 3px;
  font-size: 0.8em;
  margin-right: 5px;
  margin-bottom: 5px;
}

.repo-links {
  margin-top: 15px;
}

.repo-link {
  display: inline-block;
  margin-right: 15px;
  text-decoration: none;
}

.repo-link.disabled {
  color: #6c757d;
  cursor: not-allowed;
  text-decoration: line-through;
}

.timeline {
  margin-left: 20px;
  margin-top: 30px;
  position: relative;
}

.timeline:before {
  content: '';
  position: absolute;
  left: 0;
  top: 0;
  height: 100%;
  width: 2px;
  background-color: #ddd;
}

.timeline-item {
  position: relative;
  padding-left: 30px;
  margin-bottom: 30px;
}

.timeline-marker {
  position: absolute;
  left: -8px;
  top: 5px;
  width: 18px;
  height: 18px;
  border-radius: 50%;
  background-color: #0092ca;
  border: 2px solid white;
}

.timeline-content h4 {
  margin-top: 0;
  margin-bottom: 10px;
}

.timeline-content p {
  margin: 0;
}

.code-contact {
  margin-top: 40px;
  padding-top: 20px;
  border-top: 1px solid #eaeaea;
}
</style>
</div>
