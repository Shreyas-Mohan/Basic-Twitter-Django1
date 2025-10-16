# Twitter Django Clone

A simple Twitter-like web application built with Django. Users can register, log in, create tweets (with optional photos), edit, and delete their own tweets.

## Features

- User registration and authentication
- Create, edit, and delete tweets
- Upload photos with tweets
- Responsive Bootstrap UI

## Project Structure

```
twitter_dj/
├── manage.py
├── db.sqlite3
├── tweet/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│   └── templates/
│       └── tweet/
│           ├── tweet_list.html
│           ├── tweet_form.html
│           ├── tweet_delete_confirm.html
│           └── index.html
├── templates/
│   ├── layout.html
│   └── registration/
│       ├── login.html
│       ├── logout.html
│       └── register.html
├── static/
├── media/
└── twitter_dj/
    ├── settings.py
    ├── urls.py
    ├── wsgi.py
    └── asgi.py
```

## Setup Instructions

1. **Clone the repository**  
   `git clone <repo-url>`

2. **Install dependencies**  
   `pip install django`

3. **Apply migrations**  
   `python manage.py migrate`

4. **Create a superuser (optional)**  
   `python manage.py createsuperuser`

5. **Run the development server**  
   `python manage.py runserver`

6. **Access the app**  
   Open [http://127.0.0.1:8000/tweet/](http://127.0.0.1:8000/tweet/) in your browser.

## License

This project is for educational purposes.