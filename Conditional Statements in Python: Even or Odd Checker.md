# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program

a=int(input())

if a%2==0:
    print("EVEN")
    
else:
    print("ODD")

## Output
<img width="828" height="457" alt="image" src="https://github.com/user-attachments/assets/5fcfe898-b9c9-4d98-a368-75b4bcea8ea9" />

## Result
If the input number is divisible by 2 → Even
If not divisible by 2 → Odd
