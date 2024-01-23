# Attribute Weighting and Raster Visualization using AHP

## Introduction

This Python script facilitates attribute weighting through the Analytic Hierarchy Process (AHP) method and offers geospatial raster data visualization based on attribute weights.

## Description

The script leverages several Python libraries:

- **NumPy:** For numerical operations and array handling.
- **Fractions:** To represent rational numbers accurately.
- **Rasterio:** For reading and processing geospatial raster data.
- **Matplotlib:** For data visualization and plotting.

## Workflow

The code follows these steps:

1. **Pairwise Comparison Matrix Creation:** Allows users to input the number of attributes and their names. Then, users provide the relative importance of attributes through pairwise comparisons.

2. **Attribute Weight Calculation:** Utilizes the AHP method to calculate attribute weights.

3. **Consistency Checks:** Ensures consistency in the comparison matrix.

4. **Visualization of Attribute Weights:** Displays the calculated attribute weights.

5. **Geospatial Raster Data Display:** Presents geospatial raster data with customizable colormaps and titles.

6. **Overlaying Raster Layers:** Combines multiple raster layers based on their weights to generate a consolidated output.

## Usage

### Input:

- Provide the number of attributes and their names.
  
### Pairwise Comparison:

- Input the relative importance of attributes through pairwise comparisons.

### Visualization:

- View attribute weights.
- Visualize raster data.

## Requirements

Ensure the following Python libraries are installed:

- NumPy
- Rasterio
- Matplotlib

## Instructions

1. Run the script and follow console prompts to input attribute names and pairwise comparisons.
2. Provide file paths for raster images.
3. View attribute weights and visualize raster data.

## Files

- **GeoSpatial Analysis - AHP Script:** Python script containing the code.
- **Sample Data:** Sample raster files for testing.
- **Working Demo - Pdf:** Screen shots of how to use the script
## Outputs

1. Attribute weights.
2. Visualization of raster data based on attribute weights.
3. Ground Water Potential Areas raster image.

## Notes

- For consistent results, ensure accurate attribute comparisons during input.
- Handle any potential errors during file processing or visualization.

Feel free to explore, contribute, and share your feedback!
