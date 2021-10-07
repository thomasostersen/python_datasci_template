# A Template Data Science Project

This repository contains a base directory structure for data science projects.

## Directory Structure

Top-level layout is as follows:


    ├── README.md               <- The top-level README containing some information about the project
    ├── docs                    <- Detailed documents/info about the project
    │
    ├── data
    │   ├── external            <- Data from third party sources, could be additional or prediction datasets
    │   ├── interim             <- Intermediate data that has been transformed and/or pre-processed
    │   ├── processed           <- The final, canonical data sets for modelling
    │   └── raw                 <- The original, immutable data dump
    │
    │── code    
    │   ├── eda   	            <- Jupyter notebooks and/or scripts used for exploratory data analysis
    │   ├── data_processing     <- Jupyter notebooks and/or scripts used to process data to a modelling-ready state
    │   └── modelling    	    <- Jupyter notebooks and/or scripts used to create and evaluate models         
    │
    │── reporting               <- Reporting documents, images and presentations relating to the project
    │
    ├── deliverables         			    
    │   ├── predictions         <- Prediction outputs from modelling notebooks and/or scripts
    │   └── models              <- Model objects with associated scripts for model deployment


