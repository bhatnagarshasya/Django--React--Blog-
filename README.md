# react-django-blog-app

## Technologies
1. React
2. Tailwind CSS
3. Django 4.1.2
3. Django REST Framework


## Setting up the backend server
1. Clone the project
```bash
git clone https://github.com/bhatnagarshasya/Django-React-Blog.git
```
2. Go to the project directory (backend)
```bash
cd backend
```
3. Create a virtual environment and activate it (Windows)
```bash
python -m venv env
```
```bash
env\Scripts\activate
```
4. Install dependencies
```bash
pip install -r requirements.txt
```
5. Migrate
```bash
python manage.py migrate
```
6. Create admin/superuser
```bash
python manage.py createsuperuser
```
7. Finally run the project
```bash
python manage.py runserver
```
Now the project should be running on http://127.0.0.1:8000/

## Setting up the react app

**.env file content for backend url**
```
REACT_APP_BASE_URL = http://127.0.0.1:8000
```
run
```bash
cd frontend
npm install
npm start
```

## Credits
Dev by Shasya



