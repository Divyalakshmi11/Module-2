# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
~~~
def result(a, b):
    print("The modulo of", a, "and", b, "is:", a % b)
x = int(input("Enter the first number: "))
y = int(input("Enter the second number: "))
result(x, y)
~~~

## Output
<img width="1554" height="993" alt="Screenshot 2025-10-20 131953" src="https://github.com/user-attachments/assets/6ed7d7d7-5fb0-42c6-a80e-85bd24d25a59" />

## Result
The program successfully defines a function to calculate and display the modulo of two numbers using the % operator.
