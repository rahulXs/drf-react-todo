## drf-react-todo

An example codebase for developing simple REST APIs (backend) for todo application using django rest framework and connecting it to react frontend.

## Installation

### Backend
Create and activate virtualenv `todo`:

```bash
virtualenv todo
. ~/virtualenvs/todo/bin/activate
```

Install django and djangorestframework in virtualenv:

```bash
pip install django
pip install djangorestframework

# For CORS (Cross origin request sharing)
pip install django-cors-headers
```

### Frontend

Install `Node`

```bash
# Install node for linux
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/\
install.sh | bash

sudo apt install node
```

Use `npx` and `create-react-app` package for quickly setting up the frontend. Install `axios` package for making HTTP requests from react app.

```bash
npx create-react-app frontend

# Install axios
npm install axios
```


## Usage

```bash
# Start django server 
python manage.py runserver

# Start react app
npm start
```

## Reference
Book Django for APIs 3.1 by William S. Vincent 
