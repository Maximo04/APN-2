FROM python:3.6-alpine3.10

WORKDIR /app

COPY requirements.txt /app
RUN pip install -r requirements.txt
# Ejercicio 5> Agregar al Dockerfile en ./app  la aplicación de linux "nano"

RUN apk update
RUN apk add nano

COPY app.py /app

EXPOSE 5000

CMD python app.py

