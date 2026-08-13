---
layout: about
title: Home
permalink: /
nav: true
nav_order: 1

profile:
  align: left
  image: prof_pic.jpeg # IMPORTANT: Make sure this exactly matches your file in assets/img/
  image_circular: false
  more_info: >
    <div class="profile-socials">
      <a href="https://www.linkedin.com/in/sanidhya-gupta-79324719b/" title="LinkedIn" class="profile-link">
        <i class="fab fa-linkedin"></i>
      </a>
      <a href="https://scholar.google.co.uk/citations?view_op=list_works&hl=en&hl=en&tzom=-60&user=FzRzJX8AAAAJ" title="Google Scholar" class="profile-link">
        <i class="ai ai-google-scholar"></i>
      </a>
      <a href="mailto:sanidhya.gupta@durham.ac.uk" title="Email" class="profile-link">
        <i class="fas fa-envelope"></i>
      </a>
    </div>
news: true
selected_papers: false
social: true
---

<style>
  :root {
    --global-theme-color: #1f5fa8 !important;
    --global-hover-color: #174a81 !important;
    --global-hover-text-color: #ffffff !important;
  }

  .post a,
  .post a:visited,
  .post .nav-link,
  .post .profile a,
  .post .more-info a {
    color: #1f5fa8 !important;
  }

  .post a:hover,
  .post a:focus,
  .post .profile a:hover,
  .post .more-info a:hover {
    color: #174a81 !important;
  }

  .post article {
    display: grid;
    grid-template-columns: 280px minmax(0, 760px);
    column-gap: 2rem;
    align-items: start;
    width: 100%;
  }

  .post article .profile {
    grid-column: 1;
    grid-row: 1;
    float: none;
    width: 280px;
    margin: 0;
    justify-self: start;
    align-self: center;
  }

  .post article .clearfix {
    display: contents;
  }

  .post .about-intro {
    grid-column: 2;
    grid-row: 1;
    align-self: center;
    width: 100%;
    max-width: 760px;
  }

  .post .home-sections {
    grid-column: 1 / -1;
    grid-row: 2;
    width: 100%;
    margin-top: 1rem;
    max-width: 1040px;
  }

  .post article .profile .more-info {
    margin-top: 0.9rem;
    text-align: center;
  }

  .post article .profile .more-info p,
  .post article .profile .more-info small,
  .post article .profile .more-info br {
    display: none !important;
  }

  .post article .profile .profile-socials {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin: 0.9rem 0 0 0;
  }

  .post article .profile .profile-link,
  .post article .profile .profile-link:visited {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 44px;
    height: 44px;
    border-radius: 50%;
    background: #edf4fb;
    border: 1px solid #d9e6f3;
    color: #1f5fa8 !important;
  }

  .post article .profile .profile-link i {
    color: #1f5fa8 !important;
    font-size: 1.35rem;
  }

  .post article .profile .profile-link:hover {
    background: #1f5fa8;
    color: #ffffff !important;
  }

  .post article .profile .profile-link:hover i {
    color: #ffffff !important;
  }

  @media (max-width: 900px) {
    .post article {
      display: block;
    }

    .post article .profile {
      margin-bottom: 1.25rem;
    }
  }
</style>

<div class="about-intro">

<p>Hello! I am a Ph.D. student in Computer Science (Quantum Information &amp; Networking) at <a href="https://www.durham.ac.uk/departments/academic/computer-science/">Durham University</a>, advised by <a href="https://scholar.google.com/citations?user=tRd9i5kAAAAJ&hl=en">Dr. Thirupathaiah Vasantam</a> and <a href="https://scholar.google.com/citations?user=6ggttpsAAAAJ&hl=en">Prof. Neil Walton</a>.</p>

<p>My research lies at the intersection of <strong>quantum computing, network theory, and computer architecture</strong>. I focus on developing systems-level scheduling and resource-allocation frameworks for <strong>Modular Fault-Tolerant Quantum Computing (FTQC)</strong>. My goal is to design control and networking protocols that allow distributed, multi-core quantum computers to act as a single, powerful machine. To do this, I combine tools from queueing theory, stochastic modeling, and quantum error correction.</p>

<p>Previously, I completed my BS-MS (Major in EECS, Minor in Data Science) at <a href="https://www.iiserb.ac.in/">IISER Bhopal</a>, advised by <a href="https://sites.google.com/view/ankurraina/">Dr. Ankur Raina</a>. During this time, I worked on measurement-based quantum computing (MBQC) and quantum network coding. This research was partly supported by the <a href="https://www.quantech.org.in/about/fellowships">Chanakya UG and PG Fellowships</a>, awarded by the Department of Science (Government of India).</p>

<p>You can find more details in my <a href="{{ '/assets/pdf/Sanidhya_Gupta_CV.pdf' | relative_url }}">Curriculum Vitae</a>. I am always happy to chat about quantum architecture, network theory, or potential collaborations. Feel free to reach out at <a href="mailto:sanidhya.gupta@durham.ac.uk">sanidhya.gupta@durham.ac.uk</a>.</p>

</div>

<div class="home-sections">

<hr>

<h3>Research Interests</h3>
<ul>
  <li><strong>Modular Quantum Architectures:</strong> Distributed quantum computing, fault-tolerant architectures, and hardware-aware methods for scalable universal quantum computation.</li>
  <li><strong>Quantum Networking:</strong> Entanglement routing, quantum network coding, and quantum interconnect protocols.</li>
  <li><strong>Resource Allocation &amp; Control:</strong> Latency-aware scheduling, queueing-theoretic performance modeling, and cross-layer classical control for FTQC.</li>
</ul>

<hr>

<h3>News</h3>
<ul>
  <li><strong>August 13, 2026:</strong> Our paper <a href="https://arxiv.org/abs/2403.07596"><strong>"A Provably Secure Framework for Noise-Aware Delegated Quantum Computation and Storage"</strong></a>, was accepted for publication in <em>Quantum Information Processing</em>.</li>

  <li><strong>August 10–21, 2026:</strong> Currently attending the <a href="https://www.sdu.dk/en/forskning/qm/events/niels-bohr-quantum-summer-school-2026"><strong>Niels Bohr Quantum Summer School 2026</strong></a> at the University of Southern Denmark, focusing on quantum algorithms and quantum software.</li>

  <li><strong>July 6, 2026:</strong> Our paper <a href="https://arxiv.org/abs/2604.22471"><strong>"Boundary-Aware Stabilizer Scheduling for Distributed Quantum Error Correction"</strong></a> was accepted as a technical paper in the <strong>Quantum Networking &amp; Communications (QNET)</strong> track at IEEE Quantum Week (QCE 2026).</li>

  <li><strong>July 2, 2026:</strong> Successfully passed my 9-month Annual Progress Review for my PhD at Durham University.</li>

  <li><strong>June 24–26, 2026:</strong> Attended <a href="https://qec.codes/tartan2026/"><strong>TartanQEC 2026</strong></a> at the University of Edinburgh, a workshop focused on practical quantum error correction.</li>

  <li><strong>June 22, 2026:</strong> Presented <strong>"Scheduling Quantum Error Correction Across Networked Quantum Processors"</strong> at Durham University's Inter-Collegiate Research Conference 2026.</li>

  <li><strong>June 15–18, 2026:</strong> Attended the <a href="https://informed-ai.net/event/summer-school-2026/"><strong>INFORMED AI Summer School 2026</strong></a> at the University of Bristol School of Mathematics.</li>

  <li><strong>June 9–11, 2026:</strong> Volunteered at <a href="https://sirocco2026.webspace.durham.ac.uk/"><strong>SIROCCO 2026</strong></a>, the 33rd International Colloquium on Structural Information and Communication Complexity, held at Durham University.</li>

  <li><strong>May 12–13, 2026:</strong> Attended the <a href="https://iqnhub.org/qnetworks-2026/#programme"><strong>QNetworks 2026</strong></a> workshop in Bristol on quantum networking and distributed quantum computing.</li>

  <li><strong>October 1, 2025:</strong> Started my PhD in Computer Science at Durham University in Quantum Information and Networking.</li>
</ul>

</div>
