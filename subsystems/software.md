# Element Software

26 entries · newest first · [back to index](../README.md)

## Low recovery and poor calibration linearity in selenium analysis

*2026-05-21 · original list thread: “Selenium Element” · status: partial*

- **Symptom:** Soil and sediment samples via Aqua Regia and nitric+HF digestion methods show low chemical recovery; calibration exhibits extremely poor linearity in 0.05–1 ppb range
- **Likely cause:** Se requires high-resolution analysis with low sensitivity and high LOD; auto-generated multi-element methods unsuitable for Se; Se volatility high, exacerbated by HF and elevated temperature
- **Fix / suggestions:** (a) increase calibration standard concentration to 50 ppb; (b) add methanol or use low-flow methane to enhance ionization and sensitivity; (c) adjust method parameters (sample rate/peak count, integration window); (d) optional hydride generation approach via CETAC system; implement high-resolution analysis and careful tuning
- **Credit:** asked by Fernando Jiménez Barredo; answered by Siv Hjorth Dundas, Louis A. Derry, Heather Shrimpton

## Method editor software shows incompatibility error and interface anomaly

*2026-04-13 · original list thread: “Issue with Method editor software” · status: solved*

- **Symptom:** When clearing mass offsets in method, software can only open Periodic Table view; switching to spreadsheet view shows error "not compatible with latest version"
- **Likely cause:** IT network change caused software configuration corruption
- **Fix / suggestions:** Open Setup > Spreadsheet properties, load default Configuration File, reset table view
- **Credit:** asked by Meagan Ankney; answered by Vitor Barrote, Kirsten Widmayer

## How to open Diagnostics window in Element II software ⏳

*2026-02-12 · original list thread: “[SPAM] Diagnostics Window” · status: unresolved*

- **Symptom:** Cannot find diagnostics window in Element II software
- **Likely cause:** Not conclusively identified
- **Fix / suggestions:** UNRESOLVED in thread
- **Credit:** asked by Martine Leermakers

## Sequence evaluation crash with large datasets

*2025-10-13 · original list thread: “Sequence evaluation crashes” · status: partial*

- **Symptom:** Long-name sequences crash Element; 50-element large sequences also crash
- **Likely cause:** Sequence name too long or data file accumulation exceeds firmware limits
- **Fix / suggestions:** Create new sequence using same method/sample/report files; limit analyses ≤100; use known working template
- **Credit:** asked by Manuela Fehr; answered by Marty Fleisher, Yan Luo, Jeremy Hourigan

## Registry path error during scan ⏳

*2025-09-16 · original list thread: “Error when scanning” · status: unresolved*

- **Symptom:** Tune scan launch shows "Cannot open registry key; SOFTWARE\finnigan\Element\Executive\Logfiles" error; loses instrument connection afterward
- **Likely cause:** Software registry configuration or permission issue
- **Fix / suggestions:** UNRESOLVED in thread
- **Credit:** asked by Connor Hilton

## Host PC hardware specs for a Windows 11 replacement computer

*2025-07-23 · original list thread: “Spec for Windows 11 Computer” · status: solved*

- **Symptom:** Need the required host-PC specs to move an Element 2 onto a new, Windows 11-capable computer
- **Likely cause:** N/A (hardware-selection inquiry)
- **Fix / suggestions:** Element software is not picky about host specs — any reasonably powerful current desktop works. Recent factory Elements shipped with a **Dell OptiPlex XE4**; as Dell retires the OptiPlex name, the **Dell Pro Slim Desktop** is a good equivalent (base **Core i3** is adequate; **Core i5** worth the extra for a longer service life; base RAM/disk is fine just to run the instrument). Windows 11 is **not officially sanctioned by Bremen**, but several labs run Elements on it without known issues — follow the Windows 10 install instructions carefully and use the latest Element software version. (Complements the *Element 3.1.7 software and Windows 11* entry below, which covers the software-version side.)
- **Credit:** asked by Deborah Grimm; answered by Ted Huston

## Triple-mode count/analog/Faraday data selection logic ⏳

*2025-06-11 · original list thread: “Element Triple mode question” · status: unresolved*

- **Symptom:** How to select count vs. analog and analog vs. Faraday reporting in Triple mode?
- **Likely cause:** N/A (feature inquiry)
- **Fix / suggestions:** UNRESOLVED in thread
- **Credit:** asked by Martin Fleisher

## Windows 11 Element 3.2 installation configuration error

*2025-06-11 · original list thread: “Windows11 Element software” · status: solved*

- **Symptom:** Post-Win11 install can ignite plasma but instrument parameters incorrect (cool gas should show 18 displays 14); modification via Executive ineffective; diagnosis shows parameter range errors (torch Z shows -12 to +12 when should be -5 to +5mm)
- **Likely cause:** Win11 install steps incomplete or software version incompatible
- **Fix / suggestions:** Follow Win10 install instructions strictly step-by-step; use version 3.2.1 or later; issue resolved
- **Credit:** asked by Fernando Jiménez Barredo; answered by Ted Zateslo, Alexandre Voinot

## Sequence operation capability without plasma on ⏳

*2025-06-03 · original list thread: “measuring without plasma on” · status: unresolved*

- **Symptom:** Attempt to run sequence with plasma off; first line runs but sequence stops
- **Likely cause:** Software lacks support for this feature
- **Fix / suggestions:** UNRESOLVED in thread
- **Credit:** asked by Christopher Coath

## Half-mass acquisition setup for 230Th/238U tail correction ⏳

*2025-04-30 · original list thread: “how to monitor/quantify signal on a half mass?” · status: unresolved*

- **Symptom:** For U-Th dating on Element 2, need to run a mass scan around ~238.5 and set up an acquisition that monitors signal at half-masses (e.g., 230.5) to quantify 238U tailing onto 230Th
- **Likely cause:** N/A (method-configuration question)
- **Fix / suggestions:** UNRESOLVED in thread — no on-list answer captured. Half-mass monitoring is normally done by entering non-integer masses in the method/scan table; if you have a working recipe, please contribute.
- **Credit:** asked by Dan Sinclair

## Safety assessment of FEP reset while plasma operating

*2025-03-26 · original list thread: “Front end PC reset whilst plasma on” · status: solved*

- **Symptom:** Is FEP reset safe while plasma running; front vacuum reading stuck, NP cannot initialize
- **Likely cause:** FEP-host communication anomaly causes state desynchronization
- **Fix / suggestions:** Safe to reset FEP; after cover closed both PCs resynchronize; issue resolved
- **Credit:** asked by Sophie Slater; answered by Marcel Guillong

## Boron isotope deadtime measurement inconsistency ⏳

*2025-03-12 · original list thread: “Challanges to determine Deadtime” · status: unresolved*

- **Symptom:** Element2 deadtime measurements inconsistent; repeated testing with U, Pb, Lu isotopes remain confused
- **Likely cause:** Not conclusively identified
- **Fix / suggestions:** UNRESOLVED in thread
- **Credit:** asked by Emmi Myllykylä

## Missing .inf file when exporting large sequence data

*2025-03-07 · original list thread: “inf file _does not exist” · status: solved*

- **Symptom:** After 340 external trigger analyses, cannot export data; file not found and .inf file missing errors; Show application cannot rebuild chromatogram
- **Likely cause:** Large dataset frontend PC data processing overload causes incomplete analysis records
- **Fix / suggestions:** Reset affected analyses and re-export
- **Credit:** asked by Jakub Sliwinski; answered by Andreas

## Element 3.1.7 software Windows 11 upgrade compatibility

*2025-02-17 · original list thread: “Element 3.1.7 software and Windows 11” · status: solved*

- **Symptom:** No problem; compatibility inquiry.
- **Likely cause:** Not applicable
- **Fix / suggestions:** Latest Element software is 3.2.1.288, officially supports Windows 10. No official Windows 11 certification (Bremen). Unofficial: 3.2.1.288 reported working on ~3 labs' Win11 for up to 1 year; no issues reported but small sample size.
- **Credit:** asked by Andreas Möller; answered by Ted Zateslo

## FEP initialization error 89 ⏳

*2025-02-10 · original list thread: “Error message 89 from frontend” · status: unresolved*

- **Symptom:** Error 89 appears during FEP initialization and control computer; FEP direct trigger responds; occurred after Windows update; admin privileges reset.
- **Likely cause:** Not conclusively identified—possible Windows update side-effect; network communication issue
- **Fix / suggestions:** UNRESOLVED in thread
- **Credit:** asked by Andreas Helmle

## Sequence editor halts with file-not-found error during mass offset check

*2024-12-17 · original list thread: “Element-2 sequence editor stops with an error during a Mass” · status: partial*

- **Symptom:** Since software update 3.1.7.278 to 3.2.1.288, sequence randomly stops during auto lock mass check (1–2×/day). Mass offset DAT file written to wrong folder. Example: checking 02_SEQ182 finds file in 02_SEQ182_test folder instead of CheckMassDrift folder.
- **Likely cause:** Software bug—sequence editor reads/writes mass offset files to/from incorrect folder; old sequence folder reference cached in file
- **Fix / suggestions:** Use short sequence names. Clean data folder. Possible fix in next software version. Avoid reusing prior sequences with old folder references.
- **Credit:** asked by Wim Boer

## Analog signal loss when selecting "Both" detector mode ⏳

*2024-12-13 · original list thread: “Analog signal not reported in results” · status: unresolved*

- **Symptom:** Selecting "Both" (analog + count) in SHOW makes analog (red) signal disappear. Peak shows analog and count when selected individually, but both or in results—analog vanishes.
- **Likely cause:** Software bug—analog signal zeroed when "both" detector mode selected in method
- **Fix / suggestions:** UNRESOLVED in thread
- **Credit:** asked by George Kamenov

## FEP communication issue resolved via network adapter reset

*2024-12-11 · original list thread: “Front-end PC or communication issue_ - hopefully solved now” · status: solved*

- **Symptom:** FEP-measurement PC communication problems cause slowness.
- **Likely cause:** Network adapter driver or configuration issue
- **Fix / suggestions:** In Device Manager, remove both network adapters (FEP and facility network) without removing drivers. Restart—adapters auto-reinstall. Reconfigure FEP IP address and subnet mask. Clean data folder. System stable >3 days without PC restart.
- **Credit:** asked by Wim Boer

## Intermittent FEP communication timeout and network data stagnation

*2024-12-06 · original list thread: “Front-end PC or communication issue” · status: partial*

- **Symptom:** FEP software sometimes unresponsive or sluggish; transmit 8 kbps but receive 0 kbps. FEP power cycle resolves temporarily. All errors appear; instrument unusable before restart.
- **Likely cause:** FEP network processor window performance degradation; network interface card failure; communication latency
- **Fix / suggestions:** Restart Element software before each plasma ignition. Daily restart of network processor. Consider replacing NIC in FEP.
- **Credit:** asked by Wim Boer; answered by Rembert Breidenbach, Christopher Coath

## Long sequence length handling and performance optimization

*2024-11-20 · original list thread: “sequence length” · status: solved*

- **Symptom:** Software sluggish when running 592-sample sequence.
- **Likely cause:** Large sequence size causes software performance degradation
- **Fix / suggestions:** Run sequences of 590 samples or fewer. Disable evaluate during sequence collection—evaluate after run completion. Multiple users successfully run 598-sample sequences.
- **Credit:** asked by Anastasia Skipor; answered by Johannes Zieger, Lisa Stockli, Andreas Möller

## Sequence Editor CSV import missing Sampling/Inlet File header

*2024-10-24 · original list thread: “Sequence Editor - import” · status: solved*

- **Symptom:** CSV import does not recognize "Sampling" header for ext_trigger.inl file configuration.
- **Likely cause:** Incorrect header name in CSV template
- **Fix / suggestions:** Use "Inlet File" as correct header name instead of "Sampling". Reference KeyDefinitions.kdf file for valid headers.
- **Credit:** asked by Wim Boer; answered by Torsten Lindemann

## Isotope sequence disorder in method table

*2024-10-18 · original list thread: “Order of isotopes in the method _ wrong mass order in method” · status: partial*

- **Symptom:** After adding 49Ti, 118Sn, 204Pb, 238U to method, they display in wrong sequence in method table (45Sc, 118Sn, 204Pb–238U, then 49Ti).
- **Likely cause:** "Auto sort table" feature appears to randomly disable during method editing
- **Fix / suggestions:** Manually enable "Auto sort table"; unclear whether sort order affects data quality for that scan
- **Credit:** asked by Sebastian

## K peak drift beyond measurement window in cool plasma mode

*2024-09-27 · original list thread: “HR cool plasma K peaks shift” · status: solved*

- **Symptom:** 39K/41K peaks exit measurement window within hours of mass offset determination; peak position unstable; unable to maintain resolution; integrated area values become irregular.
- **Likely cause:** Heater beneath hood nonfunctional (confirmed: 200mA fuse burned); temperature drift affects peak position; auto lock mass ineffective for Ar2 dimers in cool plasma mode
- **Fix / suggestions:** Replace burned fuse in heater (resolved). Use MLM (manual lock mass) with alternative gas (N2/O2). Toggle between cool/hot plasma modes. Use speed mode with prescans rather than mass accuracy mode.
- **Credit:** asked by Martin Fleisher; answered by Rob Franks, Robert Brause, Joachim Hinrichs

## Sequence continues despite skimmer valve closure ⏳

*2024-08-30 · original list thread: “Sequence did not know the skimmer valve closed” · status: unresolved*

- **Symptom:** Skimmer valve closes due to plasma failure; Executive registers error but Sequence continues running (option "Stop sequence if auto lock mass fails" not checked).
- **Likely cause:** Software limitation—Sequence does not monitor skimmer valve status unless auto lock mass fails
- **Fix / suggestions:** User requests firmware/software modification so Sequence checks skimmer valve status and stops accordingly
- **Credit:** asked by Tom Marchitto

## Element Executive window unresponsive after FEP connection ⏳

*2024-08-13 · original list thread: “E2 software executive nonresponsive” · status: unresolved*

- **Symptom:** Executive window frozen; cannot move, minimize, or close; no send/receive blocks on network processor; appears in task-bar application list rather than top taskbar.
- **Likely cause:** Host PC issue or FEP communication problem after connection
- **Fix / suggestions:** Replace Ethernet cable; relocate network card on FEP; multiple restarts of FEP and host. Issue unresolved.
- **Credit:** asked by Anastasia Skipor

## Element 2 software connection and operation slowdown/freeze ⏳

*2024-06-19 · original list thread: “Software problems” · status: unresolved*

- **Symptom:** Element 2 (running since 2005) software version 3.1.2.242. FEP connection works (online data visible: vacuum, etc.), but opening Tune window or other functions (Method editor, etc.) causes extreme slowness or freeze. Tune window eventually opens; LAN connection then drops.
- **Likely cause:** Frontend PC hardware or network communication issue; possible software upgrade needed
- **Fix / suggestions:** Consider software upgrade; check RAM card (previous RAM issues reported on frontend PC); not conclusively resolved
- **Credit:** asked by Eva Szeleseva; answered by Eva Stueeken
