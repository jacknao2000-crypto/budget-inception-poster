---
name: budget-inception-poster
description: Create or edit vertical surreal photographs that preserve an ordinary seated person and real platform along the lower edge while attaching a monumental upside-down thematic world to the top, separated by a large atmospheric void. Use for “低配版盗梦空间”, Budget Inception, fake tourist check-in images, inverted-world posters, anti-gravity composites, or requests to upload a person photo and specify or randomly select an overhead dream world.
---

# Budget Inception Poster

Create a deliberately fabricated tourist photograph from one mundane reality layer and one impossible spectacle layer. Keep the result photographic, restrained, and faintly satirical rather than purely beautiful fantasy.

Use the built-in image-generation tool. Treat an uploaded photo as the edit target. If no suitable photo exists, ask for a vertical photo with a seated person near a hard platform edge and ample empty space above.

## Choose a mode

- **Specified dream:** Use the user's named subject for the upside-down world.
- **Random dream:** When no subject is given, choose one strong theme from `references/dream-themes.md`. Prefer the theme with the strongest contrast against the person's ordinary clothes and setting. Do not ask the user to choose unless the request is otherwise blocked.

## Lock the reality layer

Preserve the entire lower portion of the source photo with high fidelity:

- Keep the person's identity, face, hair, clothing, pose, hands, legs, gaze, scale, and shadow.
- Keep the platform, paving, diagonal edge, camera angle, crop, and aspect ratio.
- Keep the person ordinary and unheroic. Do not restyle them as a fashion model, explorer, or science-fiction character.
- Do not add a photographer, phone UI, queue, signage, selfie stick, frame, text, logo, or watermark.

If the source lacks an obvious platform edge, retain its closest hard real-world boundary. Do not fabricate a glossy runway.

## Build the dream layer

Change only the empty upper region:

1. Construct one coherent, monumental thematic world.
2. Rotate that whole world 180 degrees and attach it firmly to the top edge.
3. Let its recognizable forms hang downward. Preserve structural detail, weight, and scale.
4. Keep a broad pale sky, mist, air, or otherwise quiet void between the upper world and the person.
5. Match the source daylight and photographic perspective while allowing a subtle composited seam between mundane reality and impossible spectacle.

The upper world should normally occupy 25–35% of the frame, the open void 40–50%, and the fixed reality layer the remainder. Adapt only when the source composition requires it.

## Preserve the central idea

Aim for this relationship:

> an ordinary person at a cheap real photo spot + an impossibly grand virtual destination

The satire comes from the mismatch. Do not turn the image into a conventional science-fiction scene, fantasy portal, polished fashion editorial, or decorative poster. Keep the person visibly grounded in everyday reality while the upper world is spectacular enough to feel manufactured for a photograph.

## Prompt pattern

State the edit invariants before describing the theme:

```text
Preserve the complete lower reality layer: the same person, pose, clothing,
shadow, platform, diagonal edge, camera angle, crop, and aspect ratio.
Change only the large empty upper region.

Attach a monumental upside-down [THEME] to the top edge as one coherent
world. Keep a broad pale atmospheric void between it and the person.
The result is a believable but deliberately impossible tourist photograph:
ordinary reality below, fabricated spectacle above.

No text, logo, watermark, additional people, UI, selfie stick, portal,
glossy runway, or decorative graphics.
```

Expand `[THEME]` with 4–8 recognizable physical features, material cues, and a restrained palette. Do not add unrelated story elements.

## Validate the output

Regenerate or make one targeted edit if any condition fails:

- The person or platform changed materially.
- The upper world is upright, floating loose, or not connected to the top edge.
- The middle has lost its large empty buffer.
- The image reads only as beautiful fantasy and lacks the real/virtual mismatch.
- Added text, people, props, borders, interfaces, or obvious visual effects appear.
- The upper subject is too small or generic to recognize.

For iteration, change only the failed relationship. Do not redesign successful parts.
