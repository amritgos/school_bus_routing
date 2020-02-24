# Route Optimisation Algorithm  

## Install
This project requires Python3 and the following Python libraries installed:

NumPy
Pandas
matplotlib
scikit-learn
pulp
random
csv
geopy

You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

##Code
To implement the code run fnl_code.ipynb on Jupyter Notebook step by step after installing all the dependencies. 


## Data files
     bus_stop_dist.csv : bus stop distance matrix
     bus_stop_time.csv : bus stop time matrix
     cust_stop_mat.csv : customer to bus stop distance matrix
     bus_coord.npy : bus stop coordinates
     cp_coord.npy : customer coordinates

## Parameters
     w_dist_lim : walking distance limit
     cap_lim : capacity limit
     dist_lim : total distance limit
     time_lim : total time limit
## Output
     best_sol : Array with values as node index visited in the sequence of array. '0' denotes the ending of a route and starting of a new route
