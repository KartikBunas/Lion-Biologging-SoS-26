# Identifying Lion Behavioral States from GPS Tracking Data

## Project Objective
This project implements a classical machine learning pipeline to classify wild lion tracking telemetry into two core behavioral states: **Resting** and **Traveling**. The model uses geometric tracking metrics alongside diurnal context (local hour of day) to distinguish active transit patterns from stationary clusters.

## Dataset
* **Source:** Movebank Data Repository
* **Taxa:** *Panthera leo* (African Lion)
* **Source:** https://www.movebank.org/cms/webapp?gwt_fragment=page=studies,path=study3791354435
* **Scope:** ~166k GPS records across 13 unique individuals.

## Repository Layout
* `notebooks/`: Contains our Jupyter notebooks.
* `data/`: Directory for the local tracking CSV file.
* `literature/`: Contains research papers for references according to weeks.

## Weekly Development Plan
-**Week 1:** Acquiring Data and Refining it
-**Week 2-3:** Spatial Feature Engineering
-**Week 4:** Exploratory Analysis 
-**Week 5-6:** Model Training and Optimization
-**Week 7:** Interactive Geospatial Visualization
-**Week 8:** Pipeline Polish and Finalization

## Added Resources
Google drive link for anyone who wishes to access the data files
**Link:** https://drive.google.com/drive/u/0/folders/1EIgnpUT9E4iRz2YVHNhNBqGSWz1w2TyS
