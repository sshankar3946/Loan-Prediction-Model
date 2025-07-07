**Loan Approval Prediction Project**

A classification project that predicts loan approval using applicant data such as income, employment status, credit history, and more. The objective is to simulate real-world enterprise risk modeling using Python.

---

## 📌 Project Objectives

- Build a predictive model to classify whether a loan will be approved (Y/N)
- Perform exploratory data analysis (EDA) to uncover data patterns
- Handle missing values and perform feature engineering
- Implement classification using **Support Vector Machine (SVM)**
- Evaluate model performance using accuracy matrix

---

## 🧠 Tools & Libraries Used

- **Python**: pandas, NumPy, matplotlib, seaborn, scikit-learn

---

## 📊 Key Features of the Project

- **Stratified data split** to preserve target class distribution
- **SVM model** trained on cleaned, encoded features

---

## 📁 Project Structure


│
├── Dataset.csv                # Raw dataset
├── Loan_Prediction.ipynb      # Jupyter notebook with full project
├── README.md                  # Project overview


##  Sample Prediction Code

input_data = (1,1,4,1,0,3036,2504.0,158.0,360.0,0.0,1,4.852030,6091.0,8.714568)
input_data_nmpy = np.asarray(input_data)
inpdat_reshape = input_data_nmpy.reshape(1,-1)
prediction = classifier.predict(inpdat_reshape)

##  Model Performance

•	Classifier: Support Vector Machine (linear kernel)
•	Test Accuracy: ~75–80% depending on split
•	Balanced recall with stratified split

Please feel free to explore!
