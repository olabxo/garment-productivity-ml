# garment-productivity-ml

Machine Learning portfolio project predicting garment production team productivity using workplace and production data.

Project Overview:

For this project, I am looking at whether workplace and production information can be used to predict how prodctuive a garment production team can actually be. This is a regression porblem becuase the values I am trying to predict are numerical.

At this stage of the project I have focused mainly on understading the dataset, preparing it for anaylsis and creating a simple baseline model.


Dataset:

The dataset I am using is the Productivity of Garment Employees from the UCI Mahcine Learning Repository. The dataset is kept locally inside data folder and ingored by Git. More information is included in the data/README.md.

Productivity Prediction of Garment Employees [Dataset]. (2020). UCI Machine Learning Repository, CC BY 4.0 licence.
https://doi.org/10.24432/C51S6D

Project Structure:

garment_productivity-ml/
|
-   data/
        -README.md
-   notebooks/
        -01_garment_data_audit.ipynb
        -02_garment_preprocessing_baseline.ipynb
-   reports/
-   src/
-   .gitignore
-   README.md
-   requirements.txt

The 01 notebook contains the data audit. The 02 notebook contains the data cleaning, preprocessing setup, train/test split and baseline model.


Setup to run:

The project uses Python 3.13.0

1.Create a virtual environment:
    python -m venv .venv

2.Activate it in Windows Powershell:
    .\.venv\Scripts\Activate.ps1

3.Install the packages listed in requirements.txt:
    python -m pip install -r requirments.txt


Running the project:

Place the dataset file garments_worker_productivity.csv into the data folder.
Thne run the notebooks in this order:
1.notebooks/01_garment_data_audit.ipynb
2.notebooks/02_garment_preprocessing_baseline.ipynb

Run each notebook from top to bottom. The results are discussed under code blocks and everyhting is clearly labelled.
