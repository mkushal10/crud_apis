1. Install Virtual Environment
    → virtualenv venv

2. Activate Virtual Environment
    → source venv/bin/activate

3. Install Django
    → pip install django

4. Creating project
    → django-admin startproject mainproject .

5. Installing Django Rest Framework
    → pip install djangorestframework

6. Installing Core APIs
    → pip install coreapi

7. Automated generation of real Swagger/OpenAPI 2.0 schemas
    → pip install drf-yasg

8. Collecting Requirements
    → pip freeze > requirements.txt

9. Django model
    class Todo(models.Model):
        title = models.CharField(max_length = 100)
        body = models.CharField(max_length = 100)
        is_completed = models.BooleanField(default=False)
        date_created = models.DateField(auto_created=True)
        last_modified = models.DateField(auto_now=True)

        def __str___(self):
            return self.title

10. 