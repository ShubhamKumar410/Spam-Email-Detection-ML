# Spam Email Detection using Machine Learning

## Project Overview
This project uses Machine Learning to classify emails as **Spam** or **Ham (Not Spam)**. It applies Natural Language Processing (NLP) techniques to convert text data into numerical features and uses Logistic Regression for classification.

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Jupyter Notebook

## Project Workflow
1. Load and understand the email dataset.
2. Perform data preprocessing.
3. Separate email messages and labels.
4. Split the dataset into training and testing sets.
5. Convert text messages into numerical features using TF-IDF.
6. Train a Logistic Regression model.
7. Evaluate model performance using accuracy score.
8. Predict whether an email is Spam or Ham.

## Project Structure
```text
MailPrediction_Project/
│
├── mail_data.csv
├── Spam Mail Prediction using ML.ipynb
├── requirements.txt
└── README.md
```

## Installation and Setup

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Navigate to the project directory:

```bash
cd MailPrediction_Project
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch the notebook in VS Code or Jupyter Notebook and run the cells.

## Model
Logistic Regression is used for spam email classification, with TF-IDF for text feature extraction.

## Author
Shubham Kumar

## License
This project is available for educational purposes.
