# Quality checks

The released spritesheet passed v2 structural validation and visual review.

- The RGBA WebP measures 1536 × 2288, arranged in eight columns and eleven rows.
- Unused cells are transparent, with no residual RGB data beneath fully transparent pixels.
- Animations preserve the character's proportions, oversized ears, guitar, tie, and outfit details.
- The four cardinal gaze directions passed three independent blind reviews; the complete sixteen-direction loop was also inspected frame by frame.
- Transparent edges received one shared cleanup pass. The later jump-to-wave replacement reused the cleaned frames without applying another edge treatment.
- Replacement frames match their source waving frames pixel for pixel. The other ten rows are unchanged.

## Accepted minor variations

At 067.5°, 112.5°, 247.5°, and 292.5°, the gaze is close to horizontal and the upward or downward component is subtle. Independent paired reviews disagreed on 247.5° and 292.5°; review of the complete ordered loop accepted these as minor variations.

The silhouette opens slightly at the transition from 337.5° to 000°. Full-loop review found no conspicuous jump. Gaps between the legs, clothing, and guitar are natural negative space.

## Inspection records

- [Atlas validation](../qa/atlas-validation.json)
- [Gaze direction review](../qa/direction-semantics.json)
- [Gentle action replacement validation](../qa/gentle-action-validation.json)
- [Asset metadata and SHA-256](../qa/manifest.json)
