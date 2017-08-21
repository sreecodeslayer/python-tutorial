# Python, and it's awesomeness!

![Python](images/python.png)

---

# SREENADH TC

Software Engineer @ Hashwave Technologies Inc.

@sreecodeslayer in GitHub

@imsreenadh in Twitter

Shoot mails to kesav.tc8@gmail.com

---
# Hashwave Technologies Inc.

*There is nothing better than clean data*

---

# Why I love Python

- General purpose | 
- Interactive |
- HIGH Level |
- Simple learning curve | 
- Easy maintainence |
- Scalable and Portable |
- Readability | 
- Extensive open-source community |
- Major Scientific/AI/Machine learning/Data related application | 

---

# What you will need to learn

- Desire |
- Text editor |
- Basic bash commands |

---

# What we will learn in two days

+++

## Almost everything:  
- Includes: |
	- Syntax | 
	- Variable Types | 
	- Conditions/Decisions | 
	- Loops | 
	- Datastructures | 
		- List | 
		- Set | 
		- Dictionaries | 
		- Tuples |
	- Functions
	- Module and importing |
	- Classes and Objects (Basics) |
	- Files and I/O |

---

# Where to run the code?

+++

## There are two simple ways:
- Interactive Mode Programming (Python Shell) |  
- Script Mode Programming (Python Code Files) |  

---

# Syntax [The Rules]

+++

# Identifiers and Reserved Words

+++

## Identifiers:
- identify a variable, function, class, module or other object |  
- follows some naming conventions |  

+++

## Reserved Words:

- and
- exec
- not
- assert
- finally
- or
- break
- for
- pass
- class

+++

- from
- print
- continue
- global
- raise
- def
- if
- elif
- else
- return
- del

+++

- import
- try
- except
- in
- is
- while
- with
- yield
- lambda

+++

## Comments and Documentation:

+++

Single line comments

```python
# This is a python single line comment, usually used to give short description of the code below or above
```

+++

## Multiline Comments/Description :

+++

Multiline comments

```python
'''
This is a multiline comment.
This is intended mainly for longer description of modules, documentation strings, class, object entity desciprion.
You can add as many lines as you want.
Python interpreter doesn't care to read this part.
'''
```

---

# Variable Types

+++

## Variables:
- reserved memory locations to store values |
- the amount of memory allocated depends on the variable type |

+++

## Types:
- Numbers |
- Strings |
- List |
- Tuple |
- Dictionaries |

+++

## Numbers:

```python
number1 = 1
number2 = 2.5

print "Number 1: ", number1, "Type: ", type(number1)
print "Number 2: ", number2, "Type: ", type(number2)

del number1
```
@[1](Define an integer, type: INT)
@[2](Define a floating point real value, type : FLOAT)

@[4](Print out the value and type of number1)
@[5](Print out the value and type of number2)

@[7](Delete the variable and release allocated memory for the variable: number1)

+++

## Strings:

```python
#!/usr/bin/python

str = 'Hello World!'

print str
print str[0]
print str[2:5]
print str[2:]
print str[:-1]
print str * 2
print str + "TEST"
```

@[5](Prints complete string)
@[6](Prints first character of the string)
@[7](Prints characters starting from 3rd to the nth, ie. 5th here)
@[8](Prints string starting from 3rd character to the last)
@[9](Prints string starting from last character, ie. Reverse of string)
@[10](Prints string two times)
@[11](Prints concatenated string, types should match. ',' can be used to print out diff. typed variables if any)

+++

### Let's look at some basic string operations

```python
#!/usr/bin/python

str1 = 'Hello World!'
str2 = 'Hope you are on your way to become a python expert'

# Length of strings
print "Length of str1 : ",len(str1)
print "Length of str2 : ",len(str2)

# Counting occurences
print "Number of times 'a' and 'e' occur in str2 : \n",\
"a: ",str2.count('a'),"\ne: ",str2.count('e')

# Concatenation
print str1+str2
print str1,str2

# Case based operation
print str1.upper()
print str1.lower()

print str1.islower()
print str1.isupper()

print str1.lower().islower()


# Starting and Ending of string validation
print str1.startswith('Hello')
print str1.startswith('Hel')
print str1.startswith('hel')

print str2.endswith('ex')
print str2.endswith('rt')
print str2.endswith('Expert')

# Splitting string based on a character or their combination
print str2.split(" ")
print str2.split("your way")
```
@[3-4](Initialize the sample strings)
@[6-8](len operation, finding length of a string)
@[10-12](Occurence counting of certain character inside the string)
@[14-16](Couple several string together to form a single long string)
@[18-25](String based operations, conversion, verifying)
@[28-35](Checking how a string starts and ends.)
@[37-39](Splitting string based on a specific character or sub-string)

+++

