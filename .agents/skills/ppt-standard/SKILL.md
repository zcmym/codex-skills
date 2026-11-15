---
name: ppt-standard
description: Plan, create, revise, and quality-check clear, professional, editable PowerPoint presentations for academic, engineering, research, and business use. Use for slide outlines, evidence-based storytelling, charts, diagrams, technical presentations, and PPTX review.
---

# PPT Standard

## Purpose
Produce accurate, audience-focused, editable presentations. Prioritize a clear argument, traceable evidence, legibility, and consistent visual hierarchy over decoration.

## Before building
- Establish audience, purpose, duration, language, slide count, and delivery format when these materially affect the deck.
- Inspect supplied source documents, datasets, templates, and reference slides before drafting.
- Separate verified facts, calculations, assumptions, and recommendations. Never fabricate citations, data, standards, project outcomes, or quotations.
- Create a one-sentence takeaway and logical story arc before designing slides.

## Story and slide design
- Give each slide one primary message expressed as an assertion, not merely a topic label.
- Frame the problem, develop evidence and reasoning, then state conclusions and next steps.
- Prefer diagrams for systems, workflows, HVAC loops, building-energy flows, BIM processes, and cause-effect relationships when they clarify relationships.
- Label chart units, axes, time periods, sample sizes, and data sources.
- Keep slide text concise; move detail to speaker notes or an appendix.
- Use consistent grids, alignment, margins, typography, color semantics, and image treatment.
- Use high contrast and readable font sizes. Starting point: 28–36 pt titles and 18–24 pt body text.
- Avoid excessive icons, dense paragraphs, tiny footnotes, and repeated generic layouts.

## Technical and academic integrity
- Cite external claims, figures, standards, and images on slides or in speaker notes.
- For engineering claims, identify applicable standards and edition/year; verify current requirements.
- For AI, energy, HVAC, green-building, BIM, and low-carbon topics, distinguish measured data, simulations, model outputs, and proposed scenarios.
- State assumptions, boundary conditions, units, baselines, and uncertainty where relevant.
- Never imply correlation proves causation or simulated savings are measured savings.

## Build and edit
- Prefer native editable PowerPoint text, shapes, charts, and diagrams.
- Preserve the user's original file and template structure when editing; work on a copy unless instructed otherwise.
- Use a renderer compatible with the active environment (for example, PptxGenJS or python-pptx); do not assume packages or PowerPoint runtime are installed.
- Keep source data separate from slide-generation code and avoid machine-specific absolute paths.

## Quality assurance
1. Build the PPTX and confirm it opens or parses successfully.
2. Render every slide to images using an available renderer.
3. Inspect every slide for clipping, overlap, bad wrapping, illegible text, broken connectors, image distortion, and inconsistent alignment.
4. Check chart values against source data and verify units and labels.
5. Verify citations and source links.
6. Rebuild and re-render after fixes.
7. Deliver the editable PPTX and concise QA note; disclose renderer limitations or unverified details.
