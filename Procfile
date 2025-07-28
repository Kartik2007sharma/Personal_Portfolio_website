release: cd portfolio && python manage.py collectstatic --noinput

web: cd portfolio && gunicorn portfolio.wsgi:application