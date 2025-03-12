# Age Calculator 🎂  

This repository contains a simple script that calculates your age based on your birth year.  

## Code in This Repo  
```python
from datetime import datetime  

birth_year = int(input("Enter your birth year: "))  
current_year = datetime.now().year  
age = current_year - birth_year  

print(f"You are {age} years old! 🎉")
