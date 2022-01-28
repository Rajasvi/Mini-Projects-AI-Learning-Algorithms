CSE 251A | AI:Learning Algorithms
==============================

During this course, I worked on various Mini Projects exploring/experimenting with various ML algorithms. Details for individual projects can be found below:


## Mini Project 1: Prototype selection algorithm 
Nearest neighbor classification algorithm is slow for large datasets since every time it makes a prediction
it compares every single point in testing set with all the training data points. Therefore in order
to speed up the Nearest neighbor classification one of the strategy is to carefully select subset of
”prototypes” from training set which can give good classification performance. <br>
In this project I explore strategies for prototype-selection algorithm which are used by 1-NN model over MNIST data, bearing
in mind that the ultimate goal is good classification performance on test data.

## Project Organization

    ├── LICENSE
    ├── README.md                       <- The top-level README for developers using this project.
    ├── project 1
    │   ├── data      	  	             <- Data used for experiments
    │   └── report         		       <- Final submission report
    │   └── sandbox.ipynb               <- Main Code 
    │   └── problem_statement.pdf       <- Problem statement 

