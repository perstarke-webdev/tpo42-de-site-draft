# PROCESS\_AND\_ACTIONS

Gemini operates inside a fully cloned local Jekyll project that already contains the OneFlow theme.  
 A remote `origin` already exists, and authentication is configured.

Gemini must follow **every step in this file exactly**, using PSWD’s quality standards, OneFlow conventions, and stable, minimal, maintainable code patterns.

Gemini must also:

* read all instruction files before starting

* log all changes in `CHANGES_LOG.md`

* run git commands (but **never Jekyll build/serve commands**)

* produce a near-launch-ready website

---

# **1\. Instruction Files Gemini Must Read**

Before doing anything, Gemini must fully read:

* `gemini/GOAL_AND_SCOPE.md`

* `gemini/THEME_REFERENCE.txt`

* `gemini/PROCESS_AND_ACTIONS.md` (this file)

* `gemini/CLIENT_DATA.md`

* `gemini/EXAMPLE_OUTPUT.txt`

Gemini must apply:

* PSWD Web Momentum principles

* OneFlow layout conventions

* Clear, warm, precise PSWD tone

* High visual standards

* Reliability and maintainability

---

# **2\. Git Preparation**

## **2.1 `.gitignore`**

`_site/`

`node_modules/`

## **2.2 Commit Base Theme**

`git add .`

`git commit -m "Initial theme commit"`

`git push`

## **2.3 Create Working Branch**

`git checkout -b first-draft`

All work happens on `first-draft`.

---

# **3\. Pre-Processing Phase**

## **3.1 Determine Project Structure**

Gemini must NOT assume fixed sections.

From CLIENT\_DATA.md, determine whether the site should be:

* a **onepager**, or

* a **multi-page mini-site**

Gemini must derive the actual section/page list dynamically, based on meaningful content.

Examples (not mandatory):

* Hero

* About

* Services

* Offers

* Approach / Process

* Testimonials

* Pricing

* Transformation / Benefits

* Contact

* FAQ (only if content suggests it)

Only create sections/pages where meaningful content exists.

## **3.2 Extract Color Scheme**

Gemini must:

* use ONLY the brand colors from CLIENT\_DATA.md

* plus black/white

* use **all provided brand colors** in a balanced, non-monochrome way

Colors must appear across:

* primary CTAs

* secondary CTAs

* notices

* subtle backgrounds

* icon colors

* separators

* accent borders

* highlighted text

**No other strong colors are allowed.**

## **3.3 Select and Modify Skin File**

Gemini must:

* inspect available skins in `_sass/oneflow/skins/`

* choose the skin closest to the client’s aesthetic

* set chosen skin in `_config.yml`

* modify ONLY this skin file using SCSS variables

* ensure nav link colors and hover colors match brand palette

---

# **4\. Cleanup Phase**

## **4.1 Remove Placeholder Images**

Delete all images except:

* `logo.*` (if present)

* `Header.webp`

* `ugly-404`

## **4.2 Image Usage Requirements**

The final site must contain **at least 3 image placements**, ideally 3–5 or more:

Allowed visual components (all referencing `header.webp`):

* galleries

* round-images includes

* image-text-rows

* decorative or cropped variants

* icon lists

If meaningful, Gemini should vary placement types to avoid monotony. Result should be a personal, warm page that confidently uses styles and images well.

Various image options should be used.

## **4.3 Remove Demo Content**

All sample theme content must be removed.

---

# **5\. Global Config & Setup**

## **5.1 Update `_config.yml`**

Based on CLIENT\_DATA.md:

* title, subtitle

* site URL

* selected skin

* masthead opacity

* footer socials

* favicon references

* language

* imprint details

### **Critical Rule:**

If a logo is present → masthead title must be empty, no title \+ logo in the masthead, ONLY ONE.

## **5.2 Update README.md**

Use the PSWD template.

---

# **6\. Content & Page Structure**

## **6.1 Navigation**

* Onepager: scroll anchors

* Multi-page: `/pages/*.html`

* Use brand colors for nav links

* Hover must use **another accent color**, not default black

## **6.2 Multi-Page Creation**

Create only meaningful pages (derived from CLIENT\_DATA), e.g.:

* about.html

* services.html

* contact.html

* pricing.html

* imprint.md (combined imprint \+ privacy)

## **6.3 Section Creation**

Sections must:

* be derived from CLIENT\_DATA

* follow PSWD tone

* flow logically

* contain at least 1–2 warm, clear, rich paragraphs

---

# **7\. Skin & Visual Design**

Gemini must:

* use the **entire brand color palette** across the page

* avoid cold monochrome layouts

* alternate backgrounds meaningfully

* use notices with multiple brand colors (not only primary)

* ensure footer social icons KEEP the theme’s hover effect and correctly has different hover color than normal color

* use icons where meaningful

* add subtle drop shadows

* create rich visual rhythm

### **Boxes**

Boxes must receive a custom class providing:

`padding-left: 1em;`

`padding-right: 1em;`

---

# **8\. Hero Section**

Hero must always use:

`/assets/images/header.webp`

Hero must include:

* strong headline

* warm supporting subheadline

* **clear CTA**

* optional secondary CTA

* optional subtle decorative elements (icons, accent underline)

### **Overlay Rule**

Overlay must be between **0.4 and 0.7** opacity, depending on style and color scheme and if more bright/dark look is wanted.

### **Hero Variation Allowed**

Gemini may and often should slightly adjust hero (using include-file and front-matter), in order to achieve visual interestingness and warmth, by:

* adjusting overlay

* adding accent-colored CTA (might need custom css, or using existing button classes)

* highlighting words using accent color or gradients (needs custom css)

* using icons, e.g. in the CTA 

* adjusting button style

* Adjust spacing, if meaningful

---

# **9\. Section Content Implementation**

Gemini must:

* expand text meaningfully

* use warm, human, PSWD tone

* use full OneFlow components (boxes, notices, grids, columns, galleries, round images, icon lists, alternating sections)

* Create **all** required sections/pages that are derivable from client-data

* When using multi-pager, do not use alternating-color sections  
  * When using Onepager, decide based on required feel, content, colors, etc, if using alternating-color sections will match the desired design well (if in doubt, use them).   
    * When using them, the first section must always have the dedicated first section class (see example html).  
    * When using them, the last section must always be the regular, non-alternating color  
    * Use existing OneFlow classes   
    * Use hr section sep between each section  
    * Alternate colored sections and normal ones. Do not use 2 colored ones, then 1 normal one, or similar. If using them, always 1 colored, 1 normal, 1 colored, 1 normal, and so on.

### **CTAs**

Place meaningful CTAs:

* every \~1–2 sections

* when contextually helpful

### **Testimonials (if applicable)**

OneFlow has no slider.  
Gemini must create a **simple custom CSS slider** with:

* auto-slide

* **visible** dots or arrows

* clean, minimal design

* mobile-friendly

* accent color usage

### **FAQ**

Only if content suggests it (not mandatory). If yes, use clean FAQ-desgin, with arrows, opening on click, clean hover and open effects, standard clean FAQ look.

### **Other Social Proof**

Only if content suggests it (not mandatory).

If yes, style well, use meaningful icons, boxes, count-ups, or other custom styles, to make it build trust, look amazing, and not be boring and templated.

---

# **10\. AOS Animation Rules**

AOS must be installed and initialized.

Gemini must use subtle and diverse animations:

* fade-up

* fade-left

* fade-right

* zoom-in

* flip-up (rarely)

Never over-animate.

Every div / parent-element must have an appear-animation, so that either each element on its own, or through its parent element, is animated. 

E.g. in 

\<div\> \-\> needs own animation

\<p\>\</p\> \-\> via parent-div, needs no own animation

\</div\>

\<p\>\</p\> \-\> needs own animation

\<p\>\</p\> \-\> needs own animation

---

# **11\. Footer**

Footer must include:

* socials

* email

* copyright

* “Created by **PSWD**” (PSWD in **bold** and **clickable**)

### **Footer Hover Rule**

Skin overrides must NOT break the default footer hover color behavior for social item links, gemini must check that hover-color and normal color are not the same, so a clear visible hover stays for these items (already exists, must not be broken)

---

# **12\. Imprint \+ Privacy**

Starter Homepage has **one combined page**:

`pages/imprint.md`

Strict rules:

* **DO NOT** rewrite or shorten the content

* **Only** update client details. Replace all mentions of “Per” with the client name.

* Only remove GitHub Pages references, instead only mention CDN.

* CDN notice must stay or be updated to now make sense

* The same suitable update must be made to the popup include file, so that it does not mention GitHub pages, and only mentions CDN usage.

* All provided legal sections must remain intact and with full content

---

# **13\. 404 Page**

Gemini must:

* apply brand colors

* use ugly-404 image if meaningful

* add a short PSWD-style line (template can be used as is, mostly)

* keep clean and simple

* Email on here must stay [info@perstarke-webdev.de](mailto:info@perstarke-webdev.de), **not** the client email

---

# **14\. Contact Form**

If requested in client-data, create a placeholder form:

* Name

* Email

* Message

Style the contact form well, with suitable sizes, colors, paddings, clean looks, no default, but standard clean contact form design. Use color scheme provided, and match the look of the rest of the site.

Add note:

`This form is a placeholder and will be connected later.`

No JS. No Formspark.

---

# **15\. Responsiveness**

Gemini must ensure:

* all new CSS rules are mobile-friendly

* spacing matches OneFlow

* testimonial slider and FAQ collapse well on mobile

* images scale correctly

Gemini must re-read its own code to validate structure.

---

# **16\. Cleanup**

Remove:

* unused CSS

* unused includes

* empty sections

* placeholder links

* leftover demo components

---

# **17\. Final Self-Review Checklist**

Gemini must confirm:

* PSWD tone

* strong overall color usage

* correct nav colors \+ hover colors

* minimum 3 meaningful image placements

* multiple brand colors used across sections

* CTA density correct

* imprint/privacy untouched except details

* masthead title hidden when logo exists (as it generally is in the theme)

* testimonial slider meeting spec

* footer hover working

* meaningful text expansion

* balanced AOS animations

* no layout breaking

---

# **18\. Final Git Commit & Push**

`git add .`

`git commit -m "First draft"`

`git push --set-upstream origin first-draft`

---

# **19\. Desired Final Feeling & Quality Standard**

The resulting website must feel:

* visually rich

* warm, personal, trustworthy

* clear and structured

* professionally built

* balanced and calm

* animated subtly

* image-rich but coherent

* color-balanced using full brand palette

* \~80–90% launch-ready

It must resemble a site PSWD could confidently show to a client as a nearly finished draft, requiring only refinement and small adjustments.

