# CMP 262 – Week 4, Lab 1
## Lists, Tuples, and Dictionaries

### What You Are Doing

In this lab, you will practice three Python data structures:

- Lists
- Tuples
- Dictionaries

You will complete your work in:

- `ListsTuplesDictionaries.ipynb`
- `AI-Use-Report.md`

### How to Complete the Lab

1. Open `ListsTuplesDictionaries.ipynb` in Visual Studio Code.
2. Start at the top of the notebook.
3. Read each task carefully.
4. Write your own Python code in the code cell under the task.
5. Run the cell and check your output.
6. Fix any errors before moving to the next task.

The README explains the concepts, but it does **not** give the code needed to complete the assignment.

---

## Part 1 – Lists

A **list** stores multiple values in order.

Important ideas:

- List positions are called **indexes**.
- The first item is at index `0`.
- Lists can be changed.
- You can add new items to a list.
- Python functions such as `len()`, `min()`, `max()`, and `sum()` can be used with numeric lists.

You will work with a list of exam scores.

You will be asked to:

- access specific values
- find the number of values
- find the highest and lowest scores
- calculate an average
- change a value
- add a value
- use a loop and an `if` statement

### Helpful Reminder

To access an item in a list, use its index:

`list_name[index]`

To add an item, think about the list method used in class to add something to the end.

---

## Part 2 – Tuples

A **tuple** stores multiple values in order, similar to a list.

The important difference is that a tuple is **immutable**, which means its values cannot be changed directly after the tuple is created.

You will be asked to:

- create a tuple
- access a tuple value
- unpack tuple values into variables
- explain why tuples cannot be directly changed

### Helpful Reminder

Tuple items also use indexes.

Tuple unpacking means taking the values from a tuple and placing them into separate variables.

---

## Part 3 – Dictionaries

A **dictionary** stores information using **key-value pairs**.

For example, a dictionary might store information such as:

- a product name
- its price
- its quantity

The labels are called **keys**, and the information connected to those labels are the **values**.

You will be asked to:

- create a dictionary
- access a value using a key
- change an existing value
- add a new key-value pair
- loop through keys and values

### Helpful Reminder

A dictionary uses a **key** instead of a numeric index to find a value.

Think about the syntax practiced in class:

`dictionary_name[key]`

When looping through both keys and values, remember the dictionary method discussed in class that returns both.

---

## Part 4 – Final Challenge

The final challenge combines **dictionaries and lists**.

Each course name is stored as a dictionary key, and each value is a list of scores.

You will need to:

1. Access one course's list of scores.
2. Calculate an average using that list.
3. Loop through the dictionary and display each course with its scores.

This section is meant to make you combine ideas from earlier parts of the lab. The README does not provide the finished code.

---

## Before You Submit

Make sure:

- every task is completed
- every code cell has been run
- there are no errors
- the reflection is complete
- `AI-Use-Report.md` is complete

Then commit and push your work:

```
git status
git add .
git commit -m "Complete Week 4 Lab 1"
git push
```

Open your GitHub repository and confirm that your latest work appears there.

### Important

Do not delete the questions or instructor comments.

GitHub Copilot may help explain a concept, syntax, or error, but you are responsible for writing and understanding your own code.
