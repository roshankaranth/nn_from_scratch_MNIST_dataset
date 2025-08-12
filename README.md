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

    - architecture : [X,25,15,10],with He initialization, and inverted dropout with keep_prob = 0.98
        - Accuracy on training set : 93.85166666666666%
        - Accuracy on test set : 93.54%
        (Accuracy while training (1000 iterations)-> 92.13166666666666%)

    - architecture : [X,25,15,10],with He initialization, and gradient checking
        - Accuracy on training set : 94.43666666666667%
        - Accuracy on test set : 94.19999999999999%

    - architecture : [X,25,15,10],with He initialization,
        - Elapsed time : 399.93859601020813 seconds

    - architecture : [X,25,15,10],with He initialization, mini-batch gd,
        - Accuracy on training set : 99.565%
        - Accuracy on test set : 95.41%

    - architecture : [X,25,15,10],with He initialization, mini-batch gd, regularization_param = 0.8
        - Accuracy on training set : 98.27333333333334%
        - Accuracy on test set : 97.11999999999999%

    - architecture : [X,25,15,10],with He initialization, mini-batch adam
        - Accuracy on training set : 100.0%
        - Accuracy on test set : 95.89%

    - architecture : [X,25,15,10],with He initialization, mini-batch adam, regularization_param = 0.8
        - Accuracy on training set : 98.23333333333333%
        - Accuracy on test set : 97.28%

    - architecture : [X,25,15,10],with He initialization, mini-batch adam, keep_prob = 0.8
        - Accuracy on training set : 98.595%
        - Accuracy on test set : 94.71000000000001%