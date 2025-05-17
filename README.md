# Plagiarism-checker

With this project, we build a Plagiarism Checker AI tailored with the MIT Plagiarism Detection Dataset. The dataset undergoes preprocessing by retrieving the `Text` and `Class` columns, where `Text` holds the student submissions, while `Class` signifies the plagiarism classification. Textual data is transformed into numerical features using TF-IDF vectorization, and a Logistic Regression model is trained as a basic Sentence-Level Model (SLM) for classification. The model is tested with training and testing scores, analyzing accuracy alongside a comprehensive classification report. The code works seamlessly with Google Colab and serves as an easy starting point for plagiarism detection in text documents.

