Variables:

x_train : Training set 
y_train : Training label

x_test:Test set
y_test:Test labels

subject_train, subject_test 

x_data, y_data , subject_data is a merge of previous data

features contains the correct names for the x_data dataset, which are applied to the column names stored in mean_and_std_features, a numeric vector used to extract the desired data.
all_data merges x_data, y_data and subject_data
averages_data contains the relevant averages which will be later stored in a .txt file. ddply() from the plyr package is used to apply colMeans() and ease the development.
