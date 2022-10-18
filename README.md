# CMPUT404Project

## Resources Used:  
Tutorials used for user authentication
 - [Kolawole, M. (2021). FullStack React & Django Authentication : Django REST ,TypeScript, Axios, Redux & React Router. DEV.](https://dev.to/koladev/django-rest-authentication-cmh)
 - 
## Setting up environment

### Backend
    >> virtualenv venv
    >> .\venv\Scripts\activate  
    >> pip install -r requirements.txt
    >> python manage.py runserver

### Frontend
    >> yarn install
    >> yarn start

### Endpoints
<details>
<summary>://service/authors/</summary>
<br>
{
    "type": "authors",      
    "items":[
        {
            "type":"author",
            "id":"http://127.0.0.1:5454/authors/1d698d25ff008f7538453c120f581471",
            "url":"http://127.0.0.1:5454/authors/1d698d25ff008f7538453c120f581471",
            "host":"http://127.0.0.1:5454/",
            "displayName":"Greg Johnson",
            "github": "http://github.com/gjohnson",
            "profileImage": "https://i.imgur.com/k7XVwpB.jpeg"
        },
        {
            "type":"author",
            "id":"http://127.0.0.1:5454/authors/9de17f29c12e8f97bcbbd34cc908f1baba40658e",
            "host":"http://127.0.0.1:5454/",
            "displayName":"Lara Croft",
            "url":"http://127.0.0.1:5454/authors/9de17f29c12e8f97bcbbd34cc908f1baba40658e",
            "github": "http://github.com/laracroft",
            "profileImage": "https://i.imgur.com/k7XVwpB.jpeg"
        }
    ]
}
</details>
