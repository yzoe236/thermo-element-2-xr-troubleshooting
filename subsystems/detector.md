# Detector (SEM / Faraday / IDU)

17 entries · newest first · [back to index](../README.md)

## Element XR detector sensitivity degradation and abnormal SEM voltage rise ⏳

*2026-05-04 · original list thread: “Element XR Detector issue” · status: unresolved*

- **Symptom:** Daily sensitivity decline requiring constant SEM voltage increase (1650V→2100V→2250V→2450V); In count on sample decreases from 1M cps to 400–600k cps progressively; autotune shows no plateau; diagnostic panel shows no fault indication
- **Likely cause:** Not conclusively identified (detector may be aging or SEM discharge tube failure)
- **Fix / suggestions:** UNRESOLVED in thread (requires professional service diagnosis)
- **Credit:** asked by Zikri Arslan

## SEM board troubleshooting for no-signal issue

*2026-05-01 · original list thread: “No signal” · status: solved*

- **Symptom:** SEM board LED shows orange (instead of green)
- **Likely cause:** SEM board failure
- **Fix / suggestions:** Replace SEM board
- **Credit:** answered by Yan Luo

## Peak shape anomaly and noise deterioration

*2025-12-03 · original list thread: “Peak problem” · status: partial*

- **Symptom:** Laser ablation peaks turn to "fence" noise not normal peaks; low mass more affected; problem suddenly worsened recently; multiple components already replaced
- **Likely cause:** Possible IDU board failure, optical element offset, or other multi-component combination issue
- **Fix / suggestions:** Focus check IDU board; adjust discriminator; adjust settling time and mass window; replace IDU board if needed; under diagnosis
- **Credit:** asked by Dirk Hoffmann; answered by Siv Dundas, Tim Wahl, Ted Zateslo, Don Chipley

## Detector plateau operation and deadtime accuracy

*2025-10-10 · original list thread: “detector cross calibration” · status: solved*

- **Symptom:** Does detector need ensuring at plateau? Is deadtime measurement accurate?
- **Likely cause:** N/A (technical inquiry)
- **Fix / suggestions:** Must operate at detector plateau; can model detector cross-calibration and nonlinearity drift
- **Credit:** asked by Jeremy Hourigan; answered by Martine LEERMAKERS

## IDU board LED irregular flashing ⏳

*2025-09-23 · original list thread: “Ion detection board yoyo” · status: unresolved*

- **Symptom:** IDU board LED flashing irregularly; unclear what normal operation should look like
- **Likely cause:** N/A (diagnostic inquiry)
- **Fix / suggestions:** UNRESOLVED in thread
- **Credit:** asked by Connor Hilton

## Persistent background noise across full resolution range ⏳

*2025-08-18 · original list thread: “Continous background” · status: unresolved*

- **Symptom:** Uniform background noise ~2e4 cps across all resolutions and mass range; detector voltage 2297V (new December 2024); multiple PC resets ineffective; torch/shield/cone/quick valve bypass/electronics reset all tried
- **Likely cause:** Possible IDU board discriminator potentiometer offset or SEM preamplifier failure
- **Fix / suggestions:** Turn IDU board discriminator TH knob ¼ clockwise or replace IDU board; UNRESOLVED in thread
- **Credit:** asked by Siv Dundas; answered by Tim Wahl

## Anomalous peak notch (crevasse) phenomenon ⏳

*2025-07-01 · original list thread: “crevasse in the peaks” · status: unresolved*

- **Symptom:** Element2 randomly shows central notch in multiple element peaks; not typical dark noise
- **Likely cause:** Not conclusively identified; possible detector issue
- **Fix / suggestions:** UNRESOLVED in thread
- **Credit:** asked by Cecilia Geisenblosen

## Dark noise 100,000 cps abnormally high

*2025-05-06 · original list thread: “Darknoise with ElementXR” · status: solved*

- **Symptom:** Uniform dark noise ~100,000 cps across full mass range, higher than normal; persists with GE off or skimmer off; SEM, extraction plate, new guard electrode replacements all ineffective
- **Likely cause:** Kapton foil insulation breakdown causing HV arcing, or SEM preamplifier failure
- **Fix / suggestions:** Check Kapton foil integrity; adjust IDU threshold knob; replace Kapton or field probe insulation as needed; issue resolved
- **Credit:** asked by Jessica Stammeier; answered by Siv Dundas, Lisa Stockli, Ted Zateslo

## Phosphorus element response anomaly with elevated detector voltage ⏳

*2025-05-02 · original list thread: “odd P behavior with increasing detector voltage” · status: unresolved*

- **Symptom:** After raising SEM voltage to 400V above plateau, sensitivity increased 2x but lowest concentration standard signal increased unexpectedly; middle concentrations non-proportional; some P species show no sensitivity gain; effect only at this voltage
- **Likely cause:** Not conclusively identified; possible ACF inaccuracy or detector nonlinearity
- **Fix / suggestions:** Lower voltage back to original setting eliminates issue; recommend optimize voltage with P-containing standard; UNRESOLVED in thread
- **Credit:** asked by Joshua Garber

## Uranium isotope ratio anomaly and detector mismatch

*2025-04-09 · original list thread: “U isotope ratios problems on SF-ICP-MS” · status: solved*

- **Symptom:** Post-repair U isotope ratios far exceed natural values (U234/238, U235/238, U236/238); deadtime tuning and SEM deflection optimization ineffective
- **Likely cause:** Detector sensitivity mismatch with pulse/analog mode conversion factor ACF, or pulse/analog mode voltage reversed
- **Fix / suggestions:** Recalibrate deadtime and ACF; or check detector mode circuit connections; avoid mixed-mode analysis for isotope ratios
- **Credit:** asked by Ge Xiao; answered by Ted Zateslo, Alexandre Voinot, Rob Franks, Siv Dundas, Dr. Robert Brause

## SEM supply board failure after routine maintenance

*2025-02-18 · original list thread: “ElementXR SEM issues!” · status: partial*

- **Symptom:** After SEM replacement, LR slit plate/tongue replacement, pump oil replacement—no count signal, only noise in analog mode. Faraday signal normal. SEM supply board LEDs 6 and 7 yellow (should be off). Board exchange between instruments confirms board defective.
- **Likely cause:** SEM supply board failure; voltage regulator or transformer fault; shared positive and negative output power supply possibly defective
- **Fix / suggestions:** Board exchange test confirms SEM supply board defective. Replace SEM supply board ($9,500 from Thermo) or attempt board-level repair ($30 parts if voltage regulator issue).
- **Credit:** asked by Martin Fleisher; answered by Ted Zateslo, Joe Martineau, Rob Franks

## SEM supply board failure causing count-mode signal loss

*2025-01-22 · original list thread: “Loss of counting signal” · status: partial*

- **Symptom:** Count-mode signal lost; analog mode normal. IDU low-voltage supply ~4.8V (low side). SEM supply board positive output LED shows overload; measured +ve output ~1/10 expected; −ve normal. Output voltage varies with software SEM voltage setting.
- **Likely cause:** SEM supply board failure; possible shared DC power supply secondary failure; board-level voltage regulator or transformer issue
- **Fix / suggestions:** Confirm SEM supply board failure by swapping with working Element. Possible board-level repair by adjusting voltage reference (estimate $30 parts vs $9,500 board cost). Possible voltage regulator failure.
- **Credit:** asked by Corey Archer; answered by Tim Wahl, Ted Zateslo

## ACF cross-calibration issue between analog and count modes after SEM replacement ⏳

*2024-12-16 · original list thread: “Issues potentially related to ACF calibration” · status: unresolved*

- **Symptom:** After SEM swap, Ar36 signal shows non-smooth transition between red (analog 10^6–10^7 cps) and blue (count) peaks.
- **Likely cause:** Possible incorrect cross-calibration procedure after SEM swap; peak alignment issue
- **Fix / suggestions:** Confirm correct cross-calibration procedure post-SEM swap. Seek guidance adjusting peak shape for smooth signal transition.
- **Credit:** asked by Wen-Hsuan Liao

## Count signal loss during analog-mode operation

*2024-12-10 · original list thread: “Defect detector” · status: partial*

- **Symptom:** No count signal; analog signal present; Faraday detector normal. After SEM board replacement, count mode extremely unstable and low.
- **Likely cause:** Ion detection power supply voltage too low (<4.8V); SEM power supply voltage (count mode) noisy or low; possible defective SEM board
- **Fix / suggestions:** Measure 5V output on IDU—if below 4.8V, adjust trimpot. Use high-voltage probe to check SEM power supply (hazard—expert only). Replace IDU power supply if needed. Possible SEM power supply issue requiring high-voltage testing.
- **Credit:** asked by Siv Dundas; answered by Ted Zateslo

## Count signal loss after interface pump water line disconnection

*2024-11-22 · original list thread: “No Signal element 2 in tune” · status: solved*

- **Symptom:** No count-mode signal in tune after interface pump cooling line disconnection. Field regulator amp lens 1 and 2 alternately display red. Fast field regulator board LED flickers irregularly during scans. Scan card possibly failed.
- **Likely cause:** Cooling line disconnection introduces air; magnet/temperature errors occur; pre-amp under ESA shell fails
- **Fix / suggestions:** Reconnect cooling line. Reset temperature sensor. Replace pre-amp under ESA shell (blue rectangle). Confirmed: count signal restores after pre-amp replacement.
- **Credit:** asked by Tim Wahl

## ElementXR Faraday 238U detection signal complete loss ⏳

*2024-08-05 · original list thread: “lost Faraday signal on ElementXR” · status: unresolved*

- **Symptom:** No 238U signal on Faraday detector (expected 10^8 cps); only noise. Error 99 during initialization. ACF and FCF values appear normal.
- **Likely cause:** Not conclusively identified; possible power supply issue or IDU board fault; suspect small SE supply board failure
- **Fix / suggestions:** Check −200V on IDU board; test SE supply board connected to ESA; consider IDU board or defective power supply replacement
- **Credit:** asked by Martin Fleisher; answered by Rob Franks, Matt Darnell, Thurid Luetzeler

## Rapid sensitivity loss after ventilation restart

*2024-07-06 · original list thread: “Poor sensitivity (not SEM related!)” · status: solved*

- **Symptom:** E2 forced offline for scheduled power outage on June 28. Sensitivity drops sharply day by day. Following advice to raise SEM voltage 100-200V; new SEM installed July 3. July 6 startup: sensitivity worse (~50%). New SEM saturates at 2800V (abnormally high). Fore vacuum normal. Run harsh samples but carefully inspected and cleaned cones.
- **Likely cause:** Skimmer valve o-ring failure; sample intro system blockage (nebulizer, injector o-rings); interface pump underperformance; possible electronics/SEM board issue
- **Fix / suggestions:** Try new cones and different kits. Check sample intro system response time and flow rate. Measure Ar/ArO relative strength versus baseline. Check diagnostic red lights. Ultimately: skimmer valve sticking and Fore Vacuum pressure elevated; o-ring replacement restores signal.
- **Credit:** asked by Alexis Floback; answered by Rob Franks, Marty Fleisher, Vivian Lai
