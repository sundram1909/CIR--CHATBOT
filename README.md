# CIR--CHATBOT
 a conversational Chatbot is an application that is able to communicate with humans using natural language. However there exists a need for an image recognition deep learning based Chatbot is an application to recognize the images, uploaded by user and answer the questions about the image. 
.
git clone https://github.com/your-username/chess-gemini-ai.git
cd chess-gemini-ai

#2. Create a Virtual Environment

python -m venv .venv
# On Windows
.\.venv\Scripts\activate
# On Mac/Linux
source .venv/bin/activate


#3. Install Dependencies
pip install -r requirements.txt

#4. Add Your Gemini API Key
Option 1: Directly enter the key in the Streamlit sidebar

Option 2: Use a .env file (optional)

GEMINI_API_KEY=your_gemini_api_key_here

#5. Run the Streamlit App

streamlit run chess_gemini.py

#📦 Requirements

streamlit
python-chess
google-generativeai

#📁 How to Organize All Files

chess-gemini-ai/
│
├── chess_gemini.py         # Your main Streamlit app
├── README.md               # This file (project documentation)
├── requirements.txt        # Required Python libraries
├── .gitignore              # Files to ignore in GitHub
├── .env                    # (Optional) API Key - NOT uploaded to GitHub


#✅ Example .gitignore:
.env
.venv/
_pycache_/


#📋 How to Use

1.Enter your Gemini API Key

2.Choose the number of turns

3.Click Start AI Game

4.Two AI agents will play chess against each other

5.Watch the moves live on the board and in the VS Code terminal

6.Click Reset Game anytime to restart
