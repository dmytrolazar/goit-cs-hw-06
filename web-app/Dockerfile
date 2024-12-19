FROM python:3.13-slim

WORKDIR /web-app

COPY . /web-app

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 3000
EXPOSE 5000

CMD ["python", "main.py"]
