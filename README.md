# Prodigy_DS_04
# Twitter Sentiment Analysis Project

## Overview
This project performs sentiment analysis on a dataset of 1.6 million tweets to classify sentiments as positive or negative. The analysis combines **VADER sentiment analysis** for lexicon-based classification and a **Logistic Regression model** for machine learning-based sentiment prediction.

## Project Motivation
Understanding public sentiment is critical for businesses and policymakers. By analyzing large-scale Twitter data, this project aims to:
- Extract meaningful insights from tweet sentiments
- Visualize sentiment distributions to identify patterns
- Compare lexicon-based and machine learning-based sentiment classification

## Dataset
- **Source**: [Kaggle](https://www.kaggle.com/datasets)
- **Content**: Tweets without emojis, labeled as 0 (negative) or 4 (positive)
- **Preprocessing**: The dataset was simplified by changing 4 to 1 for binary classification and retaining only the `text` and `target` columns.

## Key Results
The project successfully implemented both lexicon-based and machine learning-based sentiment classification. Visualization of sentiment distributions highlighted the balance of positive and negative tweets, and the logistic regression model achieved good classification performance.

## Usage
1. **Install Dependencies**:
   Ensure all libraries are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn nltk scikit-learn
   ```

2. **Run the Code**:
   - Clone the repository.
   - Load the dataset and execute the code in a Jupyter Notebook or Python environment.

3. **VADER Lexicon Download**:
   - If running the VADER sentiment analyzer, download the VADER lexicon:
   ```python
   import nltk
   nltk.download('vader_lexicon')
   ```

## Future Work
- Experiment with more advanced models like **Random Forest** or **SVM**.
- Use other vectorization techniques (e.g., TF-IDF) for improved feature extraction.
- Integrate deep learning models like **LSTM** for further accuracy improvements.


## License
This project is open-source and available under the MIT License.

---

This README provides a thorough explanation of the project, making it easy for others to understand, replicate, or contribute. You can add any links to your code or additional resources if needed.
