FROM python:3.10-alpine

RUN apk add curl bash git

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python", "app.py"]
