<img src="https://github.com/user-attachments/assets/5c48f2a1-45e5-4022-a8bb-3cf564fe2503" width="400"/>
<img src="https://github.com/user-attachments/assets/391ea6e1-16ff-4d4a-a6df-24c486824d0e" width="400"/>

# **In this Repository you can find the code I used for my Thesis that was done for RadboudUMC**

# **EARLY PREDICTION OF ICU ADMISSION USING MACHINE LEARNING**
## Combining Vital Signs, Diagnoses, and Demographics to Support High-Risk Patient Identification at Hospital Admission

## 1 Introduction
Being able to predict whether a patient will need ICU care right at the time they’re admitted to the hospital could significantly improve patient outcomes. It would allow medical teams to act sooner, prioritize care more effectively, and make smarter use of hospital resources. Early identification of high-risk patients helps prevent deterioration, reduces delays, and eases the strain on emergency services.

Radboudumc, a university hospital in the Netherlands, has already shown the value of such an approach. By continuously monitoring patients' vital signs in regular hospital wards, they were able to reduce ICU admissions by 35% (Eddahchouri et al., 2022; Hernández & van den Berg, 2022). Inspired by this success, our research explores whether combining structured data like patient history, early test results, and vital signs can help predict ICU admission risk using machine learning. The goal is to support clinical decision-making while maintaining transparency and ethical standards.

### ❓Main Research Question
Can we accurately predict ICU admission risk at the point of hospital entry by combining a patient's medical history, vital signs, and early diagnostic test results?

## 2 Objective

To develop an interpretable and clinically relevant machine learning model that predicts the likelihood of ICU admission early in a patient’s hospital stay, using only structured data available at admission.


## 3 Methodology

- Dataset: 3,370 hospital admissions
- Target: ICU admission (3.9% positive cases)
- Features: Vital signs, diagnoses, ASA score, demographics
- Models: Logistic Regression, Decision Tree, Random Forest, Naive Bayes, XGBoost
- Techniques:
  - SMOTE to address class imbalance
  - SHAP values for interpretability
  - Stratified 5-fold cross-validation for model evaluation

## 4 Summary of Results

![image](https://github.com/user-attachments/assets/d87bac5f-308f-47eb-8394-5186ee56d83a)

## 5 Conclusion

Machine learning can provide early alerts for ICU admission risk, offering actionable insights to clinical staff. However, models must be used cautiously, as false negatives remain a risk. Transparent, interpretable models like XGBoost combined with clinical judgment offer the most ethical and effective approach. This project emphasises the potential of AI to support, not replace, healthcare professionals during critical patient admission decisions.


Link to Poster [click here](https://www.canva.com/design/DAGqm2oqlZs/ywZwCFnesbm00ApRiZl5LA/edit?utm_content=DAGqm2oqlZs&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

----------
