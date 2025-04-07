# quora_model_django

# 🧠 Quora Clone (Django)

A simple Quora-like question & answer platform built with Django, focusing on core functionality using Django Forms. Users can register, log in, post questions, answer others' questions, like answers, and log out.

---

## 🚀 Features

- User registration and login/logout
- Post questions
- View questions posted by others
- Answer questions
- Like answers
- Uses Django Forms for handling inputs
- Functional HTML pages (no front-end frameworks)

---

## 📂 Project Structure

quora_clone/ │ ├── core/ # Main app │ ├── migrations/ │ ├── templates/ # HTML templates │ │ ├── register.html │ │ ├── login.html │ │ ├── home.html │ │ ├── ask.html │ │ └── question_detail.html │ ├── admin.py │ ├── forms.py │ ├── models.py │ ├── urls.py │ └── views.py │ ├── quora_clone/ # Project settings │ ├── settings.py │ ├── urls.py │ └── wsgi.py │ └── manage.py

yaml
Copy
Edit

---

## ⚙️ Setup Instructions

### 1. Clone the repo
```bash
git clone https://github.com/your-username/quora-clone-django.git
cd quora-clone-django
2. Create & activate virtual environment (recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
3. Install dependencies
bash
Copy
Edit
pip install django
4. Apply migrations
bash
Copy
Edit
python manage.py makemigrations
python manage.py migrate
5. Create a superuser (optional)
bash
Copy
Edit
python manage.py createsuperuser
6. Run the development server
bash
Copy
Edit
python manage.py runserver
7. Open in browser
Visit: http://127.0.0.1:8000

🛠 Functionality Overview
Feature	URL
Register	/register/
Login	/login/
Logout	/logout/
Ask a Question	/ask/
View All Questions	/
View Specific Q&A	/question/<question_id>/
Like an Answer	/like/<answer_id>/
📃 License
This project is licensed under the MIT License.

🙌 Acknowledgements
Built for educational purposes and as a Django learning project.

yaml
Copy
Edit

---

Let me know if you want me to include instructions for deploying this on **Render**
