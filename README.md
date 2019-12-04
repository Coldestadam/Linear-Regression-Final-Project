# Linear-Regression-Final-Project
This project was completed by my partner Zachary Dougherty and myself. We used a dataset that was given to use by the University of San Francisco, and it detailed information about the graduated Class of 2018 starting with information from their freshmen year in 2014. Zachary created two Linear Regression models using Ridge and Lasso to create predictive and explanatory models for the GPA of the students. I myself created two Logistic Regression models that predict whether the student graduated or not. I created two models because I created an unbalanced dataset and a balanced dataset.  



## Dataset
The dataset was given to us by the University of San Francisco that contained data from the freshmen class of 2014, or the graduating class of 2018. It details some information from their freshmen year and their overall performance at the end of their academic career here at USF that such as their GPA or total amount of credits earned here at USF.

### Variables
1. RANDOM_ID - Randomized integers to anonymously identify the students.
2. GENDER - Details whether the student is either Male(M) or Female(F).
3. IN_STATE - States whether the student is from the State of California(Y) or not from the State of California(N). International students would be classified to be not from the State of California.
4. UNMET_NEED_PERCENT - Continuous values that tell at what percentage was aid not provided to fill the cost of tuition. Someone that has 100 for their data point states that they had to fully pay the tuition cost at the time without aid from the university or Federal Government. If someone has 0 for their data point, that means that their tuition was fully aided by either or both by the university and Federal Government.
5. PELL - Details whether the student qualified for the Federal Pell Grant given by the United States Government. It is (Y) if that student did qualify and (N) if that student did not qualify.
6. MAJOR - The shorten codified name of the Major that the student studied while at USF.
7. MAJOR_DESC - The Full name of the Major that the student studied.
8. SCIENCE_CLASSES - The number of science classes that the student took.
9. LAB_CLASSES - The number of lab classes that the student took.
10. RESIDENCE_HALL - Details the living situation of the student. It contains the names of the dorm buildings on USF's campus or Off-Campus if they did not live in the dorms.
11. ETHNICITY - The self-identified ethnicity of that student.
12. CREDITS_EARNED - Gives the total number of credits that the student completed from USF, and that contains transfer credits. It is required for all students to at least earn 128 credits to be eligible to graduate.
13. GPA_CREDITS - Provides the total number of GPA credits that the student earned here at USF. GPA credits are the total cummulative score that is based on what grade the student earned in all the student's courses. For example, 4 points are awarded if the student recieves an A in the course.
14. GPA - Grade Point Average of the student.

### Extra Variable for Logistic Regression
I had to create a discrete variable that states whether the student graduated or not. The marker of whether the student graduated is if the student earned more or equal to 128 credits. I inputted a 1 to classify if the student graduated and a 0 to classify that the student did not graduate.

1. logistic.col - States whether the student graduated(1) or whether the student did not graduate(0).
