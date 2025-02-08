# Analysis of U.S. Flight Data

This repository contains a project for analyzing U.S. flight data from January to April 2008. The project was developed as part of my class work and demonstrates the process of data extraction, cleaning, exploratory analysis, visualization, and text analysis using R. The analysis is documented using two main files:

- **main.rnw**: A LaTeX Beamer presentation with embedded R code (using knitr/Sweave) that outlines the analysis steps.
- **killer plot.qmd**: A Quarto document that provides interactive Shiny plots for exploring flight delay data and airline comparisons.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Files in the Repository](#files-in-the-repository)
- [Requirements](#requirements)

## Overview

This class project analyzes U.S. flight data by:
- Extracting flight records from an SQLite database.
- Cleaning and summarizing the data.
- Visualizing various aspects of departure delays using charts (lollipop charts, density plots, hex plots, and U.S. maps).
- Performing text analysis (word frequency and sentiment analysis) on customer reviews.
- Creating interactive Shiny plots for comparing airlines.

## Features

- **Data Extraction**: Uses SQL queries to extract flight data and review data from an SQLite database.
- **Data Visualization**: Includes various charts and maps that illustrate departure delay trends, on-time performance, and regional delay patterns.
- **Text Analysis**: Performs word frequency and sentiment analysis on customer reviews.
- **Interactive Shiny Plots**: The Quarto document contains interactive plots with user controls (e.g., selecting origin/destination pairs and airline comparisons).

## Files in the Repository

- `main.rnw`  
  A LaTeX Beamer presentation that documents the analysis process with embedded R code.

- `killer plot.qmd`  
  A Quarto document with interactive Shiny plots for further data exploration and airline comparison.

- **Data Files** (please place these in the correct folder as specified in the code):
  - `final_project.db`: The SQLite database containing the flight data and customer reviews.
  - `rating.xlsx`: An Excel file containing airline ratings.

- (Optional) `styles.css`  
  A CSS file to customize the appearance of the Quarto slides.

## Requirements

- **R Version**: R 4.0.0 or higher
- **Key R Packages**:
  - `shiny`
  - `RSQLite`
  - `ggplot2`
  - `dplyr`
  - `stringr`
  - `nortest`
  - `MASS`
  - `tm`
  - `wordcloud`
  - `knitr`
  - `kableExtra`
  - `usmap`
  - `viridis`
  - `readxl`
  
Install any missing packages using the command, for example:

```r
install.packages(c("shiny", "RSQLite", "ggplot2", "dplyr", "stringr", "nortest", "MASS", "tm", "wordcloud", "knitr", "kableExtra", "usmap", "viridis", "readxl"))
```
