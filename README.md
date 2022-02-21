CSE 251A | AI:Learning Algorithms
==============================

During this course, I worked on various Mini Projects exploring/experimenting various ML algorithms. Please find below the details for individual projects:


## Mini Project 1: Prototype selection algorithm 
Nearest neighbor classification algorithm is slow for large datasets since every time it makes a prediction
it compares every single point in testing set with all the training data points. Therefore in order
to speed up the Nearest neighbor classification one of the strategy is to carefully select subset of
”prototypes” from training set which can give good classification performance. <br>
<br>
In this project I explore strategies for prototype-selection algorithm which are used by 1-NN model over MNIST data, bearing
in mind that the ultimate goal is good classification performance on test data. <br>
<br>
For more details, please check out the report: [<code>project 1/CSE_251A__Mini_Project_final.pdf</code>](https://github.com/Rajasvi/Mini-Projects-AI-Learning-Algorithms/blob/master/project%201/report.pdf).

## Mini Project 2: Coordinate Descent 
Considering standard unconstrained optimization problem of minimizing Loss funtion (L(w)) where L(·) is cost function
and w ∈ R^d, in this project we plan to explore different ways of solving such problems other than standard - gradient descent and stochastic gradient descent - which work under differentiability conditions on L(w). Rephrasing the problem in much simpler way I plan to propose a coordinate descent technique where we initialize a w, followed by repeated process of picking a coordinate i ∈{1,2,...,d} and updating the value of w_i with an aim to reduce the loss. 
<br>
Primarily, we focus on answering two questions: (a) Which coordinate to choose? (b) How to set the new value of w_i?
<br>
For more details, please check out the report: [<code>project 1/CSE_251A__Mini_Project_final.pdf</code>](https://github.com/Rajasvi/Mini-Projects-AI-Learning-Algorithms/blob/master/project%202/report.pdf).


## Project Organization

    ├── LICENSE
    ├── README.md                       <- The top-level README for developers using this project.
    ├── project 1
    │   ├── data                        <- Data used for experiments
    │   └── report                      <- Final submission report
    │   └── sandbox.ipynb               <- Main Code 
    │   └── problem_statement.pdf       <- Problem statement 
    │
    ├── project 2
    │   ├── report.pdf                  <- Final submission report
    │   └── solution.ipynb              <- Final Code 
    │   └── problem_statement.pdf       <- Problem statement 

