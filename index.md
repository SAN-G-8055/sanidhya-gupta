---
layout: page
title: Home
permalink: /
nav: true
nav_order: 1
description: Home page for Sanidhya Gupta, PhD Student in Computer Science at Durham University.
---

<section class="hero-grid">
  <div>
    <p class="eyebrow">Academic Homepage</p>
    <h1 class="home-title">Sanidhya Gupta</h1>
    <p class="home-subtitle">PhD Student in Computer Science (Quantum Information and Networking)</p>
    <p class="home-affiliation">Durham University, United Kingdom</p>
    <p class="home-meta">Started October 2025 · Supervised by Dr. Thirupathaiah Vasantam and Prof. Neil Walton</p>
    <p class="home-intro">
      I am a PhD student at Durham University working on modular fault-tolerant quantum computing,
      distributed quantum error correction, quantum networking, scheduling and resource allocation
      for quantum architectures, and measurement-based quantum computation.
    </p>

    <div class="pill-row">
      <span class="interest-pill">Modular fault-tolerant quantum computing</span>
      <span class="interest-pill">Distributed quantum error correction</span>
      <span class="interest-pill">Quantum networking</span>
      <span class="interest-pill">Scheduling and resource allocation</span>
      <span class="interest-pill">Measurement-based quantum computation</span>
    </div>

    <div class="button-row">
      <a class="primary-button" href="{{ '/assets/pdf/Sanidhya_Gupta_CV.pdf' | relative_url }}">Download CV</a>
      <a class="secondary-button" href="{{ '/publications/' | relative_url }}">View Publications</a>
    </div>

    <div class="social-row">
      <a href="mailto:sanidhya.gupta@durham.ac.uk">Email</a>
      <a href="https://github.com/REPLACE_WITH_GITHUB_USERNAME">GitHub</a>
      <a href="https://scholar.google.com/citations?user=REPLACE_WITH_SCHOLAR_ID">Google Scholar</a>
      <a href="https://www.linkedin.com/in/REPLACE_WITH_LINKEDIN_USERNAME/">LinkedIn</a>
    </div>
  </div>

  <div class="profile-card">
    <img src="{{ '/assets/img/profile-placeholder.svg' | relative_url }}" alt="Profile placeholder for Sanidhya Gupta">
    <p class="profile-caption">Replace with your profile image at <code>assets/img/profile.jpg</code> or update the path in <code>index.md</code>.</p>
  </div>
</section>

<section class="section-block">
  <h2>Research Snapshot</h2>
  <div class="theme-grid">
    <article class="theme-card">
      <h3>Distributed QEC Scheduling</h3>
      <p>Boundary-aware stabilizer scheduling for modular quantum architectures over noisy photonic interconnects.</p>
    </article>
    <article class="theme-card">
      <h3>Magic-State Supply</h3>
      <p>Queueing and inventory perspectives on shared magic-state pumping architectures for distributed quantum computers.</p>
    </article>
    <article class="theme-card">
      <h3>MBQC and Quantum Networks</h3>
      <p>Measurement-based protocols, delegated quantum computation, and entanglement distribution in networked settings.</p>
    </article>
  </div>
</section>

<section class="section-block">
  <h2>Selected Updates</h2>
  <div class="news-list">
    {% assign ordered_news = site.news | sort: "date" | reverse %}
    {% for item in ordered_news limit: 3 %}
      <article class="news-item">
        <p class="news-date">{{ item.date | date: "%b %Y" }}</p>
        <h3>{{ item.title }}</h3>
        <p>{{ item.content | markdownify | strip_html | truncatewords: 28 }}</p>
      </article>
    {% endfor %}
  </div>
  <p class="small-note">Add or update news items in <code>_news/</code> as your website grows.</p>
</section>
