# Implementation and Visual Craft

Use this reference once an art direction has been selected.

## Typography

Define conceptual behavior before choosing fonts:

```yaml
type_system:
  conceptual_role:
  display_behavior:
  interface_behavior:
  numeric_behavior:
  density:
  contrast_strategy:
  expressive_device:
```

Use one or two type families. If two, give them genuinely different roles.

Use scale, width, weight, rhythm, and line breaking as design devices.

Avoid default generated-design tells unless justified:
- all-caps micro-labels everywhere;
- eyebrow over every heading;
- arbitrary one-word accent styling;
- monospace metadata used only to feel technical;
- excessive tracking.

## Color

Derive color from:
- brand;
- domain materials;
- environment;
- imagery;
- map language;
- instrumentation;
- data semantics.

Use a compact core palette when appropriate.

Color must communicate or reinforce the concept.

## Motion

Motion should explain:
- what changed;
- where an object moved;
- what is related;
- what deserves attention.

Prefer:
- state morphs;
- spatial continuity;
- direct manipulation feedback;
- a single orchestrated reveal.

Avoid generic fade-up choreography and movement on every hover.

Respect reduced motion.

## Expressive technology

Possible tools:
- shaders;
- WebGL;
- canvas;
- 3D;
- particles;
- generated visuals;
- variable fonts;
- blend modes;
- masking;
- scroll-linked effects.

For each technique ask:
1. What does it communicate?
2. Why does it belong?
3. What is the performance cost?
4. What is the fallback?
5. Is it accessible?

"It looks premium" is not enough.

## Structure

Use borders, frames, badges, labels, rules, and numbering only when they encode a relationship or state.

Do not number content that is not sequential.

## Content

Use realistic domain content:
- names;
- dates;
- measurements;
- status values;
- warnings;
- missing values;
- long values.

Placeholder content can manufacture false elegance.

## Responsive behavior

Do not merely stack desktop components.

At each width ask:
- what remains dominant;
- what collapses;
- what changes interaction mode;
- what becomes a drawer, rail, tab, or sheet;
- whether the signature move survives.

The layout can change while the thesis remains.

## Production floor

Always provide:
- keyboard operation;
- visible focus;
- semantic structure;
- sufficient contrast;
- reduced motion;
- robust text wrapping;
- accessible names;
- loading/failure behavior;
- touch-friendly targets;
- appropriate performance.
