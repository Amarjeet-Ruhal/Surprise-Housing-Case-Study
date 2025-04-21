# 🏠 House Price Analysis using Ridge and Lasso Regression

## 📄 Abstract
This project analyzes how different housing features impact property prices. Using **Ridge** and **Lasso regression models**, we identify the top 10 most influential variables affecting house prices, providing data-driven insights into what makes a home more valuable.

## 🎯 Objective
To determine the key features influencing house prices and quantify their effects using Ridge and Lasso regression techniques.

## 🧠 Introduction
Understanding house pricing dynamics is essential for buyers, sellers, and real estate investors. By applying regularization-based machine learning models, this study aims to highlight the most critical predictors that drive home prices in a given dataset.

## 🧪 Methodology
1. Data Import  
2. Data Cleaning  
3. Feature Engineering and Preprocessing  
4. Ridge Regression Modeling  
5. Lasso Regression Modeling  
6. Top Feature Comparison  
7. Interpretation of Coefficients  

## 🧾 Code Notebook
Find the complete code and notebook here:  
🔗 [Google Drive Link](https://drive.google.com/drive/u/1/folders/1_b4ldzCloIWUjIGRGCDaIUpTCsCDaI-V)

## 📊 Key Results

### 🔹 Ridge Model - Top Features
| Feature                     | Importance |
|----------------------------|------------|
| OverallQual_9              | 1.1331     |
| Neighborhood_StoneBr       | 1.0984     |
| OverallQual_8              | 1.0885     |
| Neighborhood_Crawfor       | 1.0874     |
| Exterior1st_BrkFace        | 1.0866     |
| Neighborhood_NridgHt       | 1.0848     |
| LandContour_HLS            | 1.0743     |
| CentralAir_Y               | 1.0726     |
| OverallCond_9              | 1.0725     |
| BsmtCond_TA                | 1.0689     |

### 🔸 Lasso Model - Top Features
| Feature                     | Importance |
|----------------------------|------------|
| OverallQual_9              | 1.1952     |
| GrLivArea                  | 1.1165     |
| Neighborhood_Crawfor       | 1.1039     |
| OverallQual_8              | 1.1038     |
| Neighborhood_StoneBr       | 1.0932     |
| Neighborhood_NridgHt       | 1.0919     |
| Exterior1st_BrkFace        | 1.0873     |
| CentralAir_Y               | 1.0815     |
| BsmtCond_TA                | 1.0740     |
| Functional_Typ             | 1.0738     |

## 🔍 Insights

- **GrLivArea**: A larger living area increases house price by ~1.11×.
- **OverallQual**: Better finishing quality can raise the price by ~1.08×.
- **Centralized AC**: Homes with this feature can sell for ~1.08× more.
- **Basement Condition**: Even a typical condition can lead to a ~1.06× price bump.
- **Neighborhoods**: Crawford, Stone Brook, and Northridge Heights stand out as premium locations.

## 🏁 Conclusion
Both models consistently identify **overall quality**, **neighborhood**, and **exterior features** as top predictors of house prices. Lasso uniquely highlights **living area** as a major contributor. These insights serve as a foundation for pricing strategies in real estate.

## 📌 Author
Amarjeet  
B.Tech in Metallurgical and Materials Engineering  
IIT Roorkee

---

