# Transport Cart Graphics

These SVGs are the **canonical design diagrams** for the current transport-cart concept. They intentionally replace the earlier generative concept renders as the reliable visual reference because those renders repeatedly distorted the R6, Pelican, NANUK, and tool-roll locations.

## Canonical diagrams

- `geometry_top_view.svg` — exact proportional relationship of the R6RT frame, Pelican Air 1595, and deployed NANUK 935. Use this first when constructing CAD or a generative-image blockout.
- `vertical_modes.svg` — seated and standing main-top indices, open-Pelican clearance, rear heavy-roll stand-off, and upper laptop/reference plane.
- `tool_docking_layout.svg` — operator-side perimeter toolbelt, upper Pelican small-tool roll, opposite/rear NANUK-derived heavy roll(s), waste/sorting side, and low NANUK end dock.
- `weight_architecture.svg` — 45–48 lb target / 50 lb ceiling philosophy for Pelican, NANUK, and cart package.

## Raster concept renders

The source discussion produced a number of raster concept renders. They remain useful as ideation history but are **not canonical** because at various points they:

- shrank the NANUK 935;
- rotated or hinged the NANUK incorrectly;
- shrank the Pelican Air 1595 to fit the R6 frame;
- placed heavy tool rolls on the waste/sorting side;
- omitted the rear heavy Site Ops roll;
- invented heavy full-width drawers or generic mechanic-cart structures.

Agents should use the SVGs and `../README.md` as the source of truth, and treat any raster render copied from the original conversation as directional only.

## Rendering recommendation

For any new photorealistic rendering, first build an exact-scale blockout using:

- R6RT: 42.5 × 12.5 in deployed footprint;
- Pelican Air 1595: 28.52 × 17.89 × 10.73 in;
- NANUK 935: 22 × 14 × 9 in;
- Pelican small-tools roll: 28.7 × 14 in;
- seated top plane: ~29–30 in AFF;
- standing top plane: ~39–41 in AFF, verified to clear the open Pelican lid.

Then use the blockout as the image generator's geometry reference instead of relying on prose alone.
