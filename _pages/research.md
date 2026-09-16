---
layout: page
title: Publications
permalink: /publications/
nav: true
nav_order: 2
---

<style>
  .post > article {
    display: block !important;
    width: 100% !important;
  }

  .post .publications-shell {
    max-width: 940px;
    margin: 0 auto;
    width: 100%;
  }

  .post .publication-item {
    display: grid;
    grid-template-columns: 3.8rem minmax(0, 1fr);
    column-gap: 1.25rem;
    align-items: start;
    padding: 1.2rem 0 1.35rem 0;
    border-bottom: 1px solid var(--global-divider-color);
  }

  .post .publication-item:first-child {
    padding-top: 0.4rem;
  }

  .post .publication-item:last-child {
    border-bottom: none;
  }

  .post .pub-year {
    font-size: 0.92rem;
    font-weight: 700;
    color: var(--global-theme-color);
    line-height: 1.65;
    padding-top: 0.05rem;
  }

  .post .pub-copy {
    min-width: 0;
    line-height: 1.65;
    color: var(--global-text-color);
  }

  .post .pub-authors {
    display: block;
    margin-bottom: 0.18rem;
  }

  .post .pub-title {
    display: inline-block;
    font-size: 1.03rem;
    font-weight: 650;
    color: var(--global-theme-color) !important;
    text-decoration: none;
    margin-bottom: 0.18rem;
  }

  .post .pub-title:hover {
    text-decoration: underline;
  }

  .post .pub-venue {
    display: block;
    margin-top: 0.12rem;
  }

  .post .pub-note {
    font-size: 0.92rem;
    font-weight: 500;
  }

  .post .pub-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem;
    margin-top: 0.55rem;
  }

  .post .pub-link {
    display: inline-block;
    padding: 0.12rem 0.55rem;
    border: 1px solid var(--global-theme-color);
    border-radius: 4px;
    color: var(--global-theme-color) !important;
    font-size: 0.82rem;
    font-weight: 600;
    text-decoration: none;
    line-height: 1.45;
  }

  .post .pub-link:hover {
    color: var(--global-bg-color) !important;
    background-color: var(--global-theme-color);
    text-decoration: none;
  }

  @media (max-width: 600px) {
    .post .publication-item {
      grid-template-columns: 1fr;
      row-gap: 0.25rem;
    }

    .post .pub-year {
      margin-bottom: 0.1rem;
    }
  }
</style>

<div class="publications-shell">

  <!-- QCE 2026 -->
  <div class="publication-item">
    <div class="pub-year">2026</div>

    <div class="pub-copy">
      <span class="pub-authors">
        <strong>Gupta, S.</strong>, Bhambay, S., Alavisamani, N.,
        Walton, N., &amp; Vasantam, T.
      </span>

      <a class="pub-title"
         href="https://arxiv.org/abs/2604.22471"
         target="_blank"
         rel="noopener noreferrer">
        Boundary-Aware Stabilizer Scheduling for Distributed Quantum Error Correction
      </a>

      <span class="pub-venue">
        Technical paper,
        <strong>2026 IEEE International Conference on Quantum Computing
        and Engineering (QCE26)</strong>,
        Quantum Networks and Communications (QNET) track.
        <span class="pub-note">Presenting author.</span>
      </span>

      <div class="pub-links">
        <a class="pub-link"
           href="https://arxiv.org/abs/2604.22471"
           target="_blank"
           rel="noopener noreferrer">
          arXiv
        </a>
      </div>
    </div>
  </div>


  <!-- Quantum Information Processing 2026 -->
  <div class="publication-item">
    <div class="pub-year">2026</div>

    <div class="pub-copy">
      <span class="pub-authors">
        <strong>Gupta, S.</strong> &amp; Raina, A.
      </span>

      <a class="pub-title"
         href="https://doi.org/10.1007/s11128-026-05329-4"
         target="_blank"
         rel="noopener noreferrer">
        A Provably Secure Framework for Noise-Aware Delegated Quantum Computation and Storage
      </a>

      <span class="pub-venue">
        <em>Quantum Information Processing</em>,
        <strong>25</strong>, Article 309 (2026).
      </span>

      <div class="pub-links">
        <a class="pub-link"
           href="https://doi.org/10.1007/s11128-026-05329-4"
           target="_blank"
           rel="noopener noreferrer">
          DOI
        </a>

        <a class="pub-link"
           href="https://arxiv.org/abs/2403.07596"
           target="_blank"
           rel="noopener noreferrer">
          arXiv
        </a>
      </div>
    </div>
  </div>


  <!-- IEEE QCE 2024 -->
  <div class="publication-item">
    <div class="pub-year">2024</div>

    <div class="pub-copy">
      <span class="pub-authors">
        <strong>Gupta, S.</strong> &amp; Raina, A.
      </span>

      <a class="pub-title"
         href="https://doi.org/10.1109/QCE60285.2024.10252"
         target="_blank"
         rel="noopener noreferrer">
        A Feed-Forward Method for Encoding a Stabilizer Code Using Measurement-Based Quantum Computing
      </a>

      <span class="pub-venue">
        QADA Workshop at
        <strong>2024 IEEE International Conference on Quantum Computing
        and Engineering (QCE)</strong>,
        Montréal, Canada.
      </span>

      <div class="pub-links">
        <a class="pub-link"
           href="https://doi.org/10.1109/QCE60285.2024.10252"
           target="_blank"
           rel="noopener noreferrer">
          DOI
        </a>
      </div>
    </div>
  </div>


  <!-- NCC 2023 -->
  <div class="publication-item">
    <div class="pub-year">2023</div>

    <div class="pub-copy">
      <span class="pub-authors">
        Pandey, C., <strong>Gupta, S.</strong>, Das, R. R., &amp; Raina, A.
      </span>

      <a class="pub-title"
         href="https://doi.org/10.1109/NCC56989.2023.10067927"
         target="_blank"
         rel="noopener noreferrer">
        Quantum Network Coding and Distribution of Maximally Entangled States in Measurement-Based Quantum Computing
      </a>

      <span class="pub-venue">
        <strong>2023 National Conference on Communications (NCC)</strong>,
        IIT Guwahati, India.
      </span>

      <div class="pub-links">
        <a class="pub-link"
           href="https://doi.org/10.1109/NCC56989.2023.10067927"
           target="_blank"
           rel="noopener noreferrer">
          DOI
        </a>
      </div>
    </div>
  </div>

</div>
