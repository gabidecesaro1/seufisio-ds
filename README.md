# seufisio Design System

## About
**seufisio** is a SaaS management platform built specifically for Pilates studios, physiotherapy clinics, and aesthetic spaces ("O seu sistema de gestão" — Your management system). It was created inside Artemidas, a health technology and innovation company.

**Slogan:** "Gestão descomplicada, vida simplificada"
**Brand idea:** "Gestão simplificada para estúdios de Pilates, clínicas de Fisioterapia e espaços de beleza"

### Source Materials
- Brand guide: `uploads/manual-da-marca-01.png` through `uploads/manual-da-marca-29.png`
- Logo files: `assets/` folder


### KNOWLEDGE BASE (AI CONTEXT)
This folder contains fundamental documents to guide content generation and AI interaction context, ensuring alignment with seufisio’s real-world data.
- depoimentos.md: Compiled real customer testimonials for social proof.
- faq.md: Official Frequently Asked Questions and answers.
- funcionalidades.md: Technical and commercial breakdown of all system features.
- personas.md: Detailed guide of ideal customer profiles (Mariana, Bruno, Carla).
- planos_e_precos.md: Updated pricing table and plan implementation guidelines.

---

## CONTENT FUNDAMENTALS

### Tone & Voice
- **Educational/Institutional content:** Educative, accessible, welcoming. Explains clearly, empathetically guides, offers good practices.
- **Sales/Ads content:** Persuasive, direct, focused on pain points, sense of urgency.

### Writing Style
- **Casing:** Title case for headings; sentence case for body.
- **Person:** Second person (você / seu / sua) — speaks directly to the manager/professional.
- **"seufisio"** is always written in lowercase, even at the start of a sentence.
- No emoji in brand communication.
- Bold used frequently for emphasis on key concepts.

### Example Phrases
- *"Descubra como organizar sua agenda pode transformar a experiência dos seus alunos."*
- *"Simplifique hoje para crescer de forma sólida amanhã."*
- *"Você ainda perde alunos por erro de agendamento? Está na hora de mudar."*

---

## VISUAL FOUNDATIONS

### Colors
| Token | Hex | Usage |
|-------|-----|-------|
| `--orange` | `#FD6003` | Primary action, CTA, headlines on dark |
| `--purple` | `#6C398D` | Institutional, secondary brand |
| `--navy` | `#2D3145` | Dark backgrounds, text on light |
| `--white` | `#FFFFFF` | Light backgrounds, text on dark |

### Typography
| Font | Role | Source |
|------|------|--------|
| **Days One** | Display/event titles, impactful headings | Google Fonts |
| **ASAP** | Primary communication font, body, UI | Google Fonts |

- Both fonts are available on Google Fonts.
- Days One: bold, geometric, strong personality — used for titles in events, frames, marketing.
- ASAP: clean, humanist sans-serif — used for all communications, UI, body text.

### Gradients
Multiple gradient types all mixing orange (#FD6003), purple (#6C398D), navy (#2D3145), and white:
- Orange → Purple (left to right or top to bottom) — hero backgrounds
- Navy → Orange (radial) — dark hero variant
- Light lavender/pink (subtle, used for light backgrounds in value cards, etc.)

### Backgrounds
- Full-bleed gradient backgrounds are common and on-brand.
- Flat color fills (solid orange, solid purple, solid navy) used for section slides.
- Light gradient (almost white with lavender tint) for content-heavy slides.
- Logo mark used as oversized "grafismo" watermark at low opacity.

### Cards & Containers
- Rounded corners: 8–16px range.
- Cards on light backgrounds: subtle border (purple-tinted), no heavy shadow.
- Dark cards: navy fill, white text.
- Pill/capsule shape used for labels and badges.

### Corner Radii
- Buttons: full pill (`border-radius: 100px`)
- Cards: `8px–16px`
- Badges/tags: `100px` pill

### Spacing
- Base unit: 8px
- Generous internal padding: 24–48px in cards, 40–80px in sections.

### Iconography
- No custom icon font. Brand uses minimal iconography.
- Circle outlines with brand colors used as visual containers.
- Logo mark (the ribbon/infinity shape) is the primary visual icon.
- When icons are needed, use Lucide Icons (line style, matching brand's clean aesthetic).

### Imagery & Animation
- No defined photography style in the brand guide.
- Gradients and the logo mark are the primary visual motifs.
- Animation: smooth, soft transitions preferred (ease-in-out).
- Hover states: slight opacity shift or subtle scale (1.02–1.05).

---

## ICONOGRAPHY
- Primary brand symbol: the ribbon/infinity mark (seufisio logo icon)
- Can be used as oversized decorative grafismo at low opacity (10–30%)
- Both filled (gradient) and outline versions permitted
- Icon system: Lucide Icons recommended for UI contexts
- No emoji; no unicode-as-icon patterns in the brand guide

---

## FILES INDEX

| File | Description |
|------|-------------|
| `README.md` | This file — brand overview and guidelines |
| `colors_and_type.css` | CSS custom properties for all tokens |
| `SKILL.md` | Agent skill entrypoint |
| `assets/` | Logo files (PNG) |
| `preview/` | Design system preview cards |
| `knowledge/` | Context files for AI grounding (Testimonials, FAQ, Features, etc.) |
| `ui_kit/index.html` | seufisio app UI kit — core screens |


---

Note for AI Agents: Always use the files inside the `/knowledge` folder as the primary source of truth for specialized content generation, customer support simulations, or sales copywriting. Do not deviate from the established tone and the mandatory lowercase "seufisio" branding.
