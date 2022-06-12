web: gunicorn todo_project.wsgi --log-file - --log-level debug
python manage.py collectstatic --noinput
python manage.py migrate