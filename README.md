
# Lumbar Spine Degeneration Classification

This repository contains a deep learning pipeline for classifying lumbar spine degenerative conditions using MRI images. The project employs a fine-tuned ResNet-50 architecture.

## Repository Structure
- `data/`: Folder for dataset (not included in this repository but can be downloaded following the steps in the data prep notebook below).
- `Data_Prep_lumbar_spine_degenerative_classification.ipynb`: Jupyter notebook with the data preparation code.
- `lumbar_spine_classification.ipynb`: Jupyter notebook with the full training and evaluation pipeline.
- `requirements.txt`: List of required Python packages.

## Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/AbdulBarakat/lumbar-spine-classification.git
   cd lumbar-spine-classification
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Place your dataset in the `data/` folder.

4. Run the notebook:
   ```bash
   jupyter notebook lumbar_spine_classification.ipynb
   ```

## Acknowledgments
This project is inspired by the RSNA challenge for lumbar spine classification.

---
