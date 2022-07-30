# DRLND-project1-navigation

In this project agent is trained to collect bananas in unity enviroment

## Enviroment

State space in this enviroment has 37 dimentions and containts agents velocity, along with ray based perception of objects around agent's forward direction. Given this information agent has to collect yellow bananas and omit blue ones.

To complete this task agent has four possible actions

* 0 - move forward
* 1 - move backward
* 2 - turn left
* 3 - turn right

The task is solved when the average score of the agent in 100 consecutive episodes is 13 or higher.

## Setup

To run the code, either to train or check trained agent, clone the repository and install requirements using:

```bash
pip install -r requirements.txt
```

Python 3.6 is needed for some of the packages

Then download the unity enviorment from the link below and unzip it in into the cloned repository.

[Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)

[Mac](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)

[Windows(32-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)

[Windows(64-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

## Run

To run the code to train agent run first cells from Navigation.ipynb notebook
