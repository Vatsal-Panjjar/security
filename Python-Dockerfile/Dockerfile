FROM python:3.12-alpine
WORKDIR /app
RUN addgroup -S app && adduser -S app -G app
COPY . .

USER app
CMD ["python", "app.py"]


