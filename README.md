# CaratChronicle: Tracing Trends in Diamond Price Dynamics 💎

## Overview

**CaratChronicle** aims to create a sophisticated system for predicting diamond prices using advanced data analytics and machine learning techniques. This project addresses the challenges of predicting price fluctuations in the diamond industry and emphasizes the importance of data-driven approaches.

## Methodology

- **Data Collection & Preprocessing**: We use the `gemstone.csv` dataset, which includes features like carat weight, cut, clarity, color, dimensions, and price.
- **Feature Engineering**: Techniques are applied to extract and enhance features to improve model predictions.
- **Modeling**: We evaluate several regression models to predict diamond prices:
  - **Linear Regression**
  - **Lasso Regression**
  - **Ridge Regression**
  - **ElasticNet Regression**

## Results

Here’s a summary of the model performances:

- **Linear Regression**:
  - RMSE: 1013.90
  - MAE: 674.03
  - R²: 93.69%

- **Lasso Regression** (Top Performer):
  - RMSE: 1013.88
  - MAE: 675.07
  - R²: 93.69%

- **Ridge Regression**:
  - RMSE: 1013.91
  - MAE: 674.06
  - R²: 93.69%

- **ElasticNet Regression**:
  - R²: 85.56%

Lasso Regression achieved the highest R² score, indicating its superior performance among the models evaluated.

## Key Insights

- **Predictive Features**: Significant diamond characteristics such as carat weight, cut quality, clarity, and color greatly influence price dynamics.
- **Model Comparison**: Our selected regression models outperform baseline models in capturing price trends and patterns.

## Quick Start

1. **Clone**:
   ```bash
   git clone https://github.com/yourusername/CaratChronicle.git
   cd CaratChronicle

2. **install**:
   ```bash
   pip install -r requirements.txt
3. **run**:
   ```bash
   python predict_diamond_price.py

## License

MIT License. See LICENSE for details.
