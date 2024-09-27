# Home Sales Big Data Query Analysis
## Overview
This big data analysis is designed to test the processing differences of parqueting, partitioning, and cacheing. The data features fictional home sales information based on construction specs, property type, and age.

## Tech Stack
- pyspark.sql
- pyspark
- Google Collab

## Results 
Surprisingly the run times were not consistent for each review of the code. Results of the last three runs are documented below. 

- First Round
  
  Initial time: 0.827 seconds,
  Cached time: 0.769 seconds,
  Parqueted time: 1.15 seconds

- Second Round
  
  Initial time: 1.81 seconds,
  Cached time: 1.08 seconds,
  Parqueted time: 0.84 seconds

- Third Round
  
  Initial time: 1.15 seconds,
  Cached time: 0.97 seconds,
  Parqueted time: 0.55 seconds

This code was developed in google collab without TensorFlow downloaded locally. For maximum efficiency device setup would need to be re-considered.

## Application
It appears caching and parqueting the data does yield measurable benefit for processing speed. The Jupyter Notebook is now availabe for any further queries.

## Usage
See License for copyright details.

