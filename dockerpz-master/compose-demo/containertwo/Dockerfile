FROM python:3.9-alpine

WORKDIR /polls2

COPY . .

RUN pip install --no-cache-dir -r requirements.txt
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]


EXPOSE 8001
