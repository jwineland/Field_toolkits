# Visualization Guidance for AI Agents

The concept images in `assets/` are useful for design direction but **none should be treated as dimensionally authoritative CAD**. Several visual models repeatedly distorted the cases or moved tool rolls to incorrect faces.

## Hard geometry to preserve

- Base cart: **Rock-N-Roller R6RT Mini**, not a generic shop cart.
- R6 frame width: ~12.5 in.
- R6 max deployed platform length: ~42.5 in.
- Pelican Air 1595: **28.52 x 17.89 x 10.73 in**.
- NANUK 935: **22 x 14 x 9 in**.
- Pelican small-tools roll: **28.7 x 14 in**.

### Pelican geometry

Pelican rides lengthwise on lower R6 platform. Because it is 17.89 in wide on a 12.5 in frame, it should visibly overhang ~2.7 in on both sides. It must not be shrunk to fit the frame.

For standing-service visualization, show the Pelican lid open about 90 degrees under the main top. For seated top position, show case closed.

### NANUK geometry

NANUK deploys low at an end on two removable triangular adapters.

- horizontal and square;
- 22 in hinge edge runs laterally across the cart end;
- centered on 12.5 in R6 means ~4.75 in overhang per side;
- short 14 in dimension projects outward;
- hinge is nearest the cart;
- lid rises upward beside the cart to roughly 90–95 degrees.

Do not rotate it 90 degrees, angle it, tilt it, or place the hinge on the outboard edge.

## Correct tool-control locations

### Upper small-tools roll

Existing 28.7 x 14 Pelican roll. Hang from a lightweight upper dock/frame. This is the light/precision DC tool roll.

### Rear heavy Site Ops roll(s)

Derived from NANUK contents. Hang from the **rear rail / rear face**, opposite the operator-facing perimeter toolbelt rail. They should be accessible from the opposite side of the cart and similar in general hanging format to the upper roll. Likely use 1.5–3 in stand-off plus lower restraint.

### Perimeter rail

Operator-facing modular “toolbelt” rail for removable pouches and hooks. Do not turn every vertical surface into a fixed tool board.

### Waste / sorting bags

One side only. These are collapsible divided fabric bags for waste/sorting, **not tool organizers**.

## Main top / upper frame

Main top is vertically indexed:
- seated desk position ~29–30 in AFF, Pelican closed;
- lowest standing/service position ~39–41 in AFF, clears open Pelican lid;
- optional higher standing index ~42–44 in AFF.

Upper frame may hold:
- Pelican small-tool roll;
- lightweight laptop/tablet/scanner/reference shelf;
- task light;
- torque-driver balancer boom.

Do not create a huge permanent gantry or heavy cabinet structure.

## Avoid in future renders

- generic four-caster mechanic carts;
- NANUK rendered as a tiny toolbox;
- Pelican shrunk to frame width;
- tool roll on the waste-bag side;
- duplicate tool boards where existing rolls should dock;
- deep full-width tool drawer / heavy commercial slides;
- fixed floor legs on normal Site Ops modules;
- permanent wide side tables;
- personnel standing on the cart.

## Recommended rendering workflow

For accurate future visuals, create a simple exact-scale CAD/blockout first using rectangular volumes for:

1. R6 frame: 42.5 x 12.5 in footprint;
2. Pelican: 28.52 x 17.89 x 10.73 in;
3. NANUK: 22 x 14 x 9 in;
4. small-tools roll: 28.7 x 14 in plane;
5. seated and standing top planes.

Then provide the blockout as the geometry reference to the generative renderer. Do not ask the image model to infer those proportions from prose alone.

## Selected asset notes

- `01_rollout_case_concept.svg` — early supported-rollout idea; useful history, now mostly superseded by low end docking.
- `02_lwing_variant.svg` — illustrates experimental L-wing concept; superseded for v1.
- `03_low_case_bracket_variant.svg` — closer to low NANUK support direction, but dimensions/orientation are not authoritative.
- `04_rolling_toolbelt_direction.svg` — useful conceptual shift toward pouch rail / waste module; contains geometry errors.
- `05_close_generated_concept.svg` — useful overall rolling-toolbelt composition; NANUK/tool-roll placement contains known errors.
- `06_weight_infographic.svg` — rough weight-planning visualization; numbers are planning estimates, not measured BOM data.
