# SENTIMENT-ANALYSIS-WITH-NLP

"company":CODTECH IT SOLUTIONS

"Name":Deepak Prabhu

"Intern ID":CT06DM1228

"Domain":Machine Learning

"Duration":6 weeks

"Mentor":Neela Santhosh Kumar

**Description
    Sentiment Analysis Using TF-IDF Vectorization and Logistic Regression
This project focuses on building a sentiment analysis model that can classify customer reviews as either positive or negative. The model is developed using fundamental natural language processing (NLP) techniques along with traditional machine learning methods. The objective is to convert raw text data into meaningful numerical features and use these features to train a classification model that predicts sentiment accurately.

The first stage of this project involves data preprocessing, which is essential in NLP tasks. Preprocessing includes converting all text to lowercase, removing special characters and digits, and eliminating stopwords such as "is", "the", and "an" that do not contribute significantly to sentiment. These steps help in reducing noise and improving model performance by retaining only meaningful words.

Once the data is cleaned, the next step is feature extraction using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization. TF-IDF is a powerful technique that transforms text into numerical values by evaluating how important a word is in a document relative to the entire corpus. Words that occur frequently in one document but not across all documents are given higher weights, making TF-IDF more effective than simple word counts or binary encoding. The result is a sparse matrix where each row represents a review, and each column represents a word from the vocabulary.

With the numerical feature matrix prepared, the next step is to build a machine learning model. Logistic Regression is chosen for this task due to its simplicity, interpretability, and effectiveness for binary classification problems. The model learns the relationship between word features (from TF-IDF) and sentiment labels (0 for negative, 1 for positive). After training the model on a portion of the data, it is evaluated on unseen test data to measure its accuracy and generalization.

To evaluate performance, several metrics are used, including accuracy, precision, recall, and the F1-score. These metrics are derived from the confusion matrix, which shows how many positive and negative reviews were correctly or incorrectly classified. In addition to these metrics, a heatmap of the confusion matrix is plotted for visual understanding.

One key visualization involves identifying the most influential words in determining sentiment. By examining the learned coefficients of the logistic regression model, we can extract the top words that most positively or negatively influence the sentiment prediction. For instance, words like “excellent”, “love”, and “fantastic” may be strongly associated with positive sentiment, while words like “worst”, “terrible”, and “poor” typically signal negative sentiment. These visualizations not only enhance interpretability but also validate the model's understanding of sentiment-related language.

As an optional enhancement, Principal Component Analysis (PCA) is used to reduce the high-dimensional TF-IDF vectors into two components for plotting. This helps visualize how different reviews cluster in the vector space, providing insights into the separability of sentiments.

In conclusion, this project effectively demonstrates how classic NLP techniques and machine learning can be combined to analyze customer opinions. The use of TF-IDF provides a meaningful way to represent text data, while logistic regression offers a transparent and efficient method for sentiment classification. This model can serve as a foundation for more advanced applications, such as real-time sentiment monitoring or customer feedback analysis in business environments.

**Output
![Image](https://github.com/user-attachments/assets/fc26fb28-7736-49c7-8953-731b49a07586)

  ****Deployment model 
     https://singular-arithmetic-eee881.netlify.app/

      















