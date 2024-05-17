# Car-traffic-Ganna
## Description ##
This is a demo project for the data science for business course. The aim is to demonstrate how it is possible to integrate computer vision techniques such as YOLO object detection in a web application.

## How to run the app ##

```
docker build --tag python-docker .          # Build the image
docker run -it python-docker /bin/bash      # Debug docker build issues
docker run -d -p 8080:8080 python-docker    # Run the container
docker ps                                   # Check if the container is running
docker logs xxxxxxx                         # Logs in case of error
```

## Results ##
Discussion on the obtained results