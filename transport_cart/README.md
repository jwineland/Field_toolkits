# Transport Cart / Mobile Site-Operations Station

Status: **concept / prototype planning**  
Primary base: **Rock-N-Roller R6RT Mini Multi-Cart**  
Purpose of this folder: agent-facing design handoff for continued mechanical design, weight budgeting, CAD, fabrication planning, and field validation.

## Design intent

The cart is best understood as a **modular rolling toolbelt**, not a miniature mechanic's cabinet.

The R6RT remains useful as a normal material cart / hand truck when the site-operations modules are removed. At a site, lightweight docking structures convert it into an organized mobile tool station that carries existing tool rolls, pouches, cases, power, light, and selected service fixtures.

Primary operating roles:

1. Material movement with Site Ops modules/cases removed.
2. Conventional hand-cart / dolly use.
3. Mobile Site Ops tool-control station.
4. Seated or standing laptop / console workstation.
5. Rack-side crash cart / troubleshooting station.
6. Temporary server-service surface.

Explicitly deferred from v1: using the cart as a personnel step/scaffold. A separate lightweight folding step remains the safer plan.

## Canonical dimensional anchors

These proportions should be treated as constraints in future CAD and image-generation work.

| Item | Key dimensions / weight |
|---|---|
| Rock-N-Roller R6RT | ~42.5 in max deployed platform length; ~12.5 in frame width; ~28 x 12.5 x 9.5 in folded stock envelope; ~26 lb; 500 lb cart class; 8 in rear wheels; 4 in front casters |
| Pelican Air 1595 | **28.52 x 17.89 x 10.73 in** exterior; ~13.6 lb empty/no foam |
| NANUK 935 | **22 x 14 x 9 in** exterior; ~11.6 lb empty |
| Existing Pelican small-tools roll/pallet | **28.7 x 14 in** deployed |

Important geometry:

- Pelican 1595 centered on a 12.5 in R6 frame overhangs by roughly **2.7 in per side**.
- NANUK 935, when deployed at an end with its **22 in hinge edge lateral across the 12.5 in cart**, overhangs roughly **4.75 in per side** and projects outward roughly **14 in**.
- The NANUK hinge belongs nearest the cart; its lid rises upward beside the cart rather than opening from the outboard edge.

## Weight architecture

A recent field experience carrying a ~54 lb case up stairs established a stronger human-factors requirement:

- **50 lb is the hard ceiling for any individually handled package.**
- Design target for tool cases: **45–48 lb packed**.
- Design target for the cart/accessory travel package: preferably **<=45 lb**, absolutely below 50 lb.

This means the Pelican and NANUK must be treated as separate mass budgets, not simply filled until volume is exhausted.

Approximate content budgets before detailed weighing:

- Pelican Air 1595: ~13.6 lb bare case, leaving roughly 30–33 lb for tool roll, organization, and contents if targeting 45–48 lb.
- NANUK 935: ~11.6 lb bare, leaving roughly 31–34 lb for rolls/contents at the same target.

Use a dedicated luggage scale and tag each travel package with **TARGET 45–48 LB / MAX 50 LB**.

## Current architecture at a glance

### Lower mass/storage zone

- Pelican Air 1595 rides lengthwise on the R6 lower platform and visibly overhangs the narrow frame.
- NANUK 935 normally travels as its own case; at the site it can dock low at either end using removable supports.
- Cases retain bulky, specialized, replenishment, and lower-frequency tools after their primary rolls are deployed onto the cart.

### Main working plane

The main top is height-adjustable and lightweight.

Index concepts:

- **Seated desk position:** roughly 29–30 in AFF; assumes Pelican closed.
- **Lowest standing/service position:** roughly 39–41 in AFF and must clear the Pelican 1595 lid opened to about 90 degrees.
- Optional higher standing index: roughly 42–44 in AFF.

Final positions must be set from physical R6 deck height and prototype ergonomics.

The top should be lightweight (aluminum slats, honeycomb/composite, or equivalent), potentially folding/expanding for a wider service surface. Do not turn it into a heavy shop bench.

### Upper information / precision-tool plane

The existing **28.7 x 14 in Pelican small-tools roll** is already central to the DC kit. Do not duplicate it with a heavy sliding drawer.

Preferred approach:

- Remove it from the Pelican at deployment.
- Hang/tension it on a lightweight upper docking frame.
- Potentially allow vertical parked and slightly tilted working positions.
- Upper frame can also support a small laptop/tablet/scanner/reference shelf for standing inventory, shipping, manuals, and rack service.

The upper frame also supports task lighting and the torque-driver balancer mast/boom.

### Rear heavy Site Ops roll(s)

The NANUK contains one or more heavier Site Ops tool rolls during travel.

At deployment these hang from the **rear rail / rear face of the cart**, opposite the operator-facing toolbelt rail. They should be accessible when standing on the opposite side of the cart.

Key requirements:

- Similar broad hanging format to the upper small-tools roll.
- Upper suspension plus lower restraint/support so heavy rolls do not swing.
- Likely spaced off the cart frame by ~1.5–3 in using a lightweight adapter.
- This spacing also helps preserve the Pelican lid sweep zone.

### Perimeter “rolling toolbelt” rail

The cart should accept normal task pouches that move between cart and operator:

- cordless drill/impact hook;
- electrician pouch;
- divided back-pocket tool pouch;
- meter pouch;
- fastener/small-parts pouch;
- other belt-mounted modules.

A rigid belt-like rail may be more weight-efficient than continuous 80/20. Short localized T-slot/80/20 sections can be used where continuous positional adjustment matters.

Goal: **cart -> belt -> cart** without bespoke adapters for every pouch.

### Waste / sorting side

One side is reserved for collapsible, vertically divided fabric waste/sorting bags. This is deliberately **not** another tool-roll location.

Potential divisions:

- general waste;
- packaging/recycling;
- recoverable hardware / e-waste / reusable parts.

The bags should fold nearly flat and remove easily for emptying/travel.

### NANUK low dock

Current preferred concept is not a large side table. Use two removable triangular support adapters that pin/clamp to the R6 end/upright tubes.

- NANUK sits low and level.
- 22 in hinge edge runs laterally across the cart end.
- Case projects ~14 in outward.
- Hinge is nearest the cart; lid opens upward along the cart.
- Supports should be usable at either end.
- Avoid fixed floor legs because they prevent quick repositioning.
- If anti-tip support proves necessary, use a small wheel/wheels rather than a fixed foot. Fixed-direction wheels may be especially sensible on the large-wheel end.

### Pelican lid clearance / retention

The standing index should clear the Pelican Air 1595 lid opened to approximately 90 degrees beneath the top.

Do not rely on the lid naturally staying open. Consider:

- webbing stays;
- short link stays;
- clips/straps;
- magnetic targets only as secondary parking aids.

A fixed ~90–95 degree position avoids projecting into the rear heavy-tool roll. The rear-roll spacer can provide an anchor/clearance structure.

### Power / lighting / service accessories

Current integration targets:

- compact commercial PDU/power strip under top;
- detachable extension cord;
- simple figure-eight/folding-hook cord management, not a heavy reel;
- removable task lights / upper LED light;
- torque-controlled driver on a spring balancer/retractor;
- removable indexed-height mast/boom;
- optional cordless battery charger mounts;
- optional small portable fan;
- optional paper towel holder;
- optional clip-on/magnetic small parts trays or sorting bins.

These small accessories should be designed only after the major geometry and mass budget are frozen.

## Structural / travel notes

### R6 wheel/undercarriage packaging

We investigated reducing stock folded thickness for checked baggage.

- Rear wheels are straightforward candidates for tool-less removal / quick-release retention.
- Front casters may be redesigned around removable receiver sockets.
- The curved rear members are **structural axle carriers**, not disposable skid loops; do not simply cut them away.
- A future design could modularize the rear axle-carrier assembly, but preserve the load path and proof-test any structural modification.

This is a promising packaging optimization but should not casually compromise the 500 lb-class material-handling function.

### Main top travel strategy

Candidates considered:

- thin bi-fold honeycomb/composite panel;
- aluminum roll/slat top;
- rigid narrow center top plus lightweight extension;
- travel sleeve/bag that converts into a replaceable vinyl/TPU worktop cover.

A removable server turntable / lockable lazy-Susan service plate is an optional later module, not a core travel item.

## Explicitly rejected / superseded ideas

- Heavy conventional full-extension tool drawer: too much weight and redundant with existing rolls.
- Making both hard cases conventional cantilevered drawers: tipping and weight problems.
- High fixed side table for NANUK: unnecessary lifting and structure.
- Large fixed support legs/outriggers during normal tool-cart use: interfere with mobility.
- Using stock R6/top as a step/scaffold: set aside for v1; separate folding step instead.
- Generic wide mechanic-cart chassis: undermines airline and material-cart goals.

## Next engineering tasks

1. **Weigh the actual current Pelican contents item-by-item.** Build a 45–48 lb packed plan.
2. Repeat for NANUK / heavier Site Ops roll(s).
3. Obtain/measure physical R6RT geometry: deck height, handle tube dimensions, attachment-hole spacing, wheel/axle carrier geometry.
4. Establish exact main-top seated and standing pin heights.
5. Test Pelican 1595 lid sweep at standing height and rear-roll spacing.
6. Prototype one NANUK triangular support adapter set and load-test it.
7. Prototype the perimeter belt rail with real pouches/hooks.
8. Prototype upper Pelican-roll dock and rear heavy-roll dock using the actual rolls.
9. Build a detailed cart accessory weight BOM; keep structural/accessory package <=45 lb target.
10. Only after these are fixed, place chargers, fan, paper towels, parts trays, lights, etc.

## Files in this folder

- `README.md` — this design handoff / current source of truth.
- `IMAGE_GENERATION.md` — constraints and guidance for future visualizations.
- `OPEN_QUESTIONS.md` — unresolved design decisions and recommended experiments.
- `assets/` — selected surviving concept graphics. **Treat them as directional only; several contain known geometry errors documented in `IMAGE_GENERATION.md`.**
