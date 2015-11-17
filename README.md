# python-flask-gunicorn

source ve/bin/activate

gunicorn -w 2 -b 0.0.0.0:8080 app:app --daemon --graceful-timeout 300 --timeout 300