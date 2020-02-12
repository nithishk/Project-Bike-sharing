# Project-Bike-sharing


Neural Network developed during my Deep Learning Fundamentals Nanodegree at Udacity 2020. In this project, I created a simple neural network to use it to predict bike rental ridership 


# Getting Started 

In this project, my task is to build a neural network from scratch to carry out a prediction problem on a real dataset! By building a neural network from the ground up. This Bike-Sharing-Dataset has the number of riders for each hour of each day from January 1 2011 to December 31 2012. The number of riders is split between casual and registered, summed up in the cnt column. You can see the first few rows of the data above.

Below is a plot showing the number of bike riders over the first 10 days or so in the data set. (Some days don't have exactly 24 entries in the data set, so it's not exactly 10 days.) You can see the hourly rentals here. This data is pretty complicated! The weekends have lower over all ridership and there are spikes when people are biking to and from work during the week. Looking at the data above, we also have information about temperature, humidity, and windspeed, all of these likely affecting the number of riders. You'll be trying to capture all this with your model.

![Image of Yaktocat](https://github.com/nithishk/Project-Bike-sharing/blob/master/assets/1.JPG)


# Prerequisites 

Thinks you have to install or installed on your working machine:

- Python 3.7
- Numpy (win-64 v1.15.4)
- Pandas (win-64 v0.23.4)
- Matplotlib (win-64 v3.0.2)
- Jupyter Notebook
- PyTorch (win-64 v0.4.1)


# Jupyter Notebook

- Your_first_neural_network.ipynb

This jupyter notebook describe the whole project from udacity, from the beginning to the end.


# Running the project

The whole project is located in the jupyter notebook file Your_first_neural_network.ipynb and it's include the training an the prediction part. The neural network is implemented in the file my_answer.py and used from the jupyter notebook.


# Parameters of training

To change to interations, the amount of hidden notes and some other parameters for the neural network, you can adapt these global constants inside the python file my_answer.py and watch the results.


#########################################################
# Set your hyperparameters here
##########################################################

  iterations      = 6000   
  learning_rate   = 0.65       
  hidden_nodes    = 12        
  output_nodes    = 1      


# Checkout the training results


 Progress: 100.0% ... Training loss: 0.054 ... Validation loss: 0.125

See the visual results over iteration 

![Image of Yaktocat](https://github.com/nithishk/Project-Bike-sharing/blob/master/assets/2.JPG)

# Checkout the prediction results


I use the test data to show how well the neural network is modeling the data.


![Image of Yaktocat](https://github.com/nithishk/Project-Bike-sharing/blob/master/assets/3.JPG)


# Author

- Nithish Kalakonda


# License 

[MIT](https://choosealicense.com/licenses/mit/).




