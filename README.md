# Spam Filter using Naive Bayes Classifier

This project implements a spam filter using the Naive Bayes classifier. The classifier is trained on a dataset containing spam and ham (non-spam) messages. The model is then used to classify new messages as spam or ham.

## Getting Started

To get started with the project, you can follow these steps:

1. Clone the repository.
2. Install the required packages mentioned in the `requirements.txt` file.
3. Run the `spam_filter.py` script.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn

## Usage

You can run the `spam_filter.py` script to train the model and test it with new messages. The script performs the following tasks:
- Imports necessary packages.
- Reads the dataset containing spam and ham messages.
- Preprocesses the data and creates a feature matrix using CountVectorizer.
- Splits the data into training and testing sets.
- Trains a Multinomial Naive Bayes model.
- Tests the model's accuracy and performance.
- Classifies user-provided emails as spam or ham.

## License

This project is licensed under the [MIT License](LICENSE).
