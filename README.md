# MANE 4333

## Midterm Exam

### Assigned: October 24, 2024

### Due: October 31, 2024

The midterm exam covers three major topics from MANE 4333: 1) Principal Component Analysis, 2) Multiple Linear Regression, and 3) Neural Networks. This exam will be a take-home exam. **You are to discuss the exam with no one and neither give or receive help from any other person. Any help from others will be consider academic dishonesty and will be reported.** 

The exam will be distributed through GitHub Classroom as previous homework assignments have been distributed. Your repository should contain the following files: README.md (this file), questionOneData.xlsx, questionTwoData.xlsx,  questionThreeData.xslx, and MidtermExam.ipynb.

Please complete the exam and submit before the end of the day on Thursday October 31, 2024

---

## Question 1. Principal Components Analysis (25 points total)

The first question on the exam is related to principal components analysis.

### Part a (5 points).

In cell two (code cell), enter the Python code to read filename.xlsx into a Pandas Data Frame. After the file is stored in a dataframe, use Pandas plotting to generate a scatter matrix of the data and use Seaborn to generate a heat map.

### Part b (5 Points).

In cell three (Markdown cell), discuss the information found in the scatter matrix and heat map.Your discussion, at a minimum, should consider the strength and type of relationship among the eight variables.

### Part c (5 points).

In cell four (code cell), enter the necessary commands using StandarScaler to create a new dataframe with the centered and scaled data.

### Part d (5 Points).

In cell five (code cell), enter the commands to perform a principal components analysis of all eight variables. Print the following quantities:

1.  Eigen values,
2. Eigen vectors,
3. Explained variance,
4. Explained variance ratios, and 
5. Cumulative Percent Variability Explained by each component.

### Part e (5 points).

In cell six (Markdown cell), select the number of components to be used based upon the following ? Criterion:

1. The Eigenvalue criterion
2. Proportion of (Cumulative) Explained criterion.

What is your final recommendation for the reduced number of components to use?

---

## Question 2. Multiple Linear Regression (45 total points)

This question examines multiple linear regression.

### Part a (5 points).

In cell seven (code cell), calculate the variance inflation factors (VIF) for variables $x_1$ through $x_10$.

### Part b (5 points).

In cell eight (Markdown), interpret the variance inflation factors. Are there any problem? Can you make any recommendations?

### Part c (5 Points).

In cell nine (code cell), enter the commands to fit a full model.

### Part d (5 points).

In cell ten (Markdown cell), suggest a reduced model using $\alpha=0.05$ as the critical value.

### Part e (5 points).

In cell eleven (code cell), enter the commands to fit the reduced model.

### Part f (5 points).

In cell twelve (Markdown cell), conduct a partial F-test using $\alpha=0.05$ and clear state the results of the hypothesis test.

### Part g (5 points).

In cell thirteen (code cell), enter the commands to perform a best subsets analysis provided in Week 7.

### Part h (5 points).

In cell fourteen (Markdown cell), select an overall best model and justify your selection.

### Part i (5 points).

In cell fifteen (Markdown cell), state the important analysis used to determine that model assumptions was not performed in Question.

---

## Question 3. Neural Networks (30 total points)

Questions focuses on Neural Networks.

## Part a (5 points)

In cell sixteen (code cell), perform the following functions:

1. Load data from fdjkqsa file into a dataframe,
2. Implement MinMax scaling,
3. Partitition the data into testing and training portions use random_state=1024.

### Part b (10 points)

In cell seventeen (code cell), perform the following functions:

1. Define the parameters of a MLPRegressor model,
2. Train the neural network, and
3. Evaluate the trained neural network on both the test and training segments. Include the following metrics: $R^2$, MSE, and Mean absolute error for both training and test segments.

### Part c (5 points)

In cell eighteen (code cell), perform the following functions:

1. Define a parameter grid and execute a RandomSearchCV to hypertune,
2. Train the best model found from the RandomSearchCV command, and
3. Evaluate this model using the same metrics described in part b, item 3.

### Part d (5 points)

In cell nineteen (code cell), perform the following functions:

1. Define a parameter grid and execute a GridSearchCV to hypertune,
2. Train the best model found from the GridSearchCV command, and
3. Evaluate this model using the same metrics described in part b, item 3.

### Part e (5 Points)

In cell twenty (Markdown cell), compare the model developed in parts b, c, and d. Select the best model and justify your selection.
