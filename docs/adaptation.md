# Adaptation notes

Both modes follow the official Everforest Light and Dark palettes at the default medium contrast, which are available in the Codex theme family. The source repository does not declare a separate palette package version; this draft pins its source to the immutable commit below. Tine surface roles are mapped independently, and documented light text and tag adjustments support contrast on the package's declared surfaces.

## Sources

- palette: https://github.com/sainnhe/everforest/blob/85a86eb62409e3ec88713bff3d1b9d7374e112e4/palette.md
- license: https://github.com/sainnhe/everforest/blob/85a86eb62409e3ec88713bff3d1b9d7374e112e4/LICENSE
- Codex pairing: Everforest Light and Everforest Dark, using upstream light and dark medium variants.

## Mapping decisions

- Uses official default medium contrast: light bg0 #FDF6E3 and dark bg0 #2D353B, with official foreground and accent families.
- Tine's stepped surfaces, selection and code backgrounds are semantic adaptations using adjacent Everforest background tones. Light inline code uses bg1 (#F4F0D9) so its text remains readable.
- Light secondary text is deepened to #68767D; links use the official deeper pine-blue #286983; tags are deepened to #5D7410. These mappings keep the checked text roles above 4.5:1 on the fixture's declared surfaces.
- Dark text roles, links and tags follow the upstream foreground, aqua/blue and green families. Amber marks are a Tine adaptation with explicit foreground.
- The 21-token theme API does not control fonts, task markers, arbitrary hover rules or every syntax color; no exact Codex UI reproduction is claimed.

## Local validation

See the [local check summary](local-check.md) for the exact tested combinations and current manifest digest. User screenshots and full Tine interaction acceptance are pending.

Release 0.1.1 retains the tested 0.1.0 color tokens and adds publication metadata and pinned screenshots.

See the [local check summary](local-check.md) for the exact tested combinations and manifest digest.
