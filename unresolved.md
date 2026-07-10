# Unsolved Mysteries — Can You Crack One?

41 problems from the list were never conclusively solved. If you have
solved one of these (or have a strong lead), **please open an *Add a solution* issue** —
you may save another lab weeks of downtime.

## Plasma & Torch ([details](subsystems/plasma-torch.md))

- **Torch component connector ignition wire fracture** (2024-09-26) — Ignition wire fractures inside connector; wire stuck in hole.

## Electronics & FEP ([details](subsystems/electronics-hv.md))

- **Instrument fails to shut down normally after FEP motherboard power loss** (2026-01-22) — E2 onboard processor power supply failure; instrument remains running but cannot communicate; cannot fully shut down (RF shuts off but coola
- **FEP heap corruption and startup failure** (2025-05-07) — FEP displays "heap corruption detected"; boot disk replacement leaves it stuck at "system loading"; right-side yoyo inoperative
- **FEP motherboard replacement options and timing sensitivity** (2025-01-04) — No direct issue; inquiry about finding replacement boards as new boards discontinuing soon.
- **High voltage fails to enable** (2024-10-16) — HV does not start; voltage reads −5 or −10V with full red bar on display; unchanged after multiple restarts.
- **Recovered Element XR multiple hardware failures—FEP, scan card, detector board errors** (2024-09-27) — AU offset calibration error; AU unresponsive; FEP Error 99. Frontend PC BIOS Net Mon section shows Err 15 and Err 16.
- **FEP CMOS reset and BIOS reconfiguration** (2024-08-14) — Frontend CMOS unexpectedly reset; BIOS corrupted; motherboard only enters standby when PSU powered; requires pin-start method.

## Detector ([details](subsystems/detector.md))

- **Element XR detector sensitivity degradation and abnormal SEM voltage rise** (2026-05-04) — Daily sensitivity decline requiring constant SEM voltage increase (1650V→2100V→2250V→2450V); In count on sample decreases from 1M cps to 400
- **IDU board LED irregular flashing** (2025-09-23) — IDU board LED flashing irregularly; unclear what normal operation should look like
- **Persistent background noise across full resolution range** (2025-08-18) — Uniform background noise ~2e4 cps across all resolutions and mass range; detector voltage 2297V (new December 2024); multiple PC resets inef
- **Anomalous peak notch (crevasse) phenomenon** (2025-07-01) — Element2 randomly shows central notch in multiple element peaks; not typical dark noise
- **Phosphorus element response anomaly with elevated detector voltage** (2025-05-02) — After raising SEM voltage to 400V above plateau, sensitivity increased 2x but lowest concentration standard signal increased unexpectedly; m
- **ACF cross-calibration issue between analog and count modes after SEM replacement** (2024-12-16) — After SEM swap, Ar36 signal shows non-smooth transition between red (analog 10^6–10^7 cps) and blue (count) peaks.
- **ElementXR Faraday 238U detection signal complete loss** (2024-08-05) — No 238U signal on Faraday detector (expected 10^8 cps); only noise. Error 99 during initialization. ACF and FCF values appear normal.

## Software ([details](subsystems/software.md))

- **How to open Diagnostics window in Element II software** (2026-02-12) — Cannot find diagnostics window in Element II software
- **Registry path error during scan** (2025-09-16) — Tune scan launch shows "Cannot open registry key; SOFTWARE\finnigan\Element\Executive\Logfiles" error; loses instrument connection afterward
- **Triple-mode count/analog/Faraday data selection logic** (2025-06-11) — How to select count vs. analog and analog vs. Faraday reporting in Triple mode?
- **Sequence operation capability without plasma on** (2025-06-03) — Attempt to run sequence with plasma off; first line runs but sequence stops
- **Half-mass acquisition setup for 230Th/238U tail correction** (2025-04-30) — For U-Th dating, need to scan ~238.5 and monitor half-masses (e.g. 230.5) to quantify 238U tail onto 230Th; no on-list answer captured
- **Boron isotope deadtime measurement inconsistency** (2025-03-12) — Element2 deadtime measurements inconsistent; repeated testing with U, Pb, Lu isotopes remain confused
- **FEP initialization error 89** (2025-02-10) — Error 89 appears during FEP initialization and control computer; FEP direct trigger responds; occurred after Windows update; admin privilege
- **Analog signal loss when selecting "Both" detector mode** (2024-12-13) — Selecting "Both" (analog + count) in SHOW makes analog (red) signal disappear. Peak shows analog and count when selected individually, but b
- **Sequence continues despite skimmer valve closure** (2024-08-30) — Skimmer valve closes due to plasma failure; Executive registers error but Sequence continues running (option "Stop sequence if auto lock mas
- **Element Executive window unresponsive after FEP connection** (2024-08-13) — Executive window frozen; cannot move, minimize, or close; no send/receive blocks on network processor; appears in task-bar application list 
- **Element 2 software connection and operation slowdown/freeze** (2024-06-19) — Element 2 (running since 2005) software version 3.1.2.242. FEP connection works (online data visible: vacuum, etc.), but opening Tune window

## Sample Introduction ([details](subsystems/inlet-sample.md))

- **CETAC ASX-260 autosampler z-axis drive tube replacement method** (2026-05-11) — Z-axis drive tube (green PEEK anti-twist tube SP7174) is damaged
- **ASX-100 autosampler failure after power supply replacement** (2026-01-21) — After replacing ASX-100 power supply, front panel green light blinks indicating error

## Vacuum ([details](subsystems/vacuum.md))

- **Jet interface HV pressure anomaly diagnosis** (2025-03-25) — After jet pump installation, rough vacuum 1.6e-3, high vacuum 3.8-4.2e-7, higher than literature values of 2-3e-7; no significant sensitivit
- **Distortion and FEP communication dual failure** (2024-05-26) — Instrument distortion (overnight skip); skimmer o-ring replacement provides partial fix. After restart, unable to reestablish vacuum; turbos

## Magnet ([details](subsystems/magnet.md))

- **Magnet cannot drive high-mass scanning after cooler failure** (2026-07-07) — Cooler failure caused magnet current trip; after recovery, high-mass peaks extremely small, narrow, and drift severely; Li peak normal; magn
- **Magnet control indicator intermittent flashing** (2025-10-14) — Magnet control lights red intermittently for seconds then green between Instrument and Tune modes; stays green after cover open; inserting s

## Cones & Interface ([details](subsystems/cones-interface.md))

- **Mid-resolution Fe-ArO interference difficult separation** (2025-06-25) — After slit replacement, Fe-56 ArO interference cannot separate; sensitivity and UO oxide percentage high; lens and parameter optimization li
- **Low-resolution sensitivity drop with mid-resolution unaffected** (2025-06-03) — After slit replacement, LR In sensitivity drops from 1.4e6 cps to 700K; week later drops to 350K; MR In and resolution unchanged

## Maintenance ([details](subsystems/maintenance.md))

- **ThermoFlex 2500 cooler HPC fault** (2025-10-15) — Two ThermoFlex 2500 independently show HPC error; manual indicates building water supply issue but supply normal; errors mainly occur at pla
- **Wanted: trusted third-party suppliers for cones, torches, injectors, bonnets** (2025-03-27) — Community request to compile third-party consumables suppliers for Element 2 / Neoma; no list posted
- **Sourcing an obsolete Mass-Stream D-511 argon MFC (older Element)** (2025-03-21) — Older Element needs a Mass-Stream D-511 (2 L/min Ar) MFC; obsolete, no supplier surfaced
- **Chiller water panel component leakage after 10 years operation** (2024-10-14) — Water level in chiller drops significantly; puddle found under Element; leak between parts 13 and 10/11 on water panel.

## Other ([details](subsystems/applications-other.md))

- **Ultra-pure tetrafluoroboric acid reagent procurement** (2025-12-17) — Seek US supplier for ultra-pure HBF4 38% solution for ICP-MS sample prep (Fe<0.01ppm, SO4<0.5ppm)
- **Element2 and UV laser impact on ICD wearers** (2025-07-21) — Inquire about Element2 and UV laser impact on ICD (implantable cardioverter-defibrillator) wearers
- **Gadolinium recovery problem with antimony coexistence** (2025-04-10) — Gd recovery low when mixed with Sb standard; normal when measured separately
- **Feasibility of lead-in-whole-blood analysis on Element 2** (2024-07-05) — Clinical lab evaluating on-site Element 2 for Pb in whole blood; wants protocol + running costs; nothing posted
