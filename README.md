# 🤖 AI-Powered ChatBot

Welcome to the AI-Powered ChatBot project! This application leverages Google's Generative AI to create an interactive chatbot experience.

## 🚀 Quick Start

Get the ChatBot up and running on your local machine in minutes!

### Prerequisites

- Python 3.7+
- pip (Python package manager)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/Lekhan2004/Chatbot-Basic.git
   cd Chatbot-Basic
   ```

2. Set up a virtual environment:
   ```
   pip install virtualenv
   virtualenv chatbot
   ```

3. Activate the virtual environment:
   - On Windows:
     ```
     .\chatbot\Scripts\activate
     ```
   - On macOS and Linux:
     ```
     source chatbot/bin/activate
     ```

4. Install the required packages:
   ```
   pip install Flask
   pip install -q -U google-generativeai
   ```

5. Configure the API key:
   - Open `chatbot.py` in a text editor
   - Replace `'# Your API_key #'` with your actual Google Generative AI API key

6. Start the application:
   ```
   python app.py
   ```

7. Open your web browser and visit `http://localhost:5000`

## 🖥️ Usage

1. Type your message in the chat input field
2. Press Enter or click the Send button
3. Watch as the AI generates a response
4. Continue the conversation as long as you'd like!

## 🛠️ Customization

You can customize the chatbot's behavior by modifying the `chatbot.py` file. Adjust the AI model parameters or add pre-processing steps to tailor the chatbot to your specific needs.

## 🤝 Contributing

We welcome contributions to improve the ChatBot! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🙏 Acknowledgements

- [Google Generative AI](https://developers.generativeai.google/)
- [Flask](https://flask.palletsprojects.com/)
- [Python](https://www.python.org/)

---
