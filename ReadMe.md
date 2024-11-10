# CEMADEN Summer 2023 Project

This repository contains the work completed during the summer of 2023 for CEMADEN, focusing on soil moisture analysis, spatial predictions, and kriging methodologies. The project encompasses data preprocessing, predictive modeling, and algorithmic implementations primarily in Jupyter notebooks.

## Table of Contents

- [Project Overview](#project-overview)
- [Directory Structure](#directory-structure)
- [Dependencies](#dependencies)
- [Data Files](#data-files)
- [Notebooks](#notebooks)
- [Contact](#contact)

---

## Project Overview

The main objective of this project was to develop methods for predicting soil moisture using spatial and time series data. The project employs various machine learning algorithms, statistical analysis, and geostatistical approaches such as kriging for soil moisture interpolation. These methods are tested and validated on datasets provided by CEMADEN.

## Directory Structure

The repository is organized as follows:
CEMADEN/
├── data/
│   ├── Moisture_12m.txt
│   ├── Moisture_5m.txt
│   ├── Moisture_9m.txt
│   ├── Moisture_Content_All_Soils_Result.txt
│   ├── SecondaryData.txt
│   ├── SecondaryDataPlasticity.txt
│   ├── newData.csv
├── Enhancing_Spatial_Predictions__An_Exploratory_Study.ipynb
├── Genetic Algorithms - BreastCancer PCA test.ipynb
├── Genetic Algorithms - Initial Tests.ipynb
├── Soil Moisture - Cokriging & N Dimensional Interpolation.ipynb
├── Soil Moisture - Gaussian Kriging and Cokriging.ipynb
├── Soil Moisture - Mathematical Analysis of Geostatistical Models.ipynb
├── Soil Moisture - Spherical Kriging.ipynb
├── Soil Moisture - Time Series Forecasting + Shapiro-Wilk Test.ipynb
├── Soil Moisture - Variogram Models for Cokriging.ipynb
├── README.md

## Dependencies

To replicate the analyses and run the notebooks, the following libraries are recommended:

- Python 3.x
- Jupyter Notebook
- Numpy
- Pandas
- Scikit-learn
- SciPy
- Matplotlib
- GeoPandas
- PyKrige
- Other dependencies specific to the algorithms in the notebooks

## Data Files

The repository contains several text files and CSV files with soil moisture data at different depths and formats:

- **Moisture_5m.txt, Moisture_9m.txt, Moisture_12m.txt**: Soil moisture data files at depths of 5m, 9m, and 12m, respectively.
- **Moisture_Content_All_Soils_Result.txt**: Consolidated soil moisture data for all samples.
- **SecondaryData.txt & SecondaryDataPlasticity.txt**: Secondary data files likely containing additional soil properties.
- **newData.csv**: Primary dataset used for analysis and model training.

## Notebooks

Each Jupyter notebook focuses on a specific analysis or algorithm relevant to soil moisture prediction and kriging techniques:

1. **Enhancing_Spatial_Predictions__An_Exploratory_Study.ipynb**: Exploration of spatial prediction methods to enhance the accuracy of soil moisture forecasting.
2. **Genetic Algorithms - BreastCancer PCA test.ipynb**: Implementation of genetic algorithms for dimensionality reduction using PCA (originally tested on a breast cancer dataset).
3. **Genetic Algorithms - Initial Tests.ipynb**: Initial tests and exploration of genetic algorithms on soil moisture data.
4. **Soil Moisture - Cokriging & N Dimensional Interpolation.ipynb**: Applying cokriging and N-dimensional interpolation techniques for soil moisture estimation.
5. **Soil Moisture - Gaussian Kriging and Cokriging.ipynb**: Gaussian kriging and cokriging methods to interpolate soil moisture data.
6. **Soil Moisture - Mathematical Analysis of Geostatistical Models.ipynb**: Mathematical background and analysis of various geostatistical models used in soil science.
7. **Soil Moisture - Spherical Kriging.ipynb**: Implementation of spherical kriging for soil moisture prediction.
8. **Soil Moisture - Time Series Forecasting + Shapiro-Wilk Test.ipynb**: Time series forecasting of soil moisture with normality testing using the Shapiro-Wilk test.
9. **Soil Moisture - Variogram Models for Cokriging.ipynb**: Analysis and modeling of variograms, essential for cokriging in geostatistics.

## Contact

For further information or questions, please reach out to the repository owner.

--- 
