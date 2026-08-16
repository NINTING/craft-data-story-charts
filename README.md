<div align="center">

# Craft Data Story Charts

**A complete, software-agnostic method for turning an established data finding into audience understanding, a decision, or action.**

[![License: MIT](https://img.shields.io/badge/License-MIT-172B4D.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-compatible-246BFD.svg)](https://agentskills.io)
[![skills.sh](https://img.shields.io/badge/skills.sh-install-246BFD.svg)](https://skills.sh/NINTING/craft-data-story-charts)

[English](README.md) · [简体中文](README.zh-CN.md) · [Gallery](#gallery) · [Skill](skills/craft-data-story-charts/SKILL.md)

</div>

![Highlighted operations trend showing a decision-ready data story](examples/04-highlighted-line-delivery.png)

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

The repository intentionally contains finished original images only—no chart-specific datasets, rendering scripts, or software recipes.

| KPI + sparkline | Ranked comparison |
|---|---|
| [![Retention KPI](examples/01-kpi-retention.png)](examples/01-kpi-retention.png) | [![Ranked CAC bars](examples/02-ranked-bars-cac.png)](examples/02-ranked-bars-cac.png) |

| Target comparison | Forecast + uncertainty |
|---|---|
| [![Manufacturing target dot plot](examples/03-target-dotplot-defects.png)](examples/03-target-dotplot-defects.png) | [![Capacity forecast](examples/10-forecast-capacity.png)](examples/10-forecast-capacity.png) |

| Before / after slope | Diverging composition |
|---|---|
| [![Onboarding slope chart](examples/05-slope-onboarding.png)](examples/05-slope-onboarding.png) | [![Employee satisfaction composition](examples/06-diverging-satisfaction.png)](examples/06-diverging-satisfaction.png) |

| Waterfall contribution | Relationship + exception |
|---|---|
| [![ARR waterfall](examples/07-waterfall-arr.png)](examples/07-waterfall-arr.png) | [![Store exception scatterplot](examples/08-scatter-stores.png)](examples/08-scatter-stores.png) |

| Dense-pattern heatmap | Highlighted time trend |
|---|---|
| [![Support demand heatmap](examples/09-heatmap-support.png)](examples/09-heatmap-support.png) | [![Regional delivery trend](examples/04-highlighted-line-delivery.png)](examples/04-highlighted-line-delivery.png) |

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
