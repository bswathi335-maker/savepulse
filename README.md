# savepulse
A featured e-commerce web application built with Python, Django, and SQLlite

## 🚀 Live Demo
 http://127.0.0.1:8000/   link to just the working developement server
 (do check and post all improvements and feedback in the comments)
 
## ✨ Features
- **User Authentication & Authorization:** Sign up, login, logout, password reset.
- **Track price:** Browse products and upload the product for which you want the lowest price to be tracked.
- **UserProfile** Add/remove items, update target price.
- **User Alert:** Users get automated notifications when the price drops for the targeted product.
- **Admin Panel:** Full-featured admin to manage products, prices, and users.
- **Responsive Design:** Works on desktop and mobile.
- 
  ## 🛠️ Tech Stack
- **Backend:** Python, Django, Django REST Framework 
- **Frontend:** HTML, JavaScript
- **Database:**  SQLite
- **Other:** Git, GitHub

  
## 🗂️ Installation & Setup
1. Clone the repo: `git clone https://github.com/your-username/your-repo-name.git`
2. Create a virtual environment: `python -m venv venv`
3. Activate the environment: `source venv/bin/activate` (Linux/Mac) or `venv\Scripts\activate` (Windows)
4. Install dependencies: `pip install -r requirements.txt`
5. Set up environment variables (see `.env.example`).
6. Run migrations: `python manage.py migrate`
7. Create a superuser: `python manage.py createsuperuser`
8. Run the server: `python manage.py runserver`

