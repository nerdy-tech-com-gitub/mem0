FROM python:3.13.5-slim

WORKDIR /app

COPY requirements.txt /app

RUN pip install -r requirements.txt

COPY . /app

CMD ["python", "app.py"]
