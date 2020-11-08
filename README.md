# ETH-exercises
some graded and ungraded homeworks from different courses offered at ETH Zurich :bulb:

## PCA on faces :woman: :older_man: :girl: :boy:
This exercise comes from the course Computational Intelligence Lab in the spring semester of 2020. Here we perform PCA on the variance-covariance matrix of the data to extract the principal components corresponding to 'principal eigenfaces', to later reconstruct an image as a combination of only these 'principal eigenfaces'.

## Signal Processing & Wavelets
This exercises comes from the course Computational Intelligence Lab in the spring semester of 2020. Here we represent our signal in a different basis, namely the Haar basis. We then try to get rid of noise by treshholding the signal in the Haar basis, and then to transform it back into the original basis. 

## Analysis of a high school class social network 
This exercise comes from the course Social Networks: Analaysis, Theory and Applications offered at ETH Zurich in the spring semester of 2020. The analysis was performed on a high-school classroom data set in Hungary. The Analysis was performed both on a "friendship network", where an edge in the graph represents a friendship as well as a trust network, where an edge represents a trust relationship. 

## Analysis of a London Street Gang social network
This exercise comes from the course Social Networks: Analaysis, Theory and Applications offered at ETH Zurich in the spring semester of 2020. In this exercise we study the social network of a gang based in London. The data is on co-offending in a London-based inner-city street gang, 2005-2009, operating from a social housing estate. The data comes from anonymized police arrest and conviction data for all confirmed members of the gang. It consists of four networks: hang-out together, co-offend together, commit serious crime together and commit serious crime together & kin.

We compute a number of simple network statistics, like degree distribution, proportion of homophilic ties and modularity. We also provide a number of network plots and comment on our observations throughout.

We then perform Conditional Uniform Graph tests to test whether same age group ties and ties between individuals of a common birthplace are more likely, first conditioned on network size and then additionally on the number of isolated nodes. Our findings suggest e.g. that individuals of a common birthplace are significantly more likely to commit serious crime together.

## Classification of medical images
This exercise is was the second graded project of the course Advanced Machine Learning offered at ETH Zurich in the fall semester of 2019. The task was a 3-class disease classification task with a highly imbalanced dataset derived from medical images. Our final solution was SVC with the parameter balanced set to true, which takes care of the fact that the data is unbalanced. 

Learning from our mistakes in task 1 we validated our models properly with 5-fold cross validation and grid search. The final model was a support vector machine where the class imbalance problem was handled by balancing the class weights according to frequency in the input data. This model took us to position 20 out of roughly 200 teams of ETH master students.

## Classification of ECG signals
This exercise was the third graded project of the course Advanced Machine Learning offered at ETH Zurich in the fall semester of 2019. We had to perform multi-class classification on time series data, in the form of ECG signals.

Preprocessing was paramount in this task. By studying the properties of ECG signals we could decide what would be relevant features to extract from the raw time series data. Among those were summary statistics like mean, median, standard deviation etc of the R peaks of the signals, time difference between R peaks and heart rate templates. This was done with the help of the biosppy package. Once feature extraction was complete, we used a grid search pipeline to cross validate different models. The final model was a Gradient Boosting Classifier with a median imputing strategy for missing values, which took us to a position of around 30-50 out of around 200 teams of ETH master students (leaderboard is no longer available at the time of writing).



