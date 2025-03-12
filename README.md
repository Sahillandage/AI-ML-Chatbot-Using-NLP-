Chatbot using NLP | AICTE Cycle 4
This project implements a chatbot using Natural Language Processing (NLP) techniques and Logistic Regression for intent classification. The chatbot is built using Streamlit for an interactive web-based interface.

Features
✔ Intent recognition using TF-IDF Vectorizer and Logistic Regression
✔ Interactive Streamlit-based chatbot UI
✔ Supports conversation logging with timestamps
✔ Expandable intents for easy customization

Installation & Setup
Clone the repository

sh
Copy
Edit
git clone https://github.com/Sahillandage/Chatbot_using_NLP_AICTE_Cycle4.git
cd Chatbot_using_NLP_AICTE_Cycle4
Install dependencies

sh
Copy
Edit
pip install -r requirements.txt
Run the chatbot

sh
Copy
Edit
streamlit run chatbot.py
Note: Ensure you navigate to the correct project directory before running the command.

File Structure
📂 chatbot.py - Main script for chatbot interface
📂 intents.json - Contains chatbot intents, user queries, and responses
📂 chat_log.csv - Stores chat history (generated dynamically)
📂 ImplementationofChatBot.ipynb - Notebook with chatbot implementation details

How It Works
The chatbot loads predefined intents from intents.json.
User input is vectorized using TF-IDF and classified with Logistic Regression.
Based on the predicted intent, a random response from intents.json is selected.
Conversation history is stored in chat_log.csv.
Customization
Modify intents.json to add new intents and responses.
Fine-tune the Logistic Regression model for improved accuracy.
Future Enhancements
Integration with Neural Networks for better intent recognition.
Adding voice support and real-time API integration.
Contributors
👤 Sahil Mahedimiya Landage
👤 AICTE Internship Cycle 4 Team

License
This project is licensed under the MIT License.


