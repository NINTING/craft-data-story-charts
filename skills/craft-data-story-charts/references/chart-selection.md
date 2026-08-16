# Chart selection

Choose by the judgment the audience must make. A dataset does not own a chart type; the communication task selects the encoding.

## Selection matrix

| Audience task | Preferred display | Core rule | Common failure |
|---|---|---|---|
| Remember one or two values | Large number plus a meaning sentence | Include unit, period, and comparison | Wrapping two numbers in a decorative chart |
| Look up exact values or mixed units | Table | Align text left and numbers right/decimal; use sensible precision | Heavy boxes and undifferentiated cells |
| Find high/low patterns while retaining values | Heatmap/highlight table | Use an ordered scale with a labeled direction | Rainbow scale or ambiguous midpoint |
| See the relationship between two variables | Scatterplot | Label notable points; add a benchmark only when it answers a question | Claiming causation from association |
| Follow continuous change over time | Line chart | Preserve truthful time intervals and distinguish actual from forecast | Connecting unordered categories or labeling every point |
| Compare two states | Slope chart | Label both ends; emphasize direction and important changes | Too many crossing lines or losing category order |
| Compare category magnitude | Horizontal or vertical bars | Use a zero baseline and meaningful order | Truncated baseline or arbitrary alphabetical order |
| Show total and composition | Stacked bars | Put the most important segment on a common baseline | Expecting precise comparison of every interior segment |
| Compare relative composition across groups | 100% stacked bars | Keep segment order stable and supply totals if absolute scale matters | Treating 100% as equal sample size |
| Show positive, neutral, and negative composition | Diverging stacked bars | Define the center and explain the neutral treatment | Hiding neutral or making middle segments look precisely comparable |
| Explain contributions from start to finish | Waterfall | Distinguish start, changes, subtotals, and result | Too many small steps or unclear sign behavior |
| Rank many categories with long labels | Sorted horizontal bars | Put labels before marks and strongest priority near the top | Remote legend and arbitrary order |
| Show several time series | Highlighted line or common-scale small multiples | Highlight one for live narration; separate for full context | Undifferentiated spaghetti chart |
| Show a distribution | Histogram, box, strip, or interval plot | Explain unfamiliar summaries and sample context | Using category bars for continuous bins without explanation |
| Show geographic pattern | Map only when location matters | Normalize rates and add non-map comparison when rank matters | Mapping raw totals driven by population |
| Show forecast or uncertainty | Interval/band, error bars, fan, or annotated forecast line | Name the interval; separate estimate, range, actual, and forecast | Drawing a forecast as an equally certain continuation |

## Simple text, tables, and heatmaps

Use simple text when one or two values carry the message. Pair the value with why it matters; keep the absolute context when a relative change alone could mislead.

Use a table when readers must find particular values, compare mixed units, or choose their own focus. In live presentation, a dense table competes with the speaker; move full lookup detail to an appendix when possible.

Use a heatmap when the table's pattern matters. Keep numbers when exact lookup still matters, remove heavy borders, use an ordered scale, and label low-to-high meaning.

## Scatterplots

Use for paired observations and relationship shape. Add a mean, target, or threshold only when it turns the plot into a relevant judgment. Label notable points and preserve the full relationship context. Association is not causation.

## Lines and annotated forecasts

Use a line only for continuous or ordered sequences. Plot actual time intervals truthfully. A nonzero vertical range can be valid for small changes, but disclose the scale and avoid dramatic framing.

Direct-label line ends. Reduce markers and data labels unless they support an event, endpoint, calculation, or story turn.

For forecast:

- use a boundary between actual and forecast;
- change line style and/or use a light region;
- name any prediction or confidence interval;
- label assumptions or source in a subordinate note;
- never let estimated future values look identical to observed facts.

## Slope charts

Use for two time points or states when direction and magnitude of change matter. Label both ends and use a common scale. Highlight one important category when crossings become dense. Avoid when the audience must preserve a fixed category sequence that crossings destroy.

## Bars

- Start at zero because bar length encodes value.
- Sort by natural sequence, business process, message-relevant order, or value; record the reason.
- Prefer horizontal bars for long labels or many categories.
- Keep bars wider than gaps unless grouping requires otherwise.
- Choose either a readable axis or direct values; avoid redundant precision.

## Stacked bars

Use when both total and composition matter. Only segments that share a baseline support precise comparison. Put the segment of greatest comparative interest on the baseline or choose another display.

Use 100% stacks for relative composition. Label or accompany totals if sample size or absolute volume changes the decision.

### Positive/negative diverging stacks

Use when responses or components have meaningful negative and positive directions around a center.

1. Keep a visible zero or conceptual center.
2. Order segments consistently from negative through neutral to positive.
3. Decide and explain whether neutral is centered, split, shown to one side, or displayed separately.
4. Use position/direction plus labels; do not rely on red/green alone.
5. Direct-label the conclusion or important group difference.
6. Do not demand exact comparison of floating interior segments. Use aligned bars or a table when precise category comparison is the task.

### Positive/negative contribution stacks

For growth, loss, current base, inflow, outflow, and unmet need, keep zero visible and stack in business-semantic order. A gap encoded as outline or whitespace must have an explicit label. Negative direction must represent a real negative quantity, not a decorative mirror.

## Waterfalls

Use for start → increases/decreases → finish. Preserve signs, label the result, and make subtotal behavior clear. Order changes by business sequence or explanatory logic, not by arbitrary color.

## Horizontal priority stacks

Use when many long category labels have ordered sub-ranks such as first/second/third priority. Sort rows by total priority or an explicit business order. Use one hue with ordered lightness for rank when appropriate, and directly label totals or segments needed for interpretation.

## Area and size encodings

Area is less precise than length. Use it only for rough magnitude, part-to-whole emphasis, or very large order-of-magnitude differences. Never use decorative 3D volume for quantitative comparison.

## Pies and donuts

Do not use them as a default. They require angle, area, or arc comparison and become especially weak across several groups.

Choose the alternative by task:

- one dominant result → direct number;
- category comparison → bars;
- overall composition across groups → 100% stacked bars;
- before/after direction → slope chart.

If a pie is retained for a small, unmistakable whole, keep few slices, label directly, avoid 3D/explosion, and do not ask for precise cross-pie comparison. Avoid donuts for quantitative arc-length comparison.

## Dual axes

Avoid dual y axes because readers must map each series to a different scale and a shared x axis can manufacture a relationship. Prefer direct labels, indexed series on one comparable scale, or vertically separated charts with a shared x axis.

## Multi-view displays

- Give each view one job and one conclusion title.
- Keep scales, order, naming, and semantic color consistent.
- Arrange views in the order the audience should reason through them.
- For small multiples, share the scale required for comparison.
- Do not repeat the same evidence in a chart and table unless exact lookup is a genuine secondary need.
