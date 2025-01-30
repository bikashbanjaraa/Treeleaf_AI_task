# Model Comparison Project

This project compares the performance of three different machine learning models:

- **Logistic Regression**
- **Random Forest**
- **Neural Network**

## Overview

The goal is to evaluate these models based on different performance metrics to determine which one works best for a given dataset.

## Dataset

We trained and tested the models on a dataset with features (X) and labels (y). The dataset was split into training and testing sets.

## Performance Metrics

The models were evaluated using:

- **Accuracy**: Measures overall correctness of predictions.
- **Precision**: Measures how many predicted positive instances are actually positive.
- **Recall**: Measures how many actual positive instances were correctly predicted.
- **F1 Score**: Balances precision and recall.

## Results

Here’s how the models performed:

| Model               | Accuracy | Precision | Recall | F1 Score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 80.3%    | 80.7%     | 80.3%  | 80.5%    |
| Random Forest       | 76.9%    | 77.6%     | 76.9%  | 77.1%    |
| Neural Network      | 74.7%    | 79.2%     | 74.7%  | 74.9%    |

### Key Takeaways

- **Logistic Regression performed the best overall**, with the highest accuracy and balanced precision-recall.
- **Random Forest was decent**, but slightly behind Logistic Regression.
- **Neural Network had the highest precision**, meaning it made fewer false positives, but its overall accuracy was lower.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git](https://github.com/bikashbanjaraa/Treeleaf_AI_task
   ```

   
2. Run the model training script
  
3. View performance results.
   
   ![image](https://github.com/user-attachments/assets/f395fca1-fb43-4146-851d-f33a73e6a62b)

   ![image](https://github.com/user-attachments/assets/4264e93f-d851-48c0-ae0e-a4f0085234d4)



## Future Improvements

- **Hyperparameter tuning** to improve model accuracy.
- **Feature engineering** to improve dataset quality.
- **Trying other models**, such as XGBoost or SVM, for better performance.

## Contributing

Feel free to contribute by submitting issues or pull requests!

## License

This project is open-source under the MIT License.

