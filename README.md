![Alt text](assets\WhatsApp Image 2024-09-16 at 20.06.56_36383657.jpg)




# AI Chatbot Application

Welcome to the AI Chatbot Application repository! This project demonstrates the creation of a production-ready chatbot application leveraging state-of-the-art AI technologies like GPT-4, DALL-E, FastAPI, OpenAI API, Python, and more.

## Overview
This project is designed to build a conversational AI chatbot that uses natural language processing and image generation capabilities. It can answer user queries, generate responses, and even create images using the DALL-E API. The application is built using FastAPI, which ensures high performance and easy deployment.
 
## Features
- **GPT-4 powered responses**: The chatbot generates context-aware, human-like responses using OpenAI's GPT-4 model.
- **Image generation**: Uses the DALL-E API to generate images based on user input.
- **Real-time interaction**: Real-time communication between the client and server using WebSockets.
- **FastAPI backend**: High-performance RESTful API built using FastAPI.
- **Extensible and scalable architecture**: Easily adaptable to integrate more AI models or features.
- **Error handling**: Graceful handling of invalid inputs and errors.

## Tech Stack
- **Backend**: FastAPI, Python
- **AI Models**: GPT-4, DALL-E
- **Deployment**: Render, PyCharm
- **WebSocket**: For real-time message exchange
- **Frontend**: HTML, CSS, and JavaScript
  
1.**clone the repository**
  ```bash
  https://github.com/ashutosh4m/full-stack-chatbot-final-.git
  ```

2. **Create a virtual environment**  
   ```bash
   python -m venv chatenv
   ```
   To activate the virtual environment:
   ```bash
   chatenv\Scripts\activate
   ```

3. **Install the dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**  
   Create a `.env` file with your OpenAI API keys:
   ```bash
   OPENAI_API_KEY=your-openai-api-key
   ```

5. **Run the application**  
   ```bash
   uvicorn app.main:app --reload
   ```

6. **Access the application**  
   Visit [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.
