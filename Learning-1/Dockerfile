FROM ubuntu:latest
WORKDIR /app
COPY . /app
RUN apt-get update && apt-get install -y python3 python3-pip
RUN pip3 install -r requirements.txt
CMD ["python3", "app.py"]
EXPOSE 5000
# This Dockerfile sets up a basic Python application environment using Ubuntu as the base image.