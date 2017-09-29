# ElementQuiz
Class project - guess 5 elements from the first 20 of the periodic table. Final Project for Intermediate Python class I completed

This project was done in the Jupyter Notebook environment
The goal was to use !curl to download https://raw.githubusercontent.com/MicrosoftLearning/intropython/master/elements1_20.txt" 
as elements1_20.txt
Then - open the file with the first 20 elements and read one line at a time to get element names, 
remove any whitespace (spaces, newlines) and save each element name, as lowercase, into a list

A function was created - get_names() - Call the get_names() function
User input would be the return value for the quiz responses list
The program would then check if responses are in the list of elements
Iterate through all 5 responses and compare each response to the list of 20 elements
any response that is in the list of 20 elements is correct and should be added to a list of correct responses
if not in the list of 20 elements then add to a list of incorrect responses
Finally, calculate the % correct answers and print the outcome
