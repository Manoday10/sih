# SIH_1706
Intelligent Enterprise Assistant: Enhancing Organizational Efficiency through AI-driven Chatbot Integration

## 📚 Introduction
The application is specifically designed to handle PDF documents related to organizational matters such as HR policies, IT support, and company events. It uses advanced deep learning and natural language processing techniques to provide accurate and timely responses to employee queries within a large public sector organization.

## 🛠 Skills
Flask, Langchain, PyPDF2, FAISS, HuggingFace, Google GenAI

## 💬💡 Features

- **Efficient PDF Text Extraction:** Reads and extracts text from PDF files using PyPDF2, ensuring all relevant content is processed for further analysis.

- **Text Chunking:** Splits extracted text into manageable chunks using RecursiveCharacterTextSplitter for improved processing and analysis.

- **Vector Store Management:** Utilizes FAISS for vector storage and retrieval, enabling efficient similarity searches and context-aware responses.

- **Customizable Summarization:** Employs Google Generative AI for generating summaries of PDF content, tailored to extract organizationally relevant information.

- **Contextual Query Handling:** Uses advanced NLP techniques to accurately answer questions about organizational matters based on document content.

- **Real-Time Processing Feedback:** Processes and summarizes PDF documents related to HR policies, IT support, and other organizational topics efficiently.

- **Error Reporting:** Includes robust error handling to notify users of issues during file processing or query handling, ensuring a smoother user experience.


## Installation

### Prerequisites
- Python 3.x
- Flask
- Google GenAI
- HuggingFace
- Langchain


### Dependencies

```bash
pip install -r requirements.txt
```

### Running

```bash
python app.py
```

## API Endpoints

`/process_pdf`
 - Method: `POST`
 - Description: Upload and process PDF files.
 - Request:
    - `pdf_file`: PDF File to be processed.
  
`summarize_pdf`
  - Method: `POST`
  - Description: Summarize PDF content.
  - Request:
    - `pdf_file` (multipart/form-data): PDF file to be summarized.
   
`/ask_question`
  - Method: `POST`
  - Description: Ask a question based on the document contents.
  - Request:
    - `question` (JSON): User’s question to query the document.


## 🚀 About Me
[@Siddharth Mishra](https://github.com/Sid3503)
