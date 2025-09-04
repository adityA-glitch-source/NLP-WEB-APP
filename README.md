NLP-WEB-APP
Overview

This is a simple NLP-powered web application that includes a login/registration system and a Named Entity Recognition (NER) feature.

Users can sign up and log in (credentials stored in a JSON file).

Once logged in, users can enter text into a text box.

The app calls the ParallelDots API for Named Entity Recognition.

Results are displayed directly on the web page.

Features

 User authentication (Register/Login using JSON file, no database).

 Named Entity Recognition (NER) using ParallelDots API.

 Simple and interactive web interface.

 Tech Stack

Frontend: HTML, CSS

Backend: Python (Flask)

Data Storage: JSON file (instead of DB)

API: ParallelDots Named Entity Recognition

📂 Project Structure
NLP-WEB-APP/
│-- static/          # CSS, JS files
│-- templates/       # HTML templates
│-- app.py           # Flask/Django main server file
│-- users.json       # Stores user credentials
│-- README.md        # Project documentation


📌 Future Improvements

✅ Replace JSON file with a proper database (SQLite/PostgreSQL).

✅ Add more NLP features (Sentiment Analysis, Summarization, etc.).

✅ Improve UI using Bootstrap/Tailwind/React.

📜 License

This project is licensed under the MIT License.
