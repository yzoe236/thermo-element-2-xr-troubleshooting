# Parts, Part Numbers & Money-Saving Substitutes

Every part number, price, and community-verified substitute mentioned across
the archived threads, in one table. **Verify everything independently before
ordering** — prices and availability reflect the time of the original
discussion (2024–2026), and your mileage may vary.

## Power supplies

| Need | OEM part (price if reported) | Community substitute | Source thread |
|---|---|---|---|
| Inlet system PSU | XP Power (discontinued) | **Mean Well QP-320F** (~$60, minor rewiring) or **Emerson LPQ353-CEF** (same voltages, higher wattage) or XP Power ECM100UQ44 | *Inlet System Power Supply Replacement*, 2024-10 |
| Ignition power board supply | Thermo original (expensive) | **Mean Well QP-320F** (~$60) | *Element XR - ignition problem*, 2025-05 |
| FEP power supply | FSP300-70PFL (scarce, refurbs pricey) | **Any standard ATX PSU** (verify physical size) | *replacement Element XR FEP PSU*, 2026-01 |
| Vacuum-system switching PSU | PSP-300-24 | **PSP-600-24** (direct upgrade after years of intermittent failures) | *Re-establishing vacuum (resolved)*, 2026-01 |
| SEM supply board | Thermo, **$9,500** | Board-level repair attempt: **~$30 of adjustable voltage references + regulators from Digi-Key** (positive HV side fails first; simple linear supply: transformer → rectifier → filter → regulators) | *Loss of counting signal* 2025-01; *ElementXR SEM issues!* 2025-02 |
| Magnet power stage | P/N **2046641** or **BRE0005622** | None — borrow a known-good stage to test; FET-level repair is high-risk | *E2 magnet problem*, 2026-07 |

## Pumps & vacuum

| Need | OEM part (price) | Alternative | Source thread |
|---|---|---|---|
| Roughing pump | Thermo PN 1097510 — **$5,060** | **Pfeiffer PK D61 105 D — $3,645** (same vacuum spec, different connectors) | *Roughing pump options*, 2024-11 |
| Turbopump controller | TC100 | Swap controllers between pumps to isolate fault before buying | *Turbopump HiPace 80*, 2025-02 |

## Fittings, valves & small parts

| Need | Part number | Notes | Source thread |
|---|---|---|---|
| Load coil 90° chilled-water push-fit (4 mm) | **SMC KQ2L04-M5A** (M5 thread) | | *load coil fitting*, 2024-07 |
| Argon push-fit bulkhead connector / MFC shutoff valve | Thermo **PN 1067340** | Substitute: **Colder Products MCD1204** (Fresh Water Systems) | *Argon connectors* 2025-02; *Failing sample gas MFC* 2024-10 |
| Sample gas MFC | Thermo **PN 1354110** | Requires ICP Module board rev. 7+ | *Failing sample gas MFC*, 2024-10 |
| Mass flow controller, older Element (2 L/min argon) | **Mass-Stream D-511** | Obsolete OEM MFC; sourced only as used units on-list. Newer PN 1354110 needs board rev. 7+, so not a drop-in | *mass flow controllers*, 2025-03 |
| Argon inlet ferrule (Element & Neptune) | Thermo **PN 0674790** (KEGELEINS 1/8"–1/16" PTFE) | No Swagelok equivalent | *Ferrule for Argon connection*, 2026-07 |
| Torch assembly interlock switch | **Bernstein 6008116032** | | *Torch assembly part*, 2024-11 |
| Main gas valve solenoid trigger | (~**$60**) | Test trigger resistance before replacing whole valve | *Cool gas and coil cooling error*, 2025-09 |
| Flight tube entrance aperture | (~**$3,700**) | Suspect when HR resolution plateaus below spec | *High resolution issues*, 2025-03 |
| Kapton foil, 0.08 mm amber (magnet/flight-tube insulation) | — | Supplier: **Complex Plastics** | *Kapton foil*, 2025-07 |

## Consumables & specs worth pinning

| Item | Community consensus | Source thread |
|---|---|---|
| Chiller fluid | **Distilled water only** — no glycol/algaecide, no DI water (corrodes brass); replace ~every 3 months | *Chiller*, 2025-08 |
| Torch box exhaust flow | **90–120 m³/h** | *Exhaust Flow Rate*, 2026-02 |
| Extraction lens repair kit contents | grease, 2× skimmer-valve o-rings, interface-housing o-ring, actuator washer, extraction lens, graphite orifice plate, ceramic insulating ring, 2× bulkhead covers | *Extraction Lens Repair Kit*, 2025-02 |
| Element schematics | Available from Thermo Bremen **under NDA** — invaluable for board-level repair | *Loss of counting signal*, 2025-01 |

*Found a better substitute, or a price update? Open an issue — this table only
gets more valuable as it grows.*
