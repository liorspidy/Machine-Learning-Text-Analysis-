# Gender prediction from Hebrew stories

## Description

This primary objective of this project is to build a model that can accurately predict the gender of the story author based on the content of the story using machine learnign techniques.

## Key Features

- Tokenization: The project utilizes a custom Hebrew tokenizer to extract relevant words from the text.
- TF-IDF Vectorization: Text data is transformed into numerical features using TF-IDF vectorization.
- Feature Selection: SelectKBest is used to choose the most informative features for prediction.
- PCA: Dimensionality reduction technique for improving model efficiency.
- Model Selection: Various classification models are compared and evaluated for gender prediction.
- Hyperparameter Tuning: Using GridSearchCV to find the best hyperparameters for the models.
