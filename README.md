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

**Python** is one of the most popular programming languages in the world. It is used for so many things such as making backends for websites, artificial intelligence, data science, and much more. We need lots and lots of data sets to work in these fields, for example, on websites there are lots of data of may be products or users which we need to store in such a way that they can be accessed efficiently. Then in artificial intelligence, we need data in millions. So to manage this amount of data, we structure them so they can be accessed efficiently. This structure of data is called **Data Structures**.

> The format for efficiently storing, organizing, and managing data is called **Data Structures**.

### What are the different types of data structures?

Python provides different kinds of data structures to facilitate problem-solving. These can be classified as linear or non-linear, primitive or non-primitive, and contiguous or non-contiguous.
Let's talk about all of them in detail.

1. **Primitive**: These are the basic set of different data types from which all the other data types are constructed. It is also called simple data type. It cannot be null (empty). This includes integers, strings, floats, and boolean in Python.

2. **Non-Primitive**: These are the type of data structures that can store more than one type of data. It is also called complex data type. It can be null. This includes arrays, lists, tuples, sets, dictionaries, linked lists, stacks, etc.

3. **Contiguous**: As its name suggests that these contain those 
   values that are stored in contiguous memory locations. For example,
   in an array, the elements are stored in an adjacent memory location one after another. In this type of data structure, the data element can be of primitive data type or complex data type. This includes arrays, tuples, sets, objects, strings, lists, maps, and dictionaries.

4. **Non-Contiguous**: In this type of data structure, the data elements are scattered across different memory locations. Here each data item is stored in the form of nodes which keeps a link to one or more other nodes in the collection. This includes linked lists, maps, and graphs.

5. **Linear**: In linear data structures, the elements are accessed in a sequential order irrespective of whether the data items are contiguous or non-contiguous. This includes arrays, linked lists, stacks, queues, and lists.

6. **Non-Linear**: In a nonlinear data structure,  the elements are present in the form of nodes and they are accessed in nonlinear order and they are stored in noncontiguous order. Examples include trees and graphs.

### Built-in Data Structures in Python.
Python provides four built-in data structures that cover almost 80% of the real-world data structures. Let's discuss them in detail.

1.**List**: Lists are the simplest container that comes inbuilt in Python. In other words, lists are the collection of elements within the [ ] brackets and separated by commas. A single list can contain elements of different data types and it can contain multiple elements of the same data type. A list is a mutable type which means the elements can be altered after the creation of the list.


``` 
      l1 = [1, 2, 3, "Hello", 3.4, 2 + 3j, 2, 3]
      print(l1)
      >>> [1, 2, 3, "Hello", 3.4, 2 + 3j, 2, 3]
      print(l1[0])
      >>> 1
      print(l1[2:3])
      >>> [3, "Hello"]
``` 

> **Note**: A list can contain another list, tuples, dictionaries, and sets inside it. 

2.**Tuple**: A tuple is also a collection of elements inside ( ) and they are separated by commas. It shares lots of functionality with the list like it can contain elements of multiple data types, accessing elements by indexing. A tuple is immutable which means we cannot change elements inside it once it has been created.

```
     t1 = (4, 5, 6, 4, 5, "World")
     print(t1)
     >>> (4, 5, 6, 4, 5, "World")
```

3.**Dictionary**: A dictionary is a collection of key-value pairs within { } brackets in python. In a dictionary, every element has its own key which is used to access the element unlike in lists and tuples where we use the index number to access elements. Here key and value are separated by a colon (":") and the key-value pair is separated by commas. Values inside a dictionary can be of any data type or they can be lists or tuples or even dictionaries as well but keys should be immutable and non-repeating. Keys are case sensitive which means the same name but different cases will be treated differently. 

```
     d1 = {"key1":1, "key2":[1,2,3], "key3":(4,5,6), "key4":"Hello"}
     print(d1)
     >>> {"key1":1, "key2":[1,2,3], "key3":(4,5,6), "key4":"Hello"}
     print(d1["key1"])
     >>> 1
```

4.**Set**: A set is an unordered collection data type that is mutable, and iterable but it does not contain multiple elements of the same data type. The main advantage of using a set collection is that it has a highly optimized method to check whether the specific element is present in the set or not. Since a set is unordered hence we cannot access elements by index numbers like in lists. For creating a set we use { } braces 

``` 
     s1 = {1, 2, 3, 4, 5}
     print(s1)
     >>> {1, 2, 3, 4, 5}
```

> Now every data structure will have their own separate file in this same directory with all the explanation and problems related to that.
