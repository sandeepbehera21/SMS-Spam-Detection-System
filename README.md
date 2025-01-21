# SMS Spam Detection

## 🌟 Overview

The **SMS Spam Detection** project leverages machine learning to identify whether a given SMS is spam or not. Built with Python and deployed using Streamlit, this tool provides an intuitive interface for seamless usage.

---

## 🚀 Technology Stack

- **Programming Language**: Python
- **Libraries**:
  - Scikit-learn
  - Pandas
  - NumPy
  - Streamlit

---

## ✨ Features

1. **Data Collection**

   - Gathered from the [SMS Spam Collection dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) on Kaggle, comprising over 5,500 labeled SMS messages.

2. **Data Cleaning and Preprocessing**

   - Removal of null and duplicate values.
   - Label encoding of the "type" column.
   - Text processing:
     - Tokenization
     - Removal of special characters, stop words, and punctuation
     - Stemming
     - Conversion to lowercase

3. **Exploratory Data Analysis (EDA)**

   - Insights include:
     - Character, word, and sentence counts.
     - Correlation analysis.
   - Visualizations:
     - Bar and pie charts
     - Heatmaps
     - Word clouds for spam and non-spam messages
     - Frequent word analysis for spam messages

4. **Model Building and Selection**

   - Tested classifiers: Naive Bayes, Random Forest, KNN, Decision Tree, Logistic Regression, Extra Trees Classifier, and SVC.
   - Achieved 100% precision with the best-performing model.

5. **Web Deployment**
   - Deployed via Streamlit with a clean, user-friendly interface.
   - Users can input an SMS message and receive predictions instantly.

---

---

## 📖 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/sandeepbehera21/sms-spam-detection.git
   ```
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   streamlit run app.py
   ```
4. Open your browser and visit:
   ```
   http://localhost:8501
   ```

---

## 🤝 Contributions

We welcome contributions to improve this project! Feel free to:

- Open issues for bugs or feature requests.
- Submit pull requests with enhancements.

---

## 🛠 Future Enhancements

- **Enhanced Model Performance**: Experiment with additional algorithms for improved accuracy.
- **Multilingual Support**: Extend detection to support messages in multiple languages.
- **Mobile-Friendly UI**: Optimize the Streamlit interface for mobile users.

---

Thank you for checking out the SMS Spam Detection project! 🎉
