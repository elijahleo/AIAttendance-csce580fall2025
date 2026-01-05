# CSCE 580 AI Attendance Analysis Project (fall 2025)
## Overview
This repository contains data, code, and analysis from the AI Attendance project done for CSCE 580. It includes anonymized data stored in .xlsx files, code to analyze the data, and written analysis.
## Repository Structure
* code/
  * AI_final_code.ipynb - code to run analysis
* data/
  * AI_final_data.csv - compiled data from other files in folder used in analysis
  * ClassX_[date].csv - anonymized version of data extracted from photos of attendance sheets by ChatGPT
* Question 2 answers.pdf - written analysis of data and results from code
* README.md - this file
## Requirements
- Python 3.9+
- pip
- Jupyter Notebook

> If Jupyter is not installed, see the official installation guide:  
> https://jupyter.org/install
## Usage
1. (Optional) Create and activate a virtual environment:
   Windows:
```
python -m venv venv
venv\Scripts\activate
```
2. Install dependencies (if needed):
```
pip install pandas
```
3. Open the file in Jupyter Notebook:
```
jupyter notebook AI_final_code.ipynb
```
4. Run desired notebook cells. Make sure the notebook kernel is set to the same Python environment where the dependencies were installed.
## Notes
Make sure data/AI_final_data.csv is in the same folder as AI_final_code.ipynb before running.
