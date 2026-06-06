# Model Metadata: HealthClub_AccessControlSystem

| Label | Description |
| :--- | :--- |
| **title** | HealthClub_AccessControlSystem |
| **source_paper** |Measuring Complexity and Completeness of KAOS Goal Models|
| **DOI** | 10.1109/EmpiRE.2011.6046252 |
| **authors** |P. Espada, M. Goulao, J. Araujo |
| **year** |2011|
| **domain** | Access Control |
| **model_origin** |  reconstructed-from-image |
| **Reconstructor** | Elena Sophie Soulas Moreno |
| **original_notation_and_extension** | KAOS 1.0|
| **reconstruction_notes** | • **Actor Setup**: Identified the primary actors as the *Access Control System*, *User*, *Staff*, *Card Reader*, *Registration Controller*, and *Access Controller*.<br>• **Link Adjustments**: Remodeled *"concerns" links* as standard *Needed-By links* where possible; otherwise, they were omitted to fit the syntax constraints. Added dependency links to handle cross-actor boundaries. |
| **interpretation_guidance** | • **Mapping Reference**: Used the transformation mapping rules provided in the supplementary material to convert KAOS elements into iStar 2.0 syntax. |
| **supplementary_material** | *Model-Driven Development for Requirements Engineering: The Case of Goal-Oriented Approaches* (DOI: 10.1109/QUATIC.2012.38) |


---

## Folder Contents
* **`model.txt`**: The new model file, compatible with the PiStar tool
* **`model.png`**: A high-resolution export of the model for quick viewing
