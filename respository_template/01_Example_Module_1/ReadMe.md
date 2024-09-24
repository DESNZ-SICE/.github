# Example Module 1

This document provides some guidance on the information required when uploading a new resource or model to the Github. 

## Introduction
- What is this project or module about? 
- What background does the user need to know?

## Objective
What does this Module do?

## Data/Inputs
What input data is needed for this module - remember do not store data on GitHub!
* Include links and source
* Explain the quality of data


You may want to use a table to present this information. These are not compulsory
| Data              | Quality and year last updated | Source |
| :---------------- | :------: | ----: |
| Data source 1 (e.g. National Buildings Database)       |   Good , 2024  | Report |
| Data source 2 (e.g. data collected as part of the project          |   Good  , 2024 | Can be found in ERT OneDrive  |
|  Data from reference documents |  Average, 2020 and 2015   | Link|
| Data source 4 |  2024 good data quality   | Link |

## Assumptions
Provide a list or table of key assumptions underpinning the model or analysis.

| Assumption        | Value/Relationship     | Source|
| :-----------------| :--------------------: | -----:|
| e.g. Cooking fuel in homes is electric | No gas meter connection in homes without gas boiler | CODE Methodology Report |

## How it works
Please provide a brief explanaiton of how the model/module works. This could include a diagram. 

![diagram](model_example_figure_for_github.png)

## How to run the code
You may want to include a snippet of code that users may need to use to load/run the analysis, or then describe the sequence of steps needed. For example for a model written in R you may provide a list of libraries and scripts to load:

> 'library(tidyverse)'
> 'library(reshape2)'
> 'source('core_model_functions.R')'

## Outputs

