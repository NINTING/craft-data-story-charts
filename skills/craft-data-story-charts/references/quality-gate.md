# Quality gate

Review the rendered artifact at its actual delivery size. A chart passes only when it has no hard failure, scores at least 85/100, and earns at least 15/20 in Purpose & story, comprehension, and integrity.

## Hard failures

Any one of these blocks delivery:

1. The chart has no identifiable audience use, comparison question, or takeaway.
2. The title is merely a topic when the data supports a conclusion.
3. The metric, unit, population, period, or comparison is ambiguous enough to change interpretation.
4. A bar chart uses a nonzero baseline that materially exaggerates differences.
5. Decorative 3D, perspective, area, or volume distorts the encoded values.
6. Dual axes or incompatible scales create a visually manufactured relationship.
7. The chart contradicts the underlying supplied values, ordering, signs, totals, or labels.
8. Important series cannot be identified without difficult legend lookup or guesswork.
9. Text, labels, or marks are unreadable at the intended delivery size.
10. Color is the only carrier of a critical distinction and fails common color-vision conditions.
11. Several equally strong colors or elements make the intended first visual stop indeterminate.
12. The output is code-only even though the environment can render the requested chart.

## Scoring rubric

Score each category from 0 to 20.

### 1. Purpose & story — 20

- 0–5: data dump; no conclusion or audience use.
- 6–10: a topic is visible but the implication is vague.
- 11–14: conclusion exists but action, stakes, or narrative order is weak.
- 15–17: clear result, relevant implication, and logical evidence.
- 18–20: one unmistakable Big Idea; title, annotation, and sequence work together to drive understanding or action.

### 2. Comprehension — 20

- 0–5: requires substantial verbal explanation.
- 6–10: interpretable with effort, repeated legend lookup, or specialist assumptions.
- 11–14: mostly clear with minor friction.
- 15–17: comparison, labels, units, and reading order are immediately clear.
- 18–20: a new reader can accurately state the result in seconds and find supporting values without confusion.

### 3. Visual hierarchy & focus — 20

- 0–5: no hierarchy or many competing focal points.
- 6–10: some emphasis, but defaults and clutter still compete.
- 11–14: intended focus is visible but not decisive.
- 15–17: context recedes and the key evidence dominates through restrained preattentive cues.
- 18–20: first, second, and third visual stops match the intended reasoning path exactly.

### 4. Aesthetics & accessibility — 20

- 0–5: visibly broken, crowded, inconsistent, or inaccessible.
- 6–10: functional but default-looking or poorly balanced.
- 11–14: clean with minor typography, spacing, contrast, or color issues.
- 15–17: polished alignment, whitespace, typography, palette, and readable contrast.
- 18–20: exceptionally coherent and refined while remaining restrained and accessible.

### 5. Integrity & completeness — 20

- 0–5: values, scale, labels, or comparisons are misleading or wrong.
- 6–10: important context is missing or encoding is questionable.
- 11–14: accurate but missing a helpful baseline, source, note, or uncertainty cue.
- 15–17: values, scale, units, time, and visual encoding faithfully support the conclusion.
- 18–20: complete standalone context, transparent comparison, and no visual implication beyond what the displayed values support.

## Inspection tests

Perform these tests on the rendered output:

1. **Five-second test:** look briefly, then state the takeaway. It should match the Big Idea.
2. **Eye-draw test:** look away and back. The first fixation should be the conclusion title or strongest evidence.
3. **Grayscale test:** critical distinctions should remain identifiable without hue.
4. **Thumbnail test:** hierarchy and primary comparison should survive reduction, even if fine labels do not.
5. **Title-only test:** for a multi-view sequence, titles alone should tell the story.
6. **Vertical-logic test:** every item in a view should support its title; move unrelated detail to an appendix or remove it.
7. **Value trace:** verify a representative sample of plotted values, totals, signs, labels, and order against the source data.

## Review report

Record:

```text
Hard failures: none | [list]
Purpose & story: __/20
Comprehension: __/20
Visual hierarchy & focus: __/20
Aesthetics & accessibility: __/20
Integrity & completeness: __/20
Total: __/100
Verdict: PASS | REVISE
Required revisions: [none or concise list]
```

Do not inflate the score to pass an artifact. Revise the artifact, then score the rendered revision again.
