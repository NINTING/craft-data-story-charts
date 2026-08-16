# Visual language

Use these rules inside the end-to-end method. They are not a separate styling tool.

## Reading path and text

Build a deliberate path:

1. conclusion title;
2. necessary context or subtitle;
3. strongest evidence;
4. direct labels and explanatory annotations;
5. source, definitions, assumptions, and limitations.

Most left-to-right readers begin near the upper left and scan across and down. Align the opening message and the strongest evidence with that path unless another cue intentionally changes it.

Use text to label, explain, emphasize, recommend, and tell the story. Do not assume the reader will infer the same conclusion. Prefer direct, plain language. Define unfamiliar terms and expand acronyms on first use.

### Typography hierarchy

- Use a conclusion, not a topic, as the main title when the evidence supports one.
- Use size and weight before adding more colors or typefaces.
- Keep body text and labels horizontal when practical.
- Use bold for strong emphasis; use italics and underlining sparingly because they are weaker or noisier.
- Keep line lengths and text blocks short enough to scan.
- Put units in headers, axes, or values where the reader needs them; do not force recall from a remote subtitle.
- Align text, axes, and plot edges to visible horizontal and vertical guides.

## Gestalt structure

- **Proximity:** use spacing to show groups before adding boxes.
- **Similarity:** keep the same series consistent across mark, label, annotation, and view.
- **Enclosure:** use a light region for a real grouping, actual/forecast split, or focus interval.
- **Closure:** remove a border when alignment and whitespace already define the whole.
- **Continuity:** preserve a smooth, truthful path across time, sequence, and aligned labels.
- **Connection:** connect only values with a real continuous, ordered, or relational meaning; connection is a strong claim.

## Remove, weaken, emphasize

### Remove by default when purposeless

- decorative 3D or perspective;
- chart frames and card shadows that do not show hierarchy;
- gradient gloss, bevels, and ornamental icons;
- repeated legends when direct labels work;
- markers and labels on every point;
- meaningless decimal precision;
- duplicated units, axes, or totals;
- angled labels and crossing annotation leaders;
- arbitrary color variation.

### Weaken when necessary

- axes, ticks, gridlines, benchmarks, context series, footnotes, and source text;
- secondary categories and historical reference;
- containers that genuinely separate regions.

Weaken with lighter value, thinner lines, smaller type, or lower visual density—not by making information unreadable.

### Emphasize deliberately

Keep emphasis small, often around one series, one interval, or a few values. Use one main cue and consistent supporting cues. If everything is bold, saturated, large, boxed, or labeled, nothing is emphasized.

## Color

- Start with neutral context and one purposeful accent.
- Keep semantic color meanings stable across a document.
- Use hue mainly for categories; do not imply that red is quantitatively larger than blue.
- Use an ordered lightness or saturation scale only when its direction is explained.
- Avoid rainbow palettes for ordered values.
- Do not rely on red versus green alone. Add label, sign, position, shape, line style, or lightness.
- Brand colors are inputs, not overrides. If a brand color lacks contrast or conflicts with meaning, select a readable alternative.
- Color carries emotion; match the seriousness and context of the message.

On dark backgrounds, rebuild the palette from the background outward. White and bright colors become stronger; a palette that worked on white may become harsh or illegible. Prefer a light background when no meaningful constraint requires dark.

## Fill, shading, shadows, and borders

Distinguish four different roles:

1. **Decorative shadow:** drop shadows, glow, bevel, or pseudo-depth. Remove unless it carries necessary interface hierarchy.
2. **Structural fill:** a light background that groups related items. Keep only when whitespace cannot communicate the grouping clearly.
3. **Data interval:** confidence band, forecast interval, acceptable range, or distribution envelope. This is data; retain it, label its meaning, and keep it subordinate to the estimate.
4. **Context region:** actual versus forecast, before versus after, event window, target band, or missing gap. Use light enclosure and a direct label.

Do not delete a data interval under a generic “remove shading” rule. Do not add decorative shadow under a generic “make it polished” rule.

## Position, size, and quantitative meaning

Use position and length for precise comparison when possible. Size and area can show rough magnitude but are harder to judge. Never use volume or 3D perspective for ordinary quantitative comparison.

Page area implies importance. Give equally important views comparable space. Do not enlarge a chart simply to fill a page. Use whitespace to separate, pace, and emphasize.

## Labels and legends

- Direct-label important lines, bars, points, intervals, and targets near the data.
- Keep only values necessary for comparison, calculation, endpoint recognition, or action.
- When direct labels collide, change layout, reduce series, use small multiples, or retain a concise legend.
- Keep labels and marks consistent in color, wording, and order.
- Put annotations next to the evidence they explain and state why it matters.

## Accessibility check

- Read at actual delivery size.
- Check contrast and grayscale distinguishability.
- Use a second encoding for critical distinctions.
- Use readable, consistent fonts and plain language.
- Preserve units, source, assumptions, and necessary context.
- Do not over-round when precision changes the decision; do not show meaningless precision when it does not.
