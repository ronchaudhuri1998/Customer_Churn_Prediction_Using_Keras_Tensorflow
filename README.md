## Customer_Churn_Prediction_Using_Keras_Tensorflow
Building and Optimizing Deep Learning Models for Customer Churn Prediction using Hyperparameter Tuning

- Built a Deep Learning Model for Customer Churn Prediction using TensorFlow and Keras, applying feature engineering (scaling, one-hot encoding) on structured financial data. Designed a feedforward neural network with tunable layers, activation functions, and learning rates.

- Implemented Hyperparameter Optimization using Random Search, Bayesian Optimization, and Hyperband to fine-tune model architecture. Achieved 100% accuracy, with Hyperband outperforming others by minimizing loss and reducing training time by ~50%.

- Leveraged Key Deep Learning Concepts such as activation functions (ReLU, Tanh, Sigmoid), loss function (Binary Crossentropy), and Adam optimizer to enhance performance. The project demonstrates efficient hyperparameter tuning, model evaluation, and scalability, critical for real-world ML applications.

#Model Performance Comparison
Hyperparameter Tuning Results

| Method               | Test Loss      | Test Accuracy | Time (seconds) |
|----------------------|---------------|--------------|---------------|
| Random Search       | 1.203229e-06   | 1.0          | 31.856560     |
| Bayesian Optimization | 1.675781e-06  | 1.0          | 33.066275     |
| Hyperband          | 4.849755e-08   | 1.0          | 17.171951     |


