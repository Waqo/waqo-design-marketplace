---
name: design-system
description: >-
  This skill should be used when the user asks to "audit our design system", "document this component", "create design tokens", "extend our component library", "standardize our UI", "review component consistency", or needs design-system governance.
metadata:
  version: "2.0.0"
---

# Design System

Audit, document, extend, or evolve a design system without allowing consistency to erase product identity.

## First determine the task

### Audit
Find inconsistency, duplication, hardcoded values, incomplete states, weak semantics, accessibility gaps, and unnecessary one-off patterns.

### Document
Describe how an existing token, component, or pattern works.

### Extend
Create a new primitive, component, or pattern that fits the current system.

### Evolve
Change the system itself because the product's art direction or interaction model has changed.

## Inspect before inventing

When an existing system is available, identify:
- token structure;
- typography;
- color semantics;
- spacing;
- geometry;
- elevation/surface model;
- motion;
- components;
- variants;
- states;
- patterns;
- accessibility conventions.

Do not create a new token or component until checking whether an existing one serves the need.

## Avoid design-system flattening

A design system is not a requirement that every element have:
- the same radius;
- the same shadow;
- the same density;
- the same layout grammar.

Encode intentional hierarchy.

Examples:
- controls can use one geometry while data regions use another;
- expressive display typography can coexist with restrained interface typography;
- a signature visualization can remain a specialized primitive rather than being forced into a generic card.

## Token layers

Prefer semantic layers:
1. primitives;
2. semantic tokens;
3. component/application roles.

Document meaning, not only raw values.

## Components

For each component define:
- purpose;
- anatomy;
- variants;
- sizes where necessary;
- states;
- interaction;
- responsive behavior;
- content constraints;
- accessibility;
- tokens;
- examples;
- anti-patterns.

## Patterns

Document repeated workflows, not merely visual arrangements.

Examples:
- search and filter;
- data comparison;
- empty-to-first-action;
- confirmation;
- inline edit;
- AI suggestion/review;
- map selection;
- bulk actions.

## Extending the system

When proposing a new pattern:
1. name the unmet need;
2. show why existing patterns are insufficient;
3. derive it from the current art direction;
4. define reusable behavior;
5. define states and accessibility;
6. identify migration/adoption consequences.

## Output

For audits:
- system summary;
- highest-risk inconsistencies;
- token issues;
- component issues;
- pattern issues;
- accessibility gaps;
- prioritized remediation.

For extensions:
- rationale;
- specification;
- token usage;
- variants/states;
- accessibility;
- implementation guidance;
- examples and non-examples.
