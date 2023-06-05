# Current Time in Moscow

## Overview
This is a simple Python web application that displays the current time in Moscow. It uses the Flask web framework and the datetime module to get the current time in the Europe/Moscow timezone. The time is displayed in a user-friendly format on a web page.

## Build
To build this application, you need to create a Python file with a main.py extension, for example, app.py. Then, copy the code in main.py to your file. Save the file and run it using the command python app.py in a terminal or command prompt. 
The application will start running on your local machine.

## Usage
To use the application, open a web browser and navigate to http://localhost:5000/. The current time in Moscow will be displayed on the web page. The time will be updated every time you refresh the page.

## Unit tests

I have written unit tests for the Python web application that displays the current time in Moscow. These tests ensure that the application is working as expected and help us catch any bugs early in the development process.

To run the unit tests, navigate to the directory where the `test_main.py` file is located and run the following command:
python test_main.py


Make sure that you have all the necessary dependencies installed, including Flask and any other modules that your application depends on.

If the tests pass successfully, you should see output similar to the following:

Ran 1 test in 0.001s

OK

## Git Actions CI

I have set up a continuous integration (CI) workflow using Git Actions to build and test our Python web application. The workflow has three steps: installing dependencies, running linters, and running unit tests.

To run the workflow, push changes to the `main` branch of the repository. The workflow will automatically be triggered and the steps will be run in order. Make sure that you have all the necessary dependencies installed, including Flask and any other modules that your application depends on.

I have also added Docker-related steps to our workflow to log in to a Docker registry, build a Docker image, and push the image to the registry. To use these steps, you will need to set up the `DOCKER_USERNAME` and `DOCKER_PASSWORD` secrets in your repository settings.

By following these best practices and including a Git Actions CI workflow in your project, I can ensure that my application is thoroughly tested and working as expected.
