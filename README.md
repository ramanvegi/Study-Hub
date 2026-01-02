
# 📚 StudyBud

A full-stack web platform for students to connect, share knowledge, and collaborate through topic-based discussion rooms.

---

## 🚀 Overview

**StudyBud** is a collaborative learning platform that helps learners connect, join organized study rooms, discuss topics, and exchange ideas through real-time conversations. It enables students to collaborate instantly using interactive rooms, topic-wise discussions, and a smooth real-time messaging experience.

---

### ✨ Key Features

 - 💻 Built using Django (Python) with HTML, CSS, and Bootstrap for frontend design.

 - 🧠 Implemented user authentication (login, register, logout) using Django’s built-in auth system.

 - 🗂️ Created and managed study rooms with CRUD operations (Create, Read, Update, Delete).

 - 🔍 Added search and filter functionality for finding rooms by topic or name.

 - 💬 Enabled real-time discussions within rooms through message posting.

 - ⚙️ Designed relational models using Django ORM (User, Topic, Room, Message).

 - 🌐 Developed a REST API using Django REST Framework (DRF) for room data access.

 - 🎨 Built a responsive interface using Bootstrap templates for smooth user experience.

 - 🔒 Applied authorization checks to restrict edit/delete to room hosts.


 
---

## 🛠️ Tech Stack

### Backend :
 - Python
 - Django 

### Frontend :
 - HTML
 - CSS
 - Bootstrap 

### Database : 
 - SQLite (MySQL supported)

### Auth : 
 - Django Built-in Auth

### API : 
 - Django REST Framework (DRF)

### ORM : 
 - Django ORM



--- 



## 🧠 System Design

- **User** – Authentication & ownership  
- **Topic** – Categorizes study rooms  
- **Room** – Discussion spaces  
- **Message** – Real-time interaction within rooms  

Relational models are designed using **Django ORM** for clean and scalable data handling.


---


## 🌐 REST API

A RESTful API is implemented using **Django REST Framework (DRF)** to expose room data for future frontend (React) or mobile app integration.


---


## 📂 Project Structure

study-bud/
│
├── base/
│   ├── api/
│   ├── migrations/
│   ├── templates
│   │       ├── activity_component.html
│   │       ├── activity.html
│   │       ├── delete.html
│   │       ├── feed_component.html
│   │       ├── home.html
│   │       ├── login_register.html
│   │       ├── profile.html
│   │       ├── room_form.html
│   │       ├── room.html
│   │       ├── topics_component.html
│   │       ├── topics.html
│   │       └── update_user.html
│   │
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── static/
│   ├── images/
│   │   └── rooms/
│   │       └── images
│   ├── js/
│   └── styles/
│       ├── main.css
│       └── style.css
│
├── studybud/
│   ├── settings.py
│   └── urls.py
│
├── templates/
│   ├── main.html
│   └── navbar.html
│
├── env/
│
├── requirements.txt
├── README.md
└── .gitignore

---

