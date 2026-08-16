---
name: craft-data-story-charts
description: Turn raw or summarized data into clear, elegant, audience-centered explanatory charts that communicate a business result, conclusion, recommendation, or action. Use whenever an agent must design, generate, improve, or review a data chart, graph, dashboard view, report visual, slide visual, or coded visualization, regardless of the rendering software or programming language.
---

# Craft Data Story Charts

Create explanatory data displays whose conclusion is immediately understandable, visually polished, and supported by the displayed data. Stay independent of any specific charting tool: choose the available language, library, or application that best fits the requested artifact.

## Required references

Before designing or reviewing a chart, read these files completely:

- [Chart selection](references/chart-selection.md): choose the display from the audience's comparison task.
- [Quality gate](references/quality-gate.md): use the hard failures and scoring rubric before delivery.

## Operating contract

- Optimize the chart for communication, not for showing how much analysis was performed.
- Treat exploratory analysis as preparation. Present only the explanatory result and the evidence needed to understand it.
- Design for a named audience, decision, or business use. Never design for "everyone."
- Make one primary takeaway dominant. Supporting context may remain visible but must recede.
- Use words and charts together. A chart is evidence inside a message, not the whole message by itself.
- Preserve truthful magnitude and comparison. Never use decoration or scaling that visually contradicts the values.
- Prefer familiar, precise encodings over novelty. Use position and length before angle, area, volume, or animation when they serve the same task.

## Workflow

Complete the design as one coherent pass, then render and inspect it at the quality gate.

### 1. Establish the communication contract

Determine from the request and data:

- **Audience:** the specific role or group who will use the chart.
- **Decision or use:** what they must decide, understand, approve, change, or monitor.
- **Primary question:** the comparison the chart must make easy.
- **Medium:** live presentation, written report, dashboard, web page, or standalone image.
- **Required context:** metric definition, unit, time range, baseline, target, forecast, or source.

Infer low-risk missing details from the business domain and state them briefly. Ask only when a missing fact would materially change the message or chart type.

### 2. Extract the result

Inspect the data and identify the strongest decision-relevant pattern: change, gap, rank, relationship, distribution, composition, contribution, or exception.

Write a one-sentence **Big Idea** before drawing:

`[Result or change], which matters because [business implication]; therefore [decision or action when applicable].`

The Big Idea must be a complete point of view, not a topic such as "Quarterly revenue" or "Survey results."

### 3. Choose the display

Use the primary comparison task—not the data format or software default—to select the chart. Follow [Chart selection](references/chart-selection.md).

Default to the simplest effective form:

- one or two important values → large text;
- exact lookup → table or highlighted table;
- category comparison or ranking → bars or dots;
- time trend → line;
- two-state change → slope chart;
- relationship → scatterplot;
- part-to-whole comparison → stacked bars;
- cumulative contributions → waterfall;
- dense two-dimensional pattern → heatmap.

Avoid 3D decoration and dual axes. Use pie or donut charts only for a small, unmistakable part-to-whole message where precise comparison is not required.

### 4. Compose the message

Build the visual in this order:

1. **Conclusion title:** state the takeaway in plain language.
2. **Context subtitle:** define metric, unit, population, time range, or comparison when needed.
3. **Plot:** show only evidence relevant to the primary question.
4. **Direct labels and annotations:** identify important series, values, events, targets, or gaps near the data.
5. **Source or note:** include it when the artifact must stand alone or the input provides one.

Use horizontal logic across a multi-chart sequence: reading titles alone must tell the story. Use vertical logic within each view: every mark, label, and annotation must reinforce its title.

### 5. Create visual hierarchy

- Render context in neutral tones and the primary evidence in one deliberate accent color.
- Keep each semantic color consistent across the artifact.
- Use color, size, weight, enclosure, and position sparingly to control the first, second, and third visual stops.
- Group related items through proximity, similarity, alignment, or light enclosure.
- Use whitespace to separate groups and replace unnecessary borders.
- Direct-label important series when practical; do not force legend-to-mark lookup.
- Remove chart borders, decorative backgrounds, redundant legends, excessive gridlines, unnecessary markers, repeated units, and labels that do not aid the comparison.
- Retain faint reference lines, axes, and labels when they are necessary for accurate reading.
- Make text readable at the artifact's actual delivery size and ensure sufficient contrast.
- Do not rely on red-versus-green alone; reinforce meaning with position, labels, lightness, shape, or line style.

### 6. Generate the artifact with code when requested

- Write a reproducible source file that reads or embeds the supplied data and produces the final chart.
- Keep business meaning—labels, units, ordering, annotations, and takeaway—explicit in the code.
- Choose output formats appropriate to the medium; prefer SVG or another vector format when supported, plus PNG when convenient for inspection.
- Size the canvas for the target medium rather than accepting a library default.
- Keep implementation complexity proportional to the chart. Do not introduce a framework when a small script is enough.
- Render the final artifact. Do not deliver code without the generated chart unless execution is impossible.

### 7. Inspect and pass the quality gate

Inspect the rendered artifact at actual size, not only the code. Apply [Quality gate](references/quality-gate.md).

Revise until:

- there are no hard failures;
- the score is at least 85/100;
- Purpose & story, comprehension, and integrity each receive at least 15 points;
- the first visual stop is the intended takeaway or its strongest evidence;
- a new reader can state the result without verbal coaching.

If a requested constraint prevents a passing design, preserve the constraint and report the exact quality tradeoff.

## Delivery

Provide:

- the rendered chart;
- the reproducible code or editable source when requested;
- the one-sentence takeaway;
- only the few design decisions needed to explain non-obvious choices;
- the quality-gate result, including any remaining constraint-driven tradeoff.

Do not bury the artifact under a long methodology explanation.
