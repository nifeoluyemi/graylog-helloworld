FROM --platform=linux/amd64 python:3.9-alpine

WORKDIR /helloworld-flask

COPY requirements.txt ./
 
RUN pip install -r requirements.txt

COPY . .

EXPOSE 5000

CMD [ "python3", "run.py" ]