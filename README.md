# 📚 Classify Book Genres Using Metadata

This project aims to classify books into genres based on metadata such as **author**, **length**, and **keywords**. The goal is to build a machine learning model that can predict a book's genre with high accuracy using minimal but meaningful data.

---

## 🔍 Problem Statement

Genre classification is essential for organizing books in digital libraries, recommending content to readers, and improving user experience. Traditional classification relies on manual tagging, which can be inconsistent and time-consuming. This project uses machine learning to automate genre classification based on structured metadata.

---

## 📦 Features Used

- **Author**: Known associations with specific genres.
- **Length**: Total page count or word count.
- **Keywords**: Extracted from summaries, titles, or descriptions.

---

## 🧠 Methodology

1. **Data Collection**  
   Gathered metadata from open-source datasets like Project Gutenberg and scraped summaries, lengths, and authors from public sources.

2. **Preprocessing**  
   - Cleaned and standardized metadata.
   - Converted text data (e.g., keywords) into numerical form using TF-IDF.

3. **Feature Engineering**
   - One-hot encoding for categorical data like authors.
   - Normalization for length.
   - Vectorization for keyword data.

4. **Model Training**
   - Applied supervised machine learning models such as:
     - Random Forest
     - Support Vector Machine (SVM)
     - Logistic Regression

5. **Evaluation**
   - Used accuracy, precision, recall, and F1-score to assess performance.
   - Performed cross-validation for reliability.

---

## 🧰 Tech Stack

- Python 3.x  
- Pandas  
- Scikit-learn  
- NLTK / SpaCy (for keyword extraction)  
- Jupyter Notebook

---

## 📁 Project Structure

