# MLND-Capstone
Udacity Machine Learning Nano Degree Capstone Project

This project is separated into 3 directories

* doc - proposal, report, and all associated images
* code - all code, including data_prep and model
* data - both raw and processed data

## 1: code/data_prep

Begin in the code/data_prep directory.  If you checked out all of the raw data, then you will not need to download any files, however there are Jupyter Notebook cells that will download the raw data if needed.

### 1.1: CVE

The CVEs are the first data files to be processed, fire up the __cve__ notebook, execute the **imports** cell, you may skip the download cell if you have all of the required __nvdcve-1.0-20xx.json__ files in data/raw.  Otherwise, execute the cell to download them all.  Run the rest of the cells to produce a **data/processed/cves.json** file

### 1.2: Metasploit

Next the Metasploit database needs to be processed and appended to the CVEs file.  Load up the __metasploit__ notebook, execute the **imports** cell and **files** cell like before.  Skip the download if you already have raw/metasploit.json, otherwise download it.  Execute the rest of the cells here to produce **data/processed/cves_metasploit.json**

### 1.3: Encoded

The last data processing step is to one-hot encode the data.  Load the __encode__ notebook and execute all of the cells here to create **data/processed/cves_metasploit_encoded.json**

## 2: code/model

Next, run the models in the code/model directory.

### 2.1: Linear Regression

Fire up the __regression__ notebook and execute all cells.  This will produce some graphics that are saved off to docs/img, as well as produce some results.

### 2.2: Decision Tree

Lastly, load the __decisiontree__ notebook and execute all cells.  

## 3: Done

This completes the 'walk-through' portion of the data notebook analysis