# Create-Shapefiles
# Shapefile Exporter

This Python Notebook automates the process of exporting feature classes from an ArcGIS geodatabase to shapefiles. It is specifically designed to update the infowater map on the engineering computer at Hixson Utility. 

## Purpose

The purpose of this code is to streamline the task of exporting feature classes to shapefiles for use in GIS applications. It sets up workspace environments, lists feature classes to export, specifies the output folder for shapefiles, and then executes the export process for each feature class. 

## How to Use

1. Ensure that ArcPy is installed in your Python environment.
2. Modify the workspace path (`arcpy.env.workspace`) to point to the location of your feature classes in the ArcGIS geodatabase.
3. Update the list `feature_classes` with the names of the feature classes you want to export.
4. Set the `output_shapefile` variable to specify the folder where shapefiles will be saved.
5. Execute the code to export the feature classes to shapefiles.

## Note

Ensure that the paths and names of feature classes and output folders are correctly specified to avoid errors during execution.
