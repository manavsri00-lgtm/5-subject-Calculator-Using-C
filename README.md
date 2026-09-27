# Student Percentage Calculator

A simple C program that calculates the total marks and percentage of a student based on marks obtained in five subjects.

## Features
- Takes marks of 5 subjects as input
- Calculates total marks
- Calculates percentage
- Displays the final result

## Concepts Used
- Variables
- Input/Output Functions
- Arithmetic Operators
- Basic Programming Logic

## Sample Output
Enter marks of 5 subjects:
80
75
90
85
70

Total Marks = 400
Percentage = 80.00%
                
        CODE
            
#include <stdio.h>

int main(){
    float m1 = 97; //maths
    float m2 = 98; //phy
    float m3 = 65; //chem
    float m4 = 65; //cs
    float m5 = 98; //eng
    float p = (m1 + m2 + m3 + m4 + m5)/5;
    printf("Percentage of 5 subj is : %f",p);
    return 0;
}
