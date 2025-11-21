---
layout: page
title: "Getting Started mit TPO42"
permalink: /getting-started
header:
  overlay_image: /assets/images/header.webp
  overlay_filter: rgba(0, 0, 0, 0.5)
  excerpt: "Setup, Voraussetzungen und Installation des tpo42 Frameworks"
---

<section class="site-section first-section">
  <div class="container" data-aos="fade-up">
    <div class="row">
      <div class="col-md-12">
        <h1>Getting Started</h1>
        <p class="lead">Das tpo42-Template ist in einem frühen Work-In-Progress Stadium. Als allererste Zielgruppe peilen wir Hands-On Technical Product Owner an, die das <strong>Documentation as Code</strong> Paradigma genauso lieben, wie wir. GitOps ist der Weg.</p>
      </div>
    </div>
  </div>
</section>

<hr class="section-sep">

<section class="site-section">
  <div class="container" data-aos="fade-left">
    <div class="row">
      <div class="col-md-12">
        <h2>Voraussetzungen</h2>
        <ul>
          <li>Git</li>
          <li>Docker für docToolchain im Docker-Container</li>
          <li><a href="https://pre-commit.com/">pre-commit</a> (dringend empfohlen)</li>
          <li>Text Editor mit AsciiDoc Support:
            <ul>
              <li>VS Code mit AsciiDoc Extension</li>
              <li>AsciidocFX</li>
              <li>Vim/Neovim mit entsprechenden Plugins</li>
            </ul>
          </li>
          <li>Grundkenntnisse in req42 und arc42</li>
        </ul>
        <div class="notice--primary">
          <p><strong>Docker-first Approach:</strong> Wir empfehlen ausschließlich die Verwendung von docToolchain im Docker-Container. Andere Installationsmethoden (lokale Java/Gradle-Installation) sind für erfahrene Nutzer gedacht, die wissen, was sie tun.</p>
        </div>
        <div class="notice--info">
          <p><strong>docToolchain Wrapper:</strong> Verwenden Sie das offizielle Wrapper-Skript aus dem docToolchain-Repository für die beste Erfahrung.</p>
        </div>
        <div class="notice--success">
          <p><strong>pre-commit Integration:</strong> Automatisierte Checks für Code- und Commit-Qualität sind essentiell für ein sauberes Documentation-as-Code-Setup.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<hr class="section-sep">

<section class="site-section">
  <div class="container" data-aos="fade-right">
    <div class="row">
      <div class="col-md-12">
        <h2>Quick Start</h2>
        <p>Detaillierte Anweisungen finden Sie in unserem <a href="https://github.com/tpo42/tpo42-templates/blob/main/README.adoc">GitHub README</a>.</p>
        <pre><code>git clone https://github.com/tpo42/tpo42-templates.git
cd tpo42-templates
# Folgen Sie den Anweisungen im README.adoc</code></pre>
      </div>
    </div>
  </div>
</section>
