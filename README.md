<p align="center"> 
  <img src="image/Email Logo.png" alt="Email Logo.png" width="80px" height="80px">
</p>
<p align="center"> 
<img src="gif/spam detector.gif" alt="Animated gif pacman game" height="382px">
</p>


**<h1>Problem Definition</h1>**

**Problem:**

 The goal of this project is to create a system that can classify emails as either "spam" or "ham".

 Spam emails are unwanted messages that are usually for advertising or scams.
 Ham emails are regular, legitimate messages that are not spam.


The challenge is to accurately separate spam emails from regular ones using techniques from  machine learning models.



**<h1>Why This Problem</h1>**

Email spam is a persistent and growing problem in digital communication. Every day, millions of spam emails are sent, and they often contain irrelevant content, unwanted advertisements, or malicious links. This results in a significant waste of time and resources for individuals and organizations.

Spam emails also pose a security threat, as they may contain phishing attempts or malware that can compromise sensitive information. Automating spam detection is crucial because it can improve user experience by filtering out unwanted emails, reduce the burden on manual email management, and enhance email security.

By solving this problem with a machine learning-based spam classification model, we can help users and organizations efficiently manage their inboxes and avoid the risks posed by spam emails.

---

**<h1>Approach</h1>**

My approach involves the following steps:

**<h3>1. Data Preprocessing</h3>**:

- Loading the dataset and handling missing data.
- Label encoding, where "ham" is labeled as 1 and "spam" is labeled as 0.
- Splitting the data into training and test datasets for model evaluation.

**<h3>2. Feature Extraction</h3>**:

- Using **TF-IDF Vectorizer** to convert the email messages into numerical data (features) that can be used by machine learning models. TF-IDF helps to capture the importance of words in the emails.

**<h3>3. Model Selection and Training</h3>**:

You used multiple models including:

- **Logistic Regression**
- **K-Nearest Neighbors**
- **Decision Tree Classifier**
- **Random Forest Classifier**

Each model is trained on the training data and evaluated on the test data.

**<h3>4. Model Evaluation</h3>**:

- You evaluated the models using metrics such as **accuracy**, **precision**, **recall**, and **F1 score**.
- **Learning curves** were used to observe overfitting or underfitting tendencies.
- **Confusion matrices** were plotted for the best-performing model to visualize its predictions.

  **<h3>5. Model Selection</h3>**:

The model with the highest accuracy was chosen as the final model for making predictions on new data.

**<h3>6. Prediction</h3>**:

## Finally, the trained model was used to classify a sample email into spam or ham.


![image](https://github.com/user-attachments/assets/44bfe145-0a34-469b-b566-5f5a7bbb0acd)

