FROM python:3.7.2-slim

COPY . /app
WORKDIR /app

RUN pip3 install --upgrade pip
RUN pip3 install flask


ENTRYPOINT ["python3", "app.py"]

