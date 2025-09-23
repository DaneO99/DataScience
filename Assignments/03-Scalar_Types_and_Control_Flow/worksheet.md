# 📝 Worksheet: 03 - Scalar Types and Control Flow

Use this worksheet to reinforce your understanding of variables, comparisons, and decision logic.

---

## 🧠 Section 1: Scalar Types

1. What is the output of the following code?

```python
x = 10
print(type(x))
```

`Answer:` Int

2. What scalar type would best represent:
   - A person's name: string
   - Their age: int
   - Whether they passed a test: boolean

---

### ✏️ Task: Type Practice

```python
# Create a variable for each type and print its value and type
# Example: an int, float, str, and bool
age = 26
name = dane
cool = True
print(type(age), age)
print(type(name), name)
print(type(cool) , cool)

```

---

## 🔁 Section 2: Comparison Operators

3. What does the `!=` operator mean?

`Answer:` not equal

4. What will the following code print?

```python
a = 5
b = 3
print(a < b or b < 10)
```

`Answer:` True

---

## 🔀 Section 3: Control Flow

5. Write a conditional that prints "Pass" if a grade is >= 70, and "Fail" otherwise.

```python
if grade >= 70:
   print("pass")
else:
   print("fail")

```

6. What does `elif` allow you to do?

`Answer:` check for other conditions outside of if statement

---

### ✏️ Task: Your Turn

Write a program that asks for the weather and prints:
- "Bring sunscreen" if it's sunny
- "Take an umbrella" if it's raining
- "Check the forecast" otherwise
```python
weather = "sunny"
if weather == "sunny"
   print("Bring sunscreen")
elif weather == "raining"
   print("Take an umbrella")
else:
   print("Check the forecast")
```
