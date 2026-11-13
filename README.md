# Invisible Invaders: Evidence, Story, and Fair Action

**EDE477 Science Major Project | Piter Zacari Garcia Bautista | Fall 2026**

This is a **new portfolio-ready instructional redesign**, not an ongoing journal. It builds from the existing, co-planned July 27, 2026 *Invisible Invaders* activity and is formatted in the consistent Warner School / EDE477 burgundy-and-navy visual style used in the science, social-studies, and mathematics reflection journals.

## What is included

- `main.tex` - actual Overleaf entrypoint with the complete student/teacher project, original-versus-revision comparisons, student recording sheets, visual evidence/model sequences, title page, and references.
- `sections/reflection.tex` - **exactly one PDF page** of reading-grounded reflective justification.
- `sections/original-activity.tex` - verbatim original selected subactivity `Impossible Cut + Escape the Wind + watch and wonder` (full selected Activity 2, not the full Monday camp day).
- `sections/sources.tex` - course readings, original sources, evidence, attribution, privacy, and AI-process notes.
- `assets/field-sampling-crop.jpg` - previously published privacy-cropped camp photo from the math reflection archival sources; face-free and clearly labeled as a designed recap, **not raw evidence**.
- `Invisible-Invaders-EDE477-Science-Major-Project-Portfolio.pdf` - locally compiled and visually inspected nine-page draft.

The repository also retains its historical `figures/` folder and Git history. The **previous `main.tex` is archived independently** rather than overwritten without recovery.

## Rebuild

Set `main.tex` as the Overleaf main document and use **pdfLaTeX**. Run twice for hyperlinks. From a local clone:

```sh
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

The exact output is expected to be **9 PDF pages**: 1 cover, 5 instructional design and student-facing pages, 1-page reflection, 1-page original activity appendix, 1-page source record. Cover is separate front matter; the one-page reflection is **PDF page 7**.

## Rubric fit and authenticity

The live Blackboard EDE477 Science Major Assignment asks for a science activity from placement or freely available online, original text with revisions in another color, JuST, modeling, uncertainty, storytelling, and one-page justification citing course readings.

This artifact uses the genuine July 27 camp activity co-planned by Piter and Aastha, publicly available from the [EDU486 instructional archive](https://github.com/pzg8794/EDU486/blob/main/assignments/03-camp-unit-plan/monday-water-pathways-and-first-model.md). It does **not** claim to be from Piter's current formal school placement or independently preapproved by Professor Stell. A stricter interpretation of the eligible original-source rule requires instructor clarification. The selected activity is reproduced in full in black in Appendix A; new instructions are labeled `PROPOSED REDESIGN | BLUE`.

Original activities and youth feedback are grounded in the [post-camp implementation addendum](https://github.com/pzg8794/EDU486/blob/main/assignments/03-camp-unit-plan/post-camp-implementation-revision-addendum.md). The paper proxy and field sample are never presented as chemically proven plastic or exposure evidence. Co-facilitation, student privacy, and AI-assisted layout provenance are acknowledged.

## Source-of-truth boundary

The original historical GitHub project and current Overleaf project remain separate until the owner **pulls the GitHub revision** using Overleaf's GitHub integration. A public GitHub update alone does not certify that the browser-based project has synced. No Blackboard submission or LMS receipt is implied by these files.

**Status:** complete draft source and locally compiled nine-page PDF, ready for owner review; NOT SUBMITTED. The original past project is preserved in Git history and under `archive/`.
