FROM python:3.10-slim

WORKDIR /app

COPY ./examples/example.py ./

COPY ./requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
