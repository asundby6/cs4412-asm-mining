```
# cs4412-asm-mining  
ASM - Data Mining Group Project - CS 4412  

# Project Overview  
This project utilizes unsupervised data mining to identify Attack Surface Drift and Shadow IT within a network. The focus lies on discovering natural patterns and identifying anomalies that deviate from the baselines that we establish.  

# Dataset  
The data set derives from the Unified Host and Network Data Set, which is provided by the Los Alamos National Laboratory (2017).  
-[URL Source:](https://csr.lanl.gov/data/2017/)  

# Pipeline Approach  
-PCA: Dimensionality reduction technique to simplify complex, high-dimensional datasets  
-DBSCAN: Behavioral clustering used to identify the normal groups of network activity  
-Isolation Forest: Used to give anomaly scores to different events so that we can rank potential drift cases that we discover.  

# Repository Structure  
-> /data      -> Folder for sampled datasets and processed CSVs     
-> /notebooks -> Folder for Jupyter notebooks for PCA and clustering tests  
-> /proposal  -> Folder for the project outline/documentation  
```
