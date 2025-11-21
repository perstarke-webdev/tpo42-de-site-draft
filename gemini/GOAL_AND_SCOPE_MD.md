# GOAL\_AND\_SCOPE

## **1\. Purpose of this System**

This system enables Gemini to generate a complete Starter Homepage website inside an existing OneFlow-based Jekyll project with minimal manual intervention.  
 Depending on the client input, the final result may be a onepager or a small multi-page site.

The goal is to reduce manual production time for a first draft from roughly 6 hours to about 1 hour while maintaining full PSWD quality, clarity, and brand alignment.

Gemini must:

* read the entire project folder

* understand and reuse the existing OneFlow design system

* generate a complete homepage (single or multi-page)

* update only allowed files

* select and modify the correct theme skin

* clean up placeholder elements

* deliver a near-final website draft in a single run

The output must be consistent, high-quality, and ready for expert review.

---

## **2\. What a Starter Homepage Is**

A Starter Homepage is PSWD’s streamlined website option for founders and small businesses seeking a clean, trustworthy, conversion-ready web presence without the cost or depth of a fully custom project.

It prioritizes:

* clarity

* trust

* structure

* speed

* professional simplicity

A Starter Homepage helps clients:

* articulate their offer

* present themselves credibly

* build trust

* create early business momentum

Based on client content, it may be:

* a onepager

* a multi-page site (e.g., About, Services, Contact, Imprint)

Even within this simplified format, the visual and structural quality must be high. The page should feel rich, warm, and personal.

---

## **3\. What PSWD Is**

Per Starke Web Development (PSWD) is a partner-focused web practice built on:

* clarity and precision

* a calm creative process

* trust and transparency

* momentum-driven outcomes

* high-quality execution

PSWD builds websites that help clients move forward — not just websites that “exist.”

---

## **4\. PSWD Way of Thinking**

Gemini must internalize and reflect PSWD principles:

### **4.1 Momentum**

Every section should help move the visitor toward understanding, trust, and action.

### **4.2 Clarity**

Remove noise. Reduce friction. Make the message obvious and digestible.

### **4.3 Trust**

Use strong CTAs, testimonials, clear visuals, and good structure to build credibility.

### **4.4 Calm**

Tone must be grounded, supportive, confident. No hype or filler.

### **4.5 Precision**

Prefer the simplest and cleanest implementation. Minimal changes. Clean code.

### **4.6 Partnership**

Adapt to the client’s voice and needs. Never use a meaningless template.

### **4.7 Visual Warmth & Richness**

Even simple sites must feel alive and human. Use imagery, color, rhythm, spacing, and subtle animation to create warmth, energy, and personality.

---

## **5\. Scope of the System**

### **5.1 Files Gemini Must Read**

Gemini must read:

* the entire Jekyll project

* GOAL\_AND\_SCOPE.md

* PROCESS\_AND\_ACTIONS.md

* THEME\_REFERENCE.md

* EXAMPLE\_OUTPUT.md

* CLIENT\_DATA.md

### **5.2 Files Gemini Is Allowed to Edit**

#### **Onepager:**

* Index.html

* \_includes/\*.html (testimonials, CTAs, page hero, FAQ, custom components)

* \_config.yml

* assets/css/custom-styles.css

* the selected skin file only

* 404.html

#### **Multi-page:**

In addition to the above, Gemini may create/edit /pages/\*:

* about.html

* services.html

* contact.html

* imprint.md (combined imprint \+ privacy)

* any other pages logically derived from client content

### **5.3 Additional Allowed Actions**

Gemini may:

* delete placeholder images

* select the correct skin

* update \_config.yml

* modify only the chosen skin

* create minimal, meaningful CSS classes when needed

* create simple custom components (testimonial slider, FAQ accordion, image galleries)

These components must be stable, theme-aligned, and minimal.

---

## **6\. Files Gemini Must NOT Edit**

* layout files in \_layouts/

* any core theme SCSS except the selected skin

* JavaScript theme files

* build configuration files

* system files

---

## **7\. Non-Negotiable Standards**

### **7.1 Structural Standards**

* Sections/pages must be meaningful and derived from client content.

* CTAs only where appropriate, not everywhere.

* Never alter OneFlow layout mechanics.

* Maintain clean, predictable structure.

### **7.2 Copywriting Standards**

* Clear, calm, supportive tone.

* No hype or exaggerated claims.

* Rich but concise paragraphs.

* No AI filler.

* Very limited use of dashes.

* Use client wording whenever helpful.

### **7.3 Code Standards**

* Prefer existing theme classes.

* Minimal diffs.

* Clean, valid HTML.

* No unused or leftover styles.

* Consistent indentation.

### **7.4 Theme Standards**

* Use OneFlow as intended.

* Use the selected skin only.

* No overriding layout structure.

* Modify skin via SCSS variables, never via hacks.

### **7.5 Brand Color Standards**

* Use **only** the brand colors provided in CLIENT\_DATA.md, plus black/white.

* Colors must appear across the layout (CTAs, icons, backgrounds, notices).

* No additional strong colors allowed.

* Navigation links must use brand colors in both normal and hover states.

### **7.6 Image Standards**

* Final site must contain **at least 3 image placements** (round images, gallery strips, decorative uses of header.webp).

* Use header.webp creatively.

* Imagery must support warmth, trust, and structure.

### **7.7 Hero Standards**

* Must always use header.webp.

* Overlay opacity: 0.4–0.7.

* Geminin may adjust hero to enhance clarity and warmth (accent CTA, highlighted text, subtle icon use).

* Hero must never feel flat or ignored.

---

## **8\. Expected Output Quality**

The final result must be:

* structurally correct

* visually rich

* color-balanced using the full brand palette

* warm, personal, trustworthy

* populated with real client content

* CTA-complete where meaningful

* styled entirely through the selected skin

* image-rich but coherent

* free of placeholder content

* \~80–90% launch-ready

It must never:

* break the theme

* distort layout

* introduce unnecessary complexity

* ignore client content

Gemini should always optimize for:

* clarity

* simplicity

* correctness

* minimal review surface

---

## **9\. Intent**

This system augments human development.  
 Gemini produces the heavy first draft.  
 PSWD applies expert review and final refinements.

The output must always reflect the PSWD Way of Thinking:  
 **clarity, trust, momentum, calm, partnership, precision, and visual warmth.**

