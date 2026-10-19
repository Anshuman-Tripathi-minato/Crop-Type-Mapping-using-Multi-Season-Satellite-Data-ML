# Crop Type Mapping Using Multi-Season Satellite Data

This project uses multi-season Sentinel-2 satellite data and machine learning
to classify crop types and analyse seasonal crop patterns in Karnal, Haryana,
India. The workflow combines raster preprocessing, spectral indices, Random
Forest classification, and spatial analysis for the Kharif and Rabi seasons.

## Project status

The repository contains the working notebooks, training datasets, generated
figures, tables, and classification outputs for the current study. Some large
source rasters are managed outside the repository and are not included in the
published tree.

## Objectives

- Prepare and inspect multi-season satellite data.
- Derive spectral features such as NDVI, NDWI, NDBI, and SAVI.
- Train machine-learning models for crop classification.
- Compare Kharif and Rabi crop patterns.
- Generate classification maps, area statistics, and accuracy assessments.

## Study area

The analysis focuses on the Karnal district of Haryana, India. The district
boundary and related spatial data are available in `data/boundary/` when the
source spatial files are present locally.

## Repository contents

```text
.
├── data/
│   ├── boundary/                 # Karnal boundary files
│   └── raster/                   # Source raster inputs (when available)
├── notebook/
│   ├── Karnal_Kharif.ipynb      # Kharif seasonal analysis
│   ├── Karnal_Kharif2.ipynb     # Additional Kharif processing
│   ├── ml.ipynb                 # Machine-learning workflow
│   └── *.pkl                    # Trained model artifacts
├── outputs/
│   ├── figures/                 # Maps and visualisations
│   ├── machine_learning/       # ML figures and verification tables
│   ├── rasters/                # Derived raster outputs
│   └── tables/                 # Statistics and metadata
├── rABI/                        # Rabi and multi-season analysis outputs
├── *.csv                        # Training data and summary statistics
├── figure/                      # Project figures
└── README.md
```

## Main workflow

1. Define the Karnal study area and prepare seasonal satellite data.
2. Inspect and preprocess the available raster bands.
3. Calculate spectral indices including NDVI, NDWI, NDBI, and SAVI.
4. Build seasonal feature stacks and prepare training data.
5. Train a Random Forest crop-classification model.
6. Validate the results using classification metrics and raster checks.
7. Produce crop maps, area statistics, and Kharif–Rabi comparisons.

## Data and outputs

Important files include:

- `Karnal_Kharif_Training_Data.csv` and `Karnal_Rabi_Training_Data.csv`
  contain seasonal training data.
- `Karnal_Area_Statistics.csv` contains area summaries.
- `notebook/` contains the analysis and machine-learning notebooks.
- `outputs/figures/` contains generated maps and comparison figures.
- `outputs/tables/` contains spectral, raster, and area statistics.
- `rABI/` contains Rabi and multi-season comparison analyses.

Large raster inputs and derived products may be omitted from a clone when their
binary data is not available through Git LFS. The notebooks document the
processing steps and expected inputs.

## Tools and technologies

- Python
- Jupyter Notebook
- NumPy and pandas
- Rasterio and geospatial Python tools
- scikit-learn
- Sentinel-2 multispectral imagery
- Remote sensing and GIS methods

## Running the notebooks

1. Install the Python packages used by the notebooks in a virtual environment.
2. Make sure the required raster inputs and boundary files are available in
   their expected directories.
3. Open the notebooks in `notebook/` and run the preprocessing steps before
   the classification steps.
4. Review generated files in `outputs/` and `rABI/`.

The notebooks are the authoritative source for the current input paths,
feature definitions, model settings, and output names.

## Future work

- Add multi-year seasonal observations.
- Compare additional classification algorithms.
- Improve validation with independent field samples.
- Automate the crop calendar and seasonal comparison workflow.
- Publish reproducible data-preparation and environment instructions.

## Author

**Anshuman Tripathi**

B.Tech Computer Science · Python · Remote Sensing · Machine Learning · GIS
