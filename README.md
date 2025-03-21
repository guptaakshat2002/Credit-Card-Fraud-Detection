# Credit-Card-Fraud-Detection

#### This project aims to detect fraudulent credit card transactions using machine learning techniques. It applies classification algorithms to identify whether a given transaction is fraudulent or not.

### Dataset:

The dataset used for this project is the Credit Card Fraud Detection Dataset available on Kaggle. It contains transaction details including the amount, time, and 28 anonymized numerical features.

Class: Target variable (0 = Non-Fraud, 1 = Fraud)

Time: Number of seconds elapsed between this transaction and the first transaction

Amount: Transaction amount

V1 to V28: Principal components obtained from PCA


### Project Structure:

Credit_Card_Fraud_Detection.ipynb: Jupyter Notebook containing the complete analysis and model implementation.

README.md: Project documentation.


### Methodology

Data Exploration and Visualization: Performed exploratory data analysis (EDA) using Seaborn and Matplotlib to understand the data distribution.

Data Preprocessing: Scaled the features using StandardScaler and handled class imbalance using techniques like SMOTE.

Modeling: Applied and compared the performance of Logistic Regression and Random Forest classifiers.

Evaluation: Used accuracy, precision, recall, and F1-score to evaluate model performance.


### Results

Random Forest: Provided higher accuracy and better detection of fraudulent transactions.


### Requirements

Ensure you have the following libraries installed:

      pip install numpy pandas seaborn matplotlib scikit-learn plotly

### Usage

  1. Clone the repository:

          git clone https://github.com/yourusername/Credit-Card-Fraud-Detection.git

  2. Navigate to the project directory:

         cd Credit-Card-Fraud-Detection

  3. Run the Jupyter Notebook:

         jupyter notebook Credit_Card_Fraud_Detection.ipynb

### Conclusion

This project highlights the importance of using robust classification models for fraud detection. Random Forest showed better results in handling the imbalanced dataset.


### License

This project is licensed under the MIT License.


Feel free to contribute or suggest improvements by submitting a pull request!

Author: Akshat Gupta

For any questions, contact me at akshatg989@gmail.com.



