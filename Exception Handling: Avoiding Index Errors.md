# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
Developed by: Abishek P
Register Number: 212224240002
n=int(input())
a=[]
for i in range(n):
    l=int(input())
    a.append(l)

print(a)
try:
    print(a[6])
except Indexerror:
    print("6 is not accepted")
```
## Output
![442446322-219d34ae-929b-41c4-bb6b-334322aebc01](https://github.com/user-attachments/assets/0a828ac8-fdf8-4d9e-94fb-49b1ed76591a)

## Result
The program successfully handles the IndexError when trying to access an element beyond the list’s range and displays a custom error message.
