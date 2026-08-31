# Transport Cart — Open Questions / Prototype Experiments

This file separates unresolved engineering questions from decisions already made in `README.md`.

## P0 — resolve before buying clamps or cutting wood

### R6G physical geometry

Measure a real R6G (not spec sheet):
- upright/handle tube outer diameter at candidate clamp points (determines all clamp sourcing)
- deck-surface AFF at each extension notch (determines riser heights and seated index)
- cross-member positions and tube diameter
- rear axle-carrier construction and feasible QR modification approach
- folded naked-frame thickness after wheels and casters removed (confirms MIER 90L packing)

### Actual packed case weights

New hard requirement: MAX 50 lb, target 45–48 lb per handled package.

Actions:
- weigh empty Pelican 1595 in actual configured state
- weigh 28.7×14 small-tool roll empty and loaded
- weigh each Pelican inventory group individually
- weigh empty NANUK 935 / unbranded black case
- weigh site ops rolls and contents
- identify dense/low-utility items for relocation or selective-site loading

### Pelican lid sweep

Prototype with actual 1595:
- minimum underside-of-top clearance for 90° lid position at each riser height
- useful retention angle (90–95° likely)
- interference with rear tool-roll stand-off at that angle
- confirm seated index (first notch, no riser) with lid closed

### RSA-WAG6 stock

Confirm availability at B&H or RocknRoller before ordering R6G and MIER bag.

## P1 — prototype fabrication questions

### Deck thickness validation

Prototype in 1/2" Baltic birch. Under working load (laptop + tools + downward service pressure):
- does 1/2" at 30"×12" span flex acceptably with 4-point clamp support?
- if flex is marginal, does adding a center cross-support clamp resolve it without adding weight?
- record result to inform ACP thickness selection (10mm vs 16mm core)

### ACP thickness selection

After prototype flex testing:
- if 1/2" birch is adequately stiff: 10mm ACP core is likely sufficient (~1.1 lb at 30"×12")
- if 1/2" birch shows noticeable flex under load: specify 16mm ACP core (~1.5 lb at 30"×12")
- bring confirmed dimensions to sign shop; specify structural/thick ACP, not standard 3mm signage Dibond
- expected cost $20–50 as offcut; get quote before committing

### Tube clamp sizing

All clamps depend on measured R6G tube outer diameter. Common sizes are 1" and 1.25" OD — verify before ordering:
- 4× deck attachment clamps
- 2× end shelf U-bolt saddle clamps (×2 per adapter = 4 total)
- pouch clip hangers for front rail

### Riser validation

After deck height at full extension is measured:
- confirm 3" riser reaches comfortable standing height for primary user
- confirm 6" riser is useful or redundant
- confirm riser tube section (1"×1" or 1.5"×1.5" square aluminum) fits between clamp and deck cleanly
- validate that riser + clamp assembly is stable under lateral service load

### End shelf adapter validation

Fabricate two triangular adapters (aluminum flat bar + U-bolt saddle clamps):
- case remains level
- ~4.75 in per-side overhang is acceptable in practice
- 14 in outward projection is manageable in DC and office environments
- no unacceptable chassis twist or tipping under case weight
- retention strap (1" nylon webbing + side-release buckle) is sufficient
- operator can reposition cart while case is deployed on shelf

### Tool roll hang system

Use actual rolls and pouches:
- S-hook sizing to match upper upright tube and roll grommet/loop diameter
- shock cord gauge and hook type for lower tensioning
- whether 1.5–3 in stand-off from frame is needed for rear roll (Pelican lid sweep clearance)
- front pouch clip hanger compatibility with measured tube diameter
- whether DC roll hangs best on front, rear, or end for typical site layouts — test all three

## P2 — work surface decisions

### Deck width

Current target 12 in matches R6G frame width. Questions:
- is 12 in adequate for laptop + tester side by side?
- would a 14–16 in deck (overhanging frame ~1–2 in per side) be useful and stable?
- does overhang create tipping risk at standing height with off-center load?

### Upper reference shelf

Determine whether upper uprights should support:
- tablet / reference only
- laptop at standing height
- scanner dock
- or nothing in v1 (hang roll from upper uprights instead)

Primary uses: standing inventory/shipping scans, manuals, diagrams, reference during hands-on work on main deck.

### Pelican lid retention

Test retention options:
- webbing stays (simplest)
- short link/chain stays
- clips/straps
- target ~90–95° fixed position
- rear-roll stand-off can provide secondary anchor/clearance structure

## P3 — accessory placement after main geometry frozen

Potential modules (do not drive main frame dimensions):
- cordless battery charger mounts
- small portable fan
- paper towel roll holder
- clip-on / magnetic / ESD parts trays
- additional task lighting
- cord hooks and management
- waste / sorting bag divisions
- small consumable bins

## Deferred concepts

- **Torque driver balancer / boom mast:** interesting but non-critical. Add only if weight budget allows after all primary geometry validated. Not designed into v1 frame.
- **Piano hinge folding deck:** deferred to v2 after prototype geometry validated.
- **Personnel scaffold / step mode:** v2 only with proper structural engineering, proof testing, and hard stops. Use separate lightweight folding step for v1.
- **Removable drawer:** rejected for v1 on weight and complexity grounds. May revisit in v2 if prototype reveals strong need.
