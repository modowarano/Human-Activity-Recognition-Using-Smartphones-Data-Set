# Project : Human Activity Recognition Using Smartphones Data Set

## This text file is the codebook of the R-Code file "run_Analysis.R"

* columns : a vector containing columns' names read from the txt file "features.txt"
* x_train : the data read from the txt file "x_train.txt"
* y_train : the data read from the txt file "y_train.txt"
* x_test : the data read from the txt file "x_test.txt"
* y_test : the data read from the txt file "y_test.txt"
* subject_train : the data read from the txt file "subject_train.txt"
* subject_test : the data read from the txt file "subject_test.txt"
* train_columns : a table obtained by a "cbind()" of subject_train, y_train and x_train
* test_columns : a table obtained by a "cbind()" of subject_test, y_test and x_test
* dataset : a table obtained by a "rbind()" of train_columns and test_columns
* actlabels_tmp : a vector containing the content of the file "activity_labels.txt"
* actlabels : a vector containing the activity labels
* chosen_columns : a vector containing columns' names which contain the measurements on the mean and standard deviation.
* last_dataset : the final data set
