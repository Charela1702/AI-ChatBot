# AI Chatbot Application

This project is a real-time AI chatbot built using Flask, HTML, CSS, and JavaScript, leveraging the Google Gemini AI API for generating responses. The application features a modern UI with a chat interface similar to popular chatbots, complete with user-friendly features like saving and deleting chats.

## Features

- Real-time AI chat functionality
- Save and delete chat history
- Modern and responsive UI
- Side navigation with chat history and new chat creation
- Deployment ready for Vercel

## Technologies Used

- Flask (Python)
- HTML, CSS, JavaScript
- Google Gemini AI API
- Vercel for deployment

### Prerequisites

- Python 3.x
- Flask
- Google Gemini AI API Key
- Vercel account (for deployment)


 **Configure the API key**:
    Replace the `YOUR_API_KEY` in `app.py` with your actual Google Gemini AI API key.
    ```python
    genai.configure(api_key='YOUR_API_KEY')
    ```

 **Run the application**:
    ```bash
    python app.py
    ```
    The app will be available at `http://127.0.0.1:5000`.

### File Descriptions

- **app.py**: The main Flask application file.
- **requirements.txt**: Contains all the dependencies required for the project.
- **vercel.json**: Configuration file for deploying the app on Vercel.
- **styles.css**: CSS file for styling the application.
- **scripts.js**: JavaScript file for handling the frontend logic.
- **index.html**: HTML file for the application's main interface.


## Usage

- **Send Messages**: Type your message in the input box and press Enter to send. The AI response will appear in the chat area.
- **New Chat**: Click on "New Chat" in the sidebar to start a new conversation.
- **Delete Chat**: Click on the three dots next to a chat in the sidebar to delete it. A confirmation popup will appear.

