# MongoDB Tutorial

## Aims:

- To learn the mongoDB tech and see if it will be applicable to applications I plan to make in the future.

## Implementation:

A simple Air BnB replica but for snakesssss...

- Snake BnB
    - Snake owners and their pet's can share their snake cages as seemlessly integrated snake travelling compartments. 

## Tools:

- Python 3.7.3 64-bit (download at `https://www.python.org/downloads/`)
- mongoDB (download at `https://www.mongodb.com/download-center/community`)
- mongoEngine (`pip install mongoengine` or `pip install requirements.txt` if pulling this repo)
- robo3t (download at `https://robomongo.org/download`)
- VS Code (download at `https://code.visualstudio.com/`)


 ################################################################################################################################################################################


 # Code

 The following is a high-level breakdown of all the code in this repository

 ## mongo_tutorial:

 This folder houses all of the code of the project.

- `requirements.txt`
    - The libraries used in this project.

- `program.py`
    - The main scripts which you should call to run the application.

- `program_guests.py`
    - The sub-script which handles behaviour of guests in the application.

- `program_hosts.py`
    - The sub-script which handles behaviour of hosts in the application.

## data:

This folder holds all of the code which manages the data objects of our application, for more information go and read the comments in the respective files.

- `bookings.py`
    - Class describing the booking object.

- `cages.py`
    - Class describing the cages object.

- `owners.py`
    - Class describing the owners object.

- `snakes.py`
    - Class describing the snakes object.

- `mongo_setup.py`
    - Class describing the mongo object.

## infrastructure:

This folder holds all of the code which manages the infrastructure objects of our application, for more information go and read the comments in the respective files.

- `state.py`
    - Function to reload a user account currently using the application.

- `switchlang.py`
    - Class describing the switching of functionality inside the application.

## services:

This folder holds all of the code which manages the service objects of our application, for more information go and read the comments in the respective files.

- `data_service.py`
    - This collection of functions controls the functionality of the application.

# Usage

## How-to:

- To run this application
    1. Pull the repo to a project in your chosen IDE.
    2. Go to the terminal and navigate to the project directory, install all of the requirements using `pip install requirements.txt`
    3. Go to the terminal and navigate to the project directory, once there run the application using `python3 program.py`

- Once you have the application running simply navigate the menu's by following the instructions on-screen.