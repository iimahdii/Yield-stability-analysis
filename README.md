# Yield-stability-analysis
Yield stability analysis reveals sources of large-scale nitrogen loss from the US Midwest [Paper](https://www.nature.com/articles/s41598-019-42271-1) . 



# Dataset
This Stability.ipynb contains the dataset for Crop Yield. 
The procedure is as follows: first, import unprocessed satellite images from Google Earth Engine; next, carry out image processing tasks, 
including applying a mask and clipping values, before saving the processed images;
finally, generate histograms from the processed images and store the resulting histogram file.

## Crop Yield Data 

The dataset has been taken from Brain Hung's [Crop Yield Prediction] implemented for Google Colab with 🐍 pyton and 🌕 Jupyter. 

## Dataset

| dataset | description | num bands | spatial resolution | temporal resolution | 
|---------|-------------|-----------|--------------------|---------------------|
|[MOD09A1](https://developers.google.com/earth-engine/datasets/catalog/MODIS_006_MOD09A1)| surface reflectance | 7 | 0500 m | 8 day  |
|[MYD11A2](https://developers.google.com/earth-engine/datasets/catalog/MODIS_006_MYD11A2)| surface temperature | 2 | 1000 m | 8 day  | 
|[MCD12Q1](https://developers.google.com/earth-engine/datasets/catalog/MODIS_051_MCD12Q1)| cropland mask       | 1 | 0500 m | 1 year |

## Setup

Most of the required dataset are available here and on [Google Drive](https://drive.google.com/drive/folders/1MyHkG1Q4GiSNy4KaIPTVWb0sBeuJe7OV).


# histogram veg
with num bins=32, num bands=11
