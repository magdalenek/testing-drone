FROM python:3.4-alpine
ADD . /app/code
WORKDIR /app/code
RUN pip install -r requirements.txt
CMD ["python", “app.py"]