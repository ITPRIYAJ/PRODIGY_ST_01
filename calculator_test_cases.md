Test Case 01
•	Test Case ID: TC_CALC_01
•	Test Description: Verify addition of two positive integers
•	Preconditions: Calculator application is running
•	Test Steps:
1.	Enter the first number as 5
2.	Enter the second number as 3
3.	Select the + operation
4.	Click the = button
•	Expected Result: The result displayed is 8
________________________________________
Test Case 02
•	Test Case ID: TC_CALC_02
•	Test Description: Verify subtraction of a positive and negative integer
•	Preconditions: Calculator application is running
•	Test Steps:
1.	Enter the first number as 7
2.	Enter the second number as -4
3.	Select the - operation
4.	Click the = button
•	Expected Result: The result displayed is 11
________________________________________
Test Case 03
•	Test Case ID: TC_CALC_03
•	Test Description: Verify multiplication of decimal numbers
•	Preconditions: Calculator application is running
•	Test Steps:
1.	Enter the first number as 2.5
2.	Enter the second number as 4
3.	Select the * operation
4.	Click the = button
•	Expected Result: The result displayed is 10.0
Test Case 04
•	Test Case ID: TC_CALC_04
•	Test Description: Verify division of two positive numbers
•	Preconditions: Calculator application is running
•	Test Steps:
1.	Enter the first number as 20
2.	Enter the second number as 5
3.	Select the / operation
4.	Click the = button
•	Expected Result: The result displayed is 4
________________________________________
Test Case 05
•	Test Case ID: TC_CALC_05
•	Test Description: Verify handling division by zero
•	Preconditions: Calculator application is running
•	Test Steps:
1.	Enter the first number as 15
2.	Enter the second number as 0
3.	Select the / operation
4.	Click the = button
•	Expected Result: An error message is displayed saying "Division by zero is not allowed"
________________________________________
Test Case 06
•	Test Case ID: TC_CALC_06
•	Test Description: Verify handling of non-numeric input in the first operand
•	Preconditions: Calculator application is running
•	Test Steps:
1.	Enter the first input as abc
2.	Enter the second number as 5
3.	Select the + operation
4.	Click the = button
•	Expected Result: An error message is displayed saying "Invalid input"
Test Case 07
•	Test Case ID: TC_CALC_07
•	Test Description: Verify handling of non-numeric input in the second operand
•	Preconditions: Calculator application is running
•	Test Steps:
1.	Enter the first number as 5
2.	Enter the second input as xyz
3.	Select the - operation
4.	Click the = button
•	Expected Result: An error message is displayed saying "Invalid input"
________________________________________
Test Case 08
•	Test Case ID: TC_CALC_08
•	Test Description: Verify BODMAS operation is handled correctly
•	Preconditions: Calculator supports full expressions with BODMAS rule
•	Test Steps:
1.	Enter the expression as 2 + 3 * 4
2.	Click the = button
•	Expected Result: The result displayed is 14
________________________________________
Test Case 09
•	Test Case ID: TC_CALC_09
•	Test Description: Verify handling of empty input in the first operand
•	Preconditions: Calculator application is running
•	Test Steps:
1.	Leave the first input blank
2.	Enter the second number as 4
3.	Select the + operation
4.	Click the = button
•	Expected Result: An error message is displayed saying "Input cannot be empty"
________________________________________

Test Case 10
•	Test Case ID: TC_CALC_10
•	Test Description: Verify handling of invalid operation symbol
•	Preconditions: Calculator application is running
•	Test Steps:
1.	Enter the first number as 5
2.	Enter the second number as 3
3.	Select an invalid operation symbol %
4.	Click the = button
•	Expected Result: An error message is displayed saying "Invalid operation"

