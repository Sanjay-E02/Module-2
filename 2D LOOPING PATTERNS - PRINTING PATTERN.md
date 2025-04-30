# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
To write a Python program to print reversed pyramid pattern in Python.

---

### ALGORITHM

1.Start

2.Input the number of rows n (height of the pyramid)

3.Loop from i = 0 to n - 1:

4.Print i spaces → " " * i

5.Print 2*(n - i) - 1 stars → "*" * (2 * (n - i) - 1)

6.Go to the next line after each row

7.Endach row using `print("")` to move to the next line.  

---

### PROGRAM
```
n=int(input())
s=(2n)-2
for i in range(n,-1,-1):
for j in range (s,0,-1):
print(end=" ")
s=s+1
for j in range(i+1):
print("",end=" ")
print()

```

### OUTPUT
![image](https://github.com/user-attachments/assets/d723a22f-1b86-4213-8f9d-eab576a63719)

### RESULT
Thus,the given python program is implemented and executed sucessfully.
