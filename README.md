# 1st-year-C




NAME: Mohamad Saad Ansar Bijapuri
PRN: 22070123070
Professor: Mr.Amit Kukker 

Title:1st year Mini Project

Aim: To learn Object oriented programming in C++

Theory:The structure in C is a user-defined data type that can be used to group items of possibly different types into a single type. 
The struct keyword is used to define the structure in the C programming language. The items in the structure are called its member and they can be of any valid data type.
C Structure Declaration
We have to declare structure in C before using it in our program. In structure declaration, we specify its member variables along with their datatype. We can use the struct keyword to declare the structure in C using the following syntax:

Syntax
struct structure_name {
    data_type member_name1;
    data_type member_name1;
    ....
    ....
};

The above syntax is also called a structure template or structure prototype and no memory is allocated to the structure in the declaration.

C Structure Definition
To use structure in our program, we have to define its instance. We can do that by creating variables of the structure type. We can define structure variables using two methods:

1. Structure Variable Declaration with Structure Template
struct structure_name {
    data_type member_name1;
    data_type member_name1;
    ....
    ....
}variable1, varaible2, ...;
2. Structure Variable Declaration after Structure Template
// structure declared beforehand
struct structure_name variable1, variable2, .......;

![image](https://github.com/M-S-A-B/1st-year-C/assets/140503259/8e43bde5-f1ed-4fe5-8a1f-be4e77fba06f)



Access Structure Members
We can access structure members by using the ( . ) dot operator.

Syntax
structure_name.member1;
strcuture_name.member2;
In the case where we have a pointer to the structure, we can also use the arrow operator to access the members.
Algorithm:

Start =>  declare structure and its members => define its instance => put inputs of the employee => then print the employees details => take information of work done by employee => based on that give the employee increment or decrement in annual salry and promotion and demotion as well =>  End


Explanation of the algorithm:
In this code we declare structure and its members. Then define its instance. Take inputs of the employee. Then print the employees details. Then take information of work done by employee. Based on the work done give the employee an increment or decrement in annual salry and promotion or demotion as well.


![image](https://github.com/M-S-A-B/1st-year-C/assets/140503259/b04d2e9c-dcfe-4024-a10d-9935cd8f3c58)

