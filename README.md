# Unsupervised Classification of Brookings, South Dakota

## Overview
This project applies unsupervised classification techniques to Sentinel-2 multispectral imagery covering Brookings, South Dakota. The objective is to explore land cover patterns without labeled training data and to evaluate the spatial structure of resulting spectral clusters.

## Study Area
Brookings, South Dakota, USA.

## Data
The analysis uses Sentinel-2 multispectral satellite imagery acquired from the Copernicus Programme. Sentinel-2 provides high-resolution optical data with multiple spectral bands suitable for land cover analysis. Relevant spectral bands were selected and preprocessed prior to classification.

## Methods
Unsupervised classification was implemented in Python using a Jupyter Notebook. The workflow includes:
- Loading and preprocessing Sentinel-2 spectral bands
- Normalizing pixel values
- Applying unsupervised clustering (e.g., K-means)
- Visualizing and interpreting classified outputs

## Tools and Libraries
- Python
- Jupyter Notebook
- NumPy
- scikit-learn
- rasterio
- matplotlib

## Results
The unsupervised classification identifies distinct spectral clusters corresponding to major land cover types in the Brookings area, demonstrating the utility of Sentinel-2 imagery for exploratory land cover mapping.

## Repository Structure
├── Brookins Unsupervised Classification.ipynb
└── README.md

## Author
Stephen Adebisi  
Graduate Student, Geography (GIS & Remote Sensing)
