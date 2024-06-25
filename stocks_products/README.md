# Django REST API with Docker

## Build and Run

### Build the Docker Image


docker build -t my_django_project .

## run container

docker run -d -p 8000:8000 my_django_project

## try http://localhost:8000