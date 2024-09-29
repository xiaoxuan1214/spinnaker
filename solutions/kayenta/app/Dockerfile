FROM python:3.13.0rc2-slim

WORKDIR /
ENV SUCCESS_RATE=80 \
    FLASK_APP=app.py
STOPSIGNAL SIGINT
CMD ["python", "/app.py"]
RUN pip install flask prometheus_client
COPY app.py /app.py
