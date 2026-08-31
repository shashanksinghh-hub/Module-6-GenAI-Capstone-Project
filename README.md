AI Study Assistant using Gemini API
📌 Project Overview
AI Study Assistant is a Generative AI application that allows students to upload a PDF document and ask questions based on its content.
The application uses Google's Gemini API to generate intelligent answers from the uploaded PDF.
✨ Features
📄 Upload PDF documents
🤖 AI-powered question answering
🧠 Google Gemini API integration
📚 Answers generated from PDF content
⚡ Fast and interactive responses
🎓 Useful for students and study purposes
🛠️ Technologies Used
Python
Google Gemini API
Google Colab
PyPDF
Gradio
⚙️ How It Works
User uploads a PDF document.
The application extracts text from the PDF.
The user asks a question.
The question and PDF content are sent to the Gemini AI model.
Gemini generates an answer based on the PDF content.
The answer is displayed to the user.
🏗️ Project Architecture
PDF Upload
↓
Text Extraction using PyPDF
↓
User Question
↓
Prompt Engineering
↓
Google Gemini API
↓
AI Generated Answer
🚀 Installation
Install the required libraries:
!pip install -q google-genai gradio pypdf
🔑 API Configuration
Create a Gemini API key and store it securely before running the application.
💡 Example Usage
Upload a PDF and ask questions such as:
What is Engineering Graphics?
The AI Study Assistant will analyze the PDF content and generate a relevant answer.
🎯 Learning Outcomes
This project demonstrates:
Generative AI application development
LLM API integration
Prompt Engineering
PDF text extraction
AI-based Question Answering
Building an interactive AI application
👨‍💻 Author
Shashank Singh
