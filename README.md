# Friday Chatbot

Welcome to the **Friday Chatbot** repository! This project leverages the **Gemini Pro API** to create a highly interactive and intelligent chatbot interface, powered by **Streamlit**.

---

## Features

- **Conversational Interface**: Engages users with an intuitive chat interface.
- **Gemini Pro API Integration**: Utilizes advanced AI capabilities for natural and meaningful interactions.
- **Streamlit Framework**: Provides a lightweight and responsive web application.
- **Customizable Design**: Easily adapt the chatbot to fit different use cases.

---

## Getting Started

Follow these steps to set up the Friday Chatbot on your local machine:

### Prerequisites

1. Python 3.12
2. Gemini Pro API key
3. Required Python packages (listed in `requirements.txt`)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/InquietoPartho/Friday_chatbot
   cd friday-chatbot
   ```
2. Install dependencies::
   ```bash
   pip install -r requirements.txt
   ```
3. Add your Gemini Pro API key to the .env file:
   ```bash
   GEMINI_PRO_API_KEY=your_api_key_here
   ```
4. Run the Application:
   ```bash
   streamlit run main.py
   ```
5. Open your browser and navigate to http://localhost:8501 to interact with the chatbot

You can also try the live demo of the chatbot at: [Friday Chatbot](https://fridaychatbot.streamlit.app/)

## App Preview

![Friday Chatbot Preview](assests/chat_preview.png?raw=true)

## Files Overview

- **.env**: Contains environment variables such as API keys or configuration settings. These are kept out of the codebase for security and privacy reasons.
- **main.py**: The main Python file that implements the Streamlit application, where the chatbot's interface and logic are defined.
- **README.md**: Project documentation that provides an overview, setup instructions, and details on how to run the chatbot application.

- **requirements.txt**: Lists all the dependencies required for the project. You can install them using the following command:

## Acknowledgements

- **[Streamlit](https://streamlit.io/)**: For providing the framework to easily build interactive web applications for data science and machine learning.
- **[Gemini Pro API](https://gemini.com/pro-api)**: For providing the tools to integrate chatbot capabilities and enhance the interaction with users.

## Happy coding! 🚀
