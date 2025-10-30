# 🐦 Chirper — A Mini Twitter Clone using Django

**Chirper** is a simple Django-based web application that allows users to register, log in, and share short posts (tweets) with optional images.  
It’s designed as a beginner-friendly project to understand how authentication, CRUD operations, and templates work in Django.

---

## 🚀 Features

- 👤 **User Authentication**
  - Register new users
  - Login & logout functionality
- 📝 **Tweet Management**
  - Create, edit, and delete tweets
  - Attach images to tweets
- 🔍 **Search**
  - Search tweets by content or username
- 🎨 **UI**
  - Responsive design with Bootstrap
  - Simple and clean layout
- 🔒 **Access Control**
  - Only logged-in users can create, edit, or delete tweets

---

## 🛠️ Tech Stack

| Component  | Technology |
|-------------|-------------|
| **Frontend** | HTML, CSS, Bootstrap |
| **Backend** | Django 5.x |
| **Database** | SQLite (default) |
| **Language** | Python 3.x |

---

## ⚙️ Setup Instructions
```bash
### 1️⃣ Clone the repository
git clone https://github.com/Viveksi-Taksali-27/Chirper.git
cd Chirper
```
```bash
### 2️⃣ Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate       # On Windows
### or
source venv/bin/activate    # On macOS/Linux
```
```bash
### 3️⃣ Install dependencies
pip install django
```
```bash
### 4️⃣ Apply migrations
python manage.py migrate
```
```bash
### 5️⃣ Run the development server
python manage.py runserver
```
```bash
Then open your browser and visit 👉
http://127.0.0.1:8000/
```

## 📁 Project Structure
```bash
Chirper/
├── Chirper/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
│
├── tweet/
│   ├── migrations/
│   ├── templates/
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── templates/
│   ├── layout.html
│   ├── index.html
│   ├── tweet_list.html
│   ├── tweet_form.html
│   ├── tweet_confirm_delete.html
│   └── registration/
│       ├── login.html
│       ├── logged_out.html
│       └── register.html
│
├── media/
│   └── photos/
│
├── manage.py
├── db.sqlite3
└── .gitignore
```
## 🧩 How It Works

Users register using a simple signup form.

After login, they can post tweets with text or images.

Tweets are listed on the homepage in reverse chronological order.

Users can edit or delete only their own tweets.

Search bar allows filtering tweets by text or username.

##📸 Screenshots

![🖼️ Home Page](C:\Users\vinit\OneDrive\Pictures\Screenshots 1)

![📝 Tweet Creation Form](C:\Users\vinit\OneDrive\Pictures\Screenshots 1)

![🔍 Search Results Page](C:\Users\vinit\OneDrive\Pictures\Screenshots 1)


## 💡 Future Enhancements

User profile pages with bio & followers

Like & comment system

Pagination for tweet feed

Dark/light mode toggle

## 👩‍💻 Author

Viveksi Taksali
📍 GitHub: Viveksi-Taksali-27


---

## ✅ **Next step:**  
Just open your project folder → create a new file named **`README.md`** → paste the above content → save → run these commands:

```bash
git add README.md
git commit -m "Added project README"
git push origin main
```
