# Start Here: Common Failure Patterns

This guide points into 138 indexed entries, including some follow-ups to the same
thread. The reports identify useful places to start looking; they are not a survey
from which failure rates or a diagnosis for another instrument can be calculated.

---

## 1. Front-End PC (FEP) failures

The FEP is a 1990s-architecture industrial PC, with recurring reports of motherboard failures (spares are drying up —
Element software is extremely timing-sensitive, so not every spec-compatible
board works), dead CMOS batteries scrambling the BIOS, corrupted boot disks
("system loading" hangs, RTTarget errors, heap corruption), flaky LAN
communication (NIC, RAM seating, antivirus interference), Error 89/99.

**Community survival kit:** any standard ATX PSU replaces the original FEP
supply; Rufus-built boot disks; reseating/reinstalling network adapters;
excluding the Element directory from antivirus scans; memtest86 for RAM.
**Advice: stockpile FEP spares (board, PSU, imaged boot disk) before you need
them.** → [electronics-hv.md](subsystems/electronics-hv.md)

## 2. The detector chain (SEM / IDU / ACF)

Classic storylines:
- *Sensitivity declining daily, SEM voltage creeping ever higher
  (1650 V → 2450 V)* = the SEM is dying. Replace it.
- *Count mode dead, analog fine, Faraday fine* = SEM supply board. The $9,500
  board can sometimes be repaired at board level — one lab's electronics tech
  attempted it with ~$30 of voltage references/regulators from Digi-Key.
  LEDs 6 & 7 lit yellow during scanning = board is bad ("98.995%" per a Thermo
  veteran).
- *Uniform dark noise across the whole mass range* = HV arcing through pinholes
  in Kapton foil (flight tube or field probe) — inspect and replace the foil.
- Post-SEM-swap chaos = redo deadtime and ACF cross-calibration properly; never
  measure isotope ratios in mixed detector modes.

→ [detector.md](subsystems/detector.md)

## 3. Plasma ignition & flameouts

Won't ignite: corroded ignition-cable connectors, load-coil position, cooling
water conductivity, chiller pressure below spec — even swapping the liquid-Ar
cylinder has been the culprit. Dies mid-run: cooling flow sensors (dirty paddle
wheels), RF generator overheating from blocked exhaust, high reflected power.
A stuck main gas valve is often just the ~$60 solenoid trigger.

**October 2026 update:** Arcing during interface-pump troubleshooting left a hole
in the torch-box viewing mesh and white marks on a load coil. No causal link to
the pump or confirmed coil failure was established. Replies considered superficial
marks possible; no successful repair or safe restart was reported. The original
manual requires replacement of a burned or damaged coil. A viewing-mesh hole and
guard-electrode damage are different observations and should be recorded separately.
→ [plasma-torch.md](subsystems/plasma-torch.md)

## 4. Power supplies

A cross-cutting theme: on a 20-year-old instrument, several reports trace faults to a failing power supply — inlet-system PSU,
FEP PSU, the bank of 24 V supplies in S1, the vacuum system's PSP-300-24, the
SEM supply board, the magnet power stage. The community's signature move is
replacing four-figure OEM supplies with generic industrial units
(Mean Well, Emerson) for tens of dollars.
→ [parts-and-substitutes.md](parts-and-substitutes.md)

## 5. Vacuum & mechanical

High-vacuum gauge reading an impossible e-11 = Penning gauge acting up (tap it,
reseat the RJ11, clean or replace the head). Turbopump trouble: swap TC100
controllers between pumps to isolate. Skimmer-valve o-rings age and quietly
ruin your vacuum or sensitivity — a repeat offender.
→ [vacuum.md](subsystems/vacuum.md)

## 6. Software and communications

Sequence editor bugs (long names crash it; >590 samples make it crawl; the
3.2.1.288 mass-drift check writes files to the wrong folder), "Both" detector
mode zeroing analog results (unresolved), method tables scrambling isotope
order. **Windows 11**: older threads report successful use of 3.2.1.288 in some labs. The October 2026
version discussion reports 3.2.1 as current at that time but does not establish
official Windows 11 certification.
→ [software.md](subsystems/software.md)

The September 2026 ACQLIB procedure 1 case also involved vacuum loss and remains
unresolved. It should not inherit the reboot outcome from the different July
procedure 31/2 discussion. Preserve exact error text and the order of events.

## 7. Magnet: rare but expensive

Mass drift over hours is almost always **temperature** (cooling instability),
not the magnet itself. True magnet power-stage failures (blown FETs after a
chiller event) are the hardest repairs on the machine — see the unresolved
2026 case with part numbers in [magnet.md](subsystems/magnet.md).

---

## Cooling can affect several subsystems

Cooling failures cascade: chiller hiccup → magnet current trip → mass drift →
plasma flameouts → ignition failures → cooked pre-amps. Several discussions involve cooling. Cooling maintenance is relevant to several subsystems. (Community consensus: distilled water only — no glycol, no
DI water which corrodes brass — replaced every ~3 months.)

## The community itself is the best spare part

A handful of veterans answer most questions — a former Thermo engineer,
electronics wizards, decades-long lab managers. Post to the list; someone has
seen your problem before. This repo exists to make their past answers findable.
