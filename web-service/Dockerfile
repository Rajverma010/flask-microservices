FROM python:3.11-slim
WORKDIR /app
COPY requierment.txt .
RUN pip install --no-cache-dir -r requierment.txt
COPY . .
EXPOSE 5000
CMD ["python3", "app.py"]
