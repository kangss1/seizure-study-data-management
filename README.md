# Seizure Study Data Management

Course: Data Management with SAS (PBHL-B552)  
Program: Public Health  
Institution: Indiana University Indianapolis  
Semester: Spring 2025  

## Project Overview

This repository documents a comprehensive data management project focused on a public health seizure study. The project emphasizes best practices in data cleaning, transformation, validation, and documentation using SAS. The goal was to prepare raw clinical and observational data for downstream statistical analysis while ensuring reproducibility, transparency, and regulatory readiness.

This work reflects applied data management principles commonly used in public health research environments, including variable standardization, missing data handling, dataset integration, and quality control.

## Public Health Context

Seizure disorders represent a critical area of public health research due to their impact on quality of life, healthcare utilization, and long-term outcomes. Effective data management is essential for ensuring accurate epidemiological insights, supporting evidence-based interventions, and maintaining compliance with research and ethical standards.

This project simulates a real-world public health data workflow, preparing study datasets for analysis while preserving data integrity and auditability.

## Repository Structure

seizure-study-data-management/
|
|-- README.md
|   Project overview, public health context, and usage instructions
|
|-- data/
|   |-- raw_data/
|   |   Original input datasets used in the seizure study
|   |
|   |-- processed_data/
|   |   Cleaned and analysis-ready datasets generated via SAS
|
|-- sas/
|   |-- data_cleaning.sas
|   |-- data_transformation.sas
|   |-- validation_checks.sas
|   SAS programs implementing the data management pipeline
|
|-- docs/
|   |-- abstract.md
|   |-- project_notes.md
|   |-- data_dictionary.md
|   |-- acknowledgments.md
|   Supporting documentation describing methodology and project context
|
|-- report/
|   |-- FinalProject.pdf
|   |-- FinalProject.docx
|   Formal written project submission

## Methods Summary

Key data management steps implemented in this project include:

- Importing and standardizing raw seizure study datasets
- Renaming and labeling variables for clarity and consistency
- Handling missing and inconsistent values
- Creating derived variables for analytical readiness
- Performing validation and quality checks
- Producing clean datasets suitable for statistical modeling

All transformations were performed using SAS, following structured and well-documented workflows.

## Reproducibility

To reproduce the data management process:

1. Clone or download this repository
2. Open the SAS scripts in the sas/ directory
3. Ensure raw datasets are placed in the data/raw_data/ folder
4. Execute scripts in logical order as documented in project_notes.md

Processed outputs will be generated in the data/processed_data/ directory.

## Learning Outcomes

This project demonstrates proficiency in:

- Applied data management using SAS
- Public health data preparation workflows
- Documentation and reproducibility practices
- Translating raw clinical data into analysis-ready formats

## Acknowledgments

This project was completed as part of PBHL-B552: Data Management with SAS at Indiana University Indianapolis during Spring 2025. The project follows course guidelines and learning objectives outlined in the official syllabus.

All work reflects academic coursework and is shared for portfolio and educational purposes.
