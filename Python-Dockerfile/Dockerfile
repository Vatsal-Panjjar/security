FROM python:3.12-alpine
WORKDIR /app
RUN addgroup -r app && adduser -r -g app app
COPY . .

USER app
CMD ["python", "app.py"]


