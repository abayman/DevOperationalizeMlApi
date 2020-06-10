
[![CircleCI](https://circleci.com/gh/abayman/DevOperationalizeMlApi.svg?style=svg)](https://circleci.com/gh/abayman/DevOperationalizeMlApi)

# Udacity Cloud DevOps Engineer Nanodegree Project: Operationalize a machine learning API
Microservice Project

## Project Overview:
In this project, we use a pre-trained sklearn model that can predict housing prices in Boston.

### Tasks:
* Test project code using linting
* Complete a Dockerfile to containerize this application
* Deploy containerized application using Docker and make a prediction
* Configure Kubernetes and create a Kubernetes cluster
* Deploy a container using Kubernetes and make a prediction
* Upload a complete Github repo with CircleCI to indicate the code has been tested



---
## Getting Started
### Setup the Environment

* Create a virtualenv and activate it
```
python3 -m venv <venv_name>
source <venv_name>/bin/activate
```
* Run `make install` to install the necessary dependencies
* Install docker from the official sources
* Use hadolint github documentation to build the linting tool
* Run `make lint` to lint the Dockerfile

### Running `app.py`

1. Run in Docker:  `sh run_docker.sh`
2. Run in Kubernetes:  `sh run_kubernetes.sh`


### Kubernetes Steps

* Install VirtualBox
* Install kubectl via `sudo install minikube`
* start kube via `minikube start`
* Create flask app in the container
* Run via `kubectl run` or the file via `sh run_kubernetes.sh`
