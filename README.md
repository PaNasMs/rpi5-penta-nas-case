# PaNasMs Raspberry Pi 5 + Penta SATA HAT case

Pavlo Matviienko's working case adaptation for a compact DIY NAS built with a Raspberry Pi 5 and Radxa Penta SATA HAT. Pavlo redesigned the case to improve airflow through the enclosure and cooling of the NAS components, particularly the disk bay. This repository contains the latest owner-selected version of the modified case, published from Pavlo's customized CAD folder on November 2, 2026.

## Origin

The starting point for this adaptation was the [Radxa Penta SATA HAT NAS Case on GrabCAD](https://grabcad.com/library/radxa-penta-sata-hat-nas-case-1). Credit for the original design belongs to its original creators; the airflow and cooling modifications in this working set were made by Pavlo Matviienko. This is a community adaptation, not an official Radxa product.

See the [PaNasMs build guide](https://panasms.github.io/hardware/rpi_radxa_penta/) for assembly photos, components and cooling wiring, and the [PaNasMs project](https://panasms.github.io/) for the NAS management software.

## CAD files

All 25 case files are in the repository root. `SHA256SUMS` records their checksums. SolidWorks documents are editable sources; STEP files are exchange models, and 3MF/STL files are supplied printing exports.

| Part | Files / formats |
| --- | --- |
| Bottom outer shell | `01-bottom-outer-shell` — SLDPRT, STEP, 3MF |
| Bottom shell without display | `01-bottom-outer-shell-no-display` — SLDPRT, STEP |
| Bottom shell without display or button | `01-bottom-outer-shell-no-display-no-button` — SLDPRT, STEP |
| Bottom cover | `02-bottom-cover` — SLDPRT, STEP, 3MF |
| Bottom inner frame | `03-bottom-inner-frame` — SLDPRT, STEP, 3MF |
| Top inner frame for a 6015 fan | `04-top-inner-frame-6015fan` — SLDPRT, STEP, 3MF |
| Top outer shell | `05-top-outer-shell` — SLDPRT, STEP, 3MF |
| Power button | `06-power-button.SLDPRT`, `power-button.STL`, `power-button.3mf` |
| Stand driver | `07-stand-driver.SLDPRT`, `stand-driver.STEP` |
| Assembly | `assy.SLDASM` |

Choose the bottom-shell variant matching your display and button arrangement. The older models, 5010 fan-frame variant and experimental derived models are no longer included in the current file set; previous published versions remain in Git history.

## Revision and printing status

This is the owner's current modified case. Files were copied byte-for-byte from the `customized` folder; no geometry or exports were regenerated during publication. The owner has completed the enclosure design and fit/printing work. This publication did not independently reopen the CAD assembly or validate each export against its SolidWorks source. Wiring and assembly details are in the linked build guide.

## Attribution and permissions

These files derive from the linked third-party case. The PaNasMs software license is not applied to these CAD files. No additional license grant is made here; consult the upstream model's terms and its author for reuse or redistribution permissions. This repository does not claim ownership of the original design.
