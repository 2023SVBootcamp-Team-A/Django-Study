FROM python:3.9.0

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

WORKDIR /backend
COPY requirements.txt /backend/

RUN pip install --upgrade pip
RUN pip install -r requirements.txt --no-cache-dir

COPY . /backend