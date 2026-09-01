---
name: design-handoff
description: >-
  This skill should be used when the user asks to "create design handoff", "write developer specs", "spec this UI", "prepare this for engineering", "document responsive behavior", or needs implementation-ready design specifications.
metadata:
  version: "2.0.0"
---

# Design Handoff

Produce implementation-ready design specifications so engineering does not have to guess at unstated behavior.

Use the actual design/system/code source when available.

## Include only what is known

Distinguish:
- explicit design decisions;
- existing system rules;
- inferred recommendations;
- unresolved questions.

Do not present guesses as measured specifications.

## Specification areas

### Layout
- container behavior;
- grid/axes;
- widths;
- spacing;
- alignment;
- overflow;
- stacking;
- sticky/fixed behavior.

### Typography
- token/family;
- size;
- weight;
- width if relevant;
- line height;
- tracking;
- wrapping;
- truncation.

### Color and surfaces
- semantic tokens;
- borders;
- elevation;
- transparency;
- media treatment.

### Components
For each:
- anatomy;
- variants;
- states;
- props/data;
- actions;
- validation;
- disabled/loading behavior.

### Interaction
Document:
- trigger;
- result;
- transition;
- focus behavior;
- dismissal;
- persistence;
- undo where applicable.

### Motion
Specify:
- property;
- duration;
- easing;
- spatial relationship;
- reduced-motion alternative.

### Responsive
For each meaningful breakpoint or layout mode:
- composition change;
- navigation change;
- density change;
- content priority;
- interaction change.

Do not describe mobile only as "stack vertically."

### Content resilience
Specify:
- min/max content;
- long strings;
- missing values;
- localization expansion;
- empty;
- loading;
- error.

### Accessibility
Specify:
- semantic element;
- accessible name;
- keyboard interaction;
- focus order;
- announcement behavior;
- contrast requirements.

## Signature behavior

For distinctive interfaces, explicitly document the signature move so it is not lost in implementation.

Include:
- user value;
- triggering state;
- spatial behavior;
- fallbacks;
- responsive adaptation;
- reduced-motion behavior.

## Output

Organize by screen/flow and reusable component.

End with:
- unresolved decisions;
- engineering risks;
- QA acceptance checklist.
