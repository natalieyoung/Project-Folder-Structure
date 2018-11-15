# Data and Feature Definitions
This document provides a central hub for the raw data sources, the processed/transformed data, and feature sets. More details of each dataset is provided in the data health report. 

For each dataset, a data dictionary is created describing the data schema, the meaning of each data field, and other information that is helpful for understanding the data. If the dataset is the output of processing/transforming/feature engineering existing data set(s), the names of the input data sets, and the links to scripts that are used to conduct the operation are also provided. 

## Raw Data Sources

### Summary
* Dataset1: < Provide brief summary of the data, such as how to access the data. More detailed information should be in the Dataset2 Dictionary > 
* Dataset2: < Provide brief summary of the data, such as how to access the data. More detailed information should be in the Dataset2 Dictionary > 

| Dataset Name | Original Location   | Destination Location  | Data Movement Tools/Scripts | Link to Dictionary |
| ---:| ---: | ---: | ---: | -----: |
| Dataset 1 | Brief description of its orignal location | Brief description of its destination location | [script1.py](link/to/python/script/file/in/Code) | [Dataset 1 Report](link/to/report1)|
| Dataset 2 | Brief description of its orignal location | Brief description of its destination location | [script2.R](link/to/R/script/file/in/Code) | [Dataset 2 Report](link/to/report2)|


## Processed Data

### Summary
* Processed Data1: <Provide brief summary of the processed data, such as why you want to process data in this way. More detailed information about the processed data should be in the Processed Data1 Dictionary>
* Processed Data2: <Provide brief summary of the processed data, such as why you want to process data in this way. More detailed information about the processed data should be in the Processed Data2 Dictionary> 

| Processed Dataset Name | Input Dataset(s)   | Data Processing Tools/Scripts | Link to Dictionary |
| ---:| ---: | ---: | ---: | 
| Processed Dataset 1 | [Dataset1](link/to/dataset1/report), [Dataset2](link/to/dataset2/report) | [Python_Script1.py](link/to/python/script/file/in/Code) | [Processed Dataset 1 Report](link/to/report1)|
| Processed Dataset 2 | [Dataset2](link/to/dataset2/report) |[script2.R](link/to/R/script/file/in/Code) | [Processed Dataset 2 Report](link/to/report2)|



## Feature Sets

### Summary
* Feature Set1: <Provide detailed description of the feature set, such as the meaning of each feature. More detailed information about the feature set should be in the Feature Set1 Dictionary>
* Feature Set2: <Provide detailed description of the feature set, such as the meaning of each feature. More detailed information about the feature set should be in the Feature Set1 Dictionary>

| Feature Set Name | Input Dataset(s)   | Feature Engineering Tools/Scripts | Link to Dictionary |
| ---:| ---: | ---: | ---: | 
| Feature Set 1 | [Dataset1](link/to/dataset1/report), [Processed Dataset2](link/to/dataset2/report) | [R_Script2.R](link/to/R/script/file/in/Code) | [Feature Set1 Report](link/to/report1)|
| Feature Set 2 | [Processed Dataset2](link/to/dataset2/report) |[SQL_Script2.sql](link/to/sql/script/file/in/Code) | [Feature Set2 Report](link/to/report2)|


