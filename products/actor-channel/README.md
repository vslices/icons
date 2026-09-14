# ActorChannel icon

![ActorChannel product mark](./icon-128.png)

ActorChannel uses the official VSlices icon as the primary visual material and extends it with a secondary graphical expression of the product.

The product expression is a channel between two endpoints: two nodes connected by a shared transport line. It represents explicit, human-authorized transport and handoff between actors while keeping the VSlices mark visually dominant and immediately recognizable.

The intended reading order is:

`VSlices first -> ActorChannel expression second`

## Current expression

The channel keeps a simple `1 : 1` composition: one endpoint on each side of a shared transport line. Although ActorChannel can coordinate multiple handoffs, the product mark intentionally represents that capability through the channel itself rather than by drawing multiple branches. This keeps the mark balanced and legible at extension-icon sizes.

The current channel palette transitions from blue to cool gray:

- blue represents an active origin / transport entry point;
- cool gray represents the receiving endpoint without competing visually with the official VSlices purple;
- the center ring acts as the explicit handoff / authorization point, reflecting the current interaction model in which the user deliberately triggers transport.

The blue-to-gray treatment is intentionally quieter than earlier blue-to-purple, blue-to-red, blue-to-pink, or multi-branch explorations. Its purpose is to preserve visual hierarchy: the VSlices glyph remains the first thing the eye reads, while the channel explains what ActorChannel does.

## Composition rule

The official VSlices glyph must remain the principal and recognizable element of the mark. The channel motif may add context, but it must not replace, hide, distort, or visually dominate the official glyph.

This follows the repository-wide product icon rule:

`official VSlices icon + graphical expression of the product`

## Files

- `icon.svg` — canonical vector source for the ActorChannel product mark.
- `icon-16.png` — Chromium toolbar size.
- `icon-32.png` — high-density toolbar / small UI size.
- `icon-48.png` — extension management UI size.
- `icon-128.png` — extension store / large metadata size and README preview.

Product repositories may copy the generated assets locally when required by packaging or runtime tooling. Update this canonical source first when the mark changes.
