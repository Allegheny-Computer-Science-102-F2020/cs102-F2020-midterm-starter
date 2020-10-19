# Midterm Examination for Computer Science 102 Spring 2020

## Add Your Name Here

## Re-type the sentence "I adhered to the Allegheny College Honor Code while completing this examination."

You must retype the sentence here.

## Dates for the Final Examination

- **Examination Released**: 9:00 AM on Monday, October 19, 2020
- **Examination Due**: 11:59 pm on Wednesday, October 21, 2020

## Honor Code for the Final Examination

- You must adhere to the Honor Code throughout your completion of the examination
- The examination is closed notes, closed book, and closed online resources
- You may use your laptop computer and its text editor and Python programming tools
- You may not refer to the Python source code that you wrote during the semester
- You may not refer to the technical writing that you completed during the semester

**IMPORTANT**: All students in this course are obligated to adhere to the
Allegheny College Honor Code throughout the completion of this examination. If
the instructor detects that a student has committed a likely violation of the
Allegheny College Honor Code, then he will file a report with the Dean of
Students Office. Please make sure that you review the [Honor
Code](https://sites.allegheny.edu/about/honor-code/) before you start to take
this examination. Please note that, due to the ongoing global pandemic, Sections
1 and 2 of Honor Code Article IV are not enforced for this examination.

## Procedures for the Final Examination

- You must provide answers to all these questions by typing in this file
- The final version of this file must be in your GitHub repository by the due date
- You may direct message the course instructor through the Slack workspace if you have questions
- Do not post questions about the examination in a public channel of the Slack workspace
- Unless you make special arrangements with the instructor, no late work will be accepted

## Structure of the Final Examination

- The examination is worth 100 points
- Each question has an assigned point total given in parentheses
- Provide your answer to a question by typing below the subsection header

## (10 Points) Provide a definition of the following terms:

### (2 Points) Assignment statement

### (2 Points) Floating-point number

### (2 Points) String concatenation

### (2 Points) Iteration construct

### (2 Points) Conditional logic construct

## (10 Points) Please define the following terms for integer numbers

### (5 Points) Associative property for integer arithmetic

### (5 Points) Commutative property for integer arithmetic

## (10 Points) What would be the output from running this Python program segment?

```python
def absone(n):
    if n >= 0:
        return n
    else:
        return -n

def abstwo(n):
    if n >= 0:
        return n
    return -n

print(str(absone(10)))
print(str(absone(-10)))

print()

print(str(abstwo(10)))
print(str(abstwo(-10)))
```

Please provide your response to this question in a fenced code block.

## (10 Points) What would be the output from running this Python program segment?

```python
for i in range(20):
    print("Value of i: " + str(i))

print()

for i in range(20):
    print("2 to the " + str(i)
          + " power is " + str(2**i))

print()
```

Please provide your response to this question in a fenced code block.

## (10 Points) Please explain all of the defects in the following Python program segment

```python
file - open("emails")
  for line in file:
    name, email == line.split(",")
    if name = "John Davis":
      print(email)
```

Please provide your response to this question in a paragraph or a list.

## (10 Points) Provide a definition of the following terms:

### (2 Points) Function parameter

### (2 Points) Function return value(s)

### (2 Points) Recursive function

### (2 Points) Higher-order function

### (2 Points) Lambda function (or, lambda expression)

## (10 Points) Provide a definition of the following terms:

### (2 Points) Ordered pair

### (2 Points) n-tuple

### (2 Points) Delimiter

### (2 Points) CSV file

### (2 Points) Relational database

## (10 Points) What would be the output from running this Python program segment?

```python
square_lambda = lambda x: x*x

number = 5
result = call_twice(square_lambda, number)

print("Calling the square lambda twice with " + str(number) + " is " + str(result))
print()
```

Please provide your response to this question in a fenced code block.

## (10 Points) Provide a detailed, multiple paragraph response to the following question:

Pick one laboratory or practical assignment that you worked on this semester
that you struggled to understand and solve and explain how the struggle itself
was valuable. In the context of this question, describe the struggle and how you
overcame it through your own actions. In your response to this question, you
might also discuss whether struggling built aspects of character in you (e.g.
endurance, self-confidence, or competence to solve new problems) and how these
virtues might benefit you in later ventures.

## (10 Points) Provide a detailed, multiple paragraph response to the following question:

Suppose that you have a Python program in a GitHub repository with a failing
build in GitHub Actions. After explaining an example of a way in which the build
might fail for this Python program, please furnish all of the steps that you
would take to understand and fix the build failure. Finally, please explain how,
in addition to looking for the green checkmark in GitHub Actions, you would know
that the Python program was fixed correctly.
