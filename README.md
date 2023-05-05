# CGPA_Generator_and_Analyzer

The CGPA Generator and Analyzer is a program designed to keep track of a student's semester information and provide output to the end-user about the student's current and previous semesters, as well as their overall performance. The program has its own database which is used to perform all the operations. When CSV files are fed into the system, it fetches data from it, performs calculations and displays the output to the end-user.

## Features

* Semester information management
* Performance analysis of a student's current and previous semesters
* Automatic marking of students with an IF grade if they are short of marks in the Continuous Evaluation (CE) component
* Overall performance analysis of a batch in a particular semester
* Grade point calculation based on relative grading

## Grade Point Consideration 

In this program, we have considered relative grading for the batches. The total marks at the end are first normalized so that we obtain a range between 0 to 1. Then we assign them a grade point according to the following table:

| Grade     | Grade Point |
|-----------|-------------|
| 0.90 – 1.00 | 10          |
| 0.75 – 0.90 | 9           |
| 0.60 – 0.75 | 8           |
| 0.40 – 0.60 | 7           |
| 0.20 – 0.40 | 6           |
| 0.00 – 0.20 | 5           |

The program automatically marks the student with an IF grade if they are short of marks in the Continuous Evaluation (CE) component.

## Usage

The program can be used by feeding the CSV files into the system and performing the required operations. The program will fetch data from the database, perform calculations, and display the output to the end-user.

## Conclusion

The CGPA Generator and Analyzer is a useful tool for keeping track of a student's semester information and analyzing their performance. The program provides accurate and reliable results, making it an essential tool for educators and students alike.
