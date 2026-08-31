# Transport Cart / Mobile Site-Operations Station

Status: **concept / prototype planning**
Primary base: **Rock-N-Roller R6G Ground Glider Multi-Cart**
Purpose of this folder: agent-facing design handoff for continued mechanical design, weight budgeting, fabrication planning, and field validation.

> **R6G replaces R6RT throughout this document.** The R6G was selected over the R6RT for its larger all-terrain front casters (5"×2" vs 4"×1") while sharing identical folded frame dimensions (28"×12.5"×9.5") and being 1 lb lighter (27.6 lb vs 28.8 lb). All geometry and weight references updated accordingly.

## Design intent

The cart is best understood as a **modular rolling toolbelt**, not a miniature mechanic's cabinet.

The R6G remains useful as a normal material cart / hand truck when the site-operations modules are removed. At a site, lightweight docking structures convert it into an organized mobile tool station that carries existing tool rolls, pouches, cases, power, light, and selected service fixtures.

Primary operating roles:

1. Material movement with Site Ops modules/cases removed.
2. Conventional hand-cart / dolly use.
3. Mobile Site Ops tool-control station.
4. Seated or standing laptop / console workstation (crash cart / emergency desk).
5. Rack-side crash cart / troubleshooting station.
6. Temporary server-service surface.

Explicitly deferred from v1: using the cart as a personnel step/scaffold. A separate lightweight folding step remains the safer plan.

## Canonical dimensional anchors

| Item | Key dimensions / weight |
|---|---|
| Rock-N-Roller R6G | ~42.5 in max deployed platform length; ~12.5 in frame width; **28 × 12.5 × 9.5 in folded stock envelope (wheels removed)**; **27.6 lb**; 500 lb cart class; 8×3 in rear wheels (removable); 5×2 in front all-terrain casters |
| Pelican Air 1595 | **28.52 × 17.89 × 10.73 in** exterior; ~13.6 lb empty/no foam |
| NANUK 935 / unbranded equivalent | **~22 × 14 × 9 in** exterior; ~11.6–13.7 lb empty |
| Existing Pelican small-tools roll | **28.7 × 14 in** deployed |
| Working deck (prototype) | **~30 × 12 in**, 1/2" Baltic birch |
| Working deck (final) | **~30 × 12 in**, structural ACP 10–16mm core |

Important geometry:

- Pelican 1595 centered on a 12.5 in R6G frame overhangs by roughly **2.7 in per side**.
- NANUK / unbranded case (~22 in wide) on the end shelf overhangs roughly **4.75 in per side** and projects outward roughly **14 in**.
- Working deck is sized to **working cart length (~30 in)**, not full extension. Material movement does not require the deck — deck is a workstation-mode accessory only.

## Weight architecture

- **50 lb is the hard ceiling for any individually handled package.**
- Design target for tool cases: **45–48 lb packed**.
- Design target for cart + accessory travel package: **≤50 lb absolute**, target **≤45 lb**.

### Current cart accessory weight estimate

| Item | Est. weight |
|---|---|
| R6G bare frame | 27.6 lb |
| Working deck (1/2" birch prototype, 30"×12") | ~3.6 lb |
| Working deck (structural ACP final, 30"×12") | ~1.4 lb |
| End shelf adapters ×2 (aluminum flat bar + U-bolt saddle clamps) | ~0.4 lb |
| End shelf retention strap (1" nylon webbing + buckle) | ~0.1 lb |
| RSA-WAG6 wagon bag | ~1.5 lb |
| Deck attachment clamps ×4 | ~0.3 lb |
| Riser sets (3" + 6" aluminum square tube, one set each) | ~0.4–0.8 lb |
| S-hooks / carabiners ×6 | ~0.2 lb |
| Shock cord tensioners ×4 | ~0.1 lb |
| Compact power strip (velcro-mounted under deck) | ~0.9 lb |
| USB-C task light (removable) | ~0.3 lb |
| Misc hardware (screws, washers, zip ties) | ~0.3 lb |
| **Total (birch prototype)** | **~35.7 lb** |
| **Total (ACP final)** | **~33.5 lb** |
| **Margin to 50 lb (ACP)** | **~16.5 lb** |

Tag each travel package with **TARGET 45 LB / MAX 50 LB**.

## Working height system

The R6G has multiple extension notches. Physical measurement of actual deck-surface AFF at each notch is required before finalizing riser dimensions. Estimated heights based on R6G frame geometry:

| Configuration | Est. deck height AFF | Primary use |
|---|---|---|
| First notch, no riser | ~29" | **Seated laptop / crash cart desk** — Big Agnes chair or stool |
| Full extension, no riser | ~41" | Standing work, low rack service |
| Full extension + 3" riser | ~44" | **Primary standing workstation** |
| Full extension + 6" riser | ~47" | Taller user / rack-height service |

### Riser design

Simple interchangeable square aluminum tube spacers (1"×1" or 1.5"×1.5") that sit between the cart cross member and the deck attachment clamps. Drilled to match deck clamp bolt pattern. No additional hardware — same clamps hold deck and risers. Weight per set: ~0.2–0.4 lb.

Two riser sets: **3" and 6"**. Both travel in the MIER bag alongside the cart frame.

### Pelican lid clearance at standing height

At full extension + 3" riser (~44" deck height):
- Pelican top face at ~10.73" AFF (case on lower platform)
- Lid at 90° projects ~17.89" upward from hinge = ~28.6" AFF at lid top
- Underside of deck at 44" clears open lid by ~15" — no conflict at any riser height

Do not rely on the lid naturally staying open. Use webbing stays, short link stays, or clips. Target ~90–95° retention angle to avoid projecting into the rear tool-roll zone.

## Current architecture at a glance

### Lower platform zone

- Pelican Air 1595 rides lengthwise on R6G lower platform.
- Overhangs ~2.7 in per side — this is correct and expected; do not shrink to fit.
- Cases retain bulky, specialized, replenishment, and lower-frequency tools after their primary rolls are deployed onto the cart.

### Working deck

- Fixed at ~30"×12" — working-cart length, not full extension span.
- Prototype: **1/2" Baltic birch**, edge-banded. Owner has tools for laminating and edge-banding.
- Final: **structural aluminum composite panel (ACP), 10–16mm core** — sourced from sign shop as offcut. Confirm 10mm vs 16mm thickness against span/load requirements before ordering. Do not use standard 3mm signage Dibond — specify structural/thick ACP grade. Expected cost: $20–50 for a 30"×12" piece.
- Deck attaches to cart cross member via **4× tube clamps** sized to R6G upright tube diameter (measure physically before ordering clamps).
- Riser spacers interpose between clamp and deck for height adjustment.

### End shelf (one end only)

- **Two removable triangular adapters** — aluminum flat bar + U-bolt saddle clamps (Option D).
- Sized to R6G upright tube diameter (measure physically).
- Supports NANUK 935 or unbranded case (~22 in wide, ~4.75 in overhang per side, ~14 in outward projection).
- **Retention:** 1" nylon webbing strap with side-release buckle across the front of the case.
- Removable without tools (hand-tighten U-bolts or add thumb screws for tool-free).
- Usable at either end; store unused adapter pair in MIER bag during travel.
- **Not hinged / not permanently attached.** A folding version is a v2 refinement after geometry validation.

### WAG side (opposite end from shelf)

- **RSA-WAG6 wagon bag** hangs on uprights at the end opposite the end shelf.
- Deployed function: open-top waste / sorting / long-item bin.
- Travel function: folds flat, packs inside MIER 90L alongside cart frame and removed wheels.
- This is deliberately **not** a tool-roll location.

### Operator-facing front rail

Hook-based system using cart frame tubes directly — no bespoke rail required for v1:

- **2× drill holster hooks** — S-hooks or carabiners on front cross member; tools hang by belt clips.
- **1× divided rear-pocket tool pouch** — hangs from front cross member on simple hook.
- **Meter / tester pouches** — clip to front frame tube with universal tool pouch clip hangers (Milwaukee / CLC style, sized to tube diameter).
- **Base tensioning:** shock cord or elastic loop from bottom of pouch to lower frame tube — keeps pouches snug, prevents flapping during cart movement.

### Rear face — tool roll dock

- **DC tool roll (Pelican small-tools roll, 28.7"×14"):** two S-hook / carabiner hang points from upper uprights or cross member; shock cord tensioner at bottom to lower frame tube. Removable in seconds. Can also hang on front, end, or rear selectively depending on site layout.
- **Site Ops heavy tool roll(s):** same two-point hang system on rear uprights; upper suspension plus lower shock cord restraint. 1.5–3" stand-off from frame using spacers if needed to clear Pelican lid sweep zone.
- Roll positions are **not fixed** — hang on front, rear, or end as site geometry requires.

### Upper frame / reference shelf

- Lightweight laptop / tablet / scanner reference shelf on upper uprights — optional, not a core v1 item.
- Task light (USB-C rechargeable, clip-mount) — removable.
- **Torque driver balancer / boom:** interesting but non-critical; not designed into v1 frame. Add only if weight budget allows after all primary geometry is validated.

### Power / accessories

- Compact power strip velcro-mounted under deck.
- Detachable extension cord — travels in MIER bag.
- Simple cord hooks on frame for management.
- Optional: portable fan, paper towel holder, clip-on parts trays — only after main geometry and mass budget are frozen.

## Deck material decision path

1. **Prototype in 1/2" Baltic birch** — validate fit, height, clamp positions, Pelican lid clearance, riser geometry. Edge-band with owner's existing tools.
2. **Validate geometry** — all measurements confirmed, riser heights set, clamp positions locked.
3. **Source structural ACP from sign shop** — bring confirmed dimensions, specify 10–16mm core structural grade (not 3mm signage Dibond). Get offcut quote; expect $20–50.
4. **Determine ACP thickness** — 10mm core for lighter weight if span stiffness is adequate per prototype testing; 16mm if 10mm shows flex under service load.
5. **Cut and fit ACP panel** — aviation snips, high-speed rotary, circular saw with metal blade, or jigsaw with metal blade. Owner has all applicable tools.
6. **Edge treatment** — aluminum angle trim (available at sign shops) or leave raw (ACP face sheets protect core adequately).

## R6G wheel / undercarriage packaging

- Rear wheels are primary candidates for tool-less removal / quick-release retention.
- Front casters may be redesigned around removable receiver sockets.
- The curved rear members are **structural axle carriers** — do not cut them. Preserve the 500 lb-class load path.
- Modified cart must be proof-tested at working load after any structural modification.
- Removed wheels + casters pack into MIER 90L alongside frame, deck, risers, end shelf adapters, and folded WAG6.

## Explicitly rejected / superseded ideas

- R6RT — replaced by R6G throughout.
- Heavy conventional full-extension tool drawer: too much weight, redundant with existing rolls.
- Full-span extending deck: unnecessary — material movement uses cart without deck; working deck sized to working-cart length only.
- High fixed side table for NANUK / fixed end-dock structure: replaced by simple removable triangular shelf adapters.
- Fixed floor legs / outriggers: interfere with mobility.
- Large permanent gantry or upper cabinet: excessive weight and complexity.
- Piano hinge folding deck: deferred to v2 after geometry is validated in prototype.
- Using cart as step / scaffold: deferred to v2 with proper engineering; use separate folding step for v1.
- Generic wide mechanic-cart chassis: undermines airline and material-cart goals.

## Next engineering tasks (priority order)

### P0 — before buying clamps or cutting wood

1. **Obtain R6G physically.** Measure:
   - upright/handle tube outer diameter at candidate clamp points
   - deck-surface AFF at each extension notch
   - cross-member positions and tube diameter
   - rear axle-carrier construction and QR feasibility
   - folded naked-frame thickness after wheels and casters removed
2. **Confirm Pelican lid sweep** at target standing deck height — verify 90° lid position clears deck underside.
3. **Confirm RSA-WAG6 stock** at B&H or RocknRoller before ordering.
4. **Weigh actual current Pelican 1595 contents** item by item. Build 45–48 lb packed plan.
5. **Weigh NANUK / unbranded case** empty and with site ops rolls.

### P1 — prototype fabrication

6. Cut 1/2" Baltic birch deck to working dimensions (~30"×12", refine after P0 measurements).
7. Source and fit 4× tube clamps to measured upright diameter; attach deck at first notch.
8. Fabricate end shelf adapters (aluminum flat bar + U-bolt saddle clamps); load-test with actual case.
9. Prototype riser sets in 3" and 6" aluminum square tube; verify standing heights.
10. Test Pelican lid clearance physically at each riser height.
11. Mock up tool roll hang points and pouch clips with actual rolls and pouches.

### P2 — validate and source final materials

12. If prototype deck geometry confirmed: source structural ACP from sign shop at validated dimensions.
13. Determine ACP thickness (10mm vs 16mm) based on prototype flex testing.
14. Build detailed accessory weight BOM; confirm total ≤50 lb.
15. Only after main geometry frozen: place chargers, fan, paper towels, parts trays, lights.

## Files in this folder

- `README.md` — this design document / current source of truth.
- `IMAGE_GENERATION.md` — constraints and guidance for future visualizations.
- `OPEN_QUESTIONS.md` — unresolved design decisions and prototype experiments.
- `assets/` — canonical SVG geometry, operating-mode, tool-docking, and weight diagrams.
