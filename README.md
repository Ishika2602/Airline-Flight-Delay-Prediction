Flight Delay Prediction Using Machine Learning 

Project Overview 

Flight delays significantly impact both passengers and airlines, leading to increased costs and decreased customer satisfaction. This project leverages machine learning techniques to predict flight delays using historical flight data. 

 Key Features 

- Data Analysis & Preprocessing: Cleaning, feature engineering, and data normalization. 

- Machine Learning Models: Implemented multiple models (Neural Networks, Random Forest, SVM, XGBoost) to predict flight delays. 

- Performance Optimization: Hyperparameter tuning and feature selection for improved accuracy. 

- Visualization & Insights: Created dashboards using Power BI/Tableau to showcase delay patterns. 

 Dataset 

- Total Records: 539,383 flights 

- Features Include: Flight duration, departure time, airline, origin, destination, and day of the week. 

- Data Source: Kaggle - [Airlines Flight Delay Dataset](https://www.kaggle.com/datasets/jimschacko/airlines-dataset-to-predict-a-delay) 

Machine Learning Models 

| Model                     | Accuracy  | AUC    |

|---------------------------|----------|--------|

| Neural Network       | 96.47% | 0.9465 |

| Gradient Boosting (GBM)   | 89.86%   | 0.9259 |

| Random Forest             | 66.25%   | 0.9254 |

| Support Vector Machine    | 65.44%   | 0.9152 |

| Lasso Regression          | 64.87%   | 0.9091 |

 
 Technologies Used 

- Programming Languages:Python, SQL 

- Libraries:Pandas, NumPy, Scikit-Learn, TensorFlow, PyTorch, XGBoost, Seaborn 

- Data Visualization:Power BI, Tableau, Matplotlib 

- Big Data Processing: Apache Spark, Hadoop 


Performance Metrics 

- Accuracy:96.47% (Neural Network) 

- Precision & Recall Analysis:High recall for capturing delayed flights. 

- Confusion Matrix & ROC Curve: Evaluated model performance across different thresholds. 

 
 Recommendations & Future Work 

✔️ Incorporate Real-Time Data: Integrate live weather & air traffic data. 

✔️ Enhance Model Performance:Use ensemble learning & feature engineering. 

✔️ Deploy Model:Create an API for real-time flight delay predictions. 

✔️ Interpretability:Apply Explainable AI (XAI) techniques for better decision-making. 
