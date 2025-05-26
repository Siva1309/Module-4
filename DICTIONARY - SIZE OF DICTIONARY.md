# Exp.No:16  
## DICTIONARY - SORTING THE KEYS AND VALUES IN ALPHABETICAL ORDER BY DICTIONARY VALUE

---

### AIM  
To write a Python program that sorts the keys and values of a dictionary in ascending alphabetical order based on the dictionary values.

---

### ALGORITHM

Start the program.

Define a dictionary d with key-value pairs.

Use the sorted() function along with a lambda function as the key argument to sort the dictionary items based on the values.

Store the sorted list of tuples in a variable s.

Print the message indicating that the keys and values are sorted by value.

Print the sorted list s.

End the program.

---

### PROGRAM

```
d = {1: 2, 2: 56, 3: 323, 4: 24, 5: 12, 6: 18}

s = sorted(d.items(), key=lambda x: x[1])

print("Keys and Values sorted in alphabetical order by the value")
print(s)

```

### OUTPUT
![Screenshot (239)](https://github.com/user-attachments/assets/21805db4-99c7-4c8c-b502-740b6b8f61f2)


### RESULT
Thus the python program was initiated and executed successfully.
