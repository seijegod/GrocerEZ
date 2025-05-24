GrocerEZ

GrocerEZ is a Django-based web application designed to simplify grocery browsing and management. Users can register, log in, and explore a categorized list of groceries such as fruits, vegetables, meat, and beverages, complete with images and detailed variants.

 Features

- ✅ User Registration and Login System
- ✅ Dynamic Product Categories with Images
- ✅ Filter and View Product Variants (e.g., different types of fruits)
- ✅ Responsive UI (desktop + mobile)
- ✅ Protected Routes with Django Authentication

 Project Structure

GrocerEZ/
├── main/
│   ├── static/
│   │   └── main/
│   │       ├── Fruits_Images/
│   │       └── [other static folders]
│   ├── templates/
│   │   └── main/
│   │       ├── base.html
│   │       ├── login.html
│   │       ├── register.html
│   │       └── dashboard.html
│   ├── views.py
│   ├── urls.py
│   ├── models.py
├── GrocerEZ/
│   ├── settings.py
│   └── urls.py
└── manage.py

 Setup Instructions

1. Clone the repository
   git clone https://github.com/Cyzeros/grocerez.git
   cd grocerez

2. Create a virtual environment
   python -m venv env

   Activate it:
   - On Windows:
     env\Scripts\activate
   - On Mac/Linux:
     source env/bin/activate

3. Install dependencies
   pip install -r requirements.txt

4. Apply migrations
   python manage.py migrate

5. Run the development server
   python manage.py runserver

6. Open in your browser
   http://127.0.0.1:8000

🔐 Credentials for Demo (Optional)

You can create a superuser to access the admin panel:
   python manage.py createsuperuser

🖼️ Screenshots
  In Screenshots_GrocerEZ



🛡️ Security Features

- Passwords are hashed using Django's built-in system
- Routes are protected with @login_required
- User data is only accessible after login

🤝 Team Members

- Front-End Designer: 
- Back-End Developer: 
- Database Manager: 
- Authentication & Security: 
- Project Coordinator: 

📜 License

This project is licensed under the MIT License.



Made with by Team GrocerEZ
