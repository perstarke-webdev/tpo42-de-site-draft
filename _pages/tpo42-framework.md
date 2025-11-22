---
layout: page
title: "TPO42 Framework"
permalink: /tpo42-framework
excerpt: "TPO42 entstand aus der praktischen Notwendigkeit heraus, die Lücke zwischen Product Management und Software Architecture zu schließen."
header:
  overlay_image: /assets/images/header.webp
  overlay_filter: rgba(0, 0, 0, 0.5)
---

<div class="box box--primary" data-aos="fade-up">
        <p>TPO42 baut die Brücke zwischen Produktvision und Produktarchitektur.</p>
Während ein arc42 Dokument die Frage:
<span style="font-style: italic"> "Was sollen wir über unsere Architektur kommunizieren/dokumentieren?" </span> und ein req42 Dokument die Frage:
<span style="font-style: italic">Warum sollen wir uns über unser Produkt Gedanken machen </span> getrennt beantwortet,
verbindet TPO42 die Fragen und benutzt das <span style="font-style: italic">"Wie sollen wir kommunizieren/dokumentieren?"</span> weiter.
</div>


<div class="notice--primary" data-aos="fade-down">
  <p><strong>Für wen ist TPO42?</strong> Für Technical Product Owner, die eine pragmatische Lösung für die Dokumentation von Anforderungen und Architektur suchen.</p>
  <p><strong>Basiert auf Standards:</strong> TPO42 verbindet die bewährten Methoden von req42 und arc42.</p>
  <p><strong>Open Source:</strong> Das Framework ist Open Source und wird offen entwickelt.</p>
</div>

<hr class="section-sep">

<section class="site-section">
  <div class="container" data-aos="fade-left">
    <div class="row">
      <div class="col-md-12">
        <h2>Lizenz & Referenzen</h2>
        <p>Das TPO42 Framework steht unter der <strong>Creative Commons Attribution-ShareAlike 4.0 International License</strong> und verwendet die bewährten Frameworks:</p>
        <ul>
          <li><a href="https://req42.de/" target='_blank' rel='noopener noreferrer nofollow'>req42</a> - Requirements Engineering (Dr. Peter Hruschka, Markus Meuten)</li>
          <li><a href="https://arc42.org/" target='_blank' rel='noopener noreferrer nofollow'>arc42</a> - Architecture Documentation (Dr. Peter Hruschka, Dr. Gernot Starke)</li>
        </ul>
        <div class="notice--info">
          <p><strong>Creative Commons Lizenz:</strong> Sie dürfen das Material teilen, bearbeiten und kommerziell nutzen, solange Sie angemessene Urheber- und Rechteangaben machen und Ihre Beiträge unter derselben Lizenz verbreiten. 
Ihre eigenen Inhalte, die in TPO42-Templates eingebettet sind, können Sie nach Ihren eigenen Regeln verwenden und veröffentlichen.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<hr class="section-sep">


# Das Framework

## 1. Struktur

Die einfachen Templates von arc42 und req42 bleiben erhalten. Dieses Template unterstellt, dass man sich zuerst Gedanken um das **Warum** macht, weswegen arc42-Kapitel im Zweifel Inhalte aus req42-Kapiteln einschließen.

Als **Technical Product Owner** verbringt man weniger Zeit im Backlog - diese Aufgabe teilt man sich mit dem "hohen Projektmanagement", dass die gesamte Produkt-Vision verantwortet. Dafür ist der Brückenschlag zur Architektur wichtiger.

Das bedeutet, die Kapitel:

- Scope-Abgrenzung
- Qualitätsanforderungen
- Modelle zur Unterstützung

werden wichtiger, Kapitel wie

- Stakeholder
- Randbedingungen
- Produkt-Backlog

erhalten zu dem blauen noch einen roten Aspekt*

<small>
*Vergleiche <a href="https://req42.de/req42-im-ueberblick#ergebnisorientiert&#8212;&#8203;nicht-prozessorientiert">req42 im Überblick &gt; Ergebnisorientiert – nicht prozessorientiert</a>
</small>

## 2. Redundanzen im Überblick

<a href="/assets/images/req42-arc42-redundancy.png" data-lightbox="image-1">
  <img src="/assets/images/req42-arc42-redundancy.png" alt="req42 arc42 redundancy">
</a>

