## Experiment No: 1d – Conditional Statements- Checking Divisible by both 9 and 5

## AIM  
To Write a Python program to read a number and check whether the number is divisible by both 9 and 5 or not using  if else statement.
## ALGORITHM  
1. Begin the program.
2. Input a number from the user.
3. Check if the number is divisible by both 9 and 5:
4. If the number is divisible by both 9 and 5 (i.e., number % 9 == 0 and number % 5 == 0)
5. Print "The number is divisible by both 9 and 5".
6. Else, print "The number is not divisible by both 9 and 5".
7.Terminate the program
## PROGRAM
```python
n=int(input())
if n%9==0 and n%5==0:
    print(f"{n} is divisible by both 5 and 9")
else:
    print(f"{n} is NOT divisible by both 5 and 9")
```
## OUTPUT
![image](https://github.com/user-attachments/assets/4afdf159-1c2e-4ad7-9b0f-426f9005d980)

## RESULT
Thus, the prgrom to read a number and check whether the number is divisible by 9 or 5 using if-else statement is implemented and verified successfully.
