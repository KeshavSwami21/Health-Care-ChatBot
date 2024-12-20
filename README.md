# Medical Chatbot

## Overview

The **Medical Chatbot** is a sophisticated conversational agent built to assist users with healthcare-related queries. It provides symptom recognition, disease classification, and general medical guidance. By leveraging machine learning and natural language processing (NLP), the chatbot ensures accurate and efficient real-time responses to user inputs.

## Features

- **Symptom Recognition**  
  Understands and identifies user-reported symptoms for preliminary diagnosis.
  
- **Disease Classification**  
  Utilizes machine learning models to classify potential diseases based on input symptoms.

- **Real-Time Interaction**  
  Offers seamless communication with instant responses, providing a dynamic and engaging user experience.

- **User-Friendly Interface**  
  Simple and intuitive chat interface designed for ease of use, ensuring accessibility for all users.

## Technologies Used

This project is built using a combination of robust and modern technologies:

- **Python**  
  The core programming language for backend development.
  
- **Django**  
  A high-level web framework used to build scalable and secure web applications.

- **SpaCy**  
  An open-source natural language processing library used for advanced text processing and entity recognition.

- **Machine Learning Models**  
  Utilizes both pre-trained and custom models for accurate disease classification.

- **Django Channels**  
  An extension to Django that supports WebSockets, enabling real-time communication for an interactive user experience.

## Getting Started

To set up and run the Medical Chatbot locally, follow the steps below.

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/medical-chatbot.git
cd medical-chatbot
```

### 2. Install Dependencies

Install the required dependencies from the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 3. Run the Development Server

Start the Django development server:

```bash
python manage.py runserver
```

After the server starts, access the chatbot in your browser at [http://localhost:8000/](http://localhost:8000/).

## Usage

Once the server is running, follow these steps:

1. Open the chatbot interface in your browser.
2. Type your symptoms or medical queries in the chatbox.
3. Receive real-time responses and guidance based on your input.

## Contributing

We encourage contributions to improve the project. To contribute:

1. **Fork the Repository**  
   Create a fork of the repository on GitHub.

2. **Create a New Branch**  
   For your feature or bug fix, create a new branch:
   ```bash
   git checkout -b feature-name
   ```

3. **Make Changes**  
   Implement your feature or bug fix and commit the changes:
   ```bash
   git commit -m 'Add new feature'
   ```

4. **Push to the Branch**  
   Push your changes to the new branch:
   ```bash
   git push origin feature-name
   ```

5. **Create a Pull Request**  
   Submit a pull request with a detailed description of your changes.
