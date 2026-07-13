# AI-Based Emotion Detection Web Application

### Emotion Detection using IBM Watson NLP and Flask

This project is a polished Flask-based web application that accepts user text, analyzes its emotional tone using NLP, and displays the predicted emotions through a simple interface.

![Python](https://img.shields.io/badge/Python-3.11+-blue?logo=python)
![Flask](<https://img.shields.io/badge/Flask-Web%20Framework-black?logo=flask>)
![IBM Watson](<https://img.shields.io/badge/IBM-Watson%20NLP-blue>)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## Overview

This application demonstrates how to combine a Flask web server with an AI-powered emotion detection service. It takes user input, sends it to the Watson NLP endpoint, extracts the emotion scores, and identifies the dominant emotion for presentation in the browser.

---

## Objectives

- Build an AI-powered emotion detection app
- Consume IBM Watson NLP APIs
- Develop reusable Python modules
- Create a clean Flask web interface
- Add unit tests for validation
- Handle invalid or empty input gracefully

---

## Features

- Detects joy, anger, fear, disgust, and sadness
- Identifies the dominant emotion
- Provides a lightweight web UI
- Includes basic error handling
- Organized with a reusable Python package structure

---

## Tech Stack

| Technology        | Purpose              |
| ----------------- | -------------------- |
| Python            | Backend logic        |
| Flask             | Web framework        |
| IBM Watson NLP    | Emotion prediction   |
| Requests          | API communication    |
| HTML / JavaScript | Frontend interaction |
| unittest          | Unit testing         |

---

## Project Structure

```text
EmotionDetection-WebApp/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── static/
│   └── mywebscript.js
├── server.py
├── test_emotion_detection.py
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## Workflow

```text
User Input → Flask Server → Watson NLP API → Emotion Scores → Dominant Emotion → UI Output
```

---

## Project Components

- Emotion Detection Module: Sends the text to the NLP service and extracts emotion results.
- Flask Server: Handles user requests and returns the formatted response.
- Unit Testing: Verifies the detector for known example inputs.
- Error Handling: Gracefully manages blank or invalid input.

---

## Project Demonstration

### 1. Folder Structure

![Folder Structure](images/1_folder_structure.png)

### 2. Emotion Detection Function

![Emotion Detection Function](images/2a_emotion_detection.png)

### 3. Application Creation

![Application Creation](images/2b_application_creation.png)

### 4. Output Formatting

![Output Formatting](images/3a_output_formatting.png)

### 5. Formatted Output Test

![Formatted Output Test](images/3b_formatted_output_test.png)

### 6. Packaging Structure

![Packaging Structure](images/4a_packaging.png)

### 7. Packaging Validation

![Packaging Validation](images/4b_packaging_test.png)

### 8. Unit Test Code

![Unit Test Code](images/5a_unit_testing.png)

### 9. Unit Test Result

![Unit Test Result](images/5b_unit_testing_result.png)

### 10. Flask Server

![Flask Server](images/6a_server.png)

### 11. Web App Deployment

![Deployment](images/6b_deployment_test.png)

### 12. Error Handling Function

![Error Handling Function](images/7a_error_handling_function.png)

### 13. Error Handling Server

![Error Handling Server](images/7b_error_handling_server.png)

### 14. Invalid Input Demo

![Invalid Input Demo](images/7c_error_handling_interface.png)

### 15. Final Server Implementation

![Final Server Implementation](images/8a_server_modified.png)

### 16. Static Analysis Result

![Static Analysis Result](images/8b_static_code_analysis.png)

---

## Running Locally

1. Create and activate a virtual environment.
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Start the Flask app:
   ```bash
   python server.py
   ```
4. Open the app in your browser at:
   ```text
   http://127.0.0.1:5000/
   ```

> Note: This project uses the IBM Watson Emotion API, so its behavior depends on the availability of that endpoint in your environment.

---

# 📚 Learning Outcomes

Through this project, I gained practical experience with:

- REST APIs
- Natural Language Processing
- Flask Web Development
- Python Packaging
- Unit Testing
- Error Handling
- Static Code Analysis
- Clean Code Practices

---

# 🔮 Future Improvements

- 🌍 Multi-language Emotion Detection
- 📊 Emotion Confidence Charts
- 📁 Prediction History
- ☁️ Cloud Deployment
- 🤖 Transformer-based Local Model
- 📱 Responsive UI

---

# 🌐 Connect With Me

- 🔗 LinkedIn: https://www.linkedin.com/in/utsav-mehta-462653258/
- 💻 GitHub: https://github.com/utsavmehta24
- 🌍 Portfolio: https://medium.com/@utsavmehta24072003
- 📧 Email: utsavmehta24072003@gmail.com
- 🐦 X (Twitter): https://x.com/Lucid24by7_io

---

<div align="center">
