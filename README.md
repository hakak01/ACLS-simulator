# ACLS Simulator

A mobile-first ACLS megacode simulator in one file (`index.html`). No build tools: open the file in any browser.

## Cases

1. VF / pulseless VT arrest
2. Asystole / PEA arrest (PEA from blood loss, or asystole from hypoxia)
3. Post-ROSC care
4. Symptomatic bradycardia (complete heart block)
5. Tachycardia with a pulse: unstable or stable SVT, unstable or stable atrial fibrillation, unstable or stable monomorphic VT, polymorphic VT
6. Hyperkalemia arrest
7. Massive pulmonary embolism arrest

## Switches

- Pause and explain, or real-time megacode
- Ideal AHA setup, or low-resource (monophasic defibrillator, no pacer, no capnography, bag-mask only, no amiodarone or adenosine, no lab or ultrasound)
- Dummy patient as a 2D drawing or a 3D model, or a 3D room for Meta Quest (open the page in the Quest browser, tap "Start in the 3D room", then "Enter VR")

You are the team leader. At the end you get a score out of 100 with the guideline reason and source for each point, the ideal treatment for the case as a list, and a demonstration: the simulator plays the ideal treatment on the same patient, step by step.

The 3D parts load the three.js library from the internet; the 2D version works offline.

## Sources

- Wigginton JG, et al. Part 9: Adult Advanced Life Support: 2025 AHA Guidelines for CPR and ECC. Circulation 2025;152(16 suppl 2):S538-S577. doi:10.1161/CIR.0000000000001376
- Cao D, et al. Part 10: Adult and Pediatric Special Circumstances of Resuscitation. Circulation 2025;152(16 suppl 2):S578-S672. doi:10.1161/CIR.0000000000001380
- Hirsch KG, et al. Part 11: Post-Cardiac Arrest Care. Circulation 2025;152(16 suppl 2):S673-S718. doi:10.1161/CIR.0000000000001375
- Disque K. Advanced Cardiac Life Support Provider Handbook (2020-2025 guidelines), version 2021.01. Satori Continuum Publishing; 2021.

The full text of Parts 10 and 11 could not be opened while building this. The hyperkalemia and pulmonary embolism doses come from older AHA guidance (2010 Part 12; 2020 Part 3) and are marked as unchecked in the debrief.

For training only. Not a medical device.
