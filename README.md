
<h1>Project Overview</h1>
<p>This project aims to detect fraudulent credit card transactions using machine learning. The goal was to build a model that could accurately identify fraudulent transactions based on the features provided in the dataset, thereby helping to prevent financial losses due to fraud.</p>

<h2>Dataset</h2>
<p>The dataset used for this project consists of anonymized features derived from credit card transactions. It includes the following key features:</p>

<li>Time: The number of seconds elapsed between this transaction and the first transaction in the dataset.</li>
<li>V1, V2, ..., V28: Principal component analysis (PCA) transformed features to protect confidentiality.</li>
<li>Amount: The transaction amount.</li>
<li>Class: The target variable, where 1 indicates a fraudulent transaction and 0 indicates a legitimate transaction.</li>
<h3>Project Structure</h3>
<li>Data Preprocessing: Handling imbalanced data, scaling features, and data transformation.</li>
<li>Exploratory Data Analysis (EDA): Understanding the distribution of data and the relationships between features.</li>
<li>Model Training: Training the model to detect fraud.</li>
<li>Model Evaluation: Evaluating the performance of the model using metrics like accuracy, precision, recall, F1-score.</li>
<li>Prediction: Using the model to predict fraudulent transactions in new data</li>
