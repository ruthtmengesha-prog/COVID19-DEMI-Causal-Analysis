# COVID-19 DEMI Causal Analysis

## Project Overview

This project evaluates the use of the DEMI causal AI algorithm for estimating COVID-19 PCR positivity using home-observable patient findings. The analysis uses the COVIDCARE dataset and DEMI knowledgebase to examine relationships between recent COVID-19 exposure, fever, cough, fatigue, loss of taste, loss of smell, shortness of breath, and PCR positivity.

The project was completed as a proof-of-concept causal analysis for HI 823.

## Objectives

The main objectives of this project were to:

- Identify home-observable findings that may be relevant to COVID-19 PCR positivity.
- Map the selected findings to concepts in the DEMI knowledgebase.
- Evaluate the temporal ordering of the selected findings.
- Estimate total and direct effects on PCR positivity.
- Evaluate how predicted PCR positivity changes as findings are added to a hypothetical patient scenario.

## Repository Contents

- `COVID_Demi_Final_Project_HI823.ipynb` - Jupyter Notebook containing the complete analysis, code, results, and visualizations.
- `README.md` - Overview and instructions for the project.
- `requirements.txt` - Python packages required to run the analysis.

## Data

The analysis uses the COVIDCARE patient dataset and the COVIDCARE DEMI knowledgebase provided for HI 823.

The data files are not included in this public repository. Users with authorized access should place the required files in their local project directory and update the file paths in the notebook as needed.

## How to Run the Project

1. Download or clone this repository.
2. Install the required Python packages listed in `requirements.txt`.
3. Obtain the required COVIDCARE dataset and DEMI knowledgebase.
4. Update the dataset and knowledgebase file paths in the notebook to match their location on your computer.
5. Open `COVID_Demi_Final_Project_HI823.ipynb` in Jupyter Notebook.
6. Run the notebook cells in order from top to bottom.

## Main Analysis

The notebook includes:

- COVIDCARE dataset inspection and PCR outcome identification
- Selection and mapping of seven home-observable findings
- DEMI temporal ordering
- Total and direct causal-effect estimation
- Causal network visualization
- Hypothetical patient scenario analysis
- Progressive PCR-positivity probability visualization

## Author

Ruth Mengesha, BSN, RN  
Master of Science in Health Informatics  
George Mason University  
HI 823 - Causal Analysis  
Summer 2026
