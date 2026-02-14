# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:

1.Start the program and import the required libraries.
2.Seed the random number generator using the current time(i.e) rand(time(0));
3.Get the number of randon number to generate.
4.Pass the value for number of iterations and print the numbers.
5.End the program.

# PROGRAM:
```c
#include <stdio.h> 
#include <stdlib.h> 
#include <time.h> 
int main() { 
int i, n; 
srand(time(0)); 
printf("Enter how many pseudorandom numbers you want to generate: "); 
scanf("%d", &n); 
printf("Generating %d pseudorandom numbers between 0 and 99:\n", n); 
for (i = 0; i < n; i++) { 
int randomNumber = rand() % 100; 
printf("%d ", randomNumber); 
} 
printf("\n"); 
return 0; 
}
```
# OUTPUT:

<img width="1004" height="584" alt="image" src="https://github.com/user-attachments/assets/9a54264f-c77e-4966-a4c8-c2d27fe82288" />

# RESULT:
The implementation of pseudorandom number generation is executed successfully.
