# Model Metadata: MedicalConsultationAndDiagnosis

| Label | Description |
| :--- | :--- |
| **title** | MedicalConsultationAndDiagnosis |
| **source_paper** | Eliciting goals for business process models with non-functinoal requirements catalogues |
| **DOI** | 10.1007/978-3-642-01862-6_4 |
| **authors** | E. Cardoso, J. Almeida, G. Guizzardi, R. Guizzardi |
| **year** | 2009 |
| **domain** | Healthcare |
| **model_origin** |  reconstructed-from-image |
| **original_notation_and_extension** | Tropos 1.0 |
| **reconstruction_notes** | • **Goal-to-Task Refactoring**: Converted the goal *"prescribe patient's treatment"* into a *Task* to satisfy syntax requirements (allowing a connection with a resource).<br>• **Link Adjustments**: Refactored original cross-goal *"+" contribution links* into standard *OR / Means-End links*, and changed other goal-to-goal contributions into *AND* or *OR* structural links (depending on context).<br>• **Softgoal & Dependency Fixes**: Translated a *Means-End link* from a goal to a softgoal into a *Qualification link* to fit the context; introduced an intermediate *Task* to legally support necessary *Needed-By links*. |
| **interpretation_guidance** | / |
| **supplementary_material** | / |

---

## Folder Contents
* **`model.txt`**: The new model file, compatible with the PiStar tool
* **`model.png`**: A high-resolution export of the model for quick viewing
