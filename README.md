# CST116-Lab9
Oregon Institute of Technology
CST 116 Computer Concepts & Problem Solving
Lab #9: Reading From & Writing To Files, Array Database


CST116
Module 9: Lab 9


Debugging


1. Go to learnbydoingbooks.com
2. Select STUDENT RESOURCES
3. Download Chapter 11.zip
4. Load the Chapter 11 Debug.cpp code
5. Follow the instructions in the top of the code.


Submit: code & runs
10 pts


Reading From and Writing To a file
Write a program that reads the following from a file:
* Name
* Social Security Number
* Wage
* Number of hours worked in a week
* Status (full-time: “F” or part-time: “P”)
If a person is a full-time employee, $5 is deducted from their wages for union fees.
Time and a half is paid for any tie worked after 40 hours in a week.


For the output file, you must display the person’s name, Social Security Number, wage, number of hours, straight time pay, over time pay, whether they are a part-time or full-time employee and their net pay.
Make sure that the output is formatted into rows and columns and includes the appropriate titles and column headings.


Data: Use the following information as data for your data file:


John Smith 123-09-8765 9.00 46 F

Molly Brown 432-89-7654 9.50 40 F

Tim Wheeler 239-34-3458 11.25 83 F

Keil Wader 762-84-6543 6.50 35 P

Trish Dish 798-65-9844 7.52 40 P

Anthony Lei 934-43-9843 9.50 56 F

Kevin Ashes 765-94-7343 4.50 30 P

Cheryl Prince 983-54-9000 4.65 45 F

Kim Cares 343-11-2222 10.00 52 F

David Cockroach 356-98-1236 5.75 48 F

Will Kusick 232-45-2322 15.00 45 P


20 pts
Submit: full development process


Menu-Driven Database
This program involves developing a menu-driven database application. 
You need to accept as input from a file a person’s first name, last name, phone number and birth date.
This program will be menu drive with the following options:
1. Find a person’s information
2. Add a person to the database
3. Edit a person’s information
4. Display all records to the screen
5. Quit


* Option 1 allows the user to enter a name after which you will search for and display the person’s information.
* Option 2 allows the user to add a person to the database.
* Option 3 allows the user to change ANY information related to a specific individual. Be careful: if the user changes the last name of the person, the arrays will need to be resorted.
* Option 4 displays to the screen all of the records sorted by last name in the database.
* Option 5 will end the program.


The data will be read from the file only ONCE, and will only update the file after the person has chosen Option 5 from the menu.
All other modifications to the data are performed on the arrays storing the information.


Data: Create your own data file using realistic personal data to exercise all of the option in the program.




30 pts
Submit: full development process


50 pts
