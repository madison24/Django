## Exercise 2.2: Django Project Set Up

### Learning Goals

- Describe the basic structure of a Django project
- Summarize the difference between projects and apps
- Create a Django project and run it locally
- Create a superuser for a Django web application

### Reflection Questions

1. Suppose you’re in an interview. The interviewer gives you their company’s website as an example, asking you to convert the website and its different parts into Django terms. How would you proceed? For this question, you can think about your dream company and look at their website for reference.

   - Taking Pinterest as an example, I would say the whole website/application would be an example of a Project in Django terms. While the Login, Messages, Notifications, Profile, and other features would be called Apps in Django.

2. In your own words, describe the steps you would take to deploy a basic Django application locally on your system.

   - To deploy a Django application locally I would first create a virtual environment by entering the `mkvirtualenv` command then install django with `pip install django`. Next, I'd create the project by entering `django-admin startproject` followed by the name of the project and to avoid confusion later on I would change the name of the root directory to src by going to the project folder in the terminal and entering `mv (project-name) src`. Next I would run migrations in the terminal by entering `python manage.py migrate` and run the server by entering `python manage.py runserver` and the application is deployed!

3. Do some research about the Django admin site and write down how you’d use it during your web application development.

   - Since Django admin is a GUI where users can Create, Read, Update, and Delete directly on the project, I would use it to add users and data to the database.
