# Use the official Python base image
FROM python:3.9-slim

# Make main folder
RUN mkdir /app

# Set the working directory in the container
WORKDIR /app

# add app folder
ADD . /app/

# Install Flask and other dependencies
RUN pip install -r requirements.txt

# Expose the port on which the Flask app will run
EXPOSE 5000

# Define the command to run the Flask app when the container starts
CMD ["python", "app.py/main.py"]