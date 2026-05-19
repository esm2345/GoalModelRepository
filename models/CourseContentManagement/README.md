# Model Metadata: CourseContentManagement
| Label | Description |
| :--- | :--- |
| **title** | CourseContentManagement |
| **source_paper** | Using Goal Models to Visualize and Prioritize Requirements for Learning Management Systems |
| **DOI** |https://ceur-ws.org/Vol-1954/ |
| **authors** | V. Lantz, J. Horkoff, S. Alibrahim |
| **year** | 2017 |
| **domain** | Academic Management, Learning Management System |
| **model_origin** | reconstructed-from-image  |
| **original_notation_and_extension** | iStar 1.0 |
| **reconstruction_notes** | • **Syntax Compliance**: Refactored *AND links* pointing from a task to a resource into standard *Needed-By links* to adhere to tool constraints.<br>• **Cross-Actor Refactoring**: Converted a *Help contribution* that originally crossed actor boundaries (from CCM to LMS) into a valid actor dependency, which was then broken down into individual internal *Help links*.<br>• **Dependum Creation**: Generated and added missing dependum nodes required by the syntax, labeling them contextually based on the surrounding context and the *dependee*. |
| **interpretation_guidance** |/|
| **supplementary_material** | /|

---

## Folder Contents
* **`model.txt`**: The new reconstructed model file, compatible with the PiStar tool
* **`model.png`**: A high-resolution export of the model for quick viewing
