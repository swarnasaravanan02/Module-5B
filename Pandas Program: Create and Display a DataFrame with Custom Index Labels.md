# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
import numpy as np

import pandas as pd

exam_data=eval(input())

lab=np.array(eval(input()))

df=pd.DataFrame(exam_data,index=lab)

print(df)
## Output
<img width="1261" height="321" alt="image" src="https://github.com/user-attachments/assets/832b9de9-9867-4777-bea2-73b5191e31cb" />

## Result
Thus, the program to create and display a Pandas DataFrame with custom index labels was executed successfully.
