---
name: frontend-design
description: >-
  This skill should be used when the user asks to "design a frontend", "build a UI", "redesign this interface", "make this look less generic", "create a dashboard", "create a landing page", "make this Dribbble-level", "improve the visual design", or needs contemporary art direction and production frontend implementation.
metadata:
  version: "2.0.0"
---

# Frontend Design

Create distinctive, contemporary, production-grade frontend work without defaulting to the statistical average of recent UI.

The governing principle is:

> Discover a visual idea that could only belong to this product, then make it usable.

A technically clean interface can still fail if its screenshot could belong to dozens of unrelated products.

## Choose the mode

### Concept mode
Use for greenfield products, major redesigns, expressive landing pages, high-visibility interfaces, and requests for visually original work.

Prioritize exploration before convergence.

### Product mode
Use after selecting a visual direction or for focused implementation tasks.

Prioritize usability, states, responsive behavior, accessibility, maintainability, and performance.

For substantial new UI:

**Concept mode → direction selection → Product mode.**

## Step 1: Understand

Before designing, identify:
- subject/product;
- audience;
- primary user job;
- environment;
- core objects and information;
- characteristic user state;
- domain materials, measurements, imagery, language, and metaphors;
- brand constraints.

Use realistic content.

If a missing assumption materially changes the design, make a concrete working assumption rather than silently generating generic SaaS.

## Step 2: Calibrate visually

For contemporary or expressive work, read `references/visual-radar.md`.

Use domain, recent craft, and cross-domain references.

Do not copy a single reference. Extract visual genes.

## Step 3: Diverge

Read `references/art-direction.md`.

Generate at least three genuinely incompatible concepts for substantial creative work.

Different mental models, not theme variants.

## Step 4: Select and art-direct

Choose one direction.

Define:
- visual thesis;
- source worlds;
- primary visual behavior;
- quiet supporting elements;
- signature move;
- one controlled violation if useful.

Do not define the full token system until the direction is selected.

## Step 5: Compose spatially

Design the view as a spatial field before deriving components.

Use ASCII sketches if useful.

Think in masses, axes, anchors, edges, clusters, density, negative space, and depth.

Avoid accidental cardification.

## Step 6: Design the characteristic state

Show the product in meaningful use, not merely in a clean resting state.

Decide whether the most representative moment is:
- live;
- selected;
- editing;
- comparing;
- warning;
- historical;
- AI-assisted;
- empty;
- loading;
- failure;
- success.

## Step 7: Tokenize and implement

Read `references/implementation.md`.

Define:
- typographic behavior;
- color logic;
- geometry;
- spacing;
- motion;
- surfaces.

Use expressive technology only when it serves the product concept.

## Step 8: Render and critique

Read `references/critique-loop.md`.

When previews/screenshots are possible, make visual review part of the loop.

If the critique reveals a structural issue, recompose rather than merely polishing tokens.

## Step 9: Productize

Complete:
- responsive adaptation;
- keyboard support;
- visible focus;
- semantic structure;
- accessibility;
- reduced motion;
- loading/error/empty states;
- edge cases;
- performance.

## Compact planning format

Use this before implementation when the task is substantial:

```yaml
product:
  audience:
  primary_job:
  characteristic_state:

visual_radar:
  domain_signals:
  contemporary_signals:
  cross_domain_signal:
  overexposed_patterns_to_avoid:

directions:
  - name:
    thesis:
    composition:
    signature_move:
    risk:
  - name:
    thesis:
    composition:
    signature_move:
    risk:
  - name:
    thesis:
    composition:
    signature_move:
    risk:

selected_direction:
  why:
  art_direction:
  controlled_violation:

type:
  conceptual_role:
  display_behavior:
  interface_behavior:
  numeric_behavior:

color:
  - name: "#HEX"
  - name: "#HEX"
  - name: "#HEX"
  - name: "#HEX"

layout:
  concept:
  alignment:
  density:
  responsive_shift:

motion:
  primary_moment:
  interaction_feedback:

genericness_check:
  what_could_still_belong_to_another_product:
  revision:
```

Keep the plan concise enough to drive work rather than becoming design-theater documentation.

## Final test

Before calling the design finished, answer:
- What is the visual thesis?
- What could only belong to this product?
- What is the signature move?
- Which current default did you intentionally avoid?
- What contemporary technique did you use, if any, and why?
- Could the composition survive a logo swap without becoming generic?
- Is any decoration doing no work?
- Does mobile preserve the idea?
- Is the interface accessible and performant?

If the strongest description is only "clean, modern, professional," the design is not finished.
