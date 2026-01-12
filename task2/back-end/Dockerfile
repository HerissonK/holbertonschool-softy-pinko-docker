# Is based on the latest ubuntu
FROM ubuntu:latest

# Update APT using apt-get update
RUN apt-get update

# Upgrade currently installed software through APT using apt-get upgrade -y
RUN apt-get upgrade -y

# Install python3 and pip3
RUN apt-get install -y python3 python3-pip

# Install Flask using pip3
RUN pip3 install flask --break-system-packages

# Set the working directory to /app
WORKDIR /app

# Copy the contents of the current directory to /app in the container
COPY . /app

# Expose port 5000 for the Flask application
EXPOSE 5252

# Once built, you can run the Docker image in a container and it will echo “Hello, World!” on the terminal.
CMD ["python3", "api.py"]  
