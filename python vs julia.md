# Julia vs Python Syntax Comparison

## 1. Variables Declaration
#### Julia 
```julia
x = 10
y = 3.14
s = "Hello"
b = true
```
#### Python 
```python
x = 10
y = 3.14
s = "Hello"
b = True
```

## 2. Loops

### For Loop
#### Julia 
```julia
for i in 1:5
    println(i)
end
```
#### Python
```python
for i in range(1, 6):
    print(i)
```

### While Loop
#### Julia
```julia
i = 1
while i <= 5
    println(i)
    i += 1
end
```
#### Python
```python
i = 1
while i <= 5:
    print(i)
    i += 1
```

## 3. Conditional Statements
#### Julia 
```julia

x = 10
if x > 5
    println("Greater")
elif x == 5
    println("Equal")
else
    println("Smaller")
end
```
#### Python
```python

x = 10
if x > 5:
    print("Greater")
elif x == 5:
    print("Equal")
else:
    print("Smaller")
```

## 4. Functions
#### Julia
```julia

def function add(a, b)
    return a + b
end

println(add(3, 5))
```
#### Python
```python

def add(a, b):
    return a + b

print(add(3, 5))
```

## 5. Arrays & Lists
#### Julia
```julia

arr = [1, 2, 3, 4]
println(arr[1])  # First element
```
#### Python
```python

arr = [1, 2, 3, 4]
print(arr[0])  # First element
```

## 6. Tuples
#### Julia
```julia

t = (1, "hello", 3.5)
println(t[1])
```
#### Python
```python

t = (1, "hello", 3.5)
print(t[0])
```

## 7. Dictionaries
#### Julia
```julia

dict = Dict("name" => "Alice", "age" => 25)
println(dict["name"])
```
#### Python
```python

dict = {"name": "Alice", "age": 25}
print(dict["name"])
```

## 8. Exception Handling
#### Julia
```julia

try
    println(10 / 0)
catch e
    println("Error: ", e)
end
```
#### Python
```python
try:
    print(10 / 0)
except Exception as e:
    print("Error:", e)
```

