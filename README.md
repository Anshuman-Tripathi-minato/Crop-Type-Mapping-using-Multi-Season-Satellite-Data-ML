# Crop-Type-Mapping-using-Multi-Season-Satellite-Data-ML-
AI-assisted crop type and cropping pattern mapping using multi-season Sentinel-2 satellite imagery, Google Earth Engine, Random Forest, and NDVI analysis.

# 🌾 AI-Assisted Crop Type Mapping using Multi-Season Satellite Data

## Project Status

🚧 **Work in Progress**

This project has recently been started and is currently under development.

The objective is to classify agricultural crop types and analyze cropping patterns using multi-season Sentinel-2 satellite imagery, vegetation indices, and Machine Learning techniques in Google Earth Engine (GEE).

---

# Project Overview

Agricultural crop mapping plays an important role in:

- Precision Agriculture
- Food Security
- Land Use Monitoring
- Crop Health Assessment
- Seasonal Crop Analysis

This project uses temporal satellite observations from different crop seasons (Kharif and Rabi) to distinguish agricultural fields based on vegetation behavior.

---

# Objective

Develop an AI-assisted crop classification workflow that combines:

- Multi-season Sentinel-2 imagery
- NDVI time-series analysis
- Google Earth Engine
- Random Forest classification
- Spatial analysis
- Accuracy assessment

---

# Study Area

Punjab–Haryana Agricultural Belt, India

(Area of Interest will be updated after preprocessing.)

---

# Dataset

Satellite Imagery

- Sentinel-2 Surface Reflectance

Bands Used

- Band 4 (Red)
- Band 8 (Near Infrared)
- SWIR (Optional)

Ancillary Data

- AOI Boundary
- Training Samples
- Validation Samples

---

# Tools & Technologies

- Google Earth Engine
- Python
- JavaScript (GEE)
- QGIS
- Scikit-learn
- Remote Sensing
- GIS

---

# Machine Learning

The following classifiers will be explored:

- Random Forest
- Support Vector Machine (Optional)

---

# Workflow

1. Define Area of Interest
2. Download Multi-season Sentinel-2 Images
3. Cloud Masking
4. Band Stacking
5. NDVI Generation
6. Seasonal Composite Creation
7. Feature Engineering
8. Training Sample Collection
9. Random Forest Classification
10. Accuracy Assessment
11. Area Statistics
12. Final Crop Type Map

---

# Expected Outputs

- Multi-season NDVI Maps
- Crop Classification Map
- Cropping Pattern Map
- Confusion Matrix
- Accuracy Metrics
- Area Statistics
- Final Thematic Maps

---

# Repository Structure

```
crop-type-mapping/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── training/
│
├── gee/
│   ├── preprocessing.js
│   ├── ndvi.js
│   ├── classification.js
│
├── notebooks/
│
├── outputs/
│   ├── maps/
│   ├── figures/
│   └── reports/
│
├── docs/
│
├── README.md
└── requirements.txt
```

---

# Current Progress

- [x] Literature Review
- [x] Project Planning
- [ ] Study Area Selection
- [ ] Download Sentinel-2 Images
- [ ] Cloud Masking
- [ ] NDVI Calculation
- [ ] Multi-season Composite
- [ ] Training Data Collection
- [ ] Random Forest Model
- [ ] Classification
- [ ] Accuracy Assessment
- [ ] Final Maps
- [ ] Documentation

---

# Future Improvements

- Multi-year crop monitoring
- Time-series classification
- Deep Learning approaches
- Automatic crop calendar extraction
- Integration with agricultural statistics

---

# References

- Sentinel-2
- Google Earth Engine
- Scikit-learn Documentation
- QGIS Documentation

---

## Author

Anshuman Tripathi

B.Tech Computer Science

Python • Google Earth Engine • Remote Sensing • Machine Learning • GIS
