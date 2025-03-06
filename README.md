# Large Dataset Correlation Analysis Dashboard

## Overview
This project provides an interactive dashboard for analyzing large datasets using correlation analysis. The dashboard allows users to upload large CSV files and processes them efficiently in chunks to handle memory limitations. The tool computes and visualizes the correlation matrix among numerical columns to help identify relationships between features.

## Features
- 📂 **File Upload**: Supports CSV file uploads.
- 📊 **Handles Large Datasets**: Reads CSV in chunks to manage memory efficiently.
- 📈 **Correlation Matrix**: Computes and displays a correlation matrix for numerical columns.
- 🎨 **Heatmap Visualization**: Generates a heatmap using Seaborn for correlation analysis.
- 🔍 **Feature Selection**: Identifies highly correlated features above a defined threshold (default: 0.8).

## Installation & Dependencies
To run this project, ensure you have the following dependencies installed:
```bash
pip install pandas seaborn matplotlib ipywidgets
```
If running in Google Colab, no additional setup is required, as these libraries are pre-installed.

## How to Use
1. Run the Python script in a Jupyter Notebook or Google Colab.
2. Upload a CSV file using the file upload widget.
3. The script reads the dataset in chunks and merges them.
4. It extracts numeric columns and computes the correlation matrix.
5. A heatmap visualization is generated.
6. It identifies highly correlated feature pairs above a threshold of 0.8.

## Example Output
- **Dataset Overview:**
  - Number of rows and columns.
  - Preview of the first few rows.
- **Correlation Matrix:**
  - Tabular display of correlation values.
- **Heatmap Visualization:**
  - Graphical representation of correlation relationships.
- **Highly Correlated Features:**
  - List of feature pairs with high correlation values.

## Future Improvements
- Allow user-defined correlation thresholds.
- Enable selection of target variables for predictive analysis.
- Support additional file formats (Excel, JSON, etc.).
- Provide an option for downloading analysis reports.

## License
This project is licensed under the MIT License.

