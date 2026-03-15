---
title: 📌 Palindrome
parent: • programs
grand_parent: 2. Python
grand_grand_parent: "3. Technical-Skills"
nav_order: 2
has_children: true
---


Hi I am Dipika this is my First program 

--- 
# Hi I am Dipika this is my First program 

--- 
## Hi I am Dipika this is my First program 

--- 
### Hi I am Dipika this is my First program 

--- 
# **Hi I am Dipika this is my First program**

--- 
## **Hi I am Dipika this is my First program**

--- 
### **Hi I am Dipika this is my First program**




---

# 2️⃣ `palindrome.py` (Palindrome Program)

A **palindrome** is a word or number that reads the same **forward and backward**.

Example:

* 121
* 1331
* madam

```python
# palindrome.py

num = int(input("Enter a number: "))

temp = num
reverse = 0

while num > 0:
    digit = num % 10
    reverse = reverse * 10 + digit
    num = num // 10

if temp == reverse:
    print(temp, "is a palindrome number")
else:
    print(temp, "is not a palindrome number")
```

### Example Output

```
Enter a number: 121
121 is a palindrome number
```


