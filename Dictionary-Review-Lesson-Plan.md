# CMP 262 – Dictionary Review Lesson Plan

## Topic

Python Dictionaries Review

## Goal

Students will understand what a dictionary is, how key-value pairs work, and how to create, access, update, and loop through dictionaries before starting Week 4 Lab 1.

## Suggested Time

30–40 minutes

## 1. Quick Connection to Lists – 5 minutes

Start by reviewing a list:

```python
student = ["Jordan", "CMP262", 91]
```

Ask students:

- What does `student[0]` mean?
- What does `student[2]` mean?
- Is it easy to remember what each position represents?

Explain:

A list uses positions or indexes.

Sometimes it is easier to give each value a meaningful label.

## 2. Introduce Dictionaries – 5 minutes

Show:

```python
student = {
    "name": "Jordan",
    "course": "CMP262",
    "grade": 91
}
```

Explain:

A dictionary stores **key-value pairs**.

- `"name"` is a key.
- `"Jordan"` is the value.
- `"course"` is a key.
- `"CMP262"` is the value.

A key is a label that helps us find a value.

## 3. Accessing Values – 5 minutes

Show:

```python
print(student["name"])
print(student["grade"])
```

Ask students what they expect before running the code.

Important point:

With a list, we normally use an index.

```python
student_list[0]
```

With a dictionary, we normally use a key.

```python
student["name"]
```

## 4. Updating a Value – 5 minutes

Show:

```python
student["grade"] = 94
print(student)
```

Explain that using an existing key changes its value.

Ask:

What value do you expect for `grade` after this line runs?

## 5. Adding a New Key-Value Pair – 5 minutes

Show:

```python
student["credits"] = 3
print(student)
```

Explain:

If the key does not already exist, Python adds a new key-value pair.

## 6. Looping Through a Dictionary – 5 minutes

Show:

```python
for key, value in student.items():
    print(key, value)
```

Explain:

`.items()` gives us both the key and the value.

Ask students to predict the output.

## 7. Dictionary Containing a List – 5 minutes

Show:

```python
course_scores = {
    "CMP262": [88, 92, 95],
    "CMP129": [84, 90, 87]
}
```

Explain:

A dictionary value does not have to be one number or one string.

A value can also be a list.

Show:

```python
print(course_scores["CMP262"])
```

Then:

```python
scores = course_scores["CMP262"]
average = sum(scores) / len(scores)
print(average)
```

Connect this directly to the final part of the lab.

## In-Class Check for Understanding

Ask students to answer without running code first.

### Question 1

What is printed?

```python
book = {
    "title": "Python Basics",
    "pages": 250
}

print(book["title"])
```

Answer: `Python Basics`

### Question 2

What does this line do?

```python
book["pages"] = 300
```

Answer: It changes the value associated with the `pages` key.

### Question 3

What does this line do?

```python
book["author"] = "Smith"
```

Answer: It adds a new key-value pair.

### Question 4

What is the main difference between these?

```python
student_list[0]
student_dict["name"]
```

Answer:

The list accesses a value using an index. The dictionary accesses a value using a key.

## Small Class Practice

Give students this dictionary:

```python
course = {
    "name": "CMP262",
    "credits": 3,
    "students": 22
}
```

Ask them to:

1. Display the course name.
2. Change the number of students to 24.
3. Add a key named `room` with the value `"CH-201"`.
4. Display the complete dictionary.
5. Loop through the dictionary and display each key and value.

## Transition to the Lab

Tell students:

In the lab, you will first review lists and tuples. Then you will use the same dictionary operations we practiced today.

The final activity combines dictionaries and lists, which is important because real datasets often contain multiple related values.
