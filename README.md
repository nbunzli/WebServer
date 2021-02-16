Simple example of a webserver which uses the nginx docker image to host static html content.

Use the following commands to build and run the docker image.
```
docker build -t <TAG> .
docker run -p 80:80 -d <TAG>
```

Content can then be accessed at port 80 of the host machine.