# Use the official Python image as the base image
FROM python:3.9-slim

# Set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# Set the working directory
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install dependencies
RUN pip install --no-cache-dir --upgrade pip && \
    pip install --no-cache-dir flask redis gunicorn

# Expose the port the app runs on
EXPOSE 90

# Run the application with Gunicorn
CMD ["gunicorn", "-b", "0.0.0.0:90", "-w", "4", "app:app"]
