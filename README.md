# FileBot

**FileBot** is a chatbot specifically designed to answer questions based on uploaded PDF files. It utilizes **OpenAI's API** to generate responses from the content of the PDF file, allowing users to interact with the document conversationally.

## Features

- **PDF Upload:** Upload a PDF file, and FileBot will extract and analyze its content.
- **Question Answering:** Ask questions about the content of the uploaded PDF, and FileBot will provide responses based on the text.
- **OpenAI Integration:** The bot uses OpenAI's language models to generate accurate and context-aware answers from the uploaded PDF.

## Requirements

Before running the application, you will need an **OpenAI API Key**. Please follow these steps to generate the key:

1. **Generate an OpenAI API Key:**  
   Get your API key by signing up on OpenAI's platform and generating a key through this [link](xxxxx).  

2. **Add Your API Key to the Script:**  
   In the script, there is a section where you will need to manually add your OpenAI API key. Look for the following comment in the script:

   ```python
   # Add your OpenAI API key here
   OPENAI_API_KEY = "your-api-key-here"

3. **Python 3.x:**
Ensure that Python is installed on your machine. You can download Python [here](https://www.python.org/downloads/).

4. **Required Libraries:**
Install the required dependencies by running:
     ```bash
     pip install -r requirements.txt


## How It Works

### Step 1: Upload a PDF File
FileBot currently only supports PDF uploads. Upload the PDF file that you want to interact with.

### Step 2: Ask Questions
After uploading the PDF, you can start asking questions about its content. FileBot will process your queries and provide relevant answers based on the PDF's text.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/FileBot.git
   cd FileBot

2. **Add Your OpenAI API Key:**
Open the Python script, locate the section with the comment `# Add your OpenAI API key here`, and insert your key:
   ```python
   OPENAI_API_KEY = "your-api-key-here"

3.**Run the Application:**
 Start FileBot by running using bash in the sript folder: 
    ```bash
    python FileBot.py
 

## Usage
- Upload a PDF file.
- Ask questions related to the content of the PDF file.
- The chatbot will respond with answers generated based on the PDF content.




