# README
This file is a guide to the artifact evaluation for MODELS 2021.

## What is the artifact?
The artifact is the replication package for the paper _Collaborative Model-Driven Software Engineering: A Systematic Update_. The full dataset including raw data, ETL scripts, and analysis scripts produced during the study are available.

## How to obtain the artifact?
This artifact is openly available from its [GitHub repository](https://github.com/S2-group/cmdse-2021-replication-package).

## Contents
The README file of the replication package contains up-to-date information about the contents of the package. For convenience, we provide the contents below as well.

### Data & analysis scripts

This replication package is structured as follows:
* `/corpus` - Corpus: papers, and ID mappings (for traceability).
  * `01_Corpus_full.xlsx` - Full corpus: the list of the 886 papers identified through the systematic search and screened during the study. The data contains the inclusion/exclusion criteria of the papers, including the criterion an exclusion was based on.
  * `02_Primary_studies_included.xlsx` - The list of 54 papers included in our study. Information about the snowballing round the paper was found included.
  * `03_Clusters.xlsx` - The list of 29 clusters.
  * `04_Primary_studies_clustered_with_PID.xlsx` - The list of 29 clusters with the eventual ID used in the paper.
  * `05_Corpus-final.pdf` - An integrated overview of the 54 included papers shown in the 29 clusters.
  * `README.MD` - Information about the ID mappings.
* `/data` - Data.
   * `analysis.csv` - Clean data in a processable form.
   * `analysis-09052021-clean.xlsx` - Clean data.
   * `analysis-years.csv` - Clean data for the publication year analysis in a processable form.
   * `analysis-years.xlsx` - Clean data for the publication year analysis.
* `/analysis` - Analysis scripts.
   * `/descriptive` - Descriptive statistics (.R script and the resulting .PDF report).
   * `/horizontal` - Horizontal statistics (.R script and the resulting .PDF report).
   * `/publishers` - Publisher data (.R script and the resulting .txt output).
   * `/significance` - Significance analysis of the 2012/2013 publication ouput increase (.R script and the resulting .txt output).
   * `/venues` - Venues analysis (.R script and the resulting .txt output).
   * `/year_stacked` - Number and type of publications by year on a stacked bar chart (.R script and the resulting .PDF report).
* `/results.zip` - Data+Analysis in one .zip file.
* `ClassificationSchemaChanges.pdf` - Classification schema changes.
* `DataExtractionForm-FINAL.xlsx` - Extracted data spreadsheet.

### Original study
* [Protocol and replication package](http://people.disim.univaq.it/mirco.franzago/collaborativeMDSE)
* [Publication](https://ieeexplore.ieee.org/document/8047991/)



## Legal notice
The replication package and the current artifact evaluation package strictly does not contain any copies of the papers due to the licensing limitations imposed by the publishing organizations.