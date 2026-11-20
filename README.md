
# Iris Flower Classification 🌸

Project completed as part of the **CodeAlpha Data Science Internship**.

## 🎯 Objective
Classify Iris flowers (setosa, versicolor, virginica) using four measurements:
sepal length, sepal width, petal length, and petal width.

## 📊 Dataset
- **150 flowers**
- **4 features**
- **3 balanced species** (50 samples each)
- **No missing values**

## ⚙️ Methodology
1. Exploratory data analysis and visualization.
2. Split the dataset into 80% training and 20% testing, followed by normalization.
3. Trained 5 models: Logistic Regression, KNN, Decision Tree, Random Forest, and SVM.
4. Evaluation using accuracy, confusion matrix, classification report, and cross-validation.
5. Model comparison and hyperparameter tuning using GridSearchCV.
6. Testing on new measurements.

## 📈 Results

| Model | Test Accuracy | CV Mean | CV Standard Deviation |
|---|---|---|---|
| KNN | 93.33% | 97.33% | 2.49 |
| SVM | 96.67% | 96.00% | 3.89 |
| Decision Tree | 93.33% | 95.33% | 3.40 |
| Logistic Regression | 93.33% | 95.33% | 4.52 |
| Random Forest | 90.00% | 94.67% | 2.67 |

**Selected model: KNN**, based on its highest cross-validation mean score and best stability.

**Most important features:** [Your 2 features].

## ⚠️ Limitations
- Small dataset: the test set contains only 30 flowers, so a single misclassification changes the accuracy by 3.33 percentage points.
- Differences between models are of the same order of magnitude as the variation across folds, meaning the models are generally comparable.

## 💻 Installation

```bash
git clone https://github.com/[your-username]/CodeAlpha_IrisFlowerClassification.git
cd CodeAlpha_IrisFlowerClassification
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

Then open `Iris_Classification.ipynb` and run all cells.

## 🛠️ Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 👩‍💻 Author
[Your Name] | [Your LinkedIn Profile](your-linkedin-url)
