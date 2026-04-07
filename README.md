# 🧠 ML Projects Repository

A collection of machine learning projects built to explore different problem types, algorithms, and workflows — ranging from basic regression to more advanced classification and custom metric-based systems.

---

## 📁 Repository Structure

Each project follows a consistent and scalable structure:

```
Project_Name/
│
├── Data_Viz_Data/                 # Data Visualization Data and EDAs 
├── Model_Source_Code/             # Jupyter notebooks & Dataset files
│   ├── electricity_data.csv
|   ├── initial.ipynb      # Experimental / testing notebook
│   └── model_.ipynb       # Finalized model implementation
└── README.md              # Project-specific documentation
```

---

## 🔁 Workflow Strategy

Each project follows a structured development pipeline:

### 🧪 `initial.ipynb`

* Used for experimentation and testing
* Feature engineering, EDA, trying different models
* Safe space for breaking things and iterating

### ✅ `model_.ipynb`

* Clean, finalized version of the model
* Only stable and verified logic is included
* Represents the “production-ready” notebook

> Any new idea or modification is first tested in `initial.ipynb`, and once validated, transferred to `model_.ipynb`.
#### Note: Underscore in `model_.ipynb` represents respective model folders.

### 💾 Datsets

* Each project includes a sample dataset (100–200 rows) to allow quick setup and testing without heavy downloads.
* Due to the large size of full datasets, they are not stored in this repository.
Instead, Kaggle dataset links are provided in each model’s README for easy access.
* This approach ensures:
  * ⚡ Fast cloning of the repository
  * 🧪 Easy experimentation with sample data
  * 📦 Access to complete datasets when needed
---

## 📊 Projects Included

* ⚡ Electricity Consumption Prediction
* ⚡ CPU Temperature Prediction
* 📖 Student Marks Prediction

---

## 🧠 Skills & Concepts Covered

* Regression & Classification
* Feature Engineering
* Data Visualization (EDA)
* Model Evaluation Metrics
* Handling Different Dataset Types
* Iterative Model Development

---

## 🚀 Future Improvements

* Add advanced models (ensemble, boosting, etc.)
* Hyperparameter tuning
* Model deployment (Flask / API)
* Performance comparison across models
* Centralized experiment tracking

---

## ⚙️ Tools & Libraries

* Python
* NumPy, Pandas
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📌 Note

This repository is built with a strong focus on:

* Structured experimentation
* Clean separation between testing and final models
* Consistency across projects
* Kaggle knowledge

---

## 👨‍💻 Author

Hardik Basu

---
