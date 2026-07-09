# Trace — Project Documentation

Graphic Design track capstone: brand identity and UX/UI design system for **Trace**,
an AI-powered microplastics-detection wellness platform ("Understanding Microplastics.
Taking Action.").

## Contents

- `Project Proposal.pdf` — original brand strategy proposal (brand summary, problem
  statement, persona, SWOT)
- `Trace Presentation.pdf` — master visual deliverable (moodboard, logo development,
  mobile app, website, social, merchandise, business card)
- `Project Documentation-2.pdf` — program's documentation requirements/guidelines
- `Documentation/` — the 7-document project documentation set, generated as PDFs:
  1. Project Planning & Management
  2. Requirements Gathering
  3. Design Analysis & UX/UI Design
  4. Creative Toolkit & Brand Applications
  5. Design QA & Review
  6. Brand Guidelines Manual
  7. Final Project Report

## Regenerating the documentation PDFs

The PDFs in `Documentation/` are generated with reportlab, not hand-edited.

```bash
cd Documentation
python3 generate_all.py
```

- `_build.py` — shared design system (fonts, colors, tables, callouts, page chrome)
- `generate_all.py` — content for all 7 documents; edit here, then re-run

Content is sourced from `Project Proposal.pdf` and `Trace Presentation.pdf`; sections
that assume a coded software system (database design, API docs, source code, etc.) are
intentionally omitted as not applicable to the Graphic Design track.
