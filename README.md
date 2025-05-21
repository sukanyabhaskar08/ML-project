# ML-project
# 🏠 House Price Prediction using XGBoost

This project implements a house price prediction model using the Ames Housing dataset. It uses feature preprocessing, normalization, and XGBoost regression to estimate the sale price of houses.

## 📁 Dataset
- Dataset used: `AmesHousing.csv`
- Source: Available online or via Kaggle

## 📊 Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`
- `xgboost`

## ⚙️ Workflow
1. Load and clean the dataset
2. Encode categorical variables
3. Normalize numerical features for visualization
4. Train/Test split
5. Train XGBoost Regressor
6. Evaluate using RMSE and R²
7. Visualize:
   - Feature importances
   - Actual vs Predicted prices
   - Residuals and Error distributions

## 📈 Results
- **RMSE**: ~[add your value from the output]
- **R² Score**: ~[add your value from the output]

## 📸 Sample Visuals
- Boxplots of normalized features
- Feature Importance (Top 20)
- Actual vs Predicted scatter plot
- Overlayed Histogram (Actual vs Predicted)

## 🧠 Author
Pooja Sinha  
[Your GitHub Profile Link]

## 💡 Note
You can run this project using Google Colab or Jupyter Notebook. Make sure you install all necessary dependencies using:

```bash
pip install xgboost seaborn
