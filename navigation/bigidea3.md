---
layout: post
title: BigIdea 3 Team Teach
description: Big Idea 3 Team Teach - Manas, Arhaan, Ahmad
permalink: /teach/bigidea3
comments: true
---

## Lesson: Lists and Filtering Algorithms

### Learning Objectives
- Clearly understand list structures in Python.
- Implement basic list operations and methods.
- Apply simple filtering algorithms to lists.

---

### Introduction to Lists

A **list** in Python is an ordered collection of items that can include different data types, such as integers, strings, and booleans. Lists are defined using square brackets `[]`.

**Creating and Accessing Lists:**
```python
fruits = ["apple", "banana", "cherry", "date"]
print(fruits[0])  # Output: apple
print(fruits[-1]) # Output: date
```

**Modifying Lists:**
```python
fruits[1] = "blueberry"
print(fruits)  # Output: ["apple", "blueberry", "cherry", "date"]
```

### Popcorn Hack #1 (3 minutes)
Create a list named `pets` containing three types of pets. Write Python code to display the first pet from your list.

---

**Engaging Video:**
Watch this short video on Python lists to reinforce your understanding:
[Python Lists Explained](https://www.youtube.com/watch?v=ohCDWZgNIU0)

---

### Filtering Algorithms
Filtering involves selecting items from a list based on certain conditions.

**Example:** Selecting odd numbers:
```python
numbers = [1, 2, 3, 4, 5, 6]
odd_numbers = [num for num in numbers if num % 2 != 0]
print(odd_numbers)  # Output: [1, 3, 5]
```

### Popcorn Hack #2 (5 minutes)
Given the list `grades = [88, 92, 70, 85, 60]`, write code to display grades higher than 80.

---

**Engaging Video:**
Watch this brief tutorial on filtering lists:
[Filtering Lists in Python](https://www.youtube.com/watch?v=3dt4OGnU5sM)

---

### Efficiency Considerations
Simple filtering algorithms usually check each item once, making their time complexity O(n), with n being the list length.

---

### Homework Hacks

**Homework Hack #1:**
Create a list `temperatures = [65, 70, 75, 80, 85]`. Write code to filter and display temperatures above 72.

**Homework Hack #2:**
Write Python code that:
- Creates a list with numbers from 1 to 20.
- Filters numbers divisible by 4.
- Prints the resulting list.

**Homework Hack #3 (Bonus Challenge):**
Create a function `short_words`:
- Takes a list of words as input.
- Returns words with fewer than 5 letters.
- Demonstrate your function with a sample list.

---

### Review Questions
- How do you define and modify lists in Python?
- Give an example of a scenario where filtering would be useful.
- Describe what the efficiency of filtering means.

---

**Submission:** Submit your solutions and review question responses on the slack MCQ Form by Thrusday 11:59 PM.

