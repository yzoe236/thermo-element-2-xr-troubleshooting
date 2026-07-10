# Electronics, High Voltage & Front-End PC (FEP)

20 entries · newest first · [back to index](../README.md)

## High detector noise caused by Kapton foil damage or internal arcing

*2026-06-24 · original list thread: “Detector noise due to arcing” · status: solved*

- **Symptom:** 100+ kcps noise present when laser mode activated; noise occurs across all detection modes and mass points; noise disappears when HV turned off
- **Likely cause:** Kapton foil pinhole damage on flight tube; or Kapton foil damage on field probe; or internal insulator arcing traces near exit slit or quad
- **Fix / suggestions:** (a) first remove field probe and inspect its Kapton foil (relatively simple); (b) if needed, replace Kapton foil between flight tube and magnet; (c) clean white insulator below exit slit/quad using 1200 grit sandpaper
- **Credit:** asked by Sebastian Kommescher; answered by Tim Wahl, Lisa Stockli, Ted Zateslo

## E2 FEP LAN communication with main controller unstable

*2026-03-09 · original list thread: “E2 LAN communication dropping off” · status: partial*

- **Symptom:** After electronics restart, communication normal briefly, then stops after minutes to hours with complete loss of communication; when communication lost, FEP left-side yoyo indicator stops flashing, front panel buttons unresponsive, manual power switch toggle required to restart
- **Likely cause:** FEP communication card failure; FEP motherboard failure; FEP memory module poor contact; CPU fan failure causing overheating; main controller computer failure; antivirus software interference
- **Fix / suggestions:** Remove and reinstall FEP communication card or move to different slot; check memory module contacts; check CPU fan operation; configure antivirus to exclude Element directory; replace communication card; if needed, replace main controller computer
- **Credit:** asked by Thomas Marchitto; answered by Eva Stueeken, Anastasia K Skipor, Gimena Colombo, Lisa Stockli, Jeffrey Colussy, Christopher Coath

## Instrument fails to shut down normally after FEP motherboard power loss ⏳

*2026-01-22 · original list thread: “Element shut down” · status: unresolved*

- **Symptom:** E2 onboard processor power supply failure; instrument remains running but cannot communicate; cannot fully shut down (RF shuts off but coolant, interface pump remain running, skimmer valve stays open)
- **Likely cause:** FEP motherboard failure
- **Fix / suggestions:** Press S1 switch to cut power (poor design; no other normal shutdown method); FEP motherboard must be replaced
- **Credit:** asked by Richard Ash; answered by Matt Darnell, Heather

## Element XR FEP power supply replacement options

*2026-01-07 · original list thread: “replacement Element XR FEP PSU” · status: solved*

- **Symptom:** FEP switch PSU (FSP300-70PFL) fails; market shortage and refurbished units expensive
- **Likely cause:** N/A (hardware replacement inquiry)
- **Fix / suggestions:** Any standard ATX PSU compatible (verify size); online market (Newegg) has economical options
- **Credit:** asked by Ethan Goddard; answered by Ted Zateslo

## Element XR network initialization failure

*2025-10-27 · original list thread: “ElementXR Instrument not initializing” · status: partial*

- **Symptom:** After S2/FEP restart, network connects but no readouts and buttons unresponsive; subsequent restart stalls at network init window; left yoyo shows no red LED
- **Likely cause:** FEP-host severe clock offset or boot issue or motherboard failure
- **Fix / suggestions:** Reset FEP and main BIOS time/date; check sync
- **Credit:** asked by Martin Fleisher; answered by Ted Zateslo

## High-voltage startup failure and 24V supply anomaly

*2025-09-09 · original list thread: “High voltage_power supply problems” · status: partial*

- **Symptom:** Cover down, HV cannot start, reads -514V; below S1/S2 power box repeating click sounds; HV Electronics and High Vac LEDs flashing red-green; multiple board LEDs flashing; settings desynchronized
- **Likely cause:** Multiple 24V supply failures or S2-below PD unit distributor failure
- **Fix / suggestions:** Check output voltage of four 24V supplies in S1 unit or check PD distribution unit and power lines
- **Credit:** asked by Calum Greenhalgh; answered by Christopher Coath

## Element XR ignition failure and power supply fault

*2025-05-21 · original list thread: “Element XR - ignition problem faulty board or power supply” · status: solved*

- **Symptom:** Cannot ignite plasma; top power board LED off; LED on at same location in working instrument
- **Likely cause:** Power board or its power supply failure
- **Fix / suggestions:** Power supply located right of problem board; original Thermo expensive; can substitute Mean Well QP-320F with minor rewiring, approximately $60
- **Credit:** asked by Zikri Arslan; answered by Melissa Gilbert

## FEP boot failure resolved

*2025-05-13 · original list thread: “Lost communication with front end computer_ Element XR (Solv” · status: solved*

- **Symptom:** See 2025-05-07 (FEP heap corruption, stuck at system loading)
- **Likely cause:** Boot disk corruption
- **Fix / suggestions:** Create new boot disk using Rufus 4.0
- **Credit:** asked by Rachel Dennis

## FEP heap corruption and startup failure ⏳

*2025-05-07 · original list thread: “Lost communication with front end computer_ Element XR” · status: unresolved*

- **Symptom:** FEP displays "heap corruption detected"; boot disk replacement leaves it stuck at "system loading"; right-side yoyo inoperative
- **Likely cause:** Memory failure or boot disk corruption
- **Fix / suggestions:** Replace RAM or rebuild boot disk; UNRESOLVED in thread
- **Credit:** asked by Rachel Dennis; answered by Grant Craig

## Plasma ignition failure and vacuum check anomaly

*2025-04-18 · original list thread: “Ignite plasma issue, communication or hardware problem” · status: partial*

- **Symptom:** Cannot ignite plasma post-repair; vacuum check fails; front and high vacuum readings frozen; cannot obtain software information
- **Likely cause:** FEP-host communication anomaly or vacuum sensor power loss or insufficient power
- **Fix / suggestions:** Check 24V power supply on PD distribution unit and all related board connections; try complete S1/S2 and main unit power down then restart
- **Credit:** asked by Linhan (Leo) Li; answered by Richard Ash, Tim Wahl, Ted Zateslo, Andreas Möller

## New FEP communication failure and restart button wiring

*2025-04-14 · original list thread: “FEP and Communications” · status: partial*

- **Symptom:** New FEP installed 18 months ago finally loses communication; replacing with old FEP but pin configuration differs; restart switch wire connection location unknown
- **Likely cause:** Motherboard differences cause different wire position
- **Fix / suggestions:** Check motherboard model and consult manual to determine restart switch wiring
- **Credit:** asked by Richard Ash; answered by Christopher Coath

## Front-end PC fails to boot after reset

*2025-03-11 · original list thread: “FEP not booting up” · status: partial*

- **Symptom:** FEP reset button unresponsive; screen shows RTTarget error; FEP attempts USB boot with no progress
- **Likely cause:** CMOS battery depletion restores BIOS to defaults, or USB boot disk corrupted, or motherboard failure
- **Fix / suggestions:** Replace CMOS battery, test RAM with memtest86, try known-working USB boot disk or boot from floppy
- **Credit:** asked by Jakub Sliwinski; answered by Ted Zateslo, Tim Wahl

## Element XR detector sensitivity loss and ESA anomaly

*2025-03-05 · original list thread: “Element XR SEM issue - similar to Marty Fleischer's issue” · status: partial*

- **Symptom:** After laser ablation of archaeological silver sample, sensitivity drops sharply; replacement with new SEM yields no count signal; HV-related indicator lights abnormal during diagnosis
- **Likely cause:** Possible ESA ground short circuit or HV regulator board failure
- **Fix / suggestions:** Check HV regulator board and investigate ESA short circuit, disconnect output line for testing; circuit-level diagnosis or motherboard replacement required
- **Credit:** asked by Joshua M. Garber; answered by Christopher Coath

## FEP motherboard replacement options and timing sensitivity ⏳

*2025-01-04 · original list thread: “FEP motherboard replacements” · status: unresolved*

- **Symptom:** No direct issue; inquiry about finding replacement boards as new boards discontinuing soon.
- **Likely cause:** Not applicable
- **Fix / suggestions:** Query which replacement boards users have successfully deployed. Element FEP software extremely timing-sensitive; many spec-compliant boards may not work. Seek currently available boards with known working status.
- **Credit:** asked by Ted Zateslo

## Hood safety interlock triggers spuriously and disables HV

*2024-11-21 · original list thread: “Interlock hood safety interlock engaging for no apparent rea” · status: partial*

- **Symptom:** HV and interlock hood LED turn red despite no manual interlock adjustment; issue disappears after multiple hood open/close cycles or power cycle. Magnetic field regulator and temperature field regulator also trigger; auxiliary gas reading elevated.
- **Likely cause:** Hood interlock switch failure; PD controller circuit issue; interlock switch or actuator misalignment
- **Fix / suggestions:** Check front and rear hood interlock switches and "keys" to activate them. Verify hood seated correctly. Adjust switch/actuator position by loosening mounting screws.
- **Credit:** asked by Maya Reimi; answered by Ted Zateslo

## High voltage fails to enable ⏳

*2024-10-16 · original list thread: “HV off” · status: unresolved*

- **Symptom:** HV does not start; voltage reads −5 or −10V with full red bar on display; unchanged after multiple restarts.
- **Likely cause:** Suspected Kapton hole or HV board/power supply fault
- **Fix / suggestions:** Disconnect HV outlet—if HV starts, board is normal. Check hood interlocks to rule out interlock issues. Inspect for discharge in dark lab.
- **Credit:** asked by Martin Fleisher; answered by Matt Darnell

## Recovered Element XR multiple hardware failures—FEP, scan card, detector board errors ⏳

*2024-09-27 · original list thread: “Issues probably related to FEP and ion detector board” · status: unresolved*

- **Symptom:** AU offset calibration error; AU unresponsive; FEP Error 99. Frontend PC BIOS Net Mon section shows Err 15 and Err 16.
- **Likely cause:** Possible FEP hardware fault or BIOS configuration issue; AU (analog unit) failure
- **Fix / suggestions:** Investigate BIOS settings; sequentially exchange AU, scan cards, and ion detector boards; issue unresolved after component swaps
- **Credit:** asked by Wen-Hsuan Liao

## FEP freeze during tune and scan operations

*2024-09-13 · original list thread: “E2 programs Slow_Freeze when scanning” · status: partial*

- **Symptom:** LAN connection lost on scan initiation; instrument slows; tune page grayed; recovery only via RF button. Fast field regulator LED flickers irregularly during scans. All scans missing mid-range peaks. Two PSOU LEDs illuminate.
- **Likely cause:** Possible new FEP RAM insufficient (1GB vs 2GB); scan card failure; or host PC issue
- **Fix / suggestions:** Relocate scan card; install additional RAM; test with different host; check FEP fan operation and power supply voltage
- **Credit:** asked by Tim Wahl; answered by Ted Zateslo

## FEP CMOS reset and BIOS reconfiguration ⏳

*2024-08-14 · original list thread: “BIOS configuration for EL2 Frontend” · status: unresolved*

- **Symptom:** Frontend CMOS unexpectedly reset; BIOS corrupted; motherboard only enters standby when PSU powered; requires pin-start method.
- **Likely cause:** CMOS unexpectedly reset
- **Fix / suggestions:** Need step-by-step BIOS reconfiguration guide; query USB boot instructions and USB program copy procedures
- **Credit:** asked by Vitor Barrote

## FEP motherboard communication loss and recovery

*2024-07-30 · original list thread: “Connection Between Computer and FEP” · status: solved*

- **Symptom:** Element 2 loses FEP communication after university firewall update. FEP fails to boot after restart.
- **Likely cause:** FEP power supply failure; BIOS corruption (after battery replacement); possible network adapter issue
- **Fix / suggestions:** Replace FEP power supply; reset BIOS by pin-shorting; factory assistance to reconfigure IP address. Follow-up: IT department reinstalls network adapter in Device Manager; reconfigure IP address; clean data folders. System stable >3 days without restart.
- **Credit:** asked by Tim Wahl; answered by Laurel McEllistrem, Anastasia Skipor, Christopher Coath
