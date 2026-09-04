# Portfolio — Content Plan

Devraj Gothi · drafted 2026-09-03

Facts in `[brackets]` are unfilled — fill them, don't let them get invented.

---

## 1. Decisions locked

| | |
|---|---|
| **Positioning** | Design *and* build, same person. Hero carries that; sections carry the emphasis. |
| **Priority audience** | Both, clients first. |
| **Voice** | Plain and confident. Short declaratives. No adjectives doing heavy lifting. |
| **About treatment** | `O-006` — a sixth row in the work list. |
| **Primary action** | Email. No contact form. |

### Anti-goals

- No fabricated testimonials, client logos, metrics, or awards.
- No equal-thumbnail card grid.
- No services grid, process timeline, or skills bar chart.
- Mandala site and politician site stay out. Not even as filler.
- RAG/AI is not a second headline practice — it lives inside About.

---

## 2. Sections — four, plus a footer

```
1. Hero
2. Work      ← all 5 projects, as 5 rows in ONE section
3. About     ← O-006, a row in that same list
4. Contact
   Footer
```

---

## 3. Hero

Currently holding the reference site's copy. Replace.

**Tagline** (display serif, STIX Two Text):

> I Design It. Then I Build It.

Alternates: *Designed And Built By One Person* · *One Person, Both Halves*

**Paragraph** (Archivo):

> I design and build websites end to end — layout, type, motion, code. Mostly for founders and small teams who need the whole thing, not half of it.

**CTA:** See My Work → `#work`

---

## 4. Work

One section. Five rows. Row = number · name · tagline · provenance label · Explore More. Hover reveals the site capture.

Client work leads. **The Client / Self-directed label goes on the row, visible** — three of these have no client behind them, and the label is what keeps the section honest.

### O-001 · QSense Tech — *Crop Science, Made Visible*

**Client** · <https://qsensetech.com>

> Agri-biotech that reads crop health from light. Dark, instrument-like, with live spectral readouts running in the hero.

### O-002 · Lilysys Solutions — *Genomes, Made Legible*

**Client** · <https://dna-website-ten.vercel.app>

> Whole-genome sequencing for microbial labs. Clean, white, clinical — built so the science reads before the design does.

### O-003 · SOKAI — *Calibre S-01*

**Self-directed** · <https://sokia-watch-web-desgin.vercel.app>

> A watch house that doesn't exist, built like one that does. The most technically ambitious thing here.

Next 15 · Framer Motion · Lenis

### O-004 · Avelon — *Heritage, Still Worn*

**Self-directed** · <https://avelon-clothing.vercel.app>

> Heritage menswear, invented. Full-bleed garment photography and a wordmark big enough to carry the whole page.

### O-005 · Ashbourne — *Laid Down in the Dark*

**Self-directed** · <https://whisky-website-design.vercel.app>

> Whisky, in the dark. A chapter-based scroll where the page gets deeper instead of longer.

### Layout notes

- Blurbs run 12–25 words. Names 3–12 characters.
- Layout must hold 4–8 projects without a redesign.
- Every project links to the live site, new tab.
- Architected so `/work/[slug]` can drop in later without restructuring.

---

## 5. About — `O-006 · Devraj` — *The Sixth Project*

Sixth row in the same list, same component. Expands into you instead of a site.

Why it works: reuses the row you already built, needs no new section, and lands the one true thing about the page — the site is the work sample.

> **What I do.** I design and build websites. Both halves, same person — the layout, the type, the motion and the code are decisions made by one head instead of handed across a wall.
>
> **What I'm doing now.** `[current status — studying? employed? full-time freelance?]`, plus AI work: retrieval systems that let you ask questions of your own documents and get answers that cite where they came from. Same job as everything else on this page — take something complicated and make it legible.
>
> **Where I'm going.** Taking on freelance work, and open to a role where design and engineering aren't two different teams.

Portrait slot reserved.

---

## 6. Contact

> **Start a conversation.**
>
> Tell me what you're building. I'll tell you honestly whether I'm the right person for it.

Email at display size, the only link on the section. No form.

`devrajgothi11@gmail.com`

---

## 7. Footer

- GitHub — <https://github.com/devraj11gothi>
- LinkedIn — <https://www.linkedin.com/in/devraj11gothi>
- © 2026

---

## 8. Blockers

- **`assets/work/` is empty.** Five site captures at 1440px. The Work section cannot be built without them.

## 9. Open questions

- Current status — the bracket in §5. Student, employed, full-time freelance?
- Domain?
- Downloadable CV, or is email enough?
- Anything about the AI/RAG work that should be described more precisely?

---

## 10. Build status

- [x] Hero — built (`index.html`, `styles.css`). Copy still placeholder.
- [ ] Work
- [ ] About (`O-006`)
- [ ] Contact
- [ ] Footer
