FAQ Question-Answer Program

This repository contains a simple FAQ Question-Answer Program that reads questions and answers from a text file and allows the user to interactively answer questions. The program utilizes the scikit-learn library for vectorizing text and calculating cosine similarity to find the most relevant answers to the user's questions.

How It Works
1) Text File Format: The program reads from a text file (FAQ_ai.txt) where each line contains a question or an answer. The format should alternate between questions and answers, like so:

Q: What is artificial intelligence?
A: Artificial Intelligence (AI) is the simulation of human intelligence processes by machines, especially computer systems.

Q: How does machine learning work?
A: Machine learning involves training algorithms to recognize patterns in data and make predictions or decisions without being explicitly programmed.

Q: What are neural networks?
A: Neural networks are algorithms modeled after the human brain that are used to recognize patterns and learn from data.

Q: Can you explain natural language processing?
A: Natural Language Processing (NLP) is a field of AI that enables computers to understand, interpret, and generate human language.

Q: What is the purpose of a decision tree?
A: A decision tree is used for classification and regression tasks by splitting data into subsets based on input features to make decisions.

Q: How does supervised learning differ from unsupervised learning?
A: Supervised learning uses labeled data to train models, while unsupervised learning finds patterns in unlabeled data.

Q: What are convolutional neural networks used for?
A: Convolutional Neural Networks (CNNs) are primarily used for processing structured grid data, such as images, and are effective in image recognition tasks.

Q: What is the difference between overfitting and underfitting?
A: Overfitting occurs when a model learns the training data too well, including noise, leading to poor generalization, while underfitting happens when a model is too simple to capture underlying patterns.

Q: How does reinforcement learning operate?
A: Reinforcement learning involves an agent learning to make decisions by receiving rewards or penalties based on its actions in an environment.

Q: What are some common applications of AI in daily life?
A: Common applications include virtual assistants, recommendation systems, autonomous vehicles, and personalized advertisements.

...

2) Reading the File: The program reads the file and extracts the questions and answers into separate lists.

3 )Vectorizing Text: Using scikit-learn's TfidfVectorizer, the program converts the questions into numerical vectors.

4) Interactive Q&A: The user can input their questions, and the program calculates the cosine similarity between the user's question and the preloaded questions to find and display the most relevant answer.


Setup and Execution

Prerequisites
Python 3.6+
Anaconda (recommended for managing dependencies)
Required Python packages: scikit-learn, numpy

Installation

1) Clone the Repository
git clone https://github.com/yourusername/faq-question-answer-program.git
cd faq-question-answer-program

2) Install Dependencies
pip install -r requirements.txt


3)Prepare the Text File
Ensure you have your FAQ_ai.txt file formatted as described above.
Place the file in the same directory as main.py.

Running the Program

1) Execute the Script
python main.py

Interact with the Program
-The program will prompt you to ask a question.
-Type your question and press Enter.
-The program will display the most relevant answer based on the provided FAQ.

Example 
Please ask your question: What is artificial intelligence?
A: Artificial Intelligence (AI) is the simulation of human intelligence processes by machines, especially computer systems.


































