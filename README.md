# Association Rule Based Clinical Data Mining and Risk Prediction for Gestational Diabetes Mellitus (GDM)

Project website: 
http://thetruth.ccs.neu.edu/numom2b/index.html

Here are the steps to follow to reproduce the association rules from scratch using the data provided. If you are only interested in the association rules produced in the end you can directly access it under the data_source directory ("GDM_Association_Rules_2021_10_13_filtered.csv.zip") and unzip the file.

Pre-requisites
- Jupyter Notebook
- WEKA 3.8 (See "WEKA_Instructions.txt")

How to run
- Download the competition data set "nuMoM2b_Dataset_NICHD Data Challenge.csv" and put it under the data_source directory

- Run the jupyter notebook "Preprocessing.ipynb" block by block from top to bottom.
  - By the end of running this notebook the following files should be produced under data_source (assuming no file name changes)
    - preg_outcomes.csv
    - baseline_data_2021_10_13.csv
    - baseline_data_2021_10_13_AR_Ready.csv

- Follow the instructions specified in "WEKA_Instructions.txt"
  - A txt file named "weka_AR_2020_10_13.txt" should be produced in the end

- Run the jupyter notebook "WekaTextProcessing.ipynb" block by block from top to bottom.

- A csv file named "GDM_Association_Rules_2021_10_13_filtered.csv" should be present under data_source. These are the associations rules that are available for query on the website

