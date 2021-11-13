# Food Delivery

# About
Food Delivery contains only professional and reliable software technologies like Python Django, Django REST framework and JWT social authentication. Now you can forget about specifically and expensive website templates and hard to fix SQL errors! Furthermore, Food Delivery provide localization and internationalization features.

# Easy restaurant management setup
1. Clone the GitHub repo in a separate folder:
```
git remote add origin https://github.com/kibomamoses/food-delivery-Django-backend-using-Baton.git

```
2. Go to the main directory of the project:
```
cd food-delivery-Django-backend-using-Baton
```
3. Install dependencies:
```
pip install -r requirements.txt
```
4. Create database migrations for each app:
```
python manage.py makemigrations
```
5. Apply database migrations:
```
python manage.py migrate
```
6. Create first superuser (admin profile), remember your credentials:
```
python manage.py createsuperuser
```
7. Run server on the localhost:
```
python manage.py runserver
```

# Requirements
Regular Meal CMS project has been written with the Python Django framework.

1. *Global*:  
  1.1. Django   
  1.2. Django REST Framework  

2. *Admin-panel*:  
  2.1. django-baton  
  2.2. django-admin-numeric-filter  
  2.3. django-filter  

3. *Internationalization and localization*:  
  3.1. django-modeltranslation  

4. *Django ORM Models*:  
  5.1. model_mommy  
  5.2. django-imagekit  

5. *Social authentication*:  
  5.1. djoser  
  5.2. social-auth-app-django  

6. *Extra*:  
  6.1. unidecode  
  6.2. markdown  
  6.3. coverage  
  6.4. pillow  


