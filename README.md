# Rad52 InterPro Data Extraction

This repository contains a Jupyter Notebook used to retrieve and structure protein information related to the **Rad52 family** from the **InterPro API** (EMBL-EBI). The script performs automated data collection, parsing, and organization into a structured dataset suitable for downstream computational or biological analysis.

## Overview

The notebook queries the InterPro API, iterates through paginated results, extracts relevant metadata, and compiles the information into a pandas DataFrame. The final dataset is exported as a CSV file.

## Data Extracted

- Protein accession  
- Protein name  
- Protein length  
- Taxonomic information  

These fields support structural studies, domain comparison, and integration into multi-omics datasets.

## Technologies Used

- Python  
- Requests (API communication)  
- Pandas (data manipulation)  
- Jupyter Notebook

## Biological Context

The Rad52 protein family plays a central role in DNA repair and homologous recombination.  
By compiling a curated dataset of Rad52-related proteins, this project enables:

- Structural prediction studies  
- Domain annotation  
- Evolutionary analysis

## Output

The repository includes:

- The original `.ipynb` notebook  
- A CSV file containing all retrieved InterPro entries  

## Purpose

This project demonstrates practical experience with:

- Programmatic access to biological databases  
- Data acquisition workflows  
- Reproducible bioinformatics pipelines  
