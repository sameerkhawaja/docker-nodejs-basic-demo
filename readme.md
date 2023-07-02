Create the docker image with
`docker build -t <username>/<appname>:<version> .`

Get the imagename from Docker desktop or from the command
`docker images`

Run the docker container with the image we just made use
`docker run -p 5000:8080 <image_name>`

The app will be exposed on localhost:5000

create volumes with
`docker volume create <volume-name>`