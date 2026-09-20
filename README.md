# CMP 262 – Week 4, Lab 1
## Lists, Tuples, and Dictionaries

### What You Are Doing

In this lab, you will practice three Python data structures:

- Lists
- Tuples
- Dictionaries

You will work inside the `ListsTuplesDictionaries.ipynb` notebook.

Each section includes an example first. Run the example, look at the output, and then complete the task below it.

### Before You Start

1. Open `ListsTuplesDictionaries.ipynb` in Visual Studio Code.
2. Make sure the Python/Jupyter kernel is selected.
3. Start at the top of the notebook.
4. Run each example before completing the task below it.

---

## Part 1 – Lists

A list stores multiple values in order.

Example:

```python
numbers = [10, 20, 30]
print(numbers)
print(numbers[0])
```

The first item is at index `0`.

You will create a list called:

```python
exam_scores = [78, 84, 91, 87, 95]
```

You will practice:

- displaying the first and last score
- finding the number of scores
- finding the highest and lowest score
- calculating the average
- changing one value
- adding a new value
- using a loop to display scores that are 90 or higher

Example of a loop:

```python
values = [5, 12, 7, 15]

for value in values:
    if value >= 10:
        print(value)
```

---

## Part 2 – Tuples

A tuple is similar to a list, but you cannot directly change its values.

Example:

```python
location = (40.7, -74.0)

print(location)
print(location[0])
```

You will create:

```python
student_info = ("Jordan", "CMP262", "Data Science")
```

You will practice:

- displaying tuple values
- accessing a value by index
- unpacking a tuple into variables
- explaining why tuples are immutable

Example of tuple unpacking:

```python
point = (3, 5)

x, y = point

print(x)
print(y)
```

---

## Part 3 – Dictionaries

A dictionary stores information using key-value pairs.

Example:

```python
person = {
    "name": "Alex",
    "age": 20
}

print(person["name"])
```

Here:

- `"name"` is the key
- `"Alex"` is the value

You will create:

```python
student_record = {
    "name": "Jordan",
    "course": "CMP262",
    "grade": 91
}
```

You will practice:

- accessing values using keys
- updating a value
- adding a new key-value pair
- looping through a dictionary

Example of changing and adding values:

```python
car = {
    "make": "Toyota",
    "year": 2025
}

car["year"] = 2026
car["color"] = "blue"

print(car)
```

Example of looping through a dictionary:

```python
for key, value in car.items():
    print(key, value)
```

---

## Part 4 – Final Challenge

You will work with a dictionary that stores lists:

```python
course_scores = {
    "CMP262": [88, 92, 95],
    "CMP129": [84, 90, 87]
}
```

You will:

1. Display the scores for `CMP262`.
2. Calculate the average for `CMP262`.
3. Loop through the dictionary and display each course with its scores.

Example:

```python
data = {
    "A": [1, 2, 3]
}

print(data["A"])
```

---

## What to Submit

Make sure you complete:

- `ListsTuplesDictionaries.ipynb`
- `AI-Use-Report.md`

Before submitting:

1. Run all notebook cells.
2. Make sure there are no errors.
3. Save your work.
4. Commit and push your work to GitHub.

Use:

```
git status
git add .
git commit -m "Complete Week 4 Lab 1"
git push
```

Then open your GitHub repository and make sure your latest work appears there.

### Important

Do not delete the examples, questions, or instructor comments.

GitHub Copilot may help explain a concept or error, but you are responsible for writing and understanding your own code.
