# Reproducible Research Package - Stata

---
title: "README for Reproducibility Packages"
output:
  word_document: default
  html_document: default
---

Welcome to the **Reproducible Research Fundamentals 2024** training repository. This repository will guide you through all the exercises across the following stages:

Author: Xuerong Lei
Last modified: October 3, 2024

This reproducibility package contains the work developed during the Reproducibility Research Training 2024.

- **Stata Version**: Version 18.0

- **0. Path changes**: 
1. Please change the paths in your "main.do" do file with your own path in line 12-17 accordingly.

- **1. Data Processing**: 
1. Please make sure there is no other data using "clear all" before running codes. 
2. Please switch to from "0" to "1" from line 39 if your "if()" is 0 to make sure you run all the do files in order to not-run/run do-files 

- **2. Data Construction**: Build indicators and variables from the processed data.
- **3. Data Analysis**: Conduct analyses using the constructed data.
- **4. Reproducibility Package**: Package all work into a reproducible format for sharing and validation.



*Folder Structure*

There are 2 main folders.

1. Stata: It contains the code and the outputs.
2. Data: It contains the original data files and intermediates.

The Stata version used to create these outputs is Stata 18. The ado folder in the Code folder contains the packages (dependencies) with the appropriate versions necessary to replicate the results.

In the main.do file located in Stata/Code, you should change the paths to be in accordance with the location of this elements in your local drive.

*Data Files*

There are three raw datasets:

1. TZA_CCT_baseline.dta
2. TZA_amenity.csv
3. treat_status.dta

These inputs were provided by the teaching team.

*Code Files*

There are four data scripts:

1. main.do: The main.do file executes the whole process to generate the outputs.
2. 01-processing-data.do: It creates tidy and clean data.
3. 02-constructing-data.do: It creates the indicators of interest.
3. 03-analyzing-data.do: it creates the analysis outputs.

*Test*
I run 2 times the codes, there is no error.
