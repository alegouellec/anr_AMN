# ANR_AMN

Repository containing resource files, metadata, and processed datasets related to the **ANR_AMN** project.

## Overview

This repository gathers the main working files used for patient/sample description, biomarker metadata, metabolomics, and lipidomics analyses.

The objective of this repository is to centralize the datasets and resource tables used in the project in a structured and accessible way.

## Repository content

### Patient and cohort information
- `01_Récap des patients par analys...`
  Summary table of patients by analysis.
- `02_Patients_Metadata.xlsx`
  Patient metadata file.
- `03_BIOMARK_Metadata.xlsx`
  Metadata related to the BIOMARK dataset.
- `04_Data_BIOMARK.csv`
  Exported BIOMARK data table.

### Metabolomics data
- `05_Metabo_C18.xlsx`
  Processed metabolomics dataset for C18 analysis.
- `05_Metabo_C18_InChI.csv`
  Annotation table including InChI-related information for C18 metabolites.
- `06_SamplemetaData_C18.csv`
  Sample metadata associated with C18 metabolomics.
- `07_Metabo_HILIC_Results.xlsx`
  Processed metabolomics dataset for HILIC analysis.
- `07_Metabo_HILIC_Results_Expan...`
  Expanded HILIC results table.
- `08_Metabo_HILIC_Sample_Metad...`
  Sample metadata associated with HILIC metabolomics.

### Lipidomics data
- `09_Lipido_Globale.xlsx`
  Global lipidomics dataset.
- `10_Lipido_Eicosa.xlsx`
  Eicosanoid/lipid mediator dataset.

### Additional files
- `C18_raw.xlsx`
  Raw or less processed C18 metabolomics data.
- `Covid_data_Wuhan.xlsx`
  Additional comparison/reference dataset.

## Data organization

The files are organized by analysis type:
- **clinical / patient metadata**
- **metabolomics (C18 and HILIC)**
- **lipidomics**
- **supporting reference files**

## Recommended use

Before starting any analysis:
1. Check the corresponding metadata file.
2. Verify sample identifiers across datasets.
3. Use processed tables together with sample metadata for statistical analyses.
4. Keep raw and processed files clearly separated.

## Notes

- File names were kept close to the original project naming for traceability.
- Some files may contain sensitive or project-internal information and should be handled accordingly.
- This repository is intended for project organization, data sharing within the collaboration, and downstream analyses.

## To do

- Add a short description of the ANR_AMN project.
- Specify file provenance and update history.
- Add scripts and workflows if analysis code is included later.
- Clarify naming conventions for raw vs processed data.

## Contact

Project: **ANR_AMN**  
Maintainer: **Audrey Le Gouellec** *(to adapt if needed)*
