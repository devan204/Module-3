# Exp.No:3d  
## TUPLES - PROGRAM TO CREATE A TUPLE OF MULTIPLES OF 3 AND PRINT THEIR SUM

---

### AIM  
To write a Python program that takes an integer N as input, creates a tuple containing all multiples of 3 up to N (excluding N), and prints the tuple along with the sum of its elements.


### ALGORITHM

Start

Take an integer input N from the user

Create an empty list l

Use a for loop to iterate from 1 to N-1

For each number, check if it is a multiple of 3 (i.e., i % 3 == 0)

If true, append it to the list l

Convert the list l to a tuple result

Calculate the sum of the tuple elements using the sum() function and store it in variable s

Print the tuple and the sum

End

---

### PROGRAM

```
x=int(input())
l=[]
for i in range(1,x):
    if i%3==0:
        l.append(i)
        
result=tuple(l)
s=sum(result)

print(result)
print("Sum is", s)
```

### OUTPUT
![Screenshot (236)](https://github.com/user-attachments/assets/db0689e0-8bf3-4f45-a83c-a29f4c6df43d)

### RESULT
Thus the python program was initiated and executed successfully 
