# PHP Test

The following are a set of two developer tests that we ask prospective staff to complete before face-to-face interviews. 
They are intended to assess skills in PHP.

Please ensure you send us all files required to run the scripts. We will test your submission using PHP 7.1

You are free to send multiple files to answer the questions but all files created to answer this test must be created 
within the time allocated.

You are not allowed to use any external libraries or code snippets (i.e. no jQuery, web frameworks or any pre-written 
libraries you may have). The only exception to this is you may use a testing framework for question 2 if you wish 
(e.g. PHPUnit), but there is no requirement to do so.

Please answer as many of the questions as you can within 3 hours.

# 1 – Multidimensional array

Display the list of books in an HTML page based on the data array in _data.php_, outputting all content in the data 
array to the page. 

You should include functionality on the page that allows the user to sort the data by:
 
* Name (ascending)
* Price (cheapest first)

And filter the data by:

* Only show books released in 2016
* Only show books released in 2015
* Show all books

By default display all books, sorted by Price (cheapest first).

The format of your answer should be a PHP script (to be accessed via a web browser) that outputs a valid HTML document. 
The primary focus of the test is PHP, so please don’t spend lots of time crafting beautiful CSS – it’s not necessary. 
However, it is expected that you use appropriate and clean HTML to output results.
￼￼￼￼￼￼￼￼
# 2 - OO

Write a number of PHP classes to represent the following business rules:

* Each employee is either a Manager or Staff
* All Staff have a Staff ID, Email address and Password
* Staff ID cannot be changed once set
* Managers also have a Telephone number

Please test these business rules using the following tests. At their simplest the test should be a single PHP script
that contains code to run these tests. You may use a testing framework (e.g. PHPUnit) for this element if you wish.  

* I can create an employee setting ID and email
* I can only set a valid email address for an employee
* I cannot change the Staff ID once set
* I can set a password and this is stored securely (e.g. I cannot return the password in plain text)
* I can check to see if the stored password is the same as an inputted password
* I can only set a Telephone number on a Manager
* I can test whether an employee is a Manager

The format of your answer can either be a PHP script run on the CLI or a PHP script (to be accessed via a web browser) 
that outputs a valid HTML document.
￼￼
