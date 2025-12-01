# 📘 LESSON 1 —Python Syntax & Core Philosophy
## 1️⃣ Python Has No { }: Indentation is the structure
Java:
```java
if (x > 10) {
    System.out.println("hi");
}
```

Python:
```Python
if x > 10:
    print("hi")
```
Rules:
- No semicolons
- Colon (:) starts a block
- Indentation = 4 spaces recommended


## 2️⃣ Everything Is Dynamically Typed
```python
a = 10
b = "Bob"
c:int = 5
```

## 3️⃣ Everything is an object.
```python
x = [1,2,3]
y = x
y.append(4)
print(x)   # [1,2,3,4]

```

## 4️⃣ Python Uses `None` Instead of `null` Use `is`, not `==`.


## 5️⃣ Python Has Only One Loop Type
```python
for i in range(5):
    print(i)

for s in ["a","b","c"]:
    print(s)

while True:
    pass

```

## 7️⃣ Functions Are First-Class

```python
def add(x, y):
    return x + y

fn = add
print(fn(1,2))

```