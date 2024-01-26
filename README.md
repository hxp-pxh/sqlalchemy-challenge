# Honolulu Climate Analysis and Exploration

## Overview

<!-- Overview of the Module -->
This repository contains a climate analysis and exploration for Honolulu, Hawaii. The analysis is intended to aid in trip planning by investigating climate data, focusing primarily on precipitation and temperature trends, to offer a clearer understanding of the climate dynamics over the past year.

## Contents

- `hawaii.sqlite`: The SQLite database containing climate data.
- `climate_starter.ipynb`: Jupyter Notebook with the climate analysis and data exploration. Utilizes Python with SQLAlchemy ORM queries, Pandas, and Matplotlib for data visualization.
- `app.py`: Flask API crafted based on the queries developed in the Jupyter notebook. This API provides access to the climate data via multiple endpoints.
- `README.md`: This document, detailing the project and its components.

## Bootcamp
UTOR-VIRT-DATA-PT-08-2023-U-LOLC-MTTH(B)Assignments
Module 10 Challenge - October 2023

## Student
HxP

## Objectives

### Climate Analysis
<!-- Objective details of climate analysis -->
- Determined the latest date in the dataset.
- Procured and depicted precipitation data for the previous year.
- Computed summary statistics for the precipitation data.
- Undertook a station analysis to identify the most active weather stations and their temperature observations.

### Flask API Development
<!-- Objective details of Flask API development -->
- Constructed various routes to facilitate access to the climate data:
  - Precipitation data.
  - List of weather stations.
  - Temperature observations for the most active station.
  - Temperature statistics for a specified start date or date range.

## Tools Used
- Python
- Flask
- SQLAlchemy
- Pandas
- Matplotlib
- SQLite

## Key Findings
<!-- Key findings or results from the analysis -->
- (You can add a summary of significant findings from your analysis)

## Running the Code
<!-- Instructions on how to run the code -->
1. Clone the repository to your local machine.
2. Launch the `climate_starter.ipynb` in Jupyter Notebook to see the climate analysis.
3. For the Flask API, execute the `app.py` script and navigate to the displayed local host URL to explore the endpoints.

## Acknowledgements
<!-- Acknowledgements and credits -->
- Data furnished by UTOR-VIRT-DATA Bootcamp.
- Continuous guidance and support were provided by instructors, TAs, and student success managers.
