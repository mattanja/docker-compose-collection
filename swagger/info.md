
https://github.com/swagger-api/swagger-editor

Running the image from DockerHub

To use this, run the following:

docker pull swaggerapi/swagger-editor
docker run -d -p 80:8080 swaggerapi/swagger-editor

This will run Swagger Editor (in detached mode) on port 80 on your machine, so you can open it by navigating to http://localhost in your browser.
