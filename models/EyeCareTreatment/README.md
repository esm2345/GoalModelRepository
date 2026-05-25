# Model Metadata: EyeCareTreatment


| Label | Description |
| :--- | :--- |
| **title** | EyeCareTreatment |
| **source_paper** | Aligning goal and value models for information system design |
| **DOI** | 10.1007/978-3-642-01187-0_11 |
| **authors** | A. Edirisuriya, J. Zdravkovic |
| **year** | 2009|
| **domain** | [Application area (e.g. legal, healthcare, security)] |
| **model_origin** | reconstructed-from-image  |
| **original_notation_and_extension** | KAOS 1.0 |
| **reconstruction_notes** | • **Actor Setup**: Identified the *Patient*, *Primary Care Physician*, and *Eye-Care Specialist* as primary actors based on the source text and Table 1.<br>• **Element Adjustments**: Kept the original goal phrasing, but refactored *"Patient satisfaction"* into a standard *Softgoal*.<br>• **Link Mapping**: Modeled *Means-End links* and *OR links* identically to fit the syntax. Added dependency links to handle cross-actor boundaries.<br>• **Dependency Anchoring**: Added a few redundant elements to create valid connection points for those cross-actor dependencies. |
| **interpretation_guidance** | • **Mapping Reference**: Used the transformation mapping rules provided in the supplementary material to convert KAOS elements into iStar 2.0 syntax. |
| **supplementary_material** | *Model-Driven Development for Requirements Engineering: The Case of Goal-Oriented Approaches* (DOI: 10.1109/QUATIC.2012.38) |

---

## Folder Contents
* **`model.txt`**: The new model file, compatible with the PiStar tool
* **`model.png`**: A high-resolution export of the model for quick viewing
