# Classification-based-on-smartphone-sensor-data
My bachelor's thesis with topic "Classification based on smartphone sensor data"


#Abstract
Today’s smartphones include many kinds of sensors that produce large amounts of data. This data
can be used in different machine learning applications. One of these applications is human activity
recognition (HAR), where sensor data for example can be used for transportation mode detection.
In previous studies, different smartphone sensors have been used for transportation mode detection.
One sensor, which has proven to be effective for this purpose is accelerometer, because it is energy
efficient and has obtained good accuracies in this task.


This thesis investigates how well two state-of-the-art classification methods perform in transportation mode detection based on smartphone accelerometer data. Data used in this thesis contains pre-processed magnitude of the accelerometer values from seven transportation modes. These
modes are driving a car, taking a bus, taking a subway, taking a train, bicycling, walking and being
stationary.


The classification methods which were used for transportation mode detection were random
forest and boosting. Random forest is an ensemble classification method that uses many decision
trees with randomized number of features and randomized cases (observations) in the training set
to perform the classification task. Boosting methods are ensemble classifiers that take the majority
vote of many weak learners in their classification rule. Boosting method that is used in this thesis
is called as adaptive boosting or AdaBoost.


The AdaBoost classifier performed slightly better in transportation mode detection than the
random forest classifier with the accuracy of 92.357 %. The random forest classifier produced
classification with the accuracy of 91.600 %. However, the performance differences were rather
marginal. Both models classified the non-motorized transportation modes better than the motorized
modes and the most misclassification happened between the motorized transportation modes. This
why the point of development was thought to be the discovery of new features that would improve
the classification accuracy of the motorized transportation modes
