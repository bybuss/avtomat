FROM python:3.12.0-slim

WORKDIR /app
COPY . /app

RUN pip install -r req.txt

CMD python manage.py runserver 0.0.0.0:8000
