FROM python:3.11.0b4-slim-buster
WORKDIR /app
RUN groupadd -r app && useradd -r -g app app
COPY ..

USER app
CMD ["python", "app.py"]


