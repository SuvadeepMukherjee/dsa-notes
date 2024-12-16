## Hello World

#### Comments 

Python interprets anything after a # as a comment 

#### Print 

The print() function is used to tell a computer to talk .The message to be printed should be surrounded by quotes

```python
print("There is something at work in my soul, which I do not understand.")
```

#### String 

In python a string is either surrounded by double quotes ("Hello World") or ('Hello World')

#### Variables

In python we assign variables by using the equals sign . Variables cant have spaces or symbols in their names othen than an underscore(_) . They cant begin with numbers but they can have numbers after the first letter

#### Errors

Two common errors that we encounter while writing python are SyntaxError and NameError 

- Syntax Error means there is something wrong with the way our program is written- punctuation that does not belong , a command where it is not expected or a missing parethesis can all trigger a syntax error
- Name Error - a name error occurs when the python interpreter sees a word it does not recognize.Code that contains something that looks like a variable but was never identified will throw a namerror

#### Numbers 

-  An integer or integer is a whole number 
- A floating-point number or a float is a decimal point number
- Numbers can be assigned to variables or used literally in a program

```python
an_int=2

a_float = 2.1

print(an_int + 3)
```

- We call the number 3 here a literal , meaning its actually the number 3 and not a variable with the number 3 assigned to it

#### Calculations 

- Python performs the arithmatic operations of addition, substarction , multiplication and division with +,-,* and /
- When we perform division the result has a decimal place .This is because Python converts all int's to float's before performing division 
- Division can throw its own special error : ZeroDivsionError . Python will raise this error when attempting to divide by 0 
- Mathematical operations in Python follow the standard mathematical order of operations

#### Changing Numbers 

- Performing arithmetic on variables does not change the variable - we can only update a variable using the = sign

#### Exponention

We perform exponention on python using the notation ** 

#### Modulo 

The modulo operator is indicated by % and gives the remainder of a division calculation

#### Concatenation 

- The + operator doesnt just add numbers , it can also add 2 strings .The process of combining 2 strings is called string concatenation. Performing String concatenation creates a brand new string comprised of first strings content followed by second strings contents 
- If we want to concatenate a string with a number we will need to make the number a string using the str() function . If we are trying to print() a numeric variable we can use commas to pass it as a different argument rather than converting it to a string  

#### Plus Equals 

- When we have a number saved in a variable and want to add to the current value of the variable we can use the += (plus-equals) operator 
- The plus-equals operator also can be used for string concatenation

#### Multi-line Strings 

- By using the quote -marks (''' or """) instead of one, we tell the program that the string does not end until the next triple quote

#### User Input 

- While we output a variables value using print() , we assign information to a variable using input() .The input() function requires a prompt message , which it will print out for the user before they enter the new information

```python
likes_snakes = input("Do you like snakes ? ")
```

