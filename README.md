
<img width="1410" height="384" alt="Screenshot 2025-11-22 233446" src="https://github.com/user-attachments/assets/8adccd3e-acd5-4006-b9d0-5c66ab8bdb4f" />


# EX:4 Classes and Objects in Python: Calculate the Area of a Circle

##  Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

##  Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

##  Program
```
import math
class cse:
    def mech(self):
        r=float(input())
        c=math.pi*r**2
        print(f"Area of circle: {c:.2f}")
ci=saveeth()
ci.slot()
```
## Output
![image](https://github.com/user-attachments/assets/cca0c592-7e8f-468b-8558-2cae1e730e21)

## Result
Thus,the Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation is created successfully.

# Dictionary Operations in Python: Merging Two Dictionaries

##  Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

##  Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

##  Program

```
dict1 =eval(input())
dict2 =eval(input())
dict1.update(dict2)
print(dict1)
```

## Output
![image](https://github.com/user-attachments/assets/e595914a-e68a-4fb1-8e40-4ce26cb346c6)

## Result
Thus,the Python program that merges **two dictionaries** and combines their key-value pairs is created successfully.

# Dictionary-Python Program to Sort a Dictionary by Keys and Values

##  Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order


##  Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**


## Program
```
from collections import OrderedDict
d = {'ravi': '10', 'rajnish': '9', 'sanjeev': '15', 'yash': '2', 'suraj': '32'}
sorted_dict = OrderedDict(sorted(d.items()))
print(sorted_dict)
```

## Output
![image](https://github.com/user-attachments/assets/3c44002d-bf46-41ca-a16e-ea9fae0b5b65)

## Result
Thus,the Python program that sorts a dictionary's is created successfully.

# Exception Handling in Python: Avoiding Index Errors

##  Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

##  Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

##  Program
```
lst=[5, 10, 20]

try:
    print(lst[5])
except IndexError:
    msg="You're out of list range"
    print(msg)
```

## Output
![image](https://github.com/user-attachments/assets/f68fcba0-ae4d-4f2a-9c16-b3697dc58e14)

## Result
Thus,the Python program that handles an **IndexError** when trying to access an element beyond the available range of a list is created successfully.


# File Handling in Python: Count Lines Not Starting with 'T'

##  Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

##  Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

##  Program
```
def returnSum(myDict):
    final=0
    for i in myDict.values():
        final+=i
    return final
#driver functions

myDict = {'a': 100, 'b': 200, 'c': 300}
print("Sum :",returnSum(myDict))
```

## Output
![1747908563952889867843913870984](https://github.com/user-attachments/assets/e433700f-35f4-466a-9308-aaa23583592a)


## Result
Thus,the Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'` is created successfully.
