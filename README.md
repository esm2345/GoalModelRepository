# Goal Model Repository


This repository aims to collect, categorize, and publicly share a curated open-source catalogue of Goal Models for Goal-Oriented Requirements Engineering (GORE). Each model in the dataset is stored in JSON format using the iStar 2.0 notation [1] in the [PiStar tool](https://github.com/jhcp/piStar) [2], and has been either reconstructed from its original publication, provided directly by the authors, or translated from another GORE modeling notation.






## Table of Contents
* [Repository Structure](#repository-structure)
* [How to Navigate](#how-to-navigate)
* [How to Contribute](#how-to-contribute)
* [Source Papers](#source-papers)
* [Scope Statement](#scope-statement)
* [Authorship and Credit Policy](#authorship-and-credit-policy)
* [Conditions of Use and License](#conditions-of-use-and-license)
* [Repository Administration Policies](#repository-administration-policies)
* [How to Cite](#how-to-cite)
* [References](#references)



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
4. Download and open `model.txt` in PiStar [2] to view the reconstructed model
5. Refer to `original_image.png` and `original_description.txt` for the original source context
6. Look up the metadata labels `reconstruction_notes`, `interpretation_guidance` and `supplementary_material` (in `README.md` in the model file) for additional context and to understand how the model was created



## How to Contribute
To maintain a high-quality and consistent repository, please follow the contribution policy below:

### Contributor Policy
* **Who Can Submit:** Anyone, who has a model that complies with the requirements specified in the Scope Statement below
* **Metadata and File Requirements:** Contributors must provide the piStar JSON export (`model.txt`), an exported piStar image (`model.png`) and the files named accordingly. Additionally, depositors must complete the `README.md` metadata template. All metadata fields are strictly required, with the exception of the final three optional fields.
* **Review and Curation Process:** All new entries must be submitted via a GitHub Pull Request (PR). The repository maintainers will conduct a review process to verify source authenticity, check metadata completeness, and validate the accuracy of the reconstruction before merging the files into the public dataset.
* **Legal Compliance:** By depositing files into this repository, contributors affirm that their submissions comply with all applicable copyright laws (e.g., ensuring open-access or fair-use rights to share the original source image) and are not intentionally malicious.

### Contribution Steps

1. Create a fork of this repository and create a new branch for your model submission.
2. Inside the `/models` directory, create a new folder with a descriptive title summarizing the scenario of your model (e.g., `DomainName_SpecificApplication`).
3. Inside your new folder, you must include the machine-readable JSON source file (named `model.txt`) and image of the model (`model.png`) exported from the PiStar tool.
4. Copy the standard `README.md` metadata template into your folder. Fill out every field completely. The final three fields are optional, but the reconstruction notes must be highly detailed to explain any assumptions or interpretations made during the modeling process. Supplementary material used for language mappings must also be explicitly stated in its respective metadata field.
5. Open a Pull Request against the main repository. In the description, detail exactly what you are submitting or what specific corrections you made.







## Source Papers
All models in this repository are reconstructed from published research in
Goal-Oriented Requirements Engineering (GORE) and were found using specified search queries in the Scopus database. Each model's source paper, authors, and publication details are referenced in the `metadata_catalogue.xlsx`.


## Scope Statement

To ensure the consistency, interoperability, and scientific validity of the dataset, this repository implements the following policy for inclusion:

* **What is Accepted:** 
  * **Technical Format:** This repository exclusively accepts goal models provided as machine-readable JSON files conforming to the iStar 2.0 notation, specifically designed to be loaded and edited within the piStar modeling tool. 
  * **Source Authenticity:** To maintain strict quality control, models must originate from verifiable sources. This includes models published in peer-reviewed academic literature, formal technical reports, or documented industry case studies. Unverified, purely hypothetical, or incomplete personal models will not be accepted.
  * **Metadata & Documentation:** All submissions must be accompanied by a completed metadata template. All fields within the template are mandatory, with the exception of the final three optional fields. Furthermore, if a model was reconstructed or translated from a static image, the exact process, interpretations, and any assumptions made must be explicitly documented in the reconstruction notes.

* **What is Not Accepted:** 
  * This repository does not accept raw natural language requirements, software code, or unstructured text. Furthermore, static, non-editable model images (such as PDFs, PNGs, or JPEGs) are strictly rejected as standalone entries; images are only accepted as supplementary material to accompany a fully reconstructed, machine-readable JSON file.






## Authorship and Credit Policy
To avoid ambiguity, this repository distinguishes between the creators of the model itself and the creators of the repository artifact (reconstruction):

* **Original Authors:** Full academic credit for the conceptual frameworks, goals, and original system designs remains strictly with the authors of the source publications. Their work is explicitly cited in the `metadata_catalogue.xlsx` and within the individual metadata of each model.
* **Reconstructors:** The individual who translates the original visual model into the machine-readable iStar 2.0 format (the JSON file) is credited as the "Reconstructor" within the model's `README.md` metadata file. Reconstructors are credited for the technical data entry and translation, but do not claim ownership of the underlying intellectual property.
* **Conflict Resolution:** If the original authors of a published model wish to update, modify, or completely remove the reconstructed version of their work from this repository, their requests will be given absolute priority. 



## Conditions of Use and License

**Licensing:**
The reconstructed machine-readable goal models (JSON files) and accompanying metadata in this repository are distributed openly under the [MIT License](LICENSE). You are free to share, reuse, and adapt these files, provided you give appropriate credit. 




## Repository Administration Policies

**Privacy Policy:**
This repository is hosted entirely on GitHub and does not independently collect, process, or store personal user data, nor does it use proprietary tracking cookies. Any data collection regarding repository traffic or user accounts is governed strictly by [GitHub’s standard Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement). 

**Retention Policy:**
All reconstructed goal models and metadata accepted into this repository are intended to be retained indefinitely. Entries will only be removed or substantially modified under the following specific conditions:
1. A direct request for removal by the original authors of the source publication.
2. A verified copyright violation regarding the supplementary material.
3. The discovery of critical, unfixable errors in the model reconstruction.

**End-of-Life Policy:**
If active maintenance of this repository ends, the dataset will not be deleted. It will remain publicly accessible here on GitHub as a static, read-only archive.



## How to Cite

> E. Soulas Moreno. *Building an Open Dataset of GoalOriented
Requirements Engineering Models*. DTU, 2026. Available at: https://github.com/esm2345/GoalModelRepository/blob/main/README.md


## References
[1] F. Dalpiaz, X. Franch, and J. Horkoff, “Istar 2.0 language guide,” arXiv preprint
arXiv:1605.07767, 2016. DOI: 10.48550/arXiv.1605.07767. [Online]. Available: https:
//arxiv.org/abs/1605.07767.

[2] Pimentel, João and Castro, Jaelson. piStar Tool – A Pluggable Online Tool for Goal Modeling. 2018 IEEE 26th International Requirements Engineering Conference, pp. 498-499. Available at: [text](https://github.com/jhcp/piStar)