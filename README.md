# Ex 1:Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```py
a=int(input())
z=bin(a)
print(z)
```

## Output
<img width="157" height="65" alt="image" src="https://github.com/user-attachments/assets/16ede00c-4a2c-455b-a6e2-78ade4149ea9" />

## Result
Thus, the python program was executed successfully.




# Ex 2:Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```py
def result(a,b):
    return a%b
a=int(input())
b=int(input())
print(f"modulo is {result(a,b)}")
```

## Output
<img width="179" height="93" alt="image" src="https://github.com/user-attachments/assets/47359142-8f0d-49ff-a0f0-8142a6819f4a" />

## Result
Thus, the python program was executed successfully.




# Ex 3:Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```py
a=int(input())
b=int(input())
c=int(input())
f=a+b+c
print(f)
```

## Output
<img width="140" height="115" alt="image" src="https://github.com/user-attachments/assets/9600715a-dffd-469f-8038-e103f3d89d65" />

## Result
Thus, the python program was executed successfully.




# Ex 4:🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```py
a=int(input())
for i in range(a):
    for j in range(a-i-1):
        print(end=" ")
    for m in range(i+1):          
             ncr=1
             if(i>0):
                ncr=1
                for k in range(1,m+1):
                     c=(i-k+1)/k
                     ncr=ncr*c
             print(int(ncr), end=" ")
    print("")
```

## Sample Output
<img width="188" height="152" alt="image" src="https://github.com/user-attachments/assets/8aca64a3-7032-4715-90ff-619c4ff12c9f" />

## Result
Thus, the python program was executed successfully.




## Ex 5:Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```py
num=int(input())
rev=0
temp=num

while temp>0:
    rem=temp%10
    rev=rev*10+rem
    temp//=10
    
if rev==num:
        print(f"The given number {num} is a Palindrome")
else:
        print(f"The given number {num} is not a palindrome")
```

## Output
<img width="460" height="56" alt="image" src="https://github.com/user-attachments/assets/38a3141e-bf84-46f8-984f-69f9b6ec9e60" />

<img width="495" height="73" alt="image" src="https://github.com/user-attachments/assets/5f9c3462-9a93-4636-8a4d-68dfd20ecbcc" />

## Result
Thus, the python program was executed successfully.
