# Digitalising Building Layouts

## Project Overview

An architecture company has recently completed an initiative to digitalize their building layout designs. This project leverages Data Science and Machine Learning techniques to analyze these digital layouts, aiming to improve productivity and facilitate robust designs. The project involves extracting geometrical features, clustering designs, and classifying their complexity based on the number of corners.

## Problem Statement

The company has converted the plan view of buildings into bitmaps of size 640 x 480 pixels, resulting in a repository of 1183 such views. They aim to leverage this data to achieve the following goals:

1. **Design Family Grouping**: Group the designs into families based on their shapes to improve insights and standardize designs by creating templates. At least two different approaches should be used.
2. **Complexity Classification**: Classify the complexity of layouts into Low, Medium, and High Complexity based on the number of corners. Establish criteria based on a formal analysis of the layouts.

## Technologies Used

- **Python**
- **Feature Generation**
- **Clustering**
- **OpenCV**
- **Data Analysis**

## Project Description

1. **Extracted Geometrical Features**: Used OpenCV to determine corners, bounding box, hull area, compactness, and interior angles of building layout images.
2. **K-means Clustering**: Applied K-means clustering to group images by feature similarity.
3. **Complexity Scoring**: Developed a complexity score based on the number of corners to categorize images into low, medium, and high complexity.

## Installation

1. **Clone the repository**:

2. **Male sure that all dependencies are already installed before running .ipynb file**:


## Results

- **Design Family Grouping**: Grouped the designs into families to provide insights and create design templates.
- **Complexity Classification**: Classified the complexity of layouts based on the number of corners and established criteria for complexity.
