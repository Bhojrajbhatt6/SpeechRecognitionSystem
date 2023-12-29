# SpeechRecognitionSystem


This repository contains a Python script for building and training a simple audio command classification model. The model is implemented using the Multinomial Naive Bayes algorithm. The dataset used for training and testing consists of a small set of audio commands and their corresponding labels.

## Dataset Overview

The dataset includes the following:

- **Audio Data**: A list of audio command strings.
- **Labels**: Corresponding labels for each audio command, indicating the type of command (e.g., "greeting," "command," "farewell").

## Data Preprocessing

1. **Text Vectorization**: The audio command strings were vectorized using the CountVectorizer from scikit-learn.
2. **Label Encoding**: The categorical labels were encoded for model training.

## Model Building

The model was built using the Multinomial Naive Bayes algorithm, a commonly used algorithm for text classification tasks.

## Model Training and Testing

The model was trained on the provided audio data and labels. Test data consisting of new audio commands was used to evaluate the model's performance.

## Model Evaluation

The trained model was used to predict labels for test audio commands, and the predictions were compared with the actual labels. The accuracy of the model was calculated using the `accuracy_score` function.

## Test Data Predictions

The model made predictions on the following test audio commands:

1. **'open the window'** - Predicted Label: 'command'
2. **'play a song'** - Predicted Label: 'command'
3. **'hello there'** - Predicted Label: 'command'

## Conclusion

The audio command classification model demonstrated the ability to predict command labels for given audio inputs. Further improvements, such as expanding the dataset and exploring advanced machine learning models, could enhance the accuracy of the model.


