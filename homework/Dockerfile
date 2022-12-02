FROM python

ENV PYTHONDONTWRITEBYTECODE=1

ENV PYTHONUNBUFFERED=1

WORKDIR /app

COPY . .

RUN pip install django
RUN pip install python-decouple

EXPOSE 80

CMD ["python", "manage.py", "runserver", "0.0.0.0:8090"]