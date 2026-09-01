---
name: accessibility-review
description: >-
  This skill should be used when the user asks to "audit accessibility", "check a11y", "is this accessible?", "review WCAG", "check keyboard navigation", "check contrast", or needs accessibility remediation before design or developer handoff.
metadata:
  version: "2.0.0"
---

# Accessibility Review

Audit a UI, design, prototype, or implementation for accessibility and provide concrete remediation.

Use the applicable accessibility standard requested by the user. If none is specified, use current WCAG 2.x AA expectations appropriate to the environment and clearly identify the basis.

Do not claim automated visual inspection proves full compliance.

## Review areas

### Perceivable
Check:
- text contrast;
- non-text contrast;
- meaningful images;
- text scaling;
- information not conveyed by color alone;
- visible focus;
- readable typography.

### Operable
Check:
- keyboard access;
- logical focus order;
- focus trapping;
- escape behavior;
- target sizes;
- motion;
- timing;
- gestures;
- hover-only interactions.

### Understandable
Check:
- labels;
- instructions;
- validation;
- errors;
- predictable controls;
- consistent naming;
- destructive action clarity.

### Robust
Check:
- semantic elements;
- accessible names;
- roles/states/properties;
- live-region behavior;
- screen-reader announcements;
- custom widget semantics.

## Responsive and zoom behavior

Assess:
- reflow;
- clipping;
- horizontal scrolling;
- text enlargement;
- sticky/fixed elements;
- touch interactions.

## Dynamic states

Audit:
- loading;
- success;
- failure;
- disabled;
- expanded/collapsed;
- dialogs;
- menus;
- drag and drop;
- notifications;
- live updates.

## Motion

Check:
- reduced-motion support;
- flashing;
- essential vs decorative animation;
- whether motion communicates information unavailable elsewhere.

## Report format

For each issue provide:
- severity;
- affected element/state;
- problem;
- user impact;
- remediation;
- relevant criterion when confidently applicable.

Group into:
- blockers;
- high impact;
- medium;
- polish.

State what could not be verified from the available artifact.
