# netflix-data-analysis
# Netflix Data Analysis & Machine Learning 📊🎬

## 📌 Objective

The goal of this project is to analyze the Netflix Movies and TV Shows dataset and build a machine learning model to classify content as either a Movie or a TV Show.

---

## 📂 Dataset

* Source: Kaggle
* Dataset: Netflix Movies and TV Shows
* Contains information such as title, director, cast, country, release year, rating, and more.

---

## 🧹 Data Cleaning

* Handled missing values in columns like `director`, `cast`, `country`, and `rating`
* Converted `date_added` to datetime format
* Extracted a new feature: `year_added`

---

## 📊 Exploratory Data Analysis (EDA)

### Key Insights

* Movies dominate Netflix content compared to TV Shows
* United States and India are the top content-producing countries
* Significant growth in content after 2015
* Most content is targeted towards mature audiences (TV-MA, TV-14)
* Documentaries and Stand-Up Comedy are among the most common genres

---

## 🤖 Machine Learning

### Models Used

* Logistic Regression
* Decision Tree Classifier

### Features Used

* `release_year`
* `rating`
* `year_added`

---

## 📈 Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 67.4%    |
| Decision Tree       | 70.8%    |

---

## 📋 Model Evaluation

### Logistic Regression

* High recall for Movies
* Poor performance for TV Shows
* Biased towards predicting Movies

### Decision Tree

* Better balance between classes
* Improved detection of TV Shows
* Overall better performance

---

## 🔍 Evaluation Metrics

* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)

---

## 🧠 Conclusion

* Netflix content has grown rapidly, especially after 2015
* Movies dominate the platform’s content
* Decision Tree performed better than Logistic Regression
* Model performance can be improved with better feature engineering

---

## 🚀 Future Improvements

* Use additional features like genre and country
* Perform hyperparameter tuning
* Try advanced models like Random Forest
* Apply NLP techniques on descriptions

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* Matplotlib
* Scikit-learn

---

## 📌 Project Status

✅ Completed (Data Analysis + Machine Learning)

---

## 👩‍💻 Author

Chandana Kukudala
Aspiring Data Scientist
