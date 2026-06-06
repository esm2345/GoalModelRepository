# Model Metadata: ContactTracingApp_COVID19

| Label | Description |
| :--- | :--- |
| **title** | ContactTracingApp_COVID19 |
| **source_paper** | A Divide & Concur Approach to Collaborative Goal Modeling with Merge in Early-RE |
| **DOI** | 10.1109/RE54965.2022.00009|
| **authors** | K. Habutzel, A. Jain, A. Grubb|
| **year** |2022 |
| **domain** | Healthcare |
| **model_origin** |  reconstructed-from-image  |
| **Reconstructor** | Elena Sophie Soulas Moreno |
| **original_notation_and_extension** |Tropos 1.0 with evaluation annotations using evidence pairs |
| **reconstruction_notes** | • **Goal Type Adjustment**: Refactored the goal *"minimize exposure"* into a *Softgoal* to correctly allow for contribution links.<br>• **Link Refactoring**: Converted the original *"++" contribution* between internal tasks of different actors into a standard *Resource Dependency* to maintain cross-actor boundaries.<br>• **Omissions**: Omitted an inter-actor *Hurt* contribution, as iStar 2.0 lacks a native equivalent and no semantically clean dependency could be established between the softgoal *avoid exposing others* in the *Emma* actor and the *Share exposure* Task in *Tracking App*. |
| **interpretation_guidance** | / |
| **supplementary_material** | / |

---

## Folder Contents
* **`model.txt`**: The new model file, compatible with the PiStar tool
* **`model.png`**: A high-resolution export of the model for quick viewing
