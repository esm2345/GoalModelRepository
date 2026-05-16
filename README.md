# GoalModelRepository


This repository aims to collect, categorize, and publicly share a curated open-source catalogue of Goal Models for Goal-Oriented Requirements Engineering (GORE). Each model in the dataset is stored in JSON format using the iStar 2.0 notation [1] in the [PiStar tool](https://github.com/jhcp/piStar) [2], and has been either reconstructed from its original publication, provided directly by the authors, or translated from another GORE modeling notation.


To support the findability, accessibility, and reproducibility of research in GORE, every artifact is accompanied by structured metadata.

## Repository Structure
```text
GoalModelRepository/
├── README.md                           ← repository overview and usage instructions
├── metadata_catalogue.xlsx             ← consolidated metadata catalogue
├── metadata_catalogue.csv
├── docs/
│   └── metadata-schema.md              ← metadata schema definition
└── models/
    ├── BusinessStrategy_Modelling/     ← model file
    │   ├── README.md                   ← metadata for the specific model
    │   ├── model.txt                   ← model stored in JSON format
    │   ├── model.png                   ← reconstructed model in PiStar
    │   ├── original_image.png          ← original model image from source paper
    │   └── original_description.txt    ← optional original description
    │
    ├── DecisionMaking_for_SelfAdaptiveSystem/
    ├── GreenManager_MultiAgentSmartHome/
    ├── RemoteDataMirroring_Application/
    └── ...

```

Each model folder is assigned a descriptive title summarizing the modeled scenario and contains the model's metadata, the JSON-formatted source file, an image of the model created in the PiStar tool [2], and the original model image from its source.


## How to Navigate

1. Look up the model title in `metadata_catalogue.xlsx` by filtering for its domain, author, year or other metadata label
2. Find the corresponding model folder in `/models`
3. Open `model.png` for a quick preview on the modeled scenario
3. Download and open `model.txt` in PiStar [2] to view the reconstructed model
4. Refer to `original_image.png` and `original_description.txt` for the original source context
5. Look up the metadata labels `reconstruction_notes`, `interpretation_guidance` and `supplementary_material` (in `README.md` in the model file) for additional context and to understand how the model was created


## Source Papers
All models in this repository are reconstructed from published research in
Goal-Oriented Requirements Engineering (GORE) and were found using specified search queries in the Scopus database. Each model's source paper, authors, and publication details are referenced in the `metadata_catalogue.xlsx`.

## How to Cite

> E. Soulas Moreno. *Building an Open Dataset of GoalOriented
Requirements Engineering Models*. DTU, 2026. Available at: https://github.com/esm2345/GoalModelRepository/blob/main/README.md


## References
[1] F. Dalpiaz, X. Franch, and J. Horkoff, “Istar 2.0 language guide,” arXiv preprint
arXiv:1605.07767, 2016. DOI: 10.48550/arXiv.1605.07767. [Online]. Available: https:
//arxiv.org/abs/1605.07767.

[2] Pimentel, João and Castro, Jaelson. piStar Tool – A Pluggable Online Tool for Goal Modeling. 2018 IEEE 26th International Requirements Engineering Conference, pp. 498-499. Available at: [text](https://github.com/jhcp/piStar)