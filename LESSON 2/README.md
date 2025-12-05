# 🎯 LESSON 2 — Variables, Data Types & Python Collections (Java → Python)

## 🟩 1. Basic Data Types
| Python  | Example          | Java Equivalent |
| ------- | ---------------- | --------------- |
| `int`   | `10`             | int             |
| `float` | `3.14`           | double          |
| `str`   | `"hello"`        | String          |
| `bool`  | `True` / `False` | boolean         |
| `None`  | `None`           | null            |

## 🟧 2. Strings
Python strings are SUPER friendly.
```python
s = "hello"
print(s.upper())
print(s.replace("h","j"))
```

f-strings (Python's best feature)

```python
name = "Bob"
print(f"Hello {name}, welcome")
```

## 🟥 4. Lists (Java: ArrayList but cooler)

Python list = dynamic array + can store mixed types.
```python
nums = [10, 20, 30]
nums.append(40)
nums[1] = 99
```

Slicing (super important)

```python
a = [0,1,2,3,4]
print(a[1:4])   # 1,2,3
print(a[:3])    # 0,1,2
print(a[2:])    # 2,3,4
```