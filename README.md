 # Django Todo Application
Step1:
Folder Structure :
todo_project/
├── todo/
│   ├── migrations/
│   ├── templates/
│   │   ├── todo/
│   │       ├── task_list.html
│   │       ├── add_task.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   ├── static/ (if used)
│       ├── css/
│       ├── js/
├── manage.py
├── db.sqlite3
├── requirements.txt
├── README.md


* Description : 
This is a simple Todo app built using Django. You can add tasks, view the task list, and mark tasks as completed.

* Setup :
1. Clone the repository: `git clone https://github.com/AfsanaAkterMitu/todo_project.git `
2. Navigate to the project directory: `cd todo_project`
3. Install dependencies: `pip install -r requirements.txt`
4. Run migrations: `python manage.py migrate`
5. Start the server: `python manage.py runserver`

* Features : 
- Add new tasks
- View task list
- Mark tasks as completed


Step 2: Create a Virtual Environment
python -m venv venv
venv\Scripts\activate 


Step 3: Install Dependencies
pip install -r requirements.txt


Step 4: Run Migrations
python manage.py migrate


Step 5: Start the Development Server
python manage.py runserver


Step 6: Access the Application
Open your browser and go to http://127.0.0.1:8000/.
