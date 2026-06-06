# Model Metadata: CleaningRobotSystem


| Label | Description |
| :--- | :--- |
| **title** | CleaningRobotSystem |
| **source_paper** | A goal model elaboration for localizing changes in software evolution |
| **DOI** | 10.1109/RE.2013.6636715 |
| **authors** |H. Nakagawa, A. Ohsuga, S. Honiden|
| **year** |2013|
| **domain** | Autonomous Systems |
| **model_origin** | reconstructed-from-image  |
| **Reconstructor** | E. Soulas Moreno |
| **original_notation_and_extension** | KAOS 1.0 with control loop annotations |
| **reconstruction_notes** | • **Actor Setup**: Identified the *Cleaning Robot* as the primary actor.<br>• **Element Tweaks**: Added intermediate tasks to bridge the gap between goals and resources, keeping everything aligned with syntax constraints.<br>• **Link Mapping**: Converted *"concerns" links* into standard *Needed-By links*.<br>• **Omissions**: Left out extra manual annotations and comments. |
| **interpretation_guidance** | • **Mapping Reference**: Used the transformation mapping rules provided in the supplementary material to convert KAOS elements into iStar 2.0 syntax. |
| **supplementary_material** | *Model-Driven Development for Requirements Engineering: The Case of Goal-Oriented Approaches* (DOI: 10.1109/QUATIC.2012.38) |
---

## Folder Contents
* **`model.txt`**: The new model file, compatible with the PiStar tool
* **`model.png`**: A high-resolution export of the model for quick viewing
