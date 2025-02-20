# Fake News Detection Model

This project is a machine learning model designed to detect fake news using Logistic Regression and Decision Tree Classifier, combined with a Voting Classifier for improved accuracy.

## Features

✅ Text cleaning: 
- Removes URLs, punctuation, and extra whitespaces. 
- Converts text to lowercase.
- Lemmatizes words to their root forms.

✅ Feature extraction:
- Uses Term Frequency-Inverse Document Frequency (TF-IDF) to convert text data into numerical vectors.

✅ Ensemble learning:
- Combines Logistic Regression and Decision Tree Classifier using a soft Voting Classifier.

✅ Model evaluation:
- Accuracy, precision, recall, and F1-score for performance measurement.

## Dataset

The model uses two datasets:
- **True.csv**: Contains verified real news articles.
- **Fake.csv**: Contains fake news articles.

These datasets are combined into a single dataframe, with labels: 
- `0` for real news.
- `1` for fake news.

## Installation

1️⃣ Clone the repository:
```bash
git clone <repository-url>
cd fake-news-detection
```

2️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

3️⃣ Download the dataset and place `True.csv` and `Fake.csv` in the project directory.

## Usage

✅ Run the model:
```bash
python your_file_name.py
```

✅ Evaluate performance:
- Accuracy
- Confusion Matrix
- Classification Report

✅ Make predictions:
- The model predicts whether a news article is real or fake based on the text input.

## File Structure

```
├── your_file_name.py
├── True.csv
├── Fake.csv
├── requirements.txt
├── README.md
```

## Dependencies
- Pandas
- NumPy
- Scikit-learn
- NLTK

## Results

The Voting Classifier achieved high accuracy in detecting fake news, making it reliable for real-world applications.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

---

✨ **Happy Coding!** 🚀

