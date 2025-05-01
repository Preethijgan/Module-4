## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
Developed by: Preethi J
Register no: 21223220080
```

```
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30}
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50}
def merge (dict1,dict2): 
   res={**dict1 , **dict2}
   return res 
dict3=merge(dict1,dict2)
print(dict3) 

```

## Output
![image](https://github.com/user-attachments/assets/7675a6a9-4db4-46cd-a0cd-4c83c788daac)


## Result
Thus, the program has been successfully executed. 
