# Dockerfile specifically for kubernetes
FROM python:3.9-slim

RUN pip install pipenv

COPY . .

RUN pipenv install
CMD ["./process-results.sh"]

