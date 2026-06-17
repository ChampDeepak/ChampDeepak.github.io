---
layout: page
title: Portfolio
permalink: /portfolio/
description: Selected research, AI and software engineering projects by Deepak Sharma.
---

<p class="page-lede">Full-Stack Developer &amp; Machine Learning enthusiast. A selection of things I’ve researched, designed and shipped — from text-to-music research to event-driven data pipelines and agentic AI.</p>

<h2 class="section-heading portfolio-group">Research &amp; AI</h2>

<div class="projects">

  <article class="project">
    <h3 class="project__title">Inter-Sample Similarity Analysis in Text-to-Music Models</h3>
    <p class="project__role">Research Project</p>
    <p class="project__desc">An empirical study of diversity and inter-sample similarity in text-to-music generation using the open-source HeartMula model. Generated and analysed <strong>1,760 audio clips</strong> to compare encoding-level interventions against prompt-expansion strategies, and designed a qualitative framework to surface the trade-offs between latent-space interventions and prompt engineering.</p>
    <ul class="project__tags">
      <li>Generative Audio</li><li>Empirical Study</li><li>Prompt Engineering</li>
    </ul>
    <p class="project__links">
      <a href="https://github.com/ChampDeepak/txt2music" target="_blank" rel="noopener">Source ↗</a>
      <a href="https://github.com/ChampDeepak/txt2music/blob/main/paper/paper.pdf" target="_blank" rel="noopener">Paper ↗</a>
    </p>
  </article>

  <article class="project">
    <h3 class="project__title">Corrective RAG System</h3>
    <p class="project__role">Agentic AI · LLMs · Retrieval-Augmented Generation</p>
    <p class="project__desc">An agentic Corrective RAG pipeline that validates retrieved context <em>before</em> response generation to reduce hallucinations. Built retrieval, reranking and answer-generation workflows for grounded question answering, and deployed it as an interactive app.</p>
    <ul class="project__tags">
      <li>RAG</li><li>LLMs</li><li>Agents</li>
    </ul>
    <p class="project__links">
      <a href="https://github.com/ChampDeepak/simplerag" target="_blank" rel="noopener">Source ↗</a>
      <a href="https://simplerag.vercel.app/" target="_blank" rel="noopener">Live demo ↗</a>
    </p>
  </article>

  <article class="project">
    <h3 class="project__title">Assistive Object Detection for the Visually Impaired</h3>
    <p class="project__role">Computer Vision · Deep Learning</p>
    <p class="project__desc">Explored and evaluated deep-learning object-detection pipelines for detecting and localizing everyday objects in real-world scenes, aimed at assisting visually impaired users.</p>
    <ul class="project__tags">
      <li>Object Detection</li><li>CNNs</li><li>Accessibility</li>
    </ul>
    <p class="project__links">
      <a href="https://github.com/ChampDeepak/Team_Panchtatv" target="_blank" rel="noopener">Source ↗</a>
    </p>
  </article>

  <article class="project">
    <h3 class="project__title">Fake Social Media Account Detection</h3>
    <p class="project__role">Machine Learning · Classification</p>
    <p class="project__desc">A supervised classification pipeline that uses profile-level behavioral features to flag fraudulent accounts. Performed feature engineering, compared classical ML models on their precision/recall trade-offs, and deployed via Streamlit.</p>
    <ul class="project__tags">
      <li>scikit-learn</li><li>Feature Engineering</li><li>Streamlit</li>
    </ul>
    <p class="project__links">
      <a href="https://github.com/ChampDeepak/FakeAccDetection" target="_blank" rel="noopener">Source ↗</a>
      <a href="https://fakeaccdetection.streamlit.app/" target="_blank" rel="noopener">Live demo ↗</a>
    </p>
  </article>

</div>

<h2 class="section-heading portfolio-group">Software Engineering</h2>

<div class="projects">

  <article class="project">
    <h3 class="project__title">Messaging &amp; Collaboration Platform</h3>
    <p class="project__role">React · Node.js · Inngest · Sentry</p>
    <p class="project__desc">A real-time messaging platform integrating Inngest for background jobs and Sentry for live error tracking to cut production downtime. Secured user sessions with Clerk, enabled low-latency messaging via Stream.io, and translated a provided design system into a pixel-perfect responsive UI with Tailwind CSS.</p>
    <ul class="project__tags">
      <li>React</li><li>Node.js</li><li>Stream.io</li><li>Tailwind CSS</li>
    </ul>
    <p class="project__links">
      <a href="https://github.com/ChampDeepak/slack-clone" target="_blank" rel="noopener">Source ↗</a>
      <a href="https://slack-clone-frontend-fawn.vercel.app/" target="_blank" rel="noopener">Live demo ↗</a>
    </p>
  </article>

  <article class="project">
    <h3 class="project__title">Automated ETL Data Pipeline</h3>
    <p class="project__role">Google Apps Script · GitHub Actions · Python</p>
    <p class="project__desc">An event-driven pipeline that triggers data validation via Google Apps Script the moment a Google Sheet updates. Automated the full Extract-Transform-Load workflow with GitHub Actions, eliminating data-entry errors through strict type-checking and automated alerts.</p>
    <ul class="project__tags">
      <li>Event-Driven</li><li>CI/CD</li><li>Python</li>
    </ul>
    <p class="project__links">
      <a href="https://github.com/ChampDeepak/etlPipeline" target="_blank" rel="noopener">Source ↗</a>
    </p>
  </article>

  <article class="project">
    <h3 class="project__title">Custom HTTP Server</h3>
    <p class="project__role">Python · Socket Programming · TCP/IP</p>
    <p class="project__desc">A lightweight, multi-threaded HTTP server built from first principles with Python sockets to understand TCP, HTTP parsing and connection lifecycles. Engineered robust parsing for GET/POST methods and static-file serving, with a focus on throughput.</p>
    <ul class="project__tags">
      <li>Sockets</li><li>Concurrency</li><li>From Scratch</li>
    </ul>
    <p class="project__links">
      <a href="https://github.com/ChampDeepak/httpbasedserver" target="_blank" rel="noopener">Source ↗</a>
    </p>
  </article>

  <article class="project">
    <h3 class="project__title">Energy Monitoring CLI Tool</h3>
    <p class="project__role">Java · JDBC · MySQL</p>
    <p class="project__desc">A normalized relational schema with indexing strategies in MySQL to speed up heavy aggregation queries for an electricity-monitoring platform. Wrote Java JDBC routines to aggregate daily energy usage, billing estimates and budgets into a wrapped CLI app.</p>
    <ul class="project__tags">
      <li>Java</li><li>SQL</li><li>Data Modeling</li>
    </ul>
    <p class="project__links">
      <span class="project__links-muted">Private repository</span>
    </p>
  </article>

</div>
