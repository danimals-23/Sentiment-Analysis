# Sentiment-Analysis
Personal sentiment analysis project based on a project that was done in class, in which we used a naive bayes classifier trained on 400000 movie reviews, each classified as 1 (positive sentiment) and 0 (negative sentiment).

## Testing Results
Below are testing results which we observed from the naive bayes classifier.

Accuracy: 0.857875

### Confusion Matrix: 
| <!-- -->    | <!-- -->    |
|-------------|-------------|
| 3497 |  469 |
|  668 | 3366 |

### Classification Report:
|            |   precision  |  recall | f1-score  | support |
| ---------- | ------------ | ------- | --------- | ------- |
|          0 |      0.84    |  0.88   |   0.86    |  3966   |
|          1 |      0.88    |  0.83   |   0.86    |  4034   |
|   accuracy |              |         |   0.86    |  8000   |
|  macro avg |      0.86    |  0.86   |   0.86    |  8000   |
| weighted avg |      0.86  |    0.86 |     0.86  |  8000   |
