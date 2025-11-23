---
layout: page
title: "Getting Started mit tpo<span class='red'>42</span>"
permalink: /getting-started
excerpt: "Das tpo<span class='red'>42</span>-Template ist in einem frühen Work-In-Progress Stadium. Als allererste Zielgruppe peilen wir Hands-On Technical Product Owner an, die das <span class='primary-bold'>Documentation as Code</span> Paradigma genauso lieben wie wir. GitOps ist der Weg."
header:
  overlay_image: /assets/images/getting-started.webp
  overlay_filter: rgba(0, 0, 0, 0.5)
---

<section class="left" markdown="1">

<div data-aos="fade-left" markdown="1">

# Voraussetzungen

- Git
- Docker für docToolchain im Docker-Container
- <a href="https://pre-commit.com/" target="_blank" rel="noopener noreferrer nofollow">pre-commit</a> (dringend empfohlen)
- Text Editor mit AsciiDoc Support:
    - VS Code mit AsciiDoc Extension
    - AsciidocFX
    - Vim/Neovim mit entsprechenden Plugins
- Grundkenntnisse in req42 und arc42

<div class="notice--primary" markdown="1">

**Docker-first Approach:**  
Wir empfehlen ausschließlich die Verwendung von docToolchain im Docker-Container.  
Andere Installationsmethoden (lokale Java/Gradle-Installation) sind für erfahrene Nutzer gedacht, die wissen, was sie tun.

**docToolchain Wrapper:**  
Verwenden Sie das offizielle Wrapper-Skript aus dem docToolchain-Repository für die beste Erfahrung.

**pre-commit Integration:**  
Automatisierte Checks für Code- und Commit-Qualität sind essentiell für ein sauberes Documentation-as-Code-Setup.

</div>

</div>

<hr class="section-sep">

<div data-aos="fade-right" markdown="1">

## Quick Start

Detaillierte Anweisungen finden Sie in unserem  
<a href="https://github.com/TPO42/TPO42-templates/blob/main/README.adoc"
target="_blank" rel="noopener noreferrer nofollow">GitHub README</a>.

```
git clone https://github.com/TPO42/TPO42-templates.git
cd TPO42-templates
# Folgen Sie den Anweisungen im README.adoc
````

</div>

<div class="notice--success" data-aos="fade-down" markdown="1">

Für Technical Product Owner, die Documentation as Code lieben. 🎯

</div>

</section>