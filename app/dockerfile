FROM python:latest
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
RUN pip install --upgrade flask werkzeug
EXPOSE 5000
CMD ["python", "app.py"]