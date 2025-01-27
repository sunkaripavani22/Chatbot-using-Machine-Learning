# Chatbot-using-Machine-Learning
A chatbot is a computer program designed to simulate human conversation and assist users in various tasks through natural language processing (NLP). When implemented using a logistic regression model, the chatbot utilizes one of the simplest machine learning algorithms to classify and respond to user queries.
# Intents-Based Chatbot Using Logistic Regression and NLP

## Overview
This project is a chatbot designed to classify and respond to user input based on predefined intents. It utilizes Natural Language Processing (NLP) techniques and a Logistic Regression model to predict user intent and generate appropriate responses. The chatbot is deployed using Streamlit, providing an interactive and user-friendly interface.

---

## Features
- **Intent Classification**: Classifies user input into predefined intents using Logistic Regression.
- **NLP Integration**: Implements text processing techniques like tokenization and TF-IDF vectorization.
- **Interactive Interface**: Built with Streamlit for real-time interactions.
- **Conversation Logging**: Logs user-chatbot interactions with timestamps in a CSV file.
- **Scalable Design**: Easily extendable by adding more intents or integrating advanced models.

---

## Project Structure
- **`intents.json`**: A dataset containing labeled intents, patterns, and responses.
- **Streamlit Interface**: A web-based interface for user interactions.
- **Conversation Log**: A CSV file storing the history of conversations.

---

## How It Works
1. **Data Preprocessing**:
   - User inputs are tokenized and vectorized using the TF-IDF method.
2. **Model Training**:
   - A Logistic Regression model is trained on the intents dataset to classify user input into corresponding intents.
3. **Response Generation**:
   - Based on the predicted intent, a random response is selected from the predefined responses for that intent.
4. **Interactive Chat**:
   - Users interact with the chatbot through a web interface, and conversation history is logged for review.

---

## Setup and Installation
1. Clone the repository:
  git clone <repository-url>
   cd <repository-folder>
2.Install dependencies:
   pip install -r requirements.txt
3.Download NLTK Data
  import nltk
  nltk.download('punkt')
4.Run the application
  streamlit run <script_name>.py
Usage:
Navigate to the chatbot interface.
Enter a message in the input box and press Enter.
View the chatbot's response and explore the "Conversation History" tab for past interactions.
Learn more about the project in the "About" section.

Future Enhancements:
Expand the dataset with additional intents and patterns.
Integrate sentiment analysis for personalized responses.
Implement multilingual support for broader accessibility.
Explore deep learning models for improved intent classification.

Contributions:
Contributions are welcome! Feel free to open issues or submit pull requests to improve the chatbot.




