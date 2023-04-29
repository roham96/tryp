# TryP 
#
### Learn php and laravel step by step 
<hr>

PHP Constants

What is Constant in PHP
A constant is a name or an identifier for a fixed value. Constant are like variables, except that once they are defined, they cannot be undefined or changed (except magic constants).

Constants are very useful for storing data that doesn't change while the script is running. Common examples of such data include configuration settings such as database username and password, website's base URL, company name, etc.

Constants are defined using PHP's define() function, which accepts two arguments: the name of the constant, and its value. Once defined the constant value can be accessed at any time just by referring to its name. Here is a simple example:

```
<?php
// Defining constant
define("SITE_URL", "https://www.tutorialrepublic.com/");
 
// Using constant
echo 'Thank you for visiting - ' . SITE_URL;
?>
```
The output of the above code will be:

Naming Conventions for PHP Constants
Name of constants must follow the same rules as variable names, which means a valid constant name must starts with a letter or underscore, followed by any number of letters, numbers or underscores with one exception: the $ prefix is not required for constant names.