# TryP 
#
### Learn php and laravel step by step 
<hr>

PHP Echo and Print Statements

The PHP echo Statement
The echo statement can output one or more strings. In general terms, the echo statement can display anything that can be displayed to the browser, such as string, numbers, variables values, the results of expressions etc.

Since echo is a language construct not actually a function (like if statement), you can use it without parentheses e.g. echo or echo(). However, if you want to pass more than one parameter to echo, the parameters must not be enclosed within parentheses.

Display Strings of Text
The following example will show you how to display a string of text with the echo statement:

```
<?php
// Displaying string of text
echo "Hello World!";
?>
```
The output of the above PHP code will look something like this:

Hello World!

```
<?php
// Displaying HTML code
echo "<h4>This is a simple heading.</h4>";
echo "<h4 style='color: red;'>This is heading with style.</h4>";
?>
```
The output of the above PHP code will look something like this:

This is a simple heading.
</br>
<font color="red"> This is heading with style. </font>


```
<?php
// Defining variables
$txt = "Hello World!";
$num = 123456789;
$colors = array("Red", "Green", "Blue");
 
// Displaying variables
echo $txt;
echo "<br>";
echo $num;
echo "<br>";
echo $colors[0];
?>
```

The output of the above PHP code will look something like this:

```
Hello World!
123456789
Red
```

The PHP print Statement
You can also use the print statement (an alternative to echo) to display output to the browser. Like echo the print is also a language construct not a real function. So you can also use it without parentheses like: print or print().

Both echo and print statement works exactly the same way except that the print statement can only output one string, and always returns 1. That's why the echo statement considered marginally faster than the print statement since it doesn't return any value.

Display Strings of Text
The following example will show you how to display a string of text with the print statement:
```
<?php
// Displaying string of text
print "Hello World!";
?>
```
The output of the above PHP code will look something like this:

Hello World!
Display HTML Code
The following example will show you how to display HTML code using the print statement:

```
<?php
// Displaying HTML code
print "<h4>This is a simple heading.</h4>";
print "<h4 style='color: red;'>This is heading with style.</h4>";
?>
```
The output of the above PHP code will look something like this:

This is a simple heading.
</br>
<font color="red"> This is heading with style. </font>

Display Variables
The following example will show you how to display variable using the print statement:

```
<?php
// Defining variables
$txt = "Hello World!";
$num = 123456789;
$colors = array("Red", "Green", "Blue");
 
// Displaying variables
print $txt;
print "<br>";
print $num;
print "<br>";
print $colors[0];
?>
```

The output of the above PHP code will look something like this:

```
Hello World!
123456789
Red
```