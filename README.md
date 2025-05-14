# 19CS301-Module4
### Register No - 212222020008
### Name - Harini B

# EX: 4.1 Dictionary
### Aim: Write a Python script to check whether a given key  5,9 already exists in a dictionary. d = {1: 10, 2: 20, 3: 30, 4: 40, 5: 50, 6: 60}
### Algorithm:

**STEP 1:** Start.

**STEP 2:** Create a dictionary `d` with some key-value pairs.

**STEP 3:** Create a list `keys` containing keys to check.

**STEP 4:** Use a `for` loop to iterate through each key `i` in the `keys` list:
- If `i` is present in the dictionary `d`, print `"Key is present in the dictionary"`.
- Otherwise, print `"Key is not present in the dictionary"`.

**STEP 5:** Stop.

### Program:
```
d = {1:10,2:20,3:30,4:40,5:50,6:60}
keys= [5,9]
for i in keys:
    if i in d:
        print("Key is present in the dictionary")
    else:
        print("Key is not present in the dictionary")

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/12625925-47c6-4334-a7dd-166d3b022581)

### Result: Thus, the given program is implemented and executed successfully .
