---
name: analyze-viral-video
description: Analyze short-form product videos with the user's “viral scene × product × viral angle” method. Use when Codex receives a video, keyframes, script, or scene description and must judge whether the content is worth copying, distinguish validated viral material from unverified tests or operator self-entertainment, extract reusable scene and camera-angle components, or produce a concrete remake plan.
---

# Analyze Viral Video

Analyze every submitted video as a new category and an independent sample. Do not compare it with earlier videos unless the user explicitly requests comparison.

## Core model

Apply this formula:

> Viral material = viral scene × product × viral angle

Treat the multiplication sign as a compatibility requirement:

- Require the scene to attract a specific audience or desire.
- Require the product to belong naturally in that scene.
- Require the angle to reveal the product, create anticipation, or prove an effect.
- Require all three components to target the same person.

Do not mistake subtitles, transitions, props, trending music, many products, or generic questions for the core viral components. They are supporting devices only.

## Workflow

1. Inspect the complete video or evenly sampled keyframes. Separate recording artifacts from the source video.
2. Identify the primary product. If the visual focus could indicate two products, give a conditional verdict for each rather than guessing.
3. Extract the scene:
   - environment and time;
   - character identity and life state;
   - clothing, manicure, accessories, materials, lighting, and background;
   - hidden social meaning and target desire.
4. Extract the angle:
   - framing and camera position;
   - hand or body movement;
   - reveal, comparison, transformation, try-on, or proof mechanism;
   - reason a viewer waits for the next frame.
5. Test scene-product-angle compatibility.
6. Classify evidence and state uncertainty.
7. Give a decisive copy verdict and, when appropriate, a practical remake plan.

Read [references/decision-rules.md](references/decision-rules.md) when deciding evidence level, identifying operator self-entertainment, or writing the final verdict.

## Evidence discipline

Distinguish content logic from performance proof:

- Call material “validated viral” only when reliable performance data or explicit user confirmation supports it.
- Call material “testable” when the three components fit but performance is unknown.
- Call material “operator self-entertainment” when forms look complete but no clear user desire or compatible scene exists.

Never infer virality from visual polish alone. Never soften a weak result merely because the video contains a transition or interaction prompt.

## Output

Lead with exactly one verdict:

- **Can copy**
- **Replace one component, then test**
- **Do not copy**

Then report:

1. **Viral scene** — name it and explain the audience and hidden meaning.
2. **Product** — explain why it fits or conflicts.
3. **Viral angle** — describe the reusable framing and action.
4. **Compatibility** — state whether all three target the same person.
5. **Viewer motivation** — explain why a viewer stops and waits.
6. **Reusable library components** — list only components worth saving.
7. **Remake plan** — provide concrete steps only for “Can copy” or “Replace one component, then test.”

Keep the analysis product-focused. Do not pad the answer with generic hooks, captions, or imagined benefits that are not visible or user-supplied.
