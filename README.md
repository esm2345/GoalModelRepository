# GoalModelRepository

## About
This repository aims to collect, categorize, and publicly share a curated open-source catalogue of Goal Models for Goal-Oriented Requirements Engineering (GORE). Each model in the dataset is stored in JSON format using the iStar 2.0 notation [1] in the PiStar tool [2], and has been either reconstructed from its original publication, provided directly by the authors, or translated from another GORE modeling notation.

To support the findability, accessibility, and reproducibility of research in GORE, every artifact is accompanied by structured metadata.

## Repository Structure

GoalModelRepository/
|__ README.md                           ← this file
|__ metadata_catalogue.xlsx             ← all model metadata in one place
|__ metadata_catalogue.csv
|__ docs/
|   |__ metadata-schema.md              ← schema definition for model metadata
|__ models/
    |__ BusinessStrategy_Modelling/     ← model file
    |   |__ README.md                   ← metadata schema for the specific model
    |   |__ model.txt                   ← txt file of model in JSON format
    |   |__ model.png                   ← image of reconstructed model
    |   |__ original_image.png          ← image of model in source paper
    |   |__ original_description.txt    ← (optional) original description of model in source paper
    |__ DecisionMaking_for_SelfAdaptiveSystem/
    |__ GreenManger_MultiAgentSmartHome/
    |__ RemoteDataMirroring_Application/
    |__ ...
...

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
Requirements Engineering Models*. DTU, 2026. Available at: [GitHub URL]

## References
[1] F. Dalpiaz, X. Franch, and J. Horkoff, “Istar 2.0 language guide,” arXiv preprint
arXiv:1605.07767, 2016. DOI: 10.48550/arXiv.1605.07767. [Online]. Available: https:
//arxiv.org/abs/1605.07767.

[2] Pimentel, João and Castro, Jaelson. piStar Tool – A Pluggable Online Tool for Goal Modeling. 2018 IEEE 26th International Requirements Engineering Conference, pp. 498-499.