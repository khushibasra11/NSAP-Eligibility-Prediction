# NSAP Eligibility Prediction using IBM AutoAI

## Project Overview
This project uses machine learning to predict the appropriate NSAP (National Social Assistance Programme) scheme for applicants based on district-level socio-economic data. The model was built using IBM AutoAI and deployed as a REST API through IBM Cloud's Machine Learning service.

## Repository Contents
- ibm_project.pptx – Project presentation
- ibm_project.pdf – Project report or PDF version of the presentation

## Problem Statement
Manually verifying and assigning welfare schemes to applicants can lead to delays and errors. This project aims to automate the classification process to help government agencies deliver benefits efficiently and accurately.

## Dataset
- Source: AI Kosh – District-wise pension data under the NSAP
- Key features used: statename, districtname, totalmale, totalfemale, totaltransgender, totalsc, totalst, totalgen, totalobc, totalaadhaar, totalmobilenumber
- Target variable: schemecode

## Model Development
IBM AutoAI was used to:
- Preprocess the data
- Generate and compare multiple model pipelines
- Select the best-performing classification model
- Perform hyperparameter tuning

## Deployment
The best model was deployed as an online REST API using the Machine Learning service on IBM Cloud. The API can accept applicant data and return the predicted NSAP scheme.

## Results
The model achieved high accuracy in predicting scheme eligibility. Feature importance charts and evaluation metrics confirmed the reliability of the model.
