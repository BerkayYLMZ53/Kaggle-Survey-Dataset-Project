# 📊 Kaggle Survey Data Mining and Preprocessing Comparison Project

This project is a data mining study conducted on the **Kaggle Survey Dataset (`kagglesurvey.csv`)**, which contains preferences of data scientists and software developers. The primary goal of the project is to demonstrate the performance differences between models trained on raw data versus those trained after applying data preprocessing steps.

## 🎯 Project Objective and Methodology
In data mining, raw data is often noisy, contains missing values, and is not directly suitable for modeling. In this project, the analysis is split into two main stages:
1. **Original (Unpreprocessed) Data Analysis:** KNN, Decision Tree, Naive Bayes, and Random Forest models were trained directly on the raw dataset without any prior cleaning or optimization to establish baseline performance metrics.
2. **Preprocessed Data Analysis:** Missing values, potential data leaks, and class imbalances in categorical variables were addressed; the same algorithms were then trained again to evaluate the changes in performance.

## 📊 Dataset Structure
The `kagglesurvey.csv` dataset used in this project includes key variables regarding user preferences:
* `WorkToolsSelect`: Tools actively used by participants in data science and software development workflows.
* `LanguageRecommendationSelect`: Programming languages recommended for beginners.
* `EmployerIndustry`: The industry sector in which the employers operate.
* `WorkAlgorithmsSelect`: Machine learning and data mining algorithms used most frequently in workflows.

## 🛠️ Technologies and Models Used
* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **Algorithms Used:**
  * **K-Nearest Neighbors (KNN):** Distance-based classification analysis (a neighborhood value of `k=225` was tested in the sample architecture).
  * **Decision Tree:** Classification trees based on Entropy and Gini criteria.
  * **Gaussian Naive Bayes:** Probability-based classification approach.
  * **Random Forest Classifier:** Ensemble learning approach utilizing groups of decision trees.

## 📈 Implemented Workflows and Analyses
* **Data Preprocessing:** Handling or imputing missing values, and converting categorical variables into numerical format using `LabelEncoder`.
* **K-Fold Cross-Validation:** Computed cross-validation scores to evaluate generalization capabilities and monitor for potential overfitting.
* **Performance Metrics:** Models were evaluated multi-dimensionally using `accuracy`, `precision`, `recall`, and `f1_score` metrics, rather than relying solely on raw accuracy.
* **Visualization:** Confusion matrices were plotted using `sns.heatmap` to analyze the classification performance of the models (particularly KNN).

## 📁 Repository Content
* 📄 `kagglesurvey.csv`: The raw survey dataset analyzed in the project.
* 📓 `Veri_Orijinal_Hali.ipynb`: Modeling work performed on the raw data without preprocessing steps.
* 📓 `Veri_Onisleme_Yapılmış.ipynb`: Preprocessing steps, transformations, and cross-validation-supported modeling work.

## 🚀 Running the Project Locally

1. Clone the repository to your computer:
   ```bash
   git clone https://github.com/BerkayYLMZ5353/kaggle-survey-data-mining.git
   ```
```
