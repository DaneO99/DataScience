# 📝 Worksheet: 02 - Working with Data

Use this worksheet to review and reinforce your understanding of Python data containers.

---

## 🧠 Section 1: Lists

1. What method adds an item to the end of a list?  
   `Answer:` list.append(value)

2. How can you remove an item from a list by value?  
   `Answer:` list.remove(value

3. What’s the result of this code?

```python
nums = [2, 4, 6]
nums.append(8)
print(nums)
```

   `Answer:` 2,4,6,8

---

### ✏️ Task: List Practice

```python
# Create a list of your top 3 favorite foods.
# Add another food to the list.
# Remove one item and print the list.
```
```python
food = ['pizza','pasta','steak']
food.append('burgers')
food.remove('pasta')
```
---

## 🔒 Section 2: Tuples

4. What is a key difference between a list and a tuple?  
   `Answer:` lists can be changed after creating tuples can't be

5. Can you change the contents of a tuple once it is created? Why or why not?  
   `Answer:` no lists are immutable

---

### ✏️ Task: Tuple Practice

```python
# Create a tuple with your favorite 3 numbers.
# Unpack it into three variables and print each.
```
```python
numbers = ( 6 , 88 , 3)
for num in numbers:
   print(num)
```
---

## 🔑 Section 3: Dictionaries

6. What does the `.get()` method do differently from accessing a key directly?  
   `Answer:` ____________________________

7. How do you loop through both keys and values in a dictionary?  
   `Answer:` for key , value in dictionary.items():

---

### ✏️ Task: Dictionary Practice

```python
# Create a dictionary with keys: 'name', 'age', and 'hobby'.
# Print each key and value in the format "key: value".
```
```python
about_me = {'Name: ' , 'Dane Fitzgerald' , 'Age: ' : 26 , 'Hobby: ' : 'Golf'}
for key , value in about_me.items():
   print(key, value)
```
---

## 🧾 Submit Checklist

- [Y] I practiced creating and modifying lists.
- [Y] I understand how tuples are different from lists.
- [Y] I accessed and looped through dictionary items.
