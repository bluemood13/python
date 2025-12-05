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


## 6️⃣ List Comprehensions (Python Superpower)

```
Java (manual loop):

List<Integer> nums = new ArrayList<>();
for (int i = 0; i < 5; i++) nums.add(i);
```

```python
nums = [i for i in range(5)]
```

## The Range of Python
🟦 What is range() in Python?

Think of range() like a virtual number generator.

Java version:
```java
for (int i = 0; i < 10; i++) {
    ...
}
```

Python version uses range:

```python
for i in range(0, 10):
    ...
``` 

🟩 Three ways to use range()

1) range(stop)

Starts at 0, stops before stop.

```python
range(5) → 0, 1, 2, 3, 4
```

Equivalent Java loop:
```java
for (int i = 0; i < 5; i++)
```

2) range(start, stop)

Starts at start, ends before stop.

```python
range(2, 7) → 2, 3, 4, 5, 6
```

Java version:
```java
for (int i = 2; i < 7; i++)
```

3) range(start, stop, step)

Adds a step (like i += step in Java).

```python
range(0, 10, 2) → 0, 2, 4, 6, 8
```

Java version:

```java
for (int i = 0; i < 10; i += 2)
```


