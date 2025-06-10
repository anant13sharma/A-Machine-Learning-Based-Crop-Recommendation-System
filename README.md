# A-Machine-Learning-Based-Crop-Recommendation-System
A machine learning-based crop recommendation system trained on 69K+ samples. It predicts the most suitable crop based on soil nutrients (N, P, K), pH, rainfall, temperature, and humidity. Models like Random Forest, Decision Tree, and Naive Bayes are used for multiclass classification.

---

## Dataset

The dataset used in this project was compiled by the **Indian Council of Agricultural Research (ICAR)** and made publicly available by the **Indian Chamber of Food and Agriculture (ICFA)**. It includes soil nutrient ratios (N, P, K, C, S, Mg, Fe, Mn), pH levels, temperature, humidity, and rainfall data across 69,718 samples covering 22 crops.

- **Source:** Indian Chamber of Food and Agriculture (ICFA)  
- **Accessed from:** [Figshare - Crop Recommendation Dataset](https://figshare.com/articles/dataset/Crop_Recommendation_dataset/26308696)

### Target
- Multiclass output: Crop name (22 classes)

---

## Preprocessing Steps
- Removed null/NaN values
- Removed duplicate entries
- Feature selection
- Correlation analysis using heatmaps and pair plots
- Normalization of features

---

## Exploratory Data Analysis (EDA)
- Correlation heatmap
- Pairwise plot grid
- Relational plots
- Distribution plots
- Mean values per crop class

---

## Machine Learning Models Used
- Logistic Regression
- Naive Bayes
- Decision Tree
- Random Forest
- Neural Network

(Additional models such as SVM and Neural Networks can be added in future iterations)

---

## Results Summary
| Model               | Accuracy |
|----------------------|----------|
| Naive Bayes          | ~40%     |
| Logistic Regression  | ~77%     |
| Decision Tree        | ~72%     |
| Random Forest        | ~92%     |
| Neural Network       | ~98%     |

- Neural Network achieved the highest accuracy (~98%) but with higher complexity. Random Forest also performed well without overfitting.

---

## Learnings
- Importance of feature selection and preprocessing
- EDA helps in understanding relationships between variables
- Model comparison is key for choosing the right solution

---

## Future Work
- Implement more advanced models like SVM and XGBoost
- Build a secondary model to predict actual yield for recommended crops
- Develop a user-friendly web interface or mobile app for farmer use

  
## Acknowledgements
- Thanks to publicly available datasets from Kaggle, ICAR, and RARI.

---
