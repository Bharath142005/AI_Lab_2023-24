# Ex.No: 5   Logic Programming – Factorial of number   
### DATE: 09/09/2025                                                                           
### REGISTER NUMBER : 212222060024
### AIM: 
To  write  a logic program for finding the factorial of given number using SWI-PROLOG. 
### Algorithm:
1. STEP 1: Start the program
2. STEP 2:  Write a rules for finding factorial of given program in SWI-PROLOG.
3.   a)	factorial of 0 is 1 => written as factorial(0,1).
4.   b)	factorial of number greater than 0 obtained by recursively calling the factorial    function.
5. STEP 3: Run the program  to find answer of  query.
6. STEP 4: Stop the program.

### Program:
```
factorial(0,1).
factorial(A,B) :-  
           A > 0, 
           C is A-1,
           factorial(C,D),
           B is A*D.
```
### Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5476512e-2895-4609-9ad4-ec86bd52e3fb" />
### Result:
Thus the factorial of given number was found by logic programming. 
