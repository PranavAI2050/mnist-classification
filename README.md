# Handwritten Digit Classification on MNIST

This project explores the classification of handwritten digits (0-9) from the MNIST dataset using three different machine learning models:

- Logistic Regression (baseline)
- Fully Connected Neural Network (Sequential MLP)
- Convolutional Neural Network (CNN)

## Project Overview

The goal is to classify grayscale 28x28 pixel images into digit classes, improving accuracy progressively across models.

## Results Summary

| Model                   | Test Accuracy | Notes                                         |
|-------------------------|---------------|-----------------------------------------------|
| Logistic Regression     | 93%           | Strong baseline; struggles with similar digits |
| Sequential MLP          | 96.4%         | Captures nonlinear patterns; better performance |
| Convolutional Neural Net | 98.94%        | Best performance; leverages spatial features  |

## Conclusion

- Logistic Regression provides a solid baseline.
- MLP improves accuracy by learning nonlinearities.
- CNN achieves highest accuracy by effectively extracting spatial features.
- Future work includes more advanced CNN architectures, regularization techniques, and data augmentation.

## How to Run

1. Ensure you have Python 3.x installed.
2. Install required dependencies (e.g., TensorFlow, scikit-learn).
3. Run the training scripts for each model to reproduce results.
4. Evaluate on the MNIST test set to see performance metrics.

---

For detailed analysis, results, and future directions, refer to the full report.

