---
layout: post
title: BigIdea 3 Team Teach
description: Big Idea 3 Team Teach - Manas, Arhaan, Ahmad
permalink: /teach/bigidea3
comments: true
---

## Lesson: Lists and Filtering Algorithms

### Learning Objectives
- Thoroughly understand Python lists, their properties, and how to manipulate them.
- Master various list operations and methods.
- Accurately apply and evaluate filtering algorithms.
- Analyze the performance and efficiency of filtering algorithms.

---

### Introduction to Lists

A **list** in Python is an ordered, mutable collection of elements that can hold multiple data types simultaneously, such as integers, floats, strings, and booleans. Lists are highly versatile and are enclosed within square brackets `[]`.

**Creating Lists:**
```python
# Example list containing multiple data types
example_list = [42, 3.1415, "Python", True]
print(example_list)
```

**Accessing List Elements:**
- Positive indexing (starts from 0).
- Negative indexing (starts from -1, referring to the last element).
```python
colors = ["red", "green", "blue", "yellow"]
print(colors[2])  # Output: blue
print(colors[-1]) # Output: yellow
```

**Modifying Lists:**
You can change, add, or remove elements.
```python
colors[1] = "purple"   # Changing element
colors.append("orange") # Adding element
colors.remove("red")   # Removing element
print(colors)  # Output: ['purple', 'blue', 'yellow', 'orange']
```

### Popcorn Hack #1 (5 minutes)
Create a list named `movies` containing your four favorite movies. Write Python code to replace the second movie with a new movie, add another movie to the list, and display the updated list.

---

**Engaging Video:**
Enhance your understanding of lists with this comprehensive tutorial:
[Complete Python List Tutorial](https://www.youtube.com/watch?v=ohCDWZgNIU0)

---

### Filtering Algorithms
Filtering algorithms selectively extract elements from a list based on defined conditions.

**Basic Example:** Filtering even numbers:
```python
numbers = [11, 14, 18, 23, 29, 32, 40]
even_numbers = [num for num in numbers if num % 2 == 0]
print(even_numbers)  # Output: [14, 18, 32, 40]
```

### Popcorn Hack #2 (8 minutes)
Given the list `ages = [15, 20, 34, 16, 18, 21, 14, 19]`, write Python code to create a new list containing only ages that are eligible for voting (18 or older).

---

**Engaging Video:**
Understand filtering clearly with this short video:
[How to Filter Lists in Python](https://www.youtube.com/watch?v=3dt4OGnU5sM)

---

### Efficiency and Performance of Filtering Algorithms
Filtering typically requires iterating through the entire list once. This linear iteration results in a time complexity of O(n), where n is the number of elements in the list.

**Performance Consideration:**
- Filtering larger datasets will take proportionally more time.
- Understanding efficiency helps optimize performance, particularly for large-scale applications.

---

### Homework Hacks

**Homework Hack #1:**
Watch both the videos and write notes on them
- 3 bullet points per video 
- If you have more than 6 bullet points per video you will be rewarded

**Homework Hack #2:**
Create Python code that:
- Initializes a list containing numbers from 1 to 30.
- Filters out and displays numbers divisible by 3 but not by 5.
- Prints both the original and filtered lists clearly.

**Homework Hack #3 (Bonus Challenge):**
Develop a function named `filter_long_names` that:
- Accepts a list of names and a number representing minimum name length.
- Returns a new list containing only names that meet or exceed the minimum length.
- Test your function with a provided list of your choice.

---

### Review Questions
- Explain what lists are in Python, including how to modify and manipulate them.
- Provide a real-world scenario where a filtering algorithm might be applied.
- Discuss why analyzing the efficiency of filtering algorithms is important for software development.

---

**Submission:** Submit your detailed code implementations and thoughtful answers to the review questions on the MCQ form by 4/10 at 11:59 PM. 

