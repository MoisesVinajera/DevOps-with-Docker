# Exercise 1.10: Ports open

In this exercise, we won't create a new Dockerfile.

The image devopsdockeruh/simple-web-service will start a web service in port 8080 when given the command "server". From 1.7 you should have an image ready for this. Use -p flag to access the contents with your browser. The output to your browser should be something like: { message: "You connected to the following path: ...

Submit your used commands for this exercise.

## Steps

- docker run -p 8080:8080 web-server

## Results

File text.log
![Exercise 1.10](Exercise_1.10.png)
