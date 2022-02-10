# FortranBasedLanguage-Parser

Project for the course Programming Language Concepts. 
The programming language that I used is C++.
Here below I will describe the syntax of the simple fortran-based language my program will accept.

## Start and End the Program
The code has to start with the keyword `PROGRAM`, and then followed by the name of your program.
The end of your program has to end with the keywords `END PROGRAM` followed by the name of the program.
- the program name has to match.
Here below an example:
```
PROGRAM circle
...*some code*...
END PROGRAM circle
```

## Variables
In order to assign variables, you would have to declare it first using one of the keywords: `INTEGER`, `REAL`,`CHAR` followed by a colon, 
and then by the variable name. If the variable is declared with the keyword `INTEGER` the variable has to be an integer, `REAL` for real numbers, and `CHAR` for characters or strings. 
- Valid identifiers are alphanumeric but can contain underscores, and must begin with a letter.
Here below an example:
```
INTEGER : i
i = 10
REAL : r
r = 3.14
CHAR : str1
str1 = "hi"
```

## Print statements
To print you will have to use the keyword `PRINT` followed by a comma. 
- if `PRINT` expects a String expression it has to be between `""`
Here below an example:
```
PRINT , "Hello World"
CHAR : str1
str1 = "Hello World 2"
PRINT , str1
```

## If Statements
The syntax for if statements is with the keyword `IF` followed by a boolean expression and a `THEN` keyword. To end the if stamement 
it has to end with the keywords `END IF`.
Here below an example:
```
IF ( r == 5) THEN
PRINT , "Hello World"
END IF
```

Check the test cases folder to see which sample program would compile and which ones would not.
