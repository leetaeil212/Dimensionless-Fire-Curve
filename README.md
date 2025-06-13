# Dimensionless-Fire-Curve

Implementation of dimensionless fire curve models for heat release rate prediction

## Paper
"Prediction of heat release rates using a dimensionless fire curve model reflecting materials specific characteristics"
- Submitted to Fire Safety Journal

## Model Implementations
This repository contains three dimensionless fire curve models:

1. **Dimensionless_Linear_Model.ipynb** - Linear growth and decay model
2. **Dimensionless_Quadratic_Model.ipynb** - Quadratic growth and decay model  
3. **Dimensionless_QuadExp_Model.ipynb** - Quadratic growth with exponential decay model

## How to Use
1. Click on any `.ipynb` file above
2. Click "Open in Colab" button at the top of the file
3. In Colab:
  - Run the first cells to set up the environment
  - Upload your experimental data file when prompted
  - Run all remaining cells (Runtime → Run all)

## Input Data Format
The notebooks accept CSV files with experimental heat release rate data:
- Column 1: Time (seconds)
- Column 2: Heat Release Rate (kW)

## Validated Materials
The dimensionless fire curve models have been successfully applied to:
- Wood Pallet
- Wood Crib
- Cardboard Box
- Plastic Trash Can

Users can apply these models to other combustible materials by uploading their own experimental data.

## Requirements
All required libraries are pre-installed in Google Colab:
- NumPy
- SciPy  
- Matplotlib
- Pandas

## Code Author
Taeil Lee (Korea University)

## Paper Authors
Taeil Lee, Ohseong Lee, Jaewon Shim, Jaeha Lee, and Goangseup Zi

## License
MIT License
