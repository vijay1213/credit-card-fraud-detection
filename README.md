**Credit Card Fraud Detection Model**

The goal of this project is to develop a logistic regression model capable of accurately detecting fraudulent credit card transactions within a given transactional dataset. To achieve this, a prerequisite study in imbalanced learning is required to understand the challenges associated with imbalanced datasets.

The initial logistic regression model is implemented to classify transactions as either fraudulent or legitimate. However, due to the inherent class imbalance in the dataset, the model may struggle to detect fraudulent cases effectively, even though it may boast of high accuracy, resulting in a low Recall Value and a high False Negative Rate.

To address this issue and enhance the model's efficiency, Synthetic Minority Oversampling Technique (SMOTE) is introduced. SMOTE is a popular oversampling technique that synthesizes new instances of the minority class (fraudulent transactions) by interpolating features from the existing minority samples. By generating synthetic samples, the dataset becomes more balanced, enabling the model to learn and generalize better.

The project focuses on improving the Recall Value and reducing the False Negative Rate, as these metrics are crucial in detecting fraudulent transactions. By leveraging SMOTE, the logistic regression model is expected to achieve higher efficiency in identifying fraudulent cases, thus minimizing the financial losses associated with credit card fraud.

The initial model achieved an impressive accuracy of 99% but struggled with a low recall value (0.59) and a high False Negative Rate (FNR) of 0.40 due to imbalanced data. By applying the Synthetic Minority Oversampling Technique (SMOTE), the FNR was reduced to 0.11, and the recall value increased to 0.89, significantly improving the efficiency and effectiveness of the model in identifying fraudulent transactions.

The project involves several steps, including data preprocessing, feature engineering, model training, and evaluation. The logistic regression model is implemented using suitable libraries or frameworks, ensuring efficient processing and accurate predictions. The performance of the model is assessed using appropriate evaluation metrics, such as accuracy, recall and FNR

Overall, this project aims to develop an effective logistic regression model using SMOTE to enhance the detection of fraudulent credit card transactions. By addressing the challenges posed by imbalanced datasets, the model can improve the Recall Value and minimize the False Negative Rate, contributing to more robust fraud detection systems in the financial domain.

Dataset Repository: Kaggle
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
