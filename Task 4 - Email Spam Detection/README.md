Email spam detection with Machine learning

Introduction

This project involve creating a machine learning-based email spam detection system. The project encompasses data preprocessing, feature extraction, model training and evaluation, and the deployment of the model using Flask-based application.

Data Preparation and Preprocessing

**Dataset Overview**
The dataset used in this project is a collection of email messages labeled as 'spam' or 'ham' (non-spam). It contains the following columns:

v1: Email label (spam/ham).

v2: Email text.

**Preprocessing Steps**

Data Cleaning: Removed irrelevant columns ('Unnamed: 2', 'Unnamed: 3', 'Unnamed: 4') to focus on the label and email content.

Label Encoding: Converted the textual labels (spam/ham) into binary format (1 for spam, 0 for ham).

Text Preprocessing: Applied text normalization techniques such as lowercasing and removing punctuation.

Train-Test Split: Divided the dataset into training (80%) and testing (20%) sets.

**Feature Extraction**

TF-IDF Vectorization: Transformed the email texts into a numerical format using Term Frequency-Inverse Document Frequency (TF-IDF) to reflect the importance of words within the emails.

**Model Selection and Training**

Algorithm: Chose Multinomial Naive Bayes for its effectiveness in text classification tasks.
Training: The model was trained on the preprocessed training dataset.

**Model Evaluation**

Accuracy: Achieved an overall accuracy of 97%.

Precision and Recall:
<p>For 'ham': 96% precision, 100% recall.</p>
<p>For 'spam': 100% precision, 75% recall.</p>

**Confusion Matrix:**
Correctly classified 965 'ham' and 113 'spam' emails.

Misclassified 37 'spam' emails as 'ham'.

**Deployment of the Model**

**Flask Application**
The model was developed using a simple  Flask based application to serve the model as an API endpoint.

The following features were implemented in the application:
<ol>
<li>Email text input.</li>
<li>Spam classification using the trained model.</li>
<li>JSON response with classification results.</li>
</ol>

**User Interface**
A simple user interface using HTML, CSS, and JavaScript was created to enable users interact with the application

**Features of the User Interface:**
<ol>
<li>A text box for users to input email content.</l>
<li>A submit button to send data to the Flask API.</l>
<li>Display area for showing the classification result.</l>
</o>

