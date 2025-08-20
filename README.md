“Predictive Modelling of Digital Literacy 


 📊 Predictive Modelling of Digital Literacy Using Machine Learning

 Project Overview

This project focuses on predicting digital literacy status among individuals using Machine Learning techniques.
Digital literacy is an essential skill in today’s digital-first world, yet many demographic and socioeconomic factors influence whether people are digitally literate or not.

Using a structured dataset (demographics, education, income, internet access, etc.), this project applies classification algorithms to determine whether an individual is digitally literate.

✅ Best Model: Support Vector Machine (SVM) with 86% accuracy
✅ Applications: Educational planning, policy-making, digital inclusion programs

---



 Dataset

* Attributes:

  * Gender, Age, Education Level, Occupation, Income Level, Internet Access
  * Target Variable:Digital Literacy (1 = Literate, 0 = Not Literate)
* Data cleaning included handling missing values, duplicates, outliers, and categorical encoding.



Methodology

1. Data Preprocessing

* Missing value imputation
* Outlier detection (IQR method, Boxplots)
* Encoding categorical variables (One-Hot & Label Encoding)
* Normalization & Standardization

 2. Machine Learning Models

* Logistic Regression
* Random Forest Classifier
* Support Vector Machine (SVM)

 3. **Evaluation Metrics**

* Accuracy
* Precision, Recall, F1-Score
* Confusion Matrix
* ROC Curve & AUC

---

Results

| Model               | Accuracy | Precision | Recall    | F1-Score |
| ------------------- | -------- | --------- | --------- | -------- |
| Logistic Regression | 69%      | 0.68–0.70 | 0.68–0.70 | 0.69     |
| Random Forest       | 85%      | 0.84–0.86 | 0.84–0.86 | 0.85     |
| SVM (best model)    | **86%**  | 0.80–0.96 | 0.75–0.97 | 0.86     |

Final Model Chosen:Support Vector Machine (SVM)


 Tech Stack
Programming Language:Python
Libraries:Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Tools:Jupyter Notebook, GitHub, Power BI (for visualization, optional)



 How to Run

1. Clone the repo:

   bash
   git clone https://github.com/yourusername/digital-literacy-ml.git
   cd digital-literacy-ml
   

2. Install dependencies:

   bash
   pip install -r requirements.txt
   

3. Run Jupyter Notebook for model training:

   bash
   jupyter notebook notebooks/Digital_Literacy.ipynb
  



 Applications

 Identifying communities with low digital literacy
 Supporting **government & NGOs** for targeted digital literacy programs
 Assisting **educational institutions** to bridge the digital divide
 data-driven **policy-making**



References

 Hargittai, E. (2002). Second-level digital divide. [First Monday](https://firstmonday.org/ojs/index.php/fm/article/view/942)
 UNESCO (2018). [Digital Literacy Skills Framework](https://unesdoc.unesco.org/ark:/48223/pf0000265403)
 OECD (2019). [Measuring the Digital Transformation](https://doi.org/10.1787/9789264311992-en)


Author

Sarthak R Shetty
📌 MSc Big Data Analytics | St. Aloysius (Deemed to be University), Mangaluru
🔗 [LinkedIn Profile]www.linkedin.com/in/sarthak-r-shetty22
📧 Email: sarthakrshetty36@gmail.com


