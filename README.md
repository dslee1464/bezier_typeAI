# bezier_typeAI
BEZIER - Interactive toolkit for controlling domestication-foreignization spectrum in cross-lingual typography

# bezier_typeAI

**Visual interface for controlling the Domestication Threshold in cross-lingual typography**

> An interactive toolkit that lets designers manipulate the domestication–foreignization spectrum in real time across Korean (한국어), Chinese (中文, Zhōngwén), and English typefaces — through direct visual interaction rather than text prompting.

---

## Concept

When AI transforms type styles across scripts, it doesn't treat all cultures equally. It exhibits a **domestication bias (자국화 편향)** — bending foreign letterforms toward familiar aesthetic norms. This project makes that bias visible, measurable, and controllable.

The central concept is the **Domestication Threshold (자국화 임계점)**: the tipping point at which a typeface's cultural identity shifts from foreign to domestic. By exposing this threshold as a slider, designers gain direct agency over cross-cultural visual translation.

```
← Foreignization                    Domestication →
|-------|-------|-------|---[↑]---|-------|-------|
                          Threshold
```

---

## Features (in development)

- **Spectrum Slider** — drag to move between foreignization and domestication in real time
- **Cross-lingual rendering** — simultaneous preview across Korean, Chinese (中文), and English glyphs
- **Threshold visualization** — see exactly where the cultural tipping point occurs
- **Bias audit** — compare AI-generated output against the domestication baseline

---

## Research Background

This tool is developed alongside a series of academic papers:

| Paper | Venue | Status |
|-------|-------|--------|
| Domestication bias in AI-generated Korean–Chinese–English typography | KSDS 2025 (한국디자인학회) | Submitted |
| Domestication Threshold: direct visual manipulation vs. text prompting | DIS 2026 | In progress |
| Cross-lingual type style transfer as cultural negotiation | CHI (target) | Planned |

The core argument: **direct visual manipulation outperforms text prompting** for controlling visual-semiotic bias in cross-lingual type transformation.

---

## Stack (planned)

```
Frontend    React + TypeScript
Backend     Python + FastAPI
Model       FontDiffuser (AAAI 2024) / fine-tuned diffusion model
Dataset     Korean–Chinese–English paired typeface corpus
```

---

## Roadmap

- [ ] Repository structure setup
- [ ] Dataset curation (Korean–Chinese–English glyph pairs)
- [ ] Model integration (FontDiffuser baseline)
- [ ] Slider prototype (domestication spectrum UI)
- [ ] Threshold detection algorithm
- [ ] User study / evaluation framework
- [ ] Paper release + demo

---

## Related Work

- FontDiffuser (AAAI 2024) — one-shot cross-lingual font generation
- Venuti, L. (1995) — *The Translator's Invisibility* (domestication–foreignization theory)
- Variable Font axis design — conceptual precedent for spectrum-based type control

---

## Author

**Sol Lee (이다솔)**
Graduate Researcher, Visual Communication Design
Seoul National University (서울대학교)
Incoming MFA Design & Technology, Parsons School of Design

---

## License

MIT License — open for research and collaboration.
