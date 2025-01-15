# FitVista: Sculpting Wellness, Shaping Lives

## Overview
FitVista is a predictive model designed to classify clients into obesity risk categories based on lifestyle and behavioral factors. This machine learning solution aims to empower fitness professionals with actionable insights, enabling them to tailor fitness plans for clients and drive better health outcomes.

---

## Objective
The primary goal of this project is to:
1. Develop a robust **Obesity Classification Model** to estimate obesity levels.
2. Provide actionable reports to guide fitness professionals in customizing fitness plans for clients.
3. Establish a foundation for future enhancements, such as delivering personalized fitness recommendations.

---

## Features
- **Obesity Classification Model:** Predicts obesity levels across seven risk categories.
- **Insights:** Reports highlight key factors contributing to obesity, such as high-calorie intake and eating habits.
- **Model Evaluation:** Comparative analysis of Logistic Regression, Decision Tree, and Random Forest classifiers.
- **Data Visualization:** Charts and plots to support findings and interpret results effectively.

---

## Dataset
- **Source:** [Estimation of obesity levels based on eating habits and physical condition (2019)](https://doi.org/10.24432/C5H31Z) from the UCI Machine Learning Repository.
- **Details:**
  - 2,111 entries with 17 features.
  - Includes data from individuals in Mexico, Peru, and Colombia.
  - Features include eating habits, physical conditions, and demographic details.
  - Dataset composition:
    - 77% generated via **Weka** and **SMOTE**.
    - 23% from user inputs on a web platform.
  - Classification Categories:
    - Insufficient Weight
    - Normal Weight
    - Overweight
    - Obesity I, II, III
  - **Outliers:**
    - Observed in individuals aged 35 and above.
    - Dataset skewed towards younger age groups (18-40).

---

## Machine Learning Models
1. **Logistic Regression:**
   - Strengths: Improved performance for specific classes.
   - Challenges: Inconsistent predictions for certain categories.
2. **Decision Tree:**
   - Strengths: Simple and interpretable.
   - Challenges: Variability in performance; prone to overfitting.
3. **Random Forest Classifier:**
   - Strengths: Robust and stable across all obesity categories.
   - Preferred model for its overall classification performance.

---

## Results and Insights
- **Key Findings:**
  - High-calorie intake correlates strongly with higher obesity levels.
  - Individuals eating "Always" between meals are more likely to fall into higher obesity categories.
  - Gender distribution shows similar obesity patterns, with specific variations in extreme categories.
- **Model Selection:**
  - **Random Forest Classifier** is recommended for its consistent and accurate predictions across all classes.

---

## Tools and Technologies Used
- **Programming Language:** Python
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn
- **Platform:** Google Colab
- **Data Visualization:** Histograms, bar plots, and classification metrics for insights.

---

## Future Scope
- **Mobile Applications:** Develop apps to provide real-time updates and fitness recommendations to professionals and users.
- **Personalized Plans:** Incorporate tailored fitness plans based on obesity classification results.
- **Advanced Models:** Explore deep learning techniques for enhanced accuracy.
- **Socialization:** Integrate push notifications for better user engagement.

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone <repository_url>
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
3. Open the `Group_14_Obesity_Classification.ipynb` notebook in Google Colab or Jupyter Notebook.
4. Upload the provided dataset to the notebook environment.
5. Run all the cells sequentially to:
   - Load and preprocess the dataset.
   - Train and evaluate the machine learning models.
   - Visualize results and extract insights.

---

## Future Enhancements
- **Integration with Mobile Platforms:** Build a mobile application to provide real-time access to fitness reports and obesity classifications.
- **Tailored Fitness Plans:** Extend the system to recommend customized fitness and dietary plans based on user profiles.
- **Advanced Modeling:** Experiment with deep learning models like Neural Networks for better classification accuracy.
- **Data Expansion:** Enrich the dataset with inputs from diverse global demographics for broader applicability.

---

## Contributors
- **Sai Praneeth Veerapalli**
- **Shubhang Yadav Sandaveni**
- **Swapna Vippaturi**

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.


