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

> "Operators are one of the main concepts in programming"

Now, we have variables and different types of data types and we need to perform some operations with our data or values like calculations or comparisons, etc. So, here comes the operators in the picture. In Python, we have different types of operators and these are:

(i) **Logical Operators**: Logical operators are the operators which compare two expressions and return the value in True or False. Following are the logical operators:

   1) **and**: It compares two expressions and returns True if both the 
      operators return True. For example -: let's take two expressions A 
      and B then 
       
![table-chart (1)](https://user-images.githubusercontent.com/93759322/189498988-9f2acf12-05fd-4a34-a308-a3893f7e59f1.png)

   2) **or**: It compares two expressions and returns True if one of the 
       expressions returns True. For example -: let's take two expressions 
       A and B then 

![table-chart (3)](https://user-images.githubusercontent.com/93759322/189499025-b3ddc663-78cb-4045-a8b0-680a68ba6e25.png)


   3) **not**: It returns True if the expression returns False and returns 
       False if the expression returns True.

(ii) **Equality Operators**: These operators strictly check the equality         
      of two values. The following operators belong to this equality 
      operator: 

   1) **==**: Equivalent Operator, returns True if both the value are 
          equal. For example 
                   
                2 == 2
                returns True

   2) **!=**: Not Equivalent, returns True if both values are not equal.
                
                2 != 3
                returns True

   3) **is**: Same Identity, it is for reference equality. It checks if 
        two variables point toward the same object.

                a = 1
                b = 1
                a is b
                returns True

   4) **is not**:Different Identity, it checks if both variables don't 
        point toward the same object.

                a = 1
                b = "1"
                a is not b
                returns True

(iii) **Comparison Operators**: Comparison operators are the 
      operators which are used to compare two values. Following are the 
      comparison operators available in Python:
   
   1) **<**: Less than, it checks if the left-hand side value is less than 
       that of the right-hand side value, if so it returns True.


                 2 < 3
                 returns True
                 4 < 2
                 returns False 

   2) **>**: Greater than, it checks if the left-hand side value is greater 
       than that of the right-hand side value, if so it returns True.

                 2 > 3
                 returns False
                 4 > 2
                 returns True

   3) **<=**: Less than equal to, it checks if the left-hand side value is 
       less than or equal to that of the right-hand side value, if so it 
       returns True.
       
                    3 <= 3
             return True
             2 <= 4
             return True
             3 <= 2
             return False
4) **>=**: Greater than equal to, it checks if the left-hand side value is greater than or equal to that of the right-hand side value
             
             3 >= 3
             
             return True
             
             2 >= 4
             
             return False
             
             3 >= 2
             return True
(iv) **Arithmetic Operators**: Arithmetic operators are used to 
       perform mathematical operations like calculations. Following are 
       the arithmetic operators present in Python:

   1) **+**: Use for addition

   2) **-**: Use for subtraction

   3) ** * **: Use for multiplication

   4) **/**:Use for division

   5) **//** : Integer division, it returns the integer part of the quotient
        For example:

                13 // 4
                return 3
                11 // 5 
                return 2
   
   6) **%**: Modulo operator: it returns the remainder of the division
        For example:
        
                11 % 4 
                return 3
                15 % 6
                return 3


> There are many other operators in Python like the **Bitwise** operator and **Sequence** operator. 



So now that we are familiar with variables, data-types in  Python and we know how to perform operations on values using different operators. Now let's talk about the real data structures present in Python programming language.
