web: gunicorn main_service.wsgi --log-file -
worker: celery -A main_service worker --loglevel=info
