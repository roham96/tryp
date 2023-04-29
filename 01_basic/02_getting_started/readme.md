# TryP 
#
### Learn php and laravel step by step 
<hr>

PHP Getting Started

Getting Started with PHP
Here, you will learn how easy it is to create dynamic web pages using PHP. Before begin, be sure to have a code editor and some working knowledge of HTML and CSS.

If you're just starting out in web development, start learning from here »

Well, let's get straight into it.

Setting Up a Local Web Server
PHP script execute on a web server running PHP. So before you start writing any PHP program you need the following program installed on your computer.

The Apache Web server
The PHP engine
The MySQL database server
You can either install them individually or choose a pre-configured package for your operating system like Linux and Windows. Popular pre-configured package are XAMPP and WampServer.

WampServer is a Windows web development environment. It allows you to create web applications with Apache2, PHP and a MySQL database. It will also provide the MySQL administrative tool PhpMyAdmin to easily manage your databases using a web browser.

Creating Your First PHP Script
Now that you have successfully installed WampServer on your computer. In this section we will create a very simple PHP script that displays the text "Hello, world!" in the browser window.

Ok, click on the WampServer icon somewhere on your Windows task bar and select the "www directory". Alternatively, you can access the "www" directory through navigating the C:\wamp\www. Create a subdirectory in "www" directory let's say "project".

Now open up your favorite code editor and create a new PHP file then type the following code:

```
<?php
// Display greeting message
echo "Hello, world!";
?>
```

Now save this file as "hello.php" in your project folder (located at C:\wamp\www\project), and view the result in your browser through visiting this URL: http://localhost/project/hello.php.

Alternatively, you can access the "hello.php" file through selecting the localhost option and then select the project folder from the WampSever menu on the taskbar.

PHP can be embedded within a normal HTML web page. That means inside your HTML document you can write the PHP statements, as demonstrated in the follwoing example:

```
<!DOCTYPE HTML>
<html>
<head>
    <title>PHP Application</title>
</head>
<body>
<?php
// Display greeting message
echo 'Hello World!';
?>
</body>
</html>
```

You will learn what each of these statements means in upcoming chapters.