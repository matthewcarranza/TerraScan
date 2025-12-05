# TerraScan -- AI Land Use Classifier & Wildfire Risk Scoring System

TerraScan is a deep learning--powered system that automatically
classifies land use from satellite imagery and generates wildfire risk
scores using real-time weather data.

## Overview

TerraScan uses a fine-tuned ResNet50 CNN trained on the EuroSAT dataset
to classify images into 10 land-use categories and combines vegetation
predictions with Open-Meteo weather data to output a 0--100 wildfire
risk score.

## Features

-   Land use classification (97% validation accuracy)
-   Wildfire risk scoring system
-   Satellite image upload workflow
-   Real-time weather integration
-   End-to-end notebook pipeline

## Project Structure

    TerraScan/
    │
    ├── TerraScan.ipynb
    ├── README.md
    ├── data/
    ├── models/
    └── utils/

## Installation

``` bash
git clone https://github.com/<your-username>/TerraScan.git
cd TerraScan
pip install -r requirements.txt
```

## Usage

Run the Jupyter notebook:

    TerraScan.ipynb

## Future Improvements

-   Vision Transformers (ViT)
-   Multi-spectral satellite imagery
-   Web-based dashboard
-   Spatial weather grids

## Contributors

-   Matthew Marietta
-   Matthew Carranza
