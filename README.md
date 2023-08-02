# Fake-News-Detection

Project Title: Fake News Detection

Description:
Fake News Detection is an intelligent web application that uses machine learning to classify news articles as either real or fake. The project aims to combat the spread of misinformation and promote reliable news sources by providing users with a tool to verify the authenticity of news articles they come across on the internet.

Technologies Used:
1. Flask: Flask is a micro web framework in Python used to build the web application and handle HTTP requests.
2. Jupyter Notebook: Jupyter Notebook is used for data exploration, preprocessing, and model development.
3. Passive Aggressive Classifier: The Passive Aggressive Classifier is a popular online learning algorithm for binary classification tasks.
4. TfidfVectorizer: The TfidfVectorizer is used to convert text data into numerical features for training the machine learning model.
5. HTML/CSS: The user interface of the web application is created using HTML for structure and CSS for styling.

Functionality:
1. Home Page: The home page of the web application provides a user-friendly interface for users to input news articles they want to verify.
2. Prediction: Upon submitting an article, the web application uses the trained Passive Aggressive Classifier to predict whether the news is real or fake.
3. Result: The result page displays the prediction, indicating whether the article is classified as real or fake.
4. Model Update (Optional): The application may include a feature to update the machine learning model periodically to ensure accuracy and adaptability to new data.

Workflow:
1. Data Collection: The dataset for training the machine learning model consists of labeled news articles, where each article is classified as real or fake.
2. Data Preprocessing: The text data is preprocessed, including steps like removing stop words, tokenization, and vectorization using the TfidfVectorizer.
3. Model Development: In Jupyter Notebook, the Passive Aggressive Classifier is trained on the preprocessed data to learn to distinguish between real and fake news.
4. Model Deployment: The trained model is saved and loaded into the Flask web application for prediction.
5. Web Application: Flask is used to create the web application with the prediction functionality and user interface.
6. Testing: The application is thoroughly tested to ensure proper functionality and accuracy.

Challenges:
- Handling Imbalanced Data: Ensuring that the model is not biased towards the majority class (e.g., real news) due to imbalanced data distribution in the dataset.
- Handling Textual Data: Dealing with textual data and converting it into numerical features that the machine learning model can understand.
- Model Performance: Ensuring that the model's accuracy and generalization are satisfactory for reliable predictions.
Algorithm : passive aggressive classifier [ ML]
Accuracy : 95% [Approx]
