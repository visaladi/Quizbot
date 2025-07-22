# Quizbot
PDF Quiz Generator

A simple Flask-based web application that converts PDF or text files into multiple-choice quizzes. It extracts text from uploaded documents, generates fill-in-the-blank questions, and provides selectable answer options.

Features

Upload PDF (.pdf) or plain text (.txt) files

Automatic text extraction using PyPDF2

Fill-in-the-blank question generation without external NLP libraries

Multiple-choice options generated from sentence keywords

Interactive web interface built with Flask

Score calculation and result display

Prerequisites

Python 3.12 or higher

pip package manager

Installation

Clone the repository

git clone https://github.com/yourusername/pdf-quiz-generator.git
cd pdf-quiz-generator

Create and activate a virtual environment

python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

Install dependencies

pip install -r requirements.txt

Usage

Start the Flask app

python app.py

Open your browser at http://127.0.0.1:5000/

Upload a PDF or TXT file on the landing page

Generate and take your quiz

View your score on the results page

Project Structure

pdf-quiz-generator/
├── app.py               # Main Flask application
├── workers.py           # Text extraction and question generation logic
├── templates/           # HTML templates
│   ├── index.html       # Landing page
│   ├── quiz.html        # Quiz interface
│   └── result.html      # Results page
├── static/              # Static assets (CSS, JS)
│   ├── styles.css       # Styling
│   └── script.js        # Front-end interactivity
├── pdf/                 # Temporary upload folder
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation

tributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.
