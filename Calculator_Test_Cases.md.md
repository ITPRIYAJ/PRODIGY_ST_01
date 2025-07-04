### Test Case 01

*   **Test Case ID**: TC\_CALC\_01
    
*   **Test Description**: Verify addition of two positive integers
    
*   **Preconditions**: Calculator application is running
    
*   **Test Steps**:
    
    1.  Enter the first number as `5`
        
    2.  Enter the second number as `3`
        
    3.  Select the `+` operation
        
    4.  Click the `=` button
        
*   **Expected Result**: The result displayed is `8`
    

* * *

### Test Case 02

*   **Test Case ID**: TC\_CALC\_02
    
*   **Test Description**: Verify subtraction of a positive and negative integer
    
*   **Preconditions**: Calculator application is running
    
*   **Test Steps**:
    
    1.  Enter the first number as `7`
        
    2.  Enter the second number as `-4`
        
    3.  Select the `-` operation
        
    4.  Click the `=` button
        
*   **Expected Result**: The result displayed is `11`
    

* * *

### Test Case 03

*   **Test Case ID**: TC\_CALC\_03
    
*   **Test Description**: Verify multiplication of decimal numbers
    
*   **Preconditions**: Calculator application is running
    
*   **Test Steps**:
    
    1.  Enter the first number as `2.5`
        
    2.  Enter the second number as `4`
        
    3.  Select the `*` operation
        
    4.  Click the `=` button
        
*   **Expected Result**: The result displayed is `10.0`
    

* * *

### Test Case 04

*   **Test Case ID**: TC\_CALC\_04
    
*   **Test Description**: Verify division of two positive numbers
    
*   **Preconditions**: Calculator application is running
    
*   **Test Steps**:
    
    1.  Enter the first number as `20`
        
    2.  Enter the second number as `5`
        
    3.  Select the `/` operation
        
    4.  Click the `=` button
        
*   **Expected Result**: The result displayed is `4`
    

* * *

### Test Case 05

*   **Test Case ID**: TC\_CALC\_05
    
*   **Test Description**: Verify handling division by zero
    
*   **Preconditions**: Calculator application is running
    
*   **Test Steps**:
    
    1.  Enter the first number as `15`
        
    2.  Enter the second number as `0`
        
    3.  Select the `/` operation
        
    4.  Click the `=` button
        
*   **Expected Result**: An error message is displayed saying `"Division by zero is not allowed"`
    

* * *

### Test Case 06

*   **Test Case ID**: TC\_CALC\_06
    
*   **Test Description**: Verify handling of non-numeric input in the first operand
    
*   **Preconditions**: Calculator application is running
    
*   **Test Steps**:
    
    1.  Enter the first input as `abc`
        
    2.  Enter the second number as `5`
        
    3.  Select the `+` operation
        
    4.  Click the `=` button
        
*   **Expected Result**: An error message is displayed saying `"Invalid input"`
    

* * *

### Test Case 07

*   **Test Case ID**: TC\_CALC\_07
    
*   **Test Description**: Verify handling of non-numeric input in the second operand
    
*   **Preconditions**: Calculator application is running
    
*   **Test Steps**:
    
    1.  Enter the first number as `5`
        
    2.  Enter the second input as `xyz`
        
    3.  Select the `-` operation
        
    4.  Click the `=` button
        
*   **Expected Result**: An error message is displayed saying `"Invalid input"`
    

* * *

### Test Case 08

*   **Test Case ID**: TC\_CALC\_08
    
*   **Test Description**: Verify BODMAS operation is handled correctly
    
*   **Preconditions**: Calculator supports full expressions with BODMAS rule
    
*   **Test Steps**:
    
    1.  Enter the expression as `2 + 3 * 4`
        
    2.  Click the `=` button
        
*   **Expected Result**: The result displayed is `14`
    

* * *

### Test Case 09

*   **Test Case ID**: TC\_CALC\_09
    
*   **Test Description**: Verify handling of empty input in the first operand
    
*   **Preconditions**: Calculator application is running
    
*   **Test Steps**:
    
    1.  Leave the first input blank
        
    2.  Enter the second number as `4`
        
    3.  Select the `+` operation
        
    4.  Click the `=` button
        
*   **Expected Result**: An error message is displayed saying `"Input cannot be empty"`
    

* * *

### Test Case 10

*   **Test Case ID**: TC\_CALC\_10
    
*   **Test Description**: Verify handling of invalid operation symbol
    
*   **Preconditions**: Calculator application is running
    
*   **Test Steps**:
    
    1.  Enter the first number as `5`
        
    2.  Enter the second number as `3`
        
    3.  Select an invalid operation symbol `%`
        
    4.  Click the `=` button
        
*   **Expected Result**: An error message is displayed saying `"Invalid operation"`