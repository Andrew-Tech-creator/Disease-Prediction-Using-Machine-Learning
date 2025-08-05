🧠 Disease Prediction Using Machine Learning

This repository contains a Machine Learning-based Disease Prediction system. It predicts the most likely disease a person might be suffering from, based on input symptoms.

📌 Features

* Predicts diseases using supervised machine learning classifiers.
* Takes multiple symptoms as input.
* Trained on a labeled dataset with 132 symptoms and 41 diseases.
* Uses three algorithms for better prediction:

  * Decision Tree Classifier
  * Random Forest Classifier
  * Naive Bayes Classifier
* Accuracy comparison among the models.

 📂 Repository Structure

```
├── dataset.csv                  # Main dataset with symptoms and diseases
├── Training.csv                # Training data used for model training
├── Testing.csv                 # Test data used for evaluation
├── disease_prediction.py       # Core script to train and test ML models
├── model_decision_tree.pkl     # Pickled Decision Tree model
├── model_random_forest.pkl     # Pickled Random Forest model
├── model_naive_bayes.pkl       # Pickled Naive Bayes model
├── requirements.txt            # List of dependencies
└── README.md                   # This readme file
```

---

 🚀 How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/Andrew-Tech-creator/disease-prediction-ml.git
   cd disease-prediction-ml
   ```

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

3. Run the script

   ```bash
   python disease_prediction.py
   ```

---

 🧪 Sample Input (via Script)

```python
symptoms = ['itching', 'skin_rash', 'nodal_skin_eruptions', 'dischromic _patches']
```

---

✅ Output

```
Predicted Disease (Decision Tree): Fungal infection
Predicted Disease (Random Forest): Fungal infection
Predicted Disease (Naive Bayes): Fungal infection
```

---

 📊 Model Accuracy (Example)

| Algorithm     | Accuracy |
| ------------- | -------- |
| Decision Tree | 95.83%   |
| Random Forest | 100.00%  |
| Naive Bayes   | 91.67%   |

---

 📚 Dataset Source

The dataset is derived from various online medical databases and curated for the GeeksforGeeks article.

---

 🛠 Requirements

* Python 3.6+
* scikit-learn
* pandas
* numpy
* joblib

Check `requirements.txt` for full list.

---

 🤝 Contributing

Pull requests are welcome. Feel free to open issues for suggestions or bug reports.

---

 📄 License

This project is open-source and available under the [MIT License](LICENSE).


✍️ Author
Modified and maintained by \[Andrew Michael Anthony].

