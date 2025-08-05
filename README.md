Inital NN
    - architecture : [X,25,10],
        - Accuracy on training set : 91.18833333333333%
        - Accuracy on test set : 91.58%

    - architecture : [X,10,5,10],
        - Accuracy on training set : 11.236666666666666%
        - Accuracy on test set : 11.35%

    - architecture : [X,25,15,10], without He initialization
        - Accuracy on training set : 43.34%
        - Accuracy on test set : 43.54%

    - architecture : [X,25,15,10],with He initialization,
        - Accuracy on training set : 90.34%
        - Accuracy on test set : 90.42%

    - architecture : [X,25,15,10],with He initialization, and regularization (l=0.7)
        - Accuracy on training set : 90.34166666666667%
        - Accuracy on test set : 90.42999999999999%

    - architecture : [X,25,15,10],with He initialization, and inverted dropout with keep_prob = 0.95
        - Accuracy on training set : 94.13666666666667%
        - Accuracy on test set : 93.96%
        (Accuracy while training (1000 iterations)-> 91.33666666666667%)

    