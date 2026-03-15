---
title: 📌 Prime_Number
parent: • programs
grand_parent: 2. Python
grand_grand_parent: "3. Technical-Skills"
nav_order: 1
has_children: true
---


# 1️⃣ `prime_number.py` (Prime Number Program)

A **prime number** is a number that has only **two factors: 1 and itself**.

```python
# prime_number.py

num = int(input("Enter a number: "))

if num > 1:
    for i in range(2, num):
        if num % i == 0:
            print(num, "is not a prime number")
            break
    else:
        print(num, "is a prime number")
else:
    print(num, "is not a prime number")
```

### Example Output

```
Enter a number: 7
7 is a prime number
```

