# Third-party notices

- OSEP GUI source: estea8968/OSEP, derived from Scratch GUI, BSD-3-Clause. The original `LICENSE` and `LICENSE-scratch-gui` are retained.
- OSEP's bundled Scratch VM source: the OSEP repository tracked a modified `node_modules/scratch-vm`; its BSD-3-Clause `LICENSE` is retained in `vendor/scratch-vm/`.
- Sipp Rabboni GUI artwork and 11-block VM implementation: nctutwtlab/scratch-gui `dev-rabboni` and nctutwtlab/scratch-vm `dev-rabonni`, both carrying BSD-3-Clause repository licenses. The VM implementation was adapted to use bounded JSONP requests and correct the apparent `gyroY` path typo.
- KNN: OSEP tracks a Git link to CodeLabClub/scratch3_knn but has no `.gitmodules`. That external repository did not contain a license in the inspected snapshot. Its source is **not** included; the local placeholder explicitly reports unavailability. Permission or an independently written implementation is required before claiming full OSEP feature parity.
- The user-supplied `Rabboni_Scratch API 2025` Windows application is **not included** in this repository. Its package contains third-party notices, but no redistribution license for the application was found in the inspected files. Users must obtain it through an authorized source.
- The direct USB transport was written for this project using the public Holtek HT42B564-x data sheet and physical packet observations. The GPL-3.0 Rabboni Python package was reviewed as a protocol reference; no package code or binary is included.
- The micro:bit v1/v2 HEX files were compiled from this project's `firmware/` TypeScript with Microsoft MakeCode `pxt-microbit` 9.1.2. Its MIT license text is retained at `firmware/LICENSE-makecode.txt`. Review transitive runtime notices for the compiled HEX before any public firmware distribution; no micro:bit hardware acceptance has been claimed.

Scratch and Scratch-related marks belong to their owners. The modified project is not endorsed by them.
