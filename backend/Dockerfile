FROM python:3.12.1-alpine3.19

WORKDIR /app

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
ENV SERVER_PORT=8080

CMD ["python3", "app.py"]