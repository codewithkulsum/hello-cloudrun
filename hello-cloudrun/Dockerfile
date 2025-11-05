# Use a lightweight Python image
FROM gcr.io/google-appengine/python:latest
WORKDIR /app
COPY . .
RUN pip install flask
CMD ["python", "main.py"]
