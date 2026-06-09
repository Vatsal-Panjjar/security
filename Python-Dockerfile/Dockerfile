FROM python:3.12-alpine
WORKDIR /app
RUN groupadd -r app && useradd -r -g app app
COPY . .

USER app
CMD ["python", "app.py"]


