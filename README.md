#  Logistic Regression for Credit Risk Classification

## Objective:

Our goal is to create a reliable model that accurately distinguishes between 'healthy loans' and 'high-risk loans' based on application details like loan size, interest rate, borrower income, and other factors. We aim to assess the model's effectiveness using standard metrics like accuracy, precision, and recall. Two models will be compared—one using the original data and another using resampled data to ensure fairness in training.

## Methodology:

Two models were developed for this analysis. The first utilized the original dataset, which had an imbalance between 'healthy loans' (75,036) and 'high-risk loans' (2,500). After splitting the data into Training and Test sets, a Logistic Regression model was created, and its performance was evaluated using confusion matrices, accuracy, precision, and recall.

The second model used a resampled dataset, ensuring an equal number of 'healthy loans' and 'high-risk loans' (56,271 each). Similar to the first model, the dataset was divided into Training and Test sets, and a Logistic Regression model was constructed. Evaluation metrics were then computed for both sets.

## Results:

Machine Learning Model 1 (Original Data):

    Test Data Balanced Accuracy: 99%
    Precision for 'healthy loans': 100%
    Precision for 'high-risk loans': 85%
    Recall for 'healthy loans': 99%
    Recall for 'high-risk loans': 91%

Machine Learning Model 2 (Resampled Data):

    Test Data Balanced Accuracy: 99%
    Precision for 'healthy loans': 99%
    Precision for 'high-risk loans': 99%
    Recall for 'healthy loans': 99%
    Recall for 'high-risk loans': 99%

## Summary:

The first model excels at identifying 'healthy loans' but shows a dip in performance for 'high-risk loans' due to data imbalance. The second model, trained on resampled data, performs consistently well for both loan types, making it the recommended choice. Accurate identification of 'high-risk loans' is crucial, given the potential costs associated with misidentifying and lending to such applicants.
