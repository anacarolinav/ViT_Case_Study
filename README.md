# ViT_Case_Study

This repository contains a Jupyter Notebook for a case study focused on the loading, preprocessing, and analysis of medical imaging data in the .nii.gz format. The notebook demonstrates how to handle neuroimaging data, prepare it for machine learning, and perform basic data processing tasks. This work is part of my Master's dissertation in Biomedical Engineering at the University of Minho.

### Contents
 CaseStudy1.ipynb: The main Jupyter Notebook file containing the code and explanations for the case study.
 
 original_data/: Directory where the original .nii.gz files are stored.

### Usage

1. Loading Data:
The notebook includes functions to load .nii.gz files from specified directories and preprocess them.
Data is split into real and fake categories and then concatenated for further processing.

2. Preprocessing:
The notebook processes the data by normalizing it and extracting central slices from the image volumes.
The slices are resized to 224x224 pixels and expanded to 3 channels to match the input format expected by most neural networks.

3. Running the Notebook:
Open the CaseStudy1.ipynb file in Jupyter Notebook or Jupyter Lab.
Run the cells sequentially to execute the code and follow the analysis steps.

### Data Directory Structure
Ensure that your data directory is structured as follows:

original_data/

    ├── real/
    
    └── fake/
    
real/: Directory containing real .nii.gz files.

fake/: Directory containing fake .nii.gz files.
