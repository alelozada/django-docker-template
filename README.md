# Django with Docker Template

1. Install a virtual enviroment
    
    py pip install --upgrade pip && py -m venv .venv
    
2. Created a requirements.txt

    add requests inside the file
    add the Django version inside the file (Django==3.2 for example)
    
3. Open the virtual environment

  - (Windows 11)
    .venv/Scripts/activate
    
4. Install dependencies from requirements.txt file

    pip install -r requirements.txt
    
5. Initialize the Django project

    django-admin startproject app
    
6. Install the core in the projects

    py app/manage.py startapp core
    
7. Created a dockerfile in the root and add the instructions, run:
    
    docker build .

8. Created a docker-compose.yaml file, run:
    
    docker-compose build

9. Up Django with Docker, run:
    
    docker-compose up
