# msrit-python-lab-mcsl18
# `Realtime Application Development Using Python`

## [`Program 1a`](program1a.py)

Create over 100000 data to a CSV file. Read it to list. Use menu operators to add, search, delete from the list.
Read experience(number) from user & display the faculty name, so that they can participate in BOS.

## [`Program 1b`](program1b.py)

Create synthetic dataset for student details over 100000 rows with student name, USN, CGPA, address, 
blood group, branch name, UG/PG, date of birth and year of studying. Then load dataset to tuple. Display menu for search. Dislpay the UG/PG students for a particular branch get the input from the user, where CGPA > 9.

## [`Program 1c`](program1c.py)

Weather details displaying for a particular place given longitude & latitude in the globe. Read longitude & latitude values from the user and store weather details to a dictionary.

## [`Program 2a`](program2a.py)

Write a Python program demonstrate continous blinking of a LED (blinking effect) using Raspberry PI and RPi.GPIO library

## [`Program 2b`](program2b.py)

Write a Python program to detect the intensity of light in surrounding using a LDR(Light Dependent Resistor) and display the LDR Value as output.

## [`Program 3`](program3.py)

1. Generate 100000 rows, synthesized faculty dataset where experience linearly mapped to designation, salary, no. of publications, no. of book chapters, amount of consultancy work, fund received, professional membership.
2. Read and load it into a list using function (try all the types of functions)
3. Find out the correlation among the fields in faculty dataset.
4. Perform the Linear regression analysis and plot the predicted value.

## [`Progam 4`](program4.py)
Generate 100000 rows and put in csv file, sythesized faculty dataset where experience linearly mapped to designation,
salary, no. of publications, no. of chapters, amount of consultancy work, fund recieved, professional membership.

a. Read csv file and load it into tuple and Dictionary using Function, (try all the types of function)
b. Find out correlation among the fields in faculty dataset
c. Perform the following operations:
    i. Linear Regression analysis of following & plot the predicted value in separate graphs
    ii. KNN analysis of following & plot the predicted value in separate graphs
    iii. Apply Naiye Bayes algorithm for the following & plot the predicted value in separate graphs
            (x-axis - experience, y-axis - predicted value)
            I. No. of publication
            II. No. of Book chapters
            III. AMount of Consultancy work
            IV. Fund Received
            V. Professional Membership

## [`Progam 5`](program5.py)
Generate 1,00000 rows and put in csv file, synthesized data faculty data set where experience linearly mapped to designation, 
salary, no of publication, no of book chapters, amount of consultancy work, fund received, professional membership.
    A. Read csv file and load it into tuples (try lambda function)
    B. Perform the following operations:
        i. Using regular expression search for associate professors with more than 15 years experience, assistant Professors with more than 5 years experience, Professors with more than 20 years experience
        ii. Analyze the association rule mining of associate professors for their following performance relations in different contributions
            A. No. of publication and no of book chapters
            B. No. of publication and amount of consultancy work
            C. No. of publication and fund received
            D. No. of publication and professional membership

## [`Progam 6`](program6.py)
Generate 100000 rows and put it in csv file, synthesized data faculty dataset where experience linearly mapped to designation,
salary, no. of publications, no. of chapters, amount of consultancy work, fund received and professional membership. 
Use classes and objects for the following operations:
i. Read csv file and load it into temp variables
ii. Perform the following operations
    a. Using lambda and regular expression to search for associate professors with more than 25 years experience and 
        load in another temp list called "asso_prof_25"
    b. In asso_prof_25 list do the following factoring:
        1. If experience > 25, yes means set the value as 1 else 0
        2. If publication count > 5, yes means set the value as 1 else 0
        3. Similarly do for no. of publications > 3, amount of consultancy work > 50000, fund received > 500000, 
            professional membership > 2
    c. Analyze the association rule mining of associate professors for the following performance relations in different contributions
        1. Experience, designation, no. of publications and no. of book chapters
        2. Experience, designation, no. of publications and amount of consultancy work
        3. Experience, designation, no. of publications and fund received
        3. Experience, designation, no. of publications and professional membership

## [`Progam 7`](program7.py)
Create a csv file called "books.csv" with synthesized data set having the following columns: 
Student usn, semester-number, sub-code, subject name, book referred, book-id, grade scored.
    1. Use exception handling for file operations.
        i. Read the csv file content into local variables for accessing them in python
        ii. Extract only sem-number, sub-code, book-id and grade scored and store in another CSV file called "extracted-books.csv".
        iii. Note: When you write into the "extracted-books.csv", file Convert grade code to number (Sgrade-9, A grade-8,etc) 
            and update into the file
    2. Analyse the coorelation between sem-number, sub-code, book-id and grade scored
        i. Convert the data set in required format to perform association rule mining an analyse the output
        ii. Convert the data set in required format to Perform the collaboration filtering over the data set.

## [`Progam 8`](program8.py)
Create a csv file called "books.csv" with synthesized dataset having the following columns: 
Student usn, semester-number, sub-code, subject name, book referred, book-id, grade scored.
   1. Read the csv file content into linked list for accessing them in python
   2. Extract only sem-number, sub-code, book-id and grade scored and store in another CSV file called "extracted-books.csv".
   3. Note: When you write into the "extracted-books.csv", file Convert grade code to number (Sgrade-9, A grade-8,etc) 
   and update into the file
   4. Analyse the coorelation between sem-number, sub-code, book-id and grade scored
      i. Convert the dataset in required format to perform the collaboration filtering over the dataset.
