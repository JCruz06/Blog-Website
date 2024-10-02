# Blog Website

A simple blog website built using Flask, HTML, CSS, and JavaScript. This project allows users to create, edit, and delete blog posts. It also includes features like user authentication and a responsive design.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [License](#license)

## Installation

To get started with the blog website locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/JCruz06/Blog-Website.git
2. **Navigate to the project directory**:
   ```bash
   cd Blog-Website
3. **Create and activate a virtual environment**:
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # On macOS/Linux
   .venv\Scripts\activate      # On Windows
4. **Install the dependencies**:
   ```bash
   pip install -r requirements.txt
5. **Set up environment variables: Create a .env file in the root directory with the following content**:
   ```bash
   SECRET_KEY=your_secret_key_here
   DB_URI=your_db_uri_here
6. **Run the application**:
   ```bash
   set FLASK_APP=main.py
   flask --app main run

## Usage

1. **Home Page**: Displays a list of all blog posts.
2. **User Authentication**: Users can register, log in, and log out.
3. **Create/Edit Posts**: Authenticated users can create new posts and edit or delete their own posts.

## Features

- User authentication (register, login, logout)
- Create, edit, and delete blog posts
- Responsive design for mobile and desktop
- Admin panel for managing content (if implemented)

## Technologies Used

- **Backend**: Flask, Python
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (or any other DB, update based on your usage)
- **Authentication**: Flask-Login, Flask-WTF


