<div align="center">

# Craft Data Story Charts

**A complete, software-agnostic method for turning an established data finding into audience understanding, a decision, or action.**

[![License: MIT](https://img.shields.io/badge/License-MIT-172B4D.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-compatible-246BFD.svg)](https://agentskills.io)
[![skills.sh](https://img.shields.io/badge/skills.sh-install-246BFD.svg)](https://skills.sh/NINTING/craft-data-story-charts)

[English](README.md) · [简体中文](README.zh-CN.md) · [Gallery](#gallery) · [Skill](skills/craft-data-story-charts/SKILL.md)

</div>

![Complete data-story workflow with an upstream feedback loop](examples/28-complete-workflow-feedback-loop.png)

## One transformation, not a chart cookbook

Chart software can draw marks. It cannot decide what this audience needs to understand, which evidence is sufficient, where attention should go, how text and visuals should work together, or what response the communication should produce.

This Skill carries one intent through the complete data-story process:

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

Chart types, color, typography, labels, fills, shading, borders, annotations, animation, and layout are not isolated tips. Each is selected at the stage where it advances that same communication intent.

The Skill is independent of Matplotlib, D3, ECharts, Vega, Excel, Tableau, Power BI, and any programming language.

## What the Skill makes an agent do

- separate exploratory analysis from an explanatory result;
- define the audience, desired response, medium, prior knowledge, and concerns;
- compress the result into a three-minute story and one central message;
- select only necessary evidence, context, uncertainty, and contrary evidence;
- choose the display from the comparison—not a software default;
- remove clutter, weaken context, and emphasize only the message-bearing evidence;
- construct a deliberate first, second, and third visual stop;
- treat text, reading path, color, fill, shading, spacing, and accessibility as part of the visualization;
- structure a beginning, middle, and end and adapt it for live or self-contained delivery;
- render the real artifact, test audience comprehension, and revise the earliest faulty stage.

## Install

```bash
npx skills add NINTING/craft-data-story-charts
```

For manual Codex installation, copy `skills/craft-data-story-charts` to:

```text
~/.codex/skills/craft-data-story-charts/
```

On Windows, this is normally `%USERPROFILE%\.codex\skills\craft-data-story-charts\`.

## Use

```text
Use $craft-data-story-charts with this established analysis result.

Audience: CFO and operating leads.
Desired response: decide which intervention receives next-quarter funding.
Medium: a self-contained executive slide.
Create one explanatory chart. Preserve uncertainty and contrary evidence,
render the final artifact, and apply the Skill's complete quality gate.
```

If the finding is not established, the Skill first keeps the work exploratory and avoids visually promoting an untested hypothesis into a conclusion.

## Complete method

| Stage | Question answered | Main techniques |
|---|---|---|
| 1. Exploration or explanation | Is the result established? | preserve alternatives; retain decision-changing evidence |
| 2. Context | Who needs what, how, and why? | audience, response, relationship, medium, tone, success |
| 3. Central message | What is the one complete point? | three-minute story, central sentence, storyboard |
| 4. Evidence and display | What must the audience compare? | evidence classification, honest encoding, nearest alternative |
| 5. Cognitive load | What can disappear or recede? | Gestalt, direct labels, remove → weaken → emphasize |
| 6. Attention | What should be noticed first, second, third? | position, contrast, size, weight, restrained accent |
| 7. Design | Can the audience use and accept it? | affordance, text, accessibility, aesthetics, acceptance |
| 8. Story and medium | In what order should understanding unfold? | beginning–middle–end, title spine, vertical logic, live vs written |
| 9. Render and iterate | Did the actual audience receive the intended message? | rendered inspection, retelling, value trace, upstream revision |

The maintained [Data Story Brief](skills/craft-data-story-charts/SKILL.md) prevents these stages from becoming disconnected checklists.

## Visual coverage

The references cover:

- simple text, tables, heatmaps, scatterplots, lines, slopes, bars, stacked and 100% stacked bars;
- diverging and positive/negative contribution stacks, waterfalls, horizontal priority stacks, areas, pies/donuts, dual-axis risks, and multi-view design;
- conclusion titles, typography, reading direction, direct labels, annotations, and page position;
- Gestalt grouping, alignment, whitespace, borders, legends, gridlines, markers, and precision;
- color semantics, ordered intensity, grayscale redundancy, accessibility, dark backgrounds;
- the difference between decorative shadows, structural fills, data intervals, and context regions;
- animation, category order, spaghetti-chart alternatives, common-scale small multiples, and audience acceptance.

## Gallery

The gallery was regenerated for v2 from original synthetic data. It contains 30 finished PNGs covering the method as a system—not only a list of chart types. No chart-specific datasets, rendering scripts, or software recipes are shipped in the public repository.

### Context and complete workflow

| Data Story Brief | Complete feedback loop |
|---|---|
| [![Audience-first Data Story Brief](examples/01-context-data-story-brief.png)](examples/01-context-data-story-brief.png) | [![Complete upstream workflow](examples/28-complete-workflow-feedback-loop.png)](examples/28-complete-workflow-feedback-loop.png) |

### Choose the display from the audience's task

| Simple text | Exact-value table |
|---|---|
| [![Simple KPI text](examples/02-simple-text-kpi.png)](examples/02-simple-text-kpi.png) | [![Lookup table](examples/03-lookup-table.png)](examples/03-lookup-table.png) |

| Highlight table / heatmap | Scatter relationship |
|---|---|
| [![Highlight table heatmap](examples/04-highlight-table-heatmap.png)](examples/04-highlight-table-heatmap.png) | [![Scatter relationship](examples/05-scatter-relationship.png)](examples/05-scatter-relationship.png) |

| Highlighted time trend | Forecast interval |
|---|---|
| [![Highlighted line trend](examples/06-highlighted-line-trend.png)](examples/06-highlighted-line-trend.png) | [![Forecast interval](examples/07-forecast-interval.png)](examples/07-forecast-interval.png) |

| Before / after slope | Ranked bars |
|---|---|
| [![Slope chart](examples/08-slope-before-after.png)](examples/08-slope-before-after.png) | [![Ranked horizontal bars](examples/09-ranked-horizontal-bars.png)](examples/09-ranked-horizontal-bars.png) |

| Total + composition | Relative composition |
|---|---|
| [![Stacked total and composition](examples/10-stacked-total-composition.png)](examples/10-stacked-total-composition.png) | [![One-hundred-percent composition](examples/11-100pct-composition.png)](examples/11-100pct-composition.png) |

| Diverging sentiment | Positive / negative contribution |
|---|---|
| [![Diverging sentiment](examples/12-diverging-sentiment.png)](examples/12-diverging-sentiment.png) | [![Positive and negative contribution](examples/13-positive-negative-contribution.png)](examples/13-positive-negative-contribution.png) |

| Waterfall | Priority stack |
|---|---|
| [![Waterfall contribution](examples/14-waterfall-contribution.png)](examples/14-waterfall-contribution.png) | [![Horizontal priority stack](examples/15-horizontal-priority-stack.png)](examples/15-horizontal-priority-stack.png) |

| Distribution / interval | Pie alternatives by task |
|---|---|
| [![Distribution interval](examples/16-distribution-interval.png)](examples/16-distribution-interval.png) | [![Pie alternatives](examples/17-pie-alternatives-by-task.png)](examples/17-pie-alternatives-by-task.png) |

| Dual-axis alternative | Geography + precise rank |
|---|---|
| [![Dual-axis alternative](examples/18-dual-axis-alternative.png)](examples/18-dual-axis-alternative.png) | [![Map plus normalized comparison](examples/29-map-plus-normalized-comparison.png)](examples/29-map-plus-normalized-comparison.png) |

| Area for magnitude | Line for precise change |
|---|---|
| [![Area and line chosen by task](examples/30-area-versus-line-task.png)](examples/30-area-versus-line-task.png) | [![Text and reading path](examples/21-text-reading-path.png)](examples/21-text-reading-path.png) |

### Reduce friction and direct attention

| Declutter before / after | Attention hierarchy |
|---|---|
| [![Declutter transformation](examples/19-declutter-before-after.png)](examples/19-declutter-before-after.png) | [![Attention hierarchy](examples/20-attention-hierarchy.png)](examples/20-attention-hierarchy.png) |

| Fill and shading semantics | Dense series to small multiples |
|---|---|
| [![Fill and shading semantics](examples/22-fill-shading-semantics.png)](examples/22-fill-shading-semantics.png) | [![Small multiples](examples/23-spaghetti-to-small-multiples.png)](examples/23-spaghetti-to-small-multiples.png) |

| Dark-background adaptation | Redundant accessible encoding |
|---|---|
| [![Dark background](examples/26-dark-background.png)](examples/26-dark-background.png) | [![Accessible encoding](examples/27-accessible-redundant-encoding.png)](examples/27-accessible-redundant-encoding.png) |

### Story and delivery

| Beginning → middle → end | Live vs self-contained |
|---|---|
| [![Beginning middle end](examples/24-beginning-middle-end.png)](examples/24-beginning-middle-end.png) | [![Live versus written delivery](examples/25-live-vs-self-contained.png)](examples/25-live-vs-self-contained.png) |

## Repository structure

```text
craft-data-story-charts/
├── skills/craft-data-story-charts/
│   ├── SKILL.md
│   ├── agents/openai.yaml
│   └── references/
│       ├── end-to-end-method.md
│       ├── chart-selection.md
│       ├── visual-language.md
│       ├── story-delivery.md
│       ├── quality-gate.md
│       └── methodology-map.md
├── examples/*.png
├── README.md
├── README.zh-CN.md
├── CONTRIBUTING.md
└── LICENSE
```

## Methodology and provenance

This is an independent open-source operationalization inspired primarily by Cole Nussbaumer Knaflic's *Storytelling with Data* and its Chinese edition, *用数据讲故事*. It is not affiliated with or endorsed by the author or publisher.

The [methodology map](skills/craft-data-story-charts/references/methodology-map.md) maps the ten chapters to the workflow and explicitly distinguishes book-derived ideas from AI-production extensions such as the named state object, rendered-output requirement, integrity checks, and numerical quality gate. No book scans or reproduced book illustrations are included.

## Contributing and license

Issues and pull requests are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

[MIT](LICENSE) © 2026 NINTING
