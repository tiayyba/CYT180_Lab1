# CYT180 – Lab 1: Python Basics (Applied Coding)

**Weight:** 3% <br>
**Work Type:** Individual <br>
**Submission Format:** Single PDF file containing screenshots from the Jupyter Notebook <br>

---

## Lab Objectives

This lab introduces you to the fundamentals of Python programming through hands-on coding. You will modify provided code and write your own Python programs to demonstrate understanding.

By the end of this lab, you should be able to:
- Run Python code in a Jupyter Notebook (Google Colab or local)
- Modify existing Python code
- Write simple Python programs from scratch
- Explain Python concepts in your own words
---
## Topics Covered

This lab will cover the following Python topics:
1. Introduction and Variables
2. Strings and Loops
3. Tuples
4. Lists (Arrays)
5. Built-in Functions
6. Indexes and Slices
7. Functions
8. Function Parameters and Typing

## Tools and Environment

You may complete this lab using **one** of the following options:

* **Google Colab** – no installation required. For guidance, refer to the enclosed document *“How to start with Google Colab”*.
* **Local Installation** – Python 3 with Jupyter Notebook. I recommend installing the **Anaconda Distribution**, which includes Python and additional tools required for this course.  
  - Installation guide (Windows): https://docs.anaconda.com/anaconda/install/windows/  
  - If you are not comfortable with installing software locally, you may use Google Colab instead.

---

## Reference Material

The following materials can help you complete this lab. These are **optional** and meant for guidance only:

1. Instructor demonstration of the concepts
2. Python official documentation: https://docs.python.org/3/tutorial/index.html
3. Additional Python tutorial: https://pythonprogramming.net/introduction-learn-python-3-tutorials/
<br>This site contains **step-by-step tutorials and videos** covering:
     - Introduction to Python
     - Tuples, Strings, and Loops
     - Lists (Arrays)
     - Built-in Functions
     - Indexes and Slices
     - Functions
     - Function Parameters and Typing  

## Starter Instructions

Create a Jupyter Notebook named `YourSenecaUSername_lab1.ipynb`. Complete **all tasks below in order**. Make sure your notebook includes:
* Code cells. Each task should be completed in its **own cell**.
* Output
* Brief comments (using Markdown cells) where requested

---
## Submission Instructions

All lab work must be submitted as a **single PDF file** on Blackboard containing screenshots of your notebook. You should create a **Word document**, add all screenshots in order, and then convert it to PDF.<br>
Follow these steps carefully:
1. At the top of each task cell, include your **name and student ID as a comment**.  
     Example:
     ```python
     # Name: Your Name
     # Student ID: 123456789
     ```
4. **Demonstrate work was done on your own machine**:
   - Open a **Windows Terminal** (or command prompt).  
   - Print your **system username**, **current date**, and **current time**. You will capture this output along with code.
4. Capture screenshots of all tasks in the notebook:
   - Each screenshot must show code and its output in the cell along with your system username, and current datetime from terminal. You can keep the terminal on the right side of notebook and then capture the screenshot.
   - Place each screenshot under its corresponding task heading (Task 1, Task 2, … Task 8).
5. Compile the word document as a PDF:
6. Check before submission:
   - All notebook screenshots clearly show your name and student ID along with system username, current date and time from the windows terminal.
   - All 8 tasks are included and clearly labeled.
   - Code runs correctly and outputs are visible.
---


## Task 1: Introduction & Variables

* Copy the following **starter code** in your notebook.
```python
name = "Student"
student_id = "000000"
print(name)
print(student_id)
```
* Replace the placeholder values with your **real name** and **student ID**.
* Add a new variable called `program` and assign it a logical value.
* Print all values using **one print statement**.
* Take a screenshot showing your code and its output, and include it in the PDF under the heading **Task 1**.

---

## Task 2: Strings and Loops
In a new cell in the notebook write code that:
* Stores a sentence in a string variable.
* Uses a `for` loop to print each character on a new line.
* Add a Markdown cell explaining **where loops are useful**.
* Take a screenshot of the code and output and include it in the PDF under Task 2.

---

## Task 3: Tuples

* In a new cell in the notebook, create a tuple called `device_info` that stores:
     * Device type (e.g., "Laptop")
     * Operating system (e.g., "Windows")
     * Year purchased
* Print each value using indexing.
* Attempt to modify one value and **observe what happens**.
* Add a short comment explaining why this happens.
* Take a screenshot and include it in the PDF under Task 3.

---

## Task 4: Lists (Arrays)

* Copy the following **starter code** in a new cell in your notebook.
```python
courses = ["CYT180", "CYS101", "DBS211"]
```
* Add one more course to the list using the `append` mthod.
* Use a for loop to print each course in the format:
  ```
  I am enrolled in CYT180
  I am enrolled in CYS101
  I am enrolled in DBS211
  I am enrolled in NET101
  ```
* Print the total number of courses.
* Take a screenshot and include it in the PDF under Task 4

---

## Task 5: Built-in Functions

Using your `courses` list from previous task:

* Use at least **three built-in functions** (e.g., `len()`, `sorted()`, `type()`)
* Print the result of each function
* Add a Markdown cell explaining **why built-in functions are useful**.
* Take a screenshot and include it in the PDF under Task 5.

---

## Task 6: Indexes and Slices

Using the `courses` list:

* Print the first course.
* Print the last course.
* Print a slice containing the first two courses.
* Explain the difference between **indexing** and **slicing**.
* Take a screenshot and include it in the PDF under Task 6.

---

## Task 7: Functions

Write a function named `greet_student` that:

* Accepts a name as a parameter.
* Prints a greeting message.
* Call the function **at least twice** with different names.
* Take a screenshot and include it in the PDF under Task 7.

---

## Task 8: Function Parameters and Typing

Write a function that:

* Accepts two numbers.
* Returns their average.
* Call the function with integers.
* Call the function with decimal values.
* Add a Markdown cell explaining **what you learned about function parameters and data types**.
* Take a screenshot and include it in the PDF under Task 8.

---

## Final Reflection

At the bottom of the word document, answer the following questions:
1. Which task helped you understand Python the most?
2. Which task was the most challenging and why?
3. What is one Python concept you feel confident about after completing this lab?

Each answer should be **2–4 sentences**, written in your own words.

---

## Important Notes
- Late submissions receive -20% per day.
- Submissions which do not follow the given guidelines will be graded as zero!
- Academic integrity policies apply.
---

