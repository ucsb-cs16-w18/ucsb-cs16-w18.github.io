---
num: "lect04"
desc: "More loops, working with floats and doubles"
ready: true
pdfurl: /lectures/CS16_Lecture4.pdf
annotatedpdfurl: /lectures/CS16_Lecture4_ann.pdf
annotatedready: true
lecture_date: 2018-01-25
---

# Code from lecture

# Topics

## Working with doubles
* Evaluating expressions with mixed numeric types
* Typecasting int to double 
* Formatted output with doubles: cout.setf()

## Practice with single for loops
* Summing a series: 

**In class practice: Write a program that takes a parameter n as a command line arguments and computes the following:**

```
1 + 1/2 + 1/3 + ....+ 1/n
```
where n is the number of terms in the series.

Sample run of the program is below:

```
$./sumSeries 2
Sum of the first 2 terms is: 1.500
```


## Nested Loops
* Nested loops
* ASCII Art with nested loops

**In class practice: Write a program to draw a square of a given width**
Example usage:

```
$./drawSquare 
Enter the width of the square: 5
* * * * *
* * * * *
* * * * *
* * * * *
* * * * *
```

Complete the code below

```
#include <iostream>
using namespace std;

void drawSquare(int n); // Function to draw a square of side n

int main(){
  // Complete the code below:
  
  
  cout<<"Enter the width of the square : "
  cin>> num;
  
  
}

// Write the definition of a function drawSquare that takes one parameter
void drawSquare(int n){













}
```



































