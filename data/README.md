# Data Setup

This repository uses the Cats vs Dogs dataset and specific ImageNet samples for visual explainability and adversarial robustness testing. The dataset is not included due to size limits.

## Cats vs Dogs Dataset
Used for Grad-CAM, Guided Backpropagation, and Feature Map Visualizations.
*   **Source:** Download from Kaggle (`karakaggle/kaggle-cat-vs-dog-dataset`).
*   Extract the contents and place them in the following directory structure:

```text
data/
└── PetImages/
    ├── Cat/
    └── Dog/
