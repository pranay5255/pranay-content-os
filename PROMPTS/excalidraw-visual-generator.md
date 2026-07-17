# Prompt: Excalidraw Visual Brief Generator

Turn a technical post into a precise, hand-drawn Excalidraw visual plan. The diagram must teach the core idea rather than decorate the post.

## Input

```text
POST OR BLOG:
[paste draft]

PRIMARY READER:
[AI researcher / data scientist / intermediate practitioner]

PLATFORM:
[X / LinkedIn / blog]
```

## Task

Select the clearest diagram type:

- Architecture or system flow
- Experiment or evaluation pipeline
- Before/after comparison
- Concept map
- Decision tree
- Method-versus-baseline comparison
- Annotated chart or result explanation

Use a 16:9 canvas for social posts unless a platform-specific crop requires otherwise. Use a white or warm off-white background, charcoal hand-drawn strokes, and a limited pastel palette.

Semantic palette:

- Light blue: input, premise, or source data
- Light purple: model, processing, or method
- Light green: validated output or desired result
- Light orange: external dependency or warning
- Light red: failure, confounder, or invalid conclusion
- Light yellow: caveat, decision, or open question
- Light teal: storage, dataset, or evidence

## Required output

```text
TEACHING GOAL
[one sentence describing what the reader should understand]

DIAGRAM TYPE
[type and why it is appropriate]

CANVAS
- Aspect ratio:
- Background:
- Reading direction:
- Safe margins:

ELEMENTS IN DRAWING ORDER
1. [shape, position, fill color, exact label]
2. [bound text or annotation]
3. [arrow direction and optional label]
...

HIERARCHY
- Primary focal point:
- Secondary detail:
- Caveat/failure emphasis:

TEXT RULES
- Title:
- Exact node labels:
- Maximum words per node:
- Minimum readable font size:

NEGATIVE CONSTRAINTS
- No photorealism
- No 3D rendering
- No gradients
- No decorative icons that do not encode meaning
- No tiny labels or dense paragraphs
- No invented metric, result, logo, citation, or profile handle
- No misleading causal arrows

ALT TEXT
[concise but complete description for a reader who cannot see the image]

OPTIONAL EXCALIDRAW JSON NOTES
- Use valid shape/text container bindings.
- Use fontFamily 1 for the hand-drawn style.
- Keep body labels at least 16px and headings at least 20px.
- Prefer fewer, larger elements with 20–30px gaps.
```

## Quality test

Reject and redesign the visual if any answer is “no”:

1. Can the reader understand the thesis without reading the post?
2. Does every arrow have a defensible meaning?
3. Is the limitation or failure mode visible when it matters?
4. Can every label be read on a phone?
5. Does the visual avoid claims not supported by the post?
