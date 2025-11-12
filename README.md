🎬 Entertainment Content Recommender

A smart web app that recommends movies and series based on your favorite picks and preferred languages. Built with Python + Flask for the backend and HTML, CSS, and JavaScript for the frontend.

🚀 Features

This web app includes 4 main pages:

🏠 Home Page

Users can select their favorite movies or series and preferred languages.
For example:

If you enter Insidious, Insidious Chapter 2, Supergirl, and Suits with English and Hindi as preferred languages, the app will recommend titles with similar genres and styles.

After clicking Get Started, the app will show the top recommended content.

🎥 Recommendation Page

Displays posters of all recommended titles — neatly sorted by IMDb score.
Clicking any poster takes you to the Movie Detail Page.

📄 Movie Detail Page

Shows detailed information about the selected title:

Genre

Summary

Available Languages

IMDb Score

Directors, Writers, and Actors
At the end, a Netflix Link is provided to watch the title directly.

🍿 Netflix Page

(Not part of the web app)
This page demonstrates what a user would see after clicking the Netflix link — you can log in and stream the chosen title from your Netflix account.

⚙️ How to Run Locally

To run this app in your local development environment:

1️⃣ Prerequisites

Make sure you have Git and Python (with pip) installed.

2️⃣ Clone the Repository
git clone https://github.com/sahilkashyap263/Entertainment-Content-Recommender.git

3️⃣ Navigate into the Directory
cd Entertainment-Content-Recommender

4️⃣ Install Dependencies
pip install flask pandas scikit-learn

5️⃣ Run the App
set FLASK_APP=app.py
flask run


Then open your browser and go to http://127.0.0.1:5000/

👤 Author

Sahil Kashyap

GitHub: sahilkashyap263

LinkedIn: linkedin.com/in/sahilkashyap263

Email: sahilkashyap263@gmail.com

💫 Show Your Support

Give this project a ⭐ if you find it cool or useful!