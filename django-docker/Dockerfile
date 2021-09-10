FROM python:3.9-alpine
ENV PYTHONBUFFERED 1

WORKDIR /app
COPY requirement.txt .
RUN pip install -r requirement.txt
COPY . .
CMD python manage.py runserver 0.0.0.0:80