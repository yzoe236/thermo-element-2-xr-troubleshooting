# Unresolved Discussions

48 entries are explicitly flagged as awaiting a confirmed outcome as of 2026-10-20.
These include unresolved requests and a partial follow-up marked ⏳. Other entries
labelled partial may also have open questions. A proposed check is not a demonstrated fix.
If you have a documented resolution, please open an Add a solution issue.

## Plasma & Torch (2 entries; [details](subsystems/plasma-torch.md))

- **Ignition arcing damages torch-box viewing mesh; load-coil spots need assessment** (2026-10-20): While an Element XR interface-pump problem was being investigated, ignition arcing left a hole in the torch-box viewing mesh and two white marks on the load coil. The poster reported no apparent damage to the torch, bonnet or platinum guard electrode.
- **Torch component connector ignition wire fracture** (2024-09-26): Ignition wire fractures inside connector; wire stuck in hole.

## Electronics & FEP (7 entries; [details](subsystems/electronics-hv.md))

- **Frontend Error 89 with abnormal Instrument-page values despite green LEDs** (2026-09-07): An Element 2 showed abnormal values on the Instrument page and Error 89, blocking plasma ignition even though instrument LEDs were green and the network connection appeared functional.
- **Instrument fails to shut down normally after FEP motherboard power loss** (2026-01-22): E2 onboard processor power supply failure; instrument remains running but cannot communicate; cannot fully shut down (RF shuts off but coolant, interface pump remain running, skimmer valve stays open)
- **FEP heap corruption and startup failure** (2025-05-07): FEP displays "heap corruption detected"; boot disk replacement leaves it stuck at "system loading"; right-side yoyo inoperative
- **FEP motherboard replacement options and timing sensitivity** (2025-01-04): No direct issue; inquiry about finding replacement boards as new boards discontinuing soon.
- **High voltage fails to enable** (2024-10-16): HV does not start; voltage reads −5 or −10V with full red bar on display; unchanged after multiple restarts.
- **Recovered Element XR multiple hardware failures—FEP, scan card, detector board errors** (2024-09-27): AU offset calibration error; AU unresponsive; FEP Error 99. Frontend PC BIOS Net Mon section shows Err 15 and Err 16.
- **FEP CMOS reset and BIOS reconfiguration** (2024-08-14): Frontend CMOS unexpectedly reset; BIOS corrupted; motherboard only enters standby when PSU powered; requires pin-start method.

## Detector (8 entries; [details](subsystems/detector.md))

- **Sourcing a replacement Element XR detector (model MC-SEV-ICP-2)** (2026-08-05): Not a fault report but a purchasing question. The poster had decided to replace the detector on an Element XR, gave the fitted model as **MC-SEV-ICP-2**, and asked what sources exist besides the OEM.
- **Element XR detector sensitivity degradation and abnormal SEM voltage rise** (2026-05-04): Daily sensitivity decline requiring constant SEM voltage increase (1650V→2100V→2250V→2450V); In count on sample decreases from 1M cps to 400–600k cps progressively; autotune shows no plateau; diagnostic panel shows no fault indication
- **IDU board LED irregular flashing** (2025-09-23): IDU board LED flashing irregularly; unclear what normal operation should look like
- **Persistent background noise across full resolution range** (2025-08-18): Uniform background noise ~2e4 cps across all resolutions and mass range; detector voltage 2297V (new December 2024); multiple PC resets ineffective; torch/shield/cone/quick valve bypass/electronics reset all tried
- **Anomalous peak notch (crevasse) phenomenon** (2025-07-01): Element2 randomly shows central notch in multiple element peaks; not typical dark noise
- **Phosphorus element response anomaly with elevated detector voltage** (2025-05-02): After raising SEM voltage to 400V above plateau, sensitivity increased 2x but lowest concentration standard signal increased unexpectedly; middle concentrations non-proportional; some P species show no sensitivity gain; effect only at this voltage
- **ACF cross-calibration issue between analog and count modes after SEM replacement** (2024-12-16): After SEM swap, Ar36 signal shows non-smooth transition between red (analog 10^6–10^7 cps) and blue (count) peaks.
- **ElementXR Faraday 238U detection signal complete loss** (2024-08-05): No 238U signal on Faraday detector (expected 10^8 cps); only noise. Error 99 during initialization. ACF and FCF values appear normal.

## Software (12 entries; [details](subsystems/software.md))

- **ACQLIB code procedure 1 repeated with a frozen Instrument page and vacuum loss** (2026-09-17): An overnight run stopped and the Instrument application froze. After FEP communication was restored, the skimmer-valve-closed warning and a red TPA LED indicated vacuum loss. The reported error was 'ACQLIB code procedure 1 repeated'.
- **How to open Diagnostics window in Element II software** (2026-02-12): Cannot find diagnostics window in Element II software
- **Registry path error during scan** (2025-09-16): Tune scan launch shows "Cannot open registry key; SOFTWARE\finnigan\Element\Executive\Logfiles" error; loses instrument connection afterward
- **Triple-mode count/analog/Faraday data selection logic** (2025-06-11): How to select count vs. analog and analog vs. Faraday reporting in Triple mode?
- **Sequence operation capability without plasma on** (2025-06-03): Attempt to run sequence with plasma off; first line runs but sequence stops
- **Half-mass acquisition setup for 230Th/238U tail correction** (2025-04-30): For U-Th dating on Element 2, need to run a mass scan around ~238.5 and set up an acquisition that monitors signal at half-masses (e.g., 230.5) to quantify 238U tailing onto 230Th
- **Boron isotope deadtime measurement inconsistency** (2025-03-12): Element2 deadtime measurements inconsistent; repeated testing with U, Pb, Lu isotopes remain confused
- **FEP initialization error 89** (2025-02-10): Error 89 appears during FEP initialization and control computer; FEP direct trigger responds; occurred after Windows update; admin privileges reset.
- **Analog signal loss when selecting "Both" detector mode** (2024-12-13): Selecting "Both" (analog + count) in SHOW makes analog (red) signal disappear. Peak shows analog and count when selected individually, but both or in results—analog vanishes.
- **Sequence continues despite skimmer valve closure** (2024-08-30): Skimmer valve closes due to plasma failure; Executive registers error but Sequence continues running (option "Stop sequence if auto lock mass fails" not checked).
- **Element Executive window unresponsive after FEP connection** (2024-08-13): Executive window frozen; cannot move, minimize, or close; no send/receive blocks on network processor; appears in task-bar application list rather than top taskbar.
- **Element 2 software connection and operation slowdown/freeze** (2024-06-19): Element 2 (running since 2005) software version 3.1.2.242. FEP connection works (online data visible: vacuum, etc.), but opening Tune window or other functions (Method editor, etc.) causes extreme slowness or freeze. Tune window eventually opens; LAN connection then drops.

## Sample Introduction (2 entries; [details](subsystems/inlet-sample.md))

- **CETAC ASX-260 autosampler z-axis drive tube replacement method** (2026-05-11): Z-axis drive tube (green PEEK anti-twist tube SP7174) is damaged
- **ASX-100 autosampler failure after power supply replacement** (2026-01-21): After replacing ASX-100 power supply, front panel green light blinks indicating error

## Vacuum (3 entries; [details](subsystems/vacuum.md))

- **nXL110i interface pump seized after an extended shutdown** (2026-10-01): An Element 2 nXL110i interface pump would not turn after the instrument had been idle for more than two months. The rotor could not be moved manually.
- **Jet interface HV pressure anomaly diagnosis** (2025-03-25): After jet pump installation, rough vacuum 1.6e-3, high vacuum 3.8-4.2e-7, higher than literature values of 2-3e-7; no significant sensitivity improvement
- **Distortion and FEP communication dual failure** (2024-05-26): Instrument distortion (overnight skip); skimmer o-ring replacement provides partial fix. After restart, unable to reestablish vacuum; turbos start but vacuum does not drop. FEP communication lost; computer in electronics box triggers alarm (reset sound at 16-second intervals).

## Magnet (3 entries; [details](subsystems/magnet.md))

- **Diagnosing insufficient magnet current: low masses fine, high masses fail** (2026-07-08): Follow-up to the entry below. ¹¹B and Na scan normally, but while scanning them the magnet current in Diagnostic cycles between values like 0, 0.5, 0.75, 2 and stays **red**; scanning ²³⁸U alone reads 4.6 (green) — the same as when not scanning. Power supply is the **blank-front-panel type, part 2046670** (i.e. the Fast field regulator).
- **Magnet cannot drive high-mass scanning after cooler failure** (2026-07-07): Cooler failure caused magnet current trip; after recovery, high-mass peaks extremely small, narrow, and drift severely; Li peak normal; magnet current indicator intermittently red; multiple red lights on diagnostics panel
- **Magnet control indicator intermittent flashing** (2025-10-14): Magnet control lights red intermittently for seconds then green between Instrument and Tune modes; stays green after cover open; inserting safety switch tongue then closing shows closed-cover behavior

## Cones & Interface (2 entries; [details](subsystems/cones-interface.md))

- **Mid-resolution Fe-ArO interference difficult separation** (2025-06-25): After slit replacement, Fe-56 ArO interference cannot separate; sensitivity and UO oxide percentage high; lens and parameter optimization limited; lower RF power improves but drastically reduces sensitivity
- **Low-resolution sensitivity drop with mid-resolution unaffected** (2025-06-03): After slit replacement, LR In sensitivity drops from 1.4e6 cps to 700K; week later drops to 350K; MR In and resolution unchanged

## Maintenance (5 entries; [details](subsystems/maintenance.md))

- **Seeking Element 1 maintenance and data-acquisition upgrade services** (2026-10-10): An Element 1 owner sought a company able to maintain the instrument and upgrade its data-acquisition system.
- **ThermoFlex 2500 cooler HPC fault** (2025-10-15): Two ThermoFlex 2500 independently show HPC error; manual indicates building water supply issue but supply normal; errors mainly occur at plasma ignition or after
- **Wanted: trusted third-party suppliers for cones, torches, injectors, bonnets** (2025-03-27): Community effort to compile reliable third-party suppliers of sample/skimmer cones, torches, injectors, and bonnets compatible with Element 2 and Neoma (good quality, pricing, or lead time) to streamline procurement and avoid delays
- **Sourcing an obsolete Mass-Stream D-511 argon MFC (older Element)** (2025-03-21): An older Element needs a replacement **Mass-Stream D-511** mass flow controller (2 L/min argon); lab seeking working used units because the part is obsolete
- **Chiller water panel component leakage after 10 years operation** (2024-10-14): Water level in chiller drops significantly; puddle found under Element; leak between parts 13 and 10/11 on water panel.

## Other (4 entries; [details](subsystems/applications-other.md))

- **Ultra-pure tetrafluoroboric acid reagent procurement** (2025-12-17): Seek US supplier for ultra-pure HBF4 38% solution for ICP-MS sample prep (Fe<0.01ppm, SO4<0.5ppm)
- **Element2 and UV laser impact on ICD wearers** (2025-07-21): Inquire about Element2 and UV laser impact on ICD (implantable cardioverter-defibrillator) wearers
- **Gadolinium recovery problem with antimony coexistence** (2025-04-10): Gd recovery low when mixed with Sb standard; normal when measured separately
- **Feasibility of lead-in-whole-blood analysis on Element 2** (2024-07-05): Clinical trace-metal lab asked to evaluate whether an on-site Element 2 can be used to monitor lead in whole blood; wants a detailed analytical protocol plus the cost of maintenance, supplies, personnel, and ease of use
