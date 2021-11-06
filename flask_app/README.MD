# Live Poll

Live Poll is simple web application written using Python packages and libraries.

## Installation requirements

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install dependencies.

```bash
click==8.0.3
colorama==0.4.4
Flask==2.0.2
itsdangerous==2.0.1
Jinja2==3.0.2
MarkupSafe==2.0.1
Werkzeug==2.0.2
```

## To execute application

```python
#CMD

> set FLASK_APP=livepoll
> set FLASK_ENV=development
# for initializing db
> flask init-db
# starting the server
> flask run

#Bash
$ export FLASK_APP=flaskr
$ export FLASK_ENV=development
# for initializing db
$ flask init-db
# starting the server
$ flask run
```

## Project Overview
- Developed using python programming language for backend and SQLite for database. 
- User authentication with login and register endpoints.
- User can create a new poll and vote.
- Used HTML, CSS for front end design.
- REST API and FLASK for back end.

## License
[MIT](https://choosealicense.com/licenses/mit/)