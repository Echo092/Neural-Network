# Neural-Network
## Short Discription
A comprehensive project focused on implementing a neural network using Python and relevant libraries. It covers the design, training, and evaluation of the model while providing insights into deployment strategies.
## Getting Started
This guide will help you set up the project on your local machine for development and testing. For production deployment instructions, see the "Deployment" section.
## Prerequisites
##### Before proceeding, ensure you have the following:

###### Anaconda: 
Install it by following this guide.

https://clouds.eos.ubc.ca/~phil/docs/problem_solving/01-Orientation/01.03-Installing-Anaconda-on-Windows.html
###### Required Libraries: 
Install dependencies using the following command:
###### pip install numpy pandas tensorflow matplotlib scikit-learn 
## Installation
Complete the setup by verifying that all tests pass successfully.

## Running the Tests
Execute the following commands to test the system functionality.
### Breakdown of Tests
#### 1. End-to-End Testing
These tests validate the complete pipeline, including data preprocessing, model training, and evaluation.
###### python test_script.py 
#### 2. Coding Style Checks
Ensure compliance with Python coding standards using:
###### flake8 <project_directory>  

## Deployment
To deploy the trained neural network in a live environment:

##### 1. Train and Save the Model
Run the following command to train the model and save it:
###### python train.py --save_model 

##### 2. Serve the Model via an API
Use a web framework like Flask or FastAPI:

###### python app.py  

## Author
Arun Prakash

## License
Project is licensed under MIT license.

## Acknowledgement
DATA1200 course assignment.