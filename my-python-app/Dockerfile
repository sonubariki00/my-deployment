# Use the official Python image as the base image
FROM python:3.9-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the Python application files to the working directory
COPY app.py .

# Install Flask and any other dependencies
RUN pip install flask

# Expose port 8000
EXPOSE 8000

# Set the default command to run when the container starts
CMD ["python", "app.py"]
