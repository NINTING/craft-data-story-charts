# Chart selection

Choose a display by the audience's primary comparison task. A dataset can support several chart types; the intended judgment determines the correct one.

## Selection matrix

| Audience task | Preferred display | Design rules | Common failure |
|---|---|---|---|
| Remember one or two values | Large text with a short statement | Show unit, period, and comparison | Wrapping a single number in a decorative chart |
| Look up exact values | Table | Align numbers, limit precision, highlight only important cells | Heavy cell borders and indiscriminate conditional color |
| Find patterns while retaining values | Highlight table or heatmap | Use an ordered scale and label its meaning | Rainbow palette or ambiguous color midpoint |
| Compare categories | Horizontal or vertical bars | Use a common zero baseline and meaningful order | Truncated baseline or arbitrary alphabetical order |
| Rank many categories | Sorted horizontal bars or dot plot | Put labels beside marks; emphasize relevant ranks | Rotated labels and a remote legend |
| Compare actual with target | Bars or dots with a reference marker | Label target and variance directly | Separate gauges that prevent comparison |
| Show a time trend | Line chart | Keep time continuous; annotate events and endpoints | Markers and labels on every point |
| Compare two states | Slope chart | Label both ends and emphasize direction | Too many crossing series |
| Compare several time series | Highlighted line, small multiples, or heatmap | Focus one or a few; hold scales constant in small multiples | An undifferentiated spaghetti chart |
| Show a relationship | Scatterplot | Label notable points; add reference line only when meaningful | Claiming causation from visual association |
| Show a distribution | Histogram, box plot, strip plot, or interval plot | Explain unfamiliar summaries; show sample context | Using a bar chart for binned continuous data without clear bins |
| Compare part-to-whole across groups | 100% stacked bars | Keep segment order and colors consistent; show sample size if relevant | Multiple pies that require angle comparison |
| Show total and composition | Stacked bars | Put the segment of greatest comparative interest on a common baseline | Expecting precise comparison of all interior segments |
| Show positive and negative composition | Diverging stacked bars | Use a meaningful center and label direction | Treating neutral responses as positive or negative without explanation |
| Explain contributions from start to finish | Waterfall | Distinguish start, changes, and result; order contributions logically | Too many small steps or unclear subtotal behavior |
| Explain a process or funnel | Ordered bars or stages | Preserve stage order and show conversion or loss explicitly | Decorative funnel area that distorts values |
| Show geographic pattern | Map only when location is analytically relevant | Use a suitable rate or normalized metric; include non-map comparison when rank matters | Mapping raw totals driven by population size |
| Show uncertainty | Interval, band, error bar, or fan chart | Name the interval and distinguish estimate from range | Showing a forecast as an equally certain continuation |

## Encoding priority

When several encodings can express the same comparison, prefer:

1. position on a common scale;
2. position on separate but aligned scales;
3. length;
4. direction or slope;
5. angle;
6. area;
7. volume;
8. color saturation.

This is a preference, not a ban. Depart when the business meaning or medium makes another encoding substantially clearer.

## Form-specific rules

### Bars

- Start the quantitative baseline at zero because bar length encodes value.
- Sort by value for ranking, by time for chronology, or by business order for a process.
- Prefer horizontal bars for long labels or many categories.
- Make bars wider than the gaps between them unless a special grouping requires otherwise.

### Lines

- Use for continuous sequences, especially time.
- A nonzero vertical range may be valid when small changes matter, but show the scale clearly and avoid dramatic framing.
- Direct-label line ends where possible.
- Distinguish forecast from actual with line style, shading, or a clearly marked boundary.

### Stacks

- Use when part-to-whole meaning matters.
- Only the segments sharing a baseline support precise comparison. Place the segment of greatest interest on that baseline or choose another chart.
- Use 100% stacks for composition only; provide totals separately if absolute scale matters.

### Pies and donuts

- Use only for a small number of segments forming a meaningful whole when the conclusion is coarse, such as one segment being clearly dominant.
- Do not use for precise comparisons, many segments, comparisons across several groups, or values that do not sum to a meaningful whole.
- Never use 3D or exploded slices.

### Tables

- Use when exact lookup is more important than pattern recognition.
- Align text left and numbers right or by decimal point.
- Use sensible precision and place units in headers instead of repeating them in every cell.
- Use whitespace and light rules instead of boxing every cell.

## Multi-view displays

- Give each view one job and one conclusion title.
- Use consistent scales, order, naming, and semantic colors across views.
- Arrange views in the order the audience should reason through them.
- Do not repeat the same evidence in a chart and table unless exact lookup is a genuine secondary need.
