# Digitalising Building Layouts

## Project Overview

An architecture company has recently completed an initiative to digitalize their building layout designs. This project leverages Data Science and Machine Learning techniques to analyze these digital layouts, aiming to improve productivity. The project involves extracting geometrical features, clustering designs, and classifying their complexity.

## Problem Statement

The company has converted the plan view of buildings into bitmaps of size 640 x 480 pixels, resulting in a repository of 1183 such views. They aim to leverage this data to achieve the following goals:

1. **Design Family Grouping**: Group the designs into families based on their shapes to improve insights.
2. **Complexity Classification**: Classify the complexity of layouts into Low, Medium, and High Complexity.

## Technologies Used

- **Python**
- **Feature Generation**
- **Clustering**
- **OpenCV**
- **Data Analysis**

## Project Description

1. **Extracted Geometrical Features**: Used OpenCV to determine corners, bounding box, hull area, compactness, and interior angles of building layout images.
2. **K-means Clustering**: Applied K-means clustering to group images by feature similarity.
3. **Feature Reduction**: Removed redundant features by analysing collinearity and multicollinearity using heatmap and 
4. **Complexity Scoring**: Developed a complexity score based on the number of corners to categorize images into low, medium, and high complexity.

## Installation

1. **Clone the repository**:

2. **Male sure that all dependencies are already installed before running .ipynb file**:


## Results

- **Design Family Grouping**: Created 36 clusters and achieved 89% accuracy in classifying layouts into these clusters.
- **Complexity Classification**: Classified the complexity of layouts based on the number of corners present in the layout.
