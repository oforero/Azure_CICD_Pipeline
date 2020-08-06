# Overview

This is a Web Service that uses a pretrained model to predict Boston house prices.
The web service is deployed to Azure as an App service.

## Project Plan

* Trello: https://trello.com/b/DglsTOf3/udacity-ci-cd
* Spred Sheet: https://docs.google.com/spreadsheets/d/1RVkXWyg3vh1xjo7_pgdA8kCZQgEEg9pqjFrYXtfy8wY/edit?usp=sharing

## Instructions

### Running the App Locally with Docker

To run the app locally you need to be running Docker. 
Go to the `flask-sklearn` directory and execute the script to start a container running the app:

```
$ cd flask-sklearn
$ ./run_docker.sh
```

![Run Docker](Screenshots/screenshot_1.png)

Open a new terminal, go to the same directory and execute the client call:

```
$ cd flask-sklearn
$ ./make_prediction.sh
```

You can adjust the prediction by editing the CURL call in that script.

![Run Docker](Screenshots/screenshot_2.png)

### Running the App in Azure

* Project running on Azure App Service

* Project cloned into Azure Cloud Shell

* Passing tests that are displayed after running the `make all` command from the `Makefile`

* Output of a test run

* Successful run of the project in Azure Pipelines

* Running Azure App Service

* Successful prediction from deployed flask app in Azure Cloud Shell> 

## Enhancements

<TODO: A short description of how to improve the project in the future>

## Demo 

<TODO: Add link Screencast on YouTube>


