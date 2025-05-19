# CIS278-Programming-Project-1-solution

Download Here: [CIS278 Programming Project #1 solution](https://jarviscodinghub.com/assignment/cis278-programming-project-1-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

This project provides an opportunity to review basic program development skills, arithmetic operators and usage of control structures. New concepts are usage of C++ namespaces and I/O streams ( cin and cout ).

PART 1 70%

The Problem
Charlie’s Sprinkler Systems sells a computer controlled lawn sprinkler system which are designed to be attached to a computer. This type of system allows for a much simpler user interface in controlling the watering/irrigation process and consequently improves the health of plants and saves water. You have been working at for Charlie’s in the warehouse, and upon hearing that you are a CIS major, Charlie has asked you to write a program to prepare invoices for his customers.

Charlie’s Sprinkler Systems produces four models of their product. The first is called the “Green Miracle” Sprinkler Controller. The basic cost of this system is $79.00 plus $2.95 per circuit control unit. It can accept between 4 and 8 circuit control units, each of which will be attached to and control a separate watering circuit.

The “Deluxe Miracle” Sprinkler Controller provides all the functionality of the Green Miracle but also includes memory that records problems that occurred when the system was in use. The basic cost of a Deluxe Miracle Sprinkler Controller is $129.50 plus $3.95 for each control unit. This model can take between 6 and 24 control units.

The “Platinum Miracle” System has a built-in network connection that allows the system to connect to “wired up” homes that use control systems such as those sold by Radio Shack and Sears. The “Ultra Miracle” is a commercial product withhardware failure. such as parks and golf courses.

The specifications for all these systems are shown in the chart below.

Base Unit Price Shipping Weight of the Base Unit (lbs.) Price Per Circuit Controller Number of Circuit Controllers Per Base Unit Shipping Weight of Each Circuit Controller (lbs.)
Green Miracle $79.00 5.5 $2.95 4 to 8 .75
Deluxe Miracle $129.50 7.5 $3.95 6 to 24 1.2
Platinum Miracle $229.99 8.0 $3.95 0 to 24 1.4
Ultra Miracle $349.99 11.5 $4.25 0 to 48 1.4

The Application
Your invoice application should function as follows:

• The user must provide:
1.) the customer’s 6 digit customer number
2.) the type item being purchased (this can be indicated using an int value, ie.
1 represents Green Miracle, 2 represents Deluxe Miracle, etc)
3.) the number of circuit controllers desired for this item
4.) the quantity of systems being purchased (you can assume that a customer will purchase
all of the same type item, each with the indicated number of circuit controllers)
If an customer number is missing a digit, or has extra digits, an error message is given and the user must reenter until a valid number is provided

If the type item is not a valid number, an error message is given, and the GREEN MIRACLE is assumed.

If the number of circuit controllers is not within the proper range, the minimum number of circuits for that product is assumed.

If the quantity is not a positive value, one item is assumed.

• Calculate and display the total price for the systems being purchased

• Calculate and display the shipping cost for the systems. You need to calculate the weight of the order based on the number of base systems and the number of circuit controllers in the order. There is a fixed $1.00 per pound shipping charge

• Calculate and display the tax charged. Tax is charged at the rate of 10 percent, but is not applied on the shipping and handling.

• Calculate and display the FINAL cost (price plus shipping) for the sale

Be sure and test your code thoroughly to ensure that all options work correctly, and that the error handling is correct. Before testing your program you should use a calculator or spreadsheet program to calculate the expected values that your program should produce. So that you can identify erroneous output.

• Once you have your program working properly for one customer order, update your program to ask the user whether they would like to process another customer.

Call your C++ file sprinkler.cpp, and submit it, making sure that your name is included in an initial comment, each control structure is commented to indicate the task it is performing, and any code that is not obvious is briefly commented as well. Indentation should indicate the code which is governed by each control structure to enhance readability. (see programming standards below)

PART 2 30%
Write a C++ program which accepts one four digit int value and displays the digits in reverse order. That is, if the input value was 9843, the program will output 3489.

Once the program works correctly for one 4-digit value, add code which will allow the user to process multiple values. The program should ask the user how many numbers will be entered, and then repeat the process for each number.

A typical program run might look like:

How many numbers would you like to process? 3
3 values will be processed.

Input first number: 5678
Reverse: 8765

Input first number: 1034
Reverse: 4301

Input first number: 9421
Reverse: 1249

Call your file numbers.cpp, and submit it, again keeping style (commenting and indentation) in mind.

Please note:
Students are to submit solution files as email attachments. Be sure your email subject indicates that you are submitting the solution to CIS278 Project 1. Only submit the .cpp files requested, I do not need or want any other project files.

DO NOT SUBMIT CODE which does not compile. As this is not an introductory programming course, I do not give any credit for code which does not execute.

Programming Standards
The program should have comment lines at the beginning that identify the course name and number, the project name and number, the programmer’s name and student id, and the date the project is due. Then include a brief description of the purpose of the program. There should be other comment lines throughout the program that identify each new section and briefly what that section is doing. Add comments liberally, particularly if there is anything that would be difficult for a maintenance programmer to understand (e.g., a difficult calculation,). It is not necessary to include comments that explain how a particular type of C++ statement works; we assume that other readers of the program know this. You should choose variable names that are descriptive, but not excessively long. All variables, other than perhaps those which are control variables for loops, should be defined at the beginning of main. Constants should be defined at the beginning of the program. You should pay close attention to the formatting of your program, since improper formatting makes your program difficult for you to debug as well as difficult for others to understand. Strive for readability and understandability in the code you write. Use white space to improve readability.

When You Need Help
If you are having problems with your program’s logic, you may want to do the following:
• trace the logic by hand
• include cout statements to print out values or to show that execution has reached a particular point
• use the debugger tools that are part of the Visual Studio Integrated Development Environment (IDE) to single step through your program or observe the values of variables.
• read any relevant descriptions in the textbook or other reference material
• refer to cplusplus.com, which provides documentation and examples of many C++ constructs
• experiment by creating a new small program with some sample code that contains the kind of statement that is causing you problems. Play with the sample code in this simpler environment.
• Look at the Project forum and see if someone else has posted a similar problem, and has received useful advice
• Only after you have tried to solve the problem yourself should you post the problem to the Project Forum, or email me for help. You should make every effort to solve each problem yourself, but when you are out of ideas then ask for assistance.

Following the above steps will help you learn the workings of the C++ language.
