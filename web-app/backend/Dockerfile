# Use an official Python image as the base
FROM python:3.8-slim

# Set the working directory
WORKDIR /app

# Copy the requirements file and install dependencies
COPY requirements.txt .
RUN pip install -r requirements.txt

# Copy the app files
COPY . .

# Expose the port the app runs on
EXPOSE 5000

# Start the backend app
CMD ["python", "app.py"]
