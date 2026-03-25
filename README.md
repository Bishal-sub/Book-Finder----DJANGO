# 📚 Book Finder (Django Project)

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Django](https://img.shields.io/badge/Django-4.x-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

---

## 🔍 Overview

**Book Finder** is a Django-based web application that allows users to explore books, view detailed information, and discover where books are available.

Admins can manage books, stores, and related data through the Django admin panel, while users interact with a clean frontend interface.

---

## ✨ Features

* 📖 Browse books by category
* 🔎 View detailed book information
* 🏬 See which stores have the book available
* ⭐ User reviews and ratings
* 🖼️ Book image support
* 🔐 Admin panel for managing data

---

## 🧱 Project Structure

```
book_finder/
│── manage.py
│── requirements.txt
│── .gitignore
│── README.md
│
├── book_finder/          # main project folder
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
|  ├── templates/
│     └── website/base.html
│     ├── home.html
│     ├── book_detail.html
│     └── store.html
│
├── books/                # your app
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── admin.py
│   └── apps.py
│
├── media/                # uploaded images

```

---

## 🗃️ Models Overview

* **Books** → Stores book details (name, author, price, category, image)
* **BookStore** → Stores shop name and location
* **BooksReviews** → User reviews and ratings
* **ISBN** → One-to-one mapping with book details

---

## 📸 Screenshots

### 🏠 Homepage

<img width="100" height="907" alt="Screenshot 2026-03-25 074029" src="https://github.com/user-attachments/assets/1ff9d22e-68e1-492a-8efa-0180302d8d8a" />


### 🏬 Store Listing

<img width="1840" height="861" alt="Screenshot 2026-03-25 074053" src="https://github.com/user-attachments/assets/79000bc7-cb99-4ff0-8283-f6284cb64a28" />


### ⚙️ Admin Panel

<img width="1856" height="832" alt="Screenshot 2026-03-25 074426" src="https://github.com/user-attachments/assets/f467c250-820e-4d18-8ef3-b046aca3a2ac" />


---

## 🚀 Getting Started

### 🔧 Prerequisites

* Python 3.10+
* pip

---

### ⚡ Installation

```bash
git clone https://github.com/bishal-sub/bookfinder.git
cd bookfinder
```

```bash
pip install -r requirements.txt
```

```bash
python manage.py migrate
```

```bash
python manage.py createsuperuser
```

```bash
python manage.py runserver
```

---

## 🌐 Usage

* Visit: `http://127.0.0.1:8000/`
* Admin panel: `http://127.0.0.1:8000/admin/`

---

## 🛠 Tech Stack

* **Backend:** Django
* **Frontend:** HTML, CSS
* **Database:** SQLite
* **Language:** Python

---

## 📌 Future Improvements

* 🔍 Search & filtering system
* 📄 Pagination
* ❤️ Wishlist / favorites
* 🌍 Deployment (Render / Railway)
* 📱 Responsive UI

---


## 👨‍💻 Author

GitHub: https://github.com/bishal-sub

---
