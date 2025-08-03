# 🛍️ Basic E-commerce Site

This is a simple full-stack e-commerce web application built using:

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js with Express.js
- **Database:** MongoDB (using Mongoose)

## 🌐 Features

- Product listing page
- Product details view
- Add to cart functionality
- Shopping cart
- User registration and login
- Order placement and tracking
- RESTful API backend

---

## 📁 Project Structure
ecommerce_project/
│
├── ecommerce_project/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── store/
│   ├── migrations/
│   │   └── __init__.py
│   ├── templates/
│   │   └── store/
│   │       ├── base.html
│   │       ├── index.html
│   │       ├── product_detail.html
│   │       ├── cart.html
│   │       └── checkout.html
│   ├── static/
│   │   └── store/
│   │       ├── style.css
│   │       └── script.js
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
│
├── db.sqlite3
├── manage.py
└── requirements.txt

