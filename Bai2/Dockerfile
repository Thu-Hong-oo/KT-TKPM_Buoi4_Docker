# Dockerfile
FROM python:3.9

WORKDIR /app

# Sao chép các file vào container
COPY . /app

# Cài đặt các yêu cầu
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5000

CMD ["python", "app.py"]
