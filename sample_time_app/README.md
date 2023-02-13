Sample App

Sample Python Flask application to showcase the steps of building and running a web server with Docker.

Docker: https://www.docker.com/
Flask documentation: https://flask.palletsprojects.com/en/1.1.x/


Build an image:
docker build -t yc6380/sample-time-app:latest .

Run:
docker run -d  --name sample-time-app -p 8080:8080 -it yc6380/sample-time-app