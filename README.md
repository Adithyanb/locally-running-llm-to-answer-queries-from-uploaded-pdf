# Query Bot: Locally Running LLM for PDF Querying

This project provides a locally hosted solution for answering queries from uploaded PDF files using a Large Language Model (LLM). The system is designed to work seamlessly, allowing users to upload files, manage data, and interact with an AI-powered bot for efficient query resolution.

## Features
- **Local Deployment**: Fully functional LLM running locally for enhanced data privacy.
- **PDF Querying**: Upload PDF files and extract insights through AI-driven responses.
- **Database Management**: Reset and update the database with ease.
- **Interactive Bot**: Interact with the bot via `bot.py` for instant query resolution.

## Prerequisites
- Python 3.8 or higher
- Virtual environment tool (e.g., `venv` or `virtualenv`)
- Required Python libraries (listed in `requirements.txt`)

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Adithyanb/locally-running-llm-to-answer-queries-from-uploaded-pdf.git
   cd locally-running-llm-to-answer-queries-from-uploaded-pdf
Create and Activate a Virtual Environment:

bash
python -m venv venv
source venv/bin/activate       # For Linux/Mac
venv\Scripts\activate          # For Windows

Install Dependencies:
bash
pip install -r requirements.txt
Add Files: Place your PDF files into the data/ folder for processing.

Usage
Reset the Database
To reset the database and clear all existing data, run:
bash
python populate_database.py --reset
Update the Database

To manually update the database without clearing it, use:
bash
python populate_database.py

To start the query bot, execute:

bash
python bot.py
