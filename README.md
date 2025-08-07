 House Price Prediction using Linear Regression
 
# Dataset
- Source: [Kaggle – Housing Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
- Target variable: `price`
- Features: `area`, `bedrooms`, `bathrooms`, `stories`, `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `parking`, `prefarea`, `furnishingstatus`

#Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab
  
#  Steps Performed
1. Loaded dataset** and explored the structure
2. Checked for missing values** – none found
3. Encoded categorical columns** using Label Encoding
4. Separated features and target**
5. Split the dataset** into training and testing sets (80-20)
6. Trained Linear Regression model**
7. Evaluated the model**
   - MAE**: ₹9.8 Lakhs
   - R² Score**: 0.649
8. Visualized results using scatter plots and evaluation metrics

# 📈 Result

The model achieved an R² score of **~0.65**, indicating it explains about 65% of the variability in housing prices — a decent baseline for a simple regression model.



