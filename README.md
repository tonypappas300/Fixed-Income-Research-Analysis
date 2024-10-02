# Fixed-Income-Research-Analysis

This project aims to provide a streamlined interface for users to interactively ask questions based on the content of fixed income research documents using Gemini, a conversational AI model.

Features
Upload PDF files: Users can upload one or multiple PDF documents to the application.
Extract text content: The application extracts text content from the uploaded PDF files using PyPDF2.
Interactive question-answering: Users can ask questions based on the content of the PDF documents using the Gemini-Pro conversational AI model.
Real-time response: The application generates responses to user questions in real-time, providing an interactive experience.

How to Use

1. Clone the repository to your local machine
2. Install the required dependencies:

pip install -r requirements.txt

3. Set up your Google API key:

Obtain a Google API key and configure it in your environment variables or in a .env file.
You can obtain a Google API key by following the instructions provided here.

4. Run the Streamlit application:

streamlit run chat.py

5. Access the application in your web browser:

Open a web browser and navigate to the URL provided by Streamlit (typically http://localhost:8501).

6. Upload PDF files and ask questions:

Upload one or multiple PDF documents using the file uploader in the sidebar.
Enter your question in the text input box and click the "Submit & Process" button.
The application will process the uploaded PDF files, extract text content, and generate responses to your questions using the Gemini AI model.
Use the Fixed Income Research Reports folder for testing pdf Bloomberg FI reports.
