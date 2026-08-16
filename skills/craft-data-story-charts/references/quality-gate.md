# Quality gate

Inspect the rendered artifact at its actual delivery size. This gate checks the complete transformation—not only whether the chart looks polished.

The hard failures, inspection protocol, numerical rubric, and 85-point threshold are AI-production extensions of the book-derived method. See [Methodology map](methodology-map.md).

## Gate 1: communication chain

Before scoring, state each link in one line:

```text
Audience → desired response → central message → necessary evidence
→ primary comparison → chosen encoding → attention order → narrative position
```

If a link is missing or contradictory, return to the earliest faulty stage. Do not repair a context or message problem with visual polish.

## Gate 2: hard failures

Any one blocks delivery:

1. No identifiable audience, desired response, central message, or comparison.
2. The title names a topic when the evidence supports a decision-relevant conclusion.
3. Necessary context, contrary evidence, uncertainty, metric, unit, population, period, or comparison is missing enough to change interpretation.
4. The selected display makes the required comparison harder than a familiar alternative without a defensible reason.
5. A bar uses a misleading nonzero baseline; time spacing is false; scales, signs, totals, or ordering contradict the supplied values.
6. 3D, perspective, area, volume, dual axes, color, or animation manufactures a relationship the data does not support.
7. Decoration, dense labels, competing colors, borders, shadows, or backgrounds obscure the evidence or reading path.
8. A data-bearing interval, forecast boundary, target, uncertainty cue, or essential reference was removed as “clutter.”
9. Critical series require difficult legend lookup, or text and marks are unreadable at delivery size.
10. Color is the only carrier of a critical distinction or fails the intended viewing conditions.
11. The intended first visual stop and story sequence cannot be identified.
12. A self-contained artifact depends on missing oral explanation, or a live visual is too dense to follow at speaking pace.
13. The result overstates causality, certainty, precision, recommendation, or generality.
14. The output is code-only when the environment can render the requested artifact.

## Gate 3: audience tests

Run these on the rendered result:

1. **Five-second retelling:** after a brief look, can a new reader state the central message?
2. **Desired-response test:** is the next understanding, decision, or action evident?
3. **Eye-draw test:** do the first three fixations match the intended attention order?
4. **Comparison test:** can the reader perform the primary comparison without mental reconstruction?
5. **Grayscale test:** do critical distinctions survive without hue?
6. **Thumbnail test:** do hierarchy and the main comparison survive reduction?
7. **Title-only test:** in a sequence, do titles alone reproduce the argument?
8. **Vertical-logic test:** does every mark and word support its view's title?
9. **Medium test:** does the artifact work without speech when distributed, or at speaking pace when presented live?
10. **Value trace:** verify representative values, signs, totals, order, labels, scales, and intervals against the supplied data.

## Gate 4: scoring rubric

Score each category from 0 to 20.

### 1. Context, purpose, and message — 20

- 0–5: data dump or invented context; no audience use.
- 6–10: topic is visible but desired response or stakes are vague.
- 11–14: conclusion exists but audience fit, implication, or context is incomplete.
- 15–17: clear audience, result, implication, and appropriate response.
- 18–20: one unmistakable message connects the audience's situation to a supported decision or action.

### 2. Evidence, comparison, and integrity — 20

- 0–5: values or encoding are wrong or misleading.
- 6–10: evidence is incomplete, comparison is laborious, or context is questionable.
- 11–14: accurate but missing a helpful benchmark, uncertainty cue, or clear comparison.
- 15–17: evidence, scales, units, intervals, and encoding honestly support the message.
- 18–20: the minimum sufficient evidence makes the intended comparison effortless without implying more than the data supports.

### 3. Cognitive load and attention — 20

- 0–5: cluttered; no hierarchy; many competing focal points.
- 6–10: some emphasis, but defaults and unnecessary elements compete.
- 11–14: mostly clear with minor legend, label, grouping, or reading-order friction.
- 15–17: context recedes, structure is evident, and key evidence dominates through restrained cues.
- 18–20: first, second, and third visual stops reproduce the intended reasoning path exactly.

### 4. Design, text, and accessibility — 20

- 0–5: broken, crowded, inconsistent, inaccessible, or dependent on decoration.
- 6–10: functional but weak in typography, spacing, contrast, alignment, or language.
- 11–14: clean with minor accessibility or hierarchy issues.
- 15–17: polished, readable, aligned, restrained, and usable in the intended medium.
- 18–20: text and visual form operate as one coherent, accessible explanation.

### 5. Story, medium, and completeness — 20

- 0–5: no sequence or unresolved communication.
- 6–10: isolated statistic or speaker-dependent artifact with missing context.
- 11–14: logical result but weak beginning/end, title spine, or medium adaptation.
- 15–17: coherent narrative, explicit resolution, and sufficient standalone or live-delivery support.
- 18–20: every view advances the audience from context through evidence to a clear resolution with no redundant detour.

## Pass rule and revision

Pass only when:

- there is no hard failure;
- total score is at least **85/100**;
- Context/purpose/message, Evidence/comparison/integrity, and Cognitive load/attention each score at least **15/20**;
- audience retelling matches the central message.

Record:

```text
Hard failures: none | [list]
Context, purpose, and message: __/20
Evidence, comparison, and integrity: __/20
Cognitive load and attention: __/20
Design, text, and accessibility: __/20
Story, medium, and completeness: __/20
Total: __/100
Audience retelling: [sentence]
Verdict: PASS | REVISE
Required revisions: [none or concise list]
```

Do not inflate a score. Revise the earliest faulty stage, render again, then repeat the gate once on the revised artifact.
