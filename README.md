# Supply Chain Management Center Induction for Repair Tracker Using a Data Visualization Tool

## Description
This tool monitors scheduled induction equipment against what is currently on hand

## Introduction
The Supply Chain Management Center Induction for Repair Tracker Power BI visualization tool was created to provide analysis to ensure that there will always be equipment on hand when it is scheduled to be inducted for repair. If there is no equipment available for an upcoming induction schedule, this tool will highlight this area. Every part of this process has sample code which shows how to do the following:

* How to extract the Condition Code F data from the Global Combat Support System
* How to extract the current Induction data from the Master Scheduling Support Tool
* How to replace the old extracted files with the new files
* How to change the Power BI report scheduled refresh setting

## Project Goals
The following are goals for this project:

* To maintain equipment readiness at each Maintenance Center when equipment is scheduled for repair
  
* To increase workforce efficiency by having a streamlined process.

* To save money on transportation costs by having a process that accounts for proximity of availabile equipment.

### Virtual Environment Set Up

* Run the command python3 -m venv venv

### Activate the virtual environment
* On Windows: .\venv\Scripts\activate
* On macOS and Linux source venv/bin/activate

### Project Libraries to Import
* Pandas
* Numpy
* Matplotlib
* Seaborn

### How to Run the Executeable file
* Download the files in the raw_data folder
* Download the EDA.ipynb file
* Create a folder on local computer and Paste the dowloaded files in the created folder
* Open the EDA.ipynb file and refer to this folder path when reading the csv files
