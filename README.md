# 19AI304-Fundamentals-of-C-Programming-2025-Odd-M1
# IAPR-1- Module 1 - FoC
## 1. Implementation of basic C programs using Literals,Consonants, Variables, Data types.
## 2. Implementation of different categories of operators.
# Ex.No:1
  Build a C program to demonstrate the usage of different types of literals: integer, float, character, and string.   
# Aim:
1.Declare three character variables to store the input characters.
2.Use the scanf function to read the characters one by one from the user.
3.Print the characters in reverse order using the printf function.
4.End the program.
# Program:
```
#include <stdio.h>

int main() {
    char a, b, c;

    printf("Enter first character: ");
    scanf(" %c", &a);

    printf("Enter second character: ");
    scanf(" %c", &b);

    printf("Enter third character: ");
    scanf(" %c", &c);

    printf("Characters in reverse order: %c %c %c\n", c, b, a);

    return 0;
}

```
# Output:
<img width="1920" height="1139" alt="C-1" src="https://github.com/user-attachments/assets/e1e964ea-f026-4b43-817f-4dc915e24a5b" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:2
  Build a C program to display the value of a macro constant and a constant variable.
# Aim:
  To build a C program that demonstrates the use of macro constants and constant variables.
# Algorithm:
### Step 1:
  Start  
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Define a macro constant `PI` with value `3.14159` using `#define`.
### Step 4: 
   Inside `main()`:
   
   4.1 Declare a constant integer variable `DAYS`
   
   4.2 Initialize it with the value `7`
   
### Step 5:  
  Use `printf()` to display the values of `PI` and `DAYS`.     
### Step 6:  
  Stop
# Program:
```
#include <stdio.h>

int main() {
    int A;

    printf("Enter a number: ");
    scanf("%d", &A);

    if (A > 0)
        printf("%d is a positive number.\n", A);
    else
        printf("%d is not a positive number.\n", A);

    return 0;
}
```
# Output:
<img width="1920" height="1142" alt="C-2" src="https://github.com/user-attachments/assets/cc40b7a8-6267-4b86-af94-782f27a4d1dd" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:3
  Build a C program to demonstrate the use of different data types such as int, float, double, and char, and display their values using printf().
# Aim:
  To build a C program that declares variables of various data types—integer, float, double, and character—initializes them, and prints their values on the screen.
# Algorithm:
1.Declare variables to store the two fraction numbers and the result.
2.Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.Use the scanf function to read the numerator and denominator of the first fraction.
4.Repeat steps 2 and 3 to get the second fraction from the user.
5.Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.Print the minimum value.
# Program:
```
#include <stdio.h>

int main() {
    float a, b, min;

    printf("Enter first number: ");
    scanf("%f", &a);

    printf("Enter second number: ");
    scanf("%f", &b);

    min = (a < b) ? a : b;

    printf("Minimum number is: %.2f\n", min);

    return 0;
}

```
# Output:
<img width="1920" height="1140" alt="C-3" src="https://github.com/user-attachments/assets/13623ed4-8283-48d2-9a9c-dec67d5e18fc" />

# Result: 

# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:4
  Build a C program to perform arithmetic and bitwise operations on two integers entered by the user. The program should display: Arithmetic operations: addition, subtraction, multiplication, division, and remainder. Bitwise operations: AND, OR, XOR, left shift, right shift, and NOT.
# Aim:
  To build a C program that takes two integers as input and demonstrates the arithmetic and bitwise operations, displaying the results of each operation.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Declare two integer variables a and b.
### Step 4: 
   Prompt the user to enter two integers and read the input using scanf().
### Step 5:    
   Perform arithmetic operations on a and b:
   #### Sum (a + b)
   #### Difference (a - b)
   #### Product (a * b)
   #### Quotient (a / b)
   #### Remainder (a % b)
### Step 6: 
  Perform bitwise operations on a and b:
  #### AND (a &amp; b)
  #### OR (a | b)
  #### XOR (a ^ b)
  #### Left shift (a << b)
  #### Right shift (a >> b)
  #### Bitwise NOT of a (~a) and b (~b)
### Step 7:   
  Display the results of all operations using printf().
### Step 8:   
  Stop
# Program:
```
#include <stdio.h>

int main() {
    int num;

    printf("Enter a number: ");
    scanf("%d", &num);

    if (num == 1)
        printf("The number is equal to 1.\n");

    return 0;
}

```

# Output:
<img width="1920" height="1142" alt="C-4" src="https://github.com/user-attachments/assets/8e74f332-c09b-44b9-8d74-dcedbf76b149" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:5
  Develop a C program to check whether a given character is a vowel, consonant, digit, or special symbol using the ternary operator.
# Aim:
  To develop and implement a C program that classifies a character as a vowel, consonant, digit, or special symbol using the ternary operator.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Input a character ch from the user.
### Step 4: 
   Check if ch is a digit ('0' to '9').
   
   If true → Print "Digit" → Go to Step 8.
   
   If false → Go to Step 5.
   
### Step 5:    
   Check if ch is an alphabet letter ('A' - 'Z' or 'a' – 'z').
   
   If true → Go to Step 6.
   
   If false → Go to Step 7.
   
### Step 6: 
   Check if ch is a vowel (a, e, i, o, u or A, E, I, O, U).
   
   If true → Print "Vowel" → Go to Step 8.
   
   If false → Print "Consonant" → Go to Step 8.
   
### Step 7:   
   Print "Special Symbol".
### Step 8:   
  Stop
# Program:
```
#include <stdio.h>

int main() {
    float m1, m2, m3, total, percentage;

    printf("Enter marks of three subjects: ");
    scanf("%f %f %f", &m1, &m2, &m3);


    total = m1 + m2 + m3;
    percentage = (total / 300) * 100; // assuming each subject is out of 100

    printf("\nTotal Marks = %.2f", total);
    printf("\nPercentage = %.2f%%", percentage);


    if (m1 < 35 || m2 < 35 || m3 < 35) {
        printf("\nResult: Fail (Less than 35 marks in one or more subjects)\n");
    }
    else {
        if (percentage >= 60)
            printf("\nResult: First Division\n");
        else if (percentage >= 45)
            printf("\nResult: Second Division\n");
        else if (percentage >= 35)
            printf("\nResult: Pass Division\n");
        else
            printf("\nResult: Fail\n");
    }

    return 0;
}
```
# Output:
<img width="1920" height="1140" alt="C-5" src="https://github.com/user-attachments/assets/46eea038-bbc1-4b44-8b58-e2b910e2df05" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


