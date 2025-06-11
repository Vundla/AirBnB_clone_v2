# 🏠 Airbnb Clone - The Console & Web Project

## 📌 Description

This project is part of the **ALX Africa Software Engineering Program**. It is a **clone of the core features of Airbnb**, focusing on the backend logic, storage system, and basic front-end interface.

The goal is to build a web-based platform that mimics the original Airbnb website, allowing users to create and manage places to stay, hosts, and bookings.

The project was built in multiple stages, starting with a command-line interface (console), then evolving into a dynamic website with a RESTful API and front-end templates.

---

## 🚀 Features

- 🔧 **Command-Line Interface (Console)**
  - Create, show, update, and delete objects.
  - Persistent storage using JSON and/or database.

- 🗂️ **Data Models**
  - `User`
  - `Place`
  - `City`
  - `State`
  - `Amenity`
  - `Review`

- 🌐 **Web Static**
  - HTML/CSS pages that mimic the Airbnb user interface.

- 🧠 **Backend (Flask API)**
  - RESTful API to handle requests and serve data dynamically.
  - JSON-based endpoints.

- 💽 **Storage System**
  - Switchable between `file.json` and MySQL database.

---

## 🛠️ Technologies Used

- **Languages**: Python 3, HTML5, CSS3
- **Framework**: Flask (Python microframework)
- **Database**: MySQL
- **Storage Engines**: FileStorage & DBStorage
- **Others**: Jinja2 templates, JSON, RESTful APIs, Ubuntu/Linux environment

---

## 📁 Project Structure

AirBnB_clone/
├── console.py
├── models/
│ ├── base_model.py
│ ├── user.py
│ ├── city.py
│ ├── state.py
│ ├── place.py
│ ├── amenity.py
│ ├── review.py
│ └── engine/
│ ├── file_storage.py
│ └── db_storage.py
├── web_static/
│ ├── styles/
│ ├── images/
│ └── pages/
├── web_flask/
│ ├── templates/
│ └── routes.py
├── tests/
├── README.md
└── requirements.txt

