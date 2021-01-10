# Activity-Recognition-from-Single-Chest-Mounted-Accelerometer-
Mainly comprises uncalibrated accelerometer data mounted on 15 users. The experiment basically analyses 7 activities performed by each respondent.

I have prepared this project in two different methods. 

I have created 4 different files.
In file three file. In the first file (activity recognition.merging the datasets to one dataframe) there are 7 different activities in the dataset, I classify only  into 5 classes.

In this next file (activity recognition.dataset data visualization) box-plots histograms and plot for the dataset. I used a different method than before to store the dataset in a list of lists. This way it was easy to visualise the box plots of different activities in one graph.


In another file (Activity Recognition from Single Chest-Mounted Accelerometer)I have applied Decision Tree Classification to train and tested with gini and entropy criterion. I got an accuracy score of around 73% . Below I have attached the full code file.
If we only want 5 classes we can eliminate any two classes from Activity id 2, 5, 6 as the duration for them is very less which can be seen when you represent them in a box plot.

Now the Next another one more type we can create this project.

# KNN_&_Random_Forest_Activity_Recognition 
Here the another file which is KNN_&_Random_Forest_Activity_Recognition. I applied two different algorithms in this one: KNN where i got 71% while applying Random Forest i got only 51%  of accuracy.

Because our model is not giving proper accuracy i applied Hyper parameter Tuning i got 75% of accuracy in both KNN & Random Forest model.
