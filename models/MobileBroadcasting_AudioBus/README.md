# Model Metadata: MobileBroadcasting_AudioBus

| Label | Description |
| :--- | :--- |
| **title** | MobileBroadcasting_AudioBus |
| **source_paper** | Generating goal-oriented models from creative requirements using model driven engineering |
| **DOI** |10.1109/MoDRE.2013.6597258|
| **authors** | F. Wanderley, J. Araujo |
| **year** | 2013 |
| **domain** |Mobile Broadcasting |
| **model_origin** | reconstructed-from-image  |
| **Reconstructor** | Elena Sophie Soulas Moreno |
| **original_notation_and_extension** | KAOS 1.0 combined with UML elements|
| **reconstruction_notes** |**Omissions**: UML class diagram part (lower half) was omitted due to modeling limitations of the tool<br>• **Element Adjustments**: Kept the original goal phrasing, but refactored goals like *"Passenger interest* into *Softgoal* elements.<br>• **Link Mapping**: Modeled *Means-End links* and *OR links* identically to fit the syntax. Added dependency links to handle cross-actor boundaries.<br>• **Dependency Anchoring**: Added a few redundant elements to create valid connection points for those cross-actor dependencies. |
| **interpretation_guidance** | • **Mapping Reference**: Used the transformation mapping rules provided in the supplementary material to convert KAOS elements into iStar 2.0 syntax. |
| **supplementary_material** | *Model-Driven Development for Requirements Engineering: The Case of Goal-Oriented Approaches* (DOI: 10.1109/QUATIC.2012.38) |
---

## Folder Contents
* **`model.txt`**: The new model file, compatible with the PiStar tool
* **`model.png`**: A high-resolution export of the model for quick viewing
