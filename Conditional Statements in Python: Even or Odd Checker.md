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
```
a=int(input())
if a%2!=0:
    print(a,'is an Odd number')
    if a>=25:
        print(a,'is greater than or equal to 25')
    else:
        print(a,'is lesser than 25')
else:
    print(a,'is NOT an Odd number')
```
## Output
<img width="1920" height="1080" alt="Screenshot 2025-10-21 111438" src="https://github.com/user-attachments/assets/87b7ece6-6e3f-4dd1-a29d-2732e215120a" />

## Result
successfully created  a Python program to check whether the given number is even or odd using if...else statements.

