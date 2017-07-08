# Technovation Camp Code Curriculum
## Table of Contents
0. **MIT App Inventor**
    0. Overview and Getting Started
1. **Data**
    0. What is data?
    1. Data Types
        - Integers
        - Floats
        - Strings
        - Booleans
    2. Variables
        - Variable Scoping Local vs. Global 
    4. Lists
    3. Databases
    4. Data Exercises
2. **Code Flow (Operators, Conditional Branching, and Loops)**
    0. Conditional Operators
    1. Truth Outcomes
    2. Conditional Branching
    3. Loops
    4. Code Flow Exercises
3. **Algorithms**
    0. What are Algorithms?
    1. Types of Algorithms
        - Sorting
        - Search
    2. Algorithm Exercises
4. **Databases**
    0. What is a database and why do we need one?
    1. Types of Databases
        - Relational
        - Key/Value
        - Document
    2. Using a database
    3. Database Exercises
5. **UX and Prototyping**
    0. Flow Charts
6. **Using Device Capabilities**
    0. Camera
    2. Accelerometer
    1. GPS

## 0 - MIT App Inventor

## 1 - Data
### 1.0 - What is Data?
Data can be described most simply as information. Anytime you use an application on your computer or phone you are consuming and manipulating data. In fact all computer programs boil down to instructions for interacting with data. 

### 1.1 - Data Types
In programming there are many different types of data. Each type has unique characteristics that destinguish it from other types of data. Every piece of data in a computer program has a type assigned to it that determines how it can be used and what it can be used for.

#### Integers
Integers are any positive or negative whole number.

| Integer Examples |
| ---------------- |
| 23               |
| 56               |
| 4500000000       |
| -4               |

![integers](https://raw.githubusercontent.com/jjozwiak/technovation_camp_2017/master/integers.png "integers")

#### Floats
Floats (A.K.A. Floating Point Numbers) are any positive or negative number with a decimal point.

| Float Examples |
| -------------- |
| 3.141          |
| 1.618          |
| -0.567         |
| 4.1585         |

![floats](https://raw.githubusercontent.com/jjozwiak/technovation_camp_2017/master/floats.png "floats")

#### Strings
Strings are any collection of alphanumeric text.

| String Examples |
| --------------- |
| Johnny Depp     |
| 219-746-1512    |
| 234 Shevchenko St. |

![strings](https://raw.githubusercontent.com/jjozwiak/technovation_camp_2017/master/strings.png "strings")

#### Booleans
The word boolean is just a fancy word for True or False. It comes from Boolean Algebra which gets its name from a Nineteenth Century gentleman named George Boole.

A boolean value can be either TRUE or FALSE but not both as that would be illogical. In many programming languages if the numbers 1 or 0 are of the type boolean then 1 is the equivalent of TRUE and 0 is the equivalent of FALSE (i.e. TRUE, FALSE, true, false, 1, 0, yes, no).

| Boolean Examples |
| ---------------- |
| TRUE     |
| FALSE   |
| 1 |
| 0 |
| YES |
| NO |

![booleans](https://raw.githubusercontent.com/jjozwiak/technovation_camp_2017/master/booleans.png "booleans")

### 1.2 - Variables
Variables in programming allow us to assign a name to a specific value. For example if we say x = 2 this means there is a variable named x that holds the value 2. The value of a variable can change. In fact, that's why we call them variables.

```
x = 0
print x
x = 3
print x
x = 5
x = HELLO WORLD
print x
```

A variable can be assigned any data type.
```
x = TRUE
y = Technovation
z = 4.5
```

![variables](https://raw.githubusercontent.com/jjozwiak/technovation_camp_2017/master/variable_assignment.png "variables")

In the example above, x is a boolean, y is a string, and z is a float.

#### Variable Scoping Local Vs. Global

TBD 

### 1.3 - Lists
A list is a collection of individual pieces of data. Lists alow us to organize data in ways that make it easy for us to work with or operate on.

Let's take a shopping list for example. Each item on this list represents an individual piece of data. 

| Shopping List |
| ------------ |
| Eggs |
| Flour |
| Onions |
| Bananas |
| Bread |

![](https://raw.githubusercontent.com/jjozwiak/technovation_camp_2017/master/simple_list.png)

How many items are in this list?
What datatype is each item?

The most common operations on to perform on a list are replaciing, adding, or removing an item.

![](https://github.com/jjozwiak/technovation_camp_2017/blob/master/remove_item.png?raw=true)
![](https://github.com/jjozwiak/technovation_camp_2017/blob/master/replace_item_in_list.png?raw=true)
*It's important to note that the index for removing, or updating starts at 0 not 1*

The shopping list is an example of a simple list. However, sometimes a simple list is not good enough. What would happen if we had a list of lists? What would this look like?

TBD

This is an example of what computer programmers call "Data Modeling".

Can you think of other places a list of lists would be useful to model data?

### 1.4 - Databases
### 1.6 - Data Exercises
- Guess the correct data type to use
- Place data into the correct data type

## 2 - Code Flow (Operators, Loops and Conditional Branching)
### 2.0 - Conditional Operators

| Symbol | Operator | Description |
| -------| ----------- | -------- |
| == | Equals | Returns TRUE if operands are equal |
| != | Doesn't Equal | Returns TRUE if operands do not equal eachother |
| < | Less Than | Returns TRUE if left operand is less than right operand |
| <= | Less Than OR Equal | |
| > | Greater Than | Returns TRUE if left operand is greater than right operand |
| >= | Greater Than OR Equal | |
| AND | | |
| OR | |  |

![](https://raw.githubusercontent.com/jjozwiak/technovation_camp_2017/master/conditional_operators.png)

### 2.1 Truth Outcomes


### 2.2 Conditional Branching
Conditional statements allow a program to choose different paths based on the truth of a given condtion. Think of a condition as a Yes or No question where Yes is True and No is False. You can put any kind of Yes or No question can be a condition to use in an if statement.

The first and simplest condtional is a single if statement.

```
if (condition) {
    do this
}
OR don't do anything
```
![alt text](https://raw.githubusercontent.com/jjozwiak/technovation_camp_2017/master/simple_if_statement.png.png "Logo Title Text 1")

The second is a if - else statment.

```
if (condition) {
    do this
} else {
    OR at least do this
}
```

![alt](https://raw.githubusercontent.com/jjozwiak/technovation_camp_2017/master/if_statement_2.png "2nd ")

The third is an if - elseif - else statement.

```
if (condition) {
    do this
} else if (another condition) {
    OR do this
} else {
    OR at least do this
}
```

![](https://raw.githubusercontent.com/jjozwiak/technovation_camp_2017/master/if_elseif_else.png)

Conditional statements can be nested.

```
if (condition) {
    do this
} else {
    if (condition) {
       do this
    } else {
        OR at least do this
    }
}
```
![](https://raw.githubusercontent.com/jjozwiak/technovation_camp_2017/master/nested_conditional.png)
### 2.3 Loops

Remember lists? Often we need to 

### 2.4 Code Flow Exercises

- Truth tables

## 3 - Algorithms
### 3.2 - Algorithm Exercises
- https://www.youtube.com/watch?v=INHF_5RIxTE
- https://www.youtube.com/watch?v=8Kp-8OGwphY
- https://www.youtube.com/watch?v=DFG-XuyPYUQ
- https://www.youtube.com/watch?v=aQiWF4E8flQ
- https://www.youtube.com/watch?v=EeQ8pwjQxTM
## 4 - Databases
## 5 - UX and Prototyping
## 6 - Using Device Capabilities
