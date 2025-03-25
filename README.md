URL Shortener

Overview

This is a simple URL Shortener built using Flask, HTML, CSS, and SQLite. It allows users to shorten long URLs and redirect them using a unique short URL.

Features

Generate a short URL for a given long URL

Store URLs in an SQLite database

Redirect users to the original URL when they visit the short link

Prevent duplicate short links for the same long URL

Installation

1. Clone the Repository

git clone https://github.com/your-username/url-shortener.git
cd url-shortener

2. Install Dependencies

Make sure you have Python installed. Then, install the required dependencies:

pip install flask flask-sqlalchemy

3. Run the Application

python app.py

4. Open in Browser

Go to http://127.0.0.1:5000/ in your web browser.

Usage

Enter a long URL in the input field.

Click the "Shorten" button.

Copy the generated short URL and use it to redirect to the original URL
