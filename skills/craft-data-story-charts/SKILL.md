---
name: craft-data-story-charts
description: "Turn an established data finding into a clear, audience-centered explanatory visual and story through one complete, software-agnostic process: understand context, define the central message, choose evidence and display, remove clutter, direct attention, design for usability and accessibility, structure the narrative, render, test, and iterate. Use for charts, graphs, report visuals, dashboard views, executive slides, coded visualizations, chart redesigns, or reviews where the result must be understood and acted on rather than merely displayed."
---

# Craft Data Story Charts

## Mission

Transform data into an audience's understanding, decision, or action. Do not treat this Skill as a chart catalog, styling checklist, or software recipe. Carry one communication intent through every stage:

```text
analysis result
→ audience and desired response
→ central message and evidence
→ visual encoding
→ reduced cognitive load
→ directed attention
→ usable design
→ narrative sequence
→ rendered audience-tested result
```

The process is software-independent. Use any suitable rendering stack, but never let a tool default determine the story.

## Required references

Read these before creating or substantially redesigning an explanatory visual:

- [End-to-end method](references/end-to-end-method.md): the complete transformation and its feedback loops.
- [Chart selection](references/chart-selection.md): choose by the comparison the audience must make.
- [Visual language](references/visual-language.md): text, reading path, Gestalt structure, attention, color, fill, shading, borders, alignment, and accessibility.
- [Story and delivery](references/story-delivery.md): narrative, medium, animation, acceptance, iteration, and practice.
- [Quality gate](references/quality-gate.md): inspect the actual artifact before delivery.

Use [Methodology map](references/methodology-map.md) when tracing a rule to the book-derived method or distinguishing it from an AI-production extension.

## Maintain one Data Story Brief

Create and update this state throughout the task:

```text
Audience:
Audience relationship, prior knowledge, and likely concerns:
Decision or desired response:
Communication medium and tone:
Established finding:
Central message:
Supporting evidence:
Necessary context and contrary evidence:
Primary comparison:
Chosen display and encoding:
Reading path and attention order:
Narrative sequence:
Uncertainty and limitations:
Audience-test result:
```

Do not fill unknown fields with invented business context. Infer low-risk items when possible and label the inference; ask only when a missing answer would materially change the result.

## Complete workflow

### 1. Separate exploration from explanation

Determine whether the finding is established. Explore broadly when analysis is still open. Once the finding is established, stop exposing the entire search process and select the evidence the audience needs.

Do not use color or annotation to make an untested hypothesis look like a conclusion. Do not hide contrary evidence that would change the interpretation or decision.

### 2. Understand context before drawing

Define the specific audience, desired understanding or action, medium, available time, relationship and credibility, prior knowledge, concerns, and required detail.

Replace vague goals such as “show the data” with an observable response. Distinguish a live presentation, where the speaker controls sequence, from a self-contained document, where the reader controls sequence and needs more context.

### 3. Distill the central message

Create a three-minute version, then compress it into one complete central message:

```text
[What happened or matters], which means [stakes or benefit];
therefore [decision, recommendation, or next step when applicable].
```

Build a low-cost storyboard before polishing. Arrange problem, evidence, explanation, alternatives, and recommendation. Obtain early alignment when a stakeholder is available.

### 4. Select evidence and the display

Translate the central message into the comparison the audience must make. Then use [Chart selection](references/chart-selection.md).

Start with simple text for one or two values, a table for lookup, and familiar position-or-length encodings for comparison. Use lines for continuous change, scatterplots for relationships, slopes for two states, stacks for composition, waterfalls for contributions, and diverging stacks for positive/negative composition only when those judgments match the task.

Record why the chosen form is better than the closest alternative. Preserve honest baselines, intervals, units, ordering, totals, and uncertainty.

### 5. Remove cognitive friction

Inventory every border, background, gridline, axis, tick, marker, label, legend, color, fill, shadow, connector, icon, and decorative object. Give each a communication purpose.

Apply this order:

1. remove elements with no task;
2. weaken necessary context;
3. emphasize only the evidence that carries the message.

Use proximity, similarity, enclosure, closure, continuity, and connection to create structure. Prefer alignment and whitespace over boxes. Restore a minimal axis, grid, legend, or label if removing it prevents accurate reading.

### 6. Direct attention deliberately

Decide the intended first, second, and third visual stops. Neutralize the full view before adding emphasis. Use one dominant preattentive cue—usually position, contrast, size, weight, or a deliberate accent—and reserve stacked cues for the most important item.

Keep the focus small. Highlighting one thing suppresses others, so confirm the background evidence remains available. Direct-label important data instead of forcing legend lookup. Use conclusion text and annotations to explain why the highlighted evidence matters.

### 7. Think like a designer

Make form serve the audience's function. A reader should know where to start, how to compare, and what the result means without learning an arbitrary interface.

Check:

- **Affordance:** the reading and comparison path is evident.
- **Accessibility:** typography, contrast, language, redundant encodings, and delivery size work for the intended audience.
- **Aesthetics:** color, alignment, spacing, precision, and hierarchy feel deliberate and coherent.
- **Acceptance:** when a new form may meet resistance, show its benefit, compare old and new versions, offer meaningful alternatives, and seek feedback.

Treat text as part of the visualization. Use a conclusion title, necessary context, direct labels, annotations, definitions, and source notes in a visible hierarchy. Follow [Visual language](references/visual-language.md).

### 8. Structure the story and adapt the medium

For a sequence, establish a beginning, middle, and end:

- beginning: audience, setting, current state, and meaningful imbalance;
- middle: evidence, consequences, alternatives, and the path through the problem;
- end: resolution, recommendation, decision, or explicit open question.

Read titles alone to test horizontal logic. Within each view, test vertical logic: every mark and word must support its title. Use a reverse storyboard and an unfamiliar reader's retelling to find missing, repeated, or misplaced content.

For live delivery, use progressive reveal only when it follows the story. For self-contained delivery, include the annotations and context that speech would otherwise supply. Follow [Story and delivery](references/story-delivery.md).

### 9. Render, inspect, and iterate

When code is requested, write a reproducible source and render the artifact. Size it for the actual medium. Inspect the rendered output rather than approving code in the abstract.

Apply [Quality gate](references/quality-gate.md). If the audience test produces a different takeaway or reading order, return to the earliest stage responsible: context, message, evidence, encoding, hierarchy, or narrative. Do not patch a wrong story with more decoration.

## Delivery

Provide:

- the rendered result;
- the one-sentence central message;
- the intended audience and response;
- editable or reproducible source when requested;
- any uncertainty or constraint that changes interpretation;
- the quality-gate verdict and only the most important remaining tradeoff.

Keep methodological explanation shorter than the artifact unless the user asks for a design rationale.
