FROM python:3.7-buster

WORKDIR /flask-chat-app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

CMD ["python", "app.py"]

EXPOSE 8000

