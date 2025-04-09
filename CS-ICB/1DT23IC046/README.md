The TemperatureConverter class is a simple Java program that allows users to convert temperatures between Celsius and Fahrenheit. Here's a breakdown of the program's functionality:

Features:
User Interface:

The program first displays a menu that provides two options:

Convert from Celsius to Fahrenheit.

Convert from Fahrenheit to Celsius.

Input Handling:

The user is prompted to choose one of the two options (1 or 2) by entering the corresponding number.

Then, based on the user's choice, the program asks for a temperature input.

Conversion Logic:

Celsius to Fahrenheit Conversion:

If the user selects option 1 (Celsius to Fahrenheit), the program asks the user to input a temperature in Celsius.

The temperature is then converted to Fahrenheit using the formula:

Fahrenheit=(Celsius * 9/5)+32

The result is displayed in Fahrenheit.

Fahrenheit to Celsius Conversion:

If the user selects option 2 (Fahrenheit to Celsius), the program asks the user to input a temperature in Fahrenheit.

The temperature is then converted to Celsius using the formula:

Celsius =(Fahrenheit−32)*5/9
​
 
The result is displayed in Celsius.

Error Handling:

If the user selects an invalid option (i.e., a number other than 1 or 2), the program displays an error message: "Invalid option!"

Closing the Scanner:

At the end of the program, the scanner.close() statement is used to close the Scanner object, releasing system resources.
