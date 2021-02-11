web: gunicorn ChatServerPlayground.wsgi
web2: daphne chat.asgi:routing:application --port $PORT --bind 0.0.0.0 -v2
worker: python manage.py runworker -v2
