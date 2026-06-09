FROM python:3.10
WORKDIR /app
RUN groupadd -r app && useradd -r -g app app
COPY . .

USER app
CMD ["python", "app.py"]


