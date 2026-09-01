---
name: design-critique
description: >-
  This skill should be used when the user asks to "critique this design", "review this mockup", "review this UI", "what is wrong with this design?", "make this less generic", "assess visual hierarchy", or needs structured product-design feedback.
metadata:
  version: "2.0.0"
---

# Design Critique

Evaluate a design as a working product and as a piece of visual communication.

Do not reduce critique to preference. Tie findings to user goals, hierarchy, interaction, product identity, consistency, accessibility, or implementation consequences.

## Inputs

Work from any combination of:
- screenshot;
- rendered page;
- Figma design;
- source code;
- prototype;
- design description;
- design-system documentation.

If a live design source is connected and relevant, inspect it rather than guessing.

## Critique sequence

### 1. Immediate read
In the first few seconds:
- What draws the eye first?
- Is that the correct priority?
- Is the user's primary job understandable?
- What emotional/brand signal appears?
- Is the composition memorable or interchangeable?

### 2. Task usability
Assess:
- navigation;
- affordances;
- action clarity;
- flow;
- information scent;
- unnecessary steps;
- error prevention;
- feedback.

### 3. Hierarchy and composition
Assess:
- focal order;
- grouping;
- density;
- negative space;
- typography;
- dominant and supporting regions;
- whether visual containment is overused;
- responsive implications.

### 4. Product specificity
Run the swap test:

Imagine replacing the logo, product name, and copy.

Could the design belong to an unrelated SaaS product?

If yes, identify which parts are generic and what product-derived material could replace them.

### 5. Contemporary craft
When the brief calls for high-expression or contemporary design:
- distinguish current craft from current cliché;
- identify whether expressive techniques support the concept;
- note where the design feels dated, default, or imitative;
- do not recommend trends without a product rationale.

### 6. Consistency
Check:
- tokens;
- component behavior;
- spacing;
- geometry;
- interaction vocabulary;
- visual semantics.

Do not confuse consistency with uniformity. Different hierarchy levels may intentionally use different geometry or density.

### 7. Accessibility
Flag obvious issues, then use the accessibility-review skill for a formal audit when requested or necessary.

### 8. States and resilience
Inspect whether the design accounts for:
- loading;
- empty;
- long content;
- error;
- selection;
- disabled;
- success;
- warning;
- narrow screens.

## Feedback format

Prioritize findings.

For each meaningful issue:
1. **Observation** — what is happening.
2. **Why it matters** — user/design consequence.
3. **Recommendation** — a specific alternative.
4. **Priority** — critical, high, medium, or low.

Separate:
- structural issues;
- interaction issues;
- visual craft issues;
- consistency issues;
- accessibility issues.

Do not bury the top three changes inside a long list.

## Critique principles

- Specific over vague.
- Explain causality.
- Recommend structural fixes for structural problems.
- Preserve strong intentional choices.
- Do not redesign the work into your personal default.
- If the design is already strong, say what should *not* be changed.
