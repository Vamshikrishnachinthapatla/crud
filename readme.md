# Student Records Management System

A full-stack web application built using **Python** and **Django** to manage student records. This application supports full **CRUD (Create, Read, Update, Delete)** operations and provides user feedback after each action to enhance user experience.

## 🚀 Features

- Add new student records
- View a list of all students
- Update student details
- Delete student records
- Clean and user-friendly interface
- Instant feedback after each user action
- Built using Django's built-in ORM for efficient database interaction

## 🛠️ Technologies Used

- **Backend**: Python, Django
- **Frontend**: HTML, CSS (optional: Bootstrap for styling)
- **Database**: SQLite (default for Django, easily replaceable with PostgreSQL or others)
- **Templating**: Django Templates

## 💡 How It Works

1. Users can add new student records through a form.
2. A dashboard lists all existing students with options to edit or delete.
3. Each operation gives clear feedback (success or error messages).
4. The interface is designed to be intuitive and easy to navigate.

## 📦 Installation


1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-crud-app.git
   cd student-crud-app
   
2. Create a virtual environment and activate it:

  '''bash
  
  python -m venv venv
  source venv/bin/activate  # On Windows: venv\Scripts\activate
  

3. Install dependencies:
   
  '''bash
  
  pip install -r requirements.txt
  

4. Run migrations:
   
  '''bash
  
  python manage.py migrate
  

5. Start the development server:

   '''bash
   
   python manage.py runserver
   
   
