# Model Metadata: PatientHealthCheckRoutine

| Label | Description |
| :--- | :--- |
| **title** | PatientHealthCheckRoutine |
| **source_paper** | Adaptive socio-technical systems: A requirements-based approach|
| **DOI** | 10.1007/s00766-011-0132-1|
| **authors** |F. Dalpiaz, P. Giorgini, J. Mylopoulos |
| **year** | 2013 |
| **domain** |Healthcare |
| **model_origin** | reconstructed-from-image  |
| **Reconstructor** | E. Soulas Moreno |
| **original_notation_and_extension** | iStar 1.0 with context and task annotations|
| **reconstruction_notes** | the context annotations on the links were ommitted due to the constraints of the modeling tool |
| **interpretation_guidance** | **Activation Rules:**<br>• **g1**: alarm plays sound<br>• **g18**: alarm plays sound, if contexts **c1** and **c4** hold<br><br>**Goal Timeouts:**<br>• **g1**: 60 minutes<br>• **g18**: 40 minutes |
| **supplementary_material** | / |

---

## Folder Contents
* **`model.txt`**: The new model file, compatible with the PiStar tool
* **`model.png`**: A high-resolution export of the model for quick viewing
