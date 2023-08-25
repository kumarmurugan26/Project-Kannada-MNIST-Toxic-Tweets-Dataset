# Toxic Tweets Classification using NLP

This project involves using Natural Language Processing (NLP) techniques to classify tweets as toxic or non-toxic. The dataset used in this project contains labeled tweets, with toxicity labeled as 1 and non-toxicity labeled as 0.

## Dataset

Dataset: [Toxic Tweets Dataset](https://www.kaggle.com/datasets/ashwiniyer176/toxic-tweets-dataset)

All credits to the original collectors for providing this dataset.

## Project Steps

1. **Data Preparation**: The CSV file containing the tweets was converted into a pandas DataFrame for ease of manipulation.

2. **Text Representation**:
   - Bag of Words: The tweets were transformed into bag of words representation.
   - TF-IDF: The Term Frequency-Inverse Document Frequency representation was used to convert the text into numerical features.

3. **Models Used**:
   - Decision Trees
   - Random Forest
   - Naive Bayes Model
   - K-NN Classifier
   - Support Vector Machine (SVM)

4. **Evaluation Metrics**:
   For each model and text representation method, the following metrics were calculated:
   - Precision, Recall, F1-Score
   - Confusion Matrix
   - ROC-AUC Curve

## Results

The project's results provide insights into the effectiveness of different models and text representation methods in classifying toxic tweets. This aids in understanding which combination of model and representation works best for this task.



## Conclusion

This project showcases the application of NLP techniques for the classification of toxic and non-toxic tweets. By comparing the performance of different models and text representation methods, valuable insights are gained into the strengths and weaknesses of each approach.

## References

- Dataset: [Toxic Tweets Dataset](https://www.kaggle.com/datasets/ashwiniyer176/toxic-tweets-dataset)

