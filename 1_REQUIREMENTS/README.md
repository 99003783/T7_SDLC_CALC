## Requirements

## Introduction-
Calculator is a small, portable electronic device used to perform basic and complex operations of arithmetic. The common components of calculator are keypad, LCD Display, Battery or solar cell. 

## Research-
Some of the most popular calculator types are listed below.
 
Basic Calculators
Scientific Calculators
Graphing Calculators
Financial Calculators
Printing Calculators

Basic Calculators: These are the most common and basic calculators for simple arithmetic calculation like adding, subtracting, multiplication, division, percentage calculation. Some of the calculators have memory and check function as advanced feature. There are two types in Basic Calculator :
1.Pocket Calculator 
2.Desktop Calculator
These calculators most commonly comes in LCD display capacity of 8 digits to 12 digits. Basic Calculator priced from Rs. 100 to Rs. 400 depending on features and brands. Basic calculator generally used in Home and Office.


![bc](https://user-images.githubusercontent.com/78848590/107873607-be06b000-6ed9-11eb-840a-e9fa9f5096e4.png)

Scientific Calculators: These calculators can perform higher arithmetic and trigonometric calculations. It is generally used by higher education students and engineers. 240+ functions makes it easy to perform all types of scientific calculations. Their range varies between Rs. 500 to Rs. 1000 depending on the features and brands.

![sc](https://user-images.githubusercontent.com/78848590/107873754-c6131f80-6eda-11eb-921f-e3a1f8cf6cbb.png)

Graphing Calculators: This is to perform graphical calculation by plotting a graph and has some functions of the scientific calculator. It has quiet a big display and resolution than the others. Their range varies between Rs. 10000 to Rs. 20000 according to features and diffrent brands. 

![gc](https://user-images.githubusercontent.com/78848590/107873967-4c7c3100-6edc-11eb-87b4-c914ecf70557.png)

Financial Calculators: A financial calculator is a calculator that performs financial functions commonly needed in business. For many direct financial calculations it has standalone keys that differentiate it from standard calculators. It may allow the user to program functions that the manufacturer has not provided by default. Their range varies from Rs. 3000 to Rs. 5000 in accordance to the brands and features.

![fc](https://user-images.githubusercontent.com/78848590/107873914-e7284000-6edb-11eb-9ab8-63c62ee2708b.png)

Printing Calculators: These are similar to basic calculator that makes basic arithmetic calculation but has in-built printer to print the data and results in structured way. It is generally used in businesses where immediate print copy has to be made. Their rang varies from Rs. 1000 to Rs. 5000 according to the size, features and brands.

![pc](https://user-images.githubusercontent.com/78848590/107874017-a8df5080-6edc-11eb-8541-399cb56c9389.png)


|Calculator                    |Cost         | Features                                                                                                               |
| :-:                          | :-:         | :-:                                                                                                                    |
|Basic                         |170          |Addition, Subtraction, Multiplication and Division                                                                      |
|Scientific                    |750          |log, natural log and trignometric functions                                                                             |
|Engineer scientific           |1600         |42 built-in Physical Constants                                                                                          |
|Financial                     |3000         |The financial calculators usually have five important keys that represent the 'variables'                               |
|Printing                      |5000         |You can press TIME key to display current time and date. You can press REPRINT key to reprint operation and calculation |            |                              |             |results.                                                                                                                |
|Graphical                     |11800        |plot graphs and even solve equations                                                                                    |
|Programmable Scientific       |15000        |Programmable Scientific Calculator with 664 Functions.With Natural Textbook Display so your functions and equations look|           |                              |             |same as in your textbook.Probability, Calculus, Permutation Combination, Random Number Calculation features.Statistics  |          |                              |             |(List-based Statistics, Standard deviation, Regression analysis)                                                        |


![IMG_20210215_095604](https://user-images.githubusercontent.com/78848639/107906175-7c781280-6f76-11eb-889d-94b9af9ec8c1.jpg)




## Defining the system-
A Smart Calculator is a calculator i.e, portable and is used to perform complex problems.
Here we can perform arithmetic operations, trignometric operations, logarithmic operations, exponential functions and root functions.

## SWOT ANALYSIS


![Screenshot (768)](https://user-images.githubusercontent.com/78849093/110676451-fad47700-81f9-11eb-8bb0-91e67c6deabb.png)


## 4W&1H-

What: User friendly and pocket friendly Calculator.

Who: People of any age group can use the calculator as it is user friendly i.e, students in schools and colleges, Officer’s in industries, self- employees.

When: It is used for students for saving time and for Officer’s, employees for complex calculations (use Scientific calculator), physics formulae for students.

Why: For saving time.

How: By operating manually for analog calculators and using screen touch for smart calculators.

# Detail requirements
## High Level Requirements:
 
| ID    | Description                        |
| :-:   | :-:                                |
|HLR_1  |Arithmatic Operations               |
|HLR_2  |Trigonometric Operations            |
|HLR_3  |Logarithmic Operations and cube root| 
|HLR_4  |Mathprint                           |
|HLR_5  |Roots & Power                       |
|HLR_6  |Memory Storage                      |
|HLR_7  |Binary to Decimal                   |
|HLR_8  |Complex Numbers                     |



##  Low level Requirements:

|Requirement                 |Description                                                                                                                              |
| :-:                        | :-:                                                                                                                                     |
|Binary to Decimal Conversion|Take the input in form of only 1s and 0s as long through keypad and accordingly give the output as an int.                               |
|Root and Power              |Take input as a double and find the square root and give output in double type. To find power take inputs as int for both number and the |       |                            |exponent and return output as long.                                                                                                      |      
|Arithmetic Operations       |                                                                                                                                         |
|Addition                    |Input validation:check the ASCII value range of the user input numbers.Input type: integer, float.                                       |
|                            |Operation: Take two inputs from the user and check the data type.                                                                        |
|                            |If the inputs are in float data type; the results will be in floating point.If the inputs are in integer data type;                      | 
|                            |the result will be in integer data type.If the inputs are in combination of integer as well as floating type;                            |
|                            |then the result should be in floating type.                                                                                              |
|Subtraction:                |Input validation: check the ASCII value range of the user input numbers.Input type: integer, float.                          |
|                            |Operation: Take two inputs from the user and check the data type.Sign of both the input values must be considered and accordingly the    |      |                            |subtraction operation must be performed. If the inputs are in float data type; the results will be in floating point.If the inputs are in|      |                            |integer data type; the result will be in integer data type.If the inputs are in combination of integer as well as floating type; then the|
|                            |result should be in floating type.                                                                                                       |
|Multiplication:             |Input validation: Check the ASCII value range of the user input numbers. Also check the sign of the user input numbers.                  |
|                            |Input type: integer, float. Operation: Take two inputs from the user and check the data type.Sign of both the input values must be       |
|                            |considered and accordingly the multiplication operation must be performed. If the inputs are in float data type; the results will be in  | 
|                            |floating point.If the inputs are in integer data type; the result will be in integer data type.If the inputs are in combination of integer| 
|                            |as well as floating type; then the result should be in floating type.                                                                     |
|Division:                   |Input Validation: Check the ASCII value range of the user input numbers.Also check the sign of the user input numbers.                    |
|                            |Divide by zero is not possible. Input type: integer, float.Operation: Take two inputs from the user and check the data type.              |
|                            |Sign of both the input values must be considered and accordingly the division operation must be performed.                                |
|                            |If the inputs are in float data type; the results will be in floating point.If the inputs are in integer data type; the result will be in |     |                            |integer data type.If the inputs                                                                                                           |
|                            |are in combination of integer as well as floating type; then the result should be in floating type.                                       |
|Memory Storage              |A history button is created which shows the last five stored results.When the user hits the HISTORY button it will display the last five  |
|                            |stored value. Operation: Works with arrays.                                                                                               |                                                                                                       
| Complex mode               | It is used to calculate with the real and imaginary numbers in a single mode. |
| Math Print | It takes the input, calculates it and shows the result as well as the input together. |
|Trignometric Functions | Finding values for sin(), cos(),tan(),sec(),cosec(),cot() functions.|
|Exponential functions | To perform logarithmic functions and cube root functions. |

	

