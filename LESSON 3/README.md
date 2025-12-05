# 🎯 LESSON 3 — FUNCTIONS in Python (Java → Python)

## 🟦 1. Basic function
```python
def greet(name):
    print(f"Hello, {name}")
```    

## 🟩 2. Returning values
```python
def add(a, b):
    return a + b
```    

## 🟧 3. Default parameter
```python
def greet(name="Bob"):
    print("Hello", name)
```

## 🟥 4. *args — unlimited positional arguments
```python
def sum_all(*numbers):
    return sum(numbers)

print(sum_all(1,2,3,4))   # 10
```

Equivalent Java idea:
varargs

## 🟪 5. **kwargs — unlimited named arguments
```python
def show_info(**data):
    print(data)

show_info(name="Bob", age=20)
```

## 🟫 6. Lambda (anonymous functions)
```python
square = lambda x: x * x
print(square(5))
```

Mostly used in sorting, filtering, small callbacks.

## 🟨 7. Nested function + closure
```python
def outer(x):
    def inner(y):
        return x + y   # inner captures x
    return inner

add5 = outer(5)
print(add5(10))   # 15
```

This is how decorators work in Python.