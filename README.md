# Sentiment Analysis of Amazon Product Reviews 🛍️📊

This project applies Natural Language Processing (NLP) and Machine Learning techniques to analyze the sentiment of Amazon product reviews. The goal is to classify reviews as positive, negative, or neutral to gain insights into customer feedback.

## 📌 Features

- Preprocessing of text data using NLTK
- Data visualization for review insights
- Machine learning model training and evaluation
- Sentiment classification (Positive / Negative)
- Use of algorithms such as Logistic Regression and Naive Bayes

## 📂 Project Structure

```
Sentimental-Analysis-of-Amazon-Product-Reviews/
├── Dataset/
│   └── Reviews.csv
├── Images/
│   └── sentiment_dist.png
├── Final.ipynb
├── requirements.txt
└── README.md
```

## 📊 Dataset

The dataset contains Amazon product reviews along with metadata like ratings and review texts. It is stored in `Dataset/Reviews.csv`.

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/MordrogX/Sentimental-Analysis-of-Amazon-Product-Reviews.git
cd Sentimental-Analysis-of-Amazon-Product-Reviews
```

2. Create and activate a virtual environment (optional but recommended):

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## 🧪 Usage

Open the `Final.ipynb` notebook using Jupyter:

```bash
jupyter notebook Final.ipynb
```

Follow the notebook steps to load data, preprocess it, visualize sentiments, and train models.

## 📈 Results

- Accuracy achieved: ~85-90% depending on the model
- Visual representation of sentiment distribution
- Word clouds and bar plots for better understanding

## 📷 Sample Output

### Sentiment Distribution

<img width="964" height="572" alt="image" src="https://github.com/user-attachments/assets/f85c7498-3086-440b-8914-1aae16aeb214" />

## 📚 Technologies Used

- Python
- NLTK
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

## 🧠 Models Used

- Logistic Regression
- Naive Bayes
- (Optional: You can expand to include SVM, Random Forest)

## 📄 License

This project is licensed under the MIT License.
