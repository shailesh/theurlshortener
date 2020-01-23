##URL Shortener
An API service for shortening links programmatically.

**Tools:**

 - Django
 - Django Rest Framework
 - Ajax

**Demo:** [https://theurlshortener.herokuapp.com/](https://theurlshortener.herokuapp.com/)

**API:**
URL: `https://theurlshortener.herokuapp.com/api/shorten-url/`
Method: `POST`
Body:

```json
{
"url": "https://www.google.com/"
}
```

**Run:**

 - Clone the project
 - Create virtual env using python3 `virtualenv env --python=python3`
 - Activate env `source env/bin/activate`
 - Install required modules and lib `pip install requirements.txt` 
 - Run `python manage.py migrate` to migrate the schema to DB
 - Run local server: `python manage.py runserver` 
