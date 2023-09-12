# Skeletonizing-and-Analyzing-Pipeline-for-3D-Interstellar-Cloud-Ensembles

In order to utilize the Skeletonizing and Analysis Pipeline for Interstellar Clouds 

First, go to Installation-Instructions folder and download all packages in a new conda environment

Then there are a few different tutorial folders. 
Each tutorial folder has a link in the Data-Source.txt that points to where the data for that tutorial notebook can be downloaded from. 

Single-Grid Tutorials Folders 

- These folders include the pipeline version that analyzes one simulation or observations .fits file. 
- There are tutorial examples for both an observational .fits file, and one simulation .fits files 
- Notebooks include how to run the pipeline, and how to analyze pipeline outputs. 

Note : The pipeline has been tested on other simulation data. If you have any questions, feel free to email eem85@cornell.edu. 

Note : The pipeline assumes that simlation grids are in positiion-position-position (ppp) space, not position-position-velocity (ppv). The pipeline will skeltonize and analyze ppv grids, but the results will 
need to be interpreted more carefully. 

Multiple-Grid Tutorial Folders 

- These folders include the pipeline version that was specifically made for the Cloud Factory simulation grids. 
- There exists tutorials on how to turn the AREPO grids into fits files, run the pipeline on the ensemble of fits files, and how to analyze pipeline outputs. 

Data Table Tutorial 

- This folder includes all the data table outputs for the entire Cloud Factory simulation grid ensemble found in Mullens 2023, and how to make nice corner plots from the pipeline outputs.

Links to relevant papers : 
