# Profile README icons

The profile uses original brand artwork for social links and Microsoft Fluent
Color icons for generic symbols. Assets are checked into this repository so the
README does not depend on an icon CDN.

## Brand assets

- `brands/github-black.svg` and `brands/github-white.svg`: unmodified Invertocat
  SVGs from the [official GitHub logo pack](https://brand.github.com/GitHub_Logos.zip),
  linked by the [GitHub Brand Toolkit](https://brand.github.com/foundations/logo).
  The README selects the white or black asset with a `picture` element.
- `brands/linkedin.png`: unmodified `LI-In-Bug.png` (635 × 540) from the
  [official LinkedIn downloads](https://brand.linkedin.com/downloads),
  [in-logo pack](https://content.linkedin.com/content/dam/me/business/en-us/amp/xbu/linkedin-revised-brand-guidelines/logos/in-logo.zip).
  The pack provides PNGs; the README displays this original at 21 × 18 pixels
  while preserving its aspect ratio.

Brand assets remain subject to their owners' trademark and usage guidelines.
They are used to link to the corresponding profile or source repository.

## Generic symbols

`fluent/*.svg` are unmodified 24px Color SVGs from
[Microsoft Fluent UI System Icons](https://github.com/microsoft/fluentui-system-icons),
pinned to commit `4c94ad5f4081168c0d45bdc368f230ecb757cd09`.
The upstream MIT license is included as `fluent/LICENSE.txt`.

The original source path is
`assets/<Title Case Icon Name>/SVG/ic_fluent_<snake_case_icon_name>_24_color.svg`.
For example, `fluent/building-store.svg` comes from
`assets/Building Store/SVG/ic_fluent_building_store_24_color.svg`.

## Choices to preserve

- Use original social marks and their brand colors; avoid stylized substitutes,
  decorative rings, pale recoloring, and illustrations of brand mascots.
- Use one family of filled, multicolor symbols for generic concepts.
- Keep email and location distinct from email-provider or map-provider logos.
- Prefer SVG; use an official high-resolution PNG when an SVG is unavailable.
- Keep visible link labels as real Markdown text, rather than converting text
  to SVG paths. Decorative images have empty alt text beside those labels.
- Keep the existing README wording and banner when changing icons.
