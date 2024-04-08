### Leslie Debassige 
## Module 3 PyPoll solution 

## Overview of Project
hallenge is to create a written analysis with three key deliverables as follows; 
* Deliverable 1: The Election Results Printed to the Command Line
* Deliverable 2: The Election Results Saved to a Text File
* Deliverable 3: A written Analysis of the Election Audit (README.md)

The tools that will be used are Python in order to do the following:

* Create scripts that read, write, and store data from files or in arrays.
* Perform mathematical operations.
* Use decision statements, logical operations for complex comparisons, and repetition statements to run code more than once.
* Produce screen outputs.

 The data that we will be using is the PyPoll solution python script, the election results .csv, and the election_results.txt. to help Seth and Toms become familiar with the command line, which will be used to make updates to the GitHub repository, access local files and folders, and write and run Python programming scripts. 

## Purpose
We will be using Python to write algorithms that will assist the confirmation and analysis of election results.

## Analysis and Challenges

We will be using Python to write algorithms that will assist the confirmation and analysis of election results. 
The following was needed:

* Installation of Python for Windows and ensuring the correct version. 
* GitHub repository for the election analysis. 
* Command line copying, or cloning, the repository onto your computer.
* Run, or execute, Python files to make sure the code is working and that output is correct.
* Use arithmetic operators that make calculations like addition, subtraction, multiplication, and division.

For Example:
* /	Divides one number by another. This always results in a floating-point decimal number.	x / y
* %	The “%” is known as the modulus. When used in place of “/” it will divide one number by another, and return the remainder of the division. x % y(remainder of x/y)
* //	Divides one number by another and returns an integer. This is known as floor division.	x // y

Also for the analysis data types are stored and accessed. In the election audit, storing and accessing data in a variety of formats, such as lists, tuples, and dictionaries. Accessing the data in these data structures as well as storing data in new files are common tasks.

## Results

We learned how to retrieve data based on conditions known as a decision statements to produce analytics of winning results as shown here:

  ![Final](https://github.com/735713038455163/Election-Analysis/blob/master/Resources/Final.PNG)

The improvements were in some of the following areas:
* When writing an algorithm that performs the same task over and over, it's a lot easier to write the code for the algorithm once, and then place that algorithm in a repetition structure that can be repeated as many times as necessary. This type of repetition structure is called a loop.

Such as the for loop here for county name, county votes:

![countrynamecountyvotes](https://github.com/735713038455163/Election-Analysis/blob/main/Resources/countrynamecountyvotes.PNG)

And the for-loop candidate name, candidate votes:

![forcandidatenameandcandidatevotes](https://github.com/735713038455163/Election-Analysis/blob/main/Resources/forcandidatenameandcandidatevotes.PNG)

To review the dataset the following are considerations:

* A copy of the code needs to be downloaded to folders:
* Before you open the CSV, you need to make a connection to the file by using your computer's directory "path" to that file.
As such:

![filetoload](https://github.com/735713038455163/Election-Analysis/blob/main/Resources/filetoload.PNG)

When the file to load is successful you have an understanding how to change directory by using cd and linking a copy of the file path to ensure the code refers to the relative directory versus the absolute. 
As such:

![filetoloadsuccessful](https://github.com/735713038455163/Election-Analysis/blob/main/Resources/filetoloadsuccess.PNG)


## Challenges and Difficulties Encountered

Debugging code and troubleshooting is a difficult but rewarding task in the field of data science. 

Such as this error:

![error](https://github.com/735713038455163/Election-Analysis/blob/main/Resources/error.PNG)

The error is an IOError, which is an "Input/Output" error, meaning that we used an output directory, 'analysis/election_analysis.txt', that doesn't exist with the given file path.


- Determining the winning candidate, vote count, and percentage with a decision statement. 

![Winning Country Summary](https://github.com/735713038455163/Election-Analysis/blob/main/Resources/Winning%20County%20Summary.PNG)
![Winning](https://github.com/735713038455163/Election-Analysis/blob/main/Resources/Winning.PNG)
Lastly,

- Printing to a text file. 

![Election results](https://github.com/735713038455163/Election-Analysis/blob/main/Resources/Election%20results.PNG)
![Election results picture](https://github.com/735713038455163/Election-Analysis/blob/main/Resources/Election%20results%20picture.PNG)

Overall, I enjoyed working with Python over VBA. 

