# RevEng_Bosch_BCS220

**Reverse engineering of the Bosch eBike Charger 36‑4 / 230 (BCS220)**  
PCB layout and schematics reconstruction.

---

## Purpose and Scope

This project documents the reverse engineering of the **Bosch BCS220 eBike charger**, focusing on:

- PCB analysis  
- Reconstructed schematics  
- Component identification  
- Repair and fault analysis  
- Interoperability research  
- Technical documentation for educational purposes  

The goal is to **support repairability, understanding, and interoperability** of existing hardware, especially in cases where original documentation is unavailable.

---

## Legal and Ethical Notice

This project is intended **solely for research, repair, interoperability, and documentation purposes**.

- **No original firmware** is included  
- **No trademarks** are used in a misleading way  
- **No proprietary datasheets, service manuals, or confidential documentation** are included  
- All information was obtained **exclusively by analysis of a legally obtained physical device**

Brand names such as *Bosch* are mentioned **only to identify the compatible hardware** and remain the property of their respective owners.

This project does **not** aim to clone, counterfeit, or commercially reproduce the original product.

---

## Repository Structure and Licensing

Different parts of this repository use **different licenses**, chosen to match their content and typical reuse patterns.

## Repository Structure and Licensing
```text
RevEng_Bosch_BCS220/
├── schematics/        # Reconstructed circuit schematics (KiCad project)
│                      # License: CERN-OHL-W v2.0
├── pcb/               # pcbtracer project (PCB layout, netlists, board analysis)
│                      # License: CERN-OHL-W v2.0
├── docs/              # Reverse engineering notes, analysis reports
│                      # License: CC-BY-SA 4.0
├── photos/            # High-resolution PCB photos and annotations
│                      # License: CC-BY-SA 4.0
└── README.md
```

## Folder Details
- The schematics folder contains a subfolder with the KiCad project files. The main folder will contain pdf exports as soon as the errors in the schematics seem to be solved. Currently there are obvious errors and/or missing connections.
- The (local cloned) pcb folder can be directly opened as project folder with https://pcbtracer.com
- The photos folder is currently empty, I have a bunch of photos and I would like to sort them previously
---

## License Details

### Hardware Design Files (Schematics & PCB)

**License:**  
**CERN Open Hardware Licence v2 – Weakly Reciprocal (CERN‑OHL‑W)**

Applies to:
- Reconstructed schematics  
- PCB layouts  
- Netlists  
- EDA design files  

This license:
- Allows study, modification, manufacturing, and redistribution  
- Requires that **modified design files** remain under the same license  
- Does **not** force disclosure for private or internal use  
- Is specifically written for open hardware designs  

License text:  
https://ohwr.org/cernohl

---

### Documentation and Images

**License:**  
**Creative Commons Attribution‑ShareAlike 4.0 International (CC BY‑SA 4.0)**

Applies to:
- Written reverse‑engineering documentation  
- Analysis notes  
- Annotated PCB photographs  
- Diagrams and explanatory material  

This license:
- Allows sharing and adaptation  
- Requires attribution  
- Requires derived works to use the same license  

License text:  
https://creativecommons.org/licenses/by-sa/4.0/

---

## Disclaimer

This project is provided **“as is”**, without any warranty of correctness, safety, or completeness.

Working on mains‑powered electronics and battery chargers involves **dangerous voltages**.  
If you attempt repairs or modifications, you do so **entirely at your own risk**.

---

## Status

This is an **ongoing reverse engineering effort**.  
Schematics may be incomplete, partially inferred, or subject to correction as new findings emerge.

Contributions, corrections, and technical discussions are welcome.
