# 📝 Worksheet: 04 - Loops and Iteration

Practice and reflect on how loops work in Python.

---

## 🔁 Section 1: For Loops

1. What does `range(5)` produce?

`Answer:` 0,1,2,3,4

2. Write a `for` loop that prints numbers 1 to 10, but skips 5.

```python
for i in range(1,11):
  if i == 5:
    continue
  elif:
    print(i)
```

---

## 🔁 Section 2: While Loops

3. What’s the difference between a `for` loop and a `while` loop?

`Answer:` For loop continues for a certain number of iterations an while loop goes until a condition is met

4. What happens if a `while` loop's condition never becomes `False`?

`Answer:` Infinite loop

---

### ✏️ Task: Countdown with While

```python
num = 5
while num != 0:
  print(num)
  num -= 1

```

---

## 📁 Section 3: File Reading and `with`

5. What does the `with` statement do when opening a file?

`Answer:` handles setup and clean up

6. How do you loop over each line in a file?

`Answer:` for loop

---

### ✏️ Task: File Filter

Write code that prints only the lines in a file that contain the word `"error"`.

```python
with open('file.txt') as f:
  for line in f:
    if "error" in line:
      print(line)
```
