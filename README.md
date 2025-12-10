# Exploratory Data Analysis of Rollercoasters
A Python project using Pandas, NumPy, Matplotlib, and Seaborn

This repository contains an Exploratory Data Analysis (EDA) of a global rollercoaster dataset.  
The project focuses on understanding key characteristics of rollercoasters around the world through data cleaning, transformation, and visualization.  
It includes steps such as inspecting raw data, preparing and engineering features, exploring distributions, and analyzing relationships between variables such as speed, height, type, inversions, and year of introduction.

This work demonstrates a complete and structured EDA workflow suitable for data exploration, insight generation, and future modeling tasks.

---

## Project Overview

This project aims to:
- Explore and understand rollercoaster characteristics and trends  
- Clean and prepare a multi-column dataset (removing duplicates, parsing dates, handling missing values)  
- Analyze key features such as speed, height, coaster type, and year introduced  
- Visualize distributions and relationships between variables  
- Build a clear workflow for real-world data exploration

---

## Project Structure
data/                # Raw and cleaned datasets
notebooks/           # Jupyter notebook with full analysis
plots/               # Exported figures and graphs
README.md            # Documentation
requirements.txt     # Dependencies

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook

---

## Analysis Workflow

### 1. Data Understanding
- Review of dataframe shape, columns, and data types  
- Inspection of missing values  
- Initial descriptive statistics  

### 2. Data Preparation
- Selecting and retaining relevant variables  
- Renaming columns for clarity  
- Converting date fields  
- Handling missing data  
- Removing duplicates using  
  `Coaster_Name + Location + Opening_Date`  

### 3. Feature Exploration
- Distribution of coaster introduction years  
- Speed distribution analysis  
- Type categories (Steel, Wood, Other)  
- Summary statistics  
- Histograms, KDE plots, and boxplots  

### 4. Feature Relationships
- Scatterplots (e.g., Speed vs Height)  
- Correlation heatmaps  
- Pairplots of key variables (speed, height, inversions, G-force)  
- Grouped comparisons when relevant  

---

## Visualizations

Add your plot images here:
