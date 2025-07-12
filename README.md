# MACHINE-LEARNING-MODEL-IMPLEMENTATION
*COMPANY* : CODTECH IT SOLUTIONS
*NAME* : KOLUSU CHAITANYA VARMA
*INTERN ID* : CT08DF1081
*DOMAIN* : PYTHON PROGRAMMING
*DURATION* : 8 WEEKS
*MENTOR* : NEELA SANTHOSH

**DESCRIPTION** :

For my fourth task, I developed a spam detection system using machine learning and natural language processing (NLP) techniques. The primary objective of this task was to classify incoming messages as either spam or ham (non-spam), based solely on the content of the text. The implementation was done in Python using PyCharm. Several key libraries were used: pandas for data manipulation, nltk for natural language processing tasks like tokenization and stemming, scikit-learn for building the machine learning model, and seaborn and matplotlib for visualizations.

I began the task by loading the dataset, which typically contains  text messages labeled either as spam or ham.I included fallback logic in case the dataset was missing, allowing a sample dataset to be used instead. Once the data was loaded, unnecessary columns were dropped and only the two most important ones — the label and the message — were kept. Any rows with invalid or unexpected labels were filtered out to maintain data quality.I explored the data by analyzing the distribution of spam and ham messages. This gave me a better idea of how balanced or imbalanced the dataset was, which is important when building classification models. A simple bar chart was created to visualize the frequency of each label, helping to spot any potential bias in the data. Once this initial analysis was done, I moved on to text preprocessing, which is a critical step in any NLP pipeline. This included converting all messages to lowercase, removing punctuation, eliminating stopwords (commonly used words that do not add much meaning), and applying stemming to reduce words to their root forms. These steps ensured that the machine learning model would focus on meaningful terms and patterns.
After preprocessing, I converted the text into numerical data using TF-IDF (Term Frequency–Inverse Document Frequency) vectorization. This technique transforms text into a format that machine learning algorithms can understand, by emphasizing terms that are frequent in a message but rare across the dataset. With these features in hand, I split the data into training and testing sets and trained a Multinomial Naive Bayes classifier — a popular algorithm for text classification tasks.
The model was evaluated using several key metrics such as accuracy, precision, recall, and F1-score, and its performance was visualized using a confusion matrix and classification report. I also created a custom prediction function where new messages can be entered, and the system predicts whether they are spam or not, along with a probability score.
This spam detection system has many real-world applications. It can be integrated into email services to automatically filter unwanted promotional or fraudulent messages. It can also be used in SMS gateways, customer support platforms, and social media moderation tools to block malicious or irrelevant content.

**OUTPUT** :
<img width="600" height="400" alt="Image" src="https://github.com/user-attachments/assets/62894a3a-baac-484c-8515-42c35e14f2d2" />





