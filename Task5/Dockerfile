FROM python:3.9.3-alpine

WORKDIR /app

COPY . .

RUN pip3 install -r requirements.txt

EXPOSE 5000 

CMD ["python", "app.py"]
