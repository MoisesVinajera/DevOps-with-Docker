# Exercise 1.11: Spring

Create a Dockerfile for an old Java Spring project: GitHub page

The setup should be straightforward with the README instructions. Tips to get you started:

Use openjdk image FROM openjdk:_tag_ to get Java instead of installing it manually. Pick the tag by using the README and Docker Hub page.

You've completed the exercise when you see a 'Success' message in your browser.

Submit the Dockerfile you used to run the container.

## Steps

- docker build . -t spring-project
- docker run -p 8080:8080 spring-project

## Results

![Exercise 1.11](Exercise_1.11.png)
