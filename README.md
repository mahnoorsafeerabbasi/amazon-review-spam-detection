# amazon-review-spam-detection
"Amazon Review Recommendation System is a project that utilizes machine learning techniques to build a recommendation system for Amazon product reviews. The system includes features such as preprocessing, spam detection, and a recommendation function.
To replicate the project, please note that it requires the usage of your Kaggle API username and key to directly download the dataset from https://www.kaggle.com/datasets/smriti21/amazonreviews. The project leverages natural language processing and classification algorithms to assist users in making informed decisions based on the analysis of Amazon product reviews

the steps include:
Installs the Kaggle library using pip.
Sets the Kaggle API credentials (username and key).
Specifies the details of the dataset to be downloaded from Kaggle.
Creates a directory to save the dataset and downloads it using the Kaggle API.
Lists the files and directories within the dataset path.
Loads the dataset from a CSV file.
Preprocesses the loaded dataset by applying text preprocessing techniques such as removing punctuation, tokenization, stop word removal, and lemmatization.
Drops rows with missing values in the 'NOT VERIFIED' column.
Splits the preprocessed dataset into training and testing sets.
Vectorizes the preprocessed text data using the CountVectorizer.
Trains a logistic regression model on the vectorized training data.
Evaluates the trained model by calculating its accuracy on the testing data.
Installs the PyCaret library using pip.
Initializes a PyCaret experiment using the preprocessed dataset.
Compares different machine learning models using PyCaret's compare_models function.
Generates a confusion matrix to evaluate the performance of the best model.
Trains another logistic regression model on the entire preprocessed dataset.
Defines a recommendation function that predicts whether a given review is trustworthy or potentially spam based on the trained model.
Provides an example usage of the recommendation function by passing a review and obtaining the corresponding recommendation.
