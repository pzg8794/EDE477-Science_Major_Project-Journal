# EDE477 Science Major Project — rubric and voice audit (November 12, 2026)

**Review state: proposed corrections only; not merged into `main`, not synchronized to Overleaf, not submitted to Blackboard.** This is a reviewable patch. Do not overwrite the author's live Overleaf edits.

## Authorities examined

- Live Blackboard `Science Major Assignment`, course `_117600_1`, assessment `_9941299_1`, browser tab on November 12.
- Original co-planned [Invisible Invaders Monday, July 27 lesson](https://docs.google.com/document/d/1jc_dSOKXVhSoSbvfbivXlgfYOxrrJ2L6KwbR7LQZCLc/edit), 93 text paragraphs read from connected Google Docs, with the complete **Activity 2** defined in source paragraphs 38–47 inclusive.
- Corresponding [free public EDU486 camp lesson](https://github.com/pzg8794/EDU486/blob/main/assignments/03-camp-unit-plan/monday-water-pathways-and-first-model.md); [post-camp implementation addendum](https://github.com/pzg8794/EDU486/blob/main/assignments/03-camp-unit-plan/post-camp-implementation-revision-addendum.md).
- Original `main.tex` on `main` (Git blob `bead03d4cf94a03c6ce0dff00fd75aab81726aa9`) and current linked Overleaf project, `6af3557e9b91140108ad737c`. The existing live Overleaf PDF log reported **6 pages, 0 errors, 0 warnings** on November 10, before this patch.

## Assignment matrix

| Requirement | Original current journal | Proposed fix / resulting review state |
|---|---|---|
| Select a science lab/activity from placement or free online | Co-planned EDU486 summer science-camp Monday activity; source is public and free, but **not confirmed to be from Piter's current formal teaching placement**. | Keep truthful provenance and hyperlink to free EDU486 source. **Eligibility remains instructor-dependent** if the teacher specifically expects an externally found lesson rather than a co-created camp lesson. Do not falsely describe it as taught at the current placement. |
| Include original activity text | **Partial:** selected black excerpts and link to the whole source, with some black base text condensed from source. | **Improved:** full exact text of the 10-paragraph *Activity 2 — Impossible Cut + Escape the Wind + watch and wonder* reproduced in black in Appendix A. All 10 source paragraph strings matched an independently read Google Doc after LaTeX escaping. Appendix is the complete **chosen subactivity**, **not** the entire day's 93-paragraph lesson. |
| Highlight additions in a different color | Yes: blue `\revision{}` text with written `REVISION:` labels; black original excerpts. | Preserve; clarify key to distinguish the complete original Activity 2 and other base-language excerpts from colored proposed redesign. |
| Align with JuST | Multiple legitimate participation routes; youth decisions; systems accountability; no private identity disclosure; fair community action. | Preserve; no fabricated claim of universally successful access or youth empowerment. |
| Modeling and uncertainty | Before/during/after visual model; categorize observation vs. possible meaning vs. unknown; proxy paper is not chemically confirmed plastic; model revisions documented. | Preserve scientific bounds; no new scientific claims. |
| Storytelling | Connections across a student-facing question, field history, and storyline readings, but student evidence stories were previously under-explicit in revised sequence. | Add a short blue *Storyline launch — students' evidence stories*: youth choose a Friday observation/question, determine inquiry, then revisit the story after model revision. Personal disclosure remains optional. |
| One-page reflective justification | One `Reflective Justification` page and separate references in original 6-page Overleaf PDF, also reported in course README. Four course reading groups underpin the explanation. | **Reflection text preserved verbatim**, no new words or shortened content. Its original page-fit is verified from baseline records; **the proposed appended source has not yet received a live Overleaf recompilation or independent PDF visual check**. |
| Attribution, authenticity, privacy | Team Piter and Aastha acknowledged; EDU486 youth feedback and EDE477 readings support rationale; public-safe instructional figures; AI-process disclosure; no youth names/photos. | Preserve. This public GitHub patch adds no private student names, protected placement records, or photographs. |

## Patch boundaries and verification

- **Changed** only `main.tex` on the review branch; **no changes to `main`, the figures, or prior PDF**.
- Copied the **exact 10 original Activity 2 paragraphs** to Appendix A; each matched the original Docs text after LaTeX-safe typography conversions.
- Added one blue story-arc routine; clarified original-text scope and the color key.
- The entire original `Reflective Justification` section remains byte-for-byte unchanged.
- Readback verified the change commit and matched each paragraph. LaTeX braces balance to zero, but this is **not** a compiled-PDF or visual-QA guarantee.
- **Next acceptance checks:** run pdfLaTeX on the review branch with both image assets; inspect all pages, especially appendix and one-page reflection; compare against author's latest Overleaf edits before merging. Overleaf's GitHub integration requires an explicit sync. No LMS upload/submission is authorized by this review.

## Editorial recommendation

The central paper already sounds like Piter's teaching philosophy: access before failure, evidence over unsupported certainty, meaningful multilingual participation, and youth ownership of questions and action. Keep the original reflection's specific youth feedback and camp voice. Do not turn it into an impersonal theoretical essay. If the instructor requires a lab drawn from the current placement or an **independently authored** free online lesson, ask for that interpretation rather than relabeling camp work.
