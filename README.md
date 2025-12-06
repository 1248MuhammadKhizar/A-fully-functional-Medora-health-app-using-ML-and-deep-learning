🩺 Medora Health App
Medora Health is a Python‑based health management application with a MongoDB database. It integrates AI models, doctor consultations, calorie tracking, stress detection, and loneliness relief features into one unified platform.

📘 Introduction
Medora Health was developed as a university project but designed with professional‑grade functionality. It combines physical health tracking, mental health support, and AI‑powered insights in a single app.

🌟 Features
🔐 Secure login/signup system

🏠 Personalized homepage for each user

📄 Upload health data form for new users

📊 Stress level detection using K‑Nearest Neighbors (KNN)

👨‍⚕️ Doctor consultation system with request management

🛠️ Separate admin and doctor profiles

🤖 Transformer AI model for chatbot and smart recommendations

🍎 Calorie intake calculator based on user metrics

💬 Loneliness relief feature with supportive interaction

📈 Planned analytics dashboard

🔒 Role‑based access control (User, Doctor, Admin)

🏗️ Architecture
Frontend: Python (Streamlit, Tkinter, or Flask templates)

Backend: Python (Flask/Django REST API)

Database: MongoDB (NoSQL, document‑oriented)

AI Models:

KNN for stress detection

Transformer for NLP chatbot

Authentication: JWT / Flask‑Login

⚙️ Installation
Clone the repository

Install dependencies with pip install -r requirements.txt

Run the backend server with python app.py

Ensure MongoDB is running locally or via Atlas

🔐 Authentication
Signup with email, password, and profile data

Login with secure JWT tokens

Role‑based access: User, Doctor, Admin

🏠 Homepage
Personalized dashboard showing stress level, calorie intake, and consultation options

New users prompted to upload health data

📄 Upload Data Form
Collects age, gender, weight, height, and lifestyle habits

Data stored securely in MongoDB

📊 Stress Level Detection
Uses KNN model to classify stress levels (Low, Medium, High)

Automatically calculated after data upload

👨‍⚕️ Doctor Consultation System
Browse available doctors

Request consultations

Doctors can accept or reject requests

Future expansion: chat/video call integration

🛠️ Admin & Doctor Profiles
Admin: Approve doctors, manage users, view analytics

Doctor: Set availability, respond to consultation requests

🤖 Transformer AI Model
Provides chatbot responses

Supports loneliness relief feature

Generates smart recommendations

🍎 Calorie Intake System
Inputs: weight, height, age, gender

Outputs: daily calorie recommendation based on BMR formula

💬 Loneliness Relief Feature
AI chatbot for companionship

Provides motivational messages

Suggests relaxation techniques

🗄️ Database (MongoDB)
Collections include:

Users

Doctors

Consultations

Health data

Chat history

🛠️ Tech Stack
Languages: Python

Frameworks: Flask/Django, Streamlit/Tkinter

Database: MongoDB

AI Models: KNN, Transformer

Authentication: JWT/OAuth2

📂 Project Structure
Backend: app logic, routes, controllers, models

Frontend: UI components, templates

AI Models: stress detection, chatbot

Database: MongoDB configuration and collections

Docs: project documentation

🔮 Future Improvements
Exercise tracking

Integration with wearable devices

Video call consultations

Community support groups

Cloud deployment (AWS/Azure)

🤝 Contributing
Fork the repository

Create a new branch

Commit changes

Submit a pull request

📜 License
MIT License — free to use and modify.
