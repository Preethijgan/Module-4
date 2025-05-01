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
Developed by: Preethi J
Register no: 212223220080
```
```
list1=[5, 10, 20]
try:
print(list1[5]) 
except: 
print("You're out of list range") 


```

## Output
![image](https://github.com/user-attachments/assets/db241a27-01cf-4e7c-be58-194a6e2a28cf)


## Result
Thus, the program has been successfully executed. 
