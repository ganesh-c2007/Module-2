# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

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
```
import math
n=int(input())
for i in range(n):
    for s in range(n-i-1):
        print(" ",end="")
    for j in range(i+1):
        print(f"{math.comb(i,j)} ",end="")            
    print()
```

## Sample Output
<img width="664" height="748" alt="528591025-0fc037c1-3927-4bdf-9e10-d8320f6a752b" src="https://github.com/user-attachments/assets/061c313c-523a-4971-a4e5-c12402e002d2" />

## Result
Thus To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is executed successfully.
