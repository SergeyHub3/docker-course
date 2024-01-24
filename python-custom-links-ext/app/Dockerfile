FROM python:alpine

WORKDIR /my/app

RUN pip install pymongo

COPY . .

CMD [ "python", "main.py" ]