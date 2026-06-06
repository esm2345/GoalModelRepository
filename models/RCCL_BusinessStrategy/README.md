# Model Metadata:RCCL_BusinessStrategy
| Label | Description |
| :--- | :--- |
| **title** | RCCL_BusinessStrategy (Royal Caribbean Cruise Line)|
| **source_paper** | Can goal reasoning techniques be used for strategic decision-making?|
| **DOI** | 10.1007/978-3-319-46397-1_41 |
| **authors** | E. Paja, A. Mate, C. Woo, J. Mylopoulos |
| **year** | 2016 |
| **domain** | Travel & Hospitality |
| **model_origin** |  reconstructed-from-image  |
| **Reconstructor** | E. Soulas Moreno |
| **original_notation_and_extension** | iStar 1.0 with satisfaction annotations|
| **reconstruction_notes** | • **Link Adjustments**: Refactored original *break-links* into standard contribution links targeting an intermediate softgoal.<br>• **Syntax Alignment**: Converted *Softgoals* into a mix of *Goals* and *Softgoals* to comply with piStar syntax rules and allow means-ends links.<br>• **Dependencies**: Moved dependencies where a dependee/dependum was not a leaf node onto the most relevant leaf node (or creating new leaf node), and modeling them explicitly with a dependum node <br>• **satisfaction annotations**: were ommitted as they cannot be modeled in PiStar|
| **interpretation_guidance** | / |
| **supplementary_material** | /|

---

## Folder Contents
* **`model.txt`**: The new model file, compatible with the PiStar tool
* **`model.png`**: A high-resolution export of the model for quick viewing
