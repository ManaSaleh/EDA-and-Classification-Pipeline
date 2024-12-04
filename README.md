# **EDA and Classification Pipeline**

This repository contains a structured pipeline for Exploratory Data Analysis (EDA), data preprocessing, feature encoding, scaling/normalization, and building classification models using Logistic Regression, SVM, and KNN. The repository is designed for binary classification tasks and is adaptable to various datasets.

---

## **Repository Structure**

```
.
├── Data
│   ├── raw.csv                       # Original dataset
│   ├── scaled_data.csv               # Scaled dataset
│   └── scaled_data_with_log_sqrt.csv # Scaled dataset with log and sqrt transformations
├── DataforAlgorithms.ipynb           # Notebook for preparing data tailored for algorithms
├── EDA-ML.ipynb                      # Notebook for exploratory data analysis (EDA)
├── EncodeData.ipynb                  # Notebook for encoding categorical variables
├── Models.ipynb                      # Notebook for building classification models
└── ScaleorNormalizeData.ipynb        # Notebook for scaling and normalizing features
```

---

## **Features**

1. **EDA**:
   - Explore datasets to identify missing values, duplicates, and outliers.
   - Analyze distributions, correlations, and skewness.
   - Visualize target variable balance using charts.

2. **Data Preprocessing**:
   - Encode categorical variables with **Binary Encoding** and **One-Hot Encoding**.
   - Handle multicollinearity using **Variance Inflation Factor (VIF)**.

3. **Scaling and Normalization**:
   - Apply **MinMaxScaler** for feature scaling.
   - Perform **logarithmic** and **square root transformations** for skewed features.

4. **Classification Models**:
   - Implement **Logistic Regression**, **SVM**, and **KNN**.
   - Evaluate models using **accuracy**, **classification reports**, and **confusion matrices**.

5. **Adaptability**:
   - Easily modify the pipeline to handle different datasets or add new models.

---

## **How to Use**

### **1. Clone the Repository**
```bash
git clone https://github.com/ManaSaleh/EDA-and-Classification-Pipeline.git
cd EDA-and-Classification-Pipeline
```


### **2. Run the Notebooks**
- Use Jupyter Notebook or Jupyter Lab to run the `.ipynb` files.
- Start with **EDA-ML.ipynb** to explore the dataset.
- Follow up with other notebooks in sequence:
  - `EncodeData.ipynb`
  - `ScaleorNormalizeData.ipynb`
  - `DataforAlgorithms.ipynb`
  - `Models.ipynb`

---

## **Key Notebooks**

1. **EDA-ML.ipynb**:
   - Analyze the dataset, detect missing values and outliers, and visualize feature distributions.

2. **EncodeData.ipynb**:
   - Transform categorical variables using binary and one-hot encoding.

3. **ScaleorNormalizeData.ipynb**:
   - Scale and normalize features to ensure compatibility with ML models.

4. **Models.ipynb**:
   - Train and evaluate classification models (Logistic Regression, SVM, and KNN).
   - Compare model performance using metrics and visualizations.

5. **DataforAlgorithms.ipynb**:
   - Prepares the dataset tailored for various ML algorithms.

---

## **Example Workflow**
1. Load and explore the dataset using `EDA-ML.ipynb`.
2. Encode categorical variables using `EncodeData.ipynb`.
3. Scale or normalize features in `ScaleorNormalizeData.ipynb`.
4. Train and evaluate models in `Models.ipynb`.

---

## **Data**
- **`raw.csv`**: The original dataset.
- **`scaled_data.csv`**: The dataset after scaling.
- **`scaled_data_with_log_sqrt.csv`**: The scaled dataset with logarithmic and square root transformations applied.

---


## **Acknowledgements**
- [Scikit-learn Documentation](https://scikit-learn.org/)
---
