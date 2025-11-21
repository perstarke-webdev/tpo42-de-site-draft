# CLIENT\_DATA

Project: “TPO42”  
Type: Starter Homepage, multi-page.

# TPO42 DE Site Structure

### **1\. Home**

* enthält das ehemalige „Über tpo42“

* erklärt kurz Problem, Zielgruppe, Nutzen

* Brücke arc42/req42

* intro \+ 1–2 CTAs

### **2\. tpo42 Framework**

* technische Hauptseite

* Aufbau, Prinzipien, Struktur

* Verbindung zu arc42/req42

* Lizenz \+ Referenzen

* GitHub-Links

### **3\. Getting Started**

* Setup

* Voraussetzungen

* Installation

* Quick Start

* GitHub README Verweis

### **4\. Ressourcen (Sammelseite)**

* Examples/Gallery direkt sichtbar

* Link zu Docs

* Link zu Blog

* einfache, kompakte Darstellung

### **5\. Impressum/Datenschutz**

* Pflichtseite

* bleibt minimal

### Kontakt:

Nur im Footer.

### Design:

OneFlow Theme, an arc42 orientiert  
Stock Bilder als Heros.

**tpo42 | Jens Rehsack | Hourly Jekyll/GH Site**  
ToDo’s \- Master  
**Basic info:**

* Language  
  * DE  
* Exact services  
  * Hourly-billed help with setting up his github-based sites for tpo42 (en/de, docs, blogs) with main focus on content and editability for him

**Project Basics:**

* Short business description  
  * the road between arc42 and req42, „for beginners“  
* Goal of project  
  * show his framework, give people all the info they need, set it up similarly to arc42

**Partners:**

**Development Tool(s):**

Jeykll, GH, AsciiDoc  
**Milestones & Timeline:**

first de site, then show him as draft \+ then move to his repo  
then en site  
then blog and docs, also in both langauges  
**Financials:**

* Agreed one-time price for each service  
  * Hourly \- final rate to be discussed, say 70 but open to discuss if he needs cheaper  
* Agreed one-time upfront payment  
  * None  
* Discounts/special terms  
  * None  
* What is paid already one-time  
  * None  
* One-time costs  
  * None  
* Ongoing costs  
  * None  
* Ongoing income  
  * Hourly  
* Other financial notes  
  * None

**Branding (Colors, Fonts):**

see his old site \+ logo  
**Other to-keep Notes:**

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
**Current To-Dos:**

**Calls/Communication Notes:**

[tpo42.de](http://tpo42.de) is rudimentary live  
[https://github.com/tpo42](https://github.com/tpo42)   
Many infos in email thread  
Die leute erreichen die „nichts habern „von ahnung, arc und req zu „hoch“ (nicht preis, infos\!)  
daher pragmatisch rangehen, „was brauchen wir wirklich“,  
sukzessive an arc/req „anführen“ \+ darauf verweisen, wenn mögölich geht dorthin, aber halt für das da adrutner gemacht  
daher optisch auch ählnichh, same theme würc ich sagen  
mit style sheet sodass er es ausrollen kann mit weitern seiten etc, also clean setup mit css und dann asciidoc oder so   
damit auch sprache ergänzbar  
er hat wenig ahnung von aufbau, wie man es „ausrollt“  
com/de zum inhaltichen vorstellen  
downloads bereich dort  
docs und blog dann danach recht schnell in betrieb nehmen  
erst de  
dann en  
dann blog  
dann docs  
optik muss nicht „perfekt;“ sondern technisch für ihn easy zu machen  
Asscioodoc, außer schmuck-elemente, css will er dann nicht anfassen  
geschätzt 10-20h, zeit aufschrieben, @70€ (außer er braucth weniger, kulant, aber 70 confident vorschlagen)  
er hasst es wenn schrift nur in der mitte bleibt auch bei breitem fenster  
reader-mode mal testen  
impressum, ja\!  
erst eigenes repo als draft, dann zu ihm, (DE seite9), dann die nächsten step by step  
später domain umzug (kann er selbsst?? esc zu strato, macht er)  
dann freelancer site

The plan now is ONLY the german [tpo42.de](http://tpo42.de) site \- rest will follow later. Use notes for context.  
Dont use asciidoc, use normal html and md for now, as in examples and requirement files.

Below is the content from the past tpo42-site, use that as the base-information

| \<\!DOCTYPE html\> |
| :---- |
| \<html lang="de"\> |
| \<head\> |
| \<meta charset="utf-8"\> |
| \<meta http-equiv="X-UA-Compatible" content="IE=edge"\> |
| \<meta name="viewport" content="width=device-width, initial-scale=1"\> |
|  |
| \<title\>tpo42 Framework \- TPO42 Framework\</title\> |
| \<meta name="description" content="Technical Product Owner Framework combining req42 and arc42"\> |
|  |
| \<link rel="stylesheet" href="[/assets/css/main.css](https://www.tpo42.de/assets/css/main.css)"\> |
| \<link rel="canonical" href="[https://www.tpo42.de/](https://www.tpo42.de/)"\> |
|  |
| \<link type="application/atom+xml" rel="alternate" href="[https://www.tpo42.de/feed.xml](https://www.tpo42.de/feed.xml)" title="TPO42 Framework" /\> |
| \<\!-- Begin Jekyll SEO tag v2.8.0 \--\> |
| \<title\>tpo42 Framework | TPO42 Framework\</title\> |
| \<meta name="generator" content="Jekyll v4.4.1" /\> |
| \<meta property="og:title" content="tpo42 Framework" /\> |
| \<meta property="og:locale" content="de\_DE" /\> |
| \<meta name="description" content="Technical Product Owner Framework combining req42 and arc42" /\> |
| \<meta property="og:description" content="Technical Product Owner Framework combining req42 and arc42" /\> |
| \<link rel="canonical" href="[https://www.tpo42.de/](https://www.tpo42.de/)" /\> |
| \<meta property="og:url" content="https://www.tpo42.de/" /\> |
| \<meta property="og:site\_name" content="TPO42 Framework" /\> |
| \<meta property="og:type" content="website" /\> |
| \<meta name="twitter:card" content="summary" /\> |
| \<meta property="twitter:title" content="tpo42 Framework" /\> |
| \<script type="application/ld+json"\> |
| {"@context":"https://schema.org","@type":"WebSite","description":"Technical Product Owner Framework combining req42 and arc42","headline":"tpo42 Framework","name":"TPO42 Framework","url":"https://www.tpo42.de/"}\</script\> |
| \<\!-- End Jekyll SEO tag \--\> |
|  |
| \</head\> |
| \<body\> |
| \<header class="site-header" role="banner"\> |
| \<div class="wrapper"\> |
| \<a class="site-title" rel="author" href="[/](https://www.tpo42.de/)"\> |
| \<img src="[/assets/images/logo.svg](https://www.tpo42.de/assets/images/logo.svg)" alt="tpo42 Logo" class="site-logo"\> |
| TPO42 Framework |
| \</a\> |
|  |
| \<nav class="site-nav"\> |
| \<input type="checkbox" id="nav-trigger" class="nav-trigger" /\> |
| \<label for="nav-trigger"\> |
| \<span class="menu-icon"\> |
| \<svg viewBox="0 0 18 15" width="18px" height="15px"\> |
| \<path d="M18,1.484c0,0.82-0.665,1.484-1.484,1.484H1.484C0.665,2.969,0,2.304,0,1.484l0,0C0,0.665,0.665,0,1.484,0 h15.032C17.335,0,18,0.665,18,1.484L18,1.484z M18,7.516C18,8.335,17.335,9,16.516,9H1.484C0.665,9,0,8.335,0,7.516l0,0 c0-0.82,0.665-1.484,1.484-1.484h15.032C17.335,6.031,18,6.696,18,7.516L18,7.516z M18,13.516C18,14.335,17.335,15,16.516,15H1.484 C0.665,15,0,14.335,0,13.516l0,0c0-0.82,0.665-1.483,1.484-1.483h15.032C17.335,12.031,18,12.695,18,13.516L18,13.516z"/\> |
| \</svg\> |
| \</span\> |
| \</label\> |
|  |
| \<div class="trigger"\> |
|  |
|  |
|  |
| \<a class="page-link" href="[/overview.html](https://www.tpo42.de/overview.html)"\>Über tpo42\</a\> |
|  |
|  |
|  |
|  |
| \<a class="page-link" href="[/getting-started.html](https://www.tpo42.de/getting-started.html)"\>Getting Started mit TPO42\</a\> |
|  |
|  |
| 	\<a class="page-link" href="[https://github.com/tpo42/tpo42-templates](https://github.com/tpo42/tpo42-templates)"\>\<img src="[/assets/images/github-mark.svg](https://www.tpo42.de/assets/images/github-mark.svg)" alt="GitHub" class="icon"\>GitHub\</a\> |
| \</div\> |
| \</nav\> |
| \</div\> |
| \</header\> |
|  |
|  |
| \<main class="page-content" aria-label="Content"\> |
| \<div class="wrapper"\> |
| \<div id="preamble"\> |
| \<div class="sectionbody"\> |
| \<div class="paragraph hero"\> |
| \<p\>Das \<strong\>tpo42 Framework\</strong\> verwendet die bewährten Templates \<a href="[https://req42.de/](https://req42.de/)"\>req42\</a\> und \<a href="[https://arc42.org/](https://arc42.org/)"\>arc42\</a\>, verbindet sie unter der Haube und erlaubt so einem Technical Product Owner die effiziente Pflege von Anforderungs- und technischer Dokumentation ohne Dopplungen. Solide, praktisch und pragmatisch. Open Source und Open Development.\</p\> |
| \</div\> |
| \<div class="openblock cta-buttons"\> |
| \<div class="content"\> |
| \<div class="paragraph"\> |
| \<p\>\<a href="[overview.html](https://www.tpo42.de/overview.html)" class="btn btn-primary"\>Framework entdecken\</a\> |
| \<a href="[https://github.com/tpo42/tpo42-templates](https://github.com/tpo42/tpo42-templates)" class="btn btn-secondary"\>GitHub Repository\</a\>\</p\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \<div class="sect1"\> |
| \<h2 id="was-ist-tpo42"\>\<a class="anchor" href="[\#was-ist-tpo42](https://www.tpo42.de/#was-ist-tpo42)"\>\</a\>\<a class="link" href="[\#was-ist-tpo42](https://www.tpo42.de/#was-ist-tpo42)"\>1. Was ist tpo42?\</a\>\</h2\> |
| \<div class="sectionbody"\> |
| \<div class="paragraph"\> |
| \<p\>Der \<strong\>Technical Product Owner\</strong\> steht vor einer einzigartigen Herausforderung:\</p\> |
| \</div\> |
| \<div class="ulist"\> |
| \<ul\> |
| \<li\> |
| \<p\>✅ \<strong\>Produktvision\</strong\> in konkrete Requirements übersetzen\</p\> |
| \</li\> |
| \<li\> |
| \<p\>✅ \<strong\>Technische Architektur\</strong\> mit Business-Zielen abstimmen\</p\> |
| \</li\> |
| \<li\> |
| \<p\>✅ \<strong\>Stakeholder\</strong\> aus verschiedenen Domänen koordinieren\</p\> |
| \</li\> |
| \<li\> |
| \<p\>✅ \<strong\>Dokumentation\</strong\> die beide Welten verbindet\</p\> |
| \</li\> |
| \</ul\> |
| \</div\> |
| \<div class="paragraph"\> |
| \<p\>Deshalb baut tpo42 die Brücke zwischen Produktvision und Produktarchitektur\</p\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \<div class="sect1"\> |
| \<h2 id="community-support"\>\<a class="anchor" href="[\#community-support](https://www.tpo42.de/#community-support)"\>\</a\>\<a class="link" href="[\#community-support](https://www.tpo42.de/#community-support)"\>2. Community \&amp; Support\</a\>\</h2\> |
| \<div class="sectionbody"\> |
| \<div class="ulist"\> |
| \<ul\> |
| \<li\> |
| \<p\>\<span class="image icon"\>\<img src="[assets/images/github-mark.svg](https://www.tpo42.de/assets/images/github-mark.svg)" alt="GitHub" width="16" height="16"\>\</span\> \<strong\>GitHub:\</strong\> \<a href="[https://github.com/tpo42/tpo42-templates](https://github.com/tpo42/tpo42-templates)"\>GitHub Repository\</a\>\</p\> |
| \</li\> |
| \<li\> |
| \<p\>\<span class="image icon"\>\<img src="[assets/images/email-icon.svg](https://www.tpo42.de/assets/images/email-icon.svg)" alt="Email" width="16" height="16"\>\</span\> \<strong\>Kontakt:\</strong\> \<a href="mailto:info@tpo42.de"\>info@tpo42.de\</a\>\</p\> |
| \</li\> |
| \</ul\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \<div class="sect1"\> |
| \<h2 id="lizenz-referenzen"\>\<a class="anchor" href="[\#lizenz-referenzen](https://www.tpo42.de/#lizenz-referenzen)"\>\</a\>\<a class="link" href="[\#lizenz-referenzen](https://www.tpo42.de/#lizenz-referenzen)"\>3. Lizenz \&amp; Referenzen\</a\>\</h2\> |
| \<div class="sectionbody"\> |
| \<div class="paragraph"\> |
| \<p\>Das tpo42 Framework steht unter der \<strong\>Creative Commons Attribution-ShareAlike 4.0 International License\</strong\> und verwendet die bewährten Frameworks:\</p\> |
| \</div\> |
| \<div class="ulist"\> |
| \<ul\> |
| \<li\> |
| \<p\>\<a href="[https://req42.de/](https://req42.de/)"\>req42\</a\> \- Requirements Engineering (Dr. Peter Hruschka, Markus Meuten)\</p\> |
| \</li\> |
| \<li\> |
| \<p\>\<a href="[https://arc42.org/](https://arc42.org/)"\>arc42\</a\> \- Architecture Documentation (Dr. Peter Hruschka, Dr. Gernot Starke)\</p\> |
| \</li\> |
| \</ul\> |
| \</div\> |
| \<div class="sidebarblock license-note"\> |
| \<div class="content"\> |
| \<div class="paragraph"\> |
| \<p\>\<strong\>Creative Commons Lizenz:\</strong\> Sie dürfen das Material teilen, bearbeiten und kommerziell nutzen, solange Sie angemessene Urheber- und Rechteangaben machen und Ihre Beiträge unter derselben Lizenz verbreiten.\</p\> |
| \</div\> |
| \<div class="paragraph"\> |
| \<p\>Ihre eigenen Inhalte, die in tpo42-Templates eingebettet sind, können Sie nach Ihren eigenen Regeln verwenden und veröffentlichen.\</p\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \<hr\> |
| \<div class="paragraph"\> |
| \<p\>\<strong\>Von Technical Product Ownern, für Technical Product Owner.\</strong\> 🎯\</p\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \</main\> |
|  |
| \<footer class="site-footer h-card"\> |
| \<div class="wrapper"\> |
| \<div class="footer-col-wrapper"\> |
| \<div class="footer-col footer-col-1"\> |
| \<ul class="contact-list"\> |
| \<li class="p-name"\>\<img src="[/assets/images/logo.svg](https://www.tpo42.de/assets/images/logo.svg)" alt="tpo42 Logo" class="site-logo" width="32px" height="32px"\>TPO42 Framework\</li\> |
| \<li\> |
| \<a class="u-email" href="mailto:info@tpo42.de"\> |
| \<img src="[/assets/images/email-icon.svg](https://www.tpo42.de/assets/images/email-icon.svg)" alt="Email" class="icon"\>info@tpo42.de |
| \</a\> |
| \</li\> |
| \</ul\> |
| \</div\> |
|  |
| \<div class="footer-col footer-col-2"\> |
| \<ul class="social-media-list"\> |
| \<li\> |
| \<a href="[https://github.com/tpo42](https://github.com/tpo42)"\> |
| \<img src="[/assets/images/github-mark.svg](https://www.tpo42.de/assets/images/github-mark.svg)" alt="GitHub" class="icon"\> |
| \<span class="username"\>tpo42\</span\> |
| \</a\> |
| \</li\> |
| \<li\> |
| \<a href="[https://www.linkedin.com/in/jens-rehsack-14108926/](https://www.linkedin.com/in/jens-rehsack-14108926/)"\> |
| \<img src="[/assets/images/linkedin-icon.svg](https://www.tpo42.de/assets/images/linkedin-icon.svg)" alt="LinkedIn" class="icon"\> |
| \<span class="username"\>LinkedIn\</span\> |
| \</a\> |
| \</li\> |
| \</ul\> |
| \</div\> |
|  |
| \<div class="footer-col footer-col-3"\> |
| \<p\>Technical Product Owner Framework combining req42 and arc42\</p\> |
| \<p\>\<small\>Licensed under Creative Commons Attribution-ShareAlike 4.0\</small\>\</p\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \</footer\> |
|  |
| \</body\> |
| \</html\> |
|  |

| \<\!DOCTYPE html\> |
| :---- |
| \<html lang="de"\> |
| \<head\> |
| \<meta charset="utf-8"\> |
| \<meta http-equiv="X-UA-Compatible" content="IE=edge"\> |
| \<meta name="viewport" content="width=device-width, initial-scale=1"\> |
|  |
| \<title\>tpo42 Framework \- TPO42 Framework\</title\> |
| \<meta name="description" content="Technical Product Owner Framework combining req42 and arc42"\> |
|  |
| \<link rel="stylesheet" href="[/assets/css/main.css](https://www.tpo42.de/assets/css/main.css)"\> |
| \<link rel="canonical" href="[https://www.tpo42.de/](https://www.tpo42.de/)"\> |
|  |
| \<link type="application/atom+xml" rel="alternate" href="[https://www.tpo42.de/feed.xml](https://www.tpo42.de/feed.xml)" title="TPO42 Framework" /\> |
| \<\!-- Begin Jekyll SEO tag v2.8.0 \--\> |
| \<title\>tpo42 Framework | TPO42 Framework\</title\> |
| \<meta name="generator" content="Jekyll v4.4.1" /\> |
| \<meta property="og:title" content="tpo42 Framework" /\> |
| \<meta property="og:locale" content="de\_DE" /\> |
| \<meta name="description" content="Technical Product Owner Framework combining req42 and arc42" /\> |
| \<meta property="og:description" content="Technical Product Owner Framework combining req42 and arc42" /\> |
| \<link rel="canonical" href="[https://www.tpo42.de/](https://www.tpo42.de/)" /\> |
| \<meta property="og:url" content="https://www.tpo42.de/" /\> |
| \<meta property="og:site\_name" content="TPO42 Framework" /\> |
| \<meta property="og:type" content="website" /\> |
| \<meta name="twitter:card" content="summary" /\> |
| \<meta property="twitter:title" content="tpo42 Framework" /\> |
| \<script type="application/ld+json"\> |
| {"@context":"https://schema.org","@type":"WebSite","description":"Technical Product Owner Framework combining req42 and arc42","headline":"tpo42 Framework","name":"TPO42 Framework","url":"https://www.tpo42.de/"}\</script\> |
| \<\!-- End Jekyll SEO tag \--\> |
|  |
| \</head\> |
| \<body\> |
| \<header class="site-header" role="banner"\> |
| \<div class="wrapper"\> |
| \<a class="site-title" rel="author" href="[/](https://www.tpo42.de/)"\> |
| \<img src="[/assets/images/logo.svg](https://www.tpo42.de/assets/images/logo.svg)" alt="tpo42 Logo" class="site-logo"\> |
| TPO42 Framework |
| \</a\> |
|  |
| \<nav class="site-nav"\> |
| \<input type="checkbox" id="nav-trigger" class="nav-trigger" /\> |
| \<label for="nav-trigger"\> |
| \<span class="menu-icon"\> |
| \<svg viewBox="0 0 18 15" width="18px" height="15px"\> |
| \<path d="M18,1.484c0,0.82-0.665,1.484-1.484,1.484H1.484C0.665,2.969,0,2.304,0,1.484l0,0C0,0.665,0.665,0,1.484,0 h15.032C17.335,0,18,0.665,18,1.484L18,1.484z M18,7.516C18,8.335,17.335,9,16.516,9H1.484C0.665,9,0,8.335,0,7.516l0,0 c0-0.82,0.665-1.484,1.484-1.484h15.032C17.335,6.031,18,6.696,18,7.516L18,7.516z M18,13.516C18,14.335,17.335,15,16.516,15H1.484 C0.665,15,0,14.335,0,13.516l0,0c0-0.82,0.665-1.483,1.484-1.483h15.032C17.335,12.031,18,12.695,18,13.516L18,13.516z"/\> |
| \</svg\> |
| \</span\> |
| \</label\> |
|  |
| \<div class="trigger"\> |
|  |
|  |
|  |
| \<a class="page-link" href="[/overview.html](https://www.tpo42.de/overview.html)"\>Über tpo42\</a\> |
|  |
|  |
|  |
|  |
| \<a class="page-link" href="[/getting-started.html](https://www.tpo42.de/getting-started.html)"\>Getting Started mit TPO42\</a\> |
|  |
|  |
| 	\<a class="page-link" href="[https://github.com/tpo42/tpo42-templates](https://github.com/tpo42/tpo42-templates)"\>\<img src="[/assets/images/github-mark.svg](https://www.tpo42.de/assets/images/github-mark.svg)" alt="GitHub" class="icon"\>GitHub\</a\> |
| \</div\> |
| \</nav\> |
| \</div\> |
| \</header\> |
|  |
|  |
| \<main class="page-content" aria-label="Content"\> |
| \<div class="wrapper"\> |
| \<div id="preamble"\> |
| \<div class="sectionbody"\> |
| \<div class="paragraph hero"\> |
| \<p\>Das \<strong\>tpo42 Framework\</strong\> verwendet die bewährten Templates \<a href="[https://req42.de/](https://req42.de/)"\>req42\</a\> und \<a href="[https://arc42.org/](https://arc42.org/)"\>arc42\</a\>, verbindet sie unter der Haube und erlaubt so einem Technical Product Owner die effiziente Pflege von Anforderungs- und technischer Dokumentation ohne Dopplungen. Solide, praktisch und pragmatisch. Open Source und Open Development.\</p\> |
| \</div\> |
| \<div class="openblock cta-buttons"\> |
| \<div class="content"\> |
| \<div class="paragraph"\> |
| \<p\>\<a href="[overview.html](https://www.tpo42.de/overview.html)" class="btn btn-primary"\>Framework entdecken\</a\> |
| \<a href="[https://github.com/tpo42/tpo42-templates](https://github.com/tpo42/tpo42-templates)" class="btn btn-secondary"\>GitHub Repository\</a\>\</p\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \<div class="sect1"\> |
| \<h2 id="was-ist-tpo42"\>\<a class="anchor" href="[\#was-ist-tpo42](https://www.tpo42.de/#was-ist-tpo42)"\>\</a\>\<a class="link" href="[\#was-ist-tpo42](https://www.tpo42.de/#was-ist-tpo42)"\>1. Was ist tpo42?\</a\>\</h2\> |
| \<div class="sectionbody"\> |
| \<div class="paragraph"\> |
| \<p\>Der \<strong\>Technical Product Owner\</strong\> steht vor einer einzigartigen Herausforderung:\</p\> |
| \</div\> |
| \<div class="ulist"\> |
| \<ul\> |
| \<li\> |
| \<p\>✅ \<strong\>Produktvision\</strong\> in konkrete Requirements übersetzen\</p\> |
| \</li\> |
| \<li\> |
| \<p\>✅ \<strong\>Technische Architektur\</strong\> mit Business-Zielen abstimmen\</p\> |
| \</li\> |
| \<li\> |
| \<p\>✅ \<strong\>Stakeholder\</strong\> aus verschiedenen Domänen koordinieren\</p\> |
| \</li\> |
| \<li\> |
| \<p\>✅ \<strong\>Dokumentation\</strong\> die beide Welten verbindet\</p\> |
| \</li\> |
| \</ul\> |
| \</div\> |
| \<div class="paragraph"\> |
| \<p\>Deshalb baut tpo42 die Brücke zwischen Produktvision und Produktarchitektur\</p\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \<div class="sect1"\> |
| \<h2 id="community-support"\>\<a class="anchor" href="[\#community-support](https://www.tpo42.de/#community-support)"\>\</a\>\<a class="link" href="[\#community-support](https://www.tpo42.de/#community-support)"\>2. Community \&amp; Support\</a\>\</h2\> |
| \<div class="sectionbody"\> |
| \<div class="ulist"\> |
| \<ul\> |
| \<li\> |
| \<p\>\<span class="image icon"\>\<img src="[assets/images/github-mark.svg](https://www.tpo42.de/assets/images/github-mark.svg)" alt="GitHub" width="16" height="16"\>\</span\> \<strong\>GitHub:\</strong\> \<a href="[https://github.com/tpo42/tpo42-templates](https://github.com/tpo42/tpo42-templates)"\>GitHub Repository\</a\>\</p\> |
| \</li\> |
| \<li\> |
| \<p\>\<span class="image icon"\>\<img src="[assets/images/email-icon.svg](https://www.tpo42.de/assets/images/email-icon.svg)" alt="Email" width="16" height="16"\>\</span\> \<strong\>Kontakt:\</strong\> \<a href="mailto:info@tpo42.de"\>info@tpo42.de\</a\>\</p\> |
| \</li\> |
| \</ul\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \<div class="sect1"\> |
| \<h2 id="lizenz-referenzen"\>\<a class="anchor" href="[\#lizenz-referenzen](https://www.tpo42.de/#lizenz-referenzen)"\>\</a\>\<a class="link" href="[\#lizenz-referenzen](https://www.tpo42.de/#lizenz-referenzen)"\>3. Lizenz \&amp; Referenzen\</a\>\</h2\> |
| \<div class="sectionbody"\> |
| \<div class="paragraph"\> |
| \<p\>Das tpo42 Framework steht unter der \<strong\>Creative Commons Attribution-ShareAlike 4.0 International License\</strong\> und verwendet die bewährten Frameworks:\</p\> |
| \</div\> |
| \<div class="ulist"\> |
| \<ul\> |
| \<li\> |
| \<p\>\<a href="[https://req42.de/](https://req42.de/)"\>req42\</a\> \- Requirements Engineering (Dr. Peter Hruschka, Markus Meuten)\</p\> |
| \</li\> |
| \<li\> |
| \<p\>\<a href="[https://arc42.org/](https://arc42.org/)"\>arc42\</a\> \- Architecture Documentation (Dr. Peter Hruschka, Dr. Gernot Starke)\</p\> |
| \</li\> |
| \</ul\> |
| \</div\> |
| \<div class="sidebarblock license-note"\> |
| \<div class="content"\> |
| \<div class="paragraph"\> |
| \<p\>\<strong\>Creative Commons Lizenz:\</strong\> Sie dürfen das Material teilen, bearbeiten und kommerziell nutzen, solange Sie angemessene Urheber- und Rechteangaben machen und Ihre Beiträge unter derselben Lizenz verbreiten.\</p\> |
| \</div\> |
| \<div class="paragraph"\> |
| \<p\>Ihre eigenen Inhalte, die in tpo42-Templates eingebettet sind, können Sie nach Ihren eigenen Regeln verwenden und veröffentlichen.\</p\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \<hr\> |
| \<div class="paragraph"\> |
| \<p\>\<strong\>Von Technical Product Ownern, für Technical Product Owner.\</strong\> 🎯\</p\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \</main\> |
|  |
| \<footer class="site-footer h-card"\> |
| \<div class="wrapper"\> |
| \<div class="footer-col-wrapper"\> |
| \<div class="footer-col footer-col-1"\> |
| \<ul class="contact-list"\> |
| \<li class="p-name"\>\<img src="[/assets/images/logo.svg](https://www.tpo42.de/assets/images/logo.svg)" alt="tpo42 Logo" class="site-logo" width="32px" height="32px"\>TPO42 Framework\</li\> |
| \<li\> |
| \<a class="u-email" href="mailto:info@tpo42.de"\> |
| \<img src="[/assets/images/email-icon.svg](https://www.tpo42.de/assets/images/email-icon.svg)" alt="Email" class="icon"\>info@tpo42.de |
| \</a\> |
| \</li\> |
| \</ul\> |
| \</div\> |
|  |
| \<div class="footer-col footer-col-2"\> |
| \<ul class="social-media-list"\> |
| \<li\> |
| \<a href="[https://github.com/tpo42](https://github.com/tpo42)"\> |
| \<img src="[/assets/images/github-mark.svg](https://www.tpo42.de/assets/images/github-mark.svg)" alt="GitHub" class="icon"\> |
| \<span class="username"\>tpo42\</span\> |
| \</a\> |
| \</li\> |
| \<li\> |
| \<a href="[https://www.linkedin.com/in/jens-rehsack-14108926/](https://www.linkedin.com/in/jens-rehsack-14108926/)"\> |
| \<img src="[/assets/images/linkedin-icon.svg](https://www.tpo42.de/assets/images/linkedin-icon.svg)" alt="LinkedIn" class="icon"\> |
| \<span class="username"\>LinkedIn\</span\> |
| \</a\> |
| \</li\> |
| \</ul\> |
| \</div\> |
|  |
| \<div class="footer-col footer-col-3"\> |
| \<p\>Technical Product Owner Framework combining req42 and arc42\</p\> |
| \<p\>\<small\>Licensed under Creative Commons Attribution-ShareAlike 4.0\</small\>\</p\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \</footer\> |
|  |
| \</body\> |
| \</html\> |
|  |

| \<\!DOCTYPE html\> |
| :---- |
| \<html lang="de"\> |
| \<head\> |
| \<meta charset="utf-8"\> |
| \<meta http-equiv="X-UA-Compatible" content="IE=edge"\> |
| \<meta name="viewport" content="width=device-width, initial-scale=1"\> |
|  |
| \<title\>Getting Started mit TPO42 \- TPO42 Framework\</title\> |
| \<meta name="description" content="Technical Product Owner Framework combining req42 and arc42"\> |
|  |
| \<link rel="stylesheet" href="[/assets/css/main.css](https://www.tpo42.de/assets/css/main.css)"\> |
| \<link rel="canonical" href="[https://www.tpo42.de/getting-started.html](https://www.tpo42.de/getting-started.html)"\> |
|  |
| \<link type="application/atom+xml" rel="alternate" href="[https://www.tpo42.de/feed.xml](https://www.tpo42.de/feed.xml)" title="TPO42 Framework" /\> |
| \<\!-- Begin Jekyll SEO tag v2.8.0 \--\> |
| \<title\>Getting Started mit TPO42 | TPO42 Framework\</title\> |
| \<meta name="generator" content="Jekyll v4.4.1" /\> |
| \<meta property="og:title" content="Getting Started mit TPO42" /\> |
| \<meta property="og:locale" content="de\_DE" /\> |
| \<meta name="description" content="Technical Product Owner Framework combining req42 and arc42" /\> |
| \<meta property="og:description" content="Technical Product Owner Framework combining req42 and arc42" /\> |
| \<link rel="canonical" href="[https://www.tpo42.de/getting-started.html](https://www.tpo42.de/getting-started.html)" /\> |
| \<meta property="og:url" content="https://www.tpo42.de/getting-started.html" /\> |
| \<meta property="og:site\_name" content="TPO42 Framework" /\> |
| \<meta property="og:type" content="website" /\> |
| \<meta name="twitter:card" content="summary" /\> |
| \<meta property="twitter:title" content="Getting Started mit TPO42" /\> |
| \<script type="application/ld+json"\> |
| {"@context":"https://schema.org","@type":"WebPage","description":"Technical Product Owner Framework combining req42 and arc42","headline":"Getting Started mit TPO42","url":"https://www.tpo42.de/getting-started.html"}\</script\> |
| \<\!-- End Jekyll SEO tag \--\> |
|  |
| \</head\> |
| \<body\> |
| \<header class="site-header" role="banner"\> |
| \<div class="wrapper"\> |
| \<a class="site-title" rel="author" href="[/](https://www.tpo42.de/)"\> |
| \<img src="[/assets/images/logo.svg](https://www.tpo42.de/assets/images/logo.svg)" alt="tpo42 Logo" class="site-logo"\> |
| TPO42 Framework |
| \</a\> |
|  |
| \<nav class="site-nav"\> |
| \<input type="checkbox" id="nav-trigger" class="nav-trigger" /\> |
| \<label for="nav-trigger"\> |
| \<span class="menu-icon"\> |
| \<svg viewBox="0 0 18 15" width="18px" height="15px"\> |
| \<path d="M18,1.484c0,0.82-0.665,1.484-1.484,1.484H1.484C0.665,2.969,0,2.304,0,1.484l0,0C0,0.665,0.665,0,1.484,0 h15.032C17.335,0,18,0.665,18,1.484L18,1.484z M18,7.516C18,8.335,17.335,9,16.516,9H1.484C0.665,9,0,8.335,0,7.516l0,0 c0-0.82,0.665-1.484,1.484-1.484h15.032C17.335,6.031,18,6.696,18,7.516L18,7.516z M18,13.516C18,14.335,17.335,15,16.516,15H1.484 C0.665,15,0,14.335,0,13.516l0,0c0-0.82,0.665-1.483,1.484-1.483h15.032C17.335,12.031,18,12.695,18,13.516L18,13.516z"/\> |
| \</svg\> |
| \</span\> |
| \</label\> |
|  |
| \<div class="trigger"\> |
|  |
|  |
|  |
| \<a class="page-link" href="[/overview.html](https://www.tpo42.de/overview.html)"\>Über tpo42\</a\> |
|  |
|  |
|  |
|  |
| \<a class="page-link" href="[/getting-started.html](https://www.tpo42.de/getting-started.html)"\>Getting Started mit TPO42\</a\> |
|  |
|  |
| 	\<a class="page-link" href="[https://github.com/tpo42/tpo42-templates](https://github.com/tpo42/tpo42-templates)"\>\<img src="[/assets/images/github-mark.svg](https://www.tpo42.de/assets/images/github-mark.svg)" alt="GitHub" class="icon"\>GitHub\</a\> |
| \</div\> |
| \</nav\> |
| \</div\> |
| \</header\> |
|  |
|  |
| \<main class="page-content" aria-label="Content"\> |
| \<div class="wrapper"\> |
| \<div id="preamble"\> |
| \<div class="sectionbody"\> |
| \<div class="paragraph hero"\> |
| \<p\>Das tpo42-Template ist in einem frühen Work-In-Progress Stadium. Als allererste Zielgruppe peilen wir Hands-On Technical Product Owner an, die das \<strong\>Documentation as Code\</strong\> Paradigma genauso lieben, wie wir. GitOps ist der Weg.\</p\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \<div class="sect1"\> |
| \<h2 id="voraussetzungen"\>\<a class="anchor" href="[\#voraussetzungen](https://www.tpo42.de/getting-started.html#voraussetzungen)"\>\</a\>\<a class="link" href="[\#voraussetzungen](https://www.tpo42.de/getting-started.html#voraussetzungen)"\>1. Voraussetzungen\</a\>\</h2\> |
| \<div class="sectionbody"\> |
| \<div class="ulist"\> |
| \<ul\> |
| \<li\> |
| \<p\>Git\</p\> |
| \</li\> |
| \<li\> |
| \<p\>Docker für docToolchain im Docker-Container\</p\> |
| \</li\> |
| \<li\> |
| \<p\>\<a href="[https://pre-commit.com/](https://pre-commit.com/)"\>pre-commit\</a\> (dringend empfohlen)\</p\> |
| \</li\> |
| \<li\> |
| \<p\>Text Editor mit AsciiDoc Support:\</p\> |
| \<div class="ulist"\> |
| \<ul\> |
| \<li\> |
| \<p\>VS Code mit AsciiDoc Extension\</p\> |
| \</li\> |
| \<li\> |
| \<p\>AsciidocFX\</p\> |
| \</li\> |
| \<li\> |
| \<p\>Vim/Neovim mit entsprechenden Plugins\</p\> |
| \</li\> |
| \</ul\> |
| \</div\> |
| \</li\> |
| \<li\> |
| \<p\>Grundkenntnisse in req42 und arc42\</p\> |
| \</li\> |
| \</ul\> |
| \</div\> |
| \<div class="paragraph"\> |
| \<p\>\<strong\>Docker-first Approach:\</strong\> Wir empfehlen ausschließlich die Verwendung von docToolchain im Docker-Container. Andere Installationsmethoden (lokale Java/Gradle-Installation) sind für erfahrene Nutzer gedacht, die wissen, was sie tun.\</p\> |
| \</div\> |
| \<div class="paragraph"\> |
| \<p\>\<strong\>docToolchain Wrapper:\</strong\> Verwenden Sie das offizielle Wrapper-Skript aus dem docToolchain-Repository für die beste Erfahrung.\</p\> |
| \</div\> |
| \<div class="paragraph"\> |
| \<p\>\<strong\>pre-commit Integration:\</strong\> Automatisierte Checks für Code- und Commit-Qualität sind essentiell für ein sauberes Documentation-as-Code-Setup.\</p\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \<div class="sect1"\> |
| \<h2 id="quick-start"\>\<a class="anchor" href="[\#quick-start](https://www.tpo42.de/getting-started.html#quick-start)"\>\</a\>\<a class="link" href="[\#quick-start](https://www.tpo42.de/getting-started.html#quick-start)"\>2. Quick Start\</a\>\</h2\> |
| \<div class="sectionbody"\> |
| \<div class="paragraph"\> |
| \<p\>Detaillierte Anweisungen finden Sie in unserem \<a href="[https://github.com/tpo42/tpo42-templates/blob/main/README.adoc](https://github.com/tpo42/tpo42-templates/blob/main/README.adoc)"\>GitHub README\</a\>.\</p\> |
| \</div\> |
| \<div class="listingblock"\> |
| \<div class="content"\> |
| \<pre class="rouge highlight"\>\<code data-lang="bash"\>git clone https://github.com/tpo42/tpo42-templates.git |
| \<span class="nb"\>cd \</span\>tpo42-templates |
| \<span class="c"\>\# Folgen Sie den Anweisungen im README.adoc\</span\>\</code\>\</pre\> |
| \</div\> |
| \</div\> |
| \<hr\> |
| \<div class="paragraph"\> |
| \<p\>\<em\>Für Technical Product Owner, die Documentation as Code lieben.\</em\> 🎯\</p\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \</main\> |
|  |
| \<footer class="site-footer h-card"\> |
| \<div class="wrapper"\> |
| \<div class="footer-col-wrapper"\> |
| \<div class="footer-col footer-col-1"\> |
| \<ul class="contact-list"\> |
| \<li class="p-name"\>\<img src="[/assets/images/logo.svg](https://www.tpo42.de/assets/images/logo.svg)" alt="tpo42 Logo" class="site-logo" width="32px" height="32px"\>TPO42 Framework\</li\> |
| \<li\> |
| \<a class="u-email" href="mailto:info@tpo42.de"\> |
| \<img src="[/assets/images/email-icon.svg](https://www.tpo42.de/assets/images/email-icon.svg)" alt="Email" class="icon"\>info@tpo42.de |
| \</a\> |
| \</li\> |
| \</ul\> |
| \</div\> |
|  |
| \<div class="footer-col footer-col-2"\> |
| \<ul class="social-media-list"\> |
| \<li\> |
| \<a href="[https://github.com/tpo42](https://github.com/tpo42)"\> |
| \<img src="[/assets/images/github-mark.svg](https://www.tpo42.de/assets/images/github-mark.svg)" alt="GitHub" class="icon"\> |
| \<span class="username"\>tpo42\</span\> |
| \</a\> |
| \</li\> |
| \<li\> |
| \<a href="[https://www.linkedin.com/in/jens-rehsack-14108926/](https://www.linkedin.com/in/jens-rehsack-14108926/)"\> |
| \<img src="[/assets/images/linkedin-icon.svg](https://www.tpo42.de/assets/images/linkedin-icon.svg)" alt="LinkedIn" class="icon"\> |
| \<span class="username"\>LinkedIn\</span\> |
| \</a\> |
| \</li\> |
| \</ul\> |
| \</div\> |
|  |
| \<div class="footer-col footer-col-3"\> |
| \<p\>Technical Product Owner Framework combining req42 and arc42\</p\> |
| \<p\>\<small\>Licensed under Creative Commons Attribution-ShareAlike 4.0\</small\>\</p\> |
| \</div\> |
| \</div\> |
| \</div\> |
| \</footer\> |
|  |
| \</body\> |
| \</html\> |
|  |

