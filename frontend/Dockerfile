# Use the official Python image as base
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the application files into the container
COPY . .

# Install dependencies
RUN echo "Installing dependencies..." && \
    pip install --no-cache-dir -r requirements.txt

# Print a message
RUN echo "Dockerfile is being executed..."

# Expose the port on which the application will run
EXPOSE 8000

# Command to run the application
CMD ["python", "app.py"]
