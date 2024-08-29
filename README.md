# Full Stack Blog Application [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This is a full-stack blog application built using Flask for the backend, with HTML, CSS, and JavaScript for the frontend. The application allows users to create, view, edit, and delete blog posts. The data is stored in a SQLite database, and the UI features a modern, responsive design with blog posts displayed as tiles for easy navigation.

## Features

- **Create Posts:** Add new blog posts with a title and content.
- **View Posts:** Browse all blog posts on the homepage, displayed as tiles with a content preview.
- **Edit Posts:** Click on any blog post to edit the title and content.
- **Delete Posts:** Easily delete posts directly from the individual post view.
- **Responsive Design:** The UI is built with modern and sleek CSS, ensuring a great experience on both desktop and mobile devices.
- **Data Persistence:** Uses SQLite for storing blog post data, ensuring that posts persist between sessions.

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Flask (Python)
- **Database:** SQLite

## Setup Instructions

1. Clone the repository `git clone https://github.com/SantoshNtrjn/Blog-App.git`.
2. Install the required Python packages using `pip install -r requirements.txt`.
3. Run `python create_db.py` to set up the database.
4. Start the application using `python app.py`.
5. Access the blog at `http://localhost:5000` in your browser.
