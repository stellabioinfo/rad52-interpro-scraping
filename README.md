# Rad52 InterPro Data Extraction

This project uses Python to extract protein information from the Rad52 family using the public InterPro API (EBI).

## What the script does
- Requests paginated data from the API  
- Extracts accession, name, protein length, taxonomy, and e-value  
- Stores all results in a DataFrame  
- Saves the final dataset as a CSV file

## Technologies
Python, Requests, Pandas, Jupyter Notebook

## Biological purpose
Generate an annotated set of Rad52 proteins for downstream analyses  
(structure, domains, evolution, etc.).
