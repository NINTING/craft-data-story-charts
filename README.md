<div align="center">

# Craft Data Story Charts

**Turn raw business data into clear, elegant, decision-ready explanatory charts.**

[![License: MIT](https://img.shields.io/badge/License-MIT-172B4D.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-compatible-246BFD.svg)](https://agentskills.io)
[![skills.sh](https://skills.sh/b/NINTING/craft-data-story-charts)](https://skills.sh/NINTING/craft-data-story-charts)

[English](README.md) · [简体中文](README.zh-CN.md) · [Gallery](#gallery) · [Skill instructions](skills/craft-data-story-charts/SKILL.md)

</div>

![Highlighted operations trend showing a decision-ready data story](examples/04-highlighted-line-delivery.png)

## Why this Skill exists

Most charting tools can draw marks. They do not decide what an audience should understand, which comparison matters, what should be emphasized, or whether the result is ready to drive a decision.

`craft-data-story-charts` gives an AI agent a software-agnostic workflow for turning data into an explanatory visual:

> **Audience → decision → comparison → Big Idea → chart → visual hierarchy → rendered inspection → quality gate**

The Skill works with any capable rendering stack. It does not prescribe Matplotlib, D3, ECharts, Vega, Excel, Tableau, Power BI, or a particular programming language.

## What it changes

Without a communication method, agents often produce a generic title, default colors, a remote legend, too many labels, and no clear answer to “so what?” This Skill requires the agent to:

- identify a specific audience and business use;
- separate exploratory analysis from the explanatory result;
- write one decision-relevant Big Idea before drawing;
- select the display from the comparison task, not the software default;
- use a conclusion title and direct annotations;
- keep context visible but visually subordinate;
- render the actual artifact instead of returning code only;
- pass a hard-failure checklist and a scored quality gate before delivery.

## Gallery

The gallery shows the range of final visuals the Skill can direct an agent to produce. Only the finished images are included—the Skill remains independent of any rendering stack.

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

## Install

### Skills CLI — recommended

```bash
npx skills add NINTING/craft-data-story-charts
```

The Skills CLI discovers `skills/craft-data-story-charts/SKILL.md` and installs it for a supported agent such as Codex, Claude Code, Cursor, GitHub Copilot, Gemini CLI, or Windsurf.

### Manual Codex installation

Copy `skills/craft-data-story-charts` into your personal Codex skills directory:

```text
~/.codex/skills/craft-data-story-charts/
```

On Windows this is normally:

```text
%USERPROFILE%\.codex\skills\craft-data-story-charts\
```

Restart or open a new agent session after installation so the skill metadata can be discovered.

## Use

Mention the skill explicitly when you want guaranteed activation:

```text
Use $craft-data-story-charts with revenue_bridge.csv.

Audience: CFO.
Decision: allocate next-quarter budget between acquisition and retention.
Create one standalone executive chart with code, render PNG and SVG,
and revise it until the Skill quality gate passes.
```

The Skill can also trigger automatically for requests such as:

- “Turn this dataset into a decision-ready chart.”
- “Improve this dashboard visual so the key result is obvious.”
- “Create an executive data story from these monthly metrics.”
- “Review this chart for clarity, hierarchy, accessibility, and integrity.”

## Method

### 1. Establish the communication contract

Define the audience, decision, primary comparison, medium, and required context. The chart is designed for a specific use—not for “everyone.”

### 2. Extract the result

Analyze the data, then write a complete Big Idea:

```text
[Result or change], which matters because [business implication];
therefore [decision or action when applicable].
```

### 3. Choose the display

Choose by what the audience must compare:

| Audience task | Preferred display |
|---|---|
| Remember one or two values | Large text |
| Look up exact values | Table |
| Compare categories or ranks | Bars or dots |
| Show a time trend | Line |
| Compare two states | Slope chart |
| Show a relationship | Scatterplot |
| Compare composition | Stacked bars |
| Explain contributions | Waterfall |
| Find a dense two-dimensional pattern | Heatmap |
| Show forecast uncertainty | Interval or band |

See [the complete chart-selection reference](skills/craft-data-story-charts/references/chart-selection.md).

### 4. Compose and focus

Use a conclusion title, a context subtitle, only the necessary evidence, direct labels, and restrained annotations. Neutralize context and reserve a deliberate accent for the primary evidence.

### 5. Render and inspect

When code is requested, the Skill requires a reproducible source file and an actual rendered artifact. The agent inspects the result at delivery size rather than approving code in the abstract.

### 6. Pass the quality gate

A chart passes only when:

- it has no hard failure;
- it scores at least **85/100**;
- Purpose & story, comprehension, and integrity each score at least **15/20**;
- the intended takeaway is the first visual stop;
- a new reader can state the result without verbal coaching.

The rubric scores:

1. Purpose & story
2. Comprehension
3. Visual hierarchy & focus
4. Aesthetics & accessibility
5. Integrity & completeness

See [the complete quality gate](skills/craft-data-story-charts/references/quality-gate.md).

## Repository structure

```text
craft-data-story-charts/
├── skills/craft-data-story-charts/
│   ├── SKILL.md
│   ├── agents/openai.yaml
│   └── references/
│       ├── chart-selection.md
│       └── quality-gate.md
├── examples/
│   └── *.png
├── README.md
├── README.zh-CN.md
├── CONTRIBUTING.md
└── LICENSE
```

## Scope

This Skill focuses on converting an established data result into an effective explanatory display. It is intentionally independent of a rendering product and suitable for reports, executive slides, dashboards, web pages, and standalone coded charts.

## Contributing

Issues and pull requests are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting.

## Acknowledgements

The methodology is an independent open-source implementation inspired by audience-first explanatory visualization and data-storytelling practice, including the principles popularized by Cole Nussbaumer Knaflic's *Storytelling with Data*. This project is not affiliated with or endorsed by the author or publisher.

## License

[MIT](LICENSE) © 2026 NINTING
