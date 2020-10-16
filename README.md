# ECE444-F2020-Lab4
Docker Lab 4
This repo is a clone of https://github.com/miguelgrinberg/flasky

### Building the Dockerfile

`docker build -t <repository_name>:latest`

### Running the Docker container

`docker run -it --name <repository_name> --rm -p 5000:5000 <repository_name`

## Docker Run Command
<img src="https://github.com/rlinwu/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/Screenshots/docker_run.PNG" width=75%>

## Browser
<img src="https://github.com/rlinwu/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/Screenshots/docker_browser.PNG" width=75%>   

## Docker Image
<img src="https://github.com/rlinwu/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/Screenshots/docker_img.PNG" width=75%>  


## Differences between Docker and Virtual Machine

A Docker container image contains all the software necessary to run a software project on, and a virtual machine is a seperate operating system that runs on your current operating system. A Docker container image is also a snapshot of your environment, and it also cannot be changed. On the other hand, a virtual machine can be changed.
