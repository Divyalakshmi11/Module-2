# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
~~~
a=16
b=bin(a)
print("Binary representation of",a, "is",b)
~~~

## Output
<img width="1726" height="988" alt="Screenshot 2025-10-20 131215" src="https://github.com/user-attachments/assets/f7e3597f-9469-499b-94c6-057ff0de4416" />

## Result
The program successfully converts the number 16 into its binary representation using the built-in bin() function.



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

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
~~~
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

f = lambda a, b: a + b
print("The sum is:", f(a, b))
~~~

## Output
<img width="1600" height="987" alt="Screenshot 2025-10-20 132314" src="https://github.com/user-attachments/assets/8e41c429-eb10-4c89-aedc-a48b41f6df62" />

## Result
The program successfully defines and executes a lambda function that adds two numbers and displays the result.

## Output
<img width="1554" height="993" alt="Screenshot 2025-10-20 131953" src="https://github.com/user-attachments/assets/6ed7d7d7-5fb0-42c6-a80e-85bd24d25a59" />

## Result
The program successfully defines a function to calculate and display the modulo of two numbers using the % operator.
