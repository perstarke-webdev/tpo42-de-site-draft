---
layout: page
title: "Ressourcen"
permalink: /resources
excerpt: "Beispiele, Dokumentation und weitere Links"
header:
  overlay_image: /assets/images/resources.webp
  overlay_filter: rgba(0, 0, 0, 0.5)
  actions:
      - label: "Zu den Docs"
        url: "https://www.docs.tpo42.de"
        blank: true
      - label: "Blog lesen"
        url: "https://www.blog.tpo42.de"
        blank: true
gallery:
  - url: /assets/images/canvas.webp
    image_path: /assets/images/canvas.webp
    alt: "placeholder image 1"
  - url: /assets/images/canvas.webp
    image_path: /assets/images/canvas.webp
    alt: "placeholder image 2"
  - url: /assets/images/canvas.webp
    image_path: /assets/images/canvas.webp
    alt: "placeholder image 3"
---

<section class="site-section first-section">
  <div class="container" data-aos="fade-up">
    <h2>Beispiele</h2>
    {% include gallery %}
  </div>
</section>

<hr class="section-sep">

<section class="site-section">
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <div class="box-container">
          <div class="box box--info box-half" data-aos="zoom-in">
            <h3>Dokumentation</h3>
            <p>Ausführliche Dokumentation des TPO42 Frameworks.</p>
            <a href="#" class="btn btn--info" target="_blank" rel="noopener noreferrer nofollow">Lesen</a>
          </div>
          <div class="box box--success box-half" data-aos="zoom-in">
            <h3>Blog</h3>
            <p>Aktuelle Artikel und Neuigkeiten rund um TPO42.</p>
            <a href="#" class="btn btn--success" target="_blank" rel="noopener noreferrer nofollow">Besuchen</a>
          </div>
          <div class="box box--warning box-half" data-aos="zoom-in">
            <h3>GitHub</h3>
            <p>Der Quellcode und die Templates des TPO42 Frameworks.</p>
            <a href="https://github.com/TPO42/TPO42-templates" target="_blank" rel="noopener noreferrer nofollow" class="btn btn--warning">Ansehen</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>