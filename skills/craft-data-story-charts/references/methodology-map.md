# Methodology map and provenance

This Skill is an independent, software-agnostic operationalization of audience-centered explanatory visualization. Its primary methodological source is Cole Nussbaumer Knaflic's *Storytelling with Data* (Chinese edition: *用数据讲故事*). It summarizes and transforms ideas into agent instructions; it does not reproduce the book, its pages, or its illustrations.

## Book-derived method

| Method stage | Main source chapters | Operational meaning in this Skill |
|---|---:|---|
| Understand context | 1 | Define audience, relationship, prior knowledge, desired response, medium, tone, and success before drawing. |
| Choose an effective visual | 2 | Match the display to the comparison: text, tables, heatmaps, scatterplots, lines, slopes, bars, stacks, waterfalls, or another honest form. |
| Remove clutter | 3 | Manage cognitive load with Gestalt structure, alignment, whitespace, direct labels, and the remove → weaken → emphasize sequence. |
| Focus attention | 4 | Use memory and preattentive attributes to control the first visual stop, reading path, emphasis, size, color, and page position. |
| Think like a designer | 5 | Make form serve function through affordance, accessibility, aesthetics, acceptance, hierarchy, and text that actively explains. |
| Apply the method | 6 | Treat chart choice, decluttering, focus, text, and annotation as one transformation rather than independent tricks. |
| Tell a story | 7 | Use beginning–middle–end, audience-as-protagonist, horizontal and vertical logic, reverse storyboarding, and purposeful repetition. |
| Complete the workflow | 8 | Carry context through message, evidence, display, clutter reduction, attention, design, and narrative; return upstream when a later result fails. |
| Handle difficult situations | 9 | Adapt for dark backgrounds, animation, category order, dense multi-series views, small multiples, and composition alternatives. |
| Improve through practice | 10 | Sketch early, create controlled variants, seek feedback, budget communication time, build a reference library, and grow team capability. |

The Skill's central pipeline preserves that integration:

```text
context → central message → evidence → encoding → reduced friction
→ attention hierarchy → usable design → narrative → delivery and iteration
```

## AI-production extensions

The following requirements make the method executable and verifiable by an AI agent. They are project conventions, not claims that the book specifies these exact mechanisms:

- the named `Data Story Brief` state object;
- recording the closest rejected display alternative;
- requiring a rendered artifact when rendering is available;
- explicit integrity checks against supplied values;
- the five-second, eye-draw, grayscale, thumbnail, title-only, vertical-logic, and value-trace tests as one consolidated gate;
- hard-failure rules and the 100-point scoring rubric;
- a default pass threshold of 85/100;
- delivery of editable or reproducible source when requested.

These extensions must not override the methodology. A numerical score cannot rescue an unclear audience, unsupported conclusion, dishonest encoding, or broken story.

## Copyright boundary

Do not package or redistribute scans, page images, diagrams, extended quotations, or reconstructed book examples. Public examples should use original or synthetic data and original visual execution. Attribute the methodological inspiration and keep quotations short and necessary.
