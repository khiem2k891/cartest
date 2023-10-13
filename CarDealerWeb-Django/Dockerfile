FROM python:3.8.2
LABEL authors="Khiem"
RUN mkdir -p /app
WORKDIR /app
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1
COPY . /app
RUN pip install -r /app/requirements.txt
