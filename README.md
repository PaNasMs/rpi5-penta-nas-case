# PaNasMs Raspberry Pi 5 + Penta SATA HAT case

Pavlo Matviienko's working case adaptation for a compact DIY NAS built with a Raspberry Pi 5 and Radxa Penta SATA HAT. The original case was modified to improve cooling. This repository preserves the working CAD files, including separate fan-frame variants for 5010 and 6015 fans.

## Origin

Based on the [Radxa Penta SATA HAT NAS Case on GrabCAD](https://grabcad.com/library/radxa-penta-sata-hat-nas-case-1). Credit for the original design belongs to its original creators. This is a community adaptation, not an official Radxa product.

See the [PaNasMs build guide](https://panasms.github.io/hardware/rpi_radxa_penta/) for assembly photos, components and cooling wiring, and the [PaNasMs project](https://panasms.github.io/) for the NAS management software.

## CAD files

- `cad/step/`: exchange-format models for CAD applications.
- `cad/solidworks/`: editable SolidWorks part documents.
- `SHA256SUMS`: checksums of the preserved CAD files.

| Prefix | Part | Available formats |
| --- | --- | --- |
| 01 | Upper outer shell | STEP, SLDPRT |
| 02 | Top cover | STEP, SLDPRT |
| 03–06 | Corner inserts A–D | STEP |
| 07 | Upper inner frame | STEP, SLDPRT |
| 08 | Lower outer shell | STEP, SLDPRT |
| 09 … 5010fan | Lower inner frame, 50 × 50 × 10 mm fan variant | STEP, SLDPRT |
| 09 … 6015fan | Lower inner frame, 60 × 60 × 15 mm fan variant | STEP, SLDPRT |

The 6015 variant is the newer working frame, intended for the Noctua NF-A6x15 PWM used in this build. Choose one frame variant, not both. Other retained parts support the working assembly; their inclusion does not mean every part differs from the original design.

## Revision and printing status

These 16 files were copied byte-for-byte from the owner's working CAD directory on October 11, 2026. No geometry was regenerated or changed for publication.

This is a working CAD archive, not a newly validated print-ready release:

- Some STEP exports predate their corresponding SolidWorks source, notably the top cover and upper inner frame. The formats must not be assumed to represent identical revisions.
- No assembly document or bottom panel was present in this selected working directory. The original complete assembly and unrelated alternative cases are not bundled here.
- Older STL/3MF exports from a separate archive have deliberately not been mixed into this set. Export printable meshes from the chosen CAD revision and verify fit, fan clearance, orientation and supports before printing.
- Wiring diagrams are in the linked build guide; fan size alone does not specify electrical compatibility.

## Attribution and permissions

These files derive from the linked third-party case. The PaNasMs software license is not applied to these CAD files. No additional license grant is made here; consult the upstream model's terms and its author for reuse or redistribution permissions. This repository does not claim ownership of the original design.
