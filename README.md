
# 🧠 Mental Health Support Chatbot

This project is a Mental Health Support Chatbot built using [Streamlit](https://streamlit.io/) and [OpenAI's GPT-3.5-turbo model](https://platform.openai.com/docs/models/gpt-3-5-turbo). It provides mental health support through a chat interface, offering sentiment analysis, mood tracking, and personalized coping strategies based on user input.

A compassionate, evidence-based chatbot built with Streamlit and OpenAI to support users on their mental health journey. It analyzes user sentiment, suggests coping strategies, and provides helpful resources—all while maintaining privacy and empathy.


## ✨ Features
- 💬 **Conversational Support:** Chat with an AI assistant trained to provide empathetic, practical advice for stress, anxiety, depression, and more.
- 📊 **Sentiment Analysis:** Uses TextBlob to analyze your emotional state and tailors responses accordingly.
- 🛠️ **Coping Strategies:** Suggests actionable, evidence-based coping strategies based on your mood.
- 🔗 **Resource Links:** Offers immediate help resources and links to professional support.
- 📋 **Session Summary:** View a summary of your session's messages and mood changes.
- 🔒 **Privacy:** No personal data is stored permanently. All session data is temporary.


## ⚡ Setup Instructions


### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/Mental-Health-Support-Chatbot.git
```


### 2️⃣ Create and Activate a Virtual Environment
```bash
python -m venv env
env\Scripts\activate
```


### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```


### 4️⃣ Set Up OpenAI API Key
Create a `.env` file in the project root:
```
openai.api_key=YOUR_OPENAI_API_KEY
```


### 5️⃣ Run the App
```bash
streamlit run app.py
```


## 💡 Usage
- Type your message in the chat box and press "Send 🚀".
- View your sentiment and suggested coping strategies after each message.
- Access mental health resources and session summary as needed.


## ⚠️ Important Notes
- 🚫 **Do not share personal or sensitive information.**
- 💊 **This app does not diagnose or prescribe medication.**
- 🆘 **For emergencies, contact professional help or use the provided resources.**


## 📦 Dependencies
- streamlit
- openai
- textblob
- pandas
- python-dotenv


## 📄 License
This project is licensed under the MIT License.


## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.


## 🙏 Acknowledgements
- [OpenAI](https://openai.com/)
- [Streamlit](https://streamlit.io/)
- [TextBlob](https://textblob.readthedocs.io/en/dev/)
- [MentalHealth.gov](https://www.mentalhealth.gov/)


---

*🤖 This chatbot is for informational and supportive purposes only. For professional help, please consult a licensed mental health provider.*
## Features

- **Chat Interface**: Interact with the chatbot in a user-friendly chat interface.
- **Sentiment Analysis**: Analyze the sentiment of user messages and categorize them into different emotions.
- **Mood Tracking**: Track the user's mood over time based on their messages.
- **Coping Strategies**: Provide personalized coping strategies based on the user's emotional state.
- **Session Summaries**: Summarize the conversation and provide insights at the end of each session.
- **Helpful Resources**: Provide links to immediate help resources for mental health support.

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Vikranth3140/Mental-Health-Support-Chatbot.git
    cd Mental-Health-Support-Chatbot
    ```

2. **Create a virtual environment and activate it:**
    ```bash
    python -m venv env
    .\env\Scripts\activate
    ```

3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up your OpenAI API key:**
    - Obtain your OpenAI API key from [OpenAI](https://platform.openai.com/account/api-keys).
    - Add your API key to the environment variable `OPENAI_API_KEY` or replace `'your_openai_api_key'` in the code with your actual API key.

## Usage

1. **Run the Streamlit application:**
    ```bash
    streamlit run app.py
    ```

2. **Open the provided URL (typically `http://localhost:8501`) in your web browser.**

3. **Start interacting with the chatbot:**
    - Type your message in the input box and press "Send."
    - The chatbot will respond to your message, analyze the sentiment, track your mood, and provide coping strategies as needed.

## Project Structure

- `app.py`: The main application file containing the Streamlit code and logic for the chatbot.
- `requirements.txt`: List of required Python packages.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [OpenAI](https://openai.com/)
- [TextBlob](https://textblob.readthedocs.io/en/dev/)

## Resources

If you need immediate help, please contact one of the following resources:
- National Suicide Prevention Lifeline: 1-800-273-8255
- Crisis Text Line: Text 'HELLO' to 741741
- [More Resources](https://www.mentalhealth.gov/get-help/immediate-help)
