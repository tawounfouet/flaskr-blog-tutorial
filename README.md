## Flaskr Blog application

This tutorial will walk you through creating a basic blog application called Flaskr. Users will be able to register, log in, create posts, and edit or delete their own posts. 

By the end, the project layout will look like this:

```text
├── flaskr/
│   ├── __init__.py
│   ├── db.py
│   ├── auth.py
│   ├── blog.py
│   ├── schema.sql
│   ├── templates/
│   │   ├── base.html
│   │   ├── auth/
│   │   │   ├── login.html
│   │   │   └── register.html
│   │   └── blog/
│   │       ├── create.html
│   │       ├── index.html 
│   │       └── update.html
│   └── static/
│       └── style.css
├── tests/
│   ├── conftest.py
│   ├── data.sql
│   ├── test_factory.py
│   ├── test_db.py
│   ├── test_auth.py
│   └── test_blog.py
├── .venv/
├── .gitignore
├── pyproject.toml
├── MANIFEST.in
├── README.md
├── requirements.txt
└── setup.py
```
