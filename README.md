# DM
The project is about predicting the rating given the comment. It is basically a classification algorithm because it has 10 ratings. I have rounded off the ratings in the data frame when read from csv file.
(1) The data_mining_project.ipynb is the file which runs the classifier program.
(2) The web app works on localhost.
(3) When it is run on localhost we have to give a string input as a comment and the webapp will give the "rating" as the output.
(4) The whole code is run in python (jupyter notebook) and django (web app)
(5) The command to run webapp is "python manage.py runserver"
(6) The following libraries are required pandas (for processing data), nltk (cleaning), sklearn (for naive bayes calculation and SVM), re (for cleaning data), joblib (create and load model file) and need to install django (for webapp)
(5) Naive bayes and SVM has been used to classify the ratings and sklearn and nltk modules has been used to implement the classifier program.
(6) The model files are naive_model.joblib and svm_model.joblib
(7) naive_cv.joblib is for count vectorizer which can be used for both naive bayes and svm
