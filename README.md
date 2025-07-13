CodeAlpha Artificial Intelligence Internship.
This file documents all tasks completed during the CodeAlpha Internship in Artificial Intelligence. The internship included three main tasks: building a chatbot using Flask, creating an image classification model using PyTorch, and implementing a text summarizer using spaCy.

Task #1: Build a Simple Chatbot (Python + Flask)
Installed Flask using pip:
pip install flask

Created a folder named "chatbot_project" and inside it, created a Python file named "app.py".

Wrote a simple chatbot program in "app.py" using Flask.

Ran the chatbot server using the command:
python app.py

Opened browser and visited:
http://127.0.0.1:5000/
to confirm the server is running.

Set up Flask web server with:

'/' route using GET method for homepage

'/chat' route using POST method to accept and respond to user input

Tested chatbot using Postman by sending POST requests with JSON input (example: {"message": "Hello"}).

Received chatbot response and prediction in the terminal.

Task #2: AI for Image Classification (Python + PyTorch)
Installed required libraries:
pip install torch torchvision Pillow

Created a Python file named "classify_image.py" using Visual Studio Code.

Wrote the code to load a pretrained PyTorch model (e.g., ResNet) and perform image classification.

Placed the image file (elephant.jpeg) in the same project folder.

Ran the script with:
python classify_image.py

The model processed the image and printed the prediction result in the terminal.

Task #3: Text Summarization (Python + spaCy)
Installed required libraries:
pip install spacy
python -m spacy download en_core_web_sm

Created a Python file named "text_summarizer.py".

Wrote the code to summarize a given paragraph using NLP techniques and word frequency (using spaCy and Counter).

Ran the script in the command prompt with:
python text_summarizer.py

The summary of the input text was printed in the terminal.

Tools and Technologies Used
Programming Language: Python

Web Framework: Flask

AI Frameworks: PyTorch, spaCy

Code Editor: Visual Studio Code, Notepad

API Testing: Postman

Image Libraries: Pillow

Skills Demonstrated
Web API development with Flask

Image classification using pretrained neural networks

Natural language processing (NLP) with spaCy

Working with JSON, HTTP requests, and REST APIs

Practical use of Python libraries for AI tasks

I am grateful to CodeAlpha for the opportunity to learn and work on real AI tasks as part of this internship.
