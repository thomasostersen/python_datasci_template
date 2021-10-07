# A template R project

This repo contains a base folder structure for an R project

## Folder structure

Top-level layout is as follows:


    ├── assets             				<- Folder containing company logos, images, configurations, etc.
    ├── README.md          				<- The top-level README containing some information.
    ├── docs               				<- Documents/info about the project
    ├── R         			        	<- Custom R functions used in the project
    │
    ├── data
    │   ├── external       				<- Data from third party sources, could be additional or prediction datasets.
    │   ├── interim        				<- Intermediate data that has been transformed.
    │   ├── processed      				<- The final, canonical data sets for modeling.
    │   └── raw            				<- The original, immutable data dump.
    │
    │── scripts               		 	<- Scripts to create models, process data
    │   ├── 01-data_preparation
    │   ├── 02-EDA   	
    │   ├── 03-modelling    	
    │   ├── 04-evaluation           
    │
    │── rmds               		 		<- Markdown files
    │   ├── 01-eda.rmd          	     
    │   ├── 02-modelling.rmd  	
    │
    │── reports               		 	<- Outputs of the rmd files
    │   ├── 01-eda.html          	     
    │   ├── 02-modelling.html    	
    │
    │── apps               		 		<- Shiny apps
    │   ├── 01-supervised_prediction.rmd          	     
    │   ├── 02-unsupervised_prediction.rmd 
    │
    ├── models             				<- Trained models, model predictions, or model summaries
    │   
    ├── run_all.r         			    <- Scripts to run all the scripts	
