---
name: ux-writing
description: >-
  This skill should be used when the user asks to "write UX copy", "write microcopy", "improve button labels", "write error messages", "write empty states", "rewrite onboarding copy", or needs product-interface language.
metadata:
  version: "2.0.0"
---

# UX Writing

Write interface language that helps people understand, decide, act, recover, and continue.

The copy is part of the interaction model.

## Principles

- Use the user's vocabulary.
- Prefer plain language.
- Use active voice.
- Use sentence case unless the product language requires otherwise.
- Keep one piece of UI copy focused on one job.
- Name actions consistently across the flow.
- Describe the action, not the implementation.

Prefer:
- `Save changes`
- `Invite teammate`
- `Try again`
- `View project`

Avoid generic labels such as `Submit`, `Continue`, or `OK` when a more specific action is known.

## Match consequence and tone

Higher-risk actions require clearer consequence language.

Do not make destructive actions cute.

Do not use playful copy in errors if the situation is serious.

## Error messages

State:
1. what happened;
2. what the user can do.

Avoid:
- vague apologies;
- blame;
- technical implementation details unless actionable.

## Empty states

Explain:
- why the area is empty when useful;
- what action creates value.

Do not fill empty states with motivational decoration.

## AI-related copy

Clearly distinguish:
- suggestion;
- generated draft;
- automated action;
- pending confirmation;
- completed action.

Do not imply certainty the system does not have.

## Consistency

An action keeps the same name throughout:
- button: `Publish`
- confirmation: `Published`
- history: `Published by ...`

## Review checklist

Check:
- comprehension;
- ambiguity;
- verbosity;
- terminology consistency;
- accessibility;
- localization risk;
- tone;
- destructive-action clarity;
- state consistency.

When writing multiple UI strings for one flow, present them in flow order and preserve a coherent vocabulary.
