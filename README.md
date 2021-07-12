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
* `/data` - Data
   * `analysis.csv` - Clean data in a processable form
   * `analysis-09052021-clean.xlsx` - Clean data
   * `analysis-years.csv` - Clean data for the publication year analysis in a processable form
   * `analysis-years.xlsx` - Clean data for the publication year analysis
* `/analysis` - Analysis scripts
   * `/descriptive` - Descriptive statistics (.R script and the resulting .PDF report)
   * `/horizontal` - Horizontal statistics (.R script and the resulting .PDF report)
   * `/publishers` - Publisher data (.R script and the resulting .txt output)
   * `/significance` - Significance analysis of the 2012/2013 publication ouput increase (.R script and the resulting .txt output)
   * `/venues` - Venues analysis (.R script and the resulting .txt output)
   * `/year_stacked` - Number and type of publications by year on a stacked bar chart (.R script and the resulting .PDF report)
* `/results.zip` - Data+Analysis in one .zip file

### Original study
This paper is a systematic update of the Original Study. Information about the original study is provided below.
* [Protocol and replication package](http://people.disim.univaq.it/mirco.franzago/collaborativeMDSE)
* [Publication](https://ieeexplore.ieee.org/document/8047991/)

### Current study
* `ClassificationSchemaChanges.pdf` - Classification schema changes since the original study. One of the contributions of the current study is the revised classification framework of the Original Study. This document clearly lists every change.
* `DataExtractionForm-FINAL.xlsx` - Extracted data spreadsheet.
* `Corpus.pdf` - Complete list of the 54 primary studies and the 29 clusters. Every cluster is represented by one paper in the discussions in the paper; these papers are marked with a bold font face.
  * Clarification on the IDs:
    * `PID` - external paper ID. Assigned after the final set of papers has been determined, clustered and ordered. This ID is assigned to the cluster's representative paper (bold type face).
    * `Paper ID` - internal paper ID. Used throughout the study; kept for traceability purposes.

## Legal notice
The replication package and the current artifact evaluation package strictly does not contain any copies of the papers due to the licensing limitations imposed by the publishing organizations.