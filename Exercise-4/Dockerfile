# Use official lightweight Python image
FROM python:3.9-slim

# Set working directory in container
WORKDIR /app

# Copy requirements file and application code
COPY requirements.txt .
COPY app.py .

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 5001 for Flask API
EXPOSE 5001

# Command to run application
CMD ["python", "app.py"]
