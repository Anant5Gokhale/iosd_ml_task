# iosd_ml_task
Given a dataset create an svm model to predict whether an asteroid is hazardous or not

Given a [dataset](https://www.kaggle.com/datasets/sameepvani/nasa-nearest-earth-objects), the aim is to implement a SVM model and provide a comparative study using different kernels(linear, polynomial, gaussian, sigmoid, RBF etc) using precision and f1-scores.
The SVM model used here is for classifying data as hazardous or non-hazardous. Unlike the traditional statistical approach, svm creates a hyperplane in an n dimmensional space that distinclty classifies data points. Thus by utilising a geometric approach svm is able to create a large margin classifier, that is highly desirable as the model is able to more clearly distinguish between data groups.
