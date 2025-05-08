## Dictionary Operations in Python: Merging Two Dictionaries
# NAME: Madhupriya R
# REG NO:212224040177

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30} 
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50} def 
merge (dict1,dict2): 
res={**dict1 , **dict2} return 
res 
dict3=merge(dict1,dict2) 
print(dict3)
```

## Output
![439310420-e8333efb-3f5c-488e-bca7-cb30b9252da2](https://github.com/user-attachments/assets/86db1ca5-d53a-4a97-83ff-8a1ab6a7b333)

## Result
Thus, the program has been executed successfully.
