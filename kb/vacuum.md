# Vacuum System (Pumps & Gauges)

6 entries · newest first · [back to index](../README.md)

## Vacuum restart failure after building power loss

*2025-12-17 · original list thread: “Re-establishing vacuum after shutdown” · status: partial*

- **Symptom:** After building blackout, front vacuum cannot reach FV<10-1 mbar green light; high vacuum reads invalid (e-11); multiple checks find no recovery; prior two similar events self-recovered
- **Likely cause:** Penning gauge power loss or detector protection valve solenoid trigger failure or 24V supply failure
- **Fix / suggestions:** Check if turbo A protection valve open (should not exhaust); test 24V supply no-load output (should be 24V but may read only 16V); replace faulty 24V supply
- **Credit:** asked by Amy Managh; answered by Joe Martineau, Deborah Grimm, Ted Zateslo

## High vacuum gauge reading anomaly and failure diagnosis

*2025-05-15 · original list thread: “bad high vacuum gauge” · status: solved*

- **Symptom:** After ventilation, high vacuum reads e-11 (invalid); front vacuum normal; high vacuum LED red; front vacuum LED also flashing
- **Likely cause:** Penning gauge failure, power supply issue, or gauge head insulation breakdown
- **Fix / suggestions:** Tap Penning gauge gently; unplug/replug RJ11 cable; or disassemble head for cleaning; replace head or entire Penning unit if needed
- **Credit:** asked by Thomas Marchitto; answered by Lisa Stockli, Jakub Sliwinski, Ben Byerly, Don Chipley, Louis Derry, Andreas Möller, Ted Zateslo

## Jet interface HV pressure anomaly diagnosis ⏳

*2025-03-25 · original list thread: “HV pressure benchmark for LA-ICP-MS with jet pump” · status: unresolved*

- **Symptom:** After jet pump installation, rough vacuum 1.6e-3, high vacuum 3.8-4.2e-7, higher than literature values of 2-3e-7; no significant sensitivity improvement
- **Likely cause:** Not conclusively identified; possible vacuum system leak or parameter tuning issue
- **Fix / suggestions:** Adjust sample gas, auxiliary gas, laser gas, RF power, and Z position; UNRESOLVED in thread
- **Credit:** asked by Jakub Sliwinski

## Turbopump HiPace 80 failure recovery options

*2025-02-06 · original list thread: “Turbopump HiPace 80” · status: partial*

- **Symptom:** Turbopump loses vacuum; pump C vacuum loss recovery attempted without success; pump fails to restart; center-panel LED still red; other pumps shut down.
- **Likely cause:** TC100 controller failure or pump mechanical fault; possible insufficient pump speed or rotor contact; overdue maintenance (3–4 year oil pad replacement cycle)
- **Fix / suggestions:** Call Pfeiffer technician to interpret LED error code. Possibly exchange TC100 controller between pumps for testing. Use screwdriver to check pump vibration. Review pump manual for oil pad and lubrication maintenance. Inspect for rotor-contact particles possibly contaminating extraction lens.
- **Credit:** asked by Mery Malandrino; answered by Tim Wahl, Chip Chipley, Robert Brause

## Roughing pump replacement options and cost comparison

*2024-11-13 · original list thread: “Roughing pump options” · status: solved*

- **Symptom:** No problem; maintenance inquiry.
- **Likely cause:** Not applicable
- **Fix / suggestions:** Option 1: Thermo pump (PN 1097510), price $5,060. Option 2: Pfeiffer pump (PN PK D61 105 D), price $3,645, same vacuum spec but different connectors. Query alternative manufacturers or cost-effective substitutes.
- **Credit:** asked by Melissa Gilbert

## Distortion and FEP communication dual failure ⏳

*2024-05-26 · original list thread: “Element 2 issues” · status: unresolved*

- **Symptom:** Instrument distortion (overnight skip); skimmer o-ring replacement provides partial fix. After restart, unable to reestablish vacuum; turbos start but vacuum does not drop. FEP communication lost; computer in electronics box triggers alarm (reset sound at 16-second intervals).
- **Likely cause:** Skimmer o-rings fail again (old grease residue or new o-ring uneven coating); turbo timeout; FEP communication fault (network or hardware)
- **Fix / suggestions:** Not conclusively identified (further diagnosis required)
- **Credit:** asked by Ana Aguilar-Islas; answered by Don Chipley
