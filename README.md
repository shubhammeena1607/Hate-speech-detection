# 🛡️ Hate Speech Detection

This project demonstrates a machine learning pipeline to detect hate speech in text data using Python and Jupyter Notebook. It includes data preprocessing, feature extraction, model training, and evaluation—all aimed at identifying and classifying hateful or offensive language in social media content.

## 📁 Project Structure

├── hate speech detection.ipynb # Main notebook with code and analysis.
├── clean_dataset.csv # Cleaned dataset (CSV format).
├── clean_dataset.xlsx # Cleaned dataset (Excel format).


## 🎯 Objective

The goal is to build a supervised learning model that can classify text as:
- **Hate Speech**
- **Offensive Language**
- **Neither**

This helps in moderating online platforms and promoting safer digital spaces.

## 🧠 Techniques Used

- **Data Cleaning**: Removing noise, special characters, and stopwords
- **Text Vectorization**: Using TF-IDF for feature extraction
- **Modeling**: Logistic Regression (can be extended to SVM, Random Forest, etc.)
- **Evaluation**: Accuracy, Precision, Recall, F1-Score

## 📊 Dataset

The dataset contains labeled tweets with three categories:
- `0` → Hate Speech
- `1` → Offensive Language
- `2` → Neither

It has been cleaned and saved in both `.csv` and `.xlsx` formats for easy access.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/shubhammeena1607/Hate-speech-detection.git
   cd Hate-speech-detection
2. Open the notebook:
  jupyter notebook "hate speech detection.ipynb"

3. Run each cell step-by-step to explore the full pipeline.

📌 Future Improvements
  Integrate deep learning models like LSTM or BERT.
  Deploy as a web app using Streamlit or Flask.
  Add real-time tweet classification via Twitter API.

## 🧾 License
This project is open-source and available under the MIT License.


Let me know if you'd like a version tailored for recruiters or portfolio viewers—something that emphasizes your impact and skills more directly!






