---
layout: page
title: "Getting Started mit tpo<span class='red'>42</span>"
permalink: /getting-started
excerpt: "Das tpo<span class='red'>42</span>-Template ist in einem frühen Work-In-Progress Stadium. Als allererste Zielgruppe peilen wir Hands-On Technical Product Owner an, die das <span class='primary-bold'>Documentation as Code</span> Paradigma genauso lieben wie wir. GitOps ist der Weg."
header:
  overlay_image: /assets/images/getting-started.webp
  overlay_filter: rgba(0, 0, 0, 0.5)
---

<section class="left" Markdown="1">

  <div data-aos="fade-left">
        <h1>Voraussetzungen</h1>
        <ul>
          <li>Git</li>
          <li>Docker für docToolchain im Docker-Container</li>
          <li><a href="https://pre-commit.com/" target="_blank" rel="noopener noreferrer nofollow">pre-commit</a> (dringend empfohlen)</li>
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
          <p><strong>docToolchain Wrapper:</strong> Verwenden Sie das offizielle Wrapper-Skript aus dem docToolchain-Repository für die beste Erfahrung.</p>
          <p><strong>pre-commit Integration:</strong> Automatisierte Checks für Code- und Commit-Qualität sind essentiell für ein sauberes Documentation-as-Code-Setup.</p>
        </div>
      </div>

<hr class="section-sep">

  <div data-aos="fade-right">
        <h2>Quick Start</h2>
        <p>Detaillierte Anweisungen finden Sie in unserem <a target="_blank" rel="noopener noreferrer nofollow" href="https://github.com/TPO42/TPO42-templates/blob/main/README.adoc">GitHub README</a>.</p>
        <pre><code>git clone https://github.com/TPO42/TPO42-templates.git
cd TPO42-templates
# Folgen Sie den Anweisungen im README.adoc</code></pre>
      </div>

<div class="notice--success" data-aos="fade-down">
<p>Für Technical Product Owner, die Documentation as Code lieben. 🎯</p>
</div>


</section>