# Magnet & Mass Scanning

6 entries · newest first · [back to index](../README.md)

## Diagnosing insufficient magnet current: low masses fine, high masses fail ⏳

*2026-07-08 · original list thread: "E2 magnet problem" · status: partial*

- **Symptom:** Follow-up to the entry below. ¹¹B and Na scan normally, but while scanning them the magnet current in Diagnostic cycles between values like 0, 0.5, 0.75, 2 and stays **red**; scanning ²³⁸U alone reads 4.6 (green) — the same as when not scanning. Power supply is the **blank-front-panel type, part 2046670** (i.e. the Fast field regulator).
- **Likely cause:** Power-stage failure — the system (FR board / power stage / power supply) **cannot deliver the current needed for high masses**; more than one FET appears to have failed.
- **Fix / suggestions:** Useful diagnostic: **scan low masses (B/Na) versus ²³⁸U alone and compare the magnet current in Diagnostic** — red/cycling on low masses plus a static high-mass reading confirms insufficient current. (a) Safest test is to **swap in a known-good power stage** rather than testing FETs, since other parts of the power stage can also fail; Fast-version power stage is **P/N 2046641** or the newer **BRE0005622**. (b) FET-level repair demands serious electronics skill and may instead be a board-level fault controlling the FETs. (c) Realistically, **upgrade to a newer magnet power system** — Thermo will not attempt the repair and will only offer the upgrade; one lab reports the replacement system ran stably and trouble-free afterwards. Community help: a decommissioned E2 with a Fast magnet (likely compatible power stage/supply) was offered on-list.
- **⚠️ Safety:** The magnet supply puts out **90 V at 10 A** — enough to cause serious harm. As noted on-list, people worry about the 8 kV, but the magnet supply is the more dangerous one.
- **Credit:** asked by Thomas Marchitto; answered by Ted Zateslo, Louis A. Derry

## Magnet cannot drive high-mass scanning after cooler failure ⏳

*2026-07-07 · original list thread: “E2 magnet problem” · status: unresolved*

- **Symptom:** Cooler failure caused magnet current trip; after recovery, high-mass peaks extremely small, narrow, and drift severely; Li peak normal; magnet current indicator intermittently red; multiple red lights on diagnostics panel
- **Likely cause:** Not conclusively identified (suspected power-stage FET or magnet power-stage failure preventing generation of required high-mass magnetic field strength)
- **Fix / suggestions:** UNRESOLVED in thread; diagnostic approach: (a) borrow or purchase known-working power stage for testing; (b) optional FET replacement (high risk, requires electronics expertise); (c) upgrade to new magnet power system (expensive but recommended); relevant part numbers 2046641 or BRE0005622
- **Credit:** asked by Thomas Marchitto; answered by Joe Martineau, Ted Zateslo, Louis A. Derry

## Magnet power-stage fan check recommendation

*2026-05-14 · original list thread: “Magnet troubleshooting” · status: partial*

- **Symptom:** Magnet shows fault
- **Likely cause:** Not conclusively identified
- **Fix / suggestions:** Check whether fan in power stage is functioning normally
- **Credit:** answered by Chip

## Magnet control indicator intermittent flashing ⏳

*2025-10-14 · original list thread: “More magnet woes” · status: unresolved*

- **Symptom:** Magnet control lights red intermittently for seconds then green between Instrument and Tune modes; stays green after cover open; inserting safety switch tongue then closing shows closed-cover behavior
- **Likely cause:** Possible cover sensor association with HV safety protection circuit
- **Fix / suggestions:** UNRESOLVED in thread
- **Credit:** asked by Richard Ash

## Mass drift at analysis start and magnet sensor temperature dependency

*2025-07-22 · original list thread: “(no subject)” · status: solved*

- **Symptom:** Analysis starts with peak left of window; moves to center in seconds; approximately 5 min later repeats; all resolutions and masses affected
- **Likely cause:** Magnet sensor temperature drift or auto mass lock setting improper
- **Fix / suggestions:** Check chassis fan/heater and cooling system stability; check Mass Stability/Speed mode setting; adjust settling time and mass window; issue diagnosed
- **Credit:** asked by Richard Ash; answered by Matt Darnell, Adrian Reyes, Ted Huston, Rob Franks

## Low-resolution mass drift and cooling issue

*2025-06-25 · original list thread: “Mass Drift in LR” · status: solved*

- **Symptom:** LR peak drifts over hours; MR/HR also present but less severe; appears after cooling system electrical failure
- **Likely cause:** Cooler efficiency insufficiency causes unstable internal temperature
- **Fix / suggestions:** Repair cooling system efficiency; issue resolved
- **Credit:** asked by Claire Richards; answered by Joe Martineau, Christopher Coath, Rob Franks
