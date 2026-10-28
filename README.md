# Amazon Product Review Sentiment Analysis

## Project Overview
This project analyzes Amazon product reviews and classifies customer opinions into three sentiment categories: Positive, Neutral, and Negative.

The project was developed as part of the **OASIS INFOBYTE Data Analytics Internship** using Python, Natural Language Processing (NLP), and Machine Learning techniques.

## Objectives
- Analyze customer reviews and understand their sentiment.
- Inspect and clean messy review data.
- Preprocess text for machine learning.
- Convert review text into numerical features using TF-IDF.
- Train and compare machine learning classification models.
- Evaluate model performance using suitable metrics.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- Jupyter Notebook

## Dataset
The project uses an Amazon product reviews dataset.

The selected dataset contains customer review text, product information, and ratings. Data quality checks were performed to identify missing values and duplicate records.

*Note: The dataset is not included in this repository unless its sharing license and permissions allow redistribution.*

## Project Workflow
1. Import the required Python libraries.
2. Load and inspect the dataset.
3. Analyze missing values, duplicate records, and rating distributions.
4. Create sentiment labels based on review ratings:
   - **Negative:** Ratings 1–2
   - **Neutral:** Rating 3
   - **Positive:** Ratings 4–5
5. Remove duplicate records and handle missing values in important columns.
6. Standardize and preprocess review text.
7. Convert text into numerical features using TF-IDF.
8. Train Multinomial Naive Bayes and Logistic Regression models.
9. Compare model performance using accuracy, precision, recall, F1-score, and confusion matrices.
10. Save the cleaned dataset and model comparison results.

## Machine Learning Models
### 1. Multinomial Naive Bayes
A classification algorithm commonly used for text classification tasks.

### 2. Logistic Regression
A supervised machine learning algorithm used to classify reviews into sentiment categories.

The models are compared using evaluation metrics to understand their performance.

## Sentiment Classification
| Rating | Sentiment |
|---|---|
| 1–2 stars | Negative |
| 3 stars | Neutral |
| 4–5 stars | Positive |

## Evaluation Metrics
- **Accuracy:** Overall proportion of correct predictions.
- **Precision:** How often predicted sentiment labels are correct.
- **Recall:** How many actual examples of a sentiment are identified.
- **F1-score:** Combined measure of precision and recall.
- **Confusion Matrix:** Shows correct and incorrect classifications across sentiment categories.

The dataset contains more positive reviews than negative and neutral reviews, so class-wise evaluation is important.

## Project Files
- `sentiment_analysis.ipynb` — Notebook containing data inspection, preprocessing, model training, and evaluation.
- `outputs/model_comparison.csv` — Comparison of model evaluation metrics.
- `outputs/cleaned_sentiment_reviews.csv` — Cleaned review dataset with sentiment labels, if generated and included.

*Update the filenames above if your actual repository structure differs.*

## How to Run
1. Clone or download this repository.
2. Install the required dependencies:

   ```bash
   python -m pip install pandas numpy matplotlib seaborn scikit-learn nltk jupyter
   ```

3. Open the project notebook in Jupyter Notebook or VS Code.
4. Ensure the dataset is available at the file path used in the notebook.
5. Run the notebook cells in order.

## Key Learning Outcomes
- Data quality analysis and cleaning
- Text preprocessing using NLP techniques
- TF-IDF feature extraction
- Machine learning model training
- Classification evaluation and comparison
- Data visualization and insight communication

## Internship
**OASIS INFOBYTE — Data Analytics Internship**

## Author
shivanktiwari979-cpu
