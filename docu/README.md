First project - myfirstimage:1

Created a file called Dockerfile - needs to be this format
I then pulled down an nginx container - FROM nginx:latest


// In Docker File

FROM nginx:latest

CMD echo "Hello World"

// CMD is command and echo is print for Docker



In terminal, to build an image - docker build . -t myfirstimage:1
// . scans the file for Dockerfile
// -t is title of image
// myfirstimage:1 - [name]:[tag]

Then to retreive image - docker run myfirstimage:1 
// This will print Hello World



For first challenger // ref: com.docker.devenvironments.code
cd to challenge 1 

// In Docker File

FROM alpine:latest

CMD echo "Hello from Alpine"

// CMD is command and echo is print for Docker


Build the image - docker build . -t "myalpinetest:2020" 

Then to retreive image - docker run myalpinetest:2020
// This will print Hello from Alpine