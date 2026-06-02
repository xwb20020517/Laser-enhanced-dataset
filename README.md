# MS-RPH Dataset (Repository for Peer Review)

This repository hosts a representative baseline subset of the **MS-RPH** dataset, which is developed for fine-grained identification and automated detection of sibling rice planthopper species using advanced optical technologies.

## 📊 Dataset Overview
The data provided here focuses on the phenotypic and morphological characteristics captured under specific active laser enhancement conditions. 

* **Target Species:** Sibling and pest populations of rice planthoppers (including WBPH, SBPH, NL, NB, and NM).
* **Illumination Source:** 450 nm active blue laser enhancement.
* **Preservation Method:** Heat-induced lethal treatment applied immediately upon collection to preserve natural morphological postures and fine-grained structures.

## 📂 Repository Structure
The subset is organized as follows to ensure full reproducibility of the experimental findings:

```text
.
├── Partial laser-enhanced data/
│   └── Blue/
│       ├── Images/          # High-resolution localized biological images under 450nm laser
│       └── labels/      # Annotation files, bounding boxes, and ground-truth metadata
└── README.md
