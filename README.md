# Data Structure And Algorithms using Python 

Python is one of the most popular programming language. It is a high-level, easy to learn interpreted programming language. It was developed by Guido Van Rossum in 1991. Today python is used in many different types of purposes like software development, data analysis, machine learning, robotics, backend web development, desktop application, GUIs, 2d game development etc. So here in this repositery I am adding Data Structure and Algorightm concepts and problems and their solution.

## Data Types in Python

In programming we need to classify the data or value so that we can perform different operations on different data types 
for example: The "+" operator will add two values if they are integer or #float while the same operator will concatenate two strings 
So we can see that the same operator operate different types of values differently based on its data type, hence the classinfying the values with different data types is very important

### Data types available in Python 

(i)  **Integer**
  -> In Python we represent whole numbers using int (integer). In integers numbers can lie anywhere from negative infinity to positive infinity which make it                convinient for us to deal with integers without caring much about the memory size it will take because Python will handle it automatically.
     
     x = 4
     
     print(type(x))
     
     output >>  <class "int">
  
  
  
(ii)  **Float**
  -> In Python to represent a real number having decimal point we use float.It represent both rational and irrational numbers. There can be any number of digits before        or after the decimal point.
     
     x = 4.0
     
     print(type(x))
     
     output >>  <class "float">



(iii)  **Complex Numbers**
   -> In Python we can also work with complex number where we represent imaginary number. For example a + bj is a complex number where a and b are real numbers and j         is an imaginary number.
      
      x = 2 + 3j
      
      print(type(x))
      
      output >> <class "complex">



(iv) **String**
   -> String values are the combination of letters, charecters, numbers and special charecters inside the single, double or even tripple quotation mark. Most of the 
      time we use single and double quotation marks for single line strings and while we want to write multi-line string we use tripple quotation mark.
      
      x = "Hello World"
      
      print(type(x))
      
      output >> <class 'str'>
 
 
 
(v)  **Boolean**
   -> Boolean has only two values True (T is always capital) and False (F is always capital). We use boolean data type when we have to make decision or write                 conditional statements. We can also represent boolean values by using number such as 1 for True and 0 for False.
      
      x = True
      
      print(type(x))
      
      output >> <class 'bool'>
 
 
 
(vi)  **None**
   -> Suppose a situation where you have to declare a variable without initializing tha variable then there comes nonetype to save you . It is use to declare a 
      variable with any initial value.
      
      x = None
      
      print(type(x))
      
      output >> <class 'NoneType'>


## Operators in Programming Languages

Operators are one of the most important thing in computer programming languages with which we can perform operations with different data types. In programming we need to perform so many operations to give instructions to computers like calculations, concatinations, etc. 


**Note ->**  An expression is a statement in computer science in which the combination of number of variables, constant values, operators and functions put together to
             get value of any data type 

### Types of operators available in Python 

(i) **Logical Operators** 
   -> Logical operators are the operators which operates on two or more boolean expressions to return single boolean value. Python supports following logical                 operators:
   
   **and** : Conditional and, connects two expressions and returns True when both the expression returns True otherwise it returns False.
   
   **or**  : Conditional or, connects two expressions and returns True when one of the expression returns True otherwise it returns False.
   
   **not** : Unary negation, It return True when the expression return False and returns False when expression returns True.
   
(ii)  **Equality Operators**
    -> Equality operators are the operators which compares two operands for their equality or inequality and return True or False if they are equal or not.
