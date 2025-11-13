FROM python:3.12-alpine
WORKDIR /app
COPY dependencias.txt .
RUN pip install --no-cache-dir -r dependencias.txt
COPY app.py .
EXPOSE 5000
CMD ["python", "app.py"]
