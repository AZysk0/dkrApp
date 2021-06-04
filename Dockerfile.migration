FROM python:3.8
EXPOSE 8000
WORKDIR D:/1KPI/WEB 4term/blog
COPY requirements.txt requirements.txt 
RUN ["pip", "install", "-r", "requirements.txt"]
COPY . .
ENTRYPOINT ["python", "manage.py", "runserver", "0.0.0.0:8000"]
