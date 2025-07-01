# EM_BI_2025
EM_BI_2025 Jupyter Notebooks with the code described in the paper "Towards Improved Eye Movement Biometrics: Investigating New Features with Neural Networks". The files may be opened in e.g. in Google Colab.

# Data Preparation Instructions

Before using the GazeBase dataset for experiments defined in notebooks:
 - EM_BI_CrossValidation.ipynb
 - EM_BI_Functions.ipynb

please follow these steps to ensure the data is properly organized:

## Step 1: Extract the Data
Unzip or extract the dataset archive into a dedicated directory on your system. For example:

    /path/to/your/data/

## Step 2: Organize Data
Ensure that each round is placed in its own subfolder within the main data directory. 

The structure should look like this:

    /path/to/your/data/Random_Saccades_<number_of_rounds>
    ├── Round_1/
    ├── Round_2/
    ├── ...
	└── Round_<number_of_rounds>/
