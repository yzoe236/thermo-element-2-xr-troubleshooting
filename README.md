# Thermo Element ICP-MS Community Troubleshooting Knowledge Base

A searchable, subsystem-organized index of real-world troubleshooting discussions
for **Thermo Element 2 / Element XR** (sector-field HR-ICP-MS) instruments,
distilled from the community mailing list **the Element mailing list (lists.ucsc.edu)** (2024–2026).

These aging instruments have limited official support. The collective experience
of the user community — what broke, what it turned out to be, and what fixed it —
is often the fastest path to a repair. This repo makes that experience findable.

**119 entries** across 10 subsystems · 37 still unresolved (marked ⏳)
· last updated 2026-07-09

## Browse by subsystem

| Subsystem | Entries |
|---|---|
| [Plasma, Torch & RF](kb/plasma-torch.md) | 10 |
| [Electronics, High Voltage & Front-End PC (FEP)](kb/electronics-hv.md) | 20 |
| [Detector (SEM / Faraday / IDU)](kb/detector.md) | 17 |
| [Element Software](kb/software.md) | 24 |
| [Sample Introduction (Nebulizer / Autosampler / MFC)](kb/inlet-sample.md) | 12 |
| [Vacuum System (Pumps & Gauges)](kb/vacuum.md) | 6 |
| [Magnet & Mass Scanning](kb/magnet.md) | 5 |
| [Cones, Slits & Interface](kb/cones-interface.md) | 3 |
| [Maintenance, Chiller & Spare Parts](kb/maintenance.md) | 11 |
| [Applications & Other](kb/applications-other.md) | 11 |

## How to use

**Three ways to find your problem:**

1. **Search** — use the GitHub search box at the top of this repo (press `/`)
   with a symptom keyword, e.g. `no signal counting mode`, `Error 89`,
   `heap corruption`, `plasma ignition`, `SEM supply board`. GitHub full-text
   indexes every entry.
2. **Browse by subsystem** — go to the `kb/` file that matches where the problem
   lives (detector, plasma, FEP/electronics, …). Entries are newest-first;
   `Ctrl+F` within the page narrows it down.
3. **Trace back to the full discussion** — every entry cites the *original list
   thread subject and date*. Search that subject in the mailing-list archive
   (or your own inbox if you're a subscriber) to read the complete exchange and
   find who to talk to.

Each entry is structured **Symptom → Likely cause → Fix**, with the people who
asked/answered credited by name. ⏳ marks problems that were never conclusively
solved on-list — if you've solved one, please contribute!

## Contributing (this is the "ticket system")

- **Had a problem that's not listed?** Open an issue with the *Report a problem* template.
- **Solved something (especially a ⏳ entry)?** Open an issue with the *Add a solution* template.
- **Found an error?** Open a *Correction* issue.
- Pull requests editing the `kb/*.md` files directly are welcome too.

## Privacy & attribution

- Entries are **summaries**, not reproductions of list emails. Full context lives
  in the mailing-list archive.
- Contributor **names are kept for credit; email addresses are deliberately
  removed** from this public index.
- If you are credited here and would like your name removed or corrected, open
  an issue — it will be done promptly, no questions asked.

## Disclaimer

Community-compiled information, provided as-is, **no warranty**. Several
procedures involve **lethal high voltages** and delicate components — if you are
not qualified, don't. Verify part numbers and prices independently; they reflect
the time of the original discussion.

## Acknowledgements

All credit belongs to the members of the Element mailing list, whose generosity
with hard-won knowledge keeps these instruments alive.

*Maintained by Linhan (Leo) Li, MATFab, University of Iowa. Index generated with
AI assistance from personal mailing-list archives; curated by hand.*
