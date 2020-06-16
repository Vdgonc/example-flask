FROM python:3.8-alpine
WORKDIR /app
COPY ./requirements.txt /app
COPY ./src /app


RUN pip install -r requirements.txt
EXPOSE 3000

ENTRYPOINT [ "python", "main.py" ]