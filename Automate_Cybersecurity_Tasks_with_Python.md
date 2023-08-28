## Content



[Terms](#terms)

[Get to know Python](#get-to-know-python)

[Python environments](#python-environments)

[More about data types](#more-about-data-types)

[Assign and reassign variables in Python](#assign-and-reassign-variables-in-python)

[More on conditionals in Python](#more-on-conditionals-in-python)

[Python functions in cybersecurity](#python-functions-in-cybersecurity)

[Functions and variables](#functions-and-variables)

[Work with built-in functions](#work-with-built-in-functions)

[Import modules and libraries in Python](#import-modules-and-libraries-in-python)

[Ensure proper syntax and readability in Python](#ensure-proper-syntax-and-readability-in-python)

[Strings and the security analyst](#strings-and-the-security-analyst)

[Lists and the security analyst](#lists-and-the-security-analyst)

[More about regular expressions](#more-about-regular-expressions)

[Essential Python components for automation](#essential-python-components-for-automation)

[Import files into Python](#import-files-into-python)

[Work with files in Python](#work-with-files-in-python)

[Explore debugging techniques](#explore-debugging-techniques)

[Activities](#activities)

[Content](#content)

[Courses list](README.md#contents)




## Terms 

### A

Algorithm: A set of rules that solve a problem

Argument (Python): The data brought into a function when it is called
Automation: The use of technology to reduce human and manual effort to perform common and repetitive tasks

### B

Boolean data: Data that can only be one of two values: either True or False
Bracket notation: The indices placed in square brackets 
Built-in function: A function that exists within Python and can be called directly

### C

Command-line interface: A text-based user interface that uses commands to interact with the computer
Comment: A note programmers make about the intention behind their code
Conditional statement: A statement that evaluates code to determine if it meets a specified set of conditions

### D

Data type: A category for a particular type of data item
Debugger: A software tool that helps to locate the source of an error and assess its causes
Debugging: The practice of identifying and fixing errors in code
Dictionary data: Data that consists of one or more key-value pairs

### E

Exception: An error that involves code that cannot be executed even though it is syntactically correct

### F

File path: The location of a file or directory 
Float data: Data consisting of a number with a decimal point
Function: A section of code that can be reused in a program

### G

Global variable: A variable that is available through the entire program

### I

Immutable: An object that cannot be changed after it is created and assigned a value
Indentation: Space added at the beginning of a line of code
Index: A number assigned to every element in a sequence that indicates its position
Integer data: Data consisting of a number that does not include a decimal point
Integrated development environment (IDE): A software application for writing code that provides editing assistance and error correction tools
Interpreter: A computer program that translates Python code into runnable instructions line by line 
Iterative statement: Code that repeatedly executes a set of instructions

### K

Key-value pair: A set of data that represents two linked items: a key, and its corresponding value

### L

Library: A collection of modules that provide code users can access in their programs
List concatenation: The concept of combining two lists into one by placing the elements of the second list directly after the elements of the first list
List data: Data structure that consists of a collection of data in sequential form
Local variable: A variable assigned within a function
Log: A record of events that occur within an organization's systems
Logic error: An error that results when the logic used in code produces unintended results
Loop variable: A variable that is used to control the iterations of a loop

### M

Method: A function that belongs to a specific data type
Module: A Python file that contains additional functions, variables, classes, and any kind of runnable code

### N

Notebook: An online interface for writing, storing, and running code  

### P

Parameter (Python): An object that is included in a function definition for use in that function
Parsing: The process of converting data into a more readable format
PEP 8 style guide: A resource that provides stylistic guidelines for programmers working in Python 
Programming: A process that can be used to create a specific set of instructions for a computer to execute tasks
Python Standard Library: An extensive collection of Python code that often comes packaged with Python

### R

Regular expression (regex): A sequence of characters that forms a pattern
Return statement: A Python statement that executes inside a function and sends information back to the function call  

### S

Set data: Data that consists of an unordered collection of unique values
String concatenation: The process of joining two strings together
String data: Data consisting of an ordered sequence of characters
Style guide: A manual that informs the writing, formatting, and design of documents
Substring: A continuous sequence of characters within a string
Syntax: The rules that determine what is correctly structured in a computing language
Syntax error: An error that involves invalid usage of a programming language

### T

Tuple data: Data structure that consists of a collection of data that cannot be changed
Type error: An error that results from using the wrong data type

### U

User-defined function: A function that programmers design for their specific needs

### V

Variable: A container that stores data


[Content](#content)



## Get to know Python

In this reading, you will explore how programming works, how a computer processes the Python programming language, and how Python is used in cybersecurity.

### How programming works

Programming is a process that can be used to create a specific set of instructions for a computer to execute tasks. Computer programs exist everywhere. Computers, cell phones, and many other electronic devices are all given instructions by computer programs. 
There are multiple programming languages used to create computer programs. Python is one of these. Programming languages are converted to binary numbers, which are a series of 0s and 1s that represent the operations that the computer's central processing unit (CPU) should perform. Each instruction corresponds to a specific operation, such as adding two numbers or loading a value from memory. 
It would be very time-consuming for humans to communicate this way. Programming languages like Python make it easier to write code because you can use less syntax when instructing computers to perform complex processes.

### Using Python to program

Python is a general purpose programming language that can be used to solve a variety of problems. For example, it can be used to build websites, perform data analysis, and automate tasks. 
Python code must be converted through an interpreter before the computer can process it. An interpreter is a computer program that translates Python code into runnable instructions line by line. 

### Python versions

There are multiple versions of Python. In this course, you are using Python 3. While using Python, it's important to keep track of the version you're using. There are differences in the syntax of each version. Syntax refers to the rules that determine what is correctly structured in a computing language.

### Python in cybersecurity

In cybersecurity, Python is used especially for automation. Automation is the use of technology to reduce human and manual effort to perform common and repetitive tasks. These are some specific areas of cybersecurity in which Python might be used to automate specific tasks:
    • Log analysis
    • Malware analysis
    • Access control list management
    • Intrusion detection
    • Compliance checks
    • Network scanning

[Content](#content)


## Python environments

You can run Python through a variety of environments. These environments include notebooks, integrated development environments (IDEs), and the command line. This reading will introduce you to these environments. It will focus primarily on notebooks because this is how you'll interact with Python in this course.

### Notebooks

One way to write Python code is through a notebook. In this course, you'll interact with Python through notebooks. A notebook is an online interface for writing, storing, and running code. They also allow you to document information about the code. Notebook content either appears in a code cell or markdown cell.

### Code cells

Code cells are meant for writing and running code. A notebook provides a mechanism for running these code cells. Often, this is a play button located within the cell. When you run the code, its output appears after the code. 

### Markdown cells

Markdown cells are meant for describing the code. They allow you to format text in the markdown language. Markdown language is used for formatting plain text in text editors and code editors. For example, you might indicate that text should be in a certain header style. 

### Common notebook environments

Two common notebook environments are Jupyter Notebook and Google Colaboratory (or Google Colab). They allow you to run several programming languages, including Python. 

### Integrated development environments (IDEs)

Another option for writing Python code is through an integrated development environment (IDE), or a software application for writing code that provides editing assistance and error correction tools. Integrated development environments include a graphical user interface (GUI) that provides programmers with a variety of options to customize and build their programs. 

### Command line

The command line is another environment that allows you to run Python programs. Previously, you learned that a command-line interface (CLI) is a text-based user interface that uses commands to interact with the computer. By entering commands into the command line, you can access all files and directories saved on your hard drive, including files containing Python code you want to run. You can also use the command line to open a file editor and create a new Python file.


[Content](#content)


## More about data types

Previously, you explored data types in Python. A data type is a category for a particular type of data item. You focused on string, list, float, integer, and Boolean data. These are the data types you'll work with in this course. This reading will expand on these data types. It will also introduce three additional types.

### String

In Python, string data is data consisting of an ordered sequence of characters. Characters in a string may include letters, numbers, symbols, and spaces. These characters must be placed within quotation marks. These are all valid strings:
    • "updates needed"
    • "20%"
    • "5.0"
    • "35"
    • "**/**/**" 
    • ""
Note: The last item (""), which doesn't contain anything within the quotation marks, is called an empty string.
You can use the print() function to display a string. You can explore this by running this code: 
```py

print("updates needed")
```

The code prints "updates needed". 
You can place strings in either double quotation marks ("") or single quotation marks (''). The following code demonstrates that the same message prints when the string is in single quotation marks:
```py
print('updates needed') 
```
Note: Choosing one type of quotation marks and using it consistently makes it easier to read your code. This course uses double quotation marks.

### List

In Python, list data is a data structure that consists of a collection of data in sequential form. Lists elements can be of any data type, such as strings, integers, Booleans, or even other lists. The elements of a list are placed within square brackets, and each element is separated by a comma. The following lists contains elements of various data types:
    • [12, 36, 54, 1, 7]
    • ["eraab", "arusso", "drosas"]
    • [True, False, True, True]
    • [15, "approved", True, 45.5, False]
    • []
Note: The last item [], which doesn't contain anything within the brackets, is called an empty list.
You can also use the print() function to display a list:

```py
print([12, 36, 54, 1, 7])
```

This displays a list containing the integers 12, 36, 54, 1, and 7.

### Integer

In Python, integer data is data consisting of a number that does not include a decimal point. These are all examples of integer data:
    • -100 
    • -12
    • -1
    • 0
    • 1
    • 20
    • 500 
Integers are not placed in quotation marks. You can use the print() function to display an integer. When you run this code, it displays 5: 

```py
print(5)
```
You can also use the print() function to perform mathematical operations with integers. For example, this code adds two integers:

```py
print(5 + 2)
```
The result is 7. You can also subtract, multiply, or divide two integers.

### Float

Float data is data consisting of a number with a decimal point. All of the following are examples of float data: 
    • -2.2
    • -1.34
    • 0.0
    • 0.34 
Just like integer data, float data is not placed in quotation marks. In addition, you can also use the print() function to display float data or to perform mathematical calculations with float data. You can run the following code to review the result of this calculation:

```py
print(1.2 + 2.8)
```
The output is 4.0.
Note: Dividing two integer values or two float values results in float output when you use the symbol /:


```py
print(1/4)
print(1.0/4.0)
```
The output of both calculations is the float value of .25.  
If you want to return a whole number from a calculation, you must use the symbol // instead:


```py
print(1//4)
print(1.0//4.0)
```
It will round down to the nearest whole number. In the case of print(1//4), the output is the integer value of 0 because using this symbol rounds down the calculation from .25 to the nearest whole number. In the case of print(1.0//4.0), the output is the float value of 0.0 because it maintains the float data type of the values in the calculation while also rounding down to the nearest whole number.

### Boolean

Boolean data is data that can only be one of two values: either True or False.
You should not place Boolean values in quotation marks. When you run the following code, it displays the Boolean value of True:


```py
print(True)
```
You can also return a Boolean value by comparing numbers. Because 9 is not greater than 10, this code evaluates to False:


```py
print(9 > 10)
```

### Additional data types

In this course, you will work with the string, list, integer, float and Boolean data types, but there are other data types. These additional data types include tuple data, dictionary data, and set data.

### Tuple

Tuple data is a data structure that consists of a collection of data that cannot be changed. Like lists, tuples can contain elements of varying data types. 
A difference between tuple data and list data is that it is possible to change the elements in a list, but it is not possible to change the elements in a tuple. This could be useful in a cybersecurity context. For example, if software identifiers are stored in a tuple to ensure that they will not be altered, this can provide assurance that an access control list will only block the intended software.
The syntax of a tuple is also different from the syntax of a list. A tuple is placed in parentheses rather than brackets. These are all examples of the tuple data type:
    • ("wjaffrey", "arutley", "dkot")
    • (46, 2, 13, 2, 8, 0, 0)
    • (True, False, True, True)
    • ("wjaffrey", 13, True)
Pro tip: Tuples are more memory efficient than lists, so they are useful when you are working with a large quantity of data.

### Dictionary

Dictionary data is data that consists of one or more key-value pairs. Each key is mapped to a value. A colon (:) is placed between the key and value. Commas separate key-value pairs from other key-value pairs, and the dictionary is placed within curly brackets ({}). 
Dictionaries are useful when you want to store and retrieve data in a predictable way. For example, the following dictionary maps a building name to a number. The building name is the value, and the number is the key. A colon is placed after the key.
{ 1: "East",
  2: "West",
  3: "North",
  4: "South" }

### Set

In Python, set data is data that consists of an unordered collection of unique values. This means no two values in a set can be the same. 
Elements in a set are always placed within curly brackets and are separated by a comma. These elements can be of any data type. This example of a set contains strings of usernames:
{"jlanksy", "drosas", "nmason"}

[Content](#content)


## Assign and reassign variables in Python

Previously, you've explored variables and how to assign and reassign them in Python. In this reading, you'll expand your understanding of these topics. You’ll also learn about the general practice of naming variables so that you can avoid syntax errors and improve code readability. 

### What are variables?

In a programming language, a variable is a container that stores data. It's a named storage location in a computer's memory that can hold a value. It stores the data in a particular data type, such as integer, string, or Boolean. The value that is stored in a variable can change. 
You can think of variables as boxes with labels on them. Even when you change the contents of a box, the label on the box itself remains the same. Similarly, when you change the value stored in a variable, the name of the variable remains the same. 
Security analysts working in Python will use a variety of variables. Some examples include variables for login attempts, allow lists, and addresses.

### Working with variables

In Python, it's important to know both how to assign variables and how to reassign them.

### Assigning and reassigning variables

If you want to create a variable called username and assign it a value of "nzhao", place the variable to the left of the equals sign and its value to the right:

```py
# Assign 'username'
username = "nzhao"
```
If you later reset this username to "zhao2", you still refer to that variable container as username.
```py
# Reassign 'username'
username = "zhao2"
```

Although the contents have changed from "nzhao" to "zhao2", the variable username remains the same. 
Note: You must place "nzhao" and "zhao2" in quotation marks because they're strings. Python automatically assigns a variable its data type when it runs. For example, when the username variable contains the string "nzhao", it’s assigned a string data type.

### Assigning variables to variables

Using a similar process, you can also assign variables to other variables. In the following example, the variable username is assigned to a new variable old_username:
```py
# Assign a variable to another variable
username = "nzhao"
old_username = username
```

Because username contains the string value of "nzhao" and old_username contains the value of username, old_username now contains a value of "nzhao".

### Putting it together

The following code demonstrates how a username can be updated. The username variable is assigned an initial value, which is then stored in a second variable called old_username. After this, the username variable is reassigned a new value. You can run this code to get a message about the previous username and the current username:

```py
username = "nzhao"
old_username = username
username = "zhao2"
print("Previous username:", old_username)
print("Current username:", username)
```


### Best practices for naming variables

You can name a variable almost anything you want, but there are a few guidelines you should follow to ensure correct syntax and prevent errors:
    • Use only letters, numbers, and underscores in variable names. Valid examples: date_3, username, interval2
    • Start a variable name with a letter or underscore. Do not start it with a number. Valid examples: time,  _login
    • Remember that variable names in Python are case-sensitive. These are all different variables: time, Time, TIME, timE.
    • Don't use Python’s built-in keywords or functions for variable names. For example, variables shouldn't be named True, False, or if.  
Additionally, you should follow these stylistic guidelines to make your code easier for you and other security analysts to read and understand:
    • Separate two or more words with underscores. Valid examples: login_attempts, invalid_user, status_update
    • Avoid variables with similar names. These variables could be easily confused with one another: start_time, starting_time, time_starting.
    • Avoid unnecessarily long names for variables. For instance, don't give variables names like variable_that_equals_3.
    • Names should describe the data and not be random words. Valid examples: num_login_attempts, device_id, invalid_usernames
Note: Using underscores to separate multiple words in variables is recommended, but another convention that you might encounter is capitalizing the first letter of each word except the first word. Example: loginAttempt

[Content](#content)



## More on conditionals in Python

Previously, you explored conditional statements and how they’re useful in automating tasks in Python. So far, you’ve focused on the if and else keywords. In this reading, you’ll review these and learn another keyword, elif. You’ll also learn how you can apply the and, or, and not operators to your conditions.

### How conditional statements work

A conditional statement is a statement that evaluates code to determine whether it meets a specific set of conditions. When a condition is met, it evaluates to a Boolean value of True and performs specified actions. When the condition isn’t met, it evaluates a Boolean value of False and doesn’t perform the specified actions. 
In conditional statements, the condition is often based on a comparison of two values. This table summarizes common comparison operators used to compare numerical values.

| Operator | Use               | 
|----------|-------------------| 
| >        | greater than      | 
| <        | less than         | 
| >=       | greater than or equal to | 
| <=       | less than or equal to    | 
| ==       | equal to          | 
| !=       | not equal to      | 


Note: The equal to (==) and not equal to (!=) operators are also commonly used to compare string data.

### if statements

The keyword if starts a conditional statement. It’s a necessary component of any conditional statement. In the following example, if begins a statement that tells Python to print an "OK" message when the HTTP response status code equals 200:
if status == 200:
    print("OK")
This code consists of a header and a body.

#### The header of an if statement

The first line of this code is the header. In the header of an if statement, the keyword if is followed by the condition. Here, the condition is that the status variable is equal to a value of 200. The condition can be placed in parentheses:
```py
if (status == 200):
    print("OK")
```

In cases like this one, placing parentheses around conditions in Python is optional. You might want to include them if it helps you with code readability. However, this condition will be processed the same way if written without parentheses. 
In other situations, because Python evaluates the conditions in parentheses first, parentheses can affect how Python processes conditions. You will read more about one of these in the section of this reading on not.
Note: You must always place a colon (:) at the end of the header. Without this syntax, the code will produce an error.

#### The body of an if statement

After the header of an if statement comes the body of the if statement. This tells Python what action or actions to perform when the condition evaluates to True. In this example, there is just one action, printing "OK" to the screen. In other cases, there might be more lines of code with additional actions.
Note: For the body of the if statement to execute as intended, it must be indented further than the header. Additionally, if there are multiple lines of code within the body, they must all be indented consistently. 

### Continuing conditionals with else and elif

In the previous example, if the HTTP status response code was not equal to 200, the condition would evaluate to False and Python would continue with the rest of the program. However, it’s also possible to specify alternative actions with else and elif.

#### else statements

The keyword else precedes a code section that only evaluates when all conditions that precede it within the conditional statement evaluate to False.
In the following example, when the HTTP response status code is not equal to 200, it prints an alternative message of "check other status":
```py
if status == 200:
    print("OK")
else:
    print("check other status")
```

Note: Like with if, a colon (:) is required after else, and the body that follows the else header is indented.

#### elif statements

In some cases, you might have multiple alternative actions that depend on new conditions. In that case, you can use elif. The elif keyword precedes a condition that is only evaluated when previous conditions evaluate to False. Unlike with else, there can be multiple elif statements following if.
For example, you might want to print one message if the HTTP response status code is 200, one message if it is 400, and one if it is 500. The following code demonstrates how you can use elif for this:
```py
if status == 200:
    print("OK")
elif status == 400:
    print("Bad Request")
elif status == 500:
    print("Internal Server Error")
```
 
Python will first check if the value of status is 200, and if this evaluates to False, it will go onto the first elif statement. There, it will check whether the value of status is 400. If that evaluates to True, it will print "Bad Request", but if it evaluates to False, it will go on to the next elif statement. 
If you want the code to print another message when all conditions evaluate to False, then you can incorporate else after the last elif. In this example, if it reaches the else statement, it prints a message to check the status:
```py
if status == 200:
    print("OK")
elif status == 400:
    print("Bad Request")
elif status == 500:
    print("Internal Server Error")
else:
    print("check other status")
```

Just like with if and else, it’s important to place a colon (:) after the elif header and indent the code that follows this header.
Note: Python processes multiple elif statements differently than multiple if statements. When it reaches an elif statement that evaluates to True, it won’t check the following elif statements. On the other hand, Python will run all if statements.


### Logical operators for multiple conditions

In some cases, you might want Python to perform an action based on a more complex condition. You might require two conditions to evaluate to True. Or, you might require only one of two conditions to evaluate to True. Or, you might want Python to perform an action when a condition evaluates to False. The operators and, or, and not can be used in these cases.

#### and

The and operator requires both conditions on either side of the operator to evaluate to True. For example, all HTTP status response codes between 200 and 226 relate to successful responses. You can use and to join a condition of being greater than or equal to 200 with another condition of being less than or equal to 226:
```py
if status >= 200 and status <= 226:
    print("successful response")
```

When both conditions are True, then the "successful response" message will print.

#### or

The or operator requires only one of the conditions on either side of the operator to evaluate to True. For example, both a status code of 100 and a status code of 102 are informational responses. Using or, you could ask Python to print an "informational response" message when the code is either 100 or 102:
```py
if status == 100 or status == 102:
    print("informational response")
```

Only one of these conditions needs to be met for Python to print the message.

#### not

The not operator negates a given condition so that it evaluates to False if the condition is True and to True if it is False. For example, if you want to indicate that Python should check the status code when it’s something outside of the successful range, you can use not:
```py
if not(status >= 200 and status <= 226):
    print("check status")
```

Python first checks whether the value of status is greater than or equal to 200 and less than or equal to 226, and then because of the operator not, it inverts this. This means it will print the message if status is less than 200 or greater than 226.
Note: In this case, the parentheses are necessary for the code to apply not to both conditions. Python will evaluate the conditions within the parentheses first. This means it will first evaluate the conditions on either side of the and operator and then apply not to both of them.


[Content](#content)

## More on loops in Python

Previously, you explored iterative statements. An iterative statement is code that repeatedly executes a set of instructions. Depending on the criteria, iterative statements execute zero or more times. We iterated through code using both for loops and while loops. In this reading, you’ll recap the syntax of loops. Then, you'll learn how to use the break and continue keywords to control the execution of loops.

### for loops
If you need to iterate through a specified sequence, you should use a for loop. 
The following for loop iterates through a sequence of usernames. You can run it to observe the output:
```py
for i in ["elarson", "bmoreno", "tshah", "sgilmore"]:
    print(i)
```

The first line of this code is the loop header. In the loop header, the keyword for signals the beginning of a for loop. Directly after for, the loop variable appears. The loop variable is a variable that is used to control the iterations of a loop. In for loops, the loop variable is part of the header. In this example, the loop variable is i. 
The rest of the loop header indicates the sequence to iterate through. The in operator appears before the sequence to tell Python to run the loop for every item in the sequence. In this example, the sequence is the list of usernames. The loop header must end with a colon (:). 
The second line of this example for loop is the loop body. The body of the for loop might consist of multiple lines of code. In the body, you indicate what the loop should do with each iteration. In this case, it's to print(i), or in other words, to display the current value of the loop variable during that iteration of the loop. For Python to execute the code properly, the loop body must be indented further than the loop header. 
Note: When used in a for loop, the in operator precedes the sequence that the for loop will iterate through. When used in a conditional statement, the in operator is used to evaluate whether an object is part of a sequence.  The example if "elarson" in ["tshah", "bmoreno", "elarson"] evaluates to True because "elarson" is part of the sequence following in.

### Looping through a list

Using for loops in Python allows you to easily iterate through lists, such as a list of computer assets. In the following for loop, asset is the loop variable and another variable, computer_assets, is the sequence. The computer_assets variable stores a list. This means that on the first iteration the value of asset will be the first element in that list, and on the second iteration, the value of asset will be the second element in that list. You can run the code to observe what it outputs: 
```py
computer_assets = ["laptop1", "desktop20", "smartphone03"]
for asset in computer_assets:
    print(asset)
```


Note: It is also possible to loop through a string. This will return every character one by one. You can observe this by running the following code block that iterates through the string "security":
```py
string = "security"
for character in string:
    print(character)
```


### Using range()

Another way to iterate through a for loop is based on a sequence of numbers, and this can be done with range(). The range() function generates a sequence of numbers. It accepts inputs for the start point, stop point, and increment in parentheses. For example, the following code indicates to start the sequence of numbers at 0, stop at 5, and increment each time by 1:
range(0, 5, 1)
Note: The start point is inclusive, meaning that 0 will be included in the sequence of numbers, but the stop point is exclusive, meaning that 5 will be excluded from the sequence. It will conclude one integer before the stopping point.
When you run this code, you can observe how 5 is excluded from the sequence:
```py
for i in range(0, 5, 1):
    print(i)
```


You should be aware that it's always necessary to include the stop point, but if the start point is the default value of 0 and the increment is the default value of 1, they don't have to be specified in the code. If you run this code, you will get the same results:
```py
for i in range(5):
    print(i)
```

Note: If the start point is anything other than 0 or the increment is anything other than 1, they should be specified.

### while loops

If you want a loop to iterate based on a condition, you should use a while loop. As long as the condition is True, the loop continues, but when it evaluates to False, the while loop exits. The following while loop continues as long as the condition that i < 5 is True:
```py
i = 1
while i < 5:
    print(i)
    i = i + 1
```

In this while loop, the loop header is the line while i < 5:. Unlike with for loops, the value of a loop variable used to control the iterations is not assigned within the loop header in a while loop. Instead, it is assigned outside of the loop. In this example, i is assigned a starting value of 1 in a line preceding the loop.
The keyword while signals the beginning of a while loop. After this, the loop header indicates the condition that determines when the loop terminates. This condition uses the same comparison operators as conditional statements. Like in a for loop, the header of a while loop must end with a colon (:).
The body of a while loop indicates the actions to take with each iteration. In this example, it is to display the value of i and to increment the value of i by 1. In order for the value of i to change with each iteration, it's necessary to indicate this in the body of the while loop. In this example, the loop iterates four times until it reaches a value of 5.

### Integers in the loop condition

Often, as just demonstrated, the loop condition is based on integer values. For example, you might want to allow a user to log in as long as they've logged in less than five times. Then, your loop variable, login_attempts, can be initialized to 0, incremented by 1 in the loop, and the loop condition can specify to iterate only when the variable is less than 5. You can run the code below and review the count of each login attempt:
```py
login_attempts = 0
while login_attempts < 5:
    print("Login attempts:", login_attempts)
    login_attempts = login_attempts + 1
```

The value of login_attempts went from 0 to 4 before the loop condition evaluated to False. Therefore, the values of 0 through 4 print, and the value 5 does not print.

### Boolean values in the loop condition

Conditions in while loops can also depend on other data types, including comparisons of Boolean data. In Boolean data comparisons, your loop condition can check whether a loop variable equals a value like True or False. The loop iterates an indeterminate number of times until the Boolean condition is no longer True. 
In the example below, a Boolean value is used to exit a loop when a user has made five login attempts. A variable called count keeps track of each login attempt and changes the login_status variable to False when the count equals 4. (Incrementing count from 0 to 4 represents five login attempts.) Because the while condition only iterates when login_status is True, it will exit the loop. You can run this to explore this output: 
```py
count = 0
login_status = True
while login_status == True:
    print("Try again.")
    count = count + 1
    if count == 4:
        login_status = False
```


The code prints a message to try again four times, but exits the loop once login_status is set to False.   

### Managing loops

You can use the break and continue keywords to further control your loop iterations. Both are incorporated into a conditional statement within the body of the loop. They can be inserted to execute when the condition in an if statement is True. The break keyword is used to break out of a loop. The continue keyword is used to skip an iteration and continue with the next one. 
break
When you want to exit a for or while loop based on a particular condition in an if statement being True, you can write a conditional statement in the body of the loop and write the keyword break in the body of the conditional. 
The following example demonstrates this. The conditional statement with break instructs Python to exit the for loop if the value of the loop variable asset is equal to "desktop20". On the second iteration, this condition evaluates to True. You can run this code to observe this in the output: 
```py
computer_assets = ["laptop1", "desktop20", "smartphone03"]
for asset in computer_assets:
    if asset == "desktop20":
        break
    print(asset)
```


As expected, the values of "desktop20" and "smartphone03" don't print because the loop breaks on the second iteration.
continue
When you want to skip an iteration based on a certain condition in an if statement being True, you can add the keyword continue in the body of a conditional statement within the loop. In this example, continue will execute when the loop variable of asset is equal to "desktop20". You can run this code to observe how this output differs from the previous example with break:
```py
computer_assets = ["laptop1", "desktop20", "smartphone03"]
for asset in computer_assets:
    if asset == "desktop20":
        continue
    print(asset)
```

The value "desktop20" in the second iteration doesn't print. However, in this case, the loop continues to the next iteration, and "smartphone03" is printed. 
Infinite loops
If you create a loop that doesn't exit, this is called an infinite loop. In these cases, you should press CTRL-C or CTRL-Z on your keyboard to stop the infinite loop. You might need to do this when running a service that constantly processes data, such as a web server.


[Content](#content)



## Python functions in cybersecurity

Previously, you explored how to define and call your own functions. In this reading, you’ll revisit what you learned about functions and examine how functions can improve efficiency in a cybersecurity setting.

### Functions in cybersecurity

A function is a section of code that can be reused in a program. Functions are important in Python because they allow you to automate repetitive parts of your code. In cybersecurity, you will likely adopt some processes that you will often repeat.
When working with security logs, you will often encounter tasks that need to be repeated. For example, if you were responsible for finding malicious login activity based on failed login attempts, you might have to repeat the process for multiple logs.
To work around that, you could define a function that takes a log as its input and returns all potentially malicious logins. It would be easy to apply this function to different logs.

### Defining a function

In Python, you'll work with built-in functions and user-defined functions. Built-in functions are functions that exist within Python and can be called directly. The print() function is an example of a built-in function.
User-defined functions are functions that programmers design for their specific needs. To define a function, you need to include a function header and the body of your function.

#### Function header

The function header is what tells Python that you are starting to define a function. For example, if you want to define a function that displays an "investigate activity" message, you can include this function header:
```py
def display_investigation_message():
```

The def keyword is placed before a function name to define a function. In this case, the name of that function is display_investigation_message. 
The parentheses that follow the name of the function and the colon (:) at the end of the function header are also essential parts of the syntax.
Pro tip: When naming a function, give it a name that indicates what it does. This will make it easier to remember when calling it later.

#### Function body

The body of the function is an indented block of code after the function header that defines what the function does. The indentation is very important when writing a function because it separates the definition of a function from the rest of the code.
To add a body to your definition of the display_investigation_message() function, add an indented line with the print() function. Your function definition becomes the following:
```py
def display_investigation_message():
    print("investigate activity")
```

### Calling a function

After defining a function, you can use it as many times as needed in your code. Using a function after defining it is referred to as calling a function. To call a function, write its name followed by parentheses. So, for the function you previously defined, you can use the following code to call it:
display_investigation_message()
Although you'll use functions in more complex ways as you expand your understanding, the following code provides an introduction to how the display_investigation_message() function might be part of a larger section of code. You can run it and analyze its output:
```py
def display_investigation_message():
    print("investigate activity")
application_status = "potential concern"
email_status = "okay"
if application_status == "potential concern":
    print("application_log:")
    display_investigation_message()
if email_status == "potential concern":
    print("email log:")
    display_investigation_message()
```

The display_investigation_message() function is used twice within the code. It will print "investigate activity" messages about two different logs when the specified conditions evaluate to True. In this example, only the first conditional statement evaluates to True, so the message prints once.
This code calls the function from within conditionals, but you might call a function from a variety of locations within the code.
Note: Calling a function inside of the body of its function definition can create an infinite loop. This happens when it is not combined with logic that stops the function call when certain conditions are met. For example, in the following function definition, after you first call func1(), it will continue to call itself and create an infinite loop:
```py
def func1():
    func1()
```


[Content](#content)

## Functions and variables

Previously, you focused on working with multiple parameters and arguments in functions and returning information from functions. In this reading, you’ll review these concepts. You'll also be introduced to a new concept: global and local variables.

### Working with variables in functions

Working with variables in functions requires an understanding of both parameters and arguments. The terms parameters and arguments have distinct uses when referring to variables in a function. Additionally, if you want the function to return output, you should be familiar with return statements.

### Parameters

A parameter is an object that is included in a function definition for use in that function. When you define a function, you create variables in the function header. They can then be used in the body of the function. In this context, these variables are called parameters.  For example, consider the following function:
```py
def remaining_login_attempts(maximum_attempts, total_attempts):
    print(maximum_attempts - total_attempts)
```
This function takes in two variables, maximum_attempts and total_attempts and uses them to perform a calculation. In this example, maximum_attempts and total_attempts are parameters.

### Arguments

In Python, an argument is the data brought into a function when it is called. When calling remaining_login_attempts in the following example, the integers 3 and 2 are considered arguments:
```py
remaining_login_attempts(3, 2)
```
These integers pass into the function through the parameters that were identified when defining the function. In this case, those parameters would be maximum_attempts and total_attempts. 3 is in the first position, so it passes into maximum_attempts. Similarly, 2 is in the second position and passes into total_attempts.

### Return statements

When defining functions in Python, you use return statements if you want the function to return output. The return keyword is used to return information from a function.
The return keyword appears in front of the information that you want to return. In the following example, it is before the calculation of how many login attempts remain:
```py
def remaining_login_attempts(maximum_attempts, total_attempts):
    return maximum_attempts - total_attempts
```
Note: The return keyword is not a function, so you should not place parentheses after it.
Return statements are useful when you want to store what a function returns inside of a variable to use elsewhere in the code. For example, you might use this variable for calculations or within conditional statements. In the following example, the information returned from the call to remaining_login_attempts is stored in a variable called remaining_attempts. Then, this variable is used in a conditional that prints a "Your account is locked" message when remaining_attempts is less than or equal to 0. You can run this code to explore its output:
```py
def remaining_login_attempts(maximum_attempts, total_attempts):
    return maximum_attempts - total_attempts
remaining_attempts = remaining_login_attempts(3, 3)
if remaining_attempts <= 0:
    print("Your account is locked")
```
In this example, the message prints because the calculation in the function results in 0.
Note: When Python encounters a return statement, it executes this statement and then exits the function. If there are lines of code that follow the return statement within the function, they will not be run. The previous example didn't contain any lines of code after the return statement, but this might apply in other functions, such as one containing a conditional statement.

### Global and local variables

To better understand how functions interact with variables, you should know the difference between global and local variables. 
When defining and calling functions, you're working with local variables, which are different from the variables you define outside the scope of a function.

#### Global variables

A global variable is a variable that is available through the entire program. Global variables are assigned outside of a function definition. Whenever that variable is called, whether inside or outside a function, it will return the value it is assigned.
For example, you might assign the following variable at the beginning of your code:
```py
device_id = "7ad2130bd"
```
Throughout the rest of your code, you will be able to access and modify the device_id variable in conditionals, loops, functions, and other syntax.

#### Local variables

A local variable is a variable assigned within a function. These variables cannot be called or accessed outside of the body of a function. Local variables include parameters as well as other variables assigned within a function definition.
In the following function definition, total_string and name are local variables:
```py
def greet_employee(name):
    total_string = "Welcome" + name
    return total_string

```
The variable total_string is a local variable because it's assigned inside of the function. The parameter name is a local variable because it is also created when the function is defined. 
Whenever you call a function, Python creates these variables temporarily while the function is running and deletes them from memory after the function stops running.
This means that if you call the greet_employee() function with an argument and then use the total_string variable outside of this function, you'll get an error.

#### Best practices for global and local variables

When working with variables and functions, it is very important to make sure that you only use a certain variable name once, even if one is defined globally and the other is defined locally. 
When using global variables inside functions, functions can access the values of a global variable. You can run the following example to explore this:
```py
username = "elarson"
def identify_user():
    print(username)
identify_user()

```
The code block returns "elarson" even though that name isn't defined locally. The function accesses the global variable. If you wanted the identify_user() function to accommodate other usernames, you would have to reassign the global username variable outside of the function. This isn't good practice. A better way to pass different values into a function is to use a parameter instead of a global variable.
There's something else to consider too. If you reuse the name of a global variable within a function, it will create a new local variable with that name. In other words, there will be both a global variable with that name and a local variable with that name, and they'll have different values. You can consider the following code block:
```py
username = "elarson"
print("1:" + username)
def greet():
    username = "bmoreno"
    print("2:" + username)
greet()
print("3:" + username)
```
The first print statement occurs before the function, and Python returns the value of the global username variable, "elarson". The second print statement is within the function, and it returns the value of the local username variable, which is "bmoreno". But this doesn't change the value of the global variable, and when username is printed a third time after the function call, it's still "elarson".
Due to this complexity, it's best to avoid combining global and local variables within functions. 

[Content](#content)


## Work with built-in functions

Previously, you explored built-in functions in Python, including print(), type(), max(), and sorted(). Built-in functions are functions that exist within Python and can be called directly. In this reading, you’ll explore these further and also learn about the min() function. In addition, you'll review how to pass the output of one function into another function.

### print()

The print() function outputs a specified object to the screen. The print() function is one of the most commonly used functions in Python because it allows you to output any detail from your code.
To use the print() function, you pass the object you want to print as an argument to the function. The print() function takes in any number of arguments, separated by a comma, and prints all of them. For example, you can run the following code that prints a string, a variable, another string, and an integer together:
```py
month = "September"
print("Investigate failed login attempts during", month, "if more than", 100)
```

### type()

The type() function returns the data type of its argument. The type() function helps you keep track of the data types of variables to avoid errors throughout your code. 
To use it, you pass the object as an argument, and it returns its data type. It only accepts one argument. For example, you could specify type("security") or type(7).
Passing one function into another
When working with functions, you often need to pass them through print() if you want to output the data type to the screen. This is the case when using a function like type(). Consider the following code:
```py
print(type("This is a string"))
```
It displays str, which means that the argument passed to the type() function is a string. This happens because the type() function is processed first and its output is passed as an argument to the print() function. 

### max() and min()

The max() function returns the largest numeric input passed into it. The min() function returns the smallest numeric input passed into it.
The max() and min() functions accept arguments of either multiple numeric values or of an iterable like a list, and they return the largest or smallest value respectively.
In a cybersecurity context, you could use these functions to identify the longest or shortest session that a user logged in for. If a specific user logged in seven times during a week, and you stored their access times in minutes in a list, you can use the max() and min() functions to find and print their longest and shortest sessions:
```py
time_list = [12, 2, 32, 19, 57, 22, 14]
print(min(time_list))
print(max(time_list))
```

### sorted()

The sorted() function sorts the components of a list. The sorted() function also works on any iterable, like a string, and returns the sorted elements in a list. By default, it sorts them in ascending order. When given an iterable that contains numbers, it sorts them from smallest to largest; this includes iterables that contain numeric data as well as iterables that contain string data beginning with numbers. An iterable that contains strings that begin with alphabetic characters will be sorted alphabetically.
The sorted() function takes an iterable, like a list or a string, as an input. So, for example, you can use the following code to sort the list of login sessions from shortest to longest:
```py
time_list = [12, 2, 32, 19, 57, 22, 14]
print(sorted(time_list))
```
This displays the sorted list. 
The sorted() function does not change the iterable that it sorts. The following code illustrates this:
```py
time_list = [12, 2, 32, 19, 57, 22, 14]
print(sorted(time_list))
print(time_list)
```
The first print() function displays the sorted list. However, the second print() function, which does not include the sorted() function, displays the list as assigned to time_list in the first line of code.
One more important detail about the sorted() function is that it cannot take lists or strings that have elements of more than one data type. For example, you can’t use the list [1, 2, "hello"].

### Resources for more information

These were just a few of Python's built-in functions. You can continue learning about others on your own:
    • The [Python Standard Library documentation](https://docs.python.org/3/library/functions.html): A list of Python’s built-in functions and information on how to use them

[Content](#content)

## Import modules and libraries in Python

Previously, you explored libraries and modules. You learned that a module is a Python file that contains additional functions, variables, classes, and any kind of runnable code. You also learned that a library is a collection of modules that provide code users can access in their programs. You were introduced to a few modules in the Python Standard Library and a couple of external libraries. In this reading, you'll learn how to import a module that exists in the Python Standard Library and use its functions. You'll also expand your understanding of external libraries. 

### The Python Standard Library

The Python Standard Library is an extensive collection of Python code that often comes packaged with Python. It includes a variety of modules, each with pre-built code centered around a particular type of task. 
For example, you were previously introduced to the the following modules in the Python Standard Library:
    • The `re `module, which provides functions used for searching for patterns in log files
    • The `csv `module, which provides functions used when working with .csv files
    • The `glob and os `modules, which provide functions used when interacting with the command line
    • The `time and datetime `modules, which provide functions used when working with timestamps
Another Python Standard Library module is statistics. The statistics module includes functions used when calculating statistics related to numeric data. For example, mean() is a function in the statistics module that takes numeric data as input and calculates its mean (or average). Additionally, median() is a function in the statistics module that takes numeric data as input and calculates its median (or middle value).

### How to import modules from the Python Standard Library

To access modules from the Python Standard Library, you need to import them. You can choose to either import a full module or to only import specific functions from a module. 

#### Importing an entire module

To import an entire Python Standard Library module, you use the import keyword. The import keyword searches for a module or library in a system and adds it to the local Python environment. After import, specify the name of the module to import. For example, you can specify import statistics to import the statistics module. This will import all the functions inside of the statistics module for use later in your code.
As an example, you might want to use the mean() function from the statistics module to calculate the average number of failed login attempts per month for a particular user. In the following code block, the total number of failed login attempts for each of the twelve months is stored in a list called monthly_failed_attempts. Run this code and analyze how mean() can be used to calculate the average of these monthly failed login totals and store it in mean_failed_attempts:
```py
import statistics
monthly_failed_attempts = [20, 17, 178, 33, 15, 21, 19, 29, 32, 15, 25, 19]
mean_failed_attempts = statistics.mean(monthly_failed_attempts)
print("mean:", mean_failed_attempts)
```
The output returns a mean of 35.25. You might notice the outlying value of 178 and want to find the middle value as well. To do this through the median() function, you can use the following code:
```py
import statistics
monthly_failed_attempts = [20, 17, 178, 33, 15, 21, 19, 29, 32, 15, 25, 19]
median_failed_attempts = statistics.median(monthly_failed_attempts)
print("median:", median_failed_attempts)

```
This gives you the value of 20.5, which might also be useful for analyzing the user's failed login attempt statistics.
Note: When importing an entire Python Standard Library module, you need to identify the name of the module with the function when you call it. You can do this by placing the module name followed by a period (.) before the function name. For example, the previous code blocks use statistics.mean() and statistics.median() to call those functions. 

#### Importing specific functions from a module

To import a specific function from the Python Standard Library, you can use the from keyword. For example, if you want to import just the median() function from the statistics module, you can write from statistics import median.
To import multiple functions from a module, you can separate the functions you want to import with a comma. For instance, from statistics import mean, median imports both the mean() and the median() functions from the statistics module.
An important detail to note is that if you import specific functions from a module, you no longer have to specify the name of the module before those functions. You can examine this in the following code, which specifically imports only the median() and the mean() functions from the statistics module and performs the same calculations as the previous examples:
```py
from statistics import mean, median
monthly_failed_attempts = [20, 17, 178, 33, 15, 21, 19, 29, 32, 15, 25, 19]
mean_failed_attempts = mean(monthly_failed_attempts)
print("mean:", mean_failed_attempts)
median_failed_attempts = median(monthly_failed_attempts)
print("median:", median_failed_attempts)
```
It is no longer necessary to specify statistics.mean() or statistics.median() and instead the code incorporates these functions as mean() and median().

### External libraries

In addition to the Python Standard Library, you can also download external libraries and incorporate them into your Python code. For example, previously you were introduced to Beautiful Soup (bs4) for parsing HTML files and NumPy (numpy) for arrays and mathematical computations. Before using them in a Jupyter Notebook or a Google Colab environment, you need to install them first.
To install a library, such as numpy, in either environment, you can run the following line prior to importing the library:

`%pip install numpy`

This installs the library so you can use it in your notebook.
After a library is installed, you can import it directly into Python using the import keyword in a similar way to how you used it to import modules from the Python Standard Library. For example, after the numpy install, you can use this code to import it:
```py
import numpy
```


[Content](#content)


## Ensure proper syntax and readability in Python

Previously, you were introduced to the PEP 8 style guide and its stylistic guidelines for programmers working in Python. You also learned about how adding comments and using correct indentation makes your code more readable. Additionally, correct indentation ensures your code is executed properly. This reading explores these ideas further and also focuses on common items to check in the syntax of your code to ensure it runs. 

### Comments

A comment is a note programmers make about the intentions behind their code. Comments make it easier for you and other programmers to read and understand your code. 
It’s important to start your code with a comment that explains what the program does. Then, throughout the code, you should add additional comments about your intentions behind specific sections.
When adding comments, you can add both single-line comments and multi-line comments.

#### Single-line comments

Single-line comments in Python begin with the (#) symbol. According to the PEP 8 style guide, it’s best practice to keep all lines in Python under 79 characters to maintain readability, and this includes comments.
Single-line comments are often used throughout your program to explain the intention behind specific sections of code. For example, this might be when you're explaining simpler components of your program, such as the following for loop:
```py
# Print elements of 'computer_assets' list
computer_assets = ["laptop1", "desktop20", "smartphone03"]
for asset in computer_assets:
    print(asset)

```
Note: Comments are important when writing more complex code, like functions, or multiple loops or conditional statements. However, they're optional when writing less complex code like reassigning a variable.

#### Multi-line comments

Multi-line comments are used when you need more than 79 characters in a single comment. For example, this might occur when defining a function if the comment describes its inputs and their data types as well as its output. 
There are two commonly used ways of writing multi-line comments in Python. The first is by using the hashtag (#) symbol over multiple lines:
```py
# remaining_login_attempts() function takes two integer parameters,
# the maximum login attempts allowed and the total attempts made,
# and it returns an integer representing remaining login attempts
def remaining_login_attempts(maximum_attempts, total_attempts):
    return maximum_attempts - total_attempts
```
Another way of writing multi-line comments is by using documentation strings and not assigning them to a variable. Documentation strings, also called docstrings, are strings that are written over multiple lines and are used to document code. To create a documentation string, use triple quotation marks `(""" """)`.
You could add the comment to the function in the previous example in this way too:
```py
"""
remaining_login_attempts() function takes two integer parameters,
the maximum login attempts allowed and the total attempts made,
and it returns an integer representing remaining login attempts
"""
```

### Correct indentation

Indentation is space added at the beginning of a line of code. In Python, you should indent the body of conditional statements, iterative statements, and function definitions. Indentation is not only necessary for Python to interpret this syntax properly, but it can also make it easier for you and other programmers to read your code.
The PEP 8 style guide recommends that indentations should be four spaces long. For example, if you had a conditional statement inside of a while loop, the body of the loop would be indented four spaces and the body of the conditional would be indented four spaces beyond that. This means the conditional would be indented eight spaces in total. 
```py
count = 0
login_status = True
while login_status == True:
    print("Try again.")
    count = count + 1
    if count == 4:
        login_status = False
```

### Maintaining correct syntax

Syntax errors involve invalid usage of the Python language. They are incredibly common with Python, so focusing on correct syntax is essential in ensuring that your code runs. Awareness of common errors will help you more easily fix them. 
Syntax errors often occur because of mistakes with data types or in the headers of conditional or iterative statements or of function definitions.

#### Data types

Correct syntax varies depending on data type:
    • Place string data in quotation marks.
        ◦ Example: `username = "bmoreno"`
    • Do not add quotation marks around integer, float, or Boolean data types.
        ◦ Examples: `login_attempts = 5, percentage_successful = .8, login_status = True`
    • Place lists in brackets and separate the elements of a list with commas.
        ◦ Example: `username_list = ["bmoreno", "tshah"]`

#### Colons in headers

The header of a conditional or iterative statement or of a function definition must end with a colon. For example, a colon appears at the end of the header in the following function definition:
def remaining_login_attempts(maximum_attempts, total_attempts):
`    return maximum_attempts - total_attempts`

### Resources for more information

Learning to write readable code can be challenging, so make sure to review the PEP 8 style guide and learn about additional aspects of code readability.
    • [PEP 8 - Style Guide for Python Code](https://peps.python.org/pep-0008/): The PEP 8 style guide contains all standards of Python code. When reading this guide, it's helpful to use the table of contents to navigate through the concepts you haven't learned yet.

[Content](#content)


## Strings and the security analyst

The ability to work with strings is important in the cybersecurity profession. Previously, you were introduced to several ways to work with strings, including functions and methods. You also learned how to extract elements in strings using bracket notation and indices. This reading reviews these concepts and explains more about using the .index() method. It also highlights examples of string data you might encounter in a security setting.

### String data in a security setting

As an analyst, string data is one of the most common data types you will encounter in Python. String data is data consisting of an ordered sequence of characters. It's used to store any type of information you don't need to manipulate mathematically (such as through division or subtraction). In a cybersecurity context, this includes IP addresses, usernames, URLs, and employee IDs.
You'll need to work with these strings in a variety of ways. For example, you might extract certain parts of an IP address, or you might verify whether usernames meet required criteria.
Working with indices in strings

### Indices

An index is a number assigned to every element in a sequence that indicates its position. With strings, this means each character in the string has its own index.
Indices start at 0. For example, you might be working with this string containing a device ID: "h32rb17". The following table indicates the index for each character in this string:
| Character | Index |
|-----------|-------|
| h         | 0     |
| 3         | 1     |
| 2         | 2     |
| r         | 3     |
| b         | 4     |
| 1         | 5     |
| 7         | 6     |

You can also use negative numbers as indices. This is based on their position relative to the last character in the string:

| Character | Index |
|-----------|-------|
| h         | -7    |
| 3         | -6    |
| 2         | -5    |
| r         | -4    |
| b         | -3    |
| 1         | -2    |
| 7         | -1    |


### Bracket notation

Bracket notation refers to the indices placed in square brackets. You can use bracket notation to extract a part of a string. For example, the first character of the device ID might represent a certain characteristic of the device. If you want to extract it, you can use bracket notation for this:
`"h32rb17"[0]`
This device ID might also be stored within a variable called device_id. You can apply the same bracket notation to the variable:
```py
device_id = "h32rb17"
device_id[0]
```

In both cases, bracket notation outputs the character h when this bracket notation is placed inside a print() function. You can observe this by running the following code:
```py
device_id = "h32rb17"
print("h32rb17"[0])
print(device_id[0])
```
You can also take a slice from a string. When you take a slice from a string, you extract more than one character from it. It's often done in cybersecurity contexts when you’re only interested in a specific part of a string. For example, this might be certain numbers in an IP address or certain parts of a URL.
In the device ID example, you might need the first three characters to determine a particular quality of the device. To do this, you can take a slice of the string using bracket notation. You can run this line of code to observe that it outputs "h32":
```py
print("h32rb17"[0:3])
```
Note: The slice starts at the 0 index, but the second index specified after the colon is excluded.  This means the slice ends one position before index 3, which is at index 2. 

### String functions and methods

The str() and len() functions are useful for working with strings. You can also apply methods to strings, including the .upper(), .lower(), and .index() methods. A method is a function that belongs to a specific data type.

### str() and len()

The str() function converts its input object into a string. As an analyst, you might use this in security logs when working with numerical IDs that aren't going to be used with mathematical processes. Converting an integer to a string gives you the ability to search through it and extract slices from it.
Consider the example of an employee ID 19329302 that you need to convert into a string. You can use the following line of code to convert it into a string and store it in a variable:
`string_id = str(19329302)`
The second function you learned for strings is the len() function, which returns the number of elements in an object.
As an example, if you want to verify that a certain device ID conforms to a standard of containing seven characters, you can use the len() function and a conditional. When you run the following code, it will print a message if "h32rb17" has seven characters:
```py
device_id_length = len("h32rb17")
if device_id_length == 7:
    print("The device ID has 7 characters.")
```

### .upper() and .lower()

The .upper() method returns a copy of the string with all of its characters in uppercase. For example, you can change this department name to all uppercase by running the code "Information Technology".upper(). It would return the string "INFORMATION TECHNOLOGY".
Meanwhile, the .lower() method returns a copy of the string in all lowercase characters. "Information Technology".lower() would return the string "information technology".
.index()
The .index() method finds the first occurrence of the input in a string and returns its location. For example, this code uses the .index() method to find the first occurrence of the character "r" in the device ID "h32rb17":
```py
print("h32rb17".index("r"))
```
The .index() method returns 3 because the first occurrence of the character "r" is at index 3.
In other cases, the input may not be found. When this happens, Python returns an error. For instance, the code print("h32rb17".index("a")) returns an error because "a" is not in the string "h32rb17".
Also note that if a string contains more than one instance of a character, only the first one will be returned. For instance, the device ID "r45rt46" contains two instances of "r". You can run the following code to explore its output:

`print("r45rt46".index("r"))`

The output is 0 because .index() returns only the first instance of "r", which is at index 0. The instance of "r" at index 3 is not returned.

### Finding substrings with .index()

A substring is a continuous sequence of characters within a string. For example, "llo" is a substring of "hello".
The .index() method can also be used to find the index of the first occurrence of a substring. It returns the index of the first character in that substring. Consider this example that finds the first instance of the user "tshah" in a string:
```py
tshah_index = "tsnow, tshah, bmoreno - updated".index("tshah")
print(tshah_index)
```
The .index() method returns the index 7, which is where the substring "tshah" starts.
Note: When using the .index() method to search for substrings, you need to be careful. In the previous example, you want to locate the instance of "tshah". If you search for just "ts", Python will return 0 instead of 7 because "ts" is also a substring of "tsnow". 


[Content](#content)

## Lists and the security analyst

Previously, you examined how to use bracket notation to access and change elements in a list and some fundamental methods for working with lists. This reading will review these concepts with new examples, introduce the .index() method as it applies to lists, and highlight how lists are used in a cybersecurity context.

### List data in a security setting

As a security analyst, you'll frequently work with lists in Python. List data is a data structure that consists of a collection of data in sequential form. You can use lists to store multiple elements in a single variable. A single list can contain multiple data types. 
In a cybersecurity context, lists might be used to store usernames, IP addresses, URLs, device IDs, and data.
Placing data within a list allows you to work with it in a variety of ways. For example, you might iterate through a list of device IDs using a for loop to perform the same actions for all items in the list. You could incorporate a conditional statement to only perform these actions if the device IDs meet certain conditions. 

### Working with indices in lists

### Indices

Like strings, you can work with lists through their indices, and indices start at 0. In a list, an index is assigned to every element in the list.
This table contains the index for each element in the list ["elarson", "fgarcia", "tshah", "sgilmore"]:
| Element   | Index |
|-----------|-------|
| "elarson" | 0     |
| "fgarcia" | 1     |
| "tshah"   | 2     |
| "sgilmore"| 3     |

### Bracket notation

Similar to strings, you can use bracket notation to extract elements or slices in a list. To extract an element from a list, after the list or the variable that contains a list, add square brackets that contain the index of the element. The following example extracts the element with an index of 2 from the variable username_list and prints it. You can run this code to examine what it outputs:
```py
username_list = ["elarson", "fgarcia", "tshah", "sgilmore"]
print(username_list[2])
```
This example extracts the element at index 2 directly from the list:
```py
print(["elarson", "fgarcia", "tshah", "sgilmore"][2])
```

### Extracting a slice from a list

Just like with strings, it's also possible to use bracket notation to take a slice from a list. With lists, this means extracting more than one element from the list.
When you extract a slice from a list, the result is another list. This extracted list is called a sublist because it is part of the original, larger list. 
To extract a sublist using bracket notation, you need to include two indices. You can run the following code that takes a slice from a list and explore the sublist it returns:
```py
username_list = ["elarson", "fgarcia", "tshah", "sgilmore"]
print(username_list[0:2])
```
The code returns a sublist of ["elarson", "fgarcia"]. This is because the element at index 0, "elarson", is included in the slice, but the element at index 2, "tshah", is excluded. The slice ends one element before this index.

### Changing the elements in a list

Unlike strings, you can also use bracket notation to change elements in a list. This is because a string is immutable and cannot be changed after it is created and assigned a value, but lists are not immutable.
To change a list element, use similar syntax as you would use when reassigning a variable, but place the specific element to change in bracket notation after the variable name. For example, the following code changes element at index 1 of the username_list variable to "bmoreno".
```py
username_list = ["elarson", "fgarcia", "tshah", "sgilmore"]
print("Before changing an element:", username_list)
username_list[1] = "bmoreno"
print("After changing an element:", username_list)
```
This code has updated the element at index 1 from "fgarcia" to "bmoreno".

### List methods

List methods are functions that are specific to the list data type. These include the .insert() , .remove(), .append() and .index(). 

### .insert() 

The .insert() method adds an element in a specific position inside a list. It has two parameters. The first is the index where you will insert the new element, and the second is the element you want to insert.
You can run the following code to explore how this method can be used to insert a new username into a username list:
```py
username_list = ["elarson", "bmoreno", "tshah", "sgilmore"]
print("Before inserting an element:", username_list)
username_list.insert(2,"wjaffrey")
print("After inserting an element:", username_list)

```

Because the first parameter is 2 and the second parameter is "wjaffrey", "wjaffrey" is inserted at index 2, which is the third position. The other list elements are shifted one position in the list. For example, "tshah" was originally located at index 2 and now is located at index 3.

### .remove()

The .remove() method removes the first occurrence of a specific element in a list. It has only one parameter, the element you want to remove.
The following code removes "elarson" from the username_list:
```py
username_list = ["elarson", "bmoreno", "wjaffrey", "tshah", "sgilmore"]
print("Before removing an element:", username_list)
username_list.remove("elarson")
print("After removing an element:", username_list)
```
This code removes "elarson" from the list. The elements that follow "elarson" are all shifted one position closer to the beginning of the list.
Note: If there are two of the same element in a list, the .remove() method only removes the first instance of that element and not all occurrences.

### .append() 

The .append() method adds input to the end of a list. Its one parameter is the element you want to add to the end of the list. 
For example, you could use .append() to add "btang" to the end of the username_list:
```py
username_list = ["bmoreno", "wjaffrey", "tshah", "sgilmore"]
print("Before appending an element:", username_list)
username_list.append("btang")
print("After appending an element:", username_list)
```

This code places "btang" at the end of the username_list, and all other elements remain in their original positions.
The .append() method is often used with for loops to populate an empty list with elements. You can explore how this works with the following code:
```py
numbers_list = []
print("Before appending a sequence of numbers:", numbers_list)
for i in range(10):
    numbers_list.append(i)
print("After appending a sequence of numbers:", numbers_list)
```
Before the for loop, the numbers_list variable does not contain any elements. When it is printed, the empty list is displayed. Then, the for loop iterates through a sequence of numbers and uses the .append() method to add each of these numbers to numbers_list. After the loop, when the numbers_list variable is printed, it displays these numbers.  

### .index()

Similar to the .index() method used for strings, the .index() method used for lists finds the first occurrence of an element in a list and returns its index. It takes the element you're searching for as an input.
Note: Although it has the same name and use as the .index() method used for strings, the .index() method used for lists is not the same method. Methods are defined when defining a data type, and because strings and lists are defined differently, the methods are also different.
Using the username_list variable, you can use the .index() method to find the index of the username "tshah":
```py
username_list = ["bmoreno", "wjaffrey", "tshah", "sgilmore", "btang"]
username_index = username_list.index("tshah")
print(username_index)
```

Because the index of "tshah" is 2, it outputs this number.
Similar to the .index() method used for strings, it only returns the index of the first occurrence of a list item. So if the username "tshah" were repeated twice, it would return the index of the first instance, and not the second.


[Content](#content)


## More about regular expressions

You were previously introduced to regular expressions and a couple of symbols that you can use to construct regular expression patterns. In this reading, you'll explore additional regular expression symbols that can be used in a cybersecurity context. You'll also learn more about the re module and its re.findall() function.

### Basics of regular expressions

A regular expression (regex) is a sequence of characters that forms a pattern. You can use these in Python to search for a variety of patterns. This could include IP addresses, emails, or device IDs.
To access regular expressions and related functions in Python, you need to import the re module first. You should use the following line of code to import the re module:
`import re`
Regular expressions are stored in Python as strings. Then, these strings are used in re module functions to search through other strings. There are many functions in the re module, but you will explore how regular expressions work through `re.findall(). `The re.findall() function returns a list of matches to a regular expression. It requires two parameters. The first is the string containing the regular expression pattern, and the second is the string you want to search through.
The patterns that comprise a regular expression consist of alphanumeric characters and special symbols. If a regular expression pattern consists only of alphanumeric characters, Python will review the specified string for matches to this pattern and return them. In the following example, the first parameter is a regular expression pattern consisting only of the alphanumeric characters "ts". The second parameter, "tsnow, tshah, bmoreno",  is the string it will search through. You can run the following code to explore what it returns:
```py
import re
re.findall("ts", "tsnow, tshah, bmoreno")
```
The output is a list of only two elements, the two matches to "ts": ['ts', 'ts'].
If you want to do more than search for specific strings, you must incorporate special symbols into your regular expressions.

### Regular expression symbols

#### Symbols for character types

You can use a variety of symbols to form a pattern for your regular expression. Some of these symbols identify a particular type of character. For example, \w matches with any alphanumeric character.
Note: The \w symbol also matches with the underscore ( _ ).
You can run this code to explore what re.findall() returns when applying the regular expression of "\w" to the device ID of "h32rb17".
```py
import re
re.findall("\w", "h32rb17")
```
Because every character within this device ID is an alphanumeric character, Python returns a list with seven elements. Each element represents one of the characters in the device ID.
You can use these additional symbols to match to specific kinds of characters:
    •  `.`matches to all characters, including symbols
    • `\d`matches to all single digits [0-9]
    • `\s`matches to all single spaces 
    • `\.`matches to the period character
The following code searches through the same device ID as the previous example but changes the regular expression pattern to "\d". When you run it, it will return a different list:
```py
import re
re.findall("\d", "h32rb17")
```
This time, the list contains only four elements. Each element is one of the numeric digits in the string.

#### Symbols to quantify occurrences

Other symbols quantify the number of occurrences of a specific character in the pattern. In a regular expression pattern, you can add them after a character or a symbol identifying a character type to specify the number of repetitions that match to the pattern.
For example, the `+` symbol represents one or more occurrences of a specific character. In the following example, the pattern places it after the "\d" symbol to find matches to one or more occurrences of a single digit:
```py
import re
re.findall("\d+", "h32rb17")
```
With the regular expression "\d+", the list contains the two matches of "32" and "17".
Another symbol used to quantify the number of occurrences is the * symbol. The * symbol represents zero, one, or more occurrences of a specific character.  The following code substitutes the *  symbol for the + used in the previous example. You can run it to examine the difference:
```py
import re
re.findall("\d*", "h32rb17")
```
Because it also matches to zero occurrences, the list now contains empty strings for the characters that were not single digits.
If you want to indicate a specific number of repetitions to allow, you can place this number in curly brackets ({ }) after the character or symbol. In the following example, the regular expression pattern "\d{2}" instructs Python to return all matches of exactly two single digits in a row from a string of multiple device IDs:
```py
import re
re.findall("\d{2}", "h32rb17 k825t0m c2994eh"))
```
Because it is matching to two repetitions, when Python encounters a single digit, it checks whether there is another one following it. If there is, Python adds the two digits to the list and goes on to the next digit. If there isn't, it proceeds to the next digit without adding the first digit to the list.
Note: Python scans strings left-to-right when matching against a regular expression. When Python finds a part of the string that matches the first expected character defined in the regular expression, it continues to compare the subsequent characters to the expected pattern. When the pattern is complete, it starts this process again. So in cases in which three digits appear in a row, it handles the third digit as a new starting digit.
You can also specify a range within the curly brackets by separating two numbers with a comma. The first number is the minimum number of repetitions and the second number is the maximum number of repetitions. The following example returns all matches that have between one and three repetitions of a single digit:
```py
import re
re.findall("\d{1,3}", "h32rb17 k825t0m c2994eh")
```
The returned list contains elements of one digit like  "0", two digits like "32" and three digits like "825".

### Constructing a pattern

Constructing a regular expression requires you to break down the pattern you're searching for into smaller chunks and represent those chunks using the symbols you've learned. Consider an example of a string that contains multiple pieces of information about employees at an organization. For each employee, the following string contains their employee ID, their username followed by a colon (:), their attempted logins for the day, and their department:
`employee_logins_string = "1001 bmoreno: 12 Marketing 1002 tshah: 7 Human Resources 1003 sgilmore: 5 Finance"`
Your task is to extract the username and the login attempts, without the employee's ID number or department.
To complete this task with regular expressions, you need to break down what you're searching for into smaller components. In this case, those components are the varying number of characters in a username, a colon, a space, and a varying number of single digits. The corresponding regular expression symbols are \w+, :, \s, and \d+ respectively. Using these symbols as your regular expression, you can run the following code to extract the strings:
```py
import re
pattern = "\w+:\s\d+"
employee_logins_string = "1001 bmoreno: 12 Marketing 1002 tshah: 7 Human Resources 1003 sgilmore: 5 Finance"
print(re.findall(pattern, employee_logins_string))
```
Note: Working with regular expressions can carry the risk of returning unneeded information or excluding strings that you want to return. Therefore, it's useful to test your regular expressions.

[Content](#content)


## Essential Python components for automation

Throughout this course, you explored coding in Python. You've focused on variables, conditional statements, iterative statements, functions, and a variety of ways to work with strings and lists. In this reading, you will explore why these are all essential components when automating tasks through Python, and you'll be introduced to another necessary component: working with files. 

### Automating tasks in Python

Automation is the use of technology to reduce human and manual effort to perform common and repetitive tasks. As a security analyst, you will primarily use Python to automate tasks.
You have encountered multiple examples of how to use Python for automation in this course, including investigating logins, managing access, and updating devices.
Automating cybersecurity-related tasks requires understanding the following Python components that you've worked with in this course:

#### Variables

A variable is a container that stores data. Variables are essential for automation. Without them, you would have to individually rewrite values for each action you took in Python.

#### Conditional statements

A conditional statement is a statement that evaluates code to determine if it meets a specified set of conditions. Conditional statements allow you to check for conditions before performing actions. This is much more efficient than manually evaluating whether to apply an action to each separate piece of data.

#### Iterative statements

An iterative statement is code that repeatedly executes a set of instructions. You explored two kinds of iterative statements: for loops and while loops. In both cases, they allow you to perform the same actions a certain number of times without the need to retype the same code each time. Using a for loop allows you to automate repetition of that code based on a sequence, and using a while loop allows you to automate the repetition based on a condition.

#### Functions

A function is a section of code that can be reused in a program. Functions help you automate your tasks by reducing the need to incorporate the same code multiple places in a program. Instead, you can define the function once and call it wherever you need it. 
You can develop your own functions based on your particular needs. You can also incorporate the built-in functions that exist directly in Python without needing to manually code them.

#### Techniques for working with strings

String data is one of the most common data types that you'll encounter when automating cybersecurity tasks through Python, and there are a lot of techniques that make working with strings efficient. You can use bracket notation to access characters in a string through their indices. You can also use a variety of functions and methods when working with strings, including str(), len(), and .index().

#### Techniques for working with lists

List data is another common data type. Like with strings, you can use bracket notation to access a list element through its index. Several methods also help you with automation when working with lists. These include .insert(), .remove(), .append(), and .index().
Example: Counting logins made by a flagged user
As one example, you may find that you need to investigate the logins of a specific user who has been flagged for unusual activity. Specifically, you are responsible for counting how many times this user has logged in for the day. If you are given a list identifying the username associated with each login attempt made that day, you can automate this investigation in Python.
To automate the investigation, you'll need to incorporate the following Python components:
    • A for loop will allow you to iterate through all the usernames in the list. 
    • Within the for loop, you should incorporate a conditional statement to examine whether each username in the list matches the username of the flagged user.
    • When the condition evaluates to True, you also need to increment a counter variable that keeps track of the number of times the flagged user appears in the list.
Additionally, if you want to reuse this code multiple times, you can incorporate it into a function. The function can include parameters that accept the username of the flagged user and the list to iterate through. (The list would contain the usernames associated with all login attempts made that day.) The function can use the counter variable to return the number of logins for that flagged user.

#### Working with files in Python

One additional component of automating cybersecurity-related tasks in Python is understanding how to work with files. Security-related data will often be initially found in log files. A log is a record of events that occur within an organization's systems. In logs, lines are often appended to the record as time progresses.
Two common file formats for security logs are .txt files and .csv files. Both .txt and .csv files are types of text files, meaning they contain only plain text. They do not contain images and do not specify graphical properties of the text, including font, color, or spacing. In a .csv file, or a "comma-separated values" file, the values are separated by commas. In a .txt file, there is not a specific format for separating values, and they may be separated in a variety of ways, including spaces.
You can easily extract data from .txt and .csv files. You can also convert both into other file formats.
Coming up, you'll learn how to import, read from, and write to files. You will also explore how to structure the information contained in files.

[Content](#content)

## Import files into Python

Previously, you explored how to open files in Python, convert them into strings, and read them. In this reading, you'll review the syntax needed for this. You'll also focus on why the ability to work with files is important for security analysts using Python, and you will learn about writing files.

### Working with files in cybersecurity

Security analysts may need to access a variety of files when working in Python. Many of these files will be logs. A log is a record of events that occur within an organization's systems.
For instance, there may be a log containing information on login attempts. This might be used to identify unusual activity that signals attempts made by a malicious actor to access the system.
As another example, malicious actors that have breached the system might be capable of attacking software applications. An analyst might need to access a log that contains information on software applications that are experiencing issues.

### Opening files in Python

To open a file called "update_log.txt" in Python for purposes of reading it, you can incorporate the following line of code:
`with open("update_log.txt", "r") as file:`
This line consists of the with keyword, the open() function with its two parameters, and the as keyword followed by a variable name. You must place a colon (:) at the end of the line.

#### with

The keyword with handles errors and manages external resources when used with other functions. In this case, it's used with the open() function in order to open a file. It will then manage the resources by closing the file after exiting the with statement.
Note: You can also use the open() function without the with keyword. However, you should close the file you opened to ensure proper handling of the file. 

#### open()

The open() function opens a file in Python.
The first parameter identifies the file you want to open. In the following file structure, "update_log.txt" is located in the same directory as the Python file that will access it, "log_parser.ipynb":

```txt

/
|
home
|
analyst ______________
|                     \
logs                  code  ________________
|                      |                    \
access_log.txt         log_parser.ipynb      update_log.txt

```
Because they're in the same directory, only the name of the file is required. The code can be written as `with open("update_log.txt", "r") as file:`.
However, "access_log.txt" is not in the same directory as the Python file "log_parser.ipynb". Therefore, it's necessary to specify its absolute file path. A file path is the location of a file or directory. An absolute file path starts from the highest-level directory, the root. In the following code, the first parameter of the open() function includes the absolute file path to "access_log.txt":
`with open("/home/analyst/logs/access_log.txt", "r") as file:`
Note: In Python, the names of files or their file paths can be handled as string data, and like all string data, you must place them in quotation marks.
The second parameter of the open() function indicates what you want to do with the file. In both of these examples, the second parameter is "r", which indicates that you want to read the file.
Alternatively, you can use "w" if you want to write to a file or "a" if you want to append to a file.

#### as

When you open a file using with open(), you must provide a variable that can store the file while you are within the with statement. You can do this through the keyword as followed by this variable name. The keyword as assigns a variable that references another object. The code with open("update_log.txt", "r") as file: assigns file to reference the output of the open() function within the indented code block that follows it.

### Reading files in Python

After you use the code with open("update_log.txt", "r") as file: to import "update_log.txt" into the file variable, you should indicate what to do with the file on the indented lines that follow it. For example, this code uses the .read() method to read the contents of the file:
```py
with open("update_log.txt", "r") as file:
    updates = file.read()
print(updates)
```
The .read() method converts files into strings. This is necessary in order to use and display the contents of the file that was read.
In this example, the file variable is used to generate a string of the file contents through .read(). This string is then stored in another variable called updates. After this, print(updates) displays the string.
Once the file is read into the updates string, you can perform the same operations on it that you might perform with any other string. For example, you could use the .index() method to return the index where a certain character or substring appears. Or, you could use len() to return the length of this string.

### Writing files in Python

Security analysts may also need to write to files. This could happen for a variety of reasons. For example, they might need to create a file containing the approved usernames on a new allow list. Or, they might need to edit existing files to add data or to adhere to policies for standardization.
To write to a file, you will need to open the file with "w" or "a" as the second argument of open(). 
You should use the "w" argument when you want to replace the contents of an existing file. When working with the existing file update_log.txt, the code with open("update_log.txt", "w") as file: opens it so that its contents can be replaced. 
Additionally, you can use the "w" argument to create a new file. For example, with open("update_log2.txt", "w") as file: creates and opens a new file called "update_log2.txt". 
You should use the "a" argument if you want to append new information to the end of an existing file rather than writing over it. The code with open("update_log.txt", "a") as file: opens "update_log.txt" so that new information can be appended to the end. Its existing information will not be deleted.
Like when opening a file to read from it, you should indicate what to do with the file on the indented lines that follow when you open a file to write to it. With both "w" and "a", you can use the .write() method. The .write() method writes string data to a specified file. 
The following example uses the .write() method to append the content of the line variable to the file "access_log.txt".
```py
line = "jrafael,192.168.243.140,4:56:27,True"
with open("access_log.txt", "a") as file:
    file.write(line)
```
Note: Calling the .write() method without using the with keyword when importing the file might result in its arguments not being completely written to the file if the file is not properly closed in another way.


[Content](#content)

## Work with files in Python

You previously explored how to open files in Python as well as how to read them and write to them. You also examined how to adjust the structure of file contents through the .split() method. In this reading, you'll review the .split() method, and you'll also learn an additional method that can help you work with file contents. 

### Parsing

Part of working with files involves structuring its contents to meet your needs. Parsing is the process of converting data into a more readable format. Data may need to become more readable in a couple of different ways. First, certain parts of your Python code may require modification into a specific format. By converting data into this format, you enable Python to process it in a specific way. Second, programmers need to read and interpret the results of their code, and parsing can also make the data more readable for them.
Methods that can help you parse your data include .split() and .join().

### .split()

#### The basics of .split()

The .split() method converts a string into a list. It separates the string based on a specified character that's passed into .split() as an argument. 
In the following example, the usernames in the approved_users string are separated by a comma. For this reason, a string containing the comma (",") is passed into .split() in order to parse it into a list. Run this code and analyze the different contents of approved_users before and after the .split() method is applied to it:
```py
approved_users = "elarson,bmoreno,tshah,sgilmore,eraab"
print("before .split():", approved_users)
approved_users = approved_users.split(",")
print("after .split():", approved_users)
```

Before the .split() method is applied to approved_users, it contains a string, but after it is applied, this string is converted to a list.
If you do not pass an argument into .split(), it will separate the string every time it encounters a whitespace.
Note: A variety of characters are considered whitespaces by Python. These characters include spaces between characters, returns for new lines, and others.
The following example demonstrates how a string of usernames that are separated by space can be split into a list through the .split() method:
```py
removed_users = "wjaffrey jsoto abernard jhill awilliam"
print("before .split():", removed_users)
removed_users = removed_users.split()
print("after .split():", removed_users)
```

Because an argument isn't passed into .split(), Python splits the removed_users string at each space when separating it into a list.

#### Applying .split() to files

The .split() method allows you to work with file content as a list after you've converted it to a string through the .read() method. This is useful in a variety of ways. For example, if you want to iterate through the file contents in a for loop, this can be easily done when it's converted into a list.
The following code opens the "update_log.txt" file. It then reads all of the file contents into the updates variable as a string and splits the string in the updates variable into a list by creating a new element at each whitespace:
```py
with open("update_log.txt", "r") as file:
    updates = file.read()
updates = updates.split()
```
After this, through the updates variable, you can work with the contents of the "update_log.txt" file in parts of your code that require it to be structured as a list. 
Note: Because the line that contains .split() is not indented as part of the with statement, the file closes first. Closing a file as soon as it is no longer needed helps maintain code readability. Once a file is read into the updates variable, it is not needed and can be closed.

### .join()

#### The basics of .join()

If you need to convert a list into a string, there is also a method for that. The .join() method concatenates the elements of an iterable into a string. The syntax used with .join() is distinct from the syntax used with .split() and other methods that you've worked with, such as .index(). 
In methods like .split() or .index(), you append the method to the string or list that you're working with and then pass in other arguments. For example, the code usernames.index(2), appends the .index() method to the variable usernames, which contains a list. It passes in 2 as the argument to indicate which element to return.
However, with .join(), you must pass the list that you want to concatenate into a string in as an argument. You append .join() to a character that you want to separate each element with once they are joined into a string.
For example, in the following code, the approved_users variable contains a list. If you want to join that list into a string and separate each element with a comma, you can use ",".join(approved_users). Run the code and examine what it returns:
```py
approved_users = ["elarson", "bmoreno", "tshah", "sgilmore", "eraab"]
print("before .join():", approved_users)
approved_users = ",".join(approved_users)
print("after .join():", approved_users)
```
Before .join() is applied, approved_users is a list of five elements. After it is applied, it is a string with each username separated by a comma.
Note: Another way to separate elements when using the .join() method is to use "\n", which is the newline character. The "\n" character indicates to separate the elements by placing them on new lines.

#### Applying .join() to files

When working with files, it may also be necessary to convert its contents back into a string. For example, you may want to use the .write() method. The .write() method writes string data to a file. This means that if you have converted a file's contents into a list while working with it, you'll need to convert it back into a string before using .write(). You can use the .join() method for this.
You already examined how .split() could be applied to the contents of the "update_log.txt" file once it is converted into a string through .read() and stored as updates:
```py
with open("update_log.txt", "r") as file:
    updates = file.read()
updates = updates.split()
```
After you're through performing operations using the list in the updates variable, you might want to replace "update_log.txt" with the new contents. To do so, you need to first convert updates back into a string using .join(). Then, you can open the file using a with statement and use the .write() method to write the updates string to the file:
updates = " ".join(updates)
with open("update_log.txt", "w") as file
    file.write(updates)
The code " ".join(updates) indicates to separate each of the list elements in updates with a space once joined back into a string. And because "w" is specified as the second argument of open(), Python will overwrite the contents of "update_log.txt" with the string currently in the updates variable. 

[Content](#content)


## Explore debugging techniques

Previously, you examined three types of errors you may encounter while working in Python and explored strategies for debugging these errors. This reading further explores these concepts with additional strategies and examples for debugging Python code.

### Types of errors 

It's a normal part of developing code in Python to get error messages or find that the code you're running isn't working as you intended. The important thing is that you can figure out how to fix errors when they occur. Understanding the three main types of errors can help. These types include syntax errors, logic errors, and exceptions.

#### Syntax errors 

A `syntax error `is an error that involves invalid usage of a programming language. Syntax errors occur when there is a mistake with the Python syntax itself. Common examples of syntax errors include forgetting a punctuation mark, such as a closing bracket for a list or a colon after a function header.  
When you run code with syntax errors, the output will identify the location of the error with the line number and a portion of the affected code. It also describes the error. Syntax errors often begin with the label  "SyntaxError:" . Then, this is followed by a  description of the error. The description might simply be "invalid syntax" . Or if you forget a closing parentheses on a function, the description might be "unexpected EOF while parsing". "EOF" stands for "end of file."  
The following code contains a syntax error. Run it and examine its output:
```py
message = "You are debugging a syntax error
print(message)
```

This outputs the message "SyntaxError: EOL while scanning string literal". "EOL" stands for "end of line". The error message also indicates that the error happens on the first line. The error occurred because a quotation mark was missing at the end of the string on the first line. You can fix it by adding that quotation mark.
Note: You will sometimes encounter the error label "IndentationError" instead of "SyntaxError". "IndentationError" is a subclass of "SyntaxError" that occurs when the indentation used with a line of code is not syntactically correct. 

#### Logic errors 

A `logic error `is an error that results when the logic used in code produces unintended results.  Logic errors may not produce error messages. In other words, the code will not do what you expect it to do, but it is still valid to the interpreter. 
For example, using the wrong logical operator, such as a greater than or equal to sign (>=) instead of greater than sign (>) can result in a logic error.  Python will not evaluate a condition as you intended. However, the code is valid, so it will run without an error message. 
The following example outputs a message related to whether or not a user has reached a maximum number of five login attempts. The condition in the if statement should be login_attempts > 5, but it is written as login_attempts >= 5.  A value of 5 has been assigned to login_attempts so that you can explore what it outputs in that instance:
```py
login_attempts = 5
if login_attempts >= 5:
    print("User has not reached maximum number of login attempts.")
else:
    print("User has reached maximum number of login attempts.")
```
The output displays the message "User has not reached maximum number of login attempts." However, this is not true since the maximum number of login attempts is five. This is a logic error.
Logic errors can also result when you assign the wrong value in a condition or when a mistake with indentation means that a line of code executes in a way that was not planned.

#### Exceptions

An `exception `is an error that involves code that cannot be executed even though it is syntactically correct. This happens for a variety of reasons.
One common cause of an exception is when the code includes a variable that hasn't been assigned or a function that hasn't been defined. In this case, your output will include "NameError" to indicate that this is a name error. After you run the following code, use the error message to determine which variable was not assigned:
```py
username = "elarson"
month = "March"
total_logins = 75
failed_logins = 18
print("Login report for", username, "in", month)
print("Total logins:", total_logins)
print("Failed logins:", failed_logins)
print("Unusual logins:", unusual_logins)
```
The output indicates there is a "NameError" involving the unusual_logins variable. You can fix this by assigning this variable a value.
In addition to name errors, the following messages are output for other types of exceptions:
    • "IndexError": An index error occurs when you place an index in bracket notation that does not exist in the sequence being referenced. For example, in the list usernames = ["bmoreno", "tshah", "elarson"], the indices are 0, 1, and 2. If you referenced this list with the statement print(usernames[3]), this would result in an index error.
    • "TypeError": A type error results from using the wrong data type. For example, if you tried to perform a mathematical calculation by adding a string value to an integer, you would get a type error.
    • "FileNotFound": A file not found error occurs when you try to open a file that does not exist in the specified location.

### Debugging strategies  

Keep in mind that if you have multiple errors, the Python interpreter will output error messages one at a time, starting with the first error it encounters. After you fix that error and run the code again, the interpreter will output another message for the next syntax error or exception it encounters.
When dealing with syntax errors, the error messages you receive in the output will generally help you fix the error. However, with logic errors and exceptions, additional strategies may be needed.

### Debuggers 

In this course, you have been running code in a notebook environment. However, you may write Python code in an `Integrated Development Environment (IDE). `An Integrated Development Environment (IDE) is a software application for writing code that provides editing assistance and error correction tools. Many IDEs offer error detection tools in the form of a debugger. A debugger is a software tool that helps to locate the source of an error and assess its causes.
In cases when you can't find the line of code that is causing the issue, debuggers help you narrow down the source of the error in your program. They do this by working with breakpoints. Breakpoints are markers placed on certain lines of executable code that indicate which sections of code should run when debugging.
Some debuggers also have a feature that allows you to check the values stored in variables as they change throughout your code. This is especially helpful for logic errors so that you can locate where variable values have unintentionally changed. 

#### Use print statements 

Another debugging strategy is to incorporate temporary print statements that are designed to identify the source of the error. You should strategically incorporate these print statements to print at various locations in the code. You can specify line numbers as well as descriptive text about the location. 
For example, you may have code that is intended to add new users to an approved list and then display the approved list. The code should not add users that are already on the approved list. If you analyze the output of this code after you run it, you will realize that there is a logic error:
```py
new_users = ["sgilmore", "bmoreno"]
approved_users = ["bmoreno", "tshah", "elarson"]
def add_users():
    for user in new_users:
        if user in approved_users:
            print(user,"already in list")
        approved_users.append(user)
add_users()
print(approved_users)
```
Even though you get the message "bmoreno already in list", a second instance of "bmoreno" is added to the list. In the following code, print statements have been added to the code. When you run it, you can examine what prints:
```py
new_users = ["sgilmore", "bmoreno"]
approved_users = ["bmoreno", "tshah", "elarson"]
def add_users():
    for user in new_users:
        print("line 5 - inside for loop")
        if user in approved_users:
            print("line 7 - inside if statement")
            print(user,"already in list")
        print("line 9 - before .append method")
        approved_users.append(user)
add_users()
print(approved_users)
```
The print statement "line 5 - inside for loop" outputs twice, indicating that Python has entered the for loop for each username in new_users. This is as expected. Additionally, the print statement "line 7 - inside if statement" only outputs once, and this is also as expected because only one of these usernames was already in approved_users.
However, the print statement "line 9 - before .append method" outputs twice. This means the code calls the .append() method for both usernames even though one is already in approved_users. This helps isolate the logic error to this area. This can help you realize that the line of code approved_users.append(user) should be the body of an else statement so that it only executes when user is not in approved_users.

## Activities

### Activities content

[Activity: Activity: Practice writing Python code](#activity-practice-writing-python-code)

[Activity: Assign Python variables](#activity-assign-python-variables)

[Activity: Create a conditional statement](#activity-create-a-conditional-statement)

[Activity: Create loops](#activity-create-loops)

[Activity: Define and call a function](#activity-define-and-call-a-function)

[Activity: Create more functions](#activity-create-more-functions)

[Activity: Work with strings in Python](#activity-activity-work-with-strings-in-python)

[Activity: Develop an algorithm](#activity-develop-an-algorithm)

[Activity: Use regular expressions to find patterns](#activity-use-regular-expressions-to-find-patterns)

[Activity: Import and parse a text file](#activity-import-and-parse-a-text-file)

[Activity: Create another algorithm](#activity-create-another-algorithm)

[Activity: Update a file through a Python algorithm](#activity-update-a-file-through-a-python-algorithm)

[Activity: Debug Python code](#activity-debug-python-code)


[Content](#content)



### Activity: Practice writing Python code

### Scenario

As a security analyst, you'll often use notebook environments and notebooks to write and run code. This lab will help you get familiar with working in a notebook environment, writing code comments in Python, and displaying strings with the print() function.

In this lab, you'll complete a series of tasks that involve observing and running some pre-written cells of text and code, as well as filling in cells with your own text, Python code, and code comments.


1. The lab environment you're working in is a notebook-based coding environment. Notebooks, such as this one, consist of two types of cells: (1) text cells, also known as markdown cells, and (2) code cells.

Markdown cells allow you to write plain text and format it in the markdown language. Markdown language is used for formatting plain text in text editors and code editors. For example, you can use markdown to make headers, bold or italicize words, format text as code, add hyperlinks, and more.

2. In Python notebooks, code cells allow you to write code comments and code in Python.

To run a code cell, first place your cursor on the cell. Then, you can either click on the play icon, or press the Shift and Enter keys (or on some keyboards, the Shift and Return keys).

For this task, run the following code cell as is and observe the output.

```py

# This cell displays "Hello world!"

print("Hello world!")

```

3. Writing code comments is a way to document the intention behind code. It's a standard that analysts commonly use in their workflow. Writing comments that accompany code allows you to keep track of the technical decisions you've made in your project. This makes it easier for you and your team to read and revisit your code in order to understand what it does and why you took certain approaches.

For this task, run the following code cell as is and observe the output.


```py

# In Python, comments do not get displayed
# This code cell contains only comments

```

4. To type in a code cell, first click into the cell. Then you can write comments and code inside the cell.

For this task, add a comment at the beginning of the following code cell, describing what the code is doing. Write the comment to say # This cell displays "I am using Python.". Be sure to replace the # YOUR COMMENT HERE with your own comment before running the following cell.

```py

#  This cell displays "I am using Python."

print("I am using Python.")

```

5. In Python, print() helps you to display information to the screen.

For this task, use print() to display the message "I am a security analyst." by placing that message within the parentheses. Be sure to replace the ### YOUR CODE HERE ### with your own code before running the following code cell.

```py
# This cell displays "I am a security analyst."

print("I am a security analyst.")

```

6. For this task, write a print() statement to display the string "Python is useful for security!" Be sure to replace the ### YOUR CODE HERE ### with your own code before running the following code cell.

```py
# This cell displays "Python is useful for security!"

print("Python is useful for security!")

```

7. For your final task, you'll combine all the print() statements you've encountered and written in this lab up to this point, into one code cell.

Complete the following code with the remaining messages. Be sure to replace each ### YOUR CODE HERE ### with your own code before running the following cell.

```py
# This cell displays all the statements written so far

print("Hello world!")
print("I am using Python.")
print("I am a security analyst.")
print("Python is useful for security!")

```

[Activities content](#activities-content)

[Content](#content)

### Activity: Assign Python variables


1. In your work as an analyst, imagine there is a device only users specified on an allow list can access, and its device ID is "72e08x0".

In the following code cell, assign this value to a variable named device_id. Then, display the contents of the variable and observe the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign the `device_id` variable to the device ID that only specified users can access

device_id = "72e08x0"

# Display `device_id`

print(device_id)
```

2. Now that the variable device_id is defined, you can return its data type.

In this task, use a Python function to find the data type of the variable device_id. Store the data type in another variable called device_id_type. Then, display device_id_type to examine the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py

# Assign the `device_id` variable to the device ID that only specified users can access

device_id = "72e08x0"

# Assign `device_id_type` to the data type of `device_id`

device_id_type = type(device_id)

# Display `device_id_type`

print(device_id_type)
    

```

3. As you continue your work, you're provided a list of usernames of users who are allowed to access the device. The usernames with this access are "madebowa", "jnguyen", "tbecker", "nhersh", and "redwards".

In this task, create a variable called username_list. Assign a list with the approved usernames to this variable. Then, display the value of the username_list variable.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.


```py

# Assign `username_list` to the list of usernames who are allowed to access the device

username_list = ["madebowa", "jnguyen", "tbecker", "nhersh", "redwards"]

# Display `username_list`

print(username_list)


```

4. In this task, find the data type of the username_list. Store the type in a variable called username_list_type. Then, display username_list_type to examine the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py

# Assign `username_list` to the list of usernames who are allowed to access the device

username_list = ["madebowa", "jnguyen", "tbecker", "nhersh", "redwards"]

# Assign `username_list_type` to the data type of `username_list`

username_list_type = type(username_list)

# Display `username_list_type`

print(username_list_type)

```

5. Now, imagine that you've been informed that the previous list is not up-to-date and that there is another employee that now has access to the device. You're given the updated list of usernames with access, including the new employee, as follows: "madebowa", "jnguyen", "tbecker", "nhersh", "redwards", and "lpope".

In this task, reassign the variable username_list to the new list. Run the code to display the list before and after it's been updated to observe the difference.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign `username_list` to the list of usernames who are allowed to access the device

username_list = ["madebowa", "jnguyen", "tbecker", "nhersh", "redwards"]

# Display `username_list`

print(username_list)

# Assign `username_list` to the updated list of usernames who are allowed to access the device

username_list = ["madebowa", "jnguyen", "tbecker", "nhersh", "redwards", "lpope"]

# Display `username_list`

print(username_list)


```

6. In this task, define a variable called max_logins that represents the maximum number of login attempts allowed per user. Store the value 3 in this variable. Then, store its data type in another variable called max_logins_type. Display max_logins_type to examine the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign `max_logins` to the value 3

max_logins = 3

# Assign `max_logins_type` to the data type of `max_logins`

max_logins_type = type(max_logins)

# Display `max_logins_type`

print(max_logins_type)

```

7. In this task, define a variable called login_attempts that represents the current number of login attempts made by a user. Store the value 2 in this variable. Then, store its data type in a variable called login_attempts_type. Display login_attempts_type to observe the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign `login_attempts` to the value 2

login_attempts = 2

# Assign `login_attempts_type` to the data type of `login_attempts`

login_attempts_type = type(login_attempts)

# Display `login_attempts_type`

print(login_attempts_type)

```

8. In this task, you'll determine the Boolean value that represents whether the current number of login attempts a user has made is less than or equal to the maximum number of login attempts allowed.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign `max_logins` to the value 3

max_logins = 3

# Assign `login_attempts` to the value 2

login_attempts = 2

# Determine whether the current number of login attempts a user has made is less than or equal to the maximum number of login attempts allowed,
# and display the resulting Boolean value

print(login_attempts<= max_logins)
```

9. This code continues to check for the Boolean value of whether max_logins is less than or equal to login_attempts. In this task, reassign other values to login_attempts. For example, you might choose a value that is higher than the maximum number of attempts allowed. Observe how the output changes.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.


```py
# Assign `max_logins` to the value 3

max_logins = 3

# Assign `login_attempts` to a specific value

login_attempts = 4

# Determine whether the current number of login attempts a user has made is less than or equal to the maximum number of login attempts allowed,
# and display the resulting Boolean value

print(login_attempts <= max_logins)

```
10. Finally, you can also assign a Boolean value of True or False to a variable.

In this task, you'll create a variable called login_status, which is a Boolean that represents whether a user is logged in. Assign False to this variable and store its data type in a variable called login_status_type and display it.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign `login_status` to the Boolean value False

login_status = False

# Assign `login_status_type` to the data type of `login_status`

login_status_type = type(login_status)

# Display `login_status_type`

print(login_status_type)

```

[Activities content](#activities-content)

[Content](#content)

### Activity: Create a conditional statement


1. You are asked to help automate the process of checking whether a user's operating system requires an update. Imagine that a user's device can be running one of the following operating systems: OS 1, OS 2, or OS 3. While OS 2 is up-to-date, OS 1 and OS 3 are not. Your task is to check whether the user's system is up-to-date, and if it is, display a message accordingly. To do this, complete the conditional statement using the keyword if. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign a variable named `system` to a specific operating system, represented as a string
# This variable indicates which operating system is running
# Feel free to run this cell multiple times; each time try assigning `system` to different values ("OS 1", "OS 2", "OS 3") and observe the result

system = "OS 2"

# If OS 2 is running, then display a "no update needed" message

if system == "OS 2":
    print("no update needed")
```

2. Now try assigning the system variable to different values ("OS 1", "OS 2", and "OS 3"), run the cell, and observe what happens. Keep the conditional statement as is. Be sure to replace the ### YOUR CODE HERE ### with your own code.

```py

# Assign `system` to a specific operating system
# This variable represents which operating system is running
# Feel free to run this cell multiple times; each time try assigning `system` to different values ("OS 1", "OS 2", "OS 3") and observe the result

system = "OS 2"

# If OS 2 is running, then display a "no update needed" message

if system == "OS 2":
    print("no update needed")
    

```

3. Nothing is displayed when the system is not equal to "OS 2". This is because the condition didn't evaluate to True.

It would be beneficial if an alternative message is provided to them when updates are needed.

In the following cell, add the appropriate keyword after the first conditional so that it will display a message that conveys that an update is needed when the system is not running OS 2. Be sure to replace each ### YOUR CODE HERE ### with your own code.

Then, set the value of the system variable to indicate that OS 2 is running and run the cell. After observing what happens, set the value of system to indicate either that OS 1 is running or that OS 3 is running and run the cell.


```py

# Assign `system` to a specific operating system
# This variable represents which operating system is running

system = "OS 1"

# If OS 2 is running, then display a "no update needed" message
# Otherwise, display a "update needed" message

if system == "OS 2":
    print("no update needed")
else:
    print("update needed")


```

4. This setup is still not ideal. If the variable system contains a random string or integer, the conditional above would still display update needed.

To improve the conditional, you will need to add the elif keyword. In the following cell, you will add two elif statements after the if statement, to create the final code. The first elif statement will display update needed if system is "OS 1". The second elif statement will display the same message, if system is "OS 3". Complete the second elif statement, and then run the cell with the variable system set to a different string each time. Observe what happens when each operating system is running. Also try assigning the system variable to some strings other than "OS 1", "OS 2", and "OS 3" (for example "OS 4").

Be sure to replace each ### YOUR CODE HERE ### with your own code.

```py

# Assign `system` to a specific operating system
# This variable represents which operating system is running

system = "OS 1"

# If OS 2 is running, then display a "no update needed" message
# Otherwise if OS 1 is running, display a "update needed" message
# Otherwise if OS 3 is running, display a "update needed" message

if system == "OS 2":
    print("no update needed")
elif system == "OS 1":
    print("update needed")
elif system == "OS 3":
   print("update needed")

```

5. Writing code that is readable and concise is a best practice in programming.

The conditional above can be written more concisely.

In the following cell, use a logical operator to combine the two elif statements from the previous setup into one elif statement. Be sure to replace each ### YOUR CODE HERE ###. Then, assign the system variable to a value and run the cell. Like you did in the previous task, use "OS 1", "OS 2", "OS 3", and other strings.

```py
# Assign `system` to a specific operating system
# This variable represents which operating system is running

system = "OS 1"

# If OS 2 is running, then display a "no update needed" message
# Otherwise if either OS 1 or OS 3 is running, display a "update needed" message

if system == "OS 2":
    print("no update needed")
elif system == "OS 1" or system == "OS 3":
    print("update needed")

```

6. Now you'll move on to the next part of your work. You've been asked to investigate login attempts to a specific device. Only approved users should log on to this device.

You'll start with two authorized users, stored in the variables approved_user1 and approved_user2. You'll need to write a conditional statement that compares those variables to a third variable, username. This will be the username of a specific user trying to log in. Be sure to replace each ### YOUR CODE HERE ### with your own code.

```py
# Assign `approved_user1` and `approved_user2` to usernames of approved users

approved_user1 = "elarson"
approved_user2 = "bmoreno"

# Assign `username` to the username of a specific user trying to log in

username = "bmoreno"

# If the user trying to log in is among the approved users, then display a message that they are approved to access this device
# Otherwise, display a message that they do not have access to this device

if username == approved_user1 or username == approved_user2:
    print("This user has access to this device.")
else:
    print("This user does not have access to this device.")
    

```

7. The number of approved users has now expanded to five. Rather than storing each of the approved users' usernames individually, it would be more concise to store them in an allow list called approved_list.

The in operator in Python can be used to determine whether a given value is an element of a sequence. Using the in operator in a condition can help you check whether a specific username is part of a list of approved usernames. For example, in the code below, username in approved_list evaluates to True if the value of the username variable is included in approved_list.

Complete the code in the following cell to display the same messages that you used in the previous step. When the condition evaluates to True, the following message will be displayed: "This user has access to this device." When it evaluates to False, the following message will be displayed: "This user does not have access to this device." Then, run the cell to observe its behavior. Be sure to replace each ### YOUR CODE HERE ### with your own code. Afterwards, reassign the username variable to a username that is not approved and run the cell to observe what happens.

```py
# Assign `approved_list` to a list of approved usernames

approved_list = ["elarson", "bmoreno", "tshah", "sgilmore", "eraab"]

# Assign `username` to the username of a specific user trying to log in

username = "bmoreno"

# If the user trying to log in is among the approved users, then display a message that they are approved to access this device
# Otherwise, display a message that they do not have access to this device

if username in approved_list:
    print("This user has access to this device.")
else:
   print("This user does not have access to this device.")
    

```

8. Now you'll write another conditional statement. This one will use a organization_hours variable to check if the user logged in during specific organization hours. When that condition is met, the code should display the string "Login attempt made during organization hours.". When that condition isn't met, the code should display the string "Login attempt made outside of organization hours.".

The organization_hours variable will have a Boolean data type. If organization_hours has a Boolean value of True, that means the user is logged in during the specified organization hours. If organization_hours has a Boolean value of False, that means the user is not logged in during those hours.

Complete the conditional in the following cell. Be sure to replace each ### YOUR CODE HERE ### with your own code before running the following cell.

```py
# Assign `organization_hours` to a Boolean value that represents whether the user is trying to log in during organization hours

organization_hours = True

# If the entered `organization_hours` has a value of True, then display "Login attempt made during organization hours."
# Otherwise, display "Login attempt made outside of organization hours."

if organization_hours:
    print("Login attempt made during organization hours.")
else:
    print("Login attempt made outside of organization hours.")
    
```

9. The following cell assembles the code from the previous tasks. It includes the conditional statement that checks if a user is on the allow list and the conditional statement that checks if the user logged in during organization hours.

Run the cell below a few times. Each time, enter a different combination of values for username and organization_hours to observe how that affects the output.


```py
# Assign `approved_list` to a list of approved usernames

approved_list = ["elarson", "bmoreno", "tshah", "sgilmore", "eraab"]

# Assign `username` to the username of a specific user trying to log in

username = "bmoreno"

# If the user trying to log in is among the approved users, then display a message that they are approved to access this device
# Otherwise, display a message that they do not have access to this device

if username in approved_list:
    print("This user has access to this device.")

else:
    print("This user does not have access to this device.")

# Assign `organization_hours` to a Boolean value that represents whether the user is trying to log in during organization hours

organization_hours = True

# If the entered `organization_hours` has a value of True, then display "Login attempt made during organization hours."
# Otherwise, display "Login attempt made outside of organization hours."

if organization_hours == True:
    print("Login attempt made during organization hours.")
else:
    print("Login attempt made outside of organization hours.")

```
10. You can also provide a single message about the login attempt. To do this, you can join both conditions into a single conditional statement using a logical operator. This will make the code more concise.

Examine the code in the following cell and add the missing operator that would allow for a single message. Be sure to replace each ### YOUR CODE HERE ### with your own code before running the following cell. Then run the cell, entering different combinations of information, and observe what happens.

```py
# Assign `approved_list` to a list of approved usernames

approved_list = ["elarson", "bmoreno", "tshah", "sgilmore", "eraab"]

# Assign `username` to the username of a specific user trying to log in

username = "bmoreno"

# Assign `organization_hours` to a Boolean value that represents whether the user is trying to log in during organization hours

organization_hours = True

# If the user is among the approved users and they are logging in during organization hours, then convey that the user is logged in
# Otherwise, convey that either the username is not approved or the login attempt was made outside of organization hours

if username in approved_list and organization_hours == True:
    print("Login attempt made by an approved user during organization hours.")
else:
    print("Username not approved or login attempt made outside of organization hours.")


```

[Activities content](#activities-content)

[Content](#content)

 ### Activity: Create loops

1. In this task, you'll create a loop related to connecting to a network.

Write an iterative statement that displays Connection could not be established three times. Use the for keyword, the range() function, and a loop variable of i. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Iterative statement using `for`, `range()`, and a loop variable of `i`
# Display "Connection could not be established." three times

for i in range(3):
    print("Connection could not be established.")
```

2. The range() function can also take in a variable. To repeat a specified action a certain number of times, you can first assign an integer value to a variable. Then, you can pass that variable into the range() function within a for loop.

In your code that displays a network message connection, incorporate a variable called connection_attempts. Assign the positive integer of your choice as the value of that variable and fill in the missing variable in the iterative statement. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell. Test out the code with different values for connection_attempts and observe what happens.

```py

# Create a variable called `connection_attempts` that stores the number of times the user has tried to connect to the network

connection_attempts = 3

# Iterative statement using `for`, `range()`, a loop variable of `i`, and `connection_attempts`
# Display "Connection could not be established." as many times as specified by `connection_attempts`

for i in range(connection_attempts):
    print("Connection could not be established")

```

3. This task can also be achieved with a while loop. Complete the while loop with the correct code to instruct it to display "Connection could not be established." three times.

In this task, a for loop and a while loop will produce similar results, but each is based on a different approach. (In other words, the underlying logic is different in each.) A for loop terminates after a certain number of iterations have completed, whereas a while loop terminates once it reaches a certain condition. In situations where you do not know how many times the specified action should be repeated, while loops are most appropriate.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.


```py

# Assign `connection_attempts` to an initial value of 0, to keep track of how many times the user has tried to connect to the network

connection_attempts = 0

# Iterative statement using `while` and `connection_attempts`
# Display "Connection could not be established." every iteration, until connection_attempts reaches a specified number

while connection_attempts < 3:
    print("Connection could not be established.")

    # Update `connection_attempts` (increment it by 1 at the end of each iteration) 
    connection_attempts = connection_attempts + 1

```

4. Now, you'll move onto your next task. You'll automate checking whether IP addresses are part of an allow list. You will start with a list of IP addresses from which users have tried to log in, stored in a variable called ip_addresses. Write a for loop that displays the elements of this list one at a time. Use i as the loop variable in the for loop.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

```py

# Assign `ip_addresses` to a list of IP addresses from which users have tried to log in

ip_addresses = ["192.168.142.245", "192.168.109.50", "192.168.86.232", "192.168.131.147",
                "192.168.205.12", "192.168.200.48"]

# For loop that displays the elements of `ip_addresses` one at a time

for ip in ip_addresses:
    print(ip)

```

5. You are now given a list of IP addresses that are allowed to log in, stored in a variable called allow_list. Write an if statement inside of the for loop. For each IP address in the list of IP addresses from which users have tried to log in, display "IP address is allowed" if it is among the allowed addresses and display "IP address is not allowed" otherwise.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.
```py
# Assign `allow_list` to a list of IP addresses that are allowed to log in

allow_list = ["192.168.243.140", "192.168.205.12", "192.168.151.162", "192.168.178.71", 
              "192.168.86.232", "192.168.3.24", "192.168.170.243", "192.168.119.173"]

# Assign `ip_addresses` to a list of IP addresses from which users have tried to log in

ip_addresses = ["192.168.142.245", "192.168.109.50", "192.168.86.232", "192.168.131.147",
                "192.168.205.12", "192.168.200.48"]

# For each IP address in the list of IP addresses from which users have tried to log in, 
# If it is among the allowed addresses, then display “IP address is allowed”
# Otherwise, display “IP address is not allowed”

for i in ip_addresses:
    if i in allow_list:
        print("IP address is allowed")
    else:
        print("IP address is not allowed")

```

6. Imagine now that the information the users are trying to access is restricted, and if an IP address outside the list of allowed IP addresses attempts access, the loop should terminate because further investigation would be needed to assess whether this activity poses a threat. To achieve this, use the break keyword and expand the message that is displayed to the user when their IP address is not in allow_list to provide more specifics. Instead of "IP address is not allowed", display "IP address is not allowed. Further investigation of login activity required".

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign `allow_list` to a list of IP addresses that are allowed to log in

allow_list = ["192.168.243.140", "192.168.205.12", "192.168.151.162", "192.168.178.71", 
              "192.168.86.232", "192.168.3.24", "192.168.170.243", "192.168.119.173"]

# Assign `ip_addresses` to a list of IP addresses from which users have tried to log in

ip_addresses = ["192.168.142.245", "192.168.109.50", "192.168.86.232", "192.168.131.147",
                "192.168.205.12", "192.168.200.48"]

# For each IP address in the list of IP addresses from which users have tried to log in, 
# If it is among the allowed addresses, then display “IP address is allowed”
# Otherwise, display “IP address is not allowed”
               
for i in ip_addresses:
    if i in allow_list:
        print("IP address is allowed")
    else:
        print("IP address is not allowed") 
    
```

7. You'll now complete another task. This involves automating the creation of new employee IDs.

You have been asked to create employee IDs for a Sales department, with the criteria that the employee IDs should all be numbers that are unique, divisible by 5, and falling between 5000 and 5150. The employee IDs can include both 5000 and 5150.

Write a while loop that generates unique employee IDs for the Sales department by iterating through numbers and displays each ID created.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign the loop variable `i` to an initial value of 5000

i = 5000

# While loop that generates unique employee IDs for the Sales department by iterating through numbers
# and displays each ID created

while i <= 5150: 
    print(i)
    i +=5
    
```

8. You would like to incorporate a message that displays Only 10 valid employee ids remaining as a helpful alert once the loop variable reaches 5100.

To do so, include an if statement in your code.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign the loop variable `i` to an initial value of 5000

i = 5000

# While loop that generates unique employee IDs for the Sales department by iterating through numbers
# and displays each ID created
# This loop displays "Only 10 valid employee ids remaining" once `i` reaches 5100

while i <= 5150: 
    print(i)
    if i == 5100:
        print("Only 10 valid employee ids remaining")
    i = i + 5
    
```

[Activities content](#activities-content)

[Content](#content)

### Activity: Define and call a function

1. The following code cell contains a user-defined function named alert().

For this task, analyze the function definition, and make note of your observations.

You won't need to run the cell in order to answer the question that follows. But if you do run the cell, note that it will not produce an output because the function is just being defined here.

```py
# Define a function named `alert()` 

def alert():
    print("Potential security issue. Investigate further.")
```

2. For this task, call the alert() function that was defined earlier and analyze the output.

Be sure to replace the ### YOUR CODE HERE ### with your own code before running the following cell.

```py

# Define a function named `alert()` 

def alert():
    print("Potential security issue. Investigate further.")

# Call the `alert()` function

alert()
```

3. Functions can include other components that you've already worked with. The following code cell contains a variation of the alert() function that now uses a for loop to display the alert message multiple times.

For this task, call the new alert() function and observe the output.

Be sure to replace the ### YOUR CODE HERE ### with your own code before running the following cell.


```py

# Define a function named `alert()`

def alert(): 
    for i in range(3):
        print("Potential security issue. Investigate further.")

# Call the `alert()` function

alert()


```

4. In the next part of your work, you're going to work with a list of approved usernames, representing users who can enter a system. You'll be developing a function that helps you convert the list of approved usernames into one big string. Structuring this data differently enables you to work with it in different ways. For example, structuring the usernames as a list allows you to easily add or remove a username from it. In contrast, structuring it as a string allows you to easily place its contents into a text file.

For this task, start defining a function named list_to_string(). Write the function header.

Be sure to replace the ### YOUR CODE HERE ### with your own code. Note that running this cell will produce an error since this cell will just contain the function header; you'll write the function body and complete the function definition in a later task.

```py

# Define a function named `list_to_string()`

def list_to_string():

```

5. Now you'll begin to develop the body of the list_to_string() function.

In the following code cell, you're provided a list of approved usernames, stored in a variable named username_list. Your task is to complete the body of the list_to_string() function. Recall that the body of a function must be indented. To complete the function body, write a loop that iterates through the elements of the username_list and displays each element. Then, call the function and run the cell to observe what happens.

Be sure to replace each ### YOUR CODE HERE ### with your own code before running the following cell.

```py
# Define a function named `list_to_string()`

def list_to_string():

  # Store the list of approved usernames in a variable named `username_list`

  username_list = ["elarson", "bmoreno", "tshah", "sgilmore", "eraab", "gesparza", "alevitsk", "wjaffrey"]

  # Write a for loop that iterates through the elements of `username_list` and displays each element

  for i in username_list:
    print(i)

# Call the `list_to_string()` function

list_to_string()
```

6. String concatenation is a powerful concept in coding. It allows you to combine multiple strings together to form one large string, using the addition operator (+). Sometimes analysts need to merge individual pieces of data into a single string value. In this task, you'll use string concatenation to modify how the list_to_string() function is defined.

In the following code cell, you're provided a variable named sum_variable that initially contains an empty string. Your task is to use string concatenation to combine the usernames from the username_list and store the result in sum_variable.

In each iteration of the for loop, add the current element of username_list to sum_variable. At the end of the function definition, write a print() statement to display the value of sum_variable at that stage of the process. Then, run the cell to call the list_to_string() function and examine its output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before running the following cell.

```py
# Define a function named `list_to_string()`

def list_to_string():

  # Store the list of approved usernames in a variable named `username_list`

  username_list = ["elarson", "bmoreno", "tshah", "sgilmore", "eraab", "gesparza", "alevitsk", "wjaffrey"]

  # Assign `sum_variable` to an empty string

  sum_variable = ""

  # Write a for loop that iterates through the elements of `username_list` and displays each element

  for i in username_list:
    sum_variable = sum_variable + i

  # Display the value of `sum_variable`

  print(sum_variable)

# Call the `list_to_string()` function

list_to_string()

```

7. In this final task, you'll modify the code you wrote previously to improve the readability of the output.

This time, in the definition of the list_to_string() function, add a comma and a space (", ") after each username. This will prevent all the usernames from running into each other in the output. Adding a comma helps clearly separate one username from the next in the output. Adding a space following the comma as an additional separator between one username and the next makes it easier to read the output. Then, call the function and run the cell to observe the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before running the following cell.

```py
# Define a function named `list_to_string()`

def list_to_string():

  # Store the list of approved usernames in a variable named `username_list`

  username_list = ["elarson", "bmoreno", "tshah", "sgilmore", "eraab", "gesparza", "alevitsk", "wjaffrey"]

  # Assign `sum_variable` to an empty string

  sum_variable = ""

  # Write a for loop that iterates through the elements of `username_list` and displays each element

  for i in username_list:
    sum_variable = sum_variable + i + ", "

  # Display the value of `sum_variable`

  print(sum_variable)

# Call the `list_to_string()` function

list_to_string()
```

[Activities content](#activities-content)

[Content](#content)

### Activity: Create more functions

1. In your work as an analyst, imagine that you're provided a list of the number of failed login attempts per month, as follows:

119, 101, 99, 91, 92, 105, 108, 85, 88, 90, 264, and 223.

This list is organized in chronological order of months (January, February, March, April, May, June, July, August, September, October, November, and December).

This list is stored in a variable named failed_login_list.

In this task, use a built-in Python function to order the list. You'll pass the call to the function that sorts the list directly into the print() function. This will allow you to display and examine the result.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.
```py
# Assign `failed_login_list` to the list of the number of failed login attempts per month

failed_login_list = [119, 101, 99, 91, 92, 105, 108, 85, 88, 90, 264, 223]

# Sort `failed_login_list` in ascending numerical order and display the result

print(sorted(failed_login_list))
    
```

2. Now, you'll want to isolate the highest number of failed login attempts so you can later investigate information about the month when that highest value occurred.

You'll use the function that returns the largest numeric element from a list. Then, you'll pass this function into the print() function to display the result. This will allow you to determine which month to investigate further.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.
```py

# Assign `failed_login_list` to the list of the number of failed login attempts per month

failed_login_list = [119, 101, 99, 91, 92, 105, 108, 85, 88, 90, 264, 223]

# Determine the highest number of failed login attempts from `failed_login_list` and display the result

print(max(failed_login_list))

```

3. In your work as an analyst, you'll first define a function that displays a message about how many login attempts a user has made that day.

In this task, define a function named analyze_logins() that takes in two parameters, username and current_day_logins. Every time this function is called, it should display a message about the number of login attempts the user has made that day.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell. Note that the code cell will contain only a function definition, so running it will not produce an output.

```py
# Define a function named `analyze_logins()` that takes in two parameters, `username` and `current_day_logins`

def analyze_logins(username, current_day_logins):

    # Display a message about how many login attempts the user has made that day

    print("Current day login total for", username, "is", current_day_logins)
    
```

4. Now that you've defined the analyze_logins() function, call it to test out how it behaves.

Call analyze_logins() with the arguments "ejones" and 9.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py

# Define a function named `analyze_logins()` that takes in two parameters, `username` and `current_day_logins`

def analyze_logins(username, current_day_logins):

    # Display a message about how many login attempts the user has made that day

    print("Current day login total for", username, "is", current_day_logins)

# Call `analyze_logins()`

analyze_logins("ejones",9)


```

5. Now, you'll need to expand this function so that it also provides the average number of login attempts made by the user on that day. Doing this will require incorporating a third parameter into the function definition.

In this task, add a parameter called average_day_logins. The code will use this parameter to display an additional message. The additional message will convey the average login attemps made by the user on that day. Then, call the function with the same first and second arguments as used in Task 4 and a third argument of 3.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Define a function named `analyze_logins()` that takes in three parameters, `username`, `current_day_logins`, and `average_day_logins`

def analyze_logins(username, current_day_logins, average_day_logins ):

    # Display a message about how many login attempts the user has made that day

    print("Current day login total for", username, "is", current_day_logins)

    # Display a message about average number of login attempts the user has made that day

    print("Average logins per day for", username, "is", average_day_logins)

# Call `analyze_logins()`

analyze_logins("ejones",9,3)
    
```

6. In this task, you'll further expand the function. Include a calculation to get the ratio of the logins made on the current day to the logins made on an average day. Store this in a new variable named login_ratio. The function displays an additional message that uses this variable.

Note that if average_day_logins is equal to 0, then dividing current_day_logins by average_day_logins will cause an error. Due to the error, Python will display the following message: ZeroDivisionError: division by zero. For this activity, assume that all users will have logged in at least once before. This means that their average_day_logins will be greater than 0, and the function will not involve dividing by zero.

After defining the function, call the function with the same arguments that you used in the previous task.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Define a function named `analyze_logins()` that takes in three parameters, `username`, `current_day_logins`, and `average_day_logins`

def analyze_logins(username, current_day_logins, average_day_logins):

    # Display a message about how many login attempts the user has made that day

    print("Current day login total for", username, "is", current_day_logins)

    # Display a message about average number of login attempts the user has made that day

    print("Average logins per day for", username, "is", average_day_logins)

    # Calculate the ratio of the logins made on the current day to the logins made on an average day, storing in a variable named `login_ratio`

    login_ratio = current_day_logins / average_day_logins

    # Display a message about the ratio

    print(username, "logged in", login_ratio, "times as much as they do on an average day.")

# Call `analyze_logins()`

analyze_logins("ejones",9,3)

```

7. You'll continue working with the analyze_logins() function and add a return statement to it. Return statements allow you to send information back to the function call.

In this task, use the return keyword to output the login_ratio from the function, so that it can be used later in your work.

You'll call the function with the same arguments used in the previous task and store the output from the function call in a variable named login_analysis. You'll then use a print() statement to display the saved information.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Define a function named `analyze_logins()` that takes in three parameters, `username`, `current_day_logins`, and `average_day_logins`

def analyze_logins(username, current_day_logins, average_day_logins):

    # Display a message about how many login attempts the user has made that day

    print("Current day login total for", username, "is", current_day_logins)

    # Display a message about average number of login attempts the user has made that day

    print("Average logins per day for", username, "is", average_day_logins)

    # Calculate the ratio of the logins made on the current day to the logins made on an average day, storing in a variable named `login_ratio`

    login_ratio = current_day_logins / average_day_logins

    # Return the ratio

    return login_ratio

# Call `analyze_logins() and store the output in a variable named `login_analysis`

login_analysis = analyze_logins("ejones", 9, 3)

# Display a message about the `login_analysis`

print("ejones", "logged in", login_analysis, "times as much as they do on an average day.")
```

8. In this task, you'll use the value of login_analysis in a conditional statement. When the value of login_analysis is greater than or equal to 3, then the login activity will require further investigation, and an alert will be displayed. Incorporate this condition to complete the conditional statement in the code.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Define a function named `analyze_logins()` that takes in three parameters, `username`, `current_day_logins`, and `average_day_logins`

def analyze_logins(username, current_day_logins, average_day_logins):

    # Display a message about how many login attempts the user has made that day

    print("Current day login total for", username, "is", current_day_logins)

    # Display a message about average number of login attempts the user has made that day

    print("Average logins per day for", username, "is", average_day_logins)

    # Calculate the ratio of the logins made on the current day to the logins made on an average day, storing in a variable named `login_ratio`

    login_ratio = current_day_logins / average_day_logins

    # Return the ratio

    return login_ratio

# Call `analyze_logins() and store the output in a variable named `login_analysis`

login_analysis = analyze_logins("ejones", 9, 3)

# Conditional statement that displays an alert about the login activity if it's more than normal

if login_analysis >= 3:
    print("Alert! This account has more login activity than normal.")
    
```

[Activities content](#activities-content)

[Content](#content)


### Activity: Activity: Work with strings in Python

1. In your organization, employee IDs are currently either four digits or five digits in length. In this task, you're given a four-digit numeric employee ID stored in a variable called employee_id. Convert this to a string format and store the result in the same variable. Later, you'll update this employee ID string so that it complies with a new standardized format.

Complete the following code. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign `employee_id` to a four digit number as an initial value

employee_id = 4186

# Display the data type of `employee_id`

print(type(employee_id))

# Reassign `employee_id` to the same value but in the form of a string

employee_id = "4186"

# Display the data type of `employee_id` now

print(type(employee_id))

```

2. Imagine that you have just been informed of a new criteria for employee IDs. They must all be five digits long for standardization purposes.

In this task, you will write a conditional statement that displays a message if the length of the employee ID is less than five digits.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

```py

# Assign `employee_id` to a four digit number as an initial value

employee_id = 4186

# Reassign `employee_id` to the same value but in the form of a string

employee_id = str(employee_id)

# Conditional statement that displays a message if the length of `employee_id` is less than five digits

if len(employee_id) < 5:
    print("This employee ID has less than five digits. It does not meet length requirements.")
    
```

3. In this task, you'll build upon the previous code. If an employee ID is only four digits, you'll use concatenation to create a five-digit employee ID number.

Concatenation is a process that allows you to merge strings together. The addition operator (+) in Python allows you to concatenate two strings.

Write an if statement that evaluates whether the length of employee_id is less than 5. When the condition evaluates to True, reassign employee_id by concatenating "E" in front of the four-digit employee ID to create a five character employee ID. Then, display employee_id again. Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.


```py

# Assign `employee_id` to a four digit number as an initial value

employee_id = 4186

# Reassign `employee_id` to the same value but in the form of a string

employee_id = str(employee_id)

# Display the `employee_id` as it currently stands

print(employee_id)

# Conditional statement that updates the `employee_id` if its length is less than 5 digits

if len(employee_id) < 5:
    employee_id = employee_id + "E"
    
# Display the `employee_id` after the update
    
print(employee_id)

```

4. Now you'll move on to the next part of your task. Imagine that the characters in a device ID convey technical information about the device. You'll need to extract characters in specific positions from the device ID. Start off by extracting the fourth character.

The variable device_id represents a device ID containing alphanumeric characters; it's already stored as a string.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

```py

# Assign `device_id` to a string that contains alphanumeric characters

device_id = "r262c36"

# Extract the fourth character in `device_id` and display it

print(device_id[3])
```

5. Now you will also need to extract the first through the third characters in the device ID. So take a slice of the device ID. You can achieve this using bracket notation in Python. Then, display the slice to examine the result.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.
```py
# Assign `device_id` to a string that contains alphanumeric characters

device_id = "r262c36"

# Extract the first through the third characters in `device_id` and display the result

print(device_id[0:2])

```

6. You'll now proceed to the last part of your task. This involves extracting components of a URL.

You'll work with string indices to display various components of a URL that's stored in the URL variable. First, you'll extract and display the protocol of the URL and the :// characters that follow it using string slicing. Consider that the protocol is in the secure format of https when determining the indices for your slice.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign `url` to a specific URL

url = "https://exampleURL1.com"

# Extract the protocol of `url` along with the syntax following it, display the result

print(url[0:5])
```

7. Later in this lab, you'll extract the domain extension. To prepare for this, use the .index() method to identify the index where the domain extension .com is located in the given URL.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.
```py
# Assign `url` to a specific URL

url = "https://exampleURL1.com"

# Display the index where the domain extension ".com" is located in `url`

print(url.index(".com"))
    
```

8. It's a good idea to save important data in variables when programming. This allows for quick and easy tracking and reuse of information.

Store the output of the .index() method in a variable called ind, which is short for index. This index represents the position where the domain extension ".com" starts in the url. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell. Note that running this cell will not produce an output.
```py
# Assign `url` to a specific URL

url = "https://exampleURL1.com"

# Assign `ind` to the output of applying `.index()` to `url` in order to extract the starting index of ".com" in `url` 

ind = url.index(".com")
```

9. You can use string slicing to also extract the domain extension of a URL. To do so, you can create a slice. The starting index should be the ind variable. This contains the index where the domain extension begins. The ending index should be ind + 4 (since ".com" is four characters long). Sometimes, like in this situation, it's easier to express the ending index in relation to the starting index. Examine the following code, run it as is, and observe the output.
```py
# Assign `url` to a specific URL

url = "https://exampleURL1.com"

# Assign `ind` to the output of applying `.index()` to `url` in order to extract the starting index of ".com" in `url` 

ind = url.index(".com")

# Extract the domain extension in `url` and display it

print(url[ind:ind+4])
```

10. Finally, extract the website name from the given URL using string slicing and the ind variable that you defined earlier. In the given URL, the website name is "exampleURL1". Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.
```py
# Assign `url` to a specific URL

url = "https://exampleURL1.com"

# Assign `ind` to the output of applying `.index()` to `url` in order to extract the starting index of ".com" in `url` 

ind = url.index(".com")

# Extract the website name in `url` and display it

print(url[8:ind])
    
```

[Activities content](#activities-content)

[Content](#content)

### Activity: Develop an algorithm

1. You'll work with a list of approved usernames along with a list of the approved devices assigned to these users. The elements of the two lists are synchronized. In other words, the user at index 0 in approved_users uses the device at index 0 in approved_devices. Later, this will allow you to verify if the username and device ID entered by a user correspond to each other.

First, to explore how indices in lists work, run the following code cell as is and observe the output. Then, replace each 0 with another index and run the cell to observe what happens.

```py
# Assign `approved_users` to a list of approved usernames

approved_users = ["elarson", "bmoreno", "tshah", "sgilmore", "eraab"]

# Assign `approved_devices` to a list of device IDs that correspond to the usernames in `approved_users`

approved_devices = ["8rp2k75", "hl0s5o1", "2ye3lzg", "4n482ts", "a307vir"]

# Display the element at the specified index in `approved_users`

print(approved_users[0])

# Display the element at the specified index in `approved_devices`

print(approved_devices[0])
```

2. There's a new employee joining the organization, and they need to be provided with a username and device ID. In the following code cell, you are given a username and device ID of this new user, stored in the variables new_user and new_device, respectively. Use the .append() method to add these variables to the approved_users and approved_devices respectively. Afterwards, display the approved_users and approved_devices variables to confirm the added information. Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py

# Assign `approved_users` to a list of approved usernames

approved_users = ["elarson", "bmoreno", "tshah", "sgilmore", "eraab"]

# Assign `approved_devices` to a list of device IDs that correspond to the usernames in `approved_users`

approved_devices = ["8rp2k75", "hl0s5o1", "2ye3lzg", "4n482ts", "a307vir"]

# Assign `new_user` to the username of a new approved user

new_user = "gesparza"

# Assign `new_device` to the device ID of the new approved user

new_device = "3rcv4w6"

# Add that user's username and device ID to `approved_users` and `approved_devices` respectively

approved_users.append(new_user)
approved_devices.append(new_device)

# Display the contents of `approved_users`

print(approved_users)

# Diplay the contents of `approved_devices`

print(approved_devices)
```

3. An employee has left the team and should no longer have access to the system. In the following code cell, you are given the username and device ID of the user to be removed, stored in the variables removed_user and removed_device respectively. Use the .remove() method to remove each of these elements from the corresponding list. Afterwards, display both the approved_users and the approved_devices variables to view the removed users. Run the code and observe the results. Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.


```py

# Assign `approved_users` to a list of approved usernames

approved_users = ["elarson", "bmoreno", "tshah", "sgilmore", "eraab", "gesparza"]

# Assign `approved_devices` to a list of device IDs that correspond to the usernames in `approved_users`

approved_devices = ["8rp2k75", "hl0s5o1", "2ye3lzg", "4n482ts", "a307vir", "3rcv4w6"]

# Assign `removed_user` to the username of the employee who has left the team

removed_user = "tshah"

# Assign `removed_device` to the device ID of the employee who has left the team

removed_device = "2ye3lzg"

# Remove that employee's username and device ID from `approved_users` and `approved_devices` respectively

approved_users.remove(removed_user)
approved_devices.remove(removed_device)

# Display `approved_users`

print(approved_users)

# Diplay `approved_devices`

print(approved_devices)

```

4. As part of verifying a user's identity in the system, you'll need to check if the user is one of the approved users. Write a conditional statement that verifies if a given username is an element of the list of approved usernames. If it is, display "The user ______ is approved to access the system.". Otherwise, display "The user ______ is not approved to access the system.". Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py

# Assign `approved_users` to a list of approved usernames

approved_users = ["elarson", "bmoreno", "sgilmore", "eraab", "gesparza"]

# Assign `approved_devices` to a list of device IDs that correspond to the usernames in `approved_users`

approved_devices = ["8rp2k75", "hl0s5o1", "4n482ts", "a307vir", "3rcv4w6"]

# Assign `username` to a username

username = "sgilmore"

# Conditional statement
# If `username` belongs to `approved_users`, then display "The user ______ is approved to access the system."
# Otherwise display "The user ______ is not approved to access the system."
if username in approved_users:
    print("The user", username, "is approved to access the system.")
else:
    print("The user", username, "is not approved to access the system.")
```

5. In the next part of the algorithm, you'll be using the .index() method to find the index of username in the approved_users and store that index in a variable named ind.

When used on a list, the .index() method will return the position of the given value in the list.

Add a statement to display ind in the following code cell to explore the value it contains. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.
```py
# Assign `approved_users` to a list of approved usernames

approved_users = ["elarson", "bmoreno", "sgilmore", "eraab", "gesparza"]

# Assign `approved_devices` to a list of device IDs that correspond to the usernames in `approved_users`

approved_devices = ["8rp2k75", "hl0s5o1", "4n482ts", "a307vir", "3rcv4w6"]

# Assign `username` to a username

username = "sgilmore"

# Assign `ind` to the index of `username` in `approved_users`

ind = approved_users.index(username)

# Display the value of `ind`

print(approved_users[ind])

```

6. This task will allow you to build your understanding of list operations for the algorithm that you'll eventually build. It will demonstrate how you can find an index in one list and then use this index to display connected information in another list. First, use the .index() method again to find the index of username in the approved_users and store that in a variable named ind. Then, connect ind to the approved_devices and display the device ID located at the index ind. Afterwards, run the cell to observe the result. Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign `approved_users` to a list of approved usernames

approved_users = ["elarson", "bmoreno", "sgilmore", "eraab", "gesparza"]

# Assign `approved_devices` to a list of device IDs that correspond to the usernames in `approved_users`

approved_devices = ["8rp2k75", "hl0s5o1", "4n482ts", "a307vir", "3rcv4w6"]

# Assign `username` to a username

username = "sgilmore"

# Assign `ind` to the index of `username` in `approved_users`

ind = approved_users.index(username)

# Display the device ID at the index that matches the value of `ind` in `approved_devices`

print(approved_devices[ind])
```

7. Your next step in creating the algorithm is to determine if a username and device ID correspond. To do this, write a conditional that checks if the username is an element of the approved_devices and if the device_id stored at the same index as username matches the device_id entered. You'll use the logical operator and to connect the two conditions. When both conditions evaluate to True, display a message that the username is approved and another message that the user has their assigned device. Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign `approved_users` to a list of approved usernames

approved_users = ["elarson", "bmoreno", "sgilmore", "eraab", "gesparza"]

# Assign `approved_devices` to a list of device IDs that correspond to the usernames in `approved_users`

approved_devices = ["8rp2k75", "hl0s5o1", "4n482ts", "a307vir", "3rcv4w6"]

# Assign `username` to a username

username = "sgilmore"

# Assign `device_id` to a device ID

device_id = "4n482ts"

# Assign `ind` to the index of `username` in `approved_users`

ind = approved_users.index(username)

# Conditional statement
# If `username` belongs to `approved_users`, and if the device ID at `ind` in `approved_devices` matches `device_id`,
# then display a message that the username is approved,
# followed by a message that the user has the correct device

if username in approved_users and device_id == approved_devices[ind]:
    print("The username", username, "is approved to access the system.")
    print(device_id, "is the assigned device for", username)

```

8. It would also be helpful for users to receive messages when their username is not approved or their device ID is incorrect.

Add to the code by writing an elif statement. This elif statement should run when the username is part of the approved_users but the device_id doesn't match the corresponding device ID in the approved_devices. The statement should also display two messages conveying that information.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

(After you run the code once with a device_id of "4n482ts", you might want to explore what happens if you assign a different value to device_id.)

```py
# Assign `approved_users` to a list of approved usernames

approved_users = ["elarson", "bmoreno", "sgilmore", "eraab", "gesparza"]

# Assign `approved_devices` to a list of device IDs that correspond to the usernames in `approved_users`

approved_devices = ["8rp2k75", "hl0s5o1", "4n482ts", "a307vir", "3rcv4w6"]

# Assign `username` to a username

username = "sgilmore"

# Assign `device_id` to a device ID

device_id = "4n482ts"

# Assign `ind` to the index of `username` in `approved_users`

ind = approved_users.index(username)

# If statement
# If `username` belongs to `approved_users`, and if the element at `ind` in `approved_devices` matches `device_id`,
# then display a message that the username is approved,
# followed by a message that the user has the correct device

if username in approved_users and device_id == approved_devices[ind]:
    print("The user", username, "is approved to access the system.")
    print(device_id, "is the assigned device for", username)

# Elif statement
# Handles the case when `username` belongs to `approved_users` but element at `ind` in `approved_devices` does not match `device_id`,
# and displays two messages accordingly

elif username in approved_users and device_id != approved_devices[ind]:
    print("The user", username, "is approved to access the system, but", device_id, "is not their assigned device.")
    
```

9. In this task, you'll complete your algorithm by developing a function that uses some of the code you've written in earlier tasks. This will automate the login process.

There are multiple ways to use conditionals to automate the login process. In the following code, a nested conditional is used to achieve the goals of the algorithm. There is a conditional statement inside of another conditional statement. The outer conditional handles the case when the username is approved and the case when username is not approved. The inner conditional, which is placed inside the first if statement, handles the case when the username is approved and the device_id is correct, as well as the case when the username is approved and the device_id is incorrect.

To complete this task, you must define a function named login that takes in two parameters, username and device_id. Afterwards, call the function and pass in different username and device ID combinations to experiment and observe the function's behavior. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign `approved_users` to a list of approved usernames

approved_users = ["elarson", "bmoreno", "sgilmore", "eraab", "gesparza"]

# Assign `approved_devices` to a list of device IDs that correspond to the usernames in `approved_users`

approved_devices = ["8rp2k75", "hl0s5o1", "4n482ts", "a307vir", "3rcv4w6"]

# Define a function named `login` that takes in two parameters, `username` and `device_id`

def login(username, device_id):

    # If `username` belongs to `approved_users`,

    if username in approved_users:

        # then display "The user ______ is approved to access the system.",

        print("The user", username, "is approved to access the system.")

        # assign `ind` to the index of `username` in `approved_users`,

        ind = approved_users.index(username)

        # and execute the following conditional
        # If `device_id` matches the element at the index `ind` in `approved_devices`,

        if device_id == approved_devices[ind]:

          # then display "______ is the assigned device for ______"

          print(device_id, "is the assigned device for", username)

        # Otherwise,

        else:

          # display "______ is not their assigned device"

          print(device_id, "is not their assigned device.")

    # Otherwise (part of the outer conditional and handles the case when `username` does not belong to `approved_users`),

    else:

        # Display "The user ______ is not approved to access the system."

        print("The username", username, "is not approved to access the system.")

# Call the function you just defined to experiment with different username and device_id combinations

login("elarson","8rp2k75")
login("elarson","a307vir")
login("ela","a307vir")

```

[Activities content](#activities-content)

[Content](#content)

### Activity: Use regular expressions to find patterns

1. In order to work with regular expressions in Python, start by importing the re module. This module contains many functions that will help you work with regular expressions. By running the following code cell, the module will be available through the rest of the notebook.
```py
# Import the `re` module in Python

import re
```

2. Currently, you are looking for device IDs that begin with "r15". These characters indicate that the device is running an operating system that must be updated.

You're given a log of device IDs, stored in a variable named devices. Your eventual goal is to extract the device IDs that start with the characters "r15". For now, display the contents of the whole string to examine what it contains. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

```py

# Assign `devices` to a string containing device IDs, each device ID represented by alphanumeric characters

devices = "r262c36 67bv8fy 41j1u2e r151dm4 1270t3o 42dr56i r15xk9h 2j33krk 253be78 ac742a1 r15u9q5 zh86b2l ii286fq 9x482kt 6oa6m6u x3463ac i4l56nq g07h55q 081qc9t r159r1u"

# Display the contents of `devices`

print(devices)
```

3. In this task, you'll write a pattern to find devices that start with the character combination of "r15".

Use the regular expression symbols \w and + to create the pattern, and store it as a string in a variable named target_pattern.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell. Note that the code cell will contain only variable assignments, so running it will not produce an output.


```py

# Assign `devices` to a string containing device IDs, each device ID represented by alphanumeric characters

devices = "r262c36 67bv8fy 41j1u2e r151dm4 1270t3o 42dr56i r15xk9h 2j33krk 253be78 ac742a1 r15u9q5 zh86b2l ii286fq 9x482kt 6oa6m6u x3463ac i4l56nq g07h55q 081qc9t r159r1u"

# Assign `target_pattern` to a regular expression pattern for finding device IDs that start with "r15"

target_pattern = "r15\w+"
```

4. Use the findall() function from the re module to find the device IDs that the target_pattern matches with. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

Note: In order to use re.findall() in Tasks 4, 7, 8, 9 and 11, you must have previously run the code import re in Task 1.

```py

import re

# Assign `devices` to a string containing device IDs, each device ID represented by alphanumeric characters

devices = "r262c36 67bv8fy 41j1u2e r151dm4 1270t3o 42dr56i r15xk9h 2j33krk 253be78 ac742a1 r15u9q5 zh86b2l ii286fq 9x482kt 6oa6m6u x3463ac i4l56nq g07h55q 081qc9t r159r1u"

# Assign `target_pattern` to a regular expression pattern for finding device IDs that start with "r15"

target_pattern = "r15\w+"

# Use `re.findall()` to find the device IDs that start with "r15" and display the results

print(re.findall(target_pattern, devices))
```

5. Now, the next task you're responsible for is analyzing a network security log file and determining which IP addresses have been flagged for unusual activity.

You're given the log file as a string stored in a variable named log_file. There are some invalid IP addresses in the log file due to issues in data collection. Your eventual goal is to use regular expressions to extract the valid IP addresses from the string.

Start by displaying the contents of the log_file to examine the details inside. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.
```py
# Assign `log_file` to a string containing username, date, login time, and IP address for a series of login attempts 

log_file = "eraab 2022-05-10 6:03:41 192.168.152.148 \niuduike 2022-05-09 6:46:40 192.168.22.115 \nsmartell 2022-05-09 19:30:32 192.168.190.178 \narutley 2022-05-12 17:00:59 1923.1689.3.24 \nrjensen 2022-05-11 0:59:26 192.168.213.128 \naestrada 2022-05-09 19:28:12 1924.1680.27.57 \nasundara 2022-05-11 18:38:07 192.168.96.200 \ndkot 2022-05-12 10:52:00 1921.168.1283.75 \nabernard 2022-05-12 23:38:46 19245.168.2345.49 \ncjackson 2022-05-12 19:36:42 192.168.247.153 \njclark 2022-05-10 10:48:02 192.168.174.117 \nalevitsk 2022-05-08 12:09:10 192.16874.1390.176 \njrafael 2022-05-10 22:40:01 192.168.148.115 \nyappiah 2022-05-12 10:37:22 192.168.103.10654 \ndaquino 2022-05-08 7:02:35 192.168.168.144"

# Display contents of `log_file`
print(log_file)
```

6. In this task, you'll build a regular expression pattern that you can use later on to extract IP addresses that are in the form of xxx.xxx.xxx.xxx. In other words, you'll extract all IP addresses that contain four segments of three digits that are separated by periods.

Write a regular expression pattern that will match with these IP addresses and store it in a variable named pattern. Use the regular expression symbols \d and \. in your pattern. Note that the symbol \d matches with digits, in other words, any integer between 0 and 9. Be sure to replace the ### YOUR CODE HERE ### with your own code. Since you'll just build the pattern here, there won't be any output when you run this cell.

```py
# Assign `log_file` to a string containing username, date, login time, and IP address for a series of login attempts 

log_file = "eraab 2022-05-10 6:03:41 192.168.152.148 \niuduike 2022-05-09 6:46:40 192.168.22.115 \nsmartell 2022-05-09 19:30:32 192.168.190.178 \narutley 2022-05-12 17:00:59 1923.1689.3.24 \nrjensen 2022-05-11 0:59:26 192.168.213.128 \naestrada 2022-05-09 19:28:12 1924.1680.27.57 \nasundara 2022-05-11 18:38:07 192.168.96.200 \ndkot 2022-05-12 10:52:00 1921.168.1283.75 \nabernard 2022-05-12 23:38:46 19245.168.2345.49 \ncjackson 2022-05-12 19:36:42 192.168.247.153 \njclark 2022-05-10 10:48:02 192.168.174.117 \nalevitsk 2022-05-08 12:09:10 192.16874.1390.176 \njrafael 2022-05-10 22:40:01 192.168.148.115 \nyappiah 2022-05-12 10:37:22 192.168.103.10654 \ndaquino 2022-05-08 7:02:35 192.168.168.144"

# Assign `pattern` to a regular expression pattern that will match with IP addresses of the form xxx.xxx.xxx.xxx

pattern = "\d\d\d\.\d\d\d\.\d\d\d\.\d\d\d"
```

7. In this task, you'll use the re.findall() function on the regular expression pattern stored in the pattern variable and the provided log_file to extract the corresponding IP addresses. Afterwards, run the cell and take note of what it outputs. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
import re
# Assign `log_file` to a string containing username, date, login time, and IP address for a series of login attempts 

log_file = "eraab 2022-05-10 6:03:41 192.168.152.148 \niuduike 2022-05-09 6:46:40 192.168.22.115 \nsmartell 2022-05-09 19:30:32 192.168.190.178 \narutley 2022-05-12 17:00:59 1923.1689.3.24 \nrjensen 2022-05-11 0:59:26 192.168.213.128 \naestrada 2022-05-09 19:28:12 1924.1680.27.57 \nasundara 2022-05-11 18:38:07 192.168.96.200 \ndkot 2022-05-12 10:52:00 1921.168.1283.75 \nabernard 2022-05-12 23:38:46 19245.168.2345.49 \ncjackson 2022-05-12 19:36:42 192.168.247.153 \njclark 2022-05-10 10:48:02 192.168.174.117 \nalevitsk 2022-05-08 12:09:10 192.16874.1390.176 \njrafael 2022-05-10 22:40:01 192.168.148.115 \nyappiah 2022-05-12 10:37:22 192.168.103.10654 \ndaquino 2022-05-08 7:02:35 192.168.168.144"

# Assign `pattern` to a regular expression pattern that will match with IP addresses of the form xxx.xxx.xxx.xxx

pattern = "\d\d\d\.\d\d\d\.\d\d\d\.\d\d\d"

# Use the `re.findall()` function on `pattern` and `log_file` to extract the IP addresses of the form xxx.xxx.xxx.xxx and display the results

print(re.findall(pattern, log_file))
```

8. There are some valid IP addresses in the log_file that you haven't extracted yet. This is because each segment of digits in a valid IP address can have anywhere between one and three digits.

Adjust the regular expression in the pattern to allow for variation in the number of digits in each segment. You can do this by using the + symbol after the \d symbol. Afterwards, use the updated pattern to extract remaining IP addresses. Then, run the cell to analyze the results. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
import re
# Assign `log_file` to a string containing username, date, login time, and IP address for a series of login attempts 

log_file = "eraab 2022-05-10 6:03:41 192.168.152.148 \niuduike 2022-05-09 6:46:40 192.168.22.115 \nsmartell 2022-05-09 19:30:32 192.168.190.178 \narutley 2022-05-12 17:00:59 1923.1689.3.24 \nrjensen 2022-05-11 0:59:26 192.168.213.128 \naestrada 2022-05-09 19:28:12 1924.1680.27.57 \nasundara 2022-05-11 18:38:07 192.168.96.200 \ndkot 2022-05-12 10:52:00 1921.168.1283.75 \nabernard 2022-05-12 23:38:46 19245.168.2345.49 \ncjackson 2022-05-12 19:36:42 192.168.247.153 \njclark 2022-05-10 10:48:02 192.168.174.117 \nalevitsk 2022-05-08 12:09:10 192.16874.1390.176 \njrafael 2022-05-10 22:40:01 192.168.148.115 \nyappiah 2022-05-12 10:37:22 192.168.103.10654 \ndaquino 2022-05-08 7:02:35 192.168.168.144"

# Update `pattern` to a regular expression pattern that will match with IP addresses with any variation in the number of digits per segment

pattern = "\d+\.\d+\.\d+\.\d+"

# Use the `re.findall()` function on `pattern` and `log_file` to extract the IP addresses of the updated form specifed above and display the results

print(re.findall(pattern, log_file))
```

9. Note that all the IP addresses are now extracted but they also include invalid IP addresses with more than three digits per segment.

In this task, you'll update the pattern using curly brackets instead of the + symbol. In regular expressions, curly brackets can be used to represent an exact number of repetitions between two numbers. For example, {2,4} in a regular expression means between 2 and 4 occurrences of something. Applying this to an example, \w{2,4} would match with two, three, or four alphanumeric characters. Afterwards, you'll call the re.findall() function on the updated pattern and the log_file and store the output in a variable named valid_ip_addresses.

Then, display the contents of valid_ip_addresses and run the cell to analyze the results. Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
# Assign `log_file` to a string containing username, date, login time, and IP address for a series of login attempts 

log_file = "eraab 2022-05-10 6:03:41 192.168.152.148 \niuduike 2022-05-09 6:46:40 192.168.22.115 \nsmartell 2022-05-09 19:30:32 192.168.190.178 \narutley 2022-05-12 17:00:59 1923.1689.3.24 \nrjensen 2022-05-11 0:59:26 192.168.213.128 \naestrada 2022-05-09 19:28:12 1924.1680.27.57 \nasundara 2022-05-11 18:38:07 192.168.96.200 \ndkot 2022-05-12 10:52:00 1921.168.1283.75 \nabernard 2022-05-12 23:38:46 19245.168.2345.49 \ncjackson 2022-05-12 19:36:42 192.168.247.153 \njclark 2022-05-10 10:48:02 192.168.174.117 \nalevitsk 2022-05-08 12:09:10 192.16874.1390.176 \njrafael 2022-05-10 22:40:01 192.168.148.115 \nyappiah 2022-05-12 10:37:22 192.168.103.10654 \ndaquino 2022-05-08 7:02:35 192.168.168.144"

# Assign `pattern` to a regular expression that matches with all valid IP addresses and only those 

pattern = "\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}"

# Use `re.findall()` on `pattern` and `log_file` and assign `valid_ip_addresses` to the output 

valid_ip_addresses = re.findall(pattern, log_file)

# Display the contents of `valid_ip_addresses`

print(valid_ip_addresses)

```

10. Now, all of the valid IP addresses have been extracted. The next step is to identify flagged IP addresses.

You're given a list of IP addresses that have been previously flagged for unusual activity, stored in a variable named flagged_addresses. When these addresses are encountered, they should be investigated further. This list is just for educational purposes and contains examples of private IP addresses that are found only within internal networks.

Display this list and examine what it contains by running the cell. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.
```py
# Assign `flagged_addresses` to a list of IP addresses that have been previously flagged for unusual activity

flagged_addresses = ["192.168.190.178", "192.168.96.200", "192.168.174.117", "192.168.168.144"]

# Display the contents of `flagged_addresses`

print(flagged_addresses)

```

11. Finally, you will write an iterative statement that loops through the valid_ip_addresses list and checks if each IP address is flagged. In the following code, the address will be the loop variable. Also, include a conditional that checks if the address belongs to the flagged_addresses list. If so, it should display "The IP address ______ has been flagged for further analysis." If not, it should display "The IP address ______ does not require further analysis." Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

```py
import re

# Assign `log_file` to a string containing username, date, login time, and IP address for a series of login attempts 

log_file = "eraab 2022-05-10 6:03:41 192.168.152.148 \niuduike 2022-05-09 6:46:40 192.168.22.115 \nsmartell 2022-05-09 19:30:32 192.168.190.178 \narutley 2022-05-12 17:00:59 1923.1689.3.24 \nrjensen 2022-05-11 0:59:26 192.168.213.128 \naestrada 2022-05-09 19:28:12 1924.1680.27.57 \nasundara 2022-05-11 18:38:07 192.168.96.200 \ndkot 2022-05-12 10:52:00 1921.168.1283.75 \nabernard 2022-05-12 23:38:46 19245.168.2345.49 \ncjackson 2022-05-12 19:36:42 192.168.247.153 \njclark 2022-05-10 10:48:02 192.168.174.117 \nalevitsk 2022-05-08 12:09:10 192.16874.1390.176 \njrafael 2022-05-10 22:40:01 192.168.148.115 \nyappiah 2022-05-12 10:37:22 192.168.103.10654 \ndaquino 2022-05-08 7:02:35 192.168.168.144"

# Assign `pattern` to a regular expression that matches with all valid IP addresses and only those 

pattern = "\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}"

# Use `re.findall()` on `pattern` and `log_file` and assign `valid_ip_addresses` to the output 

valid_ip_addresses = re.findall(pattern, log_file)

# Assign `flagged_addresses` to a list of IP addresses that have been previously flagged for unusual activity

flagged_addresses = ["192.168.190.178", "192.168.96.200", "192.168.174.117", "192.168.168.144"]

# Iterative statement begins here
# Loop through `valid_ip_addresses` with `address` as the loop variable

for address in valid_ip_addresses:

    # Conditional begins here
    # If `address` belongs to `flagged_addresses`, display "The IP address ______ has been flagged for further analysis."

    if address in flagged_addresses:
        print("The IP address", address, "has been flagged for further analysis.")

    # Otherwise, display "The IP address ______ does not require further analysis."

    else:
        print("The IP address", address, "does not require further analysis.")

```

[Activities content](#activities-content)

[Content](#content)


### Activity: Import and parse a text file



1. In this task, you'll import a security log text file and store it as a string to prepare it for analysis. 

In Python, a `with` statement is often used in file handling to open a file and then automatically close the file after reading it.

You're given a variable named `import_file` that contains the name of the log file that you want to import. Start by writing the first line of the `with` statement in the following code cell. Use the `open()` function, setting the second parameter to `"r"`. Note that running this code will produce an error because it will only contain the first line of the `with` statement; you'll complete this `with` statement in the task after this. Be sure to replace the `### YOUR CODE HERE ###` with your own code.

```py
# Assign `import_file` to the name of the text file that contains the security log file

import_file = "login.txt"

# First line of the `with` statement
# Use `open()` to import security log file and store it as a string

with open(import_file, "r") as file:
```

2. Now, you'll use the `.read()` method to read the imported file, and you'll store the result in a variable named `text`. Afterwards, display the `text` and explore what it contains by running the cell. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.
```py
# Assign `import_file` to the name of the text file that contains the security log file

import_file = "login.txt"

# The `with` statement
# Use `open()` to import security log file and store it as a string

with open(import_file, "r") as file:

  # Use `.read()` to read the imported file and store the result in a variable named `text`

  text = file.read()

# Display the contents of `text`

print(text)
```

3. The output in the previous step is one big string. In this task, you'll explore how you can split the string that contains the entire imported log file into a list of strings, one string per line. 

Use the  `.split()` method to perform this split and then display the result. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell. 

Note that displaying `.split()` doesn’t change what is stored in the `text` variable. Variable reassignment would be necessary if you want to store the result after splitting.

```py
# Assign `import_file` to the name of the text file that contains the security log file

import_file = "login.txt"

# The `with` statement
# Use `open()` to import security log file and store it as a string

with open(import_file, "r") as file:

  # Use `.read()` to read the imported file and store the result in a variable named `text`

  text = file.read()

# Display the contents of `text` split into separate lines 

print(text.split())
```

4. IThere is a missing entry in the log file. You'll need to account for that by appending it to the log file. You're given the missing entry stored in a variable named `missing_entry`. 

Use the `.write()` method and the parameter `"a"` in the `open()` function. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

After the portion of the code that writes to the file, another with statement uses the `.read()` method to read the updated file into the `text` variable and then display it.
```py
# Assign `import_file` to the name of the text file that contains the security log file

import_file = "login.txt"

# Assign `missing entry` to a log that was not recorded in the log file

missing_entry = "jrafael,192.168.243.140,4:56:27,2022-05-09"

# Use `open()` to import security log file and store it as a string
# Pass in "a" as the second parameter to indicate that the file is being opened for appending purposes

with open(import_file,"a") as file:

    # Use `.write()` to append `missing_entry` to the log file

    file.write(missing_entry)

# Use `open()` with the parameter "r" to open the security log file for reading purposes

with open(import_file, "r") as file:

    # Use `.read()` to read in the contents of the log file and store in a variable named `text`

    text = file.read()

# Display the contents of `text`

print(text)
```
5. The next task you're responsible for is creating a text file. This text file should include a list of IP addresses that are allowed to access restricted information. Documenting this in a text file will help you communicate your findings to your security team. 

Start by creating a variable named `import_file` that stores the name of the file, which should be `"allow_list.txt"`. 

You're also given a variable named `ip_addresses` that stores a string containing the IP addresses that are allowed.

Run the code to display the two variables and explore what they contain. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell. 
```py
# Assign `import_file` to the name of the text file that you want to create

import_file = "allow_list.txt"

# Assign `ip_addresses` to a list of IP addresses that are allowed to access the restricted information

ip_addresses = "192.168.218.160 192.168.97.225 192.168.145.158 192.168.108.13 192.168.60.153 192.168.96.200 192.168.247.153 192.168.3.252 192.168.116.187 192.168.15.110 192.168.39.246"

# Display `import_file`

print(import_file)

# Display `ip_addresses`

print(ip_addresses)

```
6. Your next goal is to create a `with` statement in order to write the IP addresses to the text file you created in the previous step. 

You'll first open the file using the `"w"` parameter. Then, you'll write the IP addresses to the file. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell. Note that the code cell will contain a `with` statement that writes to a file but does not display information to the screen, so running it will not produce an output.
```py
# Assign `import_file` to the name of the text file that you want to create

import_file = "allow_list.txt"

# Assign `ip_addresses` to a list of IP addresses that are allowed to access the restricted information

ip_addresses = "192.168.218.160 192.168.97.225 192.168.145.158 192.168.108.13 192.168.60.153 192.168.96.200 192.168.247.153 192.168.3.252 192.168.116.187 192.168.15.110 192.168.39.246"

# Create a `with` statement to write to the text file 

with open(import_file, "w") as file:

  # Write `ip_addresses` to the text file

  file.write(ip_addresses)
```
7. In this final step, you'll complete the code you've been writing up to this point. You'll add code to read the file containing IP addresses.

Complete a `with` statement that reads the text file and stores it in a new variable called `text`. 

Afterwards, display the contents of `text` and run the cell to explore the result. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell. 
```py
# Assign `import_file` to the name of the text file that you want to create

import_file = "allow_list.txt"

# Assign `ip_addresses` to a list of IP addresses that are allowed to access the restricted information

ip_addresses = "192.168.218.160 192.168.97.225 192.168.145.158 192.168.108.13 192.168.60.153 192.168.96.200 192.168.247.153 192.168.3.252 192.168.116.187 192.168.15.110 192.168.39.246"

# Create a `with` statement to write to the text file 

with open(import_file, "w") as file:

    # Write `ip_addresses` to the text file

    file.write(ip_addresses)

# Create a `with` statement to read in the text file 

with open(import_file, "r") as file1:

    # Read the file and store the result in a variable named `text`

    text = file1.read()

# Display the contents of `text`

print(text)

```

```py
# Resets the `"login.txt"` file to its original contents
# Allows learners to complete lab more than once

# Assigns the original contents of the file to the `login_file` variable
login_file = """username,ip_address,time,date
tshah,192.168.92.147,15:26:08,2022-05-10
dtanaka,192.168.98.221,9:45:18,2022-05-09
tmitchel,192.168.110.131,14:13:41,2022-05-11
daquino,192.168.168.144,7:02:35,2022-05-08
eraab,192.168.170.243,1:45:14,2022-05-11
jlansky,192.168.238.42,1:07:11,2022-05-11
acook,192.168.52.90,9:56:48,2022-05-10
asundara,192.168.58.217,23:17:52,2022-05-12
jclark,192.168.214.49,20:49:00,2022-05-10
cjackson,192.168.247.153,19:36:42,2022-05-12
jclark,192.168.197.247,14:11:04,2022-05-12
apatel,192.168.46.207,17:39:42,2022-05-10
mabadi,192.168.96.244,10:24:43,2022-05-12
iuduike,192.168.131.147,17:50:00,2022-05-11
abellmas,192.168.60.111,13:37:05,2022-05-10
gesparza,192.168.148.80,6:30:14,2022-05-11
cgriffin,192.168.4.157,23:04:05,2022-05-09
alevitsk,192.168.210.228,8:10:43,2022-05-08
eraab,192.168.24.12,11:29:27,2022-05-11
jsoto,192.168.25.60,5:09:21,2022-05-09
"""

# Writes `login_file` to the `"login.txt"` file
with open("login.txt", "w") as file:
          file.write(login_file)

```

[Activities content](#activities-content)

[Content](#content)



### Activity: Create another algorithm


1. Your eventual goal is to develop an algorithm that parses a series of IP addresses that can access restricted information and removes the addresses that are no longer allowed. Python can automate this process.

You're given a text file called `"allow_list.txt"` that contains a series of IP addresses that are allowed to access restricted information. 

There are IP addresses that should no longer have access to this information, and their IP addresses need to be removed from the text file. You're given a variable named `remove_list` that contains the list of IP addresses to be removed.

Display both variables to explore their contents, and run the cell. Be sure to replace each `### YOUR CODE HERE ###` with your own code before running the following cell.

```py
# Assign `import_file` to the name of the file 

import_file = "allow_list.txt"

# Assign `remove_list` to a list of IP addresses that are no longer allowed to access restricted information. 

remove_list = ["192.168.97.225", "192.168.158.170", "192.168.201.40", "192.168.58.57"]

# Display `import_file`

print(import_file)

# Display `remove_list`

print(remove_list)
```


2. In this task, start by opening the text file using the `import_file` variable, the `with` keyword, and the `open()` function with the `"r"` parameter. Be sure to replace the `### YOUR CODE HERE ###` with your own code.

For now, you'll write the first line of the `with` statement. Running this code will produce an error because it will only contain the first line of the `with` statement; you'll complete this `with` statement in the task after this.

```py
# Assign `import_file` to the name of the file 

import_file = "allow_list.txt"

# Assign `remove_list` to a list of IP addresses that are no longer allowed to access restricted information. 

remove_list = ["192.168.97.225", "192.168.158.170", "192.168.201.40", "192.168.58.57"]

# First line of `with` statement

with open(import_file, "r") as file:
```


3. Now, use the `.read()` method to read the imported file in as a string and store it in a variable named `ip_addresses`. 

Afterwards, display `ip_addresses` to examine the data in its current format. 

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

```py
# Assign `import_file` to the name of the file 

import_file = "allow_list.txt"

# Assign `remove_list` to a list of IP addresses that are no longer allowed to access restricted information. 

remove_list = ["192.168.97.225", "192.168.158.170", "192.168.201.40", "192.168.58.57"]

# Build `with` statement to read in the initial contents of the file

with open(import_file, "r") as file:

  # Use `.read()` to read the imported file and store it in a variable named `ip_addresses`

  ip_addresses = file.read()

# Display `ip_addresses`

print(ip_addresses)
```

4. After reading the file, reassign the `ip_addresses` variable so its data type is updated from a string to a list. Use the `.split()` method to achieve this. Converting the string into a list will later allow you to remove individual IP addresses from the allow list.

Afterwards, display the `ip_addresses` variable to verify that the update took place.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

```py
# Assign `import_file` to the name of the file 

import_file = "allow_list.txt"

# Assign `remove_list` to a list of IP addresses that are no longer allowed to access restricted information. 

remove_list = ["192.168.97.225", "192.168.158.170", "192.168.201.40", "192.168.58.57"]

# Build `with` statement to read in the initial contents of the file

with open(import_file, "r") as file:

    # Use `.read()` to read the imported file and store it in a variable named `ip_addresses`

    ip_addresses = file.read()

# Use `.split()` to convert `ip_addresses` from a string to a list

ip_addresses = ip_addresses.split()

# Display `ip_addresses`

print(ip_addresses)
```

5. Now, you'll write code that removes the elements of `remove_list` from the `ip_addresses` list. This will require using an iterative statement.

First, build the iterative statement. Name the loop variable `element` and loop through `remove_list`. In the body of the loop, display each element. (Displaying each element is a temporary step for this task.) 

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

```py
# Assign `import_file` to the name of the file

import_file = "allow_list.txt"

# Assign `remove_list` to a list of IP addresses that are no longer allowed to access restricted information.

remove_list = ["192.168.97.225", "192.168.158.170", "192.168.201.40", "192.168.58.57"]

# Build `with` statement to read in the initial contents of the file

with open(import_file, "r") as file:

    # Use `.read()` to read the imported file and store it in a variable named `ip_addresses`

    ip_addresses = file.read()

# Use `.split()` to convert `ip_addresses` from a string to a list

ip_addresses = ip_addresses.split()

# Build iterative statement
# Name loop variable `element`
# Loop through `remove_list`

for element in remove_list:

  # Display `element` in every iteration

   print(element)
```

6. Now, you will update the body of the loop with code that will remove IP addresses from the allow list.

First, a conditional statement is used to evaluate if the loop variable `element` is part of the `ip_addresses` list. This is important to avoid the errors that would occur when using the `.remove()` method if an `element` was not part of the `ip_addresses` list. 

Then, within the conditional, apply the `.remove()` method to the `ip_addresses` list and remove the IP addresses identified in the loop variable `element`.

After the iterative statement removes  the elements, display the updated `ip_addresses` list to verify that the elements of `remove_list` are no longer in the `ip_addresses`. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

**Note:** There are not any duplicate values in the `ip_addresses` list. The `.remove()` method only removes the first occurrence of an element, so if there were duplicates, they would not be removed.

```py
# Assign `import_file` to the name of the file

import_file = "allow_list.txt"

# Assign `remove_list` to a list of IP addresses that are no longer allowed to access restricted information.

remove_list = ["192.168.97.225", "192.168.158.170", "192.168.201.40", "192.168.58.57"]

# Build `with` statement to read in the initial contents of the file

with open(import_file, "r") as file:

    # Use `.read()` to read the imported file and store it in a variable named `ip_addresses`

    ip_addresses = file.read()

# Use `.split()` to convert `ip_addresses` from a string to a list

ip_addresses = ip_addresses.split()

# Build iterative statement
# Name loop variable `element`
# Loop through `remove_list`

for element in remove_list:
    
    # Create conditional statement to evaluate if `element` is in `ip_addresses`

    if element in ip_addresses:

        # use the `.remove()` method to remove
        # elements from `ip_addresses`

        ip_addresses.remove(element)

# Display `ip_addresses`

print(ip_addresses)
```


7. The next step is to update the original file that was used to create the `ip_addresses` list. A line of code containing the `.join()` method has been added to the code so that the file can be updated. This is necessary because `ip_addresses` must be in string format when used inside the `with` statement to rewrite the file. The `.join()` method takes in an iterable (such as a list) and concatenates every element of it into a string. 

The `.join()` method is applied to a string consisting of the character that will be used to separate every element in the iterable once its converted into a string. In the code below, the method is applied to the string `"\n"`. The `"\n"` character indicates to separate each element by placing it on a new line. The argument of the `.join()` method is the iterable you want to convert, and in this case, that's `ip_addresses`. As a result, it converts `ip_addresses` from a list back into a string with each IP address on a new line.

After this line with the `.join()` method, build the `with` statement that rewrites the original file. Use the `"w"` parameter when calling the `open()` function to delete the contents in the original file and replace it with what you want to write. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell. This code cell will not produce an output.
```py
# Assign `import_file` to the name of the file

import_file = "allow_list.txt"

# Assign `remove_list` to a list of IP addresses that are no longer allowed to access restricted information.

remove_list = ["192.168.97.225", "192.168.158.170", "192.168.201.40", "192.168.58.57"]

# Build `with` statement to read in the initial contents of the file

with open(import_file, "r") as file:

    # Use `.read()` to read the imported file and store it in a variable named `ip_addresses`

    ip_addresses = file.read()

# Use `.split()` to convert `ip_addresses` from a string to a list

ip_addresses = ip_addresses.split()

# Build iterative statement
# Name loop variable `element`
# Loop through `remove_list`

for element in remove_list:
    
    # Create conditional statement to evaluate if `element` is in `ip_addresses`

    if element in ip_addresses:

        # use the `.remove()` method to remove
        # elements from `ip_addresses`

        ip_addresses.remove(element)

# Convert `ip_addresses` back to a string so that it can be written into the text file

ip_addresses = "\n".join(ip_addresses)

# Build `with` statement to rewrite the original file

with open(import_file, "w") as file1:

  # Rewrite the file, replacing its contents with `ip_addresses`

  file1.write(ip_addresses)
```

8. In this task, you'll verify that the original file was rewritten using the correct list. 

Write another `with` statement, this time to read in the updated file. Start by opening the file. Then read the file and store its contents in the `text` variable. 

Afterwards, display the `text` variable to examine the result.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.
```py
# Assign `import_file` to the name of the file

import_file = "allow_list.txt"

# Assign `remove_list` to a list of IP addresses that are no longer allowed to access restricted information.

remove_list = ["192.168.97.225", "192.168.158.170", "192.168.201.40", "192.168.58.57"]

# Build `with` statement to read in the initial contents of the file

with open(import_file, "r") as file:

  # Use `.read()` to read the imported file and store it in a variable named `ip_addresses`

  ip_addresses = file.read()

# Use `.split()` to convert `ip_addresses` from a string to a list

ip_addresses = ip_addresses.split()

# Build iterative statement
# Name loop variable `element`
# Loop through `remove_list`

for element in remove_list:
    
    # Create conditional statement to evaluate if `element` is in `ip_addresses`

    if element in ip_addresses:

        # use the `.remove()` method to remove
        # elements from `ip_addresses`

        ip_addresses.remove(element)

# Convert `ip_addresses` back to a string so that it can be written into the text file

ip_addresses = "\n".join(ip_addresses)

# Build `with` statement to rewrite the original file

with open(import_file, "w") as file:

  # Rewrite the file, replacing its contents with `ip_addresses`

  file.write(ip_addresses)

# Build `with` statement to read in the updated file

with open(import_file, "r") as file:

    # Read in the updated file and store the contents in `text`

    text = file.read()

# Display the contents of `text`

print(text)
```

9. The next step is to bring all of the code you've written leading up to this point and put it all into one function. 

Define a function named `update_file()` that takes in two parameters. The first parameter is the name of the text file that contains IP addresses (call this parameter `import_file`). The second parameter is a list that contains IP addresses to be removed (call this parameter `remove_list`).

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell. Note that this code cell will not produce an output.

```py
# Define a function named `update_file` that takes in two parameters: `import_file` and `remove_list`
# and combines the steps you've written in this lab leading up to this

def update_file(import_file, remove_list):

    # Build `with` statement to read in the initial contents of the file

    with open(import_file, "r") as file:

        # Use `.read()` to read the imported file and store it in a variable named `ip_addresses`

        ip_addresses = file.read()

    # Use `.split()` to convert `ip_addresses` from a string to a list

    ip_addresses = ip_addresses.split()

    # Build iterative statement
    # Name loop variable `element`
    # Loop through `remove_list`

    for element in remove_list:
    
        # Create conditional statement to evaluate if `element` is in `ip_addresses`

        if element in ip_addresses:

            # use the `.remove()` method to remove
            # elements from `ip_addresses`

            ip_addresses.remove(element)

    # Convert `ip_addresses` back to a string so that it can be written into the text file

    ip_addresses = "\n".join(ip_addresses)

    # Build `with` statement to rewrite the original file

    with open(import_file, "w") as file:

        # Rewrite the file, replacing its contents with `ip_addresses`

        file.write(ip_addresses)
```

10. Finally, call the `update_file()` that you defined. Apply the function to `"allow_list.txt"` and pass in a list of IP addresses as the second argument.

Use the following list of IP addresses as the second argument: 

`["192.168.25.60", "192.168.90.124", "192.168.60.153"]`

After the function call, use a `with` statement to read the contents of the allow list. Then display the contents of the allow list. Run it to verify that the file has been updated by the function.

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.
```py
# Define a function named `update_file` that takes in two parameters: `import_file` and `remove_list`
# and combines the steps you've written in this lab leading up to this

def update_file(import_file, remove_list):

    # Build `with` statement to read in the initial contents of the file

    with open(import_file, "r") as file:

        # Use `.read()` to read the imported file and store it in a variable named `ip_addresses`

        ip_addresses = file.read()

    # Use `.split()` to convert `ip_addresses` from a string to a list

    ip_addresses = ip_addresses.split()

    # Build iterative statement
    # Name loop variable `element`
    # Loop through `remove_list`

    for element in remove_list:
    
        # Create conditional statement to evaluate if `element` is in `ip_addresses`

        if element in ip_addresses:

            # use the `.remove()` method to remove
            # elements from `ip_addresses`

            ip_addresses.remove(element)

    # Convert `ip_addresses` back to a string so that it can be written into the text file

    ip_addresses = "\n".join(ip_addresses)

    # Build `with` statement to rewrite the original file

    with open(import_file, "w") as file:

        # Rewrite the file, replacing its contents with `ip_addresses`

        file.write(ip_addresses)

# Call `update_file()` and pass in "allow_list.txt" and a list of IP addresses to be removed

update_file("allow_list.txt",ip_addresses)

# Build `with` statement to read in the updated file

with open("allow_list.txt", "r") as file:

    # Read in the updated file and store the contents in `text`

    text = file.read()

# Display the contents of `text`

print(text)
```

11. final

```py
# Resets the `"allow_list.txt"` file to its original contents
# Allows learners to complete lab more than once

# Assigns the original list of IP addresses to the `ip_addresses` variable

ip_addresses = """ip address
192.168.25.60
192.168.205.12
192.168.97.225
192.168.6.9
192.168.52.90
192.168.158.170
192.168.90.124
192.168.186.176
192.168.133.188
192.168.203.198
192.168.201.40
192.168.218.219
192.168.52.37
192.168.156.224
192.168.60.153
192.168.58.57
192.168.69.116
"""

# Writes `ip_addresses` to the `"allow_list.txt"` file

with open("allow_list.txt", "w") as file:
          file.write(ip_addresses)
```


[Activities content](#activities-content)

[Content](#content)

### Activity: Update a file through a Python algorithm


#### Scenario

Review the following scenario. Then complete the step-by-step instructions.
You are a security professional working at a health care company. As part of your job, you're required to regularly update a file that identifies the employees who can access restricted content. The contents of the file are based on who is working with personal patient records. Employees are restricted access based on their IP address. There is an allow list for IP addresses permitted to sign into the restricted subnetwork. There's also a remove list that identifies which employees you must remove from this allow list.
Your task is to create an algorithm that uses Python code to check whether the allow list contains any IP addresses identified on the remove list. If so, you should remove those IP addresses from the file containing the allow list.
Note: This scenario involves developing the same algorithm that is developed in Tasks 2-7 of the Create another algorithm lab. (You do not need to reference Task 1 and Tasks 8-10 of the lab to complete this portfolio activity.) You should revisit the lab to get screenshots to include in your portfolio document. 


1. template
Algorithm for file updates in Python

Project description
[Describe the scenario in your own words.]
Open the file that contains the allow list
[Add content here.]
Read the file contents
[Add content here.]
Convert the string into a list
[Add content here.]
Iterate through the remove list
[Add content here.]
Remove IP addresses that are on the remove list
[Add content here.]
Update the file with the revised list of IP addresses
[Add content here.]
Summary
[Add content here.]

2. Access supporting materials
The following supporting material will help you complete this activity. The document Instructions for including Python code provides instructions and best practices for including samples of Python code in your portfolio activity. Keep it open as you proceed to the next steps. 

Instructions for including Python code
It’s strongly recommended that you return to the Create another algorithm lab to include
screenshots of your Python code. If this isn’t possible, you can also type your commands in
this document.
When including samples of Python code, consider the following:
● There are multiple applications that can be used to take screenshots. If you’re unsure
how to take a screenshot on your device, you can perform an online search such as
“how to take a screenshot in [your operating system].” Replace “[your operating
system]” with the operating system your computer uses.
● Do not include screenshots of the directions that are found in markdown cells. Only
include screenshots of the code cells.
● If you type your code, highlight it in gray and use a monospaced font, such as in this
example: ip_addresses = ip_addresses.split()

3. Open the file that contains the allow list
The file that you want to open is called "allow_list.txt". Assign a string containing this file name to the import_file variable. Then, use a with statement to open it. Use the variable file to store the file while you work with it inside the with statement.
Describe the Python syntax, functions, and keywords you need to accomplish this in the Open the file that contains the allow list section of the Algorithm for file updates in Python template. In the Task 2 section of Create another algorithm lab, take a screenshot of this portion of your code. Or, type this code directly into the template.

4. Read the file contents
Next, use the .read() method to convert the contents of the allow list file into a string so that you can read them. Store this string in a variable called ip_addresses.
Describe the Python syntax, functions, and keywords you need to accomplish this in the Read the file contents section of the Algorithm for file updates in Python template. In the Task 3 section of the Create another algorithm lab, take a screenshot of this portion of your code. Or, type this code directly into the template.

5. Convert the string into a list
In order to remove individual IP addresses from the allow list, the IP addresses need to be in a list format. Therefore, use the .split() method to convert the ip_addresses string into a list.
Describe the Python syntax, functions, and keywords you need to accomplish this in the Convert the string into a list section of the Algorithm for file updates in Python template. In the Task 4 section of the Create another algorithm lab, take a screenshot of this portion of your code. Or, type this code directly into the template.

6. Iterate through the remove list
A second list called remove_list contains all of the IP addresses that should be removed from the ip_addresses list. Set up the header of a for loop that will iterate through the remove_list. Use element as the loop variable.
Describe the Python syntax, functions, and keywords you need to accomplish this in the Iterate through the remove list section of the Algorithm for file updates in Python template. In the Task 5 section of the Create another algorithm lab, take a screenshot of this portion of your code. Or, type this code directly into the template.

7. Remove IP addresses that are on the remove list
In the body of your iterative statement, add code that will remove all the IP addresses from the allow list that are also on the remove list. First, create a conditional that evaluates if the loop variable element is part of the ip_addresses list. Then, within that conditional, apply the .remove() method to the ip_addresses list and remove the IP addresses identified in the loop variable element. 
Describe the Python syntax, functions, and keywords you need to accomplish this in the Remove IP addresses that are on the remove list section of the Algorithm for file updates in Python template. In the Task 6 section of the Create another algorithm lab, take a screenshot of this portion of your code. Or, type this code directly into the template.
In addition, include a sentence that explains that applying the .remove() method in this way is possible because there are no duplicates in the ip_addresses list. 

8. Update the file with the revised list of IP addresses
Now that you have removed these IP addresses from the ip_address variable, you can complete the algorithm by updating the file with this revised list. To do this, you must first convert the ip_addresses list back into a string using the .join() method. Apply .join() to the string "\n" in order to separate the elements in the file by placing them on a new line.
Then, use another with statement and the .write() method to write over the file assigned to the import_file variable.
Describe the Python syntax, functions, and keywords you need to accomplish this in the Update the file with the revised list of IP addresses section of the Algorithm for file updates in Python template. In the Task 7 section of the Create another algorithm lab, take a screenshot of this portion of your code. Or, type this code directly into the template.

9. Finalize your document
To finalize the document and make its purpose clear to potential employers, be sure to complete the Project description and Summary sections of the Algorithm for file updates in Python template. 
In the Project description section, give a general overview of the scenario and what you accomplished in Python. Write three to five sentences.
In the Summary section, provide a short summary of the algorithm by highlighting its main components. Write four to six sentences.

#### Completed

Update a file through a Python algorithm
Project description
At my organization, access to restricted content is controlled with an allow list of IP addresses. The "allow_list.txt" file identifies these IP addresses. A separate remove list identifies IP addresses that should no longer have access to this content. I created an algorithm to automate updating the "allow_list.txt" file and remove these IP addresses that should no longer have access. 
Open the file that contains the allow list
For the first part of the algorithm, I opened the "allow_list.txt" file. First, I assigned this file name as a string to the import_file variable:
```py
# assign `import_file` to the name of the file
import_file = "allow_list.txt"
```

Then, I used a with statement to open the file:
```py
# build `with` statement to read in the initial contents of the file
with open(import_file, "r") as file:
```

In my algorithm, the with statement is used with the .open() function in read mode to open the allow list file for the purpose of reading it. The purpose of opening the file is to allow me to access the IP addresses stored in the allow list file. The with keyword will help manage the resources by closing the file after exiting the with statement. In the code with open(import_file, "r") as file:, the open() function has two parameters. The first identifies the file to import, and then the second indicates what I want to do with the file. In this case, "r" indicates that I want to read it. The code also uses the as keyword to assign a variable named file; file stores the output of the .open() function while I work within the with statement.

Read the file contents
In order to read the file contents, I used the .read() method to convert it into the string.
```py
with open(import_file, "r") as file:
# use `.read()` to read the imported file and store it in a variable named `ip_addresses`
ip_addresses = file.rad()
```


When using an .open() function that includes the argument "r" for “read,” I can call the .read() function in the body of the with statement. The .read() method converts the file into a string and allows me to read it. I applied the .read() method to the file variable identified in the with statement. Then, I assigned the string output of this method to the variable ip_addresses. 

In summary, this code reads the contents of the "allow_list.txt" file into a string format that allows me to later use the string to organize and extract data in my Python program.
Convert the string into a list
In order to remove individual IP addresses from the allow list, I needed it to be in list format. Therefore, I next used the .split() method to convert the ip_addresses string into a list:

```py
# use `.split()` to convert `ip_addresses` from a string to a list
ip_addresses = ip_addresses.split()
```

The .split() function is called by appending it to a string variable. It works by converting the contents of a string to a list. The purpose of splitting ip_addresses into a list is to make it easier to remove IP addresses from the allow list. By default, the .split() function splits the text by whitespace into list elements. In this algorithm, the .split() function takes the data stored in the variable ip_addresses, which is a string of IP addresses that are each separated by a whitespace, and it converts this string into a list of IP addresses. To store this list, I reassigned it back to the variable ip_addresses. 
Iterate through the remove list
A key part of my algorithm involves iterating through the IP addresses that are elements in the remove_list. To do this, I incorporated a for loop:

```py
# build iterative statement
# name loop variable `element`
# loop through `remove_list`
for element in remove_list:
```

The for loop in Python repeats code for a specified sequence. The overall purpose of the for loop in a Python algorithm like this is to apply specific code statements to all elements in a sequence. The for keyword starts the for loop. It is followed by the loop variable element and the keyword in. The keyword in indicates to iterate through the sequence ip_addresses and assign each value to the loop variable element. 

Remove IP addresses that are on the remove list
My algorithm requires removing any IP address from the allow list, ip_addresses, that is also contained in remove_list.  Because there were not any duplicates in ip_addresses, I was able to use the following code to do this:

```py
for element in remove_list:
    if element in ip_addresses:
        ip_addresses.remove(element)
```


First, within my for loop, I created a conditional that evaluated whether or not the loop variable element was found in the ip_addresses list. I did this because applying .remove() to elements that were not found in ip_addresses would result in an error. 

Then, within that conditional, I applied .remove() to ip_addresses. I passed in the loop variable element as the argument so that each IP address that was in the remove_list would be removed from ip_addresses.




Update the file with the revised list of IP addresses 
As a final step in my algorithm, I needed to update the allow list file with the revised list of IP addresses. To do so, I first needed to convert the list back into a string. I used the .join() method for this:
```py
ip_addresses = "\n".join(ip_addresses)
```


The .join() method combines all items in an iterable into a string. The .join() method is applied to a string containing characters that will separate the elements in the iterable once joined into a string. In this algorithm, I used the .join() method to create a string from the list ip_addresses so that I could pass it in as an argument to the .write() method when writing to the file "allow_list.txt". I used the string ("\n") as the separator to instruct Python to place each element on a new line. 

Then, I used another with statement and the .write() method to update the file:
```py
with open(import_file, "w") as file:
  file.write(ip_addresses)
```


This time, I used a second argument of "w" with the open() function in my with statement. This argument indicates that I want to open a file to write over its contents. When using this argument "w", I can call the .write() function in the body of the with statement. The .write() function writes string data to a specified file and replaces any existing file content. 
In this case I wanted to write the updated allow list as a string to the file "allow_list.txt". This way, the restricted content will no longer be accessible to any IP addresses that were removed from the allow list. To rewrite the file, I appended the .write() function to the file object file that I identified in the with statement. I passed in the ip_addresses variable as the argument to specify that the contents of the file specified in the with statement should be replaced with the data in this variable.

Summary
I created an algorithm that removes IP addresses identified in a remove_list variable from the "allow_list.txt" file of approved IP addresses. This algorithm involved opening the file, converting it to a string to be read, and then converting this string to a list stored in the variable ip_addresses. I then iterated through the IP addresses in remove_list. With each iteration, I evaluated if the element was part of the ip_addresses list. If it was, I applied the .remove() method to it to remove the element from ip_addresses.. After this, I used the .join() method to convert the ip_addresses back into a string so that I could write over the contents of the "allow_list.txt" file with the revised list of IP addresses.

[Activities content](#activities-content)

[Content](#content)


### Activity: Debug Python code

1. The following code cell contains a syntax error. In this task, you'll run the code, identify why the error is occuring, and modify the code to resolve it. (To ensure that it has been resolved, run the code again to check if it now functions properly.)
```py
# For loop that iterates over a range of numbers
# and displays a message each iteration

for i in range(10):
    print("Connection cannot be established")
```

2. In the following code cell, you're provided a list of usernames. There is an issue with the syntax. In this task, you'll run the cell, observe what happens, and modify the code to fix the issue.
```py
# Assign `usernames_list` to a list of usernames

usernames_list = ["djames", "jpark", "tbailey", "zdutchma", "esmith", "srobinso", "dcoleman", "fbautist"]

# Display `usernames_list`

print(usernames_list)
```

3. In the following code cell, there is a syntax error. Your task is to run the cell, identify what is causing the error, and fix it.
```py
# Display a message in upper case 

print("update needed".upper())
```

4. In the following code cell, you're provided a `usernames_list`, a `username`, and code that determines whether the username is approved. There are two syntax errors and one exception. Your task is to find them and fix the code. A helpful debugging strategy is to focus on one error at a time and run the code after fixing each one.
```py
# Assign `usernames_list` to a list of usernames that represent approved users

usernames_list = ["djames", "jpark", "tbailey", "zdutchma", "esmith", "srobinso", "dcoleman", "fbautist"]

# Assign `username` to a specific username 

username = "esmith"

# For loop that iterates over the elements of `usernames_list` and determines whether each element corresponds to an approved user

for name in usernames_list:

    # Check if `name` matches `username` 
    # If it does match, then display a message accordingly 

    if name == username:
        print("The user is an approved user")
```

5. In this task, you'll examine the following code and identify the type of error that occurs. Then, you'll adjust the code to fix the error.
```py
# Assign `usernames_list` to a list of usernames

usernames_list = ["elarson", "bmoreno", "tshah", "sgilmore", "eraab"]

# Assign `username` to a specific username

username = "eraab"

# Determine whether `username` is the final username in `usernames_list` 
# If it is, then display a message accordingly 

if username == usernames_list[4]:
    print("This username is the final one in the list.")
```

6. In this task, you'll examine the following code. The code imports a text file into Python, reads its contents, and stores the contents as a list in a variable named `ip_addresses`. It then removes elements from `ip_addresses` if they are in `remove_list`. There are two errors in the code: first a syntax error and then an exception related to a string method. Your goal is to find these errors and fix them.
```py
# Assign `import_file` to the name of the text file

import_file = "allow_list.txt"

# Assign `remove_list` to a list of IP addressess that are no longer allowed to access the network 

remove_list = ["192.168.97.225", "192.168.158.170", "192.168.201.40", "192.168.58.57"]

# With statement that reads in the text file and stores its contents as a list in `ip_addresses` 

with open(import_file, "r") as file:
    ip_addresses = file.read()

# Convert `ip_addresses` from a string to a list

ip_addresses = ip_addresses.split()

# For loop that iterates over the elements in `remove_list`,
# checks if each element is in `ip_addresses`,
# and removes each element that corresponds to an IP address that is no longer allowed

for element in remove_list:
    if element in ip_addresses:
        ip_addresses.remove(element)

# Display `ip_addresses` after the removal process

print(ip_addresses)
```

7. In this final task, there are three operating systems: OS 1, OS 2, and OS 3. Each operating system needs a security patch by a specific date. The patch date for OS 1 is `"March 1st"`, the patch date for OS 2 is `"April 1st"`, and the patch date for OS 3 is `"May 1st"`. 

The following code stores one of these operating systems in a variable named `system`. Then, it uses conditionals to output the patch date for this operating system. 

However, this code has logic errors. Your goal is to assign the `system` variable to different values, run the code to examine the output, identify the error, and fix it.
```py
# Assign `system` to a specific operating system as a string

system = "OS 2"

# Assign `patch_schedule` to a list of patch dates in order of operating system

patch_schedule = ["March 1st", "April 1st", "May 1st"]

# Conditional statement that checks which operating system is stored in `system` and displays a message showing the corresponding patch date 

if system == "OS 1":
    print("Patch date:", patch_schedule[0])

elif system == "OS 2":
    print("Patch date:", patch_schedule[1])

elif system == "OS 3":
    print("Patch date:", patch_schedule[2])
```

[Activities content](#activities-content)

[Content](#content)

