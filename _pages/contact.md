---
layout: page
title: Contact
permalink: /contact/
nav: true
nav_order: 3
---

<style>
  .post > article {
    display: block !important;
    width: 100% !important;
  }

  .post .contact-columns {
    display: flex;
    gap: 1.5rem;
    align-items: flex-start;
    max-width: 980px;
    margin: 0 auto;
  }

  .post .contact-main,
  .post .contact-side {
    flex: 1 1 0;
    min-width: 0;
  }

  .post .contact-main {
    display: grid;
    gap: 1.5rem;
  }

  .post .contact-card {
    background: #fff;
    border: 1px solid #d9e6f3;
    border-radius: 18px;
    box-shadow: 0 10px 30px rgba(31, 95, 168, 0.08);
    padding: 1.25rem 1.35rem;
    width: 100%;
    box-sizing: border-box;
  }

  .post .contact-card h2 {
    display: flex;
    align-items: center;
    gap: 0.7rem;
    margin-bottom: 0.85rem;
  }

  .post .contact-card h2 i,
  .post .contact-links i {
    color: #1f5fa8 !important;
  }

  .post .contact-links {
    list-style: none;
    margin: 0;
    padding: 0;
  }

  .post .contact-links li {
    display: flex;
    align-items: center;
    gap: 0.8rem;
    margin-bottom: 0.9rem;
  }

  .post .contact-card a,
  .post .contact-card a:visited {
    color: #1f5fa8 !important;
  }

  @media (max-width: 900px) {
    .post .contact-columns {
      display: block;
    }

    .post .contact-side {
      margin-top: 1.5rem;
    }
  }
</style>

<div class="contact-columns">
  <div class="contact-main">
    <div class="contact-card">
      <h2><i class="fas fa-envelope"></i> Email</h2>
      <p><a href="mailto:sanidhya.gupta@durham.ac.uk">sanidhya.gupta@durham.ac.uk</a></p>
    </div>

    <div class="contact-card">
      <h2><i class="fas fa-building-columns"></i> Affiliation</h2>
      <p>Department of Computer Science<br>Durham University<br>United Kingdom</p>
    </div>
  </div>

  <div class="contact-side">
    <div class="contact-card contact-profiles">
      <h2><i class="fas fa-user-graduate"></i> Academic Profiles</h2>
      <ul class="contact-links">
        <li><i class="ai ai-google-scholar"></i><a href="https://scholar.google.co.uk/citations?view_op=list_works&hl=en&hl=en&tzom=-60&user=FzRzJX8AAAAJ">Google Scholar</a></li>
        <li><i class="fab fa-github"></i><a href="https://github.com/SAN-G-8055">GitHub</a></li>
        <li><i class="fab fa-linkedin"></i><a href="https://www.linkedin.com/in/sanidhya-gupta-79324719b">LinkedIn</a></li>
      </ul>
    </div>
  </div>
</div>
