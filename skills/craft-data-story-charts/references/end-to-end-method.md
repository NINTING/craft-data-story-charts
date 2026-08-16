# End-to-end method

This is one continuous transformation, not a set of independent tools. Each stage changes the same Data Story Brief and constrains every later choice.

## 1. Move from exploration to explanation

Exploration asks many questions and examines the full field. Explanation selects the few findings the audience needs. Do not make the audience repeat the analysis.

Before designing, classify the task:

- **Exploration:** the answer is still open. Preserve alternative views and avoid prematurely coloring a hypothesis as truth.
- **Explanation:** the result is established enough to communicate. Select the evidence that supports understanding and action.

Keep contrary evidence, limitations, and uncertainty when they can change the audience's decision. Reducing clutter is not permission to delete inconvenient evidence.

## 2. Establish the communication context

Answer three questions before drawing:

1. **Who?** Identify the specific audience, decision maker, user, and affected group. Record prior knowledge, likely concerns, trust, and the relationship to the communicator.
2. **What?** State what the audience should understand or do. Use an action verb or another observable response rather than “see the data.” Define what successful communication looks like.
3. **How?** Define live presentation, self-contained report, email, dashboard, or mixed delivery; available time; tone; and expected interaction.

Live delivery permits controlled sequence and oral explanation. Self-contained delivery requires enough context, annotation, and detail for a reader who controls the order. If one artifact must do both jobs, design separate speaking and reading layers.

## 3. Create the central message before the chart

Use two compression passes:

- **Three-minute story:** say only what is necessary if the time were cut to three minutes.
- **Central message:** reduce it to one complete sentence containing the point, why it matters, and the benefit or response.

Then make a low-cost storyboard on paper or in plain text. Arrange the problem, evidence, explanation, alternatives, and recommendation. Do not begin with polished software: an early file creates resistance to structural change.

## 4. Select evidence and comparison

Write the primary comparison as a sentence:

```text
The audience must compare [objects] by [measure] across [time/group/state]
to understand [message] and decide [response].
```

Classify each potential item as:

- evidence required for the central message;
- necessary context, benchmark, uncertainty, or contrary evidence;
- detail for appendix or interaction;
- irrelevant to this communication.

The main view does not need all analyzed data. It does need every fact whose omission would materially change interpretation.

## 5. Choose an honest encoding

Use the most familiar encoding that makes the required comparison easy. Prefer position on a common scale, then aligned position, length, slope/direction, angle, area, volume, and color intensity.

Test the nearest alternative. Examples:

- simple text versus a two-bar chart;
- table versus heatmap;
- grouped bars versus lines for time;
- bars versus 100% stacks for absolute versus relative composition;
- direct number, bars, 100% stack, or slope for a before/after survey.

Verify zero baselines for bars, truthful time spacing, common scales for small multiples, visible units, meaningful totals, consistent signs, and distinct actual/forecast treatment.

## 6. Reduce cognitive load

Treat attention as a limited budget. Inventory every element and write its purpose. Use the sequence:

```text
remove → weaken → emphasize
```

- Remove decoration, redundant encodings, meaningless precision, unnecessary markers, and labels that do not support a task.
- Weaken necessary axes, gridlines, context series, sources, and secondary explanations.
- Emphasize the smallest amount of evidence that carries the message.

Use Gestalt structure:

- proximity for grouping;
- similarity for shared meaning;
- light enclosure for regions such as actual versus forecast;
- closure to remove unnecessary boundaries;
- continuity to support a stable reading path;
- connection only for real relationships.

Restore minimal aids when deletion prevents accurate reading.

## 7. Construct an attention hierarchy

Choose the intended first three visual stops. Begin from a neutral version, then add one dominant cue. A highlight changes not only what becomes visible but what recedes, so verify that background evidence remains recoverable.

Use position, size, contrast, weight, line width, enclosure, hue, intensity, or markers deliberately. Do not use color alone for a critical distinction. Do not use a preattentive cue to imply a quantitative order it cannot support.

Text and data must share the hierarchy: conclusion title, context, evidence, direct labels, explanatory annotations, and source. Eliminate legend lookup when labels can sit near their marks.

## 8. Make form serve function

Check the design as a product the audience must use:

- **Affordance:** the start, comparison, and next step are obvious.
- **Accessibility:** readable type, plain language, adequate contrast, redundant encodings, and appropriate precision.
- **Aesthetics:** consistent alignment, spacing, color meaning, and restraint increase patience and comprehension.
- **Acceptance:** familiar forms reduce learning cost; when a different form is better, explain its benefit and use before/after comparison or meaningful alternatives.

Beauty does not repair wrong data. Simplicity does not justify missing context. Familiarity does not excuse a chart that makes the comparison harder.

## 9. Build the narrative

Create a beginning, middle, and end:

- **Beginning:** establish audience, current state, desired state, and meaningful imbalance.
- **Middle:** show evidence, consequences, causes or drivers when supported, alternatives, and the path toward resolution.
- **End:** resolve the question, request an action, offer a recommendation, or name the decision still open.

Use titles as the horizontal spine. Reading titles alone should reproduce the story. Use vertical logic inside each view: the title's claim must be supported by its marks, labels, and annotations.

Repeat the essential message in different roles—preview, evidence, recap—without copying entire text. Reverse-storyboard the finished sequence and ask an unfamiliar reader to retell it.

## 10. Adapt, render, and iterate

Match delivery to the medium:

- live: progressive reveal and simple animation may follow spoken logic;
- self-contained: static annotations and context must replace speech;
- dark background: rebuild contrast and color choices rather than porting a light theme;
- dense multi-series: highlight one, separate into common-scale small multiples, or combine both depending on medium.

Render at delivery size. Compare variants by changing one meaningful decision at a time. Keep a rollback point. Budget time for the communication stage rather than treating a software default as the final output.

If testing fails, return to the earliest faulty stage. A wrong central message requires reframing; it cannot be repaired with typography.
