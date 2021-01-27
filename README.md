# BikeSharing

Bike sharing project from Udacity Deep Learning nanodegree. I made a simple neural network model to predict daily bike rental ridership.


## About the project

Bike-Sharing-Dataset has the number of riders for each hour of each day from January 1 2011 to December 31 2012. The number of riders is split between casual and registered, summed up in the cnt column. You can see the first few rows of the data above.

Below is a plot showing the number of bike riders over the first 10 days or so in the data set. (Some days don't have exactly 24 entries in the data set, so it's not exactly 10 days.) You can see the hourly rentals here. This data is pretty complicated! The weekends have lower over all ridership and there are spikes when people are biking to and from work during the week. Looking at the data above, we also have information about temperature, humidity, and windspeed, all of these likely affecting the number of riders. You'll be trying to capture all this with your model.


<img src="https://github.com/Shahrullo/BikeSharing/tree/main/images/data_overview.PNG" width="100">


### Prerequisites

Thinks you have to install or installed on your working machine:

* Python 3.7
* Numpy (win-64 v1.15.4)
* Pandas (win-64 v0.23.4)
* Matplotlib (win-64 v3.0.2)
* Jupyter Notebook
* Torchvision (win-64 v0.2.1)
* PyTorch (win-64 v0.4.1)

### Environment: 
* [Anaconda](https://www.anaconda.com/download/)

## Jupyter Notebook 
* `BikeSharing.ipynb`

The jupyter notebook describes the whole project from udacity. You can find the whole description inside the notebook.

### Training 

To change to interations, the amount of hidden notes and some other parameters for the neural network, you can adapt these global constants inside the python file `answers.py` and watch the results.

```python
#########################################################
# Set your hyperparameters here
##########################################################
iterations = 25000
learning_rate = 0.25
hidden_nodes = 25
output_nodes = 1
```

I got my best results with these values of parameters.
