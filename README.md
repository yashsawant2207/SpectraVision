🛰️ SpectraVision: Geospatial CV Engine
SpectraVision is a specialized Computer Vision pipeline designed to transform raw Sentinel-2 multispectral satellite data into high-contrast environmental intelligence. By deciphering non-visible light (NIR and SWIR), the system automates the extraction of biophysical indices and applies CV techniques to segment complex terrains.

🚀 Key Features
Multispectral Processing: Automated ingestion and percentile stretching of 12-bit Sentinel-2 bands.
Spectral Engine: Real-time calculation of 6 key indices: NDVI, NDWI, MNDWI, SAVI, NDBI, and ARVI.
CV Feature Extraction: Integration of OpenCV for Canny edge detection and semantic segmentation of forest boundaries.

🛠️ Tech Stack
Language: Python 3.x
Geospatial: rasterio, geopandas
Computer Vision: OpenCV, NumPy
Visualization: Matplotlib, Streamlit, ipywidgets

📂 Project Structure
SpectraVision.ipynb: Main analysis and CV pipeline.
sample_data/Mumbai/: Multispectral .tiff bands (B02, B03, B04, B08, B11) used for testing.
app.py: Code for the interactive frontend dashboard.

IMPORTANT
Rendering Note: If the notebook fails to render on GitHub due to widget metadata, please view it directly in Google Colab.

Google Colab : https://colab.research.google.com/drive/15CSgDyWcX2hNUcv7Ex7zFQzM3rplLClA?usp=sharing
