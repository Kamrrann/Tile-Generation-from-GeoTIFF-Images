
## Author: Kamran Ali



# Tile Generation from GeoTIFF Images

This notebook presents a Python script designed to facilitate the generation of smaller tiles from large GeoTIFF images. The process involves partitioning the images into manageable sections, often referred to as tiles, which can be useful for various applications such as processing large datasets in smaller chunks or serving imagery over the web efficiently.

# Key Features


## Setup and Dependencies 
Importing necessary libraries: This section includes importing libraries like rasterio and os required for image processing and file operations.

## Input and Output Paths
Defining file paths: Set paths for input images and output directory where the tiles will be saved.

## Tile Generation Function
get_tiles function: This function generates tiles from the input raster dataset. It takes into account the width and height of the tiles and iterates over the raster dataset using a sliding window approach.

## Processing Image Files
Listing image files: All TIFF files in the input directory are listed for processing.
Opening and processing image files: Each image file is opened, and tiles are generated using the get_tiles function. The tiles are then saved in the output directory.



# Contributing

I welcome contributions and feedback from the community. Feel free to open issues, propose enhancements, or submit pull requests to improve this project.

