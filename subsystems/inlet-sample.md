# Sample Introduction (Nebulizer / Autosampler / MFC)

14 entries · newest first · [back to index](../README.md)

## Segmented air bubbles in the capillary stall self-aspiration and cut sensitivity

*2026-07-30 · original list thread: "Neptune — Bubbles in the sample capillary" · status: solved*

- **Symptom:** Neptune Plus running Cu and Sn isotopes with an ASX-112 and 100 µL or 50 µL nebulizers on 100 cm screw-on capillaries (ESI and Savillex both tried). After the probe moves to a different vessel (sample, standard or blank) the system **fails to aspirate**, with **alternating sections of air and liquid visible in the capillary**. Aspiration resumes after an indeterminate wait, but **signal intensity is significantly reduced from then on**. The same lab's Pb/Sr setup (Aridus 2 + ASX-100 + 50 µL nebulizer) is stable.
- **Likely cause:** Reliable self-aspiration at low flow rates is inherently difficult. There should be **only one air-bubble segment between two solutions**; multiple dismembered bubbles arise when the **autosampler is not moving smoothly**, or when **droplets on the outside of the probe wick down and get sucked in during travel**. The extra bubbles increase flow restriction, and the sensitivity loss comes from the **nebulizer not restarting at its correct flow rate**.
- **Fix / suggestions:** Check the usual culprits — organics or resin fines in the sample, the nebulizer, the probe, and the autosampler's motion; keep the probe exterior free of clinging droplets. For a permanent fix, move to a **syringe loading/injection system** (e.g. ESI's Isotope2), which maintains aspiration at the exact user-defined flow rate and removes the uncertainties of self-aspiration.
- **Credit:** asked by Bernd Hoeppner; answered by Paul Field (Elemental Scientific)

## ASX-520 without a cover lets particles fall in and block the nebulizer

*2026-07-20 · original list thread: "ASX 520 housing" · status: partial*

- **Symptom:** After many happy years on a small ASX-100, a higher-throughput project brought a 10-year-idle **ASX-520** back into service (self-aspiration mode) — and the capillary/nebulizer now **blocks constantly**. It blocks in wash, standard and sample solutions alike, yet **aliquots of the very same solutions run fine when transferred to smaller tubes and run on the covered ASX-100 with the same nebulizer and capillary**.
- **Likely cause:** Particles falling into the open sample tubes, because this ASX-520 has **no enclosure/cover**.
- **Fix / suggestions:** (a) Obtain an **ASX-520 enclosure/cover** (the poster asked the list for a spare or redundant one). (b) Alternatively the blockage may be **organic material in the tubing** — aspirate or pump a **weak NH₄OH solution** through the tubing and nebulizer to clear it.
- **Credit:** asked by Jamie Lewis; answered by Chip Chipley

## Argon sample connection ferrule crack and replacement part

*2026-07-09 · original list thread: “Ferrule for Argon connection” · status: solved*

- **Symptom:** Ferrule (tapered fitting) on argon sample inlet connection of ElementXR is cracked
- **Likely cause:** Not conclusively identified
- **Fix / suggestions:** Thermo original part number 0674790—KEGELEINS 1/8"-1/16" PTFE ferrule; compatible with Element and Neptune; no Swagelok equivalent available
- **Credit:** asked by Tim Steffens; answered by Corey Archer, Rob

## CETAC ASX-260 autosampler z-axis drive tube replacement method ⏳

*2026-05-11 · original list thread: “autosampler CETAC ASX-260” · status: unresolved*

- **Symptom:** Z-axis drive tube (green PEEK anti-twist tube SP7174) is damaged
- **Likely cause:** Z-axis drive tube aging or mechanical damage
- **Fix / suggestions:** UNRESOLVED in thread (operating manual does not include replacement procedure; unclear how tube connects to z-axis drive assembly)
- **Credit:** asked by Hana Simkova

## ASX-100 troubleshooting recommendations

*2026-01-22 · original list thread: “[Neptune] circuit Diagram - ASX-110” · status: partial*

- **Symptom:** ASX-100 malfunctions after power supply failure; front panel shows error indication
- **Likely cause:** Possible stepper motor drive chip burnout or motor failure
- **Fix / suggestions:** Disassemble and inspect by disconnecting motor; check stepper motor drive chip; replace faulty motor and drive chip; detailed disassembly steps provided
- **Credit:** answered by Christopher Coath

## ASX-100 autosampler failure after power supply replacement ⏳

*2026-01-21 · original list thread: “circuit Diagram - ASX-110” · status: unresolved*

- **Symptom:** After replacing ASX-100 power supply, front panel green light blinks indicating error
- **Likely cause:** Not conclusively identified
- **Fix / suggestions:** UNRESOLVED in thread (circuit diagram needed for diagnosis)
- **Credit:** asked by Bernd Hoeppner

## 2M NaOH sample analysis feasibility and concentration limits

*2025-12-11 · original list thread: “Samples with NaOH” · status: solved*

- **Symptom:** User needs to analyze water samples with 2M NaOH; concentration limit for acids/bases?
- **Likely cause:** N/A (application inquiry)
- **Fix / suggestions:** High base concentration causes nebulizer clogging requiring frequent purging; 500x dilution with 0.2-0.5M dilute HNO3 reduces salt accumulation; or use SeaFAST matrix separation; or 500x dilute then add equal-concentration base rinse solution to avoid pH shock
- **Credit:** asked by Siv Dundas; answered by Louis Derry, Martin Fleisher, Dr. Robert Brause, Patrick Klemens

## Jet interface impact assessment with exotic anionic components

*2025-03-14 · original list thread: “Jet interface with exotic matrix components” · status: solved*

- **Symptom:** Sediment leach liquids contain MgCl₂, hydroxylamine, acetic acid, citric acid, disulfate, ascorbic acid anions; impact on corrosion or interference?
- **Likely cause:** N/A (technical consultation)
- **Fix / suggestions:** Disulfate can trigger spontaneous ignition and requires careful handling; high salt concentration causes cone accumulation requiring frequent cleaning; recommend TDS limit 1000 ppm; can use P10 gas or acetic acid compensation
- **Credit:** asked by Jakub Sliwinski; answered by Ted Huston, Corey Archer

## Argon connector part numbers (sample/makeup gas bulkhead tubing)

*2025-02-12 · original list thread: “Argon connectors” · status: solved*

- **Symptom:** Need Argon push-fit connector PN for extraction lens/sensitivity troubleshooting.
- **Likely cause:** Not applicable
- **Fix / suggestions:** Thermo PN 1067340 or Colder Products MCD1204 (from Fresh Water Systems). MCD1204 from Grainger currently unavailable. Colder Products connectors recently swapped as Thermo PN substitute.
- **Credit:** asked by Bettina Sohst; answered by Alexis Floback

## Slow signal rise early scan then 3× drop after scan start

*2025-02-05 · original list thread: “Increasing signal” · status: partial*

- **Symptom:** Slow signal rise (~1.5 min) to full signal at scan/tune start. Each new scan initiation: signal drops ~3×. Affects all elements, concentrations, analog and count modes. Tune solution count absolutely low. Broad peaks, possible extraction lens wear.
- **Likely cause:** Dirty/worn extraction lens; LR plates/slit tongue wear; sample introduction issue (probe clog, dirty cones/injector)
- **Fix / suggestions:** Replace extraction lens. Clean/replace LR plates and slit tongue. Inspect probe, cones, injector. Verify Z position (−4.00 typical); x,y positions fixed at 4.5 (anomalous). Check tune solution concentration and peristaltic pump speed.
- **Credit:** asked by Richard Ash; answered by Tim Wahl, Chip Chipley

## Extraction lens power supply or hardware failure causing signal loss

*2025-01-08 · original list thread: “Extraction lens failure” · status: partial*

- **Symptom:** Long shutdown afterward; extraction lens shows red. After interface rebuild (new extraction lens, skimmer valve) still red. Signal extremely low (1 ppb In: 10,000 cps). ArAr dimer peak far below normal after rebuild (10^5 vs 10^7 at medium resolution).
- **Likely cause:** Extraction lens contamination/wear; inlet sample introduction issue; possible SEM detector damage during ventilation; extraction lens wire connection loose
- **Fix / suggestions:** Replace extraction lens (cheaper than detector). Verify sample gas flow and torch centering. Test analog mode only in tune solution. Check Ar/ArAr peak in Faraday and SEM. Remove SeaFAST system for testing. Replace cones, o-rings, injector if needed. Finally exchange SEM.
- **Credit:** asked by Bettina Sohst; answered by Joe Martineau, Rob Franks, Chip Chipley, Tim Wahl, Melissa Gilbert

## Sample gas MFC controller failure with backpressure flow reduction

*2024-10-30 · original list thread: “Failing sample gas MFC” · status: partial*

- **Symptom:** Sample gas fails to rise properly at startup; flow returns to 0 L/min; signal frequently disconnects during tune. Injector connection: gas flow does not exceed 0.8 L/min. Flow meter validates normal performance without injector.
- **Likely cause:** Sample gas MFC controller failure; possible MFC connector shutoff valve fault
- **Fix / suggestions:** Exchange sample MFC to unused Add2 MFC port. If still faulty, check MFC connector shutoff valve (PN 1067340). May require new MFC (PN 1354110). Check inlet system power supply LED status. Verify ICP Module board revision 7+ for compatibility with new MFC.
- **Credit:** asked by Melissa Gilbert; answered by Rob Franks, Ted Zateslo

## Inlet system power supply failure and replacement options

*2024-10-03 · original list thread: “Inlet System Power Supply Replacement” · status: solved*

- **Symptom:** XP Power inlet system power supply failed; LED indicator nonfunctional; manufacturer lacks suitable replacement.
- **Likely cause:** Power supply aging and manufacturer discontinuation
- **Fix / suggestions:** Use Emerson LPQ353-CEF (same voltage, higher wattage). Mean Well QP-320F also suitable. XP Power ECM100UQ44 as alternative. Ensure required voltages and at least rated amperage. Create voltage-position diagram for reconnection. Consider distributing load between two power supplies.
- **Credit:** asked by Melissa Gilbert; answered by Amy Managh, Rob Franks, Charles Knaack, George Kamenov, Ted Zateslo, Christopher Coath

## Peristaltic pump power supply failure and frontend corrosion

*2024-07-03 · original list thread: “Peri pump power supply” · status: partial*

- **Symptom:** Peristaltic pump exhibits suspected power supply fault. Front-end door edge shows corrosion buildup recurring within one day. Torch has remained clean for over one year; no other abnormalities.
- **Likely cause:** ESI peristaltic pump oscillation issue when powered from Inlet Board; possible unstable power supply ground; corrosion from seawater sample analysis (via seaFAST and APEX/Spiro inlet systems)
- **Fix / suggestions:** Peri pump power and control from Inlet Board (J0913 connector). ESI pump power from inlet system PSU supplying three inlet boards and external devices. Measure voltage at J0907 (+24V/+15V/−15V/+5V) to confirm. May require expensive power supply replacement; or drill bracket for cheaper alternative.
- **Credit:** asked by Melissa Gilbert, Alan Shiller; answered by Christopher Coath, Ted Zateslo
