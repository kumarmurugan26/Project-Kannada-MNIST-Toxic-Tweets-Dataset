# Kannada MNIST Classification Project

This project involves the classification of Kannada digits using various machine learning models. Instead of using Hindu numerals, we used the recently-released Kannada digits dataset, which is a 10-class classification problem. Kannada is a language spoken predominantly in Karnataka, India.

## Problem Statement

The goal of this project was to classify Kannada digits using different machine learning algorithms and evaluate their performance metrics.

Dataset: [Kannada MNIST Dataset](https://www.kaggle.com/datasets/higgstachyon/kannada-mnist)

Dataset Details: [Prabhu, Vinay Uday. "Kannada-MNIST: A new handwritten digits dataset for the Kannada language."](https://arxiv.org/abs/1908.01242)

## Project Steps

1. **Data Preprocessing**: The dataset contains 60,000 training images and 10,000 test images, each of size 28x28. The images were processed and PCA was applied to reduce the dimensions to 10 components.

2. **Models Used**:
   - Decision Trees
   - Random Forest
   - Naive Bayes Model
   - K-NN Classifier
   - Support Vector Machine (SVM)

3. **Evaluation Metrics**:
   For each model, the following metrics were calculated:
   - Precision, Recall, F1-Score
   - Confusion Matrix
   - ROC-AUC Curve

4. **Experimenting with Different Component Sizes**:
   The experiment was repeated with different PCA component sizes: 15, 20, 25, and 30. This helps to observe how changing the component size affects the performance of the models.

## Results

The results of the experiments indicated the performance of each model under different PCA component sizes. These results provide insights into how the models perform with varying levels of dimensionality reduction.



## Conclusion

This project demonstrates the process of classifying Kannada digits using various machine learning models. It also showcases the impact of dimensionality reduction using PCA on the performance of these models. The results obtained can be used to select the best model for this specific task and to determine the optimal dimensionality reduction technique.

## References

- Dataset: [Kannada MNIST Dataset](https://www.kaggle.com/datasets/higgstachyon/kannada-mnist)
- Paper: [Prabhu, Vinay Uday. "Kannada-MNIST: A new handwritten digits dataset for the Kannada language."](https://arxiv.org/abs/1908.01242)


