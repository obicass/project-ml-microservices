         ___        ______     ____ _                 _  ___  
        / \ \      / / ___|   / ___| | ___  _   _  __| |/ _ \ 
       / _ \ \ /\ / /\___ \  | |   | |/ _ \| | | |/ _` | (_) |
      / ___ \ V  V /  ___) | | |___| | (_) | |_| | (_| |\__, |
     /_/   \_\_/\_/  |____/   \____|_|\___/ \__,_|\__,_|  /_/ 
 ----------------------------------------------------------------- 


[![CircleCI](https://dl.circleci.com/status-badge/img/gh/obicass/project-ml-microservices/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/obicass/project-ml-microservices/tree/master)


The aim of this project is to deploy a Python Flask app, app.py, that provides housing price predictions through API calls. To achieve this, the following steps were followed:

Containerize the app by creating a Dockerfile.
Deploy the containerized app using Docker and Kubernetes for making predictions.
Integrate the code into CircleCI for testing.
To complete this project, a basic understanding of Python, Flask, and Docker is sufficient. Additionally, you will need the following tools:

An AWS account, Amazon Linux EC2 and Cloud9
A CircleCi account
A Docker Hub account
Minikube and Kubectl installed on the Linux instance
The project includes the following files:

app.py: A Python Flask app that serves housing price predictions via API calls.
Dockerfile: Instructions for building a Docker image of the app.
make_prediction.sh: A shell script that sends a request to the Flask app for a prediction.
Makefile: Commands for setting up and running the Docker container.
requirements.txt: Dependencies required to run the app.
