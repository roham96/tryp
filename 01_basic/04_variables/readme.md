# TryP 
#
### Learn php and laravel step by step 
<hr>

PHP Variables

What is Variable in PHP
Variables are used to store data, like string of text, numbers, etc. Variable values can change over the course of a script. Here're some important things to know about variables:

In PHP, a variable does not need to be declared before adding a value to it. PHP automatically converts the variable to the correct data type, depending on its value.
After declaring a variable it can be reused throughout the code.
The assignment operator (=) used to assign value to a variable.
In PHP variable can be declared as: $var_name = value;

```
<?php
// Declaring variables
$txt = "Hello World!";
$number = 10;
 
// Displaying variables value
echo $txt;  // Output: Hello World!
echo $number; // Output: 10
?>
```
In the above example we have created two variables where first one has assigned with a string value and the second has assigned with a number. Later we've displayed the variables values in the browser using the echo statement. The PHP echo statement is often used to output data to the browser. We will learn more about this in upcoming chapter.

Naming Conventions for PHP Variables
These are the following rules for naming a PHP variable:

All variables in PHP start with a $ sign, followed by the name of the variable.
A variable name must start with a letter or the underscore character _.
A variable name cannot start with a number.
A variable name in PHP can only contain alpha-numeric characters and    underscores (A-z, 0-9, and _).
A variable name cannot contain spaces.