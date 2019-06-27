## Introduction
This is a simple Todo application 
Django - Django REST Framework (for API CRUD operations) - React.

## Requirements
* Python3
* Pipenv

## Getting started
1. Clone the project to your machine 
```[git clone https://github.com/Jordanirabor/django-todo-react]```
2. Navigate into the diretory ```[cd django-todo-react]```
3. Source the virtual environment ```[pipenv shell]```
4. Install the dependencies ```[pipenv install]```
5. Navigate into the frontend directory ```[cd frontend]```
5. Install the dependencies ```[npm install]```

## Run the application
You will need two terminals pointed to the frontend and backend directories to start the servers for this application.

1. Backend server
```[cd backend]```  
```[python manage.py runserver]``` 
(You have to run this command while you are sourced into the virtual environment)
2. Frontend development server
```[cd frontend]```   
```[yarn start]``` 
(This will start the frontend on the adddress [localhost:3000](http://localhost:3000))

## Built With
* [React](https://reactjs.org) - A progressive JavaScript framework.
* [Python](https://www.python.org/) - A programming language that lets you work quickly and integrate systems more effectively.
* [Django](http://djangoproject.org/) - A high-level Python Web framework that encourages rapid development and clean, pragmatic design.