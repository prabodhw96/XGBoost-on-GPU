# XGBoost on GPU
## Overview
Execution of XGBoost on both CPU and GPU and comparing their training time.
## Data Description
<b>Dataset: </b>UCI Forest Cover Type Dataset <br>
<b>Link: </b>https://www.kaggle.com/uciml/forest-cover-type-dataset <br>
Cartographic variables of 581,012 measurements.
## Memory Usage
Memory usage of the dataframe is: **243.8 MB**<br>
_After Optimization_:<br>
Memory usage is: **33.8 MB**<br>
This is  **13.86%** of the initial size.
## Machine
Ran the code in cloud on [vast.ai](https://vast.ai) with following VM instance specifications:<br>
* **GPU**: GTX 1080 (8 GB)
* **RAM**: 128 GB
* **Processor**: Xeon® E5-2630 v2
## Result
No. of iterations: 100 (set to minimum) <br>
CPU Time: **1030.36 seconds** <br>
GPU Time: **19.36 seconds** <br>
#### Training Time reduced to 1.88%.<br>